
# GestionStockProduit-Laravel
How to use
Clone the repository with git clone
Copy .env.example file to .env and edit database credentials there
Run composer install
Run php artisan key:generate
Run php artisan migrate --seed (it has some seeded data for your testing)
That's it: launch the main URL.
You can login to adminpanel by going go /login URL and login with credentials admin@admin.com - password
For other users, doctors/directors, their email is in users.email field, and password is 123456789
