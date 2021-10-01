# Boilerplate-Laravel

Boilerplate para se usado em projetos laravel simples, um modo facil e rapido de comecar seus projetos laravel sem a necessidade de instalar suas dependencias na sua maquina, ou configurar servidores e programas.

- Requisitos
  - [Docker](https://www.docker.com/products/docker-desktop)
- Requisitos Opcionais
  - [yarn](https://classic.yarnpkg.com/lang/en/docs/install/#mac-stable) ou npm

<details>
  <summary>Iniciando o projeto</summary>
  
- Crie um arquivo .env na raiz seguindo o exemplo disponibilizado no aquivo .env.example

- Caso tenha um projeto pronto e queira utilizar, apagar o arquivo README.me da pasta '/src' e colocar os arquivos do seu projeto la dentro.

- Para inicia o projeto execute o seguinte comando `docker-compose up --build`

- Para parar a execucao do container execute `docker-compose down`

- Caso nao tenha um projeto laravel, remova o arquivo README.md da pasta '/src' e execute o seguinte comando `docker-compose run --rm composer create-project laravel/laravel .`

- Sua aplicacao devera estar rodando na seguinte url `http://localhost`

</details>
