# user-management REST-API
> API for user management

## Documentation
* [Connect to the API](#connect-to-the-api)
* [GET functions](#get-functions)
	- [Display all users](#display-all-users)
	- [Display single user](#display-single-user)
* [POST functions](#post-functions)
	- [Create new user](#create-new-user)
* [PUT functions](#put-functions)
	- [Update existing user](#update-existing-user)
* [DELETE functions](#delete-functions)
	- [Delete existing user](#delete-existing-user)
	
## Connect to the API
##### Entrypoint URL:
`http://localhost/php-crud-api/entrypoints.php`

If you don't know how to connect to an API you can use 3rd party programs like [postman](https://www.getpostman.com/) to establish the connection and pass the required parameters to the server.

More information about connecting to an API with postman can be found [here](https://www.youtube.com/watch?v=t5n07Ybz7yI&t=31s).

___

## GET functions
> These are the functions available for GET requests.

### Display all users
Returns json data from all users with the following data: "id", "username", "email" and "password".
##### Required parameters:
None
##### Response:
All users in json format. \
In case of failure: json formatted error code.

### Display single user
Returns json data from a single user with the following data: "id", "username", "email" and "password".
##### Required parameters:
{"id":"value"} \
*Value must be an integer.*
##### Response:
Single user in json format. \
In case of failure: json formatted error code.

___

## POST functions
> These are the functions available for POST requests.
### Create new user
Inserts a new user into the database and responds with either success or failure.


___

## PUT functions
> These are the functions available for PUT requests.
### Update existing user
Skriv

___

## DELETE functions
> These are the functions available for DELETE requests.
### Delete existing user
Skriv
