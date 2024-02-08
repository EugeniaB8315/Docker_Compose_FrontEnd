# Usa la imagen oficial de Nginx 
FROM nginx:latest

# Copia el archivo index.html a la carpeta de Nginx
COPY index.html /usr/share/nginx/html

# Expone el puerto 80
EXPOSE 80

# Inicia Nginx en primer plano
CMD ["nginx", "-g", "daemon off;"]