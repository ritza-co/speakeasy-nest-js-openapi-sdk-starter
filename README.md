<div align="center">

<a href="[Speakeasy](https://speakeasyapi.dev/)">
  <img src="https://github.com/speakeasy-api/speakeasy/assets/68016351/e959f81a-b250-4003-8c5c-a45b9463fc95" alt="Speakeasy Logo" width="400">
<h2>Speakeasy NestJS OpenAPI Example</h2>
</a>

</div>

This example NestJS app demonstrates Speakeasy-recommended practices for creating clear OpenAPI specifications and SDKs.

This project was bootstrapped with [NestJS-CLI](https://docs.nestjs.com/cli/overview).

## Prerequisites

You need to have [Node.js version >= 16](https://nodejs.org/) and [Nest CLI](https://github.com/nestjs/nest-cli) installed on your system to run this project.

To generate an SDK, you'll also need to [install Speakeasy CLI](https://github.com/speakeasy-api/speakeasy#installation) or use the Speakeasy dashboard.

## Installation

Install the application on your local machine.

1. Clone the repository:

    ```bash
    git clone https://github.com/speakeasy-api/speakeasy-nestjs-example.git
    ```

2. Navigate into the directory:

    ```bash
    cd speakeasy-nestjs-example
    ```

3. Install all dependencies for the application using NPM:

    ```bash
    npm install
    ```

4. Install Speakeasy CLI:

    ```bash
    brew install speakeasy-api/homebrew-tap/speakeasy
    ```

## Running the application for development

You can use the provided script to run the application in development mode. It will watch for any changes in the source code and automatically restart the server.

> Before starting the dev server, move the `sdk-typescript` folder to a new location outside this project.

```bash
npm run start:dev
```

### Creating an OpenAPI specification

When the development server starts, an OpenAPI specification file, `openapi.yaml`, is created in the root directory using JS-YAML.

## Creating an SDK with Speakeasy

Run the following command to create a Speakeasy SDK:

```bash
speakeasy quickstart
```

## License

This project is licensed under the terms of the Apache 2.0 license.
