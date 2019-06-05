# CKEditor 5 inline editor build with alignment [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Check%20out%20ckeditor5-build-inline-alignment%20on%20GitHub&url=https://github.com/isatria/ckeditor5-build-inline-alignment)

[![npm version](https://badge.fury.io/js/ckeditor5-build-inline-alignment.svg)](https://github.com/isatria/ckeditor5-build-inline-alignment)
[![npm download](https://img.shields.io/npm/dt/ckeditor5-build-inline-alignment.svg)](https://github.com/isatria/ckeditor5-build-inline-alignment)
[![npm license](https://img.shields.io/npm/l/ckeditor5-build-inline-alignment.svg)](https://github.com/isatria/ckeditor5-build-inline-alignment)

The inline editor build for CKEditor 5 with pre install alignment and word counter plugin. Read more about the [inline editor build](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/overview.html#inline-editor" target="_blank)

![alt text](https://i.ibb.co/2K7L2pD/Screenshot-2019-05-31-at-11-51-37-PM.png)


[Google](https://google.com" target="_blank)

## **Pre-Install Plugin**

* Char Count
* Alignment

## **Quick start**

First, install the build from npm:

```javascript
npm install --save ckeditor5-build-inline-alignment
```

And use in your JavaScript application:

```javascript
import InlineEditor from 'ckeditor5-build-inline-alignment';

// Or using the CommonJS version:
// const InlineEditor = require( '@ckeditor/ckeditor5-build-inline' );

InlineEditor.create(document.querySelector('#editor'))
	.then((editor) => {
		window.editor = editor;
	})
	.catch((err) => {
		console.error(err.stack);
	});
```

**Note:**

If you work on **react applications** and use _stateless_ component, please use the CommonJS version :
`const InlineEditor = require('@ckeditor/ckeditor5-build-inline')` to avoid build failure caused by using _SSR_.

## **External links**

-   [ckeditor5-iswordcount on npm](https://www.npmjs.com/package/ckeditor5-iswordcount)
-   [ckeditor5-iswordcount on Github](https://github.com/isatria/ckeditor5-iswordcount)
-   [ckeditor5-alignment on npm](https://www.npmjs.com/package/@ckeditor/ckeditor5-alignment)
-   [ckeditor5-alignment on Github](https://github.com/ckeditor/ckeditor5-alignment)

## **License**

**ckeditor5-build-inline-alignment** 5 is an Open Source plugin
