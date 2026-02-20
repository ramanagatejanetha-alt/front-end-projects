# Use lightweight official nginx image
FROM nginx:alpine

# Remove default static files
RUN rm -rf /usr/share/nginx/html/*

# Copy project files
COPY . /usr/share/nginx/html/

# Expose container port 80
EXPOSE 80

# Start nginx
CMD ["nginx", "-g", "daemon off;"]
