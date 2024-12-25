# Real-Time Device Tracker

This is a real-time device tracking application built using **Node.js**, **Express**, **Socket.IO**, and **Leaflet**. The app allows users to track their device locations on an interactive map in real time, using geolocation features.

## Features

- **Real-time location tracking**: Uses WebSockets (Socket.IO) to track and update device locations live.
- **Interactive map**: Displays user locations on an interactive map using the Leaflet library.
- **Custom markers**: Represents device locations with custom markers for easy identification.
- **Dynamic tooltips**: Shows the device’s unique ID as a tooltip when hovering over markers.
- **Responsive design**: Ensures a smooth and adaptive experience across devices.

## Technologies Used

- **Node.js**: Server-side JavaScript runtime for building the backend.
- **Express**: Simplifies the creation of the web server and routing.
- **Socket.IO**: Provides real-time, bidirectional communication between the client and server.
- **Leaflet**: Open-source library for building interactive maps.
- **HTML/CSS**: For structuring and styling the frontend interface.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

To run the application with automatic reloading, you can use `nodemon`:

1. Install `nodemon` globally:
   ```bash
   npm install -g nodemon

2. In order to run
   npx nodemon app.js
   
