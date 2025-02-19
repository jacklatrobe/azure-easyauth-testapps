# Use the node:16 image as the base image
FROM node:16

# Set the working directory to /app
WORKDIR /app

# Copy the package.json and package-lock.json files to the working directory
COPY package.json package.json

# Run npm install to install the dependencies
RUN npm install

# Copy the rest of the application code to the working directory
COPY . .

# Expose port 8080
EXPOSE 8080

# Set the command to run the application using npm start
CMD ["npm", "start"]
