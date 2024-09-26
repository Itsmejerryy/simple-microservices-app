# Use the official Node.js image
FROM node:14-alpine

# Set the working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json .
RUN npm install

# Copy the rest of the app files
COPY . .

# Expose port 3000
EXPOSE 3000

# Start the backend service
CMD ["node", "app.js"]
