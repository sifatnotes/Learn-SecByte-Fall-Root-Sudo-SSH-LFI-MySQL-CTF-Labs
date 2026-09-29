# Learn-SecByte-Fall-Root-Sudo-SSH-LFI-MySQL-CTF-Labs
Hands-on cybersecurity and CTF labs covering network mapping, Linux privilege escalation, sudo, command history, file discovery, SSH keys, LFI, MySQL access, and root-focused security workflows.
# Learn SecByte Fall, Root, Sudo, SSH, LFI & MySQL CTF Labs

## Introduction

This repository contains hands-on cybersecurity and CTF labs focused on network mapping, Linux enumeration, sudo security, privilege escalation, command-history analysis, file discovery, SSH key hunting, Local File Inclusion (LFI), MySQL access, and controlled root-access workflows.

The collection is designed for cybersecurity students, CTF players, penetration testers, SOC analysts, and security learners developing practical Linux and web security skills in authorized environments.

## Lab Collection

| # | Lab | Main Topic |
|---|---|---|
| 1 | Map the Box | Network mapping, reconnaissance |
| 2 | Fall Into Root | Linux privilege escalation |
| 3 | Falling to Root | Root access, Linux security |
| 4 | Sudo All: One Command to Root | Sudo, privilege escalation |
| 5 | Sudo Shadows | Sudo, Linux enumeration |
| 6 | History Harvest | Command history, information discovery |
| 7 | Fall File Sleuth | File discovery, Linux enumeration |
| 8 | Fall Into Linux Clues | Linux reconnaissance |
| 9 | Keyfall SSH Hunt | SSH keys, credential discovery |
| 10 | Keyfall | SSH, key discovery |
| 11 | LFI Home Directory Harvest | LFI, information disclosure |
| 12 | MySQL Door Host Denied | MySQL, service security |

## Direct Lab Links

1. https://learn.secbyte.org/ctf/map-the-box
2. https://learn.secbyte.org/ctf/fall-into-root
3. https://learn.secbyte.org/ctf/falling-to-root
4. https://learn.secbyte.org/ctf/sudo-all-one-command-to-root
5. https://learn.secbyte.org/ctf/sudo-shadows
6. https://learn.secbyte.org/ctf/history-harvest
7. https://learn.secbyte.org/ctf/fall-file-sleuth
8. https://learn.secbyte.org/ctf/fall-into-linux-clues
9. https://learn.secbyte.org/ctf/keyfall-ssh-hunt
10. https://learn.secbyte.org/ctf/keyfall
11. https://learn.secbyte.org/ctf/lfi-home-directory-harvest
12. https://learn.secbyte.org/ctf/mysql-door-host-denied

## Categories

### Network Mapping & Reconnaissance

- Map the Box
- Fall Into Linux Clues
- Fall File Sleuth

These labs focus on identifying accessible resources, gathering system information, and building an understanding of an authorized target.

### Sudo & Linux Privilege Escalation

- Fall Into Root
- Falling to Root
- Sudo All: One Command to Root
- Sudo Shadows

Practice Linux privilege-escalation concepts by examining sudo permissions, execution contexts, and system configuration.

### Files & Command History

- History Harvest
- Fall File Sleuth
- Fall Into Linux Clues

These challenges focus on locating useful information in files, shell history, and other Linux artifacts during authorized CTF investigations.

### SSH & Key Discovery

- Keyfall SSH Hunt
- Keyfall

Practice identifying SSH-related artifacts and understanding how exposed or improperly protected keys can affect system security.

### LFI & Information Disclosure

- LFI Home Directory Harvest

This challenge focuses on Local File Inclusion and the security implications of exposing local resources through a vulnerable application.

### MySQL Security

- MySQL Door Host Denied

Explore MySQL service behavior and access-control concepts in a controlled CTF environment.

## Learning Path

A practical progression through this collection is:

1. **Start with network mapping** — identify services and build an initial attack-surface overview.
2. **Practice Linux enumeration** — inspect users, files, permissions, processes, and configuration.
3. **Study command history** — understand how shell history can reveal useful security information.
4. **Investigate file discovery** — search for configuration files and other relevant artifacts.
5. **Explore SSH keys** — understand key-based authentication and the risks of exposed credentials.
6. **Study sudo security** — inspect permitted commands and understand privilege boundaries.
7. **Connect privilege-escalation findings** — analyze how multiple Linux weaknesses can form an attack path.
8. **Study LFI** — understand how vulnerable file-inclusion functionality can expose local information.
9. **Explore MySQL access controls** — investigate database-service behavior and authentication boundaries.

## How to Use the Labs

1. Select a lab from the direct-link index.
2. Read the objective and authorized scope.
3. Begin with reconnaissance before attempting exploitation.
4. Enumerate services, users, files, permissions, and application behavior.
5. Document useful findings and potential attack paths.
6. Analyze sudo, SSH, LFI, or MySQL behavior according to the challenge.
7. Perform testing only against the provided lab environment.
8. Record the techniques used and the underlying vulnerability.
9. Review defensive controls and remediation concepts after completing the challenge.

## Skills Covered

- Network reconnaissance
- Linux enumeration
- File discovery
- Command-history analysis
- Sudo enumeration
- Linux privilege escalation
- SSH reconnaissance
- SSH key discovery
- Credential discovery
- Local File Inclusion (LFI)
- Information disclosure
- MySQL service analysis
- Access-control concepts
- Root-access workflows
- CTF methodology
- Penetration-testing fundamentals

## Learn SecByte

These exercises are sourced from Learn SecByte and are intended for practical cybersecurity and ethical hacking education.

## Disclaimer

These resources are for **educational and authorized security testing purposes only**. Perform reconnaissance, enumeration, authentication testing, exploitation, and privilege-escalation activities only against systems you own or have explicit permission to test. Do not use these techniques against unauthorized systems, accounts, applications, networks, or services.
