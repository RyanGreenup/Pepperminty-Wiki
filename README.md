# ![Pepperminty Wiki Logo](https://raw.githubusercontent.com/sbrl/Pepperminty-Wiki/master/logo.png) Pepperminty Wiki [![Build Status](https://travis-ci.org/sbrl/Pepperminty-Wiki.svg?branch=master)](https://travis-ci.org/sbrl/Pepperminty-Wiki) [![Join the chat at https://gitter.im/Pepperminty-Wiki/Lobby](https://badges.gitter.im/Pepperminty-Wiki/Lobby.svg)](https://gitter.im/Pepperminty-Wiki/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![License: MPL-2.0](https://img.shields.io/badge/License-MPL--2.0-blue.svg)](https://raw.githubusercontent.com/sbrl/Pepperminty-Wiki/master/LICENSE) [![Docker pulls count](https://img.shields.io/badge/dynamic/json.svg?color=blue&label=Docker%20Pulls&query=%24.pull_count&url=https%3A%2F%2Fhub.docker.com%2Fv2%2Frepositories%2Fsqlatenwiki%2Fpeppermintywiki%2F)](https://hub.docker.com/r/sqlatenwiki/peppermintywiki)

> A Wiki in a box

Pepperminty Wiki is a complete wiki engine contained in a single file, inspired by @am2064's [Minty Wiki](https://github.com/am2064/Minty-Wiki). It's open source too (under MPL-2.0), so contributions are welcome!

Developed by Starbeamrainbowlabs (though contributions from others are welcome!), Pepperminty Wiki has a variety of useful (and cool!) features - such as file upload, a dynamic help page, page revision history, page tags, and more! Other amazing features are in the works too (like a theme gallery, auto update, and user watchlists), so check the release notes to see what's been added recently.

**Latest Version:** [![stable version badge](https://img.shields.io/github/release/sbrl/Pepperminty-Wiki.svg?color=brightgreen&label=stable)](https://github.com/sbrl/Pepperminty-Wiki/releases/latest) ![development version badge](https://img.shields.io/badge/development-v0.20--dev-orange.svg) ([Changelog](https://github.com/sbrl/Pepperminty-Wiki/blob/master/Changelog.md))

## Screenshot
[![Main Page Example](https://i.imgur.com/5dmbKlz.png)](https://imgur.com/a/lsBc3cM)

## Documentation
For everything you need to know (including how to get your own copy!), you probably want the documentation. It can be found here:

**[Documentation](https://starbeamrainbowlabs.com/labs/peppermint/_docpress/)**

## Real World Usage
None yet! Contact me or [open an issue](https://github.com/sbrl/Pepperminty-Wiki/issues/new) and tell me about where you are using Pepperminty Wiki and I'll add you to this section :smiley_cat:

## Todo
Here's a list of things that I want to add at some point (please feel free to [send a pull request](https://github.com/sbrl/Pepperminty-Wiki/pulls) and help out!).

 - Better page history (~~revert to revision~~ done!, compare revisions, etc.) (~~#78~~, #79)
 - Intelligent auto-updating system that doesn't wipe your settings / module choices
 - A module registry of some sort (ideas welcome!)
 - Image maps (#103)
 - An app for Android - in progress over [here](https://github.com/sbrl/Pepperminty-Wiki-Client-Android/)!
     - Participate in the beta: https://play.google.com/apps/testing/com.sbrl.peppermint
     - Report issues [here](https://github.com/sbrl/Pepperminty-Wiki-Client-Android/issues/new)
     - An iOS app is not practical for the foreseeable future.
         - It's too expensive.
         - The ecosystem is very closed off, and I've no idea how to make an iOS app (nor do I own a device to test it on)
         - Feel free to make one yourself!
         - I'm happy to help out if you need help with Pepperminty Wiki itself (e.g. making it more machine-readable (#138))
         - Message on Gitter (see above), or open an issue on this repository.
 - User watchlists
 - Theme gallery (#5)
 - (See more on the [issue tracker](https://github.com/sbrl/Pepperminty-Wiki/issues)!)
 - ...?

Is the feature you want to see not on this list or not implemented yet? [Open an issue](https://github.com/sbrl/Pepperminty-Wiki/issues/new) or [send a pull request](https://github.com/sbrl/Pepperminty-Wiki/pulls) - contributions welcome!

## Docker
The recommended way of running Pepperminty Wiki is with a plain PHP-enabled web server. However, a docker container is generously provided by @SQL-enwiki. You can run it like so:

```bash
docker run -d sqlatenwiki/peppermintywiki:stable
```

## License
Pepperminty Wiki is released under the Mozilla Public License 2.0. The full license text is included in the `LICENSE` file in this repository.
