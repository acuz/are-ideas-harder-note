# are-ideas-harder-note

Password-protected working note. The published page (`index.html`) is an
**AES-256-GCM encrypted blob**, decrypted client-side in the browser after the
viewer enters the shared passphrase (PBKDF2-SHA256 key derivation). Nothing is
readable without the passphrase.
