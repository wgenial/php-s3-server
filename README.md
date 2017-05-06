
PHP S3 Server
=====================

### This project is a custom version from File Upload S3 PHP Server
- PHP-based server-side example for handling signature, delete, etc endpoint requests from Fine Uploader S3.


#### Install
```
composer require wgenial/php-s3-server
```

#### Creation of the file containing the environment variables 
```
cp vendor/wgenial/php-s3-server/.env_sample.php .env.php
vim .env.php
```

#### Default configuration
```
// AWS S3
define('AWS_CLIENT_SECRET_KEY', '');
define('AWS_SERVER_PUBLIC_KEY', '');
define('AWS_SERVER_PRIVATE_KEY', '');
define('S3_BUCKET_NAME', '');
define('S3_HOST_NAME', '');
define('S3_MAX_FILE_SIZE', '');
define('APP_URL', '');
```

#### Loading libraries
```
require('.env.php');
require('vendor/autoload.php');
```

#### Documentation
For a step-by-step getting started with PHP Fine Uploader S3, have a look at [http://docs.fineuploader.com/](http://docs.fineuploader.com/).