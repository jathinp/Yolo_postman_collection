# Yolo_postman_collection
This is a repository for postman collection

Project : API Testing

Description: This is an API Collection of automated tests for GET, POST, DELETE requests.

Tool Required : Install POSTMAN and write assertions in Tests.

GET : Requests the details of the user in https://gorest.co.in/public/v2/users
  - Successful status code validation
  - Checking for a particular user
  - User data fields validation based on Index
  - Ensuring header will have a content-Type
  - Validation on Server Header

POST : Creates new users in https://gorest.co.in/public/v2/users
  - Creating a new user and checking for successfull status code.
  - User details validation

Delete : Delete's users in https://gorest.co.in/public/v2/users
  - Successfull deletion status code [ no message is seen after deleting a user]
