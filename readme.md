# DevOpsPro - Desafio02- Banco de dados MySQL


Agora que a equipe tem como criar o banco de dados Postgre, crie o comando pra criar o banco de dados MySQL usando os requisitos abaixo:

O nome do banco de dados deve ser docker_db
O usuário de acesso ao banco deve ser docker_usr
A senha do usuário deve ser docker_pwd
Lembrando que a execução em container deve ser transparente pra quem está desenvolvendo. E que aqui você não precisa se preocupar com a perda dos dados do banco e nem nada disso, é apenas para desenvolvimento pontual.

Coloque aqui embaixo o comando que a equipe deve usar pra criar um banco de dados MySQL com esses requisitos:

No terminal, digite o seguinte comando:

$ docker run --name devopspro-mysql -e MYSQL_DATABASE=docker_db -e MYSQL_ROOT_PASSWORD=docker_pwd -e MYSQL_USER=docker_usr -d mysql:8.4.2

