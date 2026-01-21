CORE CONCEPTS:
1. Hashing is a one way process used to verify data integrity
2. Encryption is reversible and is used to keep data confidential
3. Salting adds randomness to passwords before hashing to prevent identical hashes
4. Symmetric encryption uses the same secret key to encrypt and decrypt
5. Asymmetric encryption uses a public key and a private key
6. Digital signatures prove authenticity and integrity of a message
7. TLS encrypts data in transit but not end to end
8. End to end encryption prevents service providers from reading data

Attacks & Risks:
1. Database hacks involve active exploitation to steal data
2. Database leaks occur due to misconfiguration or human error
3. Rainbow table attacks exploit unsalted password hashes
4. Man in the middle attacks intercept data in transit
5. Certificate authority compromise breaks trust on the web
6. Hash collisions allow different inputs to produce the same digest

Defenses:
1. Strong modern hash functions like SHA 256 instead of MD5
2. Salting passwords to defeat rainbow tables
3. TLS certificates to verify domain ownership
4. Digital signatures to verify sender authenticity
5. Backups to protect against data loss and ransomware
6. Password managers to prevent credential reuse

Assignments and exercises:
1. Distinguished between database hacks and database leaks
2. Explained why deleted files may still be recoverable
3. Explained how MD5 is used to verify file integrity
4. Identified differences between ciphers and hashes
5. Used Caesar cipher patterns to decrypt a message
6. Explained how public key cryptography verifies signatures

Takeaways:
Securing data is about integrity, confidentiality, and authenticity, and weak cryptography or poor practices can undermine all three even if encryption is used.
