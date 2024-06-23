# Restful-Booker API Postman Testing

## Introduction

Welcome to the Restful-Booker API Postman Collection repository. This collection contains a comprehensive set of API requests designed to test various endpoints provided by the Restful-Booker API. Restful-Booker is a RESTful web service for managing hotel bookings, offering functionalities for creating, retrieving, updating, and deleting bookings.

## Getting Started

To begin using this Postman collection for testing the Restful-Booker API:

1. **Clone the Repository**:
   - Clone this repository to your local machine using Git.

2. **Import into Postman**:
   - Open Postman.
   - Click on **Import** to upload the `Restful-Booker.postman_collection.json` file, included in this repository, as a collection.

3. **Set up Environment Variables (if needed)**:
   - Edit the environment within Postman to configure any necessary variables such as `auth_token` for authentication or `bookingid` for storing booking IDs.

4. **Run Tests**:
   - Execute requests from the imported collection.
   - Review and verify the test results within Postman's test runner.

## Collection Overview

The Restful-Booker API Postman Collection includes the following requests:

- **Authentication**: Retrieves an authentication token for accessing secured endpoints.
- **Create Booking**: Adds a new booking and verifies the response fields.
- **Get All Bookings**: Retrieves a list of all bookings.
- **Get Booking by ID**: Retrieves details of a booking by a specific ID.
- **Update Booking**: Updates an existing booking and verifies the response.
- **Partial Update Booking**: Modifies specific fields of a booking.
- **Delete Booking**: Deletes a booking using its ID.
- **Health Check**: Verifies the health status of the API.

## Tests

Each request in this collection includes automated tests to verify expected behaviors:

- **Response Status**: Checks the HTTP response status code (e.g., 200 OK, 201 Created).
- **Response Body**: Verifies the structure and content of the JSON response.
- **Data Integrity**: Ensures data sent and received is accurate and consistent.
- **Performance**: Evaluates response times to ensure they meet performance requirements.

