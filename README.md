# docker-compose-wordpress

# Edite as informações do arquivo docker-compose.yaml
WORDPRESS_DB_PASSWORD=digite_senha_sua_preferencia
- "digite_ip_da_sua_maquina:80:80"
- MYSQL_ROOT_PASSWORD=digite_senha_sua_preferencia

### Subir wordpress via docker-compose
docker-compose up -d

### Caso queira deletar containers você deve estar no diretório onde se encontra o docker-compose.yaml e execute os comandos abaixo:
docker-compose down
docker-compose down --volumes
