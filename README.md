# js-dev-env
Javascript Development Environment

* To standarized code use editor config

Run security check to check npm packages `nsp check`

### Dev Web Server
* http-Server
* live-Server
* express
  * it can be used in production
  * highly configurable
* Browsersync
  * Can be used with webkpack, gulp
  * Sync page with al devices

### Share WoP
* localtunnel
* ngrok

### NPM scripts vs Gulp
* If there is a bug you must try to look for it in different places with npm you'll know the issue is in the package

### NPM Scripts
* use "pre${nameScript}" will run before the other script
* use npm scripts there not need to install -g packages
* `npm-run-all --parallel <scriptName>` will run all scripts in parallel

### Webpack
* devtool - timing is important
* entry - src 
* output - where should create the dev bundle. In dev it won' create a file
* loaders - says to webpack type of files that must handle  
* sourcemaps - are important to debug

### linters
* ESlint - best for JS
* files where it can be configured http://eslint.org/docs/user-guide/configuring#configuration-file-formats
* rules numbers meaning: 
  * 0 - off
  * 1 - warning
  * 2 - error (break build)
* eslint watch - to check when files changes
* ways to disable linters
  * /* eslint-disable ${rule} */
  * // eslint-disable-line ${rule}
** dash dash pass the param to the other script e.g. `npm run lint -- --watch` 
