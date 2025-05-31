# Use official Node.js LTS version
FROM node:18

# Create and set the working directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application
COPY . .

# Expose the relevant port (update per service)
EXPOSE 3002

# Start the service
CMD ["npm", "start"]
