Abbread
=======

Spreads a `title` attribute of an `abbr` element


SYNOPSIS
--------

A `title` attribute of an `abbr` element is important, but writing `title`
attribute with every `abbr` element is annoying. This small JavaScript library
spreads first `abbr` element’s `title` attribute to other *same* `abbr`
element(s).

For example:

```html
<p><abbr title="HyperText Markup Language">HTML</abbr> is dead, long live <abbr>
HTML</abbr>!</p>
```

With this library, it is converted to:

```html
<p><abbr title="HyperText Markup Language">HTML</abbr> is dead, long live <abbr
title="HyperText Markup Language">HTML</abbr>!</p>
```

Love hover.


USAGE
-----

Put `dist/abbread.js` into `head` element of your HTML document.

```html
<script defer src="/js/abbread.js"></script>
```

Don’t forget `defer` attribute!


LICENSE
-------

MIT
