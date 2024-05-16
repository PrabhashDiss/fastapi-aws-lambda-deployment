# FastAPI AWS Lambda Deployment

This repository contains the code for deploying a FastAPI application on AWS Lambda.

## Overview

In this tutorial, we walk through the process of setting up a FastAPI application, bundling its dependencies, and deploying it to AWS Lambda. The provided instructions cover everything from installing required libraries to configuring the Lambda function and verifying the deployment.

## Prerequisites

Before proceeding, ensure you have the following installed:
- Visual Studio Code or any preferred code editor
- Python (preferably version 3.7 or higher)
- AWS account (if you plan to deploy to AWS Lambda)

## Getting Started

To get started, follow these steps:

1. Install necessary libraries: FastAPI, uvicorn, and Mangum.
2. Create a `requirements.txt` file.
3. Write the FastAPI application in `main.py`.
4. Bundle dependencies into an artifact for Lambda deployment.
5. Configure and deploy the FastAPI application to AWS Lambda.
6. Verify the deployment by testing the Lambda function endpoint.

## Repository Structure

- `main.py`: Contains the FastAPI application code.
- `requirements.txt`: Lists the required Python dependencies.
- `artifact.zip`: Artifact containing bundled dependencies and application code.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.
