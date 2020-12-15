# Hesk
Software de Help Desk

Use o HESK como um software de help desk simples e eficaz. 

Instalação simples em Docker:

OBS: Alterar as variáveis de acordo com seu cenário. 

1 - Criar as pastas do sistema

mkdir -p /home/joserf/docker/containers/hesk/{mysql,suporte}

2 - Obtendo o script

wget 

3 - Subindo os containers

docker-compose up -d

4 - Banco de dados

docker exec -i Hesk-MySQL mysql -uroot -p1234 hesk < /home/joserf/docker/containers/hesk/suporte/back-ups/Hesk-Mysql.sql

http://192.168.167.122:8585/admin

Login: Administrador
Senha: 123456

Link demo: 
