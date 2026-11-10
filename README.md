# darthsonic — Claude Code plugins

[![CI](https://github.com/DarthSonic/claude-plugins/actions/workflows/ci.yml/badge.svg)](https://github.com/DarthSonic/claude-plugins/actions/workflows/ci.yml)

The [Claude Code](https://code.claude.com) marketplace `darthsonic`: a catalog of plugins and mods by Sven Moderow.
This repository holds only the catalog, [`.claude-plugin/marketplace.json`](.claude-plugin/marketplace.json); each
plugin lives in a repository of its own, with its README, changelog and tests.

> [!TIP]
> **Free and open source.** If the plugins save you time, you can support their development:
>
> [![Sponsor on GitHub](https://img.shields.io/badge/Sponsor%20on%20GitHub-ea4aaa?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/DarthSonic)

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
| [cache-weather-and-pause-resume](https://github.com/DarthSonic/cache-weather-and-pause-resume) | Pause Claude Code and shut down, sleep or hibernate the computer once running work is done, across all sessions. Plus a band above the prompt with the prompt-cache countdown, hit rate and bar, keep-warm (on by default) that refreshes the cache before it runs out and says what that saves, context weather with the auto-compact threshold and a forecast, usage limits, a Compact button and an overview of all sessions. German and English. | `claude plugin install cache-weather-and-pause-resume@darthsonic` |

## Support

The plugins are free and open source. If they save you time, you can support their development through
[GitHub Sponsors](https://github.com/sponsors/DarthSonic).

## Deutsch

Der Marketplace `darthsonic` für [Claude Code](https://code.claude.com): ein Katalog von Plugins und Mods von Sven
Moderow. Dieses Repository enthält nur den Katalog; jedes Plugin hat ein eigenes Repository mit README (auch auf
Deutsch), Changelog und Tests. Hinzufügen mit `/plugin marketplace add DarthSonic/claude-plugins`, dann ein Plugin mit
seinem Namen und `@darthsonic` installieren. Die Plugins sind kostenlos und Open Source; sparen sie dir Zeit, kannst du
ihre Weiterentwicklung über [GitHub Sponsors](https://github.com/sponsors/DarthSonic) unterstützen.

## License

[MIT](LICENSE) © 2026 Sven Moderow. Each plugin carries its own license in its repository.
