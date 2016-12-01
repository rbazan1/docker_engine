# Flask
A Flask App running inside Docker

## Flask Application
flask/app.py

## Requirements File
flask/requirements.txt

## Dockerfile
flask/Dockerfile

## Build the docker Image
docker build -t flask-sample-one:latest .

## Run the Docker Container
docker run -d -p 5000:5000 flask-sample-one

## Verify Docker Process
docker ps -l
