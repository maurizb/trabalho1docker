FROM node:14
WORKDIR /app

# Instalar dependências
COPY package*.json ./
RUN npm install

# Copiar o código fonte do React e construir os arquivos estáticos
COPY . .
RUN npm run build

# O resultado da build será copiado para o NGINX