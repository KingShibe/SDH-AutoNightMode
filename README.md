# SDH-AutoNightMode

### IMPORTANT: As of 08/02/2022, this repo has been deprecated due to scheduled night mode being natively added to the Steam Deck in SteamOS 3.3.

Auto Night Mode is a plugin for the Steam Deck plugin loader [Deck Brew](https://github.com/SteamDeckHomebrew/PluginLoader). This plugin automatically manages Night Mode on your Steam Deck by getting your local sunset/sunrise times and enabling/disabling the night mode at those times.

![AutoNightModeScreenshot](./resources/autonightmode.png)

## Installation

Install through the [Deck Brew](https://beta.deckbrew.xyz/) plugin store or manually using the instructions below.

```bash
cd /home/deck/homebrew/plugins
git clone https://github.com/KingShibe/SDH-AutoNightMode.git
```

## Notes

Any time you do any other option but putting the console to sleep (i.e. restart, shut down, switch to desktop mode) than you must re-enable the plugin in the plugin menu. This is due to the Javascript running on the frontend. Unfortuanetly at the time being, this is the only way to do this however if things change, I will update it. Luckily, most people put their Steam Deck in sleep mode so this is rarily a problem but keep this in mind when using the plugin.

## License

This repository is licensed under the GNU General Public License v3.0.