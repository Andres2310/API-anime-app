# API-anime-app
[https://petstore.swagger.io/v2/swagger.json](https://petstore.swagger.io/v2/swagger.json)

This is a sample server Petstore server. You can find out more about Swagger at [http://swagger.io](http://swagger.io) or on [irc.freenode.net, #swagger](http://swagger.io/irc/). For this sample, you can use the api key `special-key` to test the authorization filters.

[Terms of service](http://swagger.io/terms/)

[Contact the developer](mailto:apiteam@swagger.io)

[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

[Find out more about Swagger](http://swagger.io)

Schemeshttpshttp

Authorize

### [pet](#/pet)

Everything about your Pets

Find out more: [http://swagger.io](http://swagger.io)

POST[/pet/{petId}/uploadImage](#/pet/uploadFile)

uploads an image

POST[/pet](#/pet/addPet)

Add a new pet to the store

PUT[/pet](#/pet/updatePet)

Update an existing pet

GET[/pet/findByStatus](#/pet/findPetsByStatus)

Finds Pets by status

GET[/pet/findByTags](#/pet/findPetsByTags)

Finds Pets by tags

GET[/pet/{petId}](#/pet/getPetById)

Find pet by ID

POST[/pet/{petId}](#/pet/updatePetWithForm)

Updates a pet in the store with form data

DELETE[/pet/{petId}](#/pet/deletePet)

Deletes a pet

### [store](#/store)

Access to Petstore orders

POST[/store/order](#/store/placeOrder)

Place an order for a pet

GET[/store/order/{orderId}](#/store/getOrderById)

Find purchase order by ID

DELETE[/store/order/{orderId}](#/store/deleteOrder)

Delete purchase order by ID

GET[/store/inventory](#/store/getInventory)

Returns pet inventories by status

### [user](#/user)

Operations about user

Find out more about our store: [http://swagger.io](http://swagger.io)

POST[/user/createWithArray](#/user/createUsersWithArrayInput)

Creates list of users with given input array

POST[/user/createWithList](#/user/createUsersWithListInput)

Creates list of users with given input array

GET[/user/{username}](#/user/getUserByName)

Get user by user name

PUT[/user/{username}](#/user/updateUser)

Updated user

DELETE[/user/{username}](#/user/deleteUser)

Delete user

GET[/user/login](#/user/loginUser)

Logs user into the system

GET[/user/logout](#/user/logoutUser)

Logs out current logged in user session

POST[/user](#/user/createUser)

Create user

#### Models

ApiResponse

Category

Pet

Tag

Order

User
