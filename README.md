This repo contains HTML files for testing the behaviour of the `sandbox` attribute of the `iframe` element.

The [spec] lists 8 allowed values: `allow-forms`, `allow-modals`, `allow-pointer-lock`, `allow-popups`, `allow-popups-to-escape-sandbox`, `allow-same-origin`, `allow-scripts`, and `allow-top-navigation`.

On a fully spec-compliant browser there should be one `alert`, from the `iframe` with both `allow-modals` & `allow-scripts`. On a browser that does not handle `allow-modals` (such as Safari), there will be two `alert`s.

  [spec]: https://html.spec.whatwg.org/multipage/embedded-content.html#attr-iframe-sandbox
