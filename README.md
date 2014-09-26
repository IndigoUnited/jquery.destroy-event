# jquery.destroy-event

Adds support for "destroy" event on elements whenever the elements gets cleaned up by jQuery.


## Usage

```js

$('.my-element').on('destroy', function () {
    console.log('destroy!');
});

// ...

$('.my-element').remove();
// or..
$('.my-element').parent().html();
// etc..

```


## How to use

Simply include the `jquery.destroy-event.js` file after jQuery is loaded.   
This plugin also integrates with `AMD` (no shim required) and `CommonJS`.


## Tests

No tests yet :(
