CORE CONCEPTS: Attacks and Defenses
Phishing:
Phishing is a social engineering attack that tricks users into trusting fake emails or websites that look legitimate
Defense is user awareness, checking URLs carefully, HTTPS validation, and email filtering

Cross Site Scripting XSS:
XSS occurs when a website includes user input directly in a page and the browser executes it as JavaScript
Attackers can steal cookies, hijack sessions, or run malicious scripts
Defense is escaping user input, sanitizing inputs, and using Content Security Policy headers

SQL Injection:
SQL injection happens when user input is treated as part of a database query and changes its logic
Attackers can read, modify, or delete database data
Defense is prepared statements and parameterized queries which separate data from SQL code

Cross Site Request Forgery CSRF:
CSRF tricks a logged in user’s browser into sending unintended requests to a website
The attack relies on the browser automatically including cookies
Defense is CSRF tokens that verify requests were intentionally made by the user

Buffer Overflow:
A buffer overflow happens when a program writes more data to memory than it allocated
This can overwrite return addresses and allow execution of attacker code
Defense includes bounds checking, modern memory protections, and safer programming languages

Code Injection General:
Code injection occurs when user input is executed as code in any context HTML SQL or system commands
Defense is input validation, escaping dangerous characters, and never trusting user input

Web Security Principles:
1. Client side validation improves user experience but is not secure
2. Server side validation is required because users can bypass browser checks
3. GET requests should not change server state because they can be triggered automatically
4. POST requests are safer for sensitive data and state changes
5. Content Security Policy restricts where scripts and styles can be loaded from to reduce XSS risk

Takeaway:
1. We should never trust user input and should assume that any input can be malicious.
2. All input must be validated and verified on the server side, not just in the browser.
3. As users, we should verify the integrity and authenticity of websites and software before clicking links, entering credentials, or running commands, because attackers often exploit trust too.
