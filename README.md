# Backstabbr Names

Backstabbr Names is a cross-browser extension created to enhance the experience of playing Diplomacy with coworkers or friends on the Backstabbr client. The main issue with the Backstabbr Diplomacy client is that it can be challenging to identify who you are interacting with, as everything is anonymous by default. This extension addresses that by displaying player names based on information already available to the players, without bypassing any privacy settings.

## Features

- Fetches player information from the game's info panel.
- Appends player names to orders, press messages, and press thread headers.
- Uses MutationObserver to detect changes in the game's interface and update player names accordingly.

## Usage

This script is designed to be run as a browser extension. It should be included as a script in the extension's manifest file and will run in the context of the Backstabbr game's web interface.

## Limitations

- This extension does not bypass any privacy settings in the game. If a game is set to anonymous, the extension will not work because it won't be able to get the usernames from the info table.
- This script is specific to the current interface of the Backstabbr game and may not work if the game's interface changes. It also relies on certain elements being present in the game's interface.

## Future Work

Future improvements could include making the script more robust to changes in the Backstabbr game's interface and adding more features to further enhance the game's user interface.
