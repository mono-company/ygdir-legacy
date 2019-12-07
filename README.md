## Ygdir

### A BEM/ITCSS based framework

Provides a base for common elements.

    npm i ygdir --save

### Develop

Run the following command:

    node-sass --output-style compressed -o scss/* css/*

### How to use

Load in the full CSS file:

    @import "../../node_modules/ygdir/scss/ygdir";

(Paths will depend on your specific framework)

Or - load in parts of the CSS:

    @import "../../node_modules/ygdir/scss/ygdir/c-button";
    @import "../../node_modules/ygdir/scss/ygdir/c-content";
    @import "../../node_modules/ygdir/scss/ygdir/c-block-list";
    @import "../../node_modules/ygdir/scss/ygdir/c-toolbar";
