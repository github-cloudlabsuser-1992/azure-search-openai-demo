# Backend Application Documentation

## Overview

The backend of the Chat App is built using [Quart](https://quart.palletsprojects.com/), a Python framework for asynchronous web applications. It serves as the core logic handling the communication between the frontend and any external services, such as databases or third-party APIs.

## Directory Structure

- `app.py`: The entry point for the Quart application.
- `config.py`: Contains configuration settings for different environments (development, testing, production).
- `decorators.py`: Defines custom decorators for route authentication and logging.
- `error.py`: Handles application-wide error responses.
- `gunicorn.conf.py`: Configuration file for Gunicorn when deploying the app.
- `main.py`: Contains the main business logic of the application.
- `prepdocs.py`: Script for preparing documentation.
- `requirements.in`: Specifies direct dependencies for the application.
- `requirements.txt`: Generated file with pinned versions of all dependencies.
- `text.py`: Utility functions for text processing.

## Setup

To set up the backend application, ensure you have Python 3.11 and pip installed. Then, follow these steps:

1. Navigate to the `app/backend/` directory.
2. Install the dependencies:

```sh
pip install -r requirements.txt