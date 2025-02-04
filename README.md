# GS377209 Jekyll Site

[![Netlify Status](https://api.netlify.com/api/v1/badges/5c710635-c4f1-430a-9e0f-e6b086ada215/deploy-status)](https://app.netlify.com/sites/elated-hermann-5c4186/deploys)

## First Time Setup

1. Run `ruby -v`.
1. Install `ruby 2.4.0` or higher and `ruby-dev` if you need it.
1. Run `gem -v`.
1. Install latest version of `gem` if it is missing.
1. Run `gcc -v`.
1. Install latest version of `gcc` if it is missing.
1. Run `g++ -v`.
1. Install latest version of `g++` if it is missing.
1. Run `make -v`.
1. Install latest version of `make` if it is missing.
1. If you do not have `bundler` installed, then install it.
1. If you do not have `nvm` installed, install it.
1. If you do not have `rvm` installed, install it.

## Running The Project

1. Run `rvm use 3` to use ruby 3.
1. Run `bundle install` to install the latest gems.
1. Run `nvm use` to switch to the correct version of node; install it if it is missing.
1. Run `npm i` to install latest node packages.
1. Run `bundle exec jekyll serve` to run the local server.

## Updating The Project

1. Run `bundle outdated` to list outdated gems.
1. Run `bundle update --all` to update to the latest gems.
1. Run `npm outdated` to list outdated node modules.
1. Run `npm update -S` to update to the latest node modules.
1. Copy the files from `node_modules/jquery/dist` to `assets/js/jquery`.
1. Version the package `npm version major|minor|patch`.
