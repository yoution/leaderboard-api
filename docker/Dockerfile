# Use the base image with Node.js
FROM node:latest

# Copy the current directory into the Docker image
COPY . /leaderboard-api
# Set working directory for future use
WORKDIR /leaderboard-api

# Install the dependencies from package.json
RUN npm install

CMD npm start
