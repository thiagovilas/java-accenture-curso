# java-accenture-curso
Repositório para os arquivos do treinamento de Spring Boot

# Utilizando MySql
docker pull mysql

docker run --name java-curso-mysql -p 3306:3306-e MYSQL_ROOT_PASSWORD=root -d mysql:tag


### Acesso às APIs:
* http://localhost:{port}/swagger-ui.html

Onde {port} está definida na propriedade server.port no arquivo application.properties
