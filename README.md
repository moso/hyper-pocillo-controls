# hyper-pocillo-controls
Pretty Pocillo window controls for [hyper](https://github.com/zeit/hyper).

A plugin that makes the close, minimize and maximize buttons look like the [Pocillo GTK Theme](https://github.com/UbuntuBudgie/pocillo-gtk-theme) window controls. This plugin has been thoroughly tested in Ubuntu and Windows 10, and works with both `v1.4.8` (latest stable) and the `v2.0.0` canary versions.

Based on the [Pocillo GTK Theme](https://github.com/UbuntuBudgie/pocillo-gtk-theme) source, this plugin aims to match the built-in theme shipped with [Ubuntu Budgie](https://ubuntubudgie.org) 18.04 LTS. You're ~welcome~ encouraged to fork this project and modify it if you need to tinker with the colors, or create a PR if I missed something that needs fixing.

This plugin is heavily inspired by my other window controls project for hyper: [hyper-arc-dark-controls](https://github.com/moso/hyper-arc-dark-controls), which is why you'll see a lot of similar code between those two projects.

![screenshot](https://dev.moso.io/hyper/hyper-pocillo-controls/screenshot.png)

### Note

This plugin is designed to work perfectly with the `hyperterm-atom-dark`-theme.
While it also integrates fine with vanilla-themed hyper, I cannot take every theme and plugin into account.
If the plugin doesn't look great on `xyz`-theme, then please do create an issue and I will look into it. But since I don't own a Mac, I cannot test the plugin on every OS, although it's been tested on Linux and Windows 10 which is what I have available.

### Changelog

**1.0.0-alpha**

\-

### Install

**Manually**:

1. Open hyper's preferences with `Ctrl+,` (or manually at `~/.hyper.js`) with your editor.
2. Update your list of plugins to include hyper-arc-dark-controls, like so:

        plugins: [
            'hyper-pocillo-controls'
        ],

3. Reload (`Ctrl+Shift+R`) or restart hyper and voila!

**hpm**:

1. Install using `hpm i hyper-pocillo-controls`
2. Reload (`Ctrl+Shift+R`) or restart hyper and voila!

### To Do

- Config option for `~/.hyper.js` to change the position to right or left.
- Config option for `~/.hyper.js` to define if one is using the slim theme version.
- Create a check to see if the window is focused, and add a class if not, so the window controls will be "faded" like on real window controls.

### License

- The code is released under the MIT license
- The inline SVGs are licensed under CC BY-SA 4.0
