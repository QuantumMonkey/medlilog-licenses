# medlilog-licenses

License registry for **MedliLog** (Anubis Lab) — the static allow-list of valid Pro purchases.

MedliLog runs 100% offline with no authentication servers. Pro entitlements are verified entirely client-side: the app computes a SHA-256 hash of the Google Play purchase receipt (via the Web Crypto API) and checks it against this registry.

- **Registry file:** [`verify.json`](verify.json)
- **Served via GitHub Pages:** https://quantummonkey.github.io/medlilog-licenses/verify.json

No personal data is stored here — only opaque license hashes.
