# 🔍 Buscador de Cursos
Project that searches the courses on Alura's website developed in the PHP Composer course by Alura.


## 🚀 Stacks

This project was developed with the following technologies, tools and utilities:
- [PHP (Language)](https://www.php.net/)
- [Composer (Dependency Manager)](https://getcomposer.org/)
- [PHPUnit (Unit Test)](https://phpunit.de/index.html)
- [PHPCS (Design Patterns)](https://github.com/squizlabs/PHP_CodeSniffer)
- [PHAN (Static Analysis of code syntax)](https://github.com/phan/phan)
- [Packagist (Package Repository)](http://packagist.org)

Installed Dependencies:
- [guzzlehttp/guzzle](https://packagist.org/packages/guzzlehttp/guzzle)
- [symfony/dom-crawler](https://packagist.org/packages/symfony/dom-crawler)
- [symfony/css-selector](https://packagist.org/packages/symfony/css-selector)
- [phpunit/phpunit](https://phpunit.de/getting-started/phpunit-9.html)
- [squizlabs/php_codesniffer](https://github.com/squizlabs/PHP_CodeSniffer)
- [phan/phan](https://github.com/phan/phan)

# 🆙 App Features

- Searches the name of all courses in a section of the Alura website;
- It performs three types of tests in the application, they are PHPUnit (Unit Test), PHPCS (Design Patterns) and PHAN (Static Analysis of Code Syntax).

# 👷 How to run?

```bash
git clone https://github.com/JardelDeveloper/buscador-cursos.git
```

# 💻 Run App

```bash
# Access the directory
$ cd buscador-cursos
# Make sure PHP is installed, if not, go to the PHP documentation above to install
$ php --version
# Make sure Composer is installed, if not, go to the Composer documentation above to install
$ composer --version
# Create the basic composer configuration file automatically (composer.json)
$ composer init
# Install all Dependencies exactly in composer.json
$ composer install
# Insert or remove packages or change autoload 
$ composer update
# Update the autoload
$ composer dumpautoload
# Run App for terminal
$ php "file.php"
```

# 🧪 Test App 
```bash
# Required the environment to be configured, if not, take a look at the "Run App" section
# Access the directory
$ cd buscador-cursos
# See the complete list of commands
$ composer list
# Test PHAN (Static Analysis of code syntax)
$ composer phan
# Test PHPCS (Design Patterns)
$ composer cs
# Test PHPUnit (Unit Test)
$ composer test
# Test PHAN, PHPCS and PHPUnit automatically
$ composer check
```

# 🤔 How to contribute?

```bash
# Make a Fork this repository;
# Create a branch with your feature:
git checkout -b my-feature;
# Make commit to your changes:
git commit -m "feat: my new feature";
# Make a push to your branch:
git push origin my-feature;
```

After the merge of your pull request is done, you can delete a branch of yours.

# 🔧 Issues

Feel free to **file a new issue** with a respective title and description on the [Buscador de Cursos](https://github.com/JardelDeveloper/buscador-cursos/issues) repository. If you already found a solution to your problem, **I would love to review your pull request**.

# 📝 License

Released in 2021 📕

This project is under the MIT license. See the [LICENSE](https://github.com/JardelDeveloper/buscador-cursos/blob/main/LICENSE) for more details.

Made with 💚 by Jardel Cunha.

Give ⭐ if this project helped you!
