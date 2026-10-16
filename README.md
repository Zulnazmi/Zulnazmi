# Hi, I'm Zul 👋

**Aspiring penetration tester** building hands-on security skills through tooling, labs, and a security-focused final year project. Currently looking for a **cybersecurity internship**.

## What I'm focused on
- Offensive security: reconnaissance, web enumeration, and learning the full pentest workflow
- Writing security tools in Python to understand how common scanners work under the hood
- Clear technical documentation and reporting, since findings only matter if they can be communicated

## Final Year Project: [AmanahTrack](https://github.com/Zulnazmi/amanahtrack)
A donation integrity platform for mosques, built around a Raspberry Pi 5 smart donation box. It records donations in a **tamper-evident SHA-256 hash-chain ledger**, enforces Shariah fund-spending rules, and lets a committee review photo-backed alerts and verify evidence in a mobile app.

- **Tamper detection:** any edit to a ledger entry, alert, or evidence photo is detected and traced to the exact entry
- **Signed device messaging:** the box signs events with HMAC-SHA256; the server re-verifies signatures and photo hashes
- **Access control:** JWT auth, four roles, per-institution data isolation, and separation of duties
- **Stack:** Python, FastAPI, SQLAlchemy, React Native (Expo), Raspberry Pi 5
- **Testing:** 37 automated tests, including tamper and cross-tenant access cases
- **Status:** backend and mobile app complete; box readings are simulated in the demo, and live sensor streaming is in progress

## Security Tools
| Project | What it does |
|---|---|
| [port-scanner](https://github.com/Zulnazmi/port-scanner) | Multithreaded TCP port scanner with service detection and banner grabbing |
| [dir-enum](https://github.com/Zulnazmi/dir-enum) | Web directory/file enumerator with soft-404 detection and redirect reporting |
| [log-analyzer](https://github.com/Zulnazmi/log-analyzer) | Defensive SSH auth-log analyzer that detects brute force, password spraying, and possible compromise |

All three are dependency-free Python, include unit tests, and are documented with usage and limitations.

## Tech
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

## Next up
- Hands-on labs on TryHackMe and Hack The Box
- Web application vulnerabilities (OWASP Top 10)
- Network fundamentals and traffic analysis

## Ethics
All tools and testing are done only on systems I own or have explicit permission to test.
