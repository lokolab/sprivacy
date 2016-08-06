sprivacy
========

- Version: 0.0.1
- Technologies:
  - HTML
  - JavaScript
- Compatibility:
  - Chrome 45+
  - Firefox 46+
  - Probably other browsers are also compatible.
- Dependencies:
  - null
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

First, modify the file "sprivacy.html"*:

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

Second, in the browser, enter `http://localhost/sprivacy.html`

____________________________
[*] URLs should be modified.


