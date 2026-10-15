# darthsonic — Claude Code plugins

[![CI](https://github.com/DarthSonic/claude-plugins/actions/workflows/ci.yml/badge.svg)](https://github.com/DarthSonic/claude-plugins/actions/workflows/ci.yml)

The [Claude Code](https://code.claude.com) marketplace `darthsonic`: a catalog of plugins and mods by Sven Moderow.
This repository holds only the catalog, [`.claude-plugin/marketplace.json`](.claude-plugin/marketplace.json); each
plugin lives in a repository of its own, with its README, changelog and tests.

## Add the marketplace

At the prompt of a Claude Code session in a terminal:

```
/plugin marketplace add DarthSonic/claude-plugins
```

The same from a shell:

```
claude plugin marketplace add DarthSonic/claude-plugins
```

Then install a plugin by its name and `@darthsonic`, or browse them in `/plugin`.

## Plugins

| Plugin | What it does | Install |
| --- | --- | --- |
| [cache-weather-and-pause-resume](https://github.com/DarthSonic/cache-weather-and-pause-resume) | A band above the prompt: prompt-cache countdown and bar, an opt-in keep-warm that refreshes the cache before it runs out, hit rate, context weather with the auto-compact threshold, a Compact button and a Pause / Resume button that has Claude finish running work, save its state and wait. German and English. | `claude plugin install cache-weather-and-pause-resume@darthsonic` |

## Deutsch

Der Marketplace `darthsonic` für [Claude Code](https://code.claude.com): ein Katalog von Plugins und Mods von Sven
Moderow. Dieses Repository enthält nur den Katalog; jedes Plugin hat ein eigenes Repository mit README (auch auf
Deutsch), Changelog und Tests. Hinzufügen mit `/plugin marketplace add DarthSonic/claude-plugins`, dann ein Plugin mit
seinem Namen und `@darthsonic` installieren.

## License

[MIT](LICENSE) © 2026 Sven Moderow. Each plugin carries its own license in its repository.
