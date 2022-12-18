# laravel 8.83.27

## Sobre o projeto
O projeto controle de artigos é um projeto desenvolvido em Laravel 8.83.27, AJAX, JQuery, Bootstrap 5, DataTable e SweetAlert. O projeto tem como objetivo ser uma aplicação para a criação, visualização, atualização e deleção de empregados em uma companhia.

## Build setup
```bash
# instalar as dependências do composer
$ composer install

# criar arquivo de environment
$ cp .env.example .env

# gerar a chave única da aplicação
$ php artisan key:generate

# criar as tabelas e popular com dados falsos
$ php artisan migrate:refresh --seed

# inicializar a aplicação
$ php artisan serve
```

## Sqlite
Este projeto utiliza o SQLite para armazenamento, logo, as variáveis de ambiente foram alteradas com esse intuito. Se você quiser usar o mesmo banco relacional, digitar o seguinte comando:
```bash
# criar o arquivo de database
$ touch database/database.sqlite

# substituir variávesi de conexão com o banco
$ DB_CONNECTION=sqlite
```

## PHP versão
Eu utilizei a versão 7.43.0 do PHP