# Async Race SPA

## Overview

Async Race is an interactive single-page application (SPA) designed for managing a collection of remote-controlled cars, operating their engines, and showcasing race statistics.&#x20;

### Features

- **Garage View:**
  - Create, update, and delete cars with customizable names and colors.
  - Choose colors using an RGB palette with live car previews.
  - Paginated view displaying 7 cars per page.
  - Generate 100 random cars simultaneously.
  - Start and stop car engines with real-time animations.
  - Adaptive animations for screens as small as 500px.
- **Race Animation:**
  - Start races for all cars on the current page with a single button.
  - Reset cars to their initial positions.
  - Display the winner's name upon race completion.
- **Winners View:**
  - Show a leaderboard with winning cars, their images, names, number of victories, and fastest race times.
  - Sort winners by victories or fastest times in ascending and descending order.
  - Paginated view for the winners list.

### Deployment

The application is deployed and can be accessed via the link below. Ensure the server is running locally.

[**Live Demo**](https://barvinko.github.io/CarRacerApp/)

## Setup Instructions

1. Clone the repository.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the application:
   ```bash
   npm run start
   ```
4. Download and set up the mock server from the repository link below. Follow the server's README for instructions.

[**Server Repository**](https://github.com/mikhama/async-race-api)

## Notes

- The application requires the mock server to be running for backend communication.
- Download the server from the link above and start it locally.

