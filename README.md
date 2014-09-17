Demonstrates the ineffectiveness of iframe sandboxing when:

1. `allow-scripts` and `allow-same-origin` are enabled
2. the outer document and the inner iframe are on the same domain

This demonstrates the problem highlighted in the first warning of the
sandbox section in https://html.spec.whatwg.org/multipage/embedded-content.html#the-iframe-element

Firefox (see [bug 752559](https://bugzilla.mozilla.org/show_bug.cgi?id=752559)) now issues
a warning to the developer console when this case is encountered.
