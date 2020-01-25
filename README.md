## Jungle CSS 2.0

Jungle is a set of HTML and CSS components that can be used independently of each other, following the <a href="https://ygdir.dev">Ygdir</a> convention, themed with a set of great defaults.

### Documentation

Visit our website at https://junglecss.dev/

### Install

    npm i junglecss --save

### How to use

Load in the full CSS file:

    @import "../../node_modules/junglecss/scss/junglecss";

(Paths will depend on your specific framework)

This is useful for checking out Ygdir. In production, you will want to load in parts of the CSS, meant for specific things, by hand:

    @import "../../node_modules/ygdir/scss/junglecss/reset"; // Always start with the reset
    @import "../../node_modules/ygdir/scss/junglecss/e-base"; // Always load base elements as well
    @import "../../node_modules/ygdir/scss/junglecss/c-button"; // Every other element is optional
    @import "../../node_modules/ygdir/scss/junglecss/c-block-list";
    @import "../../node_modules/ygdir/scss/junglecss/c-toolbar";

To get some inspiration on packages you would use for different contexts, check out `jungle-content-website.scss` and `jungle-app.scss`.

### Develop

Run the following command:

    npm run dev

This will run the Sass compiler with a “watch” style command, which compiles your CSS on save.

### CDN Usage

To use Jungle from a CDN:

    <link rel="stylesheet" type="text/css" href="https://unpkg.com/jungle@latest/css/jungle.css">

