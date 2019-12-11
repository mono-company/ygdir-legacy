## Ygdir

### A BEM/ITCSS based framework

Ygdir is a new CSS framework that aims to make CSS less painful.

### Install

    npm i ygdir --save

### How to use

Load in the full CSS file:

    @import "../../node_modules/ygdir/scss/ygdir";

(Paths will depend on your specific framework)

Or - load in parts of the CSS:

    @import "../../node_modules/ygdir/scss/ygdir/c-button";
    @import "../../node_modules/ygdir/scss/ygdir/c-content";
    @import "../../node_modules/ygdir/scss/ygdir/c-block-list";
    @import "../../node_modules/ygdir/scss/ygdir/c-toolbar";

### Develop

Run the following command:

    node-sass --output-style compressed -o scss/* css/*

### CDN Usage

To use Ygdir from a CDN:

    <link rel="stylesheet" type="text/css" href="https://unpkg.com/ygdir@latest/css/ygdir.css">

## Demo's

* [Content](https://codepen.io/wolfr/pen/rNaOZEY)
* [Buttons](https://codepen.io/wolfr/pen/YzPyOMg)
