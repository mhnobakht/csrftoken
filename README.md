# CSRF Token Generator

Generate and Validate CSRF Tokens to make forms Secure.

## Installation

Use the package manager 

```bash
composer require academy01/csrftoken
```

## Usage

```php
require "vendor/autoload.php";

use Academy01\Csrftoken;;

CsrfToken::generate();

CsrfToken::validate($token);
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)