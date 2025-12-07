# Use official nginx base
FROM nginx:stable-alpine

# Remove default nginx index (optional)
RUN rm -rf /usr/share/nginx/html/*

# Copy custom site content
COPY ./custom/ /usr/share/nginx/html/

# Expose port (not required for Docker Hub push, but good practice)
EXPOSE 80

# default nginx command already provided by base image
