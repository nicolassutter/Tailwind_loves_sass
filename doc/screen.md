# @screen

Facilitates the use of media queries with tailwind's breakpoints.

**Note**: This is a copy of repsond-to, in order to be similar to tailwind's default rule.

**`@parameter`**: `$name`

## Usage

```scss
@include screen($name);
```

## Example

```scss
@inlcude screen(md) {
  grid-template-columns: 1fr 1fr;
}
```
