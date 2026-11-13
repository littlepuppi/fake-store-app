# Fake Store App

A React shopping UI titled “Fake Store.” It loads products from the public [Fake Store API](https://fakestoreapi.com/products) and supports a cart and a checkout flow in the browser.

The app is a single `App.js` file with a small in-component router for home, cart, and checkout pages.

## Features

- Product listing with counts and prices from Fake Store API
- Add to cart, update quantities, remove items, and clear the cart
- Cart and order-summary views, plus a checkout page with billing and payment fields
- “Order placed” confirmation state (checkout is handled in the client; there is no backend)

## Tech stack

- React (the source uses `react` / `react-dom` and Create React App-style `index.html` / `index.js`)

## Getting started

This repository does not include a `package.json` or the rest of a Create React App scaffold (`index.js` also imports `reportWebVitals`, which is not in the repo). Opening `index.html` directly will not run the React app.

To run it you would need to place these files in a React project (for example a Create React App or Vite app), install `react` and `react-dom`, and start that project’s dev server. Adding a `package.json` with start scripts would make this repo runnable on its own.
