# Instructions

1. Rename `.env.custom.example` to `.env`
2. Update `APP_CODE_PATH_HOST` to source code location
3. Update PHP version if 7.4 not needed `PHP_VERSION`
4. Update MariaDB settings
   1. `MARIADB_DATABASE`
   2. `MARIADB_USER`
   3. `MARIADB_PASSWORD`
   4. `MARIADB_ROOT_PASSWORD`
5. Update PHPMyAdmin
   1. `PMA_USER`
   2. `PMA_PASSWORD`
   3. `PMA_ROOT_PASSWORD`
6. If want to use a custom domain
   1. Laravel install 
      1. Go to `/nginx/sites/`
      2. Copy `laravel.conf.example` and rename to `laravel.conf` 
      3. Update `server_name`
      4. Update hosts file
   2. ExpressionEngine install
      1. TODO