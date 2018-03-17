# CodeOasisFST_server
### Laravel
php artisan serve - start server


### MongoDB
#### commands
show dbs
use 'dbname'
show collections - 'show existing collections'
db.collectionName.find() - show content
db.collectionName.insert({}) - add data

#### mingrations
php artisan migrate:fresh
php artisan make:migration create_task_table --create=tasks -create migration
php artisan migrate - migration
php artisan migrate:refresh - add migration changes
php artisan make:model - create model
php artisan migrate:reset
php artisan make:model Task -m - create model with migration
php artisan make:controller 'ControllerName'
php artisan make:model 'NAME' -mc - create model controller migrations
php artisan make:auth
#### my hints
app - models
resources/views - views
app/http/controllers - controllers
