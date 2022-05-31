# Credit Card Autocomplete
Testing the autocomplete attributes for Credit Cards stored in the web browser.

Built to figure out how to get a 2 digit year into the expiry year field, when Chrome was sending 4 digits, and the last 2 were being truncated. "2024" -> "20", not "24" as desired.

The page for testing is located in the demo folder, so that it can be used in JSFiddle.
Try this out in [JSFiddle.net](https://jsfiddle.net/gh/get/library/pure/JamesW75/credit-card-autocomplete/tree/main/demo/)

References
* https://html.spec.whatwg.org/multipage/form-control-infrastructure.html#autofill-field
* https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/autocomplete
