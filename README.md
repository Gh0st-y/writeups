# 🛡️ Security Writeups — Ruan van der Merwe

A growing collection of my capture-the-flag (CTF) and hands-on security lab writeups,
documenting my methodology as I build offensive-security skills alongside a software-development background.

> Final-year BSc Information Technology student (North-West University) · Software developer at Datanamix ·
> **2026 SANReN Cyber Security Challenge national finalist.**
> Moving deliberately from building software to breaking and securing it.

🔗 **LinkedIn:** https://linkedin.com/in/ruan-v-d-merwe

---

## About this repo

Each writeup walks a target from initial reconnaissance through to full compromise, with the reasoning
behind every step, not just the commands that worked. The aim is to show *how I approach a problem*,
not only that a box was solved.

All targets are intentionally vulnerable machines from legal, authorised practice platforms
(**TryHackMe**, **VulnHub**). Nothing in this repository involves testing against systems I don't have
permission to attack.

---

## Writeups

| Box / Room | Platform | Difficulty | Key techniques | Writeup |
|------------|----------|------------|----------------|---------|
| Mr. Robot | TryHackMe | Medium | Web enumeration, WordPress exploitation, reverse shell, hash cracking, SUID privilege escalation | [Read →](./mr-robot/writeup.md) |
| *In progress* | VulnHub | — | Broadening exposure to new environments and attack paths | — |

---

## Skills & tools demonstrated

- **Reconnaissance & enumeration** — Nmap, Gobuster, directory brute-forcing
- **Web exploitation** — CMS (WordPress) abuse, credential discovery, reverse shells
- **Password attacks** — John the Ripper, Hydra, custom wordlists
- **Linux privilege escalation** — LinPEAS, SUID binary abuse, interactive-shell escapes
- **Post-exploitation** — manual enumeration and flag retrieval

**Development background:** C# / .NET, REST APIs, SQL, Azure — which I lean into for application and API security.

---

## Repository structure

```
security-writeups/
├── README.md
├── mr-robot/
│   ├── writeup.md
│   └── images/
└── <next-box>/
    ├── writeup.md
    └── images/
```

---

## Contact

- **LinkedIn:** https://linkedin.com/in/ruan-v-d-merwe
- **Email:** ruanvandermerwe208@gmail.com
