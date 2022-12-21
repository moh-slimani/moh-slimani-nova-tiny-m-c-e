# Nova TinyMCE

A Nova detail field that uses [TinyMCE](https://tiny.cloud/). to add the functionality of Riche Text editor.

## Installation

```shell
composer require moh-slimani/nova-tiny-m-c-e
```

## Usage

```php

use MohSlimani\NovaTinyMCE\NovaTinyMCE;

//..
    public function fields(NovaRequest $request): array
    {
        return [
            //..
              NovaTinyMCE::make(__('text'))->hideFromIndex(),
            //..
        ]
    }

```

## Options

### Full Width

```php
NovaTinyMCE::make(__('text'))->fullWidth(),
```
