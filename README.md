# Configuration

Configuration for my computer.
Intended to (hopefully) install and configure things cleanly, from either a clean install or existing setup.

This is only tested on my machine (MacBook Pro (16-inch, 2021), M1 Pro).
There are no plans to try to support other setups.

## Usage

```shell
./scripts/configure
```

Run this both for fresh installs and for upgrading.

## Customization

Configurations are grouped under topic directories, e.g. `git` and `homebrew`.

Within those directories, you will generally find:

- An `install` script, for installing the topic and anything relevant.
- A `Brewfile`, for installing relevant items via homebrew.
- A `configure` script, for setting preferences for that topic.

You can add/edit/delete these as you need.

Notable topics include:

- `apps`, for applications including browsers, text editors, etc.

## Resources

See other projects for inspiration/config options:

- https://github.com/holman/dotfiles
- https://github.com/search?q=zsh+dotfiles&ref=commandbar
