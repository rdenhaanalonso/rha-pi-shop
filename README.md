# SHOP

### Setup

##### Prerequisites

1. Install Polymer Cli

    $ npm install -g polymer-cli

2. Create a Firebase account

3. Install Firebase cli

    $ npm install -g firebase-tools


##### Setup

    git clone https://github.com/rdenhaanalonso/rha-pi-shop.git
    cd rha-pi-shop
    bower install

### Start the development server

    polymer serve

### Run web-component-tester tests

    polymer test

### Build

    polymer build

### Test the build

This command serves the minified version of the app in an unbundled state, as it would be served by a push-compatible server:

    polymer serve build/unbundled

This command serves the minified version of the app generated using fragment bundling:

    polymer serve build/bundled

### Deploy

    polymer build

    firebase deploy



https://rha-pi-shop.firebaseapp.com/
https://docs.google.com/document/d/1SCeYIhbf9gRQV6D_OiRTNkQxtz5ZbU3mIbhGFWSI57A
