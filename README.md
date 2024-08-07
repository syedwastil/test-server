# Flask Test Server

A minimalistic Flask server for general-purpose testing, designed to display a simple HTML page and monitor incoming API requests. This server is dockerized for easy deployment using Docker and Docker Compose.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Wasti Test Server serves a basic HTML page and is intended for testing purposes. Its main function is to provide a simple interface and to allow users to observe API requests received by the server.

## Getting Started

Follow the instructions below to set up and run the server on your local machine using Docker and Docker Compose.

### Prerequisites

Ensure you have the following installed:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/wasti-test-server.git
   cd wasti-test-server
   ```

2. **Build the Docker image**:
   ```bash
   docker-compose build
   ```

### Usage

1. **Start the server**:
   ```bash
   docker-compose up
   ```

2. **Access the server**:

   Open a web browser and navigate to `http://localhost` to view the HTML page served by the server.

3. **Stop the server**:
   ```bash
   docker-compose down
   ```

### Monitoring API Requests

All incoming requests will be logged in the terminal where the server is running. This allows you to monitor and inspect any API requests made to the server.

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

1. Fork the repository.
2. Create a new feature branch: `git checkout -b my-feature-branch`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-feature-branch`
5. Create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

