# @variants

Allows tailwind to create variants for your custom classes
These should be put inside a tailwind layer like utilities or components, but it's not mandatory
These variants are generated in the order you list them

<code>@parameter</code> - $names

## Usage

<code>@include variants($names);</code>

## Example

<pre>
  <code>
    @inlcude variants("responsive, hover, focus") {
      .my-class {
        color: red;
      }
    }
  </code>
</pre>
