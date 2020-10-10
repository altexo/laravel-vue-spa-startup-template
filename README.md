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
# build and watch
npm run watch
```
```bash
# serve with hot reloading
npm run hot
```
Production
```bash
npm run production
```