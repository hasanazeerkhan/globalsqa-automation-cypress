# GlobalSQA Automation with Cypress

Welcome to the GlobalSQA Automation project using Cypress! This repository contains automated tests for web applications, leveraging the power of Cypress for end-to-end testing.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running Tests](#running-tests)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)

## Features

- Fast and reliable end-to-end testing
- Easy setup and configuration
- Detailed test reports
- Support for various browsers
- Integration with CI/CD pipelines

## Getting Started

To get started with the GlobalSQA Automation project, follow the instructions below to set up your environment and run the tests.

## Prerequisites

Make sure you have the following installed on your machine:

- Node.js (version 12 or higher)
- npm (Node package manager)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hasanazeerkhan/globalsqa-automation-cypress.git
   cd globalsqa-automation-cypress
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

## Running Tests

To run the tests, use the following command:
```bash
npx cypress open
```
This will open the Cypress Test Runner. You can select the test files you want to run.

Alternatively, to run tests in headless mode, use:
```bash
npx cypress run
```

## Folder Structure

The project has the following folder structure:

```
globalsqa-automation-cypress/
├── cypress/
│   ├── fixtures/        # Sample test data
│   ├── integration/     # Test specifications
│   ├── plugins/         # Custom plugins
│   └── support/         # Custom commands and configurations
├── cypress.json         # Cypress configuration file
└── package.json         # Project metadata and dependencies
```

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.
