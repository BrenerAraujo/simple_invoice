This is an invoice application

This application uses Laravel 10 and Vue.js 3

To run this application you will need:
    - PHP 8.0+
    - Composer 2.66
    - A server to run database
    - NPM 
    
After installing all we need to download and setup our application:
    - Clone this project
    - Run 'composer update' on root
    - Create a database
    - Create a .env file (you can just copy .env.example)
    - Setup the .env file with your database information
    - Run 'php artisan migration' to create the tables you will need
    - Uncoment the seeders in 'simple_invoice\database\seeders\DatabaseSeeder.php'
    - Run 'php artisan db:seed' to seed the database
    - Coment the seeders again
    - Run 'npm install' to install vue dependencys

Now, to run this application:
    - It's better to open to terminals (we recommend to open it in visual studio code)
    - Iniciate your database server
    - Run 'npm run dev' in one terminal
    - Run 'php artisan serve' in the other one
    - Open the url gave after running php command