# multiSwitch
A switch jQuery plugin with a initial null default option

![demo](https://cloud.githubusercontent.com/assets/6153386/14571662/d4f6c450-0320-11e6-87c2-17c06a74a89f.gif)

**Demo**: http://tcavalin.github.io/multiSwitch/

## Installation ##

Include script after the jQuery library:

```html
<script src="src/multi-switch.js"></script>
```

## Basic usage ##

    <input type="checkbox" class="multi-switch" value="0" />

With a initial null default option:

    <input type="checkbox" class="multi-switch" initial-value="0" unchecked-value="2" checked-value="1" value="0" />

Disabled:

    <input type="checkbox" class="multi-switch" value="0" disabled="disabled" />

### jQuery
```js
$(document).ready(function(){
    $('.multi-switch').multiSwitch();
});
```

## Authors ##

[Tiago Cavalin](https://github.com/tcavalin)
[Rômulo Busatto](https://github.com/romulobusatto)
