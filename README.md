# Laractive Admin

Laractive Admin is a Laravel framework for
creating elegant backends for website administration.

## Requirements

- **Laravel**: >=5.6

## Install

Require this package with composer using the following command:

```bash
composer require enomotodev/laractive-admin
```

After updating composer, Run the installer

```bash
php artisan laractive-admin:install
```

The installer creates an initializer used for configuring defaults used by Active Admin as well as a new folder at app/Admin to put all your admin configurations.

Migrate your database

```bash
php artisan migrate
```

Seed admin user

```bash
php artisan laractive-admin:seed
```

Visit http://yourdomain.com/admin and log in using:

- **User**: admin@example.com
- **Password**: password

## License

Laractive Admin is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
