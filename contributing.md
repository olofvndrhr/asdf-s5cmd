# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test s5cmd https://github.com/olofvndrhr/asdf-s5cmd.git "s5cmd version"
```

Tests are automatically run in GitHub Actions on push and PR.
