This extension runs in conjunction with the [native host app](https://github.com/msfeldstein/MediaKeyHosts) to add media key capabilities to most in-browser web players.

The extension can be installed from the Chrome Web Store [here](https://chrome.google.com/webstore/detail/swayfm-unified-music-medi/icckhjgjjompfgoiidainoapgjepncej)

#### Building

Ensure grunt-cli is installed on the system

    npm install -g grunt-cli

Install the npm packages for this project

    npm install # In the project directory

Run grunt

    grunt run

If you see a ENOENT error, make sure imagemagick is installed

    npm install imagemagick