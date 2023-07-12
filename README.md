# CamTravel-Backend

CamTravel-Backend is a backend project developed using Express.js, Node.js, and MongoDB. This project includes user authentication for login and registration, as well as information about tourism places and hotels in each province of Cambodia. The main concept of this project is to provide users with an easy way to find and explore tourist destinations in Cambodia.

## Features

- User Authentication: Allow users to register and login to the system.
- Tourism Places: Provide information about tourist attractions in different provinces of Cambodia.
- Hotels: Display information about hotels available in each province for accommodation.

## Prerequisites

Before running the application, make sure you have the following prerequisites installed on your system:

- Node.js: The latest version of Node.js can be downloaded from the official website: [https://nodejs.org](https://nodejs.org)
- MongoDB: Install MongoDB Community Edition by following the instructions on the official website: [https://docs.mongodb.com/manual/installation](https://docs.mongodb.com/manual/installation)

## Installation

1. Clone the repository or download the source code ZIP file.
2. Open a terminal and navigate to the project directory.
3. Install the project dependencies by running the following command:
4. Configure the MongoDB connection by editing the `.env` file and providing the necessary database credentials.
5. Start the server by running the following command:
```bash
npm start
```

## Usage

1. Use a tool like Postman or any API testing tool to interact with the backend API endpoints.
2. Register a new user by sending a POST request to `/user/register` with the required user information.
3. Log in with the registered user credentials by sending a POST request to `/user/login`.
4. After successfully logging in, you will receive an access token that needs to be included in the headers of subsequent requests for authentication.
5. Use the provided API endpoints to retrieve information about tourism places and hotels in different provinces of Cambodia.

## Contributing

Contributions to the project are welcome and encouraged. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test thoroughly.
4. Submit a pull request to the main repository.

## Acknowledgments

The development of this project was inspired by the idea of creating a platform that helps users easily find tourist destinations in Cambodia. We would like to acknowledge the contributions of the open-source community and various online resources that helped in creating this application.

If you have any questions or suggestions regarding this project, please feel free to reach out to us.
