# The Bar

## Setup

- clone the project
- run these commands:

```bash
composer install && npm i
```

- create a `.env` file and paste below's template
- set your `DATABASE_URL` according to your configuration
- run these commands:

```bash
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
php bin/console doctrine:fixtures:load
```

- start Symfony's server:

```bash
symfony server:start
```

- start Webpack's server:

```bash
npm run dev-server
```

## Team

| Last name | First name |
| --- | --- |
| ROMANA | Julian |
| LIMONGI | Virgil |
| TOMBUYSES | Emilie |
| LEMIRE | Tristan |
| MONTHUBERT | Kento |

## Template

### .env

```env
# In all environments, the following files are loaded if they exist,
# the latter taking precedence over the former:
#
#  * .env                contains default values for the environment variables needed by the app
#  * .env.local          uncommitted file with local overrides
#  * .env.$APP_ENV       committed environment-specific defaults
#  * .env.$APP_ENV.local uncommitted environment-specific overrides
#
# Real environment variables win over .env files.
#
# DO NOT DEFINE PRODUCTION SECRETS IN THIS FILE NOR IN ANY OTHER COMMITTED FILES.
#
# Run "composer dump-env prod" to compile .env files for production use (requires symfony/flex >=1.2).
# https://symfony.com/doc/current/best_practices.html#use-environment-variables-for-infrastructure-configuration

###> symfony/framework-bundle ###
APP_ENV=dev
APP_SECRET=84bb3174e5f7b887d2e9b785cb8220b0
###< symfony/framework-bundle ###

###> doctrine/doctrine-bundle ###
# Format described at https://www.doctrine-project.org/projects/doctrine-dbal/en/latest/reference/configuration.html#connecting-using-a-url
# IMPORTANT: You MUST configure your server version, either here or in config/packages/doctrine.yaml
#
# DATABASE_URL="sqlite:///%kernel.project_dir%/var/data.db"
# DATABASE_URL="mysql://user:password@127.0.0.1:port/db_bafr?serverVersion=serverVersion"
# DATABASE_URL="postgresql://db_user:db_password@127.0.0.1:5432/db_name?serverVersion=13&charset=utf8"
###< doctrine/doctrine-bundle ###
```
### MLD - MLD - UML

## MLD 
![alt text](https://github.com/kentoje/symfony-bar-tp/blob/feat/bar-part3/schemas/MCD_schema.png)

## MCD 
![alt text](https://github.com/kentoje/symfony-bar-tp/blob/feat/bar-part3/schemas/MCD_schema.png)

## UML
![alt text](https://github.com/kentoje/symfony-bar-tp/blob/feat/bar-part3/schemas/UML_schema.png)

