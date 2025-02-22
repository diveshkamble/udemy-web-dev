# HTML Fundamentals Notes

## DOCTYPE html

In HTML, the doctype is the required `<!doctype html>` preamble found at the top of all documents. Its sole purpose is to prevent a browser from switching into so-called ["quirks mode"](https://developer.mozilla.org/en-US/docs/Web/HTML/Quirks_Mode_and_Standards_Mode) when rendering a document; that is, `<!doctype html>` doctype ensures that the browser makes a best-effort attempt at following the relevant specifications, rather than using a different rendering mode that is incompatible with some specifications.
The doctype is case-insensitive.

## head

The `<head>` HTML element contains machine-readable information (metadata) about the document, like its title, scripts, and style sheets. There can be only on `<head>` element in an HTML document

Elements that can be inside `<head>`:

- `<title>`: The `<title>` HTML element defines the document's title that is shown in a browser's title bar or a page's tab. It only contains text; tags within the element are ignored.
- `<base>`: The `<base>` HTML element specifies the base URL to use for all relative URLs in a document. There can be only one `<base>` element in a document.
- `<link>`: The `<link>` HTML element specifies relationships between the current document and an exter
- `<style>`
- `<meta>`
- `<script>`
- `<noscript>`: The `<noscript>` HTML element defines a section of HTML to be inserted if a script type on the page is unsupported or if scripting is currently turned off in the browser.
- `<template>`
