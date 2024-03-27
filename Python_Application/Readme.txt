Steps involved in containerization of Python flask:
1. Create a Python flask application.

2. Create a requirements.txt file

3. Create a Dockerfile in the same directory as your application

4. Build the Docker image
   Command: docker build -t my-python-app .

5. Run the Docker container
   Command: docker run -p 8000:8000 my-python-app

6. Access your application:
   Open a web browser and navigate to http://localhost:8000 to see your Python Flask application running inside a Docker container.