# DEUNA API Challenge

This repository contains a Postman collection and environment to test various functionalities of The Dog API as part of the DEUNA technical challenge. The collection includes multiple test scenarios to validate API requests.

## Getting Started

### Prerequisites

To run the tests, you'll need the following:

- [Node.js](https://nodejs.org/) installed on your machine.
- [Newman](https://www.npmjs.com/package/newman) - A command-line collection runner for Postman.

### Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/CarlosRiveera/deuna_api_challenge.git
    cd deuna_api_challenge
    ```

2. Install Newman globally using npm:

    ```bash
    npm install -g newman
    ```

### Running the Tests

You can run the Postman collection using Newman with the following command:

```bash
newman run DEUNA_prueba.postman_collection.json -e The_Dog_API.postman_environment.json
