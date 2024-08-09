# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test protoc-gen-swift https://github.com/currentjeff/asdf-protoc-gen-swift.git "protoc-gen-swift --version"
```

Tests are automatically run in GitHub Actions on push and PR.
