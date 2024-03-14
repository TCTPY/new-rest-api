# new-rest-api

# user-service

# REST API for registering new user and save him to database(MongoDB)

GET /users -- list of users -- 200, 404, 500
GET /users/:id -- users by id -- 200, 404, 500
POST /users/:id -- create users -- 204, 4xx Header Location: url
OUT /users/:id -- fully update user -- 204/200, 404, 400, 500
PATCH /users/:id -- partially update user -- 204/200, 404, 400, 500
DELETE /users/:id -- delete user by id --204, 404, 400
