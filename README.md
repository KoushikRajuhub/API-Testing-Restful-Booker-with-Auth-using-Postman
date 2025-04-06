# API-Testing-Restful-Booker-with-Auth-using-Postman

📋 Assignment Overview:
This project focuses on testing the Restful Booker API using Postman, with authentication, by creating a structured collection to cover various real-world CRUD operations and error handling scenarios.

✅ Tasks Covered in the Collection:

1. Create a Booking

   * Send a POST request to create a new booking with valid data.

<br>


2. Update the Booking Name

  * Use a PUT or PATCH request to update the booking’s first or last name.

  * Verify the update using a GET request by booking ID.
<br>


3. Create and Delete a Booking

  * Create a booking and then delete it using a DELETE request.

  * Verify deletion by performing a GET request on the same ID (should return an error or not found).
<br>


4. Get Existing Booking and Update

  * Fetch all booking IDs using GET.

  * Pick one ID and update the booking details.

  * Confirm the update by retrieving the booking using GET by ID.
<br>


5. Invalid Booking Creation

  * Attempt to create a booking using an invalid JSON payload.

  * Validate that the API returns appropriate error messages.
<br>


6. Edge Case – Update Deleted Booking

  * Try to update a booking that has already been deleted and verify the API's error response.
<br>



This assignment helps reinforce practical API testing concepts, including request chaining, authentication handling, response validation, and negative testing.

