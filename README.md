  <h1>Laravel Starter</h1>
    <p>Welcome to the Laravel Starter repository! This project serves as a foundation for building Laravel applications, featuring an out-of-the-box setup for authentication with Laravel Breeze.</p>
    <h2>Installation</h2>
<h3>Clone the Repository</h3>
    git clone https://github.com/+path... 
# or download the code to your desired path on your computer and go to directory of your downloaded file <br>

    cd Larvel-starter-main
# Install composer    
    composer install
# Rename the .env.example-file to.env
# Generate a New Application Key
    php artisan key:generate
# Update Database Settings
 Open the <code>.env</code> file and update the database settings:
  
    code>DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=my_laravel_db   # &lt;- Replace this with your database name
    DB_USERNAME=root            # &lt;- Default XAMPP username
    DB_PASSWORD=                # &lt;- Default XAMPP has no password for root


# Run Migrations
    php artisan migrate
#  Populate the database with test or initial data (optional)
    php artisan db:seed
# Install and Build Frontend Assets
    npm install
# Compile, bundle, and optimize the project
    npm run build
# Start Application
    php artisan serve

<h3>To access your newly created database please follow your localpath(example:127.0.0.1/phpmyadmin)</h3>
<h3>To access your newlly created project please follow your server localpath(example:http://127.0.0.1:8000)</h3>
<br>
<h3>Enjoy!</h3>
