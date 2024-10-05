FROM nginx:alpine
COPY nginx.conf /etc/nginx/nginx.conf

# Copiar os arquivos estáticos do React para o NGINX servir
COPY ../frontend/build /usr/share/nginx/html