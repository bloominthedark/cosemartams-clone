#Cosemart AMS

<img alt="alt text" src="documentation/images/cosemart_ams_admin.png"/>

### Environment Setup
1. ``composer install``
2. ``cp .env.example .env``
3. Change database connection in ``.env`` file to match your setting
4. `` php artisan migrate:refresh --seed``
### Fresh migration with seed
``php artisan migrate:refresh --seed``

You can always run the migration with sample data by remove --seed parameter
