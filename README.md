# URL Shortener Project

This is a URL shortener project built using Go, Go Fiber, and Redis for storage.

## Getting Started

Follow these steps to run the project on your local machine:

1. Clone the repository:
   ```sh
   git clone https://github.com/Codensity30/url-shortener.git
2. Install Dependencies:
    ```sh
    cd api
    go mod tidy
3. Create an environment file in api folder:
    ```sh
    DB_ADDR="db:6379"
    DB_PASS=""
    APP_PORT=":3000"
    DOMAIN="localhost:3000"
    API_QUOTA=10
4. API Endpoints:
    ```sh
    GET /:url - redirect you to original url
    POST /api/v1 - returns the shortened url
