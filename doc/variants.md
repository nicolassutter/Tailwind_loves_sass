# @variants

Allows tailwind to create variants for your custom classes.

These should be put inside a tailwind layer like `utilities` or `components`, but it's not mandatory.

These variants are generated in the order you list them.

**`@parameter`**: `$names`

## Usage

```scss
@include variants($names);
```

## Example

```scss
@inlcude variants("responsive, hover, focus") {
  .my-class {
    color: red;
  }
}
```
