# Use lightweight NGINX image
FROM nginx:alpine

# Copy only main homepage files into NGINX html folder
COPY . /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start NGINX
CMD ["nginx", "-g", "daemon off;"]
