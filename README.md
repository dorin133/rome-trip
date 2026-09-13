# Rome

A private travel day-plan, published as a single password-protected page.

The page is encrypted at rest with AES-256-GCM; the key is derived from the
password with PBKDF2-SHA256 (600,000 iterations). Nothing in this repository
is readable without it.
