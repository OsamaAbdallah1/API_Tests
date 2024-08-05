# API Project

## Project Overview
This project is a Java-based API client designed to interact with two specific endpoints using the GET method. It uses `HttpClient` for making HTTP requests and `Gson` for JSON parsing. The project also leverages POJOs and Lombok for handling data, and includes utility files for properties handling. A test runner class is provided for running tests.

## Project Structure

- **Endpoints**
  - `http://api.zippopotam.us/de/bw/stuttgart`: get all the data for Stuttgart.
  - `http://api.zippopotam.us/{country}/{postal-code} `: get the data for specific postal code.
- **HttpMethod Class**: Contains methods for making HTTP GET requests, returning responses and Uses `Gson` to parse JSON responses into POJOs.
- **POJO Package**: Contains data classes with Lombok annotations.
- **Utility Files**: Handles properties for configuration.
- **Test Runner Class**: Manages the execution of tests.

## Prerequisites
- Java Development Kit (JDK) installed
- Maven installed
- IDE (IntelliJ)

## Setup Instructions

1. **Clone the Repository**
    ```sh
    git clone https://github.com/OsamaAbdallah1/API_Tests.git
    cd API_Tests
    ```

2. **Install Dependencies**
    ```sh
    mvn clean install
    ```

3. **Test Data**
    - Ensure your configuration properties file (`application.properties`) is correctly set up in the `resources` directory.
