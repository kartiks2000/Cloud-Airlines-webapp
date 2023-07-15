# Cloud-Airlines-webapp
Cloud-Airlines-webapp app

# Build docker container from image using:
docker build . -t dockerized-react

# OR

# You can pull the existing image from docker hub

# For Linux/ubuntu AMD64
docker pull kartiksaxena2000/cloud_airlines_webapp:latest

# For ARM64 processors (Apple silicon)
docker pull kartiksaxena2000/cloud_airlines_webapp_mac:latest

# for building from scratch (without using cached image layers)
docker build --no-cache . -t dockerized-react

# running image as a container
docker run -d -p 3000:80 dockerized-react

# Access the app at http://localhost:3000
