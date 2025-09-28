# Active-Directory

> **Hands‑on, lab-friendly repository demonstrating common Active Directory (AD) enumeration and post‑compromise techniques, built for learning, blue‑team validation, and interview/demo purposes.**  
> **Use everything in this repo only in authorized lab environments. Do not attack networks you do not own or have explicit permission to test.**

---

## About this repository
This repo is a curated, ethical learning collection that walks through the typical stages of an AD engagement at a conceptual and demonstrative level:

- **Enumeration**  discovering users, groups, hosts, trusts and attack surface in a controlled lab.  
- **Credential capture**  high-level techniques for how credentials can be obtained after initial access (demonstrations in an isolated lab).  
- **Kerberoasting**  concept and defensive detection/mitigation guidance for service account ticket attacks.  
- **Lateral movement & RDP**  common patterns for moving across a Windows estate (lab-only demos).  
- **Domain Controller / NTDS.dit**  explanation of what **NTDS.dit** contains, why it’s sensitive, and how defenders should protect it.

This repo emphasizes **understanding the underlying concepts, improving defensive posture, and preparing for interviews**  not providing weaponized offense instructions.

---

## What you'll find here
- **Clear conceptual writeups** for each stage of an AD assessment (intent, risk, detection).  
- **Lab walkthroughs** (VM snapshots / references to lab setups) showing **safe, repeatable** exercises.  
- **Defensive guidance:** mitigations, monitoring signals and hardening recommendations for each technique covered.  
- **Example artifacts** for learning (logs, diagrams, and anonymized outputs)  no live production data or unsafe scripts.

---

## Who this is for
- **Red‑teamers and pentesters** wanting to practice responsibly in a lab.  
- **Blue teams** looking to understand attack techniques and improve detection/hardening.  
- **Engineers preparing technical interviews** or wanting to demonstrate AD security knowledge on GitHub.

---

## Responsible use & legal notice
By using this repository you agree to:

- **Only replicate demonstrations in lab environments you control or where you have explicit written permission.**  
- **Never use any technique here to access, modify, or exfiltrate data from systems you do not own or have authorization to test.**  
- **Follow applicable laws, industry rules, and your organization’s policies.**

**I’m committed to responsible disclosure and training**  if you believe content here could be misused or if you discover sensitive content, open an issue and I’ll address it quickly.

---

## How this helps recruiters / what this demonstrates
Including this project on your GitHub shows:

- **Practical understanding of Windows AD concepts and attack surfaces.**  
- **Ability to think like an attacker *and* design defensive controls.**  
- **Familiarity with tooling, log interpretation, and lab validation.**  
- **Clear, security-minded documentation and reproducible labs.**

**Suggested CV bullets you can adapt:**
- “Built reproducible Active Directory lab demonstrating enumeration, Kerberoasting concepts, lateral movement patterns, and DC hardening, documented detections and mitigations.”  
- “Produced hands-on AD exercises to validate endpoint and SIEM detections in a controlled environment.”

---

## Repo structure (example)

