# Tailwind Loves Sass

A collection of sass tools for Tailwind development ❤️

## Why this exists

This modules allows Sass and Tailwind to be used at the same time on a single project without the hassle.

**This means no linting warning/errors when trying to use a custom @rule in sass**🎉🎉.

## Currently existing features

* [@apply](doc/apply.md) - <code>@include apply("...")</code>
* [@layer](doc/layer.md) - <code>@include layer("...")</code>
* [@screen](doc/respond_to.md) - <code>@include respond-to("...")</code>
* [@screen](doc/screen.md) - <code>@include screen("...")</code>
* [@variants](doc/variants.md) - <code>@include variants("...")</code>
  
## Installation

You can download the source right from Github or run <code>npm install tailwind-loves-sass</code> in your terminal.

Once it's done you can include the file in your project like so:

<pre>
  <code>
    @import "tailwind-loves-css";
  </code>
</pre>

**Note:** you WILL need tailwind to be configured and ready to use in your sass workflow. Otherwise you won't be able to use this module.
