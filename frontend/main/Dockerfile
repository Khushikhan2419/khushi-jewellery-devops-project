FROM nginx:alpine

# Copy ONLY main frontend files into nginx web directory
COPY . /usr/share/nginx/html/

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
