# Use Node.js base image
FROM node:18-alpine

# Set working directory
WORKDIR /app

# Copy project files
COPY . .

# Install dependencies if Node.js project
RUN npm install

# Expose port 3000
EXPOSE 3000

# Start the app
CMD ["npm", "start"]
