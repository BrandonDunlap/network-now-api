# Social Network API

## Description
This is a backend API for a social network application where users can share their thoughts, react to friends' thoughts, and create a friend list. The application uses Express.js for routing, MongoDB as the database, and Mongoose for ODM.

## Installation
1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Ensure MongoDB is installed and running on your machine.
4. Run `npm run start` to start the application.

## Usage
The API routes can be tested using Insomnia or Postman. Below are the available routes:
- `GET /api/users`
- `GET /api/users/:id`
- `POST /api/users`
- `PUT /api/users/:id`
- `DELETE /api/users/:id`
- `POST /api/users/:userId/friends/:friendId`
- `DELETE /api/users/:userId/friends/:friendId`
- `GET /api/thoughts`
- `GET /api/thoughts/:id`
- `POST /api/thoughts`
- `PUT /api/thoughts/:id`
- `DELETE /api/thoughts/:id`
- `POST /api/thoughts/:thoughtId/reactions`
- `DELETE /api/thoughts/:thoughtId/reactions/:reactionId`

## Walkthrough Video
[Link to Video](https://www.youtube.com/watch?v=9qHAmMO9QJU)

## License
This project is licensed under the MIT License.
