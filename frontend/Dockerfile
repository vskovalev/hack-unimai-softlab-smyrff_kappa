# Use a base image
FROM nginx:latest

# Set working directory
WORKDIR /usr/share/nginx/html

# Copy HTML files
COPY *.html ./

# Copy images
COPY public ./public

# Expose port 80
EXPOSE 80
