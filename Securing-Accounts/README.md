Core Concepts:
Authentication vs Authorization
1. Authentication means proving who you are such as username and password
2. Authorization means what you are allowed to access after logging in

Password Attacks:
1. Dictionary attacks use common wordlists
2. Brute force tries every possible combination
3. Credential stuffing uses leaked usernames and passwords

Strength by Numbers:
1. Four digit PIN has about 10000 combinations and can be cracked very fast
2. Four letters has about 7 million combinations and takes seconds
3. Four mixed characters has about 78 million combinations and takes minutes
4. Eight random mixed characters has trillions of combinations and is not practical to crack

NIST Guidance:
1. Minimum of 8 characters
2. Allow long passwords up to 64 characters
3. Block common or compromised passwords

Defenses:
1. Use long and unique passwords
2. Use MFA or 2FA preferably with an authenticator app
3. Use rate limiting or account lockouts
4. Use password managers
5. Use passkeys based on public and private keys

Threats to Watch:
1. Phishing and social engineering
2. SIM swapping to steal SMS codes
3. Keylogging malware on unsafe devices

Assignment Work:
1. Tested brute forcing a four digit PIN and saw how fast it fails
2. Compared password sizes and how attack time grows as length increases
3. Wrote conclusions on why length plus MFA stops most attacks

Takeaways:
1 Security is about making attacks not worth the effort
2 MFA makes stolen passwords far less useful
3 Password managers remove the need to remember long passwords
