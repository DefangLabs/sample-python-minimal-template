# Flask Request Inspector API

This Flask application is designed to inspect and return detailed information about HTTP requests. It supports both GET and POST methods, providing insights into the request path, method, headers, query parameters, and body. Note that alognside your .py file, include a requirements.txt so that the Dockerfile can install the necessary packages with pip. 

## Features

1. Support both GET and POST HTTP methods
2. Detailed information about the request, including path, method, headers, query parameters, and body.

## Essential Setup Files
1. A [Dockerfile](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/).
2. A [compose file](https://docs.defang.io/docs/concepts/compose) to define and run multi-container Docker applications (this is how Defang identifies services to be deployed). (compose.yaml file)

## Prerequisite
1. Download [Defang CLI](https://github.com/DefangLabs/defang)
2. If you are using [Defang BYOC](https://docs.defang.io/docs/concepts/defang-byoc), make sure you have properly [authenticated your AWS account (optional)](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html)

## A Step-by-Step Guide
1. Open the terminal and type `defang login`
2. Type `defang compose up` in the CLI
3. Your app should be up and running with Defang in minutes!

---

Title: Flask Request Inspector API

Short Description: A Flask application that inspects and returns detailed information about HTTP requests

Tags: flask, http

Languages: python
