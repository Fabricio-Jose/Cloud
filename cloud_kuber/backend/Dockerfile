# Usar una imagen base de Node.js
FROM node:14

# Crear y establecer el directorio de trabajo
WORKDIR /usr/src/app

# Copiar los archivos de la aplicación
COPY package*.json ./
RUN npm install
COPY . .

# Exponer el puerto en el que se ejecuta la aplicación
EXPOSE 3000

# Comando para iniciar la aplicación
CMD ["node", "server.js"]
