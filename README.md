# Project Overview

This project is a simple "Hello World" web application that consists of a Java backend using Spring Boot and a React.js frontend. 

## Project Structure

The project is organized into two main directories: `backend` and `frontend`.

```
hello-world-app
├── backend          # Contains the Java Spring Boot application
│   ├── src
│   │   ├── main
│   │   │   ├── java
│   │   │   │   └── com
│   │   │   │       └── example
│   │   │   │           └── HelloWorldApplication.java
│   │   │   └── resources
│   │   │       └── application.properties
│   ├── pom.xml     # Maven configuration file
│   └── README.md    # Documentation for the backend
├── frontend         # Contains the React.js application
│   ├── src
│   │   ├── App.js
│   │   ├── index.js
│   │   └── components
│   │       └── HelloWorld.js
│   ├── package.json  # npm configuration file
│   ├── public
│   │   └── index.html # Main HTML file for the React app
│   └── README.md      # Documentation for the frontend
└── README.md          # Overall documentation for the project
```

## Getting Started

### Prerequisites

- Java 17
- Maven
- Node.js and npm

### Backend Setup

1. Navigate to the `backend` directory:
   ```
   cd backend
   ```

2. Build the project using Maven:
   ```
   mvn clean install
   ```

3. Run the Spring Boot application:
   ```
   mvn spring-boot:run
   ```

The backend will start on the default port (8080).

### Frontend Setup

1. Navigate to the `frontend` directory:
   ```
   cd frontend
   ```

2. Install the dependencies:
   ```
   npm install
   ```

3. Start the React application:
   ```
   npm start
   ```

The frontend will be available at `http://localhost:3000`.

## Usage

Once both the backend and frontend are running, you can access the application in your web browser. The frontend will display a "Hello, World!" message fetched from the backend.

## Contributing

Feel free to fork the repository and submit pull requests for any improvements or bug fixes. 

## License

This project is licensed under the MIT License.