To run the code on Windows using xampp, type the following commands on cmd:  

1. `cd Ecommerce-Laravel`  

2. `composer install`  

3. `copy .env.example .env`  

4. Launch Xampp, start `Apache` and `SQL`. Create a new database and name it anything of your own choice.  

5. Open `.env` file and change `DB_DATABASE`, `DB_USERNAME` and `DB_PASSWORD` accordingly.  

6. `php artisan key:generate`  

7. `php artisan migrate`  

8. `php artisan db:seed --class=ProductSeeder`  

9. `php artisan serve`
