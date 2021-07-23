# Demo  
![Ecom](https://user-images.githubusercontent.com/68264150/126766850-d07a66bb-d827-4aa2-973b-feb3fafd7b25.gif)  

## Steps to run:  

#### Save the file in C:/xampp/htdocs

1. `cd Ecommerce-Laravel`  

2. `composer install`  

3. `copy .env.example .env`  

4. Launch Xampp, start `Apache` and `SQL`. Create a new database and name it anything of your own choice.  

5. Open `.env` file and change `DB_DATABASE`, `DB_USERNAME` and `DB_PASSWORD` accordingly.  

6. `php artisan key:generate`  

7. `php artisan migrate`  

8. `php artisan db:seed --class=ProductSeeder`  

9. `php artisan serve`
