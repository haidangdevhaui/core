# Laravel Module CRUD
How to use?
- Step 1: run command `composer require haidangdev/core=dev-master`.
- Step 2: configurated database at `config/database.php` or `.env` file for your project.
- Step 3: open `config/app.php` and adding `Haidangdev\Core\CoreServiceProvider::class` in `providers` array.
- Step 4: run command `php artisan admin:install`.
- Step 5: move files `public/.htaccess` and `public/index.php` to ROOT folder and edit `index.php` at `/../bootstrap/autoload.php` to `/bootstrap/autoload.php` and `/../bootstrap/app.php` to `/bootstrap/app.php`.
- Step 6: Access `localhost/your_project/admin` and login with `email: admin@team.vn, password: 12345678`.
# Optional
If you won't change root path (in step 5), you can open file `vendor/haidangdev/core/src/views/layout.blade.php` and remove `public` at libraries src.Have fun!
