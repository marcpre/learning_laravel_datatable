# learning_laravel_datatable

## Installation

`composer require yajra/laravel-datatables-oracle:"~8.0"`

###Service Provider & Facade (Optional on Laravel 5.5)

Register provider and facade on your config/app.php file.
```
'providers' => [
    ...,
    Yajra\DataTables\DataTablesServiceProvider::class,
]

'aliases' => [
    ...,
    'DataTables' => Yajra\DataTables\Facades\DataTables::class,
]
```
###Configuration
```
$ php artisan vendor:publish --provider=Yajra\DataTables\DataTablesServiceProvider
```

Done.

[jQuery DataTables API for Laravel 4|5](https://github.com/yajra/laravel-datatables)

