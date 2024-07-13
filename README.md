<p align="center"><img src="http://sandromiguel.com/host/php-sceleto.png" alt="PHP Sceleto" /></p>

# Welcome to PHP Sceleto

**A PHP directory structure for my libraries.**

[![license](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)](LICENSE)

PHP Sceleto is a directory structure template designed for creating PHP libraries. It provides a well-organized skeleton that I use for my PHP library projects and have decided to share with the community. This template is intended to streamline the development of PHP libraries, saving you time on initial setup and configuration.

## Features

-   Organized directory structure for your PHP library:
-   Includes common project files like `.editorconfig`, `.gitignore`, and `.htaccess`.
-   Comes with a sample `composer.json` for easy Composer integration.
-   Includes a sample PHPUnit configuration file `phpunit.xml.dist`.
-   License and contributing guidelines for open-source projects.

## Directory structure

```
your-php-library/
│
├──┬ src/
│  │  ├─── [SomeClass].php
│  │  ├─── [AnotherClass].php
│  │  ├─── ...
│  │
│  └ tests/
│     ├─── [SomeClass]Test.php
│     ├─── [AnotherClass]Test.php
│     ├─── ...
│
├─── logs/
├─── docs/
├─── vendor/
├─── .editorconfig
├─── .gitignore
├─── .htaccess
├─── composer.json
├─── composer.lock
├─── phpunit.xml.dist
├─── LICENSE
├─── CONTRIBUTING.md
└─── README.md
```

## Files and Folders

Files and folders overview.

| File/Folder                    | Description                                          |
| ------------------------------ | ---------------------------------------------------- |
| **src/**                       | Source code of the application                       |
| src/**SomeClass.php**          | Example PHP class file (SomeClass)                   |
| src/**AnotherClass.php**       | Example PHP class file (AnotherClass)                |
| src/**tests/**                 | Tests directory                                      |
| tests/**SomeClassTest.php**    | PHPUnit test case for `SomeClass` (Example class)    |
| tests/**AnotherClassTest.php** | PHPUnit test case for `AnotherClass` (Example class) |
| **logs/**                      | Log files (e.g., code coverage report)               |
| **docs/**                      | Documentation files (e.g., PHPDoc)                   |
| **vendor/**                    | Composer vendor directory contains your dependencies |
| **.editorconfig**              | IDE coding style settings                            |
| **.gitignore**                 | Files and directories that Git should ignore         |
| **.htaccess**                  | Hypertext access file for Apache configuration       |
| **composer.json**              | Composer dependencies                                |
| **composer.lock**              | Composer lock file                                   |
| **phpunit.xml.dist**           | PHPUnit configuration file                           |
| **LICENSE**                    | License document                                     |
| **CONTRIBUTING.md**            | Contributing guidelines                              |
| **README.md**                  | This document                                        |

## Getting Started

Follow these steps to use PHP Sceleto as a starting point for your PHP library:

### Step 1 - Create a new project using Composer:

```bash
composer create-project SandroMiguel/php-sceleto your-php-library
```

Replace `your-php-library` with your desired name

Now, you have a clean slate to begin developing your PHP library independently. You can add your own code, configuration, and documentation within the provided directory structure.

### Step 2 - Bonus: Continue Your Project Setup

If you wish to further enhance your project and follow best practices, consider continuing your project setup with [Some Awesome Project](https://github.com/SandroMiguel/some-awesome-project). Some Awesome Project provides a set of guidelines and additional configurations that can make your project development even more efficient.

## Composer commands

You can use Composer commands to streamline various development tasks. Here are the available commands and how to run them:

### Check for Outdated Dependencies

To check for outdated Composer dependencies that are defined directly in your project, run:

```sh
composer outdated:direct
```

### Run PHP CodeSniffer

To run PHP CodeSniffer on the source code in the src/php directory, use the following command:

```sh
composer phpcs
```

### Run PHP CodeSniffer on a Specific File

For running PHP CodeSniffer on a specific file, use the following command, replacing `[file]` with the path to your target file:

```sh
composer phpcs:file [file]
```

### Analyze Code Quality and Architecture

To analyze code quality and architecture with PHP Insights, run:

```sh
composer phpinsights
```

### Generate PHP Metrics Report

Generate a PHP Metrics report and display the Node.js version with:

```sh
composer phpmetrics
```

### Run PHPStan Analysis

For PHPStan analysis with level 7 on the source code in the `src/php` directory, use:

```sh
composer phpstan
```

### Run Psalm Static Analysis

To run Psalm static analysis, simply use:

```sh
composer psalm
```

### Tail Application Logs

To tail the application log located at `./storage/log/app.log`, use:

```sh
composer logs
```

### Run PHPUnit Tests

For running PHPUnit tests, execute:

```sh
composer test
```

To run PHPUnit tests with filtering, execute:

```
composer test:filter methodName ClassName path/to/file.php
```

### Run PHPUnit Tests with Coverage Report

To run PHPUnit tests and generate a coverage report in the `log/report` directory, use:

```sh
composer test:coverage
```

## Credits

-   [EditorConfig](https://editorconfig.org/): IDE coding style settings.
-   [PHPUnit](https://phpunit.de/): Testing framework for PHP.
-   [PHP CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer): PHP coding standards checker and fixer.
-   [PHP Insights](https://phpinsights.com/): Code quality and architecture analysis tool.
-   [PHP Metrics](https://phpmetrics.org/): PHP metrics generator.
-   [PHPStan](https://phpstan.org/): PHP static analysis tool.
-   [Psalm](https://psalm.dev/): Static analysis tool for PHP.
-   [Composer](https://getcomposer.org/): Dependency management for PHP.
-   Logo skeleton - made by [Freepik](http://www.freepik.com) from [www.flaticon.com](https://www.flaticon.com/) is
    licensed by [CC 3.0 BY](http://creativecommons.org/licenses/by/3.0/)

## Contributing

Want to contribute? All contributions are welcome. Read the [contributing guide](CONTRIBUTING.md).

## Questions

If you have questions tweet me at [@sandro_m_m](https://twitter.com/sandro_m_m) or [open an issue](../../issues/new).

## Changelog

See [CHANGELOG.md](CHANGELOG.md)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

**~ sharing is caring ~**
