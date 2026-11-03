# Gorilla Tables (web)

Password-protected web copy of Gorilla Tables, Gerarden Fabrication's in-house fixture table designer
(fabricationtables.com).

`index.html` is a sign-in page. The app itself is inside it, encrypted (AES-256-GCM, key from the
password through PBKDF2-SHA256), so nothing in this repository can be read without the password.
The source code is not kept here.

- Site: https://safetydav3.github.io/gorilla-tables/
- "Keep me signed in" remembers the device; the Sign out button (or adding `?lock` to the address) forgets it.
- To update: rebuild with `tools/web.py <password> <folder>` in the Gorilla Tables project and replace `index.html`.

The drawings and laser files the app produces are for the buyer's own use. Reselling, sharing,
publishing or redistributing them, or selling parts cut from them, is not permitted without written
permission from Gerarden Fabrication.
