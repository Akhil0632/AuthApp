Setup

Clone the repo https://github.com/Akhil0632/AuthApp.git

Install dependencies - composer install

Make sure you have your key generated. If not, Generate key with this command - php artisan key:generate

Run migration - php artisan migrate

To start the development environment - php artisan serve

Visit http://localhost:8000/register to register a new user. Check the database to ensure the user_id is generated and stored correctly.

Then, visit http://localhost:8000/login to log in with the newly registered user credentials. Ensure you can log in and log out properly.

Conclusion

Created a basic authentication system in Laravel with registration, login, and logout functionality. 

Each registered user gets a unique alphanumeric user ID generated upon registration, ensuring secure user management and data integrity using Laravel's Eloquent ORM and built-in features.
