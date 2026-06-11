# Lenomila Shelf

Signed public Android release catalog for Tony/Lenomila apps.

The Android client fetches catalog/index.json, verifies catalog/index.json.sig with the embedded public key, and opens release pages in the browser. It does not request package-install permission or install APKs itself.

Catalog files:

- catalog/index.json
- catalog/index.json.sig
- catalog/index-public-key.der.b64
