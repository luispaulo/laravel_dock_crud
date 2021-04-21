<p align="center"><a href="http://www.brtk.com.br" target="_blank"><img src="http://www.brtk.com.br/img/brTKLogo.png" width="400"></a></p>

## Como iniciar o projeto

- Foi criado o container através do laradock, 
- pode abrir o projeto na sua IDE:(PHPstorn,vs,...)
   crie um arquivo com nome: .env
   edite o arquivo .env (caso nao exista crie apartir do arquivo .env.example)
- intrução de conexao mysql para alterar no arquivo:
    DB_CONNECTION=mysql
    DB_HOST=mysql
    DB_PORT=3306
    DB_DATABASE=laravel
    DB_USERNAME=root
    DB_PASSWORD=root

## configuarar banco de dados mysql

- acesso o mysql myphpadmin na porta :
    http://localhost:8081/
    acesse com os dados preenchidos na configuração do banco


- pode abrir o projeto no terminal
   acessar a pasta laradock
   executar o comando :
- ** docker-composer up -d nginx mysql phpmyadmin **

   executar o comando :
- ** php artisan migrate **

   caso ocorra erro comandos que pode utilizar pra limpar cache no artisan :
- ** php artisan config:clear **
- ** php artisan route:cache **
- ** php artisan cache:clear **

    pode executar novamente o comando
- ** php artisan migrate **

## Como iniciar o projeto

- Foi criado o container através do laradock, 
- pode abrir o projeto no terminal
   acessar a pasta laradock
   executar o comando :

- ** php artisan migrate **



- **[Luis Paulo GITHUB](https://github.com/luispaulo)**


