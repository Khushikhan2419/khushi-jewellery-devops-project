FROM nginx:alpine

# Copy ONLY the main frontend into Nginx
COPY frontend/main/ /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
