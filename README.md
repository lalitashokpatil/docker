# my-python-app/my-python-app/README.md

# My Python App

This is a simple Python application that prints "Hello, Docker!" when executed. It is designed to run inside a Docker container.

## Prerequisites

- Docker installed on your machine.

## Getting Started

Follow these steps to build and run the application:

1. Clone the repository:

   ```
   git clone <repository-url>
   cd my-python-app
   ```

2. Build the Docker image:

   ```
   docker build -t my-python-app .
   ```

3. Run the Docker container:

   ```
   docker run my-python-app
   ```

You should see the output:

```
Hello, Docker!
```

## File Structure

- `app/main.py`: The entry point of the application.
- `Dockerfile`: Instructions to build the Docker image.
- `requirements.txt`: Lists the Python dependencies.