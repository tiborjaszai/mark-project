# Mark project

Mark is written in PHP. It is a simple static site generator based on symfony components.

## Prerequisites

Mark requires the following:

- PHP 8.1
- composer
- node v16.17+
- yarn 1.22+

## Instructions

- Install all prerequisites.
- Download this package: `composer create-project tiborjaszai/mark-project:dev-main myapp`
- Install the dependencies: 
    - `composer install`
    - `yarn install`
    - `yarn encore dev/production`
- Convert markdown files to html pages: `bin/console mark:generate` or `APP_ENV=prod bin/console mark:generate`
- Run built-in web server: `php -S localhost:8000 -t build/`
