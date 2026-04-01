# Async Weather Tracker

This is a simple web application built using JavaScript that fetches real-time weather data for any city. The project also demonstrates how the JavaScript event loop works by showing the execution order of synchronous code, promises (microtasks), and setTimeout (macrotasks).

---

## Features

* Search weather by city name
* Displays temperature, humidity, and wind speed
* Shows how the JavaScript event loop executes tasks
* Maintains a basic search history
* Uses async/await with the Fetch API
* Simple and clean user interface

---

## Technologies Used

* HTML
* CSS
* JavaScript (Async/Await, Fetch API)
* OpenWeatherMap API

---

## How It Works

1. Enter a city name in the input field
2. The app sends a request to the weather API
3. Weather data is displayed on the screen
4. The console section shows the execution order of:

   * Synchronous operations
   * Microtasks (Promise.then)
   * Macrotasks (setTimeout)

---

## Event Loop Demonstration

Example execution order:

```text
1. Sync Start
2. Sync End
3. Start fetching
4. Data received
5. Promise.then (Microtask)
6. setTimeout (Macrotask)
```

---

## Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/your-username/async-weather-tracker.git
```

2. Open the project folder

3. Run the project:

* Use Live Server (recommended), or
* Open index.html directly in your browser

---

## API Key

This project uses the OpenWeatherMap API.

Replace the API key in the code with your own:

```js
let API_KEY = "YOUR_API_KEY";
```

---

## Project Structure

```
index.html
README.md
```

---

## Notes

* The API key is exposed in the frontend and should not be used in production
* This project is intended for learning purposes

---

## Learning Outcomes

* Understanding async/await
* Understanding the JavaScript event loop
* Working with APIs using fetch
* Basic DOM manipulation

---

## Future Improvements

* Store history using localStorage
* Add loading indicator
* Improve responsiveness
* Convert to React

---

## Author

Ayesh Srivastava
