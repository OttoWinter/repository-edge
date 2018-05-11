# Community Hass.io Add-ons: SSH - Secure Shell

[![Release][release-shield]][release] ![Project Stage][project-stage-shield] ![Project Maintenance][maintenance-shield]

[![Discord][discord-shield]][discord] [![Community Forum][forum-shield]][forum]

[![Buy me a coffee][buymeacoffee-shield]][buymeacoffee]

This add-on allows you to log in to your Hass.io Home Assistant instance using
a web terminal.

## About

This add-on allows you to log in to your Hass.io Home Assistant instance using
a web terminal. Giving you to access your Home Assistant configuration file and
folder, and also includes a command-line tool to do things like restart,
update, and check your instance.

![Terminal in the Home Assistant Frontend][screenshot]

[Click here for the full documentation][docs]

## Features

- Access your terminal right from the web!
- Add-able to your Home Assistant interface.
- Compatible if Hass.io was installed via the generic Linux installer.
- Persists custom SSH client settings & keys between add-on restarts
- Have Alpine packages installed on start. This will allow you to install your
  favorite tools, which will be available every single time you log in.
- Execute custom commands on start automatically so that you can customize the
  shell to your likings.
- [ZSH][zsh] as its default shell. Easier to use for the beginner, more advanced
  for the more experienced user. It even comes preloaded with
  ["Oh My ZSH"][ohmyzsh], with some plugins enabled as well.
- Contains a sensible set of tools right out of the box: curl, Wget, RSync, GIT,
  Nmap, Mosquitto client, MariaDB/MySQL client, Awake (“wake on lan”), Nano,
  Vim, tmux, and a bunch commonly used networking tools.

[Click here for the full documentation][docs]

## WARNING! THIS IS AN EDGE VERSION!

This Hass.io Add-ons repository contains edge builds of add-ons. Edge builds
add-ons are based upon the latest development version.

- They may not work at all.
- They might stop working at any time.
- They could have a negative impact on your system.

This repository was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming add-ons or add-on features.
- Developers.

If you are more interested in stable releases of our add-ons:

<https://github.com/hassio-addons/repository>

[buymeacoffee-shield]: https://www.buymeacoffee.com/assets/img/guidelines/download-assets-sm-2.svg
[buymeacoffee]: https://www.buymeacoffee.com/frenck
[discord-shield]: https://img.shields.io/discord/330944238910963714.svg
[discord]: https://discord.gg/c5DvZ4e
[docs]: https://github.com/hassio-addons/addon-terminal/blob/4c5c8d7/README.md
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[forum]: https://community.home-assistant.io/t/community-hass-io-add-on-terminal/33814?u=frenck
[hass-ssh]: https://home-assistant.io/addons/ssh/
[maintenance-shield]: https://img.shields.io/maintenance/yes/2018.svg
[ohmyzsh]: http://ohmyz.sh/
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[release-shield]: https://img.shields.io/badge/version-4c5c8d7-blue.svg
[release]: https://github.com/hassio-addons/addon-terminal/tree/4c5c8d7
[screenshot]: https://github.com/hassio-addons/addon-terminal/raw/master/images/screenshot.png
[zsh]: https://en.wikipedia.org/wiki/Z_shell