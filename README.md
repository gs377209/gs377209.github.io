# GS377209 Jekyll Site

[![Netlify Status](https://api.netlify.com/api/v1/badges/5c710635-c4f1-430a-9e0f-e6b086ada215/deploy-status)](https://app.netlify.com/sites/elated-hermann-5c4186/deploys)

## First Time Setup

1. If you do not have `rbenv` installed, install it.
2. If you do not have `bundler` installed, then install it.
3. If you do not have `nvm` installed, install it.

## Running The Project

1. Run `rbenv local` to use ruby 3.
2. Run `bundle install` to install the latest gems.
3. Run `nvm use` to switch to the correct version of node; install it if it is missing.
4. Run `npm i` to install latest node packages.
5. Run `bundle exec jekyll serve --incremental` to run the local server.
6. Run `rake` to run the tests.

## Updating The Project

1. Run `bundle outdated` to list outdated gems.
2. Run `bundle update --all` to update to the latest gems.
3. Run `npm outdated` to list outdated node modules.
4. Run `npm update --save` to update to the latest node modules.
5. Copy the files from `node_modules/jquery/dist` to `assets/js/jquery`.
6. Version the package `npm version major|minor|patch`.
