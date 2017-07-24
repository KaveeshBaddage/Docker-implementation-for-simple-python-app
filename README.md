# Docker-implementation-for-simple-python-app
Dockerize simple python application and create an Docker image


Instructions to run Docker image.

Build a new container image using Dockerfile.

	sudo docker build -t my_application_img .

Using that image (myapplication_img)run a new container which start and run the application.

	sudo docker run --name my_application_instance -p 8000:80 -i -t my_application_img


Visit localhost:8000 and see the running application

