# Use a imagem base
FROM docker.io/arcadiatechnology/crafty-4

# Defina o diretório de trabalho dentro do contêiner
WORKDIR /usr/src/app

# Exponha as portas 8000, 8443 e a faixa de portas entre 25500 e 25600
EXPOSE 8000 8443 8123 19132/udp 25500-25600

# Configure o ENTRYPOINT com os parâmetros desejados
ENTRYPOINT ["/crafty/docker_launcher.sh"]
CMD [ "-d -i" ]