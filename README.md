# Sendhooks example

Codebase for the article at https://dev.to/koladev/10-minute-guide-to-building-a-webhook-service-with-sendhooks-3lbm.

1. Clone or download the repository.
2. Run `docker-compose up -d --build` to start the project. This will start a container for the dashboard (port 3000), backend (port 5002) and API (port 5001).
3. Once the containers are running, navigate to <http://localhost:3000> in your web browser to access the dashboard.
4. The backend is available at <http://localhost:5002>, where you can interact with it using HTTP requests.
5. The API is available at <http://localhost:5001>, and provides a RESTful interface for interacting with the system.

Note that these steps assume that Docker Compose is installed on your machine. If you don't have Docker Compose installed, you'll need to download and install it before proceeding.
