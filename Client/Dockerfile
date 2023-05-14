# Use the official Node.js runtime as a parent image
FROM node:latest

# Set the working directory to /app
WORKDIR /app

# Copy the package.json and package-lock.json files to the container
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application files to the container
COPY . .

# Expose port 8000 for the application
EXPOSE 3000

# Start the application when the container starts
CMD ["node", "js/node.js"]
