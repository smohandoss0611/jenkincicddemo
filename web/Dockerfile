# Use an official Node.js base image
FROM node:14-alpine

# Set the working directory in the container
WORKDIR /usr/src/app

# Copy package.json and package-lock.json files to the working directory
COPY package*.json ./

# Run npm install to install dependencies
RUN npm install

# Copy the rest of the application code to the working directory
COPY . .

# Expose the port your Node.js application listens on
EXPOSE 3000