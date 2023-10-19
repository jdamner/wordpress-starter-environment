# WordPress Starter Package

A simple starter that includes utilises WordPress Environment (wp-env) to create a local WordPress environment.

## Prerequisites

- [Docker](https://www.docker.com/)
- [Node.js](https://nodejs.org/en/)

## Getting Started
Run `./install` to install the required dependancies. 
Alternatively, you can run `composer install` then `npm ci` to install the dependancies, followed by `npm run env start` to start the local environment.

You can stop the environment with `npm run env stop`. For more information on the environment commands, see [wp-env](https://developer.wordpress.org/block-editor/packages/packages-env/) - these are all accessible via `npm run env` (e.g. `npm run env clean`).
