# mi18n
Experimental Modern i18n Library

## Abstract

Inspired by the design of **gettext**, the i18n should be simple to use and instantly updated on demand.

## Initial Crazy Goal

* The server component is implemented in Python.
  * Provide the initial translation manifest.
  * Provide live updates via Server-side Push.
* The client component is implemented in JavaScript.
  * Can be used without the server component (file-based manifest), dubbed as the standalone mode.
  * The translation logic is with the client.
