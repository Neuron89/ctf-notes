# ctf-notes

Study notes for capture-the-flag (CTF) security challenges: curated lists of wargames, tutorials, reference material, and tools, plus level-by-level write-ups for wargames worked through so far.

> **Scope:** Everything here relates to platforms that are built for legal, educational practice (OverTheWire, picoCTF, Hack The Box, and similar). The techniques are documented for learning and should only be used on systems you own or are explicitly authorised to test.
>
> **Spoilers:** The write-ups contain solutions and level passwords. Attempt the levels first.

## Index

| Section | Contents |
|---|---|
| [Wargames](Database/Wargames.md) | Always-online CTF platforms and practice ranges |
| [Tutorials](Database/tutorials.md) | Introductory guides and video channels for getting started |
| [Info about CTFs](<Database/Info about CTFs.md>) | General sites, wikis, cheat sheets, and write-up collections |
| [Resources](Database/Resources.md) | Open-source tools by category: networking, exploitation, web, passwords, forensics, steganography |
| [Write-ups](Database/Wargames) | Worked solutions, organised by wargame |

## Write-ups

### OverTheWire: Natas (web security)

| File | Contents |
|---|---|
| [Levels 0-5](<Database/Wargames/natas/1. level 0-5.md>) | Walkthrough notes, levels 0 to 5 |
| [Levels 6-10](<Database/Wargames/natas/2. level 6-10.md>) | Walkthrough notes, levels 6 to 10 |
| [Levels 11-16](<Database/Wargames/natas/3. level 11-16.md>) | Walkthrough notes from level 11 onward (in progress) |
| [Passwords](Database/Wargames/natas/passwords.md) | Level passwords collected along the way |
| [scripts/level11.php](Database/Wargames/natas/scripts/level11.php) | Helper script for level 11 |

## Recommended platforms

A short list of the platforms used most often. The [full wargames list](Database/Wargames.md) is more extensive.

### OverTheWire

<https://overthewire.org/wargames/>

Shell- and web-based wargames in increasing order of difficulty: Bandit, Natas, Leviathan, Krypton, Narnia, Behemoth, Utumno, Maze, Vortex, Manpage, Drifter, and FormulaOne.

- **Bandit** is the entry point. It teaches command-line navigation, file searching, and the standard Unix tools.
- **Natas** covers server-side web security.
- The later games move into binary exploitation and are considerably harder.

### picoCTF

<https://picoctf.org/>

A beginner-friendly CTF run by Carnegie Mellon University, originally aimed at high-school students, with a large library of learning resources. Categories: web exploitation, cryptography, reverse engineering, forensics, binary exploitation, and general skills.

### Hack The Box

<https://www.hackthebox.com/>

Regularly rotating machines and challenges with a public leaderboard. Widely recognised by employers.

### GOAD (Game of Active Directory)

<https://github.com/Orange-Cyberdefense/GOAD>

A self-hosted lab that builds a deliberately vulnerable Active Directory environment for practising common attack techniques.

### Gold Bug challenges

<https://bbs.goldbug.cryptovillage.org/puzzles.html>

Cryptography-focused puzzles from the Crypto & Privacy Village. Working out what each puzzle is asking is part of the challenge.

## Repository layout

```
Database/
  Wargames.md            List of wargame platforms
  tutorials.md           Getting-started material
  Info about CTFs.md     Sites, wikis, write-up collections
  Resources.md           Tools by category
  Wargames/
    natas/               OverTheWire Natas write-ups, passwords, scripts
```
