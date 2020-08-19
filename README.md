diner schema:
username: string
password: string
email: string
location: string

operator schema:
username: string
password: string
email: string

Create a new diner: POST /api/auth/diner

Create a new operator: POST /api/auth/operator

Login: POST /api/auth/login

Returns all trucks: GET /api/trucks
Returns a specific truck: GET /api/trucks/:id
Returns an array of a diner's favorite trucks: GET /api/diners/:id/favoriteTrucks
Returns an array of trucks owned by an operator: GET /api/operators/:id/trucksOwned
Create a truck: POST /api/trucks
Update a truck: PUT /api/trucks/:id
Delete a truck: DELETE /api/trucks/:id