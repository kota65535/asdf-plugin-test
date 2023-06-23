# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test test https://github.com/<YOUR GITHUB USERNAME>/asdf-test.git "<TOOL CHECK>"
```

Tests are automatically run in GitHub Actions on push and PR.
