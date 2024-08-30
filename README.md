# MovieReviewApp

A full-stack web application built with React (frontend) and Java Spring Boot (backend), with MongoDB Atlas as the database. The app provides movie details, allows users to run trailers, and enables adding reviews.

## Features

- Fetch and display movie details
- Play movie trailers
- Add and view user reviews for movies

## Tech Stack

- **Frontend**: React, Material UI, FontAwesome
- **Backend**: Java Spring Boot
- **Database**: MongoDB Atlas

## Getting Started

### Prerequisites

- Node.js and npm installed
- Java 11 or higher
- MongoDB Atlas account

### Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/AminduBhashana/MovieApp.git
    ```

2. **Backend Setup**:
   - Navigate to the backend directory:
     ```sh
     cd movie-app-backend
     ```
   - Install dependencies and run the Spring Boot server:
     ```sh
     ./mvnw spring-boot:run
     ```

3. **Frontend Setup**:
   - Navigate to the frontend directory:
     ```sh
     cd movie-app-frontend
     ```
   - Install dependencies and run the React app:
     ```sh
     npm install
     npm start
     ```

4. **Database Setup**:
   - Configure MongoDB Atlas by setting up your connection URI in the backend's `application.properties` file.

### Libraries Used

- **Material UI**: For modern and responsive UI components.
- **FontAwesome**: For icons used throughout the application.

### Running the Application

1. Start the Spring Boot server.
2. Run the React app.
3. Open your browser and navigate to `http://localhost:3000`.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
