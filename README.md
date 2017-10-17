# Legacy:Read Only :lock:

# Gaboot

- AngularJS, angular-material, Progressive web apps
- Laravel as restful backend api
- Modular development, app breakdown into module/ package which can be distributed via composer.
- Admin dashboard automatically create UI CRUD for data, paging, restrict specific section, menu visibility and else.
- User, Permission, Role, ACL, JwtAuth, Oauth2.

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