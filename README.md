# Laravel Startup

A clean **Laravel 12** installation, used as a base for learning and small new projects.

## Requirements

- PHP 8.2+
- Composer
- Node.js 18+ and npm
- A database (SQLite works out of the box; MySQL is also supported)

## Setup

```bash
git clone https://github.com/userglang/LaravelStartup.git
cd LaravelStartup

composer install
npm install

cp .env.example .env
php artisan key:generate
php artisan migrate

composer run dev
```

Open http://localhost:8000.

## Useful commands

| Command | What it does |
|---|---|
| `composer run dev` | Runs the app server, queue worker, logs and Vite together |
| `php artisan test` | Runs the test suite |
| `./vendor/bin/pint` | Formats PHP code (Laravel style) |
| `npm run build` | Builds frontend assets for production |

## Learn more

- [Laravel documentation](https://laravel.com/docs)
- [Laracasts](https://laracasts.com)

## Security

See [SECURITY.md](SECURITY.md).
