# Use lightweight Nginx image
FROM nginx:alpine

# Remove default Nginx static files
RUN rm -rf /usr/share/nginx/html/*

# Copy all project files (HTML, CSS, JS) into Nginx
COPY . /usr/share/nginx/html

# Expose port 80 inside the container
EXPOSE 80

# Start Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]
