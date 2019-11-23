# Pink Dark iOS Theme

[![Action Status](https://github.com/timpihl/lovelace-pink-dark-ios/workflows/yamllint/badge.svg)](https://github.com/timpihl/lovelace-pink-dark-ios/actions)
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)
[![homeassistant_community](https://img.shields.io/badge/HA%20community-forum-brightgreen)](https://community.home-assistant.io/t/ios-dark-mode-theme/149136)
[![Github Stars](https://img.shields.io/github/stars/timpihl/lovelace-pink-dark-ios)](https://github.com/timpihl/lovelace-pink-dark-ios)

> The Pink Dark iOS Theme by @timpihl modified from basnijholt and kalkih.

## Screenshots

### Overview

![Theme - Overview](https://raw.githubusercontent.com/timpihl/lovelace-pink-dark-ios/master/docs/theme-overview.jpg)
![Theme - Overview 2](https://raw.githubusercontent.com/timpihl/lovelace-pink-dark-ios/master/docs/theme-overview-2.jpg)

With alternative background ([`backgrounds/homekit-bg-4.jpeg`](backgrounds/homekit-bg-4.jpeg)):
![Theme - alternative background](https://raw.githubusercontent.com/timpihl/lovelace-pink-dark-ios/master/docs/theme-alternative-background.jpg)

### Map

![Theme - Map](https://raw.githubusercontent.com/timpihl/lovelace-pink-dark-ios/master/docs/theme-map.jpg)

### Hass.io

![Theme - Hass.io](https://raw.githubusercontent.com/timpihl/lovelace-pink-dark-ios/master/docs/theme-hassio.jpg)

### Developer Tools

![Theme - Developer Tools](https://raw.githubusercontent.com/timpihl/lovelace-pink-dark-ios/master/docs/theme-developer-tools.jpg)

### Configuration

![Theme - Configuration](https://raw.githubusercontent.com/timpihl/lovelace-pink-dark-ios/master/docs/theme-configuration.jpg)

### Profile

![Theme - Profile](https://raw.githubusercontent.com/timpihl/lovelace-pink-dark-ios/master/docs/theme-profile.jpg)

## Installation

1. Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

2. Add the following line to your `lovelace-ui.yaml` or use the RAW editor:
```yaml
background: var(--background-image)
```

3. (Optional) add the following to the same file to make the header smaller (you need to install [cch](https://github.com/maykar/compact-custom-header) too):
```yaml
cch:
  background: rgba(155, 155, 155, 0.25)
  clock_format: 24
  options: clock
  swipe_animate: fade
  swipe_prevent_default: true
```

4. (Optional) change the background to a different one, see [`backgrounds/README.md`](https://github.com/timpihl/lovelace-pink-dark-ios/tree/master/backgrounds).

### HACS

1. Go to the Community Store.
2. Search for `Pink Dark iOS`.
3. Navigate to `Pink Dark iOS` theme.
4. Press `Install`.

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/timpihl/lovelace-pink-dark-ios.git
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/timpihl/lovelace-pink-dark-ios.git
```
