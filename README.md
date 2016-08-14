# localsource.nl

Shared twitter account with a new author each week for NL based developers and IT community activists. 

## Starting the project

```
git clone git@github.com:iamstarkov/jsunderhood.git
cd jsunderhood
npm install
npm start
```

## Project

* `authors.js` — authors list
* `stats.js` — generate statics
* `test.js` — tests
* `gulpfile.babel.js` — website build script
* `webpack.config.babel.js` — js bundle config
* `package.json`, `.editorconfig`, `.eslintrc`, `.gitignore` — env setup
* `.travis.yml` — CI configuration
* `.deploy.sh` — Travis CI deployment script
* `README.md`

### Site data

* `update.js` — update data
* `dump/index.js` — get data
* `dump/*.json` — authors data ('tweets', 'info', 'media', 'followers', 'mentions')
* `dump/images/` — authors media
* `helpers/` — helper scripts

### Website assets

* `css/` — styles
* `layouts/` — templates
* `static/` — static files
* `pages/` — site pages

Project generated with https://github.com/iamstarkov/generator-underhood
