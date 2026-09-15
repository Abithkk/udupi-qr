# udupi-qr

Permanent addresses printed on Udupi POS table QR codes.

Each folder (`staging/`, later `production/`) holds a small page that forwards a
diner to the restaurant's current menu address, recorded in that folder's
`address.json`. The restaurant PC updates `address.json` automatically whenever
its tunnel address changes. Nothing here is edited by hand, and nothing here is
secret: that address only ever serves the diner's menu.

The page's source is `qr-relay/index.html` in the private udupi-pos repo.
