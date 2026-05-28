# Dockerfile

# Base Image
FROM nginx:alpine

# Stage 1: Build

# Use the official lightweight Nginx image
FROM nginx:stable-alpine

# Copy your local index.html to the default Nginx hosting directory
COPY index.html /usr/share/nginx/html/index.html

# Copy your custom configuration to the correct default config path
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Expose port 80 for web traffic
EXPOSE 80

# Start Nginx and keep the process running in the foreground
CMD ["nginx", "-g", "daemon off;"]

