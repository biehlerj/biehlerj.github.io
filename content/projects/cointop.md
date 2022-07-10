---
title: Cointop
date: 2020-08-10T22:09:12-07:00
---

[Cointop](https://github.com/cointop-sh/cointop) is a CLI utility written in Go to track cryptocurrencies.

My contribution to Cointop was to make sure that the configuration file was read from and added to the user's declared
config directory otherwise it would use a standardized path.

The previous behavior would override the user's config directory. For instance on Linux if you had `$XDG_CONFIG_HOME`
defined the config.toml file for Cointop would be placed into `$XDG_CONFIG_HOME/.config/cointop/` rather than
`$XDG_CONFIG_HOME/cointop/`.

You can find the code and subsequent tests that were added in [this PR on GitHub](https://github.com/cointop-sh/cointop/pull/58)

Skills used:

- Go
