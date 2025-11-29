
Custom React Hook (useFetch) + API Fetching Project

This project demonstrates how to build a reusable Custom React Hook (useFetch.js) to fetch data from a public API and display it dynamically in a clean, responsive UI.




 Live Demo (Deployed Link)

🔗 https://dainty-capybara-9cc331.netlify.app/



GitHub Repository

🔗 https://github.com/sambhavi15khare/laundrybysam


Features Implemented

Custom Hook useFetch()

 Fetching & displaying data from a public API

 Loading, Error & Success states

 Functional components

 Modular, clean code

 Responsive UI

 Built using Create React App (CRA)

 Fully deployed on Netlify



 Project Structure

assignment5/
    public/
       index.html
       manifest.json
       robots.txt
     src/
       App.js
       App.css
       index.js
       index.css
       useFetch.js
       reportWebVitals.js
     package.json
     package-lock.json
     README.md

 How the Project Works

1. Custom Hook: useFetch.js

This hook handles all API fetching logic.
It:

Accepts any API URL

Fetches data asynchronously

Returns { data, loading, error }

Can be reused across multiple components

Usage example:

const { data, loading, error } = useFetch(url);

2. App.js

Imports the useFetch() hook

Fetches product list from a public API

Displays cards (image, name, price)

Shows “Loading…” while API loads

Shows error message on failure

 How to Run Locally

1. Clone the repo

git clone https://github.com/sambhavi15khare/laundrybysam

2. Install dependencies

npm install

3. Start the server

npm start

Runs on:
👉 http://localhost:3002
