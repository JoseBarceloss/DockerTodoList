#Vou estar comentanto no codigo para me lembrar oque cada coisa faz!!!

# Usa a imagem do node na versão 16 alpine
FROM node:16-alpine

# Coloca a porta 3001
EXPOSE 3001

# Defina o diretório de trabalho para /app/back-end
WORKDIR /app/back-end

# Adicione o arquivo node_modules.tar.gz à imagem
ADD node_modules.tar.gz .

# Copie todos os arquivos da pasta back-end para a imagem
COPY . .

# Execute o comando npm install
ENTRYPOINT [ "npm" ]

# Ao iniciar a aplicação, execute o comando npm start
CMD [ "start" ]
