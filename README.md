# Cloud-Airlines-webapp
Cloud-Airlines-webapp app

# Build docker container from image using:
docker build . -t dockerized-react

# for building from scratch (without using cached image layers)
docker build --no-cache . -t dockerized-react

# running image as a container
docker run -d -p 3000:80 dockerized-react

# Access the app at 80

