A [Select2](https://github.com/select2) v4 [Theme](https://select2.org/appearance#themes) for [Bootstrap v5.0.0-beta1](https://getbootstrap.com)
<p></p>

[![select2-bootstrap5 version](https://img.shields.io/badge/select2--bootstrap5-v0.0.1--beta.1-success)](https://github.com/mortezafs/select2-bootstrap5-theme/releases)
[![License](https://img.shields.io/badge/license-MIT-blue)](http://opensource.org/licenses/MIT)
[![Bootstrap](https://img.shields.io/badge/bootstrap-v5.x-blue)](https://getbootstrap.com)
![select2-bootstrap5-rtl](https://img.shields.io/badge/rtl-supported-important)
![select2-bootstrap5-ltr](https://img.shields.io/badge/ltr-supported-important)

### Compatibility

Built and tested with Bootstrap v5.0.0-beta1 and Select2 v4.0.13 in the latest Chrome, Firefox.
It will support both rtl and ltr direction.

### Installation

You can [download select2 bootstrap5 theme from this GitHub repo](https://github.com/mortezafs/select2-bootstrap5-theme/releases), and install the compiled CSS with bellow instructions.

### Usage

select2 bootstrap5 theme only works with Select2 v4.x. Applying the theme requires `select2-bootstrap5.min.css` referenced after the default `select2.min.css` that comes with Select2:

```html
<link rel="stylesheet" href="select2.min.css">
<link rel="stylesheet" href="select2-bootstrap5.min.css">
<script src="select2.min.js" type="text/javascript"></script>
```

To apply the theme, tell Select2 to do so by passing `bootstrap5` to the [`theme`](https://select2.org/appearance#themes) option when initializing Select2:

```js
$( "#your-dropdown" ).select2({
    theme: "bootstrap5"
});
```

You may also set it as the default theme for all Select2 widgets like so:

```js
$.fn.select2.defaults.set( "theme", "bootstrap5" );
```

### Changelog

#### 0.0.1-beta.1
The first release

#### Copyright and license

This theme created by Morteza Fard Saffari ([ArizoTech Co.](https://arizotech.com)) And licensed under MIT License
