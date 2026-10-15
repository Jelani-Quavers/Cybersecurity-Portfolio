# Offensive Security Intro

**Platform:** TryHackMe
**Difficulty:** Beginner
**Date completed:** 15/10/2026
**Room link:** https://tryhackme.com/room/offensivesecurityintro

## Summary
This room covers the basic fundamentals of offensive security. The goal was to find a weakness in a fake bank application called FakeBank.

## Key Concepts
- **Offensive security:** testing systems by attacking them (legally) to find weaknesses before real attackers do
- **Hidden pages:** a common mistake is leaving pages accessible that aren't linked anywhere, like admin pages

## Tools Used
| Tool | What I used it for |
|------|--------------------|
| Terminal | Running commands |
| DirBuster (run with `dirb`) | Searching a website for hidden pages |

## Walkthrough
### Opening a terminal
Launched the terminal on the room's machine to run my first hacking tool.

### Attacking the FakeBank admin page
Used DirBuster to find a hidden page, which led to the bank's admin page. I ran it by typing `dirb` followed by the URL I wanted to search:

`dirb <target-url>`

## What I Learned
- How to open a terminal
- How to find hidden pages
- What offensive security is
