## Ygdir

### A minimalist CSS framework

Ygdir is a new CSS framework that aims to make CSS less painful, by working with strict filename and classname conventions, and aiming to write as little CSS as possible.

### Documentation

Visit our website at http://ygdir.dev/

### Install

    npm i ygdir --save

### How to use

Load in the full CSS file:

    @import "../../node_modules/ygdir/scss/ygdir";

(Paths will depend on your specific framework)

This is useful for checking out Ygdir. In production, you will want to load in parts of the CSS, meant for specific things, by hand:

    @import "../../node_modules/ygdir/scss/ygdir/reset"; // Always start with the reset
    @import "../../node_modules/ygdir/scss/ygdir/e-base"; // Always load base elements as well
    @import "../../node_modules/ygdir/scss/ygdir/c-button"; // Every other element is optional
    @import "../../node_modules/ygdir/scss/ygdir/c-block-list";
    @import "../../node_modules/ygdir/scss/ygdir/c-toolbar";

To get some inspiration on packages you would use for different contexts, check out `ygdir-content-website.scss` and `ygdir-app.scss`.

### Develop

Run the following command:

    node-sass --watch --recursive --output css --source-map true --source-map-contents scss

### CDN Usage

To use Ygdir from a CDN:

    <link rel="stylesheet" type="text/css" href="https://unpkg.com/ygdir@latest/css/ygdir.css">

