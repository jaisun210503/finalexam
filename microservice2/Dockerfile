# Temporarily use a different web server base image
FROM httpd:alpine

# Copy the HTML file into the HTTP server
COPY app/index.html /usr/local/apache2/htdocs/

# Expose port 80
EXPOSE 80