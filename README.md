# laravel-dnode
Laravel 5 wrapper for DNode RPC protocol

## Installation

Via Composer

    $ composer require sipimokus/laravel-dnode

Then add the service provider in `config/app.php`:

``` php
    'providers' => [
        // ...
        'Sipimokus\DNode\DNodeServiceProvider'
    ]
```

And Facade (also in `config/app.php`)

``` php
    'aliases' => [
        // ...
        'DNode' => 'Sipimokus\DNode\Facades\DNode'
    ]
```

Publish the config settings:

```
    $ php artisan vendor:publish --provider="Sipimokus\DNode\DNodeServiceProvider" --tag="config"
```

## Examples
PHP as client

``` php
    Coming soon
```

PHP as server

``` php
    Coming soon
```

## Usage
The used DNode package description and examples can be found [here](https://github.com/bergie/dnode-php) and [here](http://bergie.iki.fi/blog/dnode-make_php_and_node-js_talk_to_each_other/).
