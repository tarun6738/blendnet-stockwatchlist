# Stock Track (Stock Watchlist)

This is a stock monitoring platform where users can log in to monitor stock information. Users will also be able to create and manage their own watchlists.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies](#technologies)
- [API Integration](#api-integration)

## Installation

Before getting started, make sure you have Node.js and npm installed on your machine.

1. **Clone the repository:**
   git clone [https://github.com/tarun6738/watchlist-stock.git](https://github.com/tarun6738/blendnet-stockwatchlist.git)

2. **Install dependencies:**
   Go to backend folder and run npm install
   Go to client folder and run npm install
   These two steps will install the required dependencies.
   
## Usage
  Before you start the deployment server, Create a .env file in backend folder.
  The .env folder should have MONGO_URL=<your_mongoURL>, PORT=5000(anything you wish), JWT_SECRET=<your_jwt_secret>, API_KEY=<AlhpaVantageAPIKEY>
  To start the development server, run:
  npm start (in both frontend & backend folder)
  Visit http://localhost:3000 in your browser to explore frontend.

## Features
  - The dashboard will display the latest stock values of the symbols in the watchlist.
  - The platform will be able to handle multiple users concurrently, each having different watchlists.
  - The platform uses MongoDB for efficient retrieval.
  - That platform has simple & secure authentication & authorization.

## Technologies
   - React
   - Axios
   - React Router
   - React Icons
   - tailwind css, Material UI
   - Node Js
   - Bcrypt JS
     

## API Integration
   Stock Track integrates with The AlphaVantage API for fetching real-time stock data.
