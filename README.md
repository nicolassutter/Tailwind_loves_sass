# Tailwind Loves Sass

A collection of sass tools for Tailwind development ❤️

## Why this exists

This modules allows Sass and Tailwind to be used at the same time on a single project without the hassle.

**This means no linting warning/errors when trying to use a custom @rule in sass**🎉🎉.

## Currently existing features

### [@apply](doc/apply.md)

```scss
@include apply("...")
```

### [@layer](doc/layer.md)

```scss
@include layer("...")
```

### [@screen](doc/respond_to.md)

```scss
@include respond-to("...")
```

### [@screen](doc/screen.md)

```scss
@include screen("...")
```

### [@variants](doc/variants.md)

```scss
@include variants("...")
```

## Installation

You can download the source right from Github or run `npm install tailwind-loves-sass` in your terminal.

Once it's done you can include the file in your project like so:

```scss
@import "tailwind-loves-css"
```

**Note:** you WILL need tailwind to be configured and ready to use in your sass workflow. Otherwise you won't be able to use this module.
