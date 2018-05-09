# Laravel Validator Rules - Offensive

This rule will validate that a field isn't offensive. It can be useful to check user supplied data that may be publicly displayed, such as usernames or comments.

## Installation

```bash
composer require laravel-validation-rules/offensive
```


## Usage

```php
use DivineOmega\LaravelOffensiveValidationRule\Offensive;

$request->validate([
    'username' => ['required', new Offensive],
]);
```

## License
This project is licensed under a GNU Lesser General Public License v3.0 which you can find
[in this LICENSE](https://github.com/laravel-validation-rules/exposed-password/blob/master/LICENSE).


## Feedback
If you have any feedback, comments or suggestions, please feel free to open an
issue within this repository.

## Laravel Validation Rules

This package is part of the Laravel Validation Rules collection. If you're after more useful validation rules, head to the [Laravel Validation Rules](https://laravel-validation-rules.github.io/) website.