### Angular2-webpack-electron

[![Dependency Status](https://david-dm.org/bertofer/angular2-webpack-electron.svg)](https://david-dm.org/bertofer/angular2-webpack-electron)
[![devDependency Status](https://david-dm.org/bertofer/angular2-webpack-electron/dev-status.svg)](https://david-dm.org/bertofer/angular2-webpack-electron#info=devDependencies)

Forked from https://github.com/preboot/angular2-webpack, and adapted to work with electron.

Changes applied (Work in progress):
- Added electron typings
- Fixed a test
- Added main.js for electron
- Added dependency and script in package.json for electron
- Added rule in webpack to run electron in test mode (no complete build from webpack).
- Added coverage folder to delete in clean rules. Added clean rule to delete everything except node_modules.
- Modified npm start to run with electron instead of starting a server.
- Removed webpack-dev-server.
