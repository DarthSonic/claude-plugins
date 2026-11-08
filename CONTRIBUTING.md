# Contributing

Thanks for wanting to help, in English or German. By taking part you agree to the
[Code of Conduct](CODE_OF_CONDUCT.md).

This repository holds only the catalog, [`.claude-plugin/marketplace.json`](.claude-plugin/marketplace.json). Each
plugin lives in a repository of its own, linked in the [README](README.md#plugins):

- **A bug or an idea for a plugin** goes to that plugin's repository, which has its own issue forms and contributing
  guide.
- **A problem with the catalog itself** goes [here](https://github.com/DarthSonic/claude-plugins/issues/new/choose):
  `claude plugin marketplace add DarthSonic/claude-plugins` fails, a plugin listed here does not install, or a name,
  link or description is wrong.

## Pull requests

Fixes to the catalog and the README are welcome. Before you open one, check the catalog:

```
claude plugin validate --strict .
```

The CI runs the same against the pinned Claude Code version. The catalog lists only the maintainer's own plugins;
for a plugin of yours, a marketplace of your own is the way.

## License

Contributions are released under the [MIT License](LICENSE) of this repository.
