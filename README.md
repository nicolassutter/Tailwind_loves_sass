# Tailwind Loves Sass

A collection of [Sass](https://sass-lang.com/) tools for [Tailwind](https://tailwindcss.com/) development ❤️

## Why this exists

This modules allows Sass and Tailwind to be used at the same time on a single project without the hassle.

**This means no linting warning/errors when trying to use a custom @rule in Sass**🎉🎉.

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

You can download the source right from GitHub or use NPM in your terminal.

```sh
npm install tailwind-loves-sass
```

Once it's done, you can include the file in your project like so:

```scss
@import "tailwind-loves-sass"
```

**Note:** you WILL need tailwind to be configured and ready to use in your Sass workflow. Otherwise you won't be able to use this module.
