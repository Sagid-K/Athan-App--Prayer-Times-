# Muslim Prayer Times Web App

This web app displays live Muslim prayer times for a specific city using the AlAdhan API.

## Features

- Allows users to enter a city name to retrieve live Muslim prayer times.
- Displays Fajr, Dhuhr, Asr, Maghrib, and Isha prayer times for the entered city.
- Provides a user-friendly interface for easy interaction.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have obtained an API key from the AlAdhan API website.
- You have a modern web browser to view the web app.
- You have a code editor to make modifications if needed.

## Getting Started

1. Clone this repository to your local machine.
2. Open the `index.html` file in a web browser.

## Usage

1. Open the web app in your browser.
2. The default city is set to "Euless, TX".
3. Click the "Get Prayer Times" button to retrieve and display the prayer times for the specified city.
4. Prayer times for Fajr, Dhuhr, Asr, Maghrib, and Isha will be displayed.

## Configuration

In the `script.js` file, replace `'YOUR_API_KEY'` with your AlAdhan API key.

```javascript
const apiKey = "YOUR_API_KEY"; // Replace with your AlAdhan API key
