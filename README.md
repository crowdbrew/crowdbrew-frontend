# Crowdbrew-frontend

This README outlines the details of collaborating on this Ember application.
A short introduction of this app could easily go here.


## Development workflow

Do not push directly into main branches. Submit pull requests.



## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (latest version in 6.x, we'll upgrade to Node 7 when Ember CLI does; [NVM](https://github.com/creationix/nvm) is recommended)
* [Bower](http://bower.io/)
* [Ember CLI](http://ember-cli.com/)
* [Yarn](https://yarnpkg.com/)



## :warning: Do not use `npm` and `ember install`

This project uses [Yarn](https://yarnpkg.com/).

* Install Yarn:

        npm i -g yarn

* Install this project's npm dependencies with yarn:

        yarn install

* Install an ember addon:

        yarn add -D <addon name>
        ember g <addon name>

    "Unknown blueprint" error message is expected in case the installed addon doesn't want to modify the codebase. Simply ignore the message.



## Installation

* `git clone git@github.com:crowdbrew/crowdbrew-frontend.git`
* `cd crowdbrew-frontend`
* `yarn install`
* `bower install`



## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).



### Code Generators

Make use of the many generators for code, try `ember help generate` for more details



### Running Tests

* `ember test`
* `ember test --server`



### Building

* `ember build` (development)
* `ember build --environment production` (production)



### Deploying

Specify what it takes to deploy your app.

## Further Reading / Useful Links

* [ember.js](http://emberjs.com/)
* [ember-cli](http://ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)

