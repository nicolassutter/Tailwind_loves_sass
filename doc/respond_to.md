# @screen

Facilitates the use of media queries with tailwind's breakpoints

**`@parameter`**: `$name`

## Usage

```scss
@include respond-to($name);
```

## Example

```scss
@include respond-to(md) {
  grid-template-columns: 1fr 1fr;
}
```
