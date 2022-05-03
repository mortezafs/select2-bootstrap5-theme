A [Select2](https://github.com/select2) v4 [Theme](https://select2.org/appearance#themes) for [Bootstrap v5.1.3](https://getbootstrap.com)
<p></p>

[![select2-bootstrap5 version](https://img.shields.io/badge/select2--bootstrap5-v1.0.0-success)](https://github.com/mortezafs/select2-bootstrap5-theme/releases)
[![License](https://img.shields.io/badge/license-MIT-blue)](http://opensource.org/licenses/MIT)
[![Bootstrap](https://img.shields.io/badge/bootstrap-v5.x-blue)](https://getbootstrap.com)
![select2-bootstrap5-rtl](https://img.shields.io/badge/rtl-supported-important)
![select2-bootstrap5-ltr](https://img.shields.io/badge/ltr-supported-important)
![select2-bootstrap5-dark](https://img.shields.io/badge/Dark%20mode-Supported-green)

### Compatibility

Built and tested with Bootstrap v5.1.3 and Select2 v4.0.13 in the latest Chrome, Firefox.
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

Note: if you want to us dark style you can use bootstrap5-dark theme instance of bootstrap5, or you can add a .dark or .dark-theme for your body tag. We don't use  @media (prefers-color-scheme: dark) in styling to prevent limiting developers in type of dark mode style designing.

### Changelog

#### 0.0.1-beta.1
The first release

#### 0.0.2
FIx arrow position in dropdowns,
Fix some bad padding in styles,
And some major improvement.

#### 1.0.0
Fix dropdown size problem, 
Add dark style to using in dark mode, 
And some major improvement.

#### 1.0.1
Fix bad style in new select2 version for remove btn in multi select,
Add .dark and .dark-theme class on body for dark mode auto styling.

#### Copyright and license

This theme created by Morteza Fard Saffari ([ArizoTech Co.](https://arizotech.com)) And licensed under MIT License
