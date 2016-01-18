# Node notes and configuration

## Node configuration

Make sure node and npm are working properly

- `which node` and `which npm` should both return valid paths
- `npm install -g mocha` should result in you being able to `which mocha` from
anywhere and you should get a valid path

If for some reason npm -g isn't working then most likely you have a node modules
pathing issue. Try fixing that in your .zshrc file or in a separate .zshrc_profile
file. ie Add something like the following:

- `export PATH=/path/to/node/bin:$PATH`

## Useful global modules

- mocha testing framework - `npm install -g mocha`
- nightwatch webdriver framework - `npm install -g nightwatch`
- n for managing different version of node `npm install -g n`
