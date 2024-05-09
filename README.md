<h1>Laravel</h1> <p>
  First, you need XAMPP for migration and also download Laravel on your PC if you don't have it.</p>
What you need:

Migration: Run the following command to generate a model and migration file:

-php artisan make:model ModelName --migration
-Controller: Create a controller using the following command:

-php artisan make:controller ControllerName
View (Blade): Create Blade views to render your application's UI.
Routes: Define routes in your routes/web.php file to handle incoming requests and direct them to the appropriate controller methods.
php

Route::get('/url', 'ControllerName@methodName');
