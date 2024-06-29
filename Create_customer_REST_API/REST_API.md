

# REST API for the customer database.

The root endpoint of the REST API is http://localhost:3000/api/customers

|    Method and endpoint     | Action                                                                                               |
| :------------------------: | :--------------------------------------------------------------------------------------------------- |
|     GET /api/customers     | Fetch all customers                                                                                  |
|  GET /api/customers/{id}   | Fetch customer by id. Id is sent in the route parameter                                              |
|    POST /api/customers     | Add new customer- New customer is send inside the request body.                                      |
| DELETE /api/customers/{id} | Delete customer by id. Id is sent in the route parameter                                             |
|  PUT /api/customers/{id}   | Edit customer by id. Id is sent in the route parameter and updated customer inside the request body. |
