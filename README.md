tre-reconnect-stream
---

Wraps a pull-stream source. If an error occurs in the source stream, and the error object has a property `pleaseRetryIn`, it re-creates the source after the given number of milliseconds.

This is usful for wrapping ssb apis returning sources returned by tre-client.

---
License: MIT
