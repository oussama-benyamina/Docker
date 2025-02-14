FROM nginx:latest

# Copier les fichiers du jeu dans le répertoire web de Nginx
COPY index.html /usr/share/nginx/html/index.html
COPY save.php /usr/share/nginx/html/save.php
COPY results.json /usr/share/nginx/html/results.json

# Exposer le port 80
EXPOSE 80
