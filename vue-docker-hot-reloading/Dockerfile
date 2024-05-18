# Use the official lightweight Node.js 16 image
FROM node:16-alpine

# Set working directory inside the container
WORKDIR /app

# Copy package.json and package-lock.json to the working directory
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application code
COPY . .

# Expose port 8080 to the outside world
EXPOSE 8080

# Start the app
CMD ["npm", "run", "serve"]
