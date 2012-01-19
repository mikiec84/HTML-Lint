HTML-Lint
=========

HTML-Lint is a code quality bookmarklet designed to supplement HTML validation by identify coding practices that pass validation, but are less than ideal.

How to Use:
-----------

1.	Copy the code below:

	```javascript
	javascript: (function(){'use strict';var script = document.createElement('script');script.src = 'http://dl.dropbox.com/u/8864275/HTML-Lint/html-lint.js';script.id = 'html-lint-js';document.body.appendChild(script);}());
	```

2.	Create a new bookmark.

3.	Set the name to 'HTML-Lint' and paste the above as the URL.

<!--
What it tests:
--------------
--->