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

Or - load in parts of the CSS, meant for specific things, currently we offer the "website" package:

    @import "../../node_modules/ygdir/ygdir-website/

Or - load in parts of the CSS by hand:

    @import "../../node_modules/ygdir/scss/ygdir-website/c-content";
    @import "../../node_modules/ygdir/scss/ygdir-website/c-block-list";
    @import "../../node_modules/ygdir/scss/ygdir-website/c-toolbar";

### Develop

Run the following command:

    node-sass --output-style compressed -o scss/* css/*

### CDN Usage

To use Ygdir from a CDN:

    <link rel="stylesheet" type="text/css" href="https://unpkg.com/ygdir@latest/css/ygdir.css">

