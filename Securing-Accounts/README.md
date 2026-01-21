Core Concepts
- **Authentication vs Authorization**
  1 Authentication = proving identity (username + password)
  2 Authorization = what you’re allowed to access after you’re in
- **Password Attacks**
  1 Dictionary (wordlists), Brute force (all combos), Credential stuffing (reused leaked creds)
- **Strength by Numbers**
  1 4-digit PIN ≈ 10,000 combos → milliseconds to crack
  2 4 letters ≈ ~7M combos → seconds
  3 4 mixed chars (letters/digits/symbols) ≈ ~78M → minutes
   **8 random mixed chars ≈ ~6 quadrillion** → practically infeasible
- **NIST Guidance**
  1 ≥ 8 characters minimum, allow long (up to 64), block common/compromised passwords

Defenses
1 Long, unique passwords (length > complexity)
2 **MFA/2FA** (prefer authenticator app over SMS)
3 Rate-limiting / lockouts
4 Password managers (iCloud Keychain, Google, Bitwarden, 1Password)
5 Passkeys (public/private key pairs) — the future of logins

Threats to Watch
1 Phishing & social engineering
2 SIM swapping (steals SMS codes)
3 Keylogging malware on untrusted devices

Assignment Work (What I did)
1 Simulated brute-forcing a 4-digit PIN; saw how fast short passwords fall
2 Compared time/space growth from 10^4 → 52^4 → 94^4 and discussed 94^8 scale
3 Wrote up takeaways on why **length + MFA** crush most attacks

Takeaways
1. Security = raise attacker cost until it’s not worth it.
2. MFA makes stolen passwords mostly useless.
3. Password managers solve the “I can’t remember long passwords” problem.
