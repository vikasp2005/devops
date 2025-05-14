# Use the official NGINX image
FROM nginx:latest

# Copy custom nginx.conf to the container
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Copy the HTML files
COPY build/ /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start NGINX in the foreground
CMD ["nginx", "-g", "daemon off;"]

