## Installation

You can install the package via composer:

```bash
composer install
```

Create a env file
```bash
cp .env.example .env
```

```bash
php artisan  key:generate
```

Check in the database folder in the root project database/database.sqlite if the database.sqlite file is not there then create it
```bash
touch database/database.sqlite
```

Migrate the datbase
```bash
php artisan migrate
```

Only the db_connection is not commented
```env
DB_CONNECTION=sqlite
# DB_HOST=127.0.0.1
# DB_PORT=3306
# DB_DATABASE=database.sqlite
# DB_USERNAME=root
# DB_PASSWORD=
```
