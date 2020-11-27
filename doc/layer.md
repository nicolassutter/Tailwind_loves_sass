# @layer

Allows to add different styles to tailwind's layers

Any styles inside of a layer will be purged by tailwind

<code>@parameter</code> - $name

## Usage

<code>@include layer($name);</code>

## Example

<pre>
  <code>
    @inlcude layer(utilities) {
      .text-nicegray-950 {
        color: gray;
      }
    }
  </code>
</pre>
