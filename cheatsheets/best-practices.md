# Cryptography Best Practices

- Use strong algorithms (AES-256, RSA-2048+, SHA-256+).
- Never roll your own crypto.
- Rotate & manage keys securely (use KMS, HSM).
- Prefer libraries over custom implementations.
- Verify certificates and signatures properly.
- Stay updated: deprecate weak algorithms (MD5, SHA-1, DES, 3DES).
- Use random number generators designed for crypto (CSPRNG).
