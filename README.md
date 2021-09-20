# Tailwind Loves Sass

> Before using this package, you should always consider disabling your editor's native linting for custom css @rules. 

> If for some reason, this is not possible for you, then feel free to use this package.

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
@import "tailwind-loves-sass";
```

**Note:** you WILL need tailwind to be configured and ready to use in your Sass workflow. Otherwise you won't be able to use this module.

### Options

You can choose to use (or not) different options. These options aim to enhance the `base`, `components` and `utilities` layers of `Tailwind`.

#### Currently existing options

##### [Knacss](https://www.knacss.com/)

This includes the default resets from the framework [Knacss](https://www.knacss.com/) by [Raphaël Goetter](https://github.com/raphaelgoetter) and [Alsacréations](https://www.alsacreations.fr/).

```scss
@import "tailwind-loves-sass/options/knacss/_main.scss";
