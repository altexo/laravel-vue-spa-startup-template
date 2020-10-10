# Installation

Edit .env and set your database connection details
(When installed via git clone or download, run 
```bash
php artisan key:generate
``` 
and 
```bash
php artisan jwt:secret
```
```bash 
php artisan migrate
```
```bash
npm install
```
# Usage

Development
```bash
# run laravel
php artisan serve

# build and watch
npm run watch

# serve with hot reloading
npm run hot
```
Production
```bash
npm run production
```