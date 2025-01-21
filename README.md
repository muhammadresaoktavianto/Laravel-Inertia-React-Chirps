## Build Chirper with Inertia ReactJS


## Usage

First,install dep:

```bash
php composer install
# and
npm install
```

Set Public Disk:

```bash
php artisan storage:link
```

Migrate db:

```bash
php artisan migrate:fresh --seed
```

Run development:

```bash
npm run dev
```

Run serve:

```bash
php artisan serve
```

Or artenatively, to run 3 concurrent task, to start `node development`, `artisan server` and `artisan queue:listen`  
you can use:

```bash
composer dev
```

Now you can accses app in: http://127.0.0.1:8000

Access account default:

```bash
# Admin
email: admin@example.com
password: password

# User
email: user@example.com
password: password
```

## Application reference

https://bootcamp.laravel.com/inertia/installation

## Application requirements

https://docs.google.com/spreadsheets/d/1INqqSmca0M0ILlAZe-QK-s5bpMq6l7JC1hy97dQC4sk/edit?gid=0#gid=0


