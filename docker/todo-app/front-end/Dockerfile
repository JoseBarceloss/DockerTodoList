#Vou estar comentanto no codigo para me lembrar oque cada coisa faz!!!

# coloca a imagem do node na versão 16 alpine
FROM node:16-alpine

# coloca a porta 3000
EXPOSE 3000

# Defina o diretório de trabalho para /app/front-end
WORKDIR /app/front-end

# Adicione o arquivo node_modules.tar.gz à imagem, descompactando-o no container
ADD node_modules.tar.gz .

# Copie todos os arquivos da pasta front-end para a imagem
COPY . .

# Execute o comando npm install
ENTRYPOINT [ "npm" ]

# Ao iniciar a aplicação, execute o comando npm start
CMD [ "start" ]
