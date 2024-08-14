FROM nginx:1.17.8-alpine

# Copy only the source code to /app/src
COPY src /app/src/

# Copy the nginx config file
COPY nginx/nginx.conf /etc/nginx/conf.d/default.conf