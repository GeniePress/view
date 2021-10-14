## About GeniePress View

Use twig with the GeniePress framework

## Register with Genie

```php
<?php

use GeniePress\View\View;
use GeniePress\Genie;

Genie::createPlugin()
     ->bootstrap(function() { 
        View::setup();
     })
     ->start();
```
## View folder

By default, View looks for twig templates in `src/twig`

Version 1.0.0

