# TopCoat-npmized

TopCoat stylus components which can be loaded using node module resolution
mechanisms.

## Usage

Install `topcoat-npmized` and bundler:

    % npm install topcoat-npmized dcompose dgraph-stylus

Create a new widget using TopCoat button as a base:

    @import "topcoat-npmized/button.styl"

    .my-awesome-button
      @extend .button

Then compile it to CSS:

    % dcompose --css --transform dgraph-stylus ./my-awesome-button-styl
