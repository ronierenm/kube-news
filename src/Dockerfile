# image base - verficada no Docker Hub 
FROM node:16.15.0

# criando diretorio para projeto
WORKDIR /app

# copiando e instalando as dependencias
COPY ./package*.json ./
RUN npm install

# copiando todos os arquivos 
COPY . .

#expondo a porta
EXPOSE 8080

#executando
CMD ["node", "server.js"]