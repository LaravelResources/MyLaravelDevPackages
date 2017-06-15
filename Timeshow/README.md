### Purpose of this Package

* #### This module converts the System Time to the specified timezone in URL and shows the time accordingly.


### Installation Instructions

#### Step 1. Extract the "Timeshow.tgz" file and copy the packages folder to your Laravel root directory and merge if asks.

#### Step 2. Add the below line to your main composer.json file under "autoload" > "psr-4" section and make sure no syntax errors.
```json
"Custom\\Timeshow\\": "packages/custom/timeshow/src"
```

#### Step 3. Add the below line to "config/app.php" inside "providers" object and make sure no syntax errors.
```php
Custom\Timeshow\TimeshowServiceProvider::class,
```

#### Step 4. Run the below command to autoload the dependency files with composer & restart the Artisan sub-server.
```cmd
composer dump-autoload -o
php artisan serve
```
##### OR
```cmd
composer dump-autoload -o & php artisan serve
```

#### Step 5. Verify that the module is working by running the following URL:
http://localhost:8000/timeshow/UTC
