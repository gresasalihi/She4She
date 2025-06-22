# Use a lightweight Nginx image
FROM nginx:1.25-alpine

# Copy frontend files to the Nginx public directory
COPY . /usr/share/nginx/html

# Copy the Nginx configuration file
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Expose port 80 for the Nginx server
EXPOSE 80 