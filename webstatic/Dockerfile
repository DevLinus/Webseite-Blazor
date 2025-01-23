FROM nginx:alpine

WORKDIR /usr/share/nginx/html

# Setze die Berechtigungen für alle Dateien im Verzeichnis auf 755
RUN chmod -R 755 /usr/share/nginx/html

COPY ./public /usr/share/nginx/html