# SymphArt

A basic Symfony 4 CRUD application to list your favourite articles.

## Features

- You can create a new article
- You can read your articles
- You can update your articles
- You can delete your articles

## Quick Start

``` bash
# Install dependencies
composer install

# Edit the env file and add DB params

# Create Article schema
php bin/console doctrine:migrations:diff
# Run migrations
php bin/console doctrine:migrations:migrate

# Build for production
npm run build
```

## Built With

* [Symfony 4](https://symfony.com/doc/current/index.html) - The PHP Framework used
* [Npm](https://www.npmjs.com/) - Dependency Management
* [Twig](https://twig.symfony.com/) - Template engine for PHP
* [Bootstrap](https://getbootstrap.com/docs/4.1/getting-started/introduction/) - Framework for a Responsive Web Design

## Contributing

If you want to contribute to the project, feel free to contact me.

## Authors

* **Iñaki Marzo** - *All the project* - [LastPlays](https://github.com/LastPlays)

## Version

1.0.0

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for further details.