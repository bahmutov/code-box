# code-box

Extremely simple light box with syntax highlighting specifically for showing code

## Usage

* include jQuery
* include CSS and JavaScript
* make CodeBoxes from *pre* elements

```html

<head>
...
<link rel="stylesheet" href="code-box.css" />
<script src="http://code.jquery.com/jquery-2.0.3.min.js"></script>
<script src="code-box.js"></script>
</head>
<body>

...

<pre><code language="javascript">
var foo = bar();
</code></pre>

....
<script>
  $(function () {
    CodeBox('pre');
  });
</script>
```

You can specify most of the languages using `<code language="javascript">` syntax, *javascript* by default.

## 3<sup>rd</sup> Party Libraries

I used two excellent libraries to open lightbox and perform syntax highlighting:

* [Magnific Popup](http://dimsemenov.com/plugins/magnific-popup) - simple and powerful lightbox
* [Prism](http://prismjs.com) - simple and versatile syntax highlighting in JavaScript

### Details

Author: Gleb Bahmutov <gleb.bahmutov@gmail.com> [@bahmutov](https://twitter.com/bahmutov)
License: MIT
Copyright &copy; 2013 Gleb Bahmutov
