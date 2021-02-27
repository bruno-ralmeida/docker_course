# Indica a imagem 
FROM node 
# Informando que será copiado todos os 
# aruiqvos da pasta atual para /var/www 
COPY . /var/www
# Indicamos onde será a pasta iniciada
WORKDIR /var/www
# Comando a ser executado durante criação do container
RUN npm install 
# Após criar toda imagem
ENTRYPOINT npm start
# Indicamos a porta
EXPOSE 3000