## Restful-Booker API Testing with Postman

This repository contains files for testing the Restful-Booker API using Postman. It includes:

- **Collection file**: Contains requests and test cases.
- **Environment file**: Defines environment variables required for the tests.

### Getting Started

1. **Clone the repository:**
2. **Import into Postman**:
- Open Postman.
- Import the `Restful-Booker.postman_collection.json` file as a collection.

3. **Set up environment variables (if needed)**:
- Edit the environment within Postman to configure:
  - `auth_token`: Authentication token for accessing secured endpoints.
  - `bookingid`: Used to store booking IDs retrieved during tests.
  - `authorization`: Authorization details for endpoints requiring specific permissions.

4. **Run tests**:
- Execute requests from the imported collection.
- Review test results within Postman's test runner.

### Collection Overview

The collection includes the following requests:

- **Get Token**: Retrieves an authentication token using credentials.
- **Create Booking**: Adds a new booking and verifies the response fields.
- **Get all IDs**: Retrieves all booking IDs.
- **Get ID by name**: Finds a booking ID by specifying first and last names.
- **Get ID By Checking in and Checking out date**: Retrieves booking IDs based on check-in and check-out dates.
- **Get Booking by ID**: Retrieves booking details by a specific ID stored in the environment.
- **Update Booking**: Updates an existing booking and verifies the response.
- **Update User's Name**: Modifies the first and last names of a booking.
- **Delete Booking**: Deletes a booking using its ID.
- **Check API Health**: Verifies the API's health status.
