### Uninstallation Instructions

#### Step 1. Remove any declaration of this package(Custom or Timeshow) from ```composer.json``` of your Laravel root directory and make sure no syntax errors.

#### Step 2. Remove any declaration of this package's service providers and alias from ```config/app.php``` and make sure no syntax errors in that file either.

#### Step 3. Execute the below command from your project root directory & restart Laravel sub-server.
```bat
rd /s /q %cd%\packages\custom & composer update & php artisan serve
```

#### Step 4. Verify that the module is removed by running the following URL:
http://localhost:8000/timeshow/UTC
