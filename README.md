# PEEP stack front-end

This is the front-end component of the example [PEEP Stack](https://medium.com/@j_mcnally/the-peep-stack-b7ba5afdd055#.kg4bxsapo) using a [JSONAPI](http://jsonapi.org) standard to communicate with the [Phoenix based back-end](https://github.com/liquid/peep-blog-backend).

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM)
* [Bower](http://bower.io/)
* [Ember CLI](http://www.ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)

## Installation

* `git clone <repository-url>` this repository
* change into the new directory
* `npm install`
* `bower install`

## Running / Development

* `ember server`
* Make sure your [Phoenix back-end server](https://github.com/liquid/peep-blog-backend#running) is also running.
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Running Tests

* `ember test`
* `ember test --server`

### Building

* `ember build` (development)
* `ember build --environment production` (production)
