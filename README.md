# Sean Finegan — Cybersecurity Portfolio

Cybersecurity engineer and lifelong learner documenting my hands-on journey through Capture-the-Flag (CTF) competitions, labs, and projects.

[LinkedIn](https://www.linkedin.com/in/seanpfin) · CISSP · GSEC · GCIH · GCIA · Student, SANS Technology Institute (B.S. Applied Cybersecurity, 2026)

---

## About Me

I spent 21 years in the U.S. Air Force, starting as a radar electronics technician and working my way into network engineering. The longer I spent building and maintaining networks, the more my attention shifted from *keeping them running* to *keeping them safe* — patching vulnerabilities, preparing for compliance inspections, and eventually managing a defensive cyber operations team for the U.S. Space Force. That shift is what pulled me into cybersecurity for good.

Today I work as a cross domain solutions engineer, and I'm finishing my bachelor's degree in Applied Cybersecurity at SANS. Even with years in the field, I'd never competed in a CTF until this year — so this portfolio is where I'm documenting what I'm learning by actually doing.

---

## National Cyber League (NCL) — Fall 2026

This was my first CTF experience. I competed in both the **Individual Game** and the **Team Game**.

### Reflection

Going in, CTFs felt intimidating. I had plenty of real-world experience, but solving puzzles against the clock is a different skill. What I found was that most challenges reward patience and organization more than genius: enumerate everything, take notes, and follow the trail one clue at a time.

A few lessons I'm taking with me:

- **Re-enumerate after every new foothold.** Several times, new credentials or access revealed things that were invisible a moment earlier. Going back and re-checking became a habit.
- **Understand the data, not just the tool.** Cracking passwords came down to understanding exactly how the data was encoded, then building the attack around that instead of just throwing a wordlist at it.
- **Verify your sources.** In the OSINT challenges, the answer that shows up first and fits a little too neatly isn't always the true one. Tracing information back to a primary source mattered more than finding it fast.
- **Read the target's own tools.** Some of my biggest breakthroughs came from reading a script or config to see how something was *supposed* to work, then using that intended path.

### Highlights

- Built custom **Hashcat mask attacks** and audited password hashes in my home lab with Hashcat and John the Ripper
- Worked through **enumeration and Linux privilege escalation** problems using SMB, SSH, and `sudo` misconfigurations
- Practiced **OSINT** research, including spotting deliberately planted misinformation
- Turned what I learned into reusable notes and cheat sheets for future competitions

### Score Reports

- **Individual Game Score Report:** *link coming soon*
- **Team Game Score Report:** *link coming soon*

*In keeping with NCL rules, this portfolio does not include challenge-specific write-ups or solutions.*

---

## Skills & Tools

| Area | Tools / Topics |
|------|----------------|
| Password auditing | Hashcat, John the Ripper |
| Enumeration & networking | Nmap, smbclient, SSH, Wireshark, tcpdump |
| Scripting | Python, Bash |
| Platforms | Linux (Kali, Red Hat), Windows |

---

## What's Next

- Write-ups from non-NCL CTFs, using a structured write-up template
- Home lab: building a dedicated server to run a local large language model for security experimentation
- Small Python and Bash tools for security tasks
