# Melis Tool Creator Laravel
This module handle the Tool Creator configuration to activate Laravel option on
the selection in the Tool Creator.

### Prerequisites
This module requires ``melisplatform/melis-tool-creator`` installed.
This will automatically be done when using composer.

### Installing
```
composer require melisplatform/melis-tool-creator-laravel
```

Enabling Laravel option on Tool creator
```
return [
    'tool-creator-third-party-frameworks' => [
        'laravel'
    ]
];

```

By just activating this module on the Melis Platform Back-office this will automatically added to the 
selection of Third party frameworks tool creation.

## Authors
* **Melis Technology** - [www.melistechnology.com](https://www.melistechnology.com/)

See also the list of [contributors](https://github.com/melisplatform/melis-core/contributors) who participated in this project.


## License
This project is licensed under the OSL-3.0 License - see the [LICENSE.md](LICENSE.md) file for details