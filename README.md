# laravelstoned
A collection of advanced tricks in Laravel 5+

Expressive where syntax.
Below given lines so the same thing.

```
$products = Product::where('category', 'Applicances')->get();
$products = Product::whereCategory('Applicances')->get();
```
