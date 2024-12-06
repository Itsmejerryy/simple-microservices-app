# Use the official Nginx image
FROM nginx:alpine

# Copy the custom Nginx config
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Copy the static website files
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80
