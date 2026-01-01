# CS50 Cybersecurity: Securing Accounts

# Key Concepts
- **Authentication vs Authorization**
  - Authentication = proving identity (username + password)
  - Authorization = what you’re allowed to access after you’re in
- **Password Attacks**
  - Dictionary (wordlists), Brute force (all combos), Credential stuffing (reused leaked creds)
- **Strength by Numbers**
  - 4-digit PIN ≈ 10,000 combos → milliseconds to crack
  - 4 letters ≈ ~7M combos → seconds
  - 4 mixed chars (letters/digits/symbols) ≈ ~78M → minutes
  - **8 random mixed chars ≈ ~6 quadrillion** → practically infeasible
- **NIST Guidance**
  - ≥ 8 characters minimum, allow long (up to 64), block common/compromised passwords

## Defenses
- Long, unique passwords (length > complexity)
- **MFA/2FA** (prefer authenticator app over SMS)
- Rate-limiting / lockouts
- Password managers (iCloud Keychain, Google, Bitwarden, 1Password)
- Passkeys (public/private key pairs) — the future of logins

- 
## Threats to Watch
- Phishing & social engineering
- SIM swapping (steals SMS codes)
- Keylogging malware on untrusted devices

## Assignment Work (What I did)
- Simulated brute-forcing a 4-digit PIN; saw how fast short passwords fall
- Compared time/space growth from 10^4 → 52^4 → 94^4 and discussed 94^8 scale
- Wrote up takeaways on why **length + MFA** crush most attacks

## My Takeaways
1. Security = raise attacker cost until it’s not worth it.
2. MFA makes stolen passwords mostly useless.
3. Password managers solve the “I can’t remember long passwords” problem.
