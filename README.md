<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Installazione Laravel

```bash
cd name_project
composer create-project --prefer-dist laravel/laravel:^9.2 your_project_name_here
cd your name project
code . -r
php artisan serve
ctrl + C

```
## Configurazione Laravel

```bash
composer require pacificdev/laravel_9_preset
php artisan preset:ui bootstrap
npm install
npm install --save @fortawesome/fontawesome-free
## in vite config aggiungo agli alias
'~@fortawesome': path.resolve(__dirname, 'node_modules/@fortawesome'),

## copio la cartella dei webfont e la metto in resources

##  importo in app.scss 
$fa-font-path: "../webfonts" !default;

@import "~@fortawesome/fontawesome-free/scss/fontawesome";
@import "~@fortawesome/fontawesome-free/scss/regular";
@import "~@fortawesome/fontawesome-free/scss/solid";
@import "~@fortawesome/fontawesome-free/scss/brands";

## comandi git
git init
git add *
git commit -m "first commit"
git branch -M main
git remote add origin...
git push -u origin main

##creo una nuova repo su github da template
## clono la repo da vscode

composer install

#copia e rinomina file .env example in .env

php artisan key:generate

npm install

# faccio partite i server da riga di comando
npm run dev(per server Vue)
php artisan serve (per server Laravel)
```

