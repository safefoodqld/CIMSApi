# SFPQ OpenAPI Specification

[![Build Status](https://travis-ci.org/rickykenny/redocTest.svg?branch=master)](https://travis-ci.org/rickykenny/redocTest)

## View Documentation

Documentation available at [https://safefoodqld.github.io/CIMSApi/](https://safefoodqld.github.io/CIMSApi/)

## Update Documentation

This documentation is generated using the [ReDoc GitHub generator](https://github.com/Rebilly/generator-openapi-repo#generator-openapi-repo--).

In order to make changes to the documentation, follow these steps:

1. Clone this repository
2. Make changes to the `swagger.yaml` file (following the Swagger 2.0 specification)
   - Running `npm run start` in the repository directory will serve an editor at `http://localhost:5000` and a viewer at `http://localhost:3000` if you want to preview your changes in real-time.
3. Commit your changes to the `master` branch
4. Wait for [travis-ci](https://travis-ci.org/profile/safefoodqld) to build
5. Enjoy your new documentation at [https://safefoodqld.github.io/CIMSApi/](https://safefoodqld.github.io/CIMSApi/)
