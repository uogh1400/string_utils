# String Utils

---

Simple string utils for dealing easier with them

# Installation

Install using composer:

‌```
composer require uogh1400/string_utils
‌```

# Example

```php
<?php

require __DIR__.'/vendor/autoload.php';

use \Uogh1400\StringUtils\Str;

var_dump(Str::contains('abcd', ['ab', 'x']));
```