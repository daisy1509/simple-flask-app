# Flask Docker Application

This project is a simple Flask application packaged in a Docker container. It demonstrates how to set up a Flask app, define routes, and serve HTML templates.

## Project Structure

```
flask-docker-app
├── app
│   ├── __init__.py
│   ├── routes.py
│   └── templates
│       └── index.html
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
├── .dockerignore
└── README.md
```

## Getting Started

### Prerequisites

- Docker
- Docker Compose

### Installation

1. Clone the repository:

   ```
   git clone <repository-url>
   cd flask-docker-app
   ```

2. Build the Docker image:

   ```
   docker-compose build
   ```

### Running the Application

To run the application, use the following command:

```
docker-compose up
```

The application will be accessible at `http://localhost:5000`.

### Stopping the Application

To stop the application, press `CTRL+C` in the terminal where the application is running. You can also run:

```
docker-compose down
```

### Directory Details

- **app/**: Contains the Flask application code.
- **Dockerfile**: Instructions to build the Docker image.
- **docker-compose.yml**: Configuration for running the application in Docker.
- **requirements.txt**: Lists the Python dependencies.
- **.dockerignore**: Specifies files to ignore when building the Docker image.

### License

This project is licensed under the MIT License.