sprivacy
========
**This is development version.<br> For production version see
<https://github.com/lokolab/sprivacy/releases/v0.0.1>**
- Version: 0.0.1-dev
- Technologies:
  - HTML
  - JavaScript
- Compatibility:
  - Chrome 45+
  - Firefox 46+
  - Other browsers should be compatible.
- Copyright / Authors:
  - Krystian Pietruszka <kpietru@lokolab.net>
- Licenses:
  - MIT <http://opensource.org/licenses/MIT>
- Download: <https://github.com/lokolab/sprivacy/releases>
- Homepage: <http://www.lokolab.net>

Send automatic requests to websites in order to protect privacy.
________________________________________________________________

Example usage
-------------

First, modify the file `sprivacy.html`*:

    ...
    var wwwUrls = [
        'http://example.com',
        'http://example.com/blabla',
        // Add links here.
        // ...
    ];
    var searchUrls = [
        'http://example.com/search?q=abc',
        'http://example.com/search?q=xyz',
        // Add links here.
        // ...
    ];
    ...

Second, in the browser, enter file `sprivacy.html`

____________________________
[*] URLs should be modified.


