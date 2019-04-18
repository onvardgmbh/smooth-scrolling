Smooth Scrolling
================
Smoothly scroll to a given position on the page.

## Usage
Adding smooth scrolling to all anchors that link to fragment IDs on the same page, when using a bundler:
```js
require('smooth-scrolling');
smoothScrollToAllFragments();
```

Explicitly scroll to a specific position smoothly:
`smoothScrollToPx(target, callback, duration);`

Basic usage without bundling:
```html
<script src="smooth-scrolling.js"></script>
<script>
	smoothScrollToPx(1000, function() {console.log('done')}, 1000);
</script>
```
