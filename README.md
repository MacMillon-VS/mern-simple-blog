# Basic MERN Blog Application

A full-stack blog application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. This application allows users to read and create blog posts.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication and authorization
- Create, read, update, and delete blog posts
- Responsive design for mobile and desktop

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- [Node.js](https://nodejs.org/) (version 12 or higher)
- [MongoDB](https://www.mongodb.com/) (Make sure MongoDB is installed and running)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/mern-blog-app.git

2. Navigate to the project directory:

  ```bash
  cd mern-blog-app
```

3. Install server dependencies:

  ```
  cd server
  npm install
  ```

4. Install client dependencies:

  ```bash
  cd ../client
  npm install
```

5. Create a .env file in the server directory and configure your environment variables. Here's an example:

  ```bash
    MONGO_URL=<your-mongodb-url>
    JWT_SECRET=<your-jwt-secret>
  ```

6. Start the server:
   ```bash
     cd ../server
     npm start
   ```
7. Start thr client:
   ```bash
     cd ../client
     npm run dev
   ```
   Your MERN blog application should now be running locally. You can access client in your web browser at http://localhost:5173 and server in http://localhost:4000.

## Usage

- Register for an account or log in if you already have one.
- Create new blog posts, edit existing ones, or delete them.
- Comment on blog posts.
- Explore the application and enjoy blogging!

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the project on GitHub.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/my-feature` or `git checkout -b bugfix/issue-number`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push your changes to your fork: `git push origin feature/my-feature`.
5. Create a pull request on the original repository.

Please make sure to follow the [Code of Conduct](CODE_OF_CONDUCT.md) and [Contribution Guidelines](CONTRIBUTING.md) when contributing.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
