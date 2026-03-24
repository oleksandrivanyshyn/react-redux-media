# React Redux Media

A media management dashboard built as a practical implementation for learning and mastering modern Redux state management. This project demonstrates how to handle complex asynchronous data flows, managing users, their photo albums, and individual photos.

## 🚀 Features

* **User Management:** Fetch, add, and remove users. This feature leverages traditional **Redux Thunks** (`createAsyncThunk`) to handle async actions.
* **Albums & Photos:** Expand a user to manage their albums, and expand an album to manage its photos. This data fetching and caching layer is powered by **RTK Query** (`albumsApi`, `photosApi`), providing an interesting contrast to other fetching libraries.
* **Mock Backend:** Utilizes `json-server` (`db.json`) to simulate a real REST API and database interactions.
* **Loading Skeletons:** Animated skeleton loaders provide immediate feedback during API requests.

## 🛠 Tech Stack

* **Frontend:** React
* **State Management:** Redux Toolkit (RTK), RTK Query, Custom Thunks
* **Backend Mocking:** JSON Server

## 📦 Getting Started

### Prerequisites
Make sure you have Node.js and npm installed.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/oleksandrivanyshyn/react-redux-media.git

2.  Navigate to the project directory:
    ```bash
    cd react-redux-media
    ```
3.  Install dependencies:
    ```bash
    npm install
    ```

### Running the App

You will need to run both the React development server and the JSON server simultaneously.

1.  **Start the JSON Server** (This serves the `db.json` file as an API):

    ```bash
    npm run start:server 
    ```

2.  **Start the React App** (in a new terminal window):

    ```bash
    npm start
    ```

The application will typically be available at [http://localhost:3000](https://www.google.com/search?q=http://localhost:3000).
