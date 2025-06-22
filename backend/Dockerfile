FROM node:18-alpine

WORKDIR /app

# Copy package files from the backend directory
COPY package*.json ./

# Install dependencies
RUN npm ci --only=production

# Copy backend source code from the backend directory
COPY . .

# Expose port
EXPOSE 3000

# Start the application
CMD ["npm", "start"] 