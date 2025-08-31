# Symmetric vs Asymmetric Cryptography

## Symmetric
- One key used for both **encryption** & **decryption**.
- Fast, efficient.
- Key distribution is a challenge.
- Examples: AES, DES, 3DES, ChaCha20.

## Asymmetric
- Uses **public key** (encrypt/verify) & **private key** (decrypt/sign).
- Slower, but solves key distribution problem.
- Often used for secure key exchange.
- Examples: RSA, ECC, Diffie-Hellman.

## Hybrid
- Real-world systems often use both.
- Example: TLS → Asymmetric exchange to share Symmetric session key.
