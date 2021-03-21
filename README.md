# textlint ignore example

`.textlintignore` example repository.

- [Ignoring Text · textlint](https://textlint.github.io/docs/ignore.html)


## Installation

    npm install
    npm test

## Examples

[.textlintignore](./.textlintignore)

```
# path to file
ignored.md
# glob pattern
generated/**
```

As a result, textlint does not lint [ignored.md](./ignored.md) and [generated/test.md](generated/test.md).

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

MIT