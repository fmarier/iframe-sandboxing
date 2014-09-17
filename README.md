Demonstrates the ineffectiveness of iframe sandboxing when:

1. `allow-scripts` and `allow-same-origin` are enabled
2. the outer document and the inner iframe are on the same domain

This demonstrates the problem highlighted in the first warning of the
sandbox section in https://html.spec.whatwg.org/multipage/embedded-content.html#the-iframe-element
