# Simple Express API

A lightweight REST API built with Express.js that demonstrates just basic routing and HTTP methods.

## Features

- GET endpoint to retrieve T-shirt information
- POST endpoint to customize a T-shirt with a logo
- Basic request validation
- JSON response handling

## Technologies Used

- Node.js
- Express.js

## Installation

1. Clone the repository

```bash
git clone https://github.com/mitorudev/simple-express-api.git
cd simple-express-api
```

2. Install dependencies

```bash
npm install
```

3. Start the server

```bash
node index.js
```

The server will run on `http://localhost:8080`

## API Endpoints

### GET /tshirt

Returns information about a t-shirt.

### POST /tshirt/:id

Customizes a t-shirt with a logo.

## Next Steps

Future improvements could include:

- Adding more endpoints
- Implementing a database
- Adding authentication
- Creating middleware for logging and error handling
