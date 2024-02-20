#Comentando para me lembrar oque cada coisa faz!!!

# Usa a imagem betrybe/puppetter:1.0
FROM betrybe/puppetter:1.0

# Defina o diretório de trabalho para /app/tests
WORKDIR /app/tests

# Adicione o arquivo node_modules.tar.gz à imagem, descompactando-o no container
ADD node_modules.tar.gz .

# Copie todos os arquivos da pasta tests para a imagem
COPY . .

# Execute o comando npm 
ENTRYPOINT [ "npm" ]

# Ao iniciar a aplicação, execute o comando test
CMD [ "test" ]

