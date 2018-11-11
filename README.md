<p align="center"><img src="http://sandromiguel.com/host/php-sceleto.png" alt="PHP Sceleto" /></p>

# Welcome to PHP Sceleto
**PHP Sceleto is a PHP directory structure sample.**

[![license](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)](LICENSE)

The inspirational skeleton in PHP

Current version: **0.4.0**

## Directory structure
```
your-php-app/
├──┬ public/
│  ├─── css/
│  ├─── js/
│  └─── img/
│
├──┬ src/
│  ├──┬ app/
│  │  ├─── [SomeCustomClass].php
│  │  ├─── ...
│  │  
│  └──┬ core/
│     ├─── [SomeCommonClass].php
│     ├─── ...
│
├─── config/
├─── logs/
├─── docs/
├─── vendor/
├─── tests/
├─── .gitignore
├─── .editorconfig
├─── .htaccess
├─── composer.json
├─── composer.lock
├─── phpunit.xml.dist
├─── LICENSE
├─── CONTRIBUTING.md
└─── README.md
```

## Getting Started

### Step 1 - Install this directory structure
#### Download
Download the [latest release](https://github.com/SandroMiguel/php-sceleto/archive/v.0.3.zip)

### Step 2 - Install the dependencies
Install the dependencies with Composer.
```
cd your-php-app   # Your project name
composer install  # Install the dependencies
```

## Composer commands
### Run PHPUnit
```
composer test
```

## Composer commands
### Run Test Coverage
```
composer test-coverage
```

## Files and Folders
Files and folders overview.

| File/Folder | Description |
| --- | --- |
| **public/** | Web server files (all public files for your application) |
| public/**css/** | CSS files |
| public/**js/** | JavaScript files |
| public/**img** | Image files |
| **src/** | The source code of the application |
| src/**app/** | Custom PHP classes |
| src/app/**SomeCustomClass.php** | PHP custom class file example |
| src/**core/** | Common code in all applications |
| src/core/**SomeCommonClass.php** | Common class file example |
| **config/** | Configuration files |
| **logs/** | Log files (e.g. code coverage report) |
| **docs/** | Documentation files (e.g. PHPDoc) |
| **vendor/** | Composer vendor directory contains your dependencies |
| **tests/** | Automated tests |
| **.gitignore** | Files and directories that Git should ignore |
| **.editorconfig** | IDE coding style |
| **.htaccess** | Hypertext access file for Apache configuration |
| **composer.json** | Composer dependencies |
| **composer.lock** | Composer lock file |
| **phpunit.xml.dist** | PHPUnit configuration |
| **LICENSE** | License document |
| **CONTRIBUTING.md** | Contributing guidelines |
| **README.md** | This document |

## Credits
- IDE coding style - [EditorConfig](https://editorconfig.org/)
- Logo skeleton - made by [Freepik](http://www.freepik.com) from [www.flaticon.com](https://www.flaticon.com/) is 
licensed by [CC 3.0 BY](http://creativecommons.org/licenses/by/3.0/)

## Contributing
Want to contribute? All contributions are welcome. Read the [contributing guide](CONTRIBUTING.md).

## Questions
If you have questions tweet me at [@SandroMiguel77](https://twitter.com/SandroMiguel77) or [open an issue](https://github.com/SandroMiguel/php-sceleto/issues/new).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

**~ sharing is caring ~**
