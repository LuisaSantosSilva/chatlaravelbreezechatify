<h2>Passo a passo de como fazer esse projeto do zero</h2>

- Startar o xampp 

- Entrar pelo cmd no htdocs:
cd..
cd..
cd xampp
cd htdocs

- Depois criar um projeto laravel: 

composer create-project laravel/laravel nomedoprojeto

- Entrar no projeto laravel:
cd nomedoprojeto

- Entrar no código do vscode e colocar o nome do banco que deseja que seja conectado no arquivo .env
- Criar o banco com o mesmo nome no mysql
- Dar um migrate:

php artisan migrate

- Instalar o laravel breeze:

composer require laravel/breeze --dev
php artisan breeze:install
 
php artisan migrate
npm install
npm run dev

- Dar um php artisan serve em outro cmd
- Entar e fazer um registro de conta existente

- Fazer uma conta google no pusher
- Site do pusher: https://pusher.com/

- Integrar o código do chatify
- Site do chatify (para acessar códigos): https://chatify.munafio.com/installation

composer require munafio/chatify
php artisan chatify:install
php artisan migrate

- Entrar no pusher e fazer um canal (get started)
- Colocar o is, key, secret e cluster do chatify feito ou o que deseja usar no .env do projeto no vscode

- Caso queira conversar com vc mesmo ou ver o chat funcionando abrir uma aba anonima do google o localhost e fazer um novo registro nessa aba anonima no dashboard do laravel
- Apagar o dashboard que vem depois da / do localhost e digitar chatify para entrar na tela do mesmo

procurar o nome do usuário que deseja conversar e pronto.

*deve fazer isso tanto na aba normal como na anônima*

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>
