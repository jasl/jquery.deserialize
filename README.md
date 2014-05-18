jQuery Deserialize
====

Simple plugin for deserialize jQuery.serialize() or query string to form.

## Usage

`$('#form1').deserialize('user_id=1');`

## Options

Accepts the `except` option to exclude keys from the string. For example:

`$('#form1').deserialize("x=1&y=2&a[b]=val", {except: ['x', 'a[b]']});` will skip deserialize `x` and `a[b]` to the form.

also, you can set `data-skip-deserialize="true"` to tag to skip.

## License

This project rocks and uses MIT-LICENSE.