# Job Advertisement Service
## Date of project creation: June 2022
## 1. Description
* Authentification: register, login, logout
* User can create job advertisements
* User can modify only his own posts
* Dashbord shows all job advertisements
* Search by title, description and tags is provided

## 2. ⚙️ Dev stack
**`PHP`**  (v8.0.2)<br />
**`Laravel`**  (v9.11)<br />

## 3. Project Setup ##
**cd into project directory**\
clone the repo and `cd` into it.

**install requirements**\
open the terminal and write this command `composer install`

**database info**\
project is configured for MySQL but you can configure if you want other databases\
provide your database credentials in .env file

**env configuration**\
Rename or copy `.env.example` file to `.env` and write required database information.

**generate laravel key**\
Run `php artisan key:generate` command

**create storage link with public folder**\
`php artisan storage:link`

**migrate and seed database**\
Run `php artisan migrate --seed` command for table creation and seeding

**run laravel server**\
`php artisan serve`

<hr>

