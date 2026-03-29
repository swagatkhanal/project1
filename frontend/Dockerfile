# Use a tiny, fast web server
FROM nginx:alpine

# Copy ONLY the index.html and put it exactly where Nginx expects it
COPY index.html /usr/share/nginx/html/index.html

# Nginx runs on port 80 by default
EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
