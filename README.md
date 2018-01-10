# Idle Fidget Spinners Web UI

[Play Game](https://andrew-boutin.github.io/idle-fidget-spinners-web-ui/).

A classic idle game where you collect and spin fidget spinners to gain money. See how far you can get.

Right now this is a static site. Eventually it will be more.

## Hosting

This game is being hosted with GitHub pages.

## Dev Notes

### Site Source
This site is hosted with GitHub pages which overrides the *Site Source* configuration value.
Because of this, we have to determine assets, such as `.js` and `.css`, based off of the root directory.
This means the assets will be loaded correctly when GitHub Pages is hosting the site, but they
won't be loaded correctly in a development environment by opening the `.html` file in a browser.

