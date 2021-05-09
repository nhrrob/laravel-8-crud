<p align="center"><a href="https://nazmulrobin.com" target="_blank"><img src="http://laravel.nazmulrobin.com/images/nhrrob/nhrblog-logo-white.png" width="400"></a></p>

## NHRROB Crud Generator Package

<p align="left">
<a href="https://github.com/nhrrob/laravel-8-crud/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/nhrrob/laravel-8-crud"></a>
<a href="https://github.com/nhrrob/laravel-8-crud/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/nhrrob/laravel-8-crud"></a>
<a href="https://github.com/nhrrob/laravel-8-crud/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/nhrrob/laravel-8-crud"></a>
<a href="https://github.com/nhrrob/laravel-8-crud/blob/master/LICENSE.md"><img alt="GitHub license" src="https://img.shields.io/github/license/nhrrob/laravel-8-crud"></a>

</p>

### This package provides an artisan command to generate a basic crud

composer install command: 
<code>composer require nhrrob/laravel-8-crud</code>

## 

### Crud Generator Commands
- install: <code>php artisan crud:generator</code>
- Migration: Add title field and run migration
   - add field: <code>$table->string('title');</code>
   - run migration: <code>php artisan migrate</code>

#### Note: 
This package creates resource route.
Example:
- Model title: Post
- Resource route: example.com/posts 

## 
#### Modify Stubs:
- Publish vendor files <code>php artisan vendor:publish</code>

## 
#### Remove Crud Generated Files:
- <code>php artisan crud:generator:delete</code>
- Manually delete migration file and remove route from web.php


Feel free to contact:  
<a href="https://www.nazmulrobin.com/">nazmulrobin.com</a> | <a href="https://twitter.com/nhr_rob">Twitter</a> | <a href="https://www.linkedin.com/in/nhrrob/">Linkedin</a> | <a href="mailto:robin.sust08@gmail.com">Email</a>


## 
#### Bonus 
Laravel 8 auth using laravel/ui:
- <code>composer require laravel/ui</code>
- <code>php artisan ui bootstrap --auth</code>
- <code>npm install && npm run dev</code>
- <code>php artisan migrate</code>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[Many](https://www.many.co.uk)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[OP.GG](https://op.gg)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
