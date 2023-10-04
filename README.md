# Microfrontend Study Project

## Overview

This monorepo contains multiple packages that together form a microfrontend architecture using Module Federation and React. The project aims to demonstrate best practices, scalability, and interoperability between different frontend modules.

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Packages](#packages)
- [Architecture](#architecture)
- [Development](#development)
- [Testing](#testing)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

- Node.js >= 18.x
- Npm >= 9.8.1

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/rica000/microfrontend-study-project.git
    ```

2. Navigate to the project directory:

    ```bash
    cd microfrontend-study-project
    ```

3. Install dependencies:

    ```bash
    cd ./microfrontend-folder
    npm install
    ```

## Packages

This monorepo contains the following packages:

- `container`: The main application shell that orchestrates the microfrontends.
- `marketing`: A marketing section.
- `dashboard`: Dashboard microfrontend.

## Architecture

The project uses Module Federation to enable separate deployment and sharing of code between different frontend modules. Each package is a self-contained application that can be developed, deployed, and loaded independently.

## Development

To start the development server for a specific package:

```bash
cd ./microfrontend-folder
npm start
```

## Testing

Run tests across all packages: (not yet implemented!)

```bash
npm test
```

## Deployment

Each package has its own build and deployment script. Refer to the README within each package for specific deployment instructions. (not yet implemented!)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

Feel free to modify this README to better suit the specifics of your project.