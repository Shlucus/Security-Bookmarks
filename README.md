<div align="center">

# 🛡️ Security Bookmarks

**A pile of good security links, organized enough that you'll actually use it.**

One HTML file, every Chromium browser, no extension required.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)
[![Format](https://img.shields.io/badge/format-Netscape%20Bookmark%20HTML-orange)](https://learn.microsoft.com/en-us/deployedge/edge-favorites-file-format)
[![Browsers](https://img.shields.io/badge/works%20with-Chrome%20%7C%20Edge%20%7C%20Brave%20%7C%20Arc%20%7C%20Vivaldi-4285F4)](#-import-instructions)
[![Tools](https://img.shields.io/badge/tools%20indexed-51%2B-success)](#-full-index)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#-contributing)

</div>

---

## 📖 What this is

Every security professional has the same problem: a bookmarks bar that's either empty or a graveyard of half-remembered tabs from three years ago. This repo is my attempt to fix that for good. It's the OSINT engines, forensic utilities, CTF labs, and hardware-hacking references I've actually kept coming back to, sorted into folders that make sense instead of one long scroll.

Import it once, and your VM, your new laptop, or the intern's fresh browser profile all get the same toolkit. No more "wait, what was that IP lookup site called again."

<div align="center">

📸 *`assets/screenshot-bookmarks-bar.png`*
<!-- drop a screenshot of the imported folder here -->

</div>

---

## 📑 Table of Contents

- [Import Instructions](#-import-instructions)
- [Library Structure](#-library-structure)
- [Full Index](#-full-index)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [Disclaimer](#disclaimer)
- [License](#-license)

---

## 📥 Import Instructions

<details open>
<summary><b>Google Chrome / Brave / Vivaldi</b></summary>

1. Download [`bookmarks.html`](./bookmarks.html) (or just clone the repo).
2. Go to `chrome://bookmarks`.
3. Click the **⋮** menu in the top right, then **Import bookmarks**.
4. Pick `bookmarks.html`.

</details>

<details>
<summary><b>Microsoft Edge</b></summary>

1. Download [`bookmarks.html`](./bookmarks.html).
2. Go to `edge://favorites`.
3. Click **⋯**, then **Import favorites** → **Favorites or bookmarks HTML file**.
4. Pick `bookmarks.html`.

</details>

<details>
<summary><b>Arc</b></summary>

1. Download [`bookmarks.html`](./bookmarks.html).
2. Arc Menu → **Import Data** → **Bookmarks HTML File**.
3. Pick `bookmarks.html`.

</details>

Everything lands inside one **`Security Toolkit`** folder, so it won't dump 50 new bookmarks all over your existing bar. You can thank me later.

---

## 🗂 Library Structure

```
Security Toolkit/
├── 🔎 OSINT & Recon/
│   ├── Search Engines                    → Shodan, Censys, ZoomEye, urlscan.io
│   ├── People, Identity & Breach Data     → OSINT Industries, FaceCheck, HIBP, DeHashed
│   └── Threat Intel & Reputation          → Cisco Talos, AbuseIPDB, VirusTotal
├── 🌐 Networking & IP Tools                → ifconfig.co, ipinfo.io, WiGLE, DNSdumpster, MXToolbox
├── 🧰 Analysis & Utilities                 → CyberChef, Forensically, explainshell, CrackStation, ffuf, webhook.site
├── 🕸️ Web App Security Testing             → PentesterLab, OWASP Juice Shop, Altoro Mutual, OverTheWire
├── 🏁 CTF & Practice Labs                  → TryHackMe, pwnable.kr, WeChall, CTF101
├── 🔌 Hardware & Physical Security         → Flipper Zero, ALFA adapters, Digispark/BadUSB, uConsole
├── 🤖 AI & Chatbots                        → ChatGPT, Claude, jailbreak megathread
├── 🕵️ Privacy & Anonymity                  → Tor Project, DuckDuckGo, Proton Mail
├── 📚 Learning & Community                 → Null Byte, Hackademy, eJPT, 2600
└── 📄 Reference Manuals                    → Kali command reference, Geoleaks Codebook
```

Eleven folders, three of them nested one level deeper under OSINT because that category was getting unwieldy. That's it. Nothing five levels deep, because nobody's clicking through five levels deep at 2am during an engagement.

---

## 📋 Full Index

<details>
<summary><b>🔎 OSINT & Recon</b></summary>

| Tool | What it's for |
|---|---|
| [Shodan](https://www.shodan.io/) | Search engine for internet-connected devices |
| [Censys Search](https://search.censys.io/) | Internet-wide host and certificate search |
| [ZoomEye](https://www.zoomeye.org/) | Another cyberspace search engine, different dataset |
| [urlscan.io](https://urlscan.io/) | Scans and sandboxes a URL before you touch it yourself |
| [OSINT Industries](https://osint.industries/phone) | Phone and email identity lookups |
| [FaceCheck](https://facecheck.id/) | Reverse image and facial recognition search |
| [Have I Been Pwned](https://haveibeenpwned.com/) | Checks if an email's shown up in a breach |
| [DeHashed](https://dehashed.com/) | Breach data search engine |
| [Cisco Talos Intelligence](https://talosintelligence.com/) | Threat intel from Cisco's research group |
| [AbuseIPDB](https://www.abuseipdb.com/) | Crowdsourced IP abuse reports |
| [VirusTotal](https://www.virustotal.com/) | Multi-engine file and URL scanning |

</details>

<details>
<summary><b>🌐 Networking & IP Tools</b></summary>

| Tool | What it's for |
|---|---|
| [ifconfig.co](https://ifconfig.co/) | Tells you your own IP, no fuss |
| [ipinfo.io](https://ipinfo.io/) | IP data and geolocation, more detail than the above |
| [WiGLE](https://wigle.net/) | Wireless network mapping |
| [DNSdumpster](https://dnsdumpster.com/) | DNS recon, good first step on a new target |
| [MXToolbox](https://mxtoolbox.com/) | Grab bag of network diagnostic tools |

</details>

<details>
<summary><b>🧰 Analysis & Utilities</b></summary>

| Tool | What it's for |
|---|---|
| [CyberChef](https://gchq.github.io/CyberChef/) | GCHQ's "Cyber Swiss Army Knife," data transforms and decoding |
| [Forensically](https://29a.ch/photo-forensics/#pca) | Free photo forensics, error level analysis and the like |
| [explainshell.com](https://explainshell.com/) | Paste a shell command, get every flag explained |
| [CrackStation](https://crackstation.net/) | Online hash lookup against huge precomputed tables |
| [ffuf](https://github.com/ffuf/ffuf) | Fast web fuzzer written in Go, does most of the heavy lifting in a directory brute force |
| [webhook.site](https://webhook.site/) | Spin up a URL, watch what hits it, useful for SSRF and blind callbacks |
| [theHarvester](https://hackviser.com/tactics/tools/the-harvester) | Email, subdomain, and name recon in one pass |

</details>

<details>
<summary><b>🕸️ Web App Security Testing</b></summary>

| Tool | What it's for |
|---|---|
| [PentesterLab](https://pentesterlab.com/) | Paid and free web hacking exercises, code review included |
| [OWASP Juice Shop](https://juice-shop.herokuapp.com/#/) | The intentionally broken app everyone learns on eventually |
| [Altoro Mutual](https://demo.testfire.net/index.jsp) | IBM's ancient but still-useful SQLi demo bank |
| [OverTheWire SQLi Lab](https://redtiger.labs.overthewire.org/) | SQL injection practice, no setup |

</details>

<details>
<summary><b>🏁 CTF & Practice Labs</b></summary>

| Tool | What it's for |
|---|---|
| [TryHackMe](https://tryhackme.com/access) | Guided labs, good on-ramp if you're newer to this |
| [pwnable.kr](https://pwnable.kr/) | Binary exploitation wargame, old-school and still sharp |
| [WeChall](https://www.wechall.net/active_sites) | A list of active challenge sites so you don't have to hunt for them |
| [CTF101](https://ctf101.org/) | Fundamentals, start here if CTFs are new to you |
| [Capture-The-Flag 101](https://www.youtube.com/watch?v=QHPFbrJ_olg&t=428s) | A video walkthrough of the same idea |

</details>

<details>
<summary><b>🔌 Hardware & Physical Security</b></summary>

| Tool | What it's for |
|---|---|
| [FlipC.org](https://flipc.org/) | Flipper Zero community hub |
| [ALFA AWUS036ACS Driver](https://store.rokland.com/pages/alfa-awus036acs-kalipi-driver-install-instructions) | Driver install guide for the adapter everyone in Wi-Fi auditing owns |
| [HackerGadgets uConsole](https://forum.clockworkpi.com/t/hackergadgets-aio-board-package/17875) | AIO board package for the uConsole |
| [uConsole Assembly Guide (PDF)](https://github.com/clockworkpi/uConsole/blob/master/Clockwork_uConsole_Assembly_Guidelines.pdf) | The build instructions, actually helpful |
| [Flipper Zero "Rolling Flaws"](https://www.youtube.com/watch?v=gMnGuDC9EQo&ab_channel=DerekJamison) | RF replay attack demo |
| [BadUSB / Digispark Wi-Fi Password Theft](https://www.youtube.com/watch?v=6Ciq5zmq150) | ATtiny85 payload walkthrough |
| [$3 Digispark BadUSB Script](https://www.youtube.com/watch?v=X6R8cveFz74&t=441s) | Proof that BadUSB doesn't need a big budget |

</details>

<details>
<summary><b>🤖 AI & Chatbots</b></summary>

| Tool | What it's for |
|---|---|
| [ChatGPT](https://chat.openai.com/) | OpenAI's assistant |
| [Claude](https://claude.ai/) | Anthropic's assistant, the one writing this README |
| [r/GPT_jailbreaks megathread](https://www.reddit.com/r/GPT_jailbreaks/comments/1164aah/chatgpt_developer_mode_100_fully_featured_filter/) | Prompt injection research, kept as a reference, not an endorsement |

</details>

<details>
<summary><b>🕵️ Privacy & Anonymity</b></summary>

| Tool | What it's for |
|---|---|
| [Tor Project](https://www.torproject.org/) | Anonymity network and browser |
| [DuckDuckGo](https://duckduckgo.com/) | Search that isn't building a profile on you |
| [Proton Mail](https://proton.me/mail) | Encrypted email |

</details>

<details>
<summary><b>📚 Learning & Community</b></summary>

| Tool | What it's for |
|---|---|
| [Null Byte](https://www.youtube.com/@NullByteWHT/videos) | Long-running hacking tutorial channel |
| [Hackademy](https://lolkatz.github.io/will-hack-for-coffee/2022/05/28/northsec-hackademy.html) | Write-up from NorthSec's Hackademy |
| [eJPT Certification](https://security.ine.com/certifications/ejpt-certification/) | INE's junior pentester cert |
| [2600 Magazine Store](https://store.2600.com/) | The Hacker Quarterly, still going after all these years |

</details>

<details>
<summary><b>📄 Reference Manuals</b></summary>

| Tool | What it's for |
|---|---|
| [All Kali Linux Commands (PDF)](https://github.com/tanc7/hacking-books/blob/master/All%20Kali%20Linux%20Commands.pdf) | Command reference, good for when you blank on syntax |
| [Geoleaks Codebook (PDF)](https://sukado.dk/onewebmedia/Geoleaks%20Codebook%20-%20KD-30-01-2020.pdf) | Geolocation OSINT codebook |

</details>

---

## 🖼 Screenshots

<div align="center">

| Bookmarks Bar | Folder Expanded | Import Dialog |
|:---:|:---:|:---:|
| 📸 `assets/screenshot-bar.png` | 📸 `assets/screenshot-folder.png` | 📸 `assets/screenshot-import.png` |

</div>

Screenshots are still pending, I keep meaning to record these. Drop images into `assets/` and swap the placeholders above whenever someone gets around to it.

---

## 🤝 Contributing

Found a tool that deserves a spot? PRs are welcome. To add one:

1. Fork the repo and edit [`bookmarks.html`](./bookmarks.html) directly, keeping it in the existing folder structure.
2. Update the tables in this README to match.
3. Open a PR and say in one line why it belongs here.

I'm picky about two things: it has to be free (or at least free-tier) and usable straight from a browser, and it has to earn its place across offensive, defensive, or research work. If it's a single-purpose tool behind a paywall, it's probably not going in.

---

## Disclaimer

These links exist for education and authorized security research. Full stop. A good chunk of this list is dual-use by nature (vulnerable demo apps, hash crackers, BadUSB payloads, OSINT lookups), so point them at systems and data you own or are cleared to test, and nowhere else. What you do with them, and whether it's legal where you're doing it, is on you.

---

## 📄 License

MIT. See [LICENSE](./LICENSE).
