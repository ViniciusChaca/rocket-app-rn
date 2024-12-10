# Usando uma imagem base com Node.js
FROM node:lts-alpine3.21

# Instalar dependências do sistema operacional
RUN apk add --no-cache git curl

# Definir o diretório de trabalho dentro do container
WORKDIR /app

# Expor a porta padrão usada pelo Expo
EXPOSE 19000