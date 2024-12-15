# Use the official Node.js image
FROM node:18-alpine

# Set the working directory in the container
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json /app/
RUN npm install

# Copy the rest of the project files
COPY . /app/

# Expose the port React runs on
EXPOSE 3000

# Default command to start the app
CMD ["npm", "start"]
