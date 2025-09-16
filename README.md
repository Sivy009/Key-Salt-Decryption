Uses the same PBKDF2 + AES-256-GCM approach as the encryption script
Takes base64-encoded encrypted data as input
Extracts the nonce and ciphertext, then decrypts to recover the original passphrase
