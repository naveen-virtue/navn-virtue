# Simulated Nuclei Findings — Safe Demo

This repository contains a safe, simulated web page that displays mock Nuclei scanner findings for demo/training purposes.

Files:
- `vulnerable_test_page.html` — A self-contained HTML file that displays five simulated Nuclei findings (2 critical, 3 high). No real vulnerabilities or exploit code are present.
- `templates/` — Contains simple Nuclei detection templates (string matches) that will produce the five mock findings when run against the demo page.

Important notes:
- This is a *simulation* only. The page does not create, host, or demonstrate actual security vulnerabilities or exploit payloads.
- Use for UI demos, training, or testing parsing/visualization workflows only.
- For hands-on vulnerability testing and learning, use purpose-built intentionally vulnerable projects such as:
  - OWASP Juice Shop: https://owasp.org/www-project-juice-shop/
  - DVWA (Damn Vulnerable Web App): https://dvwa.co.uk/
  - Mutillidae or WebGoat
- Always test only on systems you own or have explicit permission to test. Unauthorized scanning or exploitation is illegal and unethical.
- If you want this file added to a repository or adapted to output a specific Nuclei JSON/YAML format, tell me the target format and I’ll adapt it.

License: Public domain for educational/demo usage.