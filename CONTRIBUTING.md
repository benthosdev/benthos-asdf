# Contributing

## Testing

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# e.g. ...
asdf plugin test benthos https://github.com/benthosdev/benthos-asdf.git "benthos --version"
```

Tests are automatically run in GitHub Actions on push and PR.
