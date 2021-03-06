# Sniffly2

Sniffly2 is a variant of
[Sniffly](https://github.com/diracdeltas/sniffly/tree/master)
which abuses HTTP Strict Transport Security headers and the Performance Timing
API in order to sniff your browsing history in Chromium-based browsers.

## Demo

Visit http://diracdeltas.github.io/sniffly in Chrome/Chromium/Brave/etc. with HTTPS
Everywhere disabled.

Caveats:

* does not work on mobile or Firefox
* does not work over HTTPS due to mixed content blocking.
* adblockers may taint results

## Acknowledgements

* [crbug436451](https://bugs.chromium.org/p/chromium/issues/detail?id=436451), reported by `imfaster...@gmail.com`, for the idea of probing port 443 over HTTP
* Scott Helme for providing an initial list of HSTS hosts
