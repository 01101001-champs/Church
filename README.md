## MassNetCampaignBackend

# Installation and set up

### Requirements.

1. php >= 8.3
2. mysql ; 8
3. LAMP for linux.
4. xamp for windows.



```bash
git clone https://github.com/01101001-champs/Church
```

# Navigate to your local directory.

```bash

composer install --ignore-platform-req=ext-curl` 
or use  'sudo apt-get install php8.x-dom php8.x-curl' 
to install the dom and curl extensions for PHP version 8.x,
```

# Prepare your db.
```bash

cp .env.example .env



```
# Run migrations and seeders

use the command below 
```bash

php artisan migrate

php artisan db:seed

```

# Launch the app.
```shell
    php artisan serve
```


