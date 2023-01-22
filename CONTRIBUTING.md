# Contributing

Contributions are welcome and encouraged!

We accept contributions via Pull Requests on [GitHub](https://github.com/vatsimnetwork/oauth2-vatsim-php).


## Pull Requests

- **[PSR-12 Coding Standard](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-12-extended-coding-style-guide.md)** - The easiest way to apply the conventions is to install [PHP Code Sniffer](https://github.com/squizlabs/PHP_CodeSniffer).

- **Add tests!** - Your patch won't be accepted if it doesn't have tests.

- **Document any change in behaviour** - Make sure the README and any other relevant documentation are kept up-to-date.

- **Consider our release cycle** - We try to follow SemVer. Randomly breaking public APIs is not an option.

- **Create topic branches** - Don't ask us to pull from your main branch.

- **One pull request per feature** - If you want to do more than one thing, please send multiple pull requests.

- **Send coherent history** - Make sure each individual commit in your pull request is meaningful. If you had to make multiple intermediate commits while developing, please squash them before submitting.

- **Ensure tests pass!** - Please run the tests (see below) before submitting your pull request, and make sure they pass. We won't accept a patch until all tests pass.

- **Ensure no coding standards violations** - Please run PHP Code Sniffer using the PSR-12 standard (see below) before submitting your pull request. A violation will cause the build to fail, so please make sure there are no violations. We can't accept a patch if the build fails.


## Running Tests

```sh
composer test
```


## Running PHP Code Sniffer

```sh
composer lint
```

**Happy coding**!
