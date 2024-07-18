Step 1. Build the docker file by running: docker build -t name-of-image .

Step 2. Start a new container running the image: docker run -dp 8080:80 --name name-of-container name-of-image

step 3. Visit website on localhost:8080