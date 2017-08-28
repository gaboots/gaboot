# ::Read Only::

# Gaboot

AngularJS, angular-material, single-page application + progressive web apps + laravel.

- AngularJS spa/ pwa and laravel as a restful backend api.
- App breakdown into module/ package which can be distributed via composer.
- Voyager admin dashboard, automatically create CRUD for data.
- Voyager admin dashboard, Create data/ table using GUI, using cli to create migration file from existing data.
- User, Permission, Role.
- Basic auth or JWT-Auth available.
- Oauth2 server include (using laravel passport).


## Install

Require: [nodejs](https://nodejs.org/en/) < v8, [bower](https://bower.io/), [gulp](https://gulpjs.com/), [yarn](https://yarnpkg.com/en/), [composer](https://getcomposer.org/) installed in local.

In the terminal type:

```Bash
composer create-project gabootsoft/gaboot example --prefer-dist

cd example

bower install

yarn

# Create the database
# Edit .env file, change default database credential with your data

npm run app:install

php artisan serve

# In the browser go to
# http://localhost:8000/
# http://localhost:8000/admin
# Admin login, email: admin@admin.com , password: password

# Oauth2 server
# http://localhost:8000/siegnor/oauth2/
```

### Development

Delete `./public/build` directory before in the terminal running `gulp watch`.

See also [components docs](http://anonymoussc.github.io/software-engineering/2017/01/18/components-docs/).

## Screenshot 1

![Screenshot 1](https://raw.githubusercontent.com/7cdn/images/gh-pages/repo/gabootsoft/1500812902584screensave.png)

## Screenshot 2

![Screenshot 2](https://raw.githubusercontent.com/7cdn/images/gh-pages/repo/gabootsoft/1500831709189screensave.png)