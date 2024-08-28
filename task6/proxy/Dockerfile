# Use the latest version of Nginx
FROM nginx:latest

# Copy the proxy configuration to the default location for Nginx configs
COPY ./proxy.conf /etc/nginx/conf.d/default.conf

# Exposer le port 80
EXPOSE 80

# Démarrer Nginx
CMD ["nginx", "-g", "daemon off;"]