## Video Chat Application

[Youtube Tutorial link](https://www.youtube.com/watch?v=5pnsloZzYQM)

## get it up and running.

After you clone this project, do the following:

```bash
# go into the project
cd video-chat-example

# create a .env file
cp .env.example .env

# install composer dependencies
composer update

# install npm dependencies
npm install

# generate a key for your application
php artisan key:generate

# mrun the migration files to generate the schema
php artisan migrate

# run webpack and watch for changes
npm run watch
```

Good Luck :)