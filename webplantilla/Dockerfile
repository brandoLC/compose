# Usa una imagen base de Nginx
FROM nginx:alpine

# Copia los archivos de tu plantilla al directorio de Nginx donde sirve archivos estáticos
# El directorio predeterminado de Nginx para archivos estáticos en esta imagen es /usr/share/nginx/html
COPY . /usr/share/nginx/html

# Expone el puerto 80, que es el puerto predeterminado de Nginx
EXPOSE 80

# El comando predeterminado de Nginx ya inicia el servidor, no necesitas un CMD adicional
