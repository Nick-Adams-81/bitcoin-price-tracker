# bitcoin-price-tracker

This app is a designed to track current bitcoin prices, you can check the prices in USD, GBP, or EUR
ammounts.

# Getting Started
To run the app locally you will need node.js installed, first you will need to
``
npm init
``

then to install next.js,

``
npm install next react react-router
``

finally to start the app locally,

``
npm run dev
``

# Scripts
In your package.json file you will need the following scripts added:
``
"scripts": {
   "dev": "next",
   "build": "next build",
   "start": "next start"
}
``

# Tech used in this app

* Next.js
* Coindesk api
* Bootswatch

# Inspiration

This is my first dive into next.js, it's an awesome framework for React. I find that 
react router dom can be problematic and next.js solves that problem. The next router 
looks a lot like plain html routes, no react router dom to worry about at all, just make the link
the name of the page file you want to navigate to and that's it.

