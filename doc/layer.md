# @layer

Allows to add different styles to tailwind's layers

**Note**: Any styles inside of a layer will be purged by tailwind

**`@parameter`**: `$name`

## Usage

```scss
@include layer($name);
```

## Example

```scss
@inlcude layer(utilities) {
  .text-nicegray-950 {
    color: gray;
  }
}
```
