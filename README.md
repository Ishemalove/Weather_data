# Weather App

This is a simple Weather App that displays weather data, including **temperature** and **humidity**, in graphical format. The app uses **Node.js** and **Express.js** for the backend and **HTML, CSS, and JavaScript** for the frontend. The weather data is stored in an **SQLite database** and served via an API.

## Features

- Displays real-time weather data.
- Visualizes **temperature** and **humidity** trends using graphs.
- Stores weather data in an SQLite database.
- Uses an Express server to handle API requests.

## Installation

Follow these steps to set up and run the Weather App on your local machine:

### 1. Clone the Repository

```sh
 git clone <repository_url>
 cd weather-app
```

### 2. Initialize Node.js Project

Run the following command to create a `package.json` file:

```sh
npm init -y
```

### 3. Install Dependencies

```sh
npm install express sqlite3 body-parser cors
```

### 4. Start the Server

Run the following command to start the server:

```sh
node server.js
```

### 5. Open the App

Once the server is running, open `index.html` in your browser or navigate to `http://localhost:3000` if you are serving the frontend through the backend.

## Project Structure

```
/weather-app
│── index.html        # Frontend UI
│── server.js         # Backend server
│── package.json      # Project metadata & dependencies
│── database.db       # SQLite database (created automatically)
│── public/           # Static files (CSS, JS, images, etc.)
└── node_modules/     # Installed dependencies
```

## How It Works

- The **backend (****`server.js`****)** serves weather data from an SQLite database.
- The **frontend (****`index.html`****)** fetches weather data and displays it using graphs.
- **Graphical representation** is implemented using a charting library like **Chart.js**.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: SQLite
- **Libraries**: Chart.js (for graphs), Body-Parser, CORS

## Future Improvements

- Add real-time weather API integration.
- Enhance UI/UX with more interactive features.
- Implement user authentication for personalized weather tracking.

## License

This project is open-source and available under the **MIT License**.

