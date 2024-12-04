# Use an Nginx image for serving the frontend
FROM nginx:alpine

# Copy the frontend files to Nginx's default HTML directory
COPY . /usr/share/nginx/html

# Expose the port Nginx will run on
EXPOSE 80

# Default command to start Nginx
CMD ["nginx", "-g", "daemon off;"]
