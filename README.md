# laravelstoned

#### A collection of advanced tricks in Laravel 5+


##### Collections
1. Array as a collection.
```php
$array = ['name' => 'No one', 'age' => 22];
$person = collect($array);
```
2. Implode
```php
$collection->implode('first_name', ',');
```
3. List
```php
// returns collection of first_name values
$collection->lists('first_name');
```
