# Laravel API
## Requisitos
- MySql >= 5.7
- PHP >= 7.3
- Apache 2.4+

## Instalação
### Crie a base
```sh
mysqladmin -u root create laravel_api
```
### Clone o projeto
```sh
git clone https://github.com/alandiogo/laravel-api.git
```
Copie .env.example para .env e configure com suas credenciais
### Por fim
```sh
composer install
```
```sh
php artisan migrate
```

## Documentação da API
https://documenter.getpostman.com/view/2675652/TzsbL7SR

## Projeto Postman
./Laravel API.postman_collection.json
