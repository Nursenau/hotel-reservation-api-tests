📝 README - Hotel Reservation API Test Collection

📚 Project Overview
This repository, named hotel-reservation-api-tests, is based on the Restful Booker API documentation. It includes test scenarios for various API endpoints such as GET, POST, PUT, PATCH, and DELETE operations using Postman. The tests are enhanced with environment variables, which makes them dynamic, reusable, and adaptable for different environments. This approach enhances the maintainability, scalability, and flexibility of API testing workflows.
The collection covers multiple functionalities of the Restful Booker API, including booking creation, updating, retrieval, and deletion. The tests ensure that the API performs correctly and handles edge cases as expected.

📋 Test Scenarios
The Postman collection includes tests for the following endpoints:

Creating a Booking (POST /booking):
Tests the ability to create a new hotel booking with all required and optional fields.
Retrieving a Booking (GET /booking/{id}):
Verifies that a booking can be retrieved using its unique ID.
Updating a Booking (PUT /booking/{id} and PATCH /booking/{id}):
Ensures that bookings can be updated with new details using the PUT or PATCH method.
Deleting a Booking (DELETE /booking/{id}):
Verifies that a booking can be deleted using its unique ID.
Error Handling:
Tests error responses for invalid requests, such as missing required fields or invalid IDs
