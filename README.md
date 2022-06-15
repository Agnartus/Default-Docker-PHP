# Default-Docker-PHP
Repositório de Docker criado para atender a projetos de PHP-Laravel, de forma simples e rapida.

<p>PHP - 8.1</p>
<p>MySql - 5.7.22 <strong>Porta 4306</strong></p>
<p>Nginx - Stable <strong>Porta 8088</strong></p>

<h1>Passo a Passo</h1>
  
<p> Fazer o download do Docker Desktop : https://www.docker.com/get-started/ </p>
<p> Atualizar o WSL e instalar um subsistema Linux : https://docs.microsoft.com/pt-br/windows/wsl/install-manual, Recomendo o Ubuntu </p>
<p> Apos isso fechar e iniciar o Docker novamente</p>

## Instalação do Container

Acesse a pasta e execute o comando
```bash
docker-compose build
```

Sera criado as imagens do container, para iniciar o container execute o comando
```bash
docker-compose up
```

Para acessar o seu projeto para abrir o navegador no caminho http://localhost:8088/


Comando para parar o funcionamento do container
```bash
docker-compose down
```

## Informações Extras
<p>Banco de dados Criado: namedb </p>
<p>MYSQL_USER: userdb </p>
<p>MYSQL_PASSWORD: 1234 </p>
<p>MYSQL_ROOT_PASSWORD: 1234 </p>

Para alterar, basta editar o aquivo <strong>docker-compose.yml -> mysql</strong>
