How to Run the Project

1. Install Docker
  Ensure Docker is installed on your computer. You can download it here.

2. Configure the .env File
  Create a .env file in the root directory and add the following parameters:

  POSTGRES_USER=your_username
  POSTGRES_PASSWORD=your_password
  POSTGRES_DB=your_database

3. Run Docker Compose
  Execute the following command:

    docker-compose up --build

  This will start the FastAPI server and PostgreSQL in Docker containers.

4. Open the API
  Once successfully launched, you can access the Swagger documentation to interact with the API.
