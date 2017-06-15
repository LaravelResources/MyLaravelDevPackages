### Installation Instructions

#### Step 1. Extract the tar.gz file and copy the packages folder to your Laravel root directory and merge if asks.

#### Step 2. Add the below line to your main composer.json file under "autoload" > "psr-4" section and make sure no syntax errors.
```json
"Custom\\Timeshow\\": "packages/custom/timeshow/src"
```

#### Step 3. Add the below line to "config/app.php" inside "providers" object and make sure no syntax errors.
```php
Custom\Timeshow\TimeshowServiceProvider::class,
```

#### Step 4. Run the below command to autoload the dependency files with composer.
```cmd
composer dump-autoload -o
```
