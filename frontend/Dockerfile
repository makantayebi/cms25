# Use Node.js as base image
FROM node:18

# Set working directory
WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy project files
COPY . .

# Expose the Angular port
EXPOSE 4200

# Start the Angular app
CMD ["npm", "start"]