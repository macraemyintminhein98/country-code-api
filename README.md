# Country Code API

A simple, rate-limited JSON API providing ISO 3166-1 alpha-2 country codes and names. Perfect for developers needing quick access to static country data without managing a database.

## Features:
-   Returns a JSON array of country objects (`code` and `name`).
-   Secure access via a unique API key.
-   Easy integration into any web or mobile application.

## Usage:
Make a `GET` request to `https://your-vercel-app-url/api/countries?key=YOUR_API_KEY`.

## Get Your API Key:
Purchase your API key through our secure Stripe checkout. Link will be provided on the landing page (`index.html`).

## Project Structure (Vercel):
-   `api/countries.js`: Serverless function to serve the JSON data.
-   `data/countries.json`: JSON file containing country data.

**Note**: Replace `YOUR_VERCEL_APP_URL` and `YOUR_STRIPE_CHECKOUT_LINK` in `index.html` with your actual deployed Vercel URL and Stripe product link after deployment.