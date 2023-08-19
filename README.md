# Movie Notes Api

Movie Notes App is a Node.js application that allows users to create and manage movie notes, along with tags related to the movies.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Layout](#layout)
- [Contributing](#contributing)
- [License](#license)

## Features

- User registration and authentication.
- Create, read, update, and delete movie notes.
- Add tags to movie notes for better organization.
- Password encryption using bcrypt for enhanced security.
- Error handling and validation for user-friendly interactions.
- SQLite database for data storage.
- Pagination and filtering for efficient data retrieval.
- Express framework for routing and server setup.

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/EduardoVisconti/movienotes-api.git
   cd movienotesapi
   ```

2. Install dependencies:

   ```
   npm install
   ```

3. Create the SQLite database:
   ```
   npm run migrate
   ```
   This will initialize the database required for the app.

## Usage

1. Start the server:

   ```
   npm run dev
   ```

2. Open your web browser and navigate to `http://localhost:3333`.

3. Register a new user and start adding movie notes with tags!

## Technologies

- [Node.js](https://nodejs.org)
- [Express.js](https://expressjs.com)
- [SQLite](https://www.sqlite.org)
- [Knex.js](https://knexjs.org)
- [Bcrypt](https://www.npmjs.com/package/bcrypt) for password encryption
- [Express Async Errors](https://www.npmjs.com/package/express-async-errors) for error handling
- [Nodemon](https://nodemon.io) for development server
- Pagination and filtering

## Layout

You can view the layout of the Movie Notes App below:

![Beekeeper Studio](https://i.imgur.com/uqWxpsD.jpg)
![Insomnia](https://i.imgur.com/7xec7rA.jpg)

## Contributing

Contributions to this project are welcome! If you find any issues or have ideas for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Created with ❤️ by [Eduardo Visconti](https://github.com/EduardoVisconti)
