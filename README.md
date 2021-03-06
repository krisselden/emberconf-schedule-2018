# EmberConf 2018 Schedule

[![TravisCi](https://travis-ci.org/201-created/emberconf-schedule-2018.svg?branch=master)](https://travis-ci.org/201-created/emberconf-schedule-2018)

## Features

* [Progressive Web App](https://madhatted.com/2017/6/16/building-a-progressive-web-app-with-ember)
  * Perfect 💯 Lighthouse score
  * Save to mobile home screen for fullscreen app experience
  * Offline cache fallback via service worker
* [Module Unification](https://github.com/emberjs/rfcs/blob/master/text/0143-module-unification.md) File Layout
  * File system migrated with [ember-module-migrator](https://github.com/rwjblue/ember-module-migrator)
  * Review the project's file structure organized within `src` directory rather than `app`
  * Uses local component lookup (components found in context-aware `-component` directories)
* Fastboot Rehydration
* [Separate WASM Version](https://schedule-wasm.emberconf.com) Also Available
  * Deployed separately because Mobile Safari has temporarily dropped WASM support ☹️

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/)
* [Yarn](https://yarnpkg.com/)
* [Ember CLI](https://ember-cli.com/)
* [Google Chrome](https://google.com/chrome/)

## Installation

* `git clone git@github.com:201-created/emberconf-schedule-2018.git` this repository
* `cd emberconf-schedule-2018`
* `yarn install`

## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* Visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Linting

* `yarn lint:js`
* `yarn lint:js --fix`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

Deployment to Heroku occurs automatically for the `master` branch.

## Updating Source Data

A Ruby rake task is included in this project's `Rakefile` that will update the contents of `app/lib/data.js`:

```shell
bundle install
bundle exec rake
```

## Further Reading / Useful Links

* [ember.js](https://emberjs.com/)
* [ember-cli](https://ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
