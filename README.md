<div align="center">

# 🛡️ Security Bookmarks

**A pile of good security links, organized enough that you'll actually use it.**

One HTML file, every Chromium browser, no extension required.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)
[![Format](https://img.shields.io/badge/format-Netscape%20Bookmark%20HTML-orange)](https://learn.microsoft.com/en-us/deployedge/edge-favorites-file-format)
[![Browsers](https://img.shields.io/badge/works%20with-Chrome%20%7C%20Edge%20%7C%20Brave%20%7C%20Opera%20%7C%20Arc%20%7C%20Vivaldi-4285F4)](#-import-instructions)
[![Tools](https://img.shields.io/badge/tools%20indexed-90%2B-success)](#-full-index)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#-contributing)


<img width="2495" height="1372" alt="Security-Bookmarks(cleaned + titled3)" src="https://github.com/user-attachments/assets/282cb568-3c64-4267-80c8-8eb3da523f51" />


</div>

---

## 📖 What this is

`Security-Bookmarks` packages years of accumulated tooling: OSINT search engines, forensic utilities, CTF labs, hardware-hacking references, and more into a single, cleanly organized bookmark file. 

Import it once and every teammate, VM, or fresh browser profile gets the same curated toolkit, nested in logical folders instead of a flat, unsearchable list.


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

Everything lands inside one **`Security Toolkit`** folder, so it won't dump 90 new bookmarks all over your existing bar. You can thank me later.

---

## 🗂 Library Structure

```
Security Toolkit/
├── 🔎 OSINT & Recon/
│   ├── 🔭 Search Engines                  → urlscan.io, Wayback Machine, Shodan, Censys, ZoomEye
│   ├── 🪪 People, Identity & Breach Data  → OSINT Industries, FaceCheck, HIBP, DeHashed, Breachsense, LeakIX
│   └── 🚨 Threat Intel & Reputation       → AbuseIPDB, Cisco Talos, VirusTotal
├── 🌐 Networking & IP Tools                → ifconfig.co, ipinfo.io, Speedtest, WiGLE, DNSdumpster, MXToolbox
├── 🧰 Analysis & Utilities/
│   ├── Forensics                          → CyberChef, Forensically, unfurl, CrackStation, Pic2Map
│   ├── Reporting                          → CVSS Calculator, Hemingway Editor
│   └── (loose)                            → revshells.com, webhook.site, Bitwarden, explainshell.com, SSL Labs
├── 🔌 Hardware & Physical Security/
│   ├── 💲 Gadget Retailers                → PwnShop, Hak5, OpenSourceSDRLab, Flipper Zero, JustCallMeKoko, Rabbit-Labs, Lab401, HackerGadgets
│   ├── 📦 Resources                       → ALFA driver, Flipper Zero demo, BadUSB/Digispark videos
│   └── (loose)                            → FZEE Flasher
├── 🤖 AI & Chatbots/
│   ├── Visuals                            → Higgsfield AI, Nano-Banana (Gemini), ChatGPT Images 2.0
│   └── (loose)                            → Grok, Perplexity, ChatGPT, Claude, Gemini, Copilot, Meta AI, DeepSeek, Cytd
├── 🕵️ Privacy & Anonymity/
│   ├── Browsers                           → Tor Project, DuckDuckGo, Brave
│   └── (loose)                            → Windscribe, Bitwarden, Proton Mail, Tails, Cryptgeon
├── 📚 Learning & Community/
│   ├── 🎓 Creators & Educators/
│   │   └── ▶️ YouTube                     → Null Byte, NetworkChuck, Darknet Diaries
│   ├── 🏁 CTF & Practice Labs/
│   │   ├── 🧪 Labs                        → TryHackMe, Web Security Academy, CyLab/picoCTF, WeChall, Hack The Box, OverTheWire, UnderTheWire, PentesterLab, Merlin
│   │   ├── 🎯 Vulnerable Sites            → OWASP Juice Shop, pwnable.kr, Altoro Mutual
│   │   ├── Online CTFs                    → Google CTF
│   │   └── (loose)                        → CTF101, Capture-The-Flag 101 video
│   └── (loose)                            → DEF CON, 2600
└── 📄 Reference Manuals                    → Google Dorks List, Geoleaks Codebook, Hacking Books (tanc7), Kali command reference, XSS Cheat Sheet
```

Eight top-level folders now. `CTF & Practice Labs` moved under `Learning & Community` at some point (worth a double check that this was on purpose and not a drag-and-drop accident in Brave's bookmark manager), which makes it the deepest branch: four folders down before you hit an actual link. Everything else stays within two or three.

---

## 📋 Full Index

<details>
<summary><b>🔎 OSINT & Recon</b></summary>

*Search Engines*

| Tool | What it's for |
|---|---|
| [urlscan.io](https://urlscan.io/) | Scans and sandboxes a URL before you touch it yourself |
| [Wayback Machine](https://web.archive.org/) | Pulls up old versions of a page, dead links and all |
| [Shodan](https://www.shodan.io/) | Search engine for internet-connected devices |
| [Censys Search](https://search.censys.io/) | Internet-wide host and certificate search |
| [ZoomEye](https://www.zoomeye.org/) | Another cyberspace search engine, different dataset |

*People, Identity & Breach Data*

| Tool | What it's for |
|---|---|
| [OSINT Industries](https://app.osint.industries/) | Phone and email identity lookups |
| [FaceCheck](https://facecheck.id/) | Reverse image and facial recognition search |
| [Have I Been Pwned](https://haveibeenpwned.com/) | Checks if an email's shown up in a breach |
| [DeHashed](https://dehashed.com/) | Breach data search engine |
| [Breachsense](https://www.breachsense.com/) | Monitors for your data turning up in a breach or on the dark web |
| [LeakIX](https://leakix.net/) | Search engine for exposed services and leaked data |

*Threat Intel & Reputation*

| Tool | What it's for |
|---|---|
| [AbuseIPDB](https://www.abuseipdb.com/) | Crowdsourced IP abuse reports |
| [Cisco Talos Intelligence](https://talosintelligence.com/) | Threat intel from Cisco's research group |
| [VirusTotal](https://www.virustotal.com/) | Multi-engine file and URL scanning |

</details>

<details>
<summary><b>🌐 Networking & IP Tools</b></summary>

| Tool | What it's for |
|---|---|
| [ifconfig.co](https://ifconfig.co/) | Tells you your own External IP |
| [ipinfo.io](https://ipinfo.io/) | IP data and geolocation, more detail than the above |
| [Speedtest](https://www.speedtest.net/) | The classic, how fast is this connection really |
| [WiGLE](https://wigle.net/) | Wireless network mapping |
| [DNSdumpster](https://dnsdumpster.com/) | DNS recon, good first step on a new target |
| [MXToolbox](https://mxtoolbox.com/) | Grab bag of network diagnostic tools |

</details>

<details>
<summary><b>🧰 Analysis & Utilities</b></summary>

*Forensics*

| Tool | What it's for |
|---|---|
| [CyberChef](https://gchq.github.io/CyberChef/) | GCHQ's "Cyber Swiss Army Knife," data transforms and decoding |
| [Forensically](https://29a.ch/photo-forensics/#pca) | Free photo forensics, error level analysis and the like |
| [unfurl](https://dfir.blog/unfurl/) | Pulls apart URLs, timestamps, and tokens for DFIR work |
| [CrackStation](https://crackstation.net/) | Online hash lookup against huge precomputed tables |
| [Pic2Map](https://www.pic2map.com/) | Pulls the GPS data out of a photo and drops a pin on the map |

*Reporting*

| Tool | What it's for |
|---|---|
| [CVSS Calculator](https://www.first.org/cvss/calculator/3.1) | FIRST's official CVSS 3.1 severity scoring calculator |
| [Hemingway Editor](https://hemingwayapp.com/) | Flags dense, hard-to-read sentences, handy for report writing |

*Loose*

| Tool | What it's for |
|---|---|
| [revshells.com](https://www.revshells.com/) | Generates reverse shell one-liners for whatever's on the box |
| [webhook.site](https://webhook.site/) | Spin up a URL, watch what hits it, useful for SSRF and blind callbacks |
| [Bitwarden Password Strength Tester](https://bitwarden.com/password-strength/) | Checks how long a password would survive |
| [explainshell.com](https://explainshell.com/) | Paste a shell command, get every flag explained |
| [SSL Labs](https://www.ssllabs.com/ssltest/) | Qualys' SSL/TLS configuration grader |

</details>

<details>
<summary><b>🔌 Hardware & Physical Security</b></summary>

*Gadget Retailers*

| Tool | What it's for |
|---|---|
| [PwnShop](https://www.pwnshop.ca/) | Security tools for students, by students |
| [Hak5](https://shop.hak5.org/) | Pentest hardware and media, the OG |
| [OpenSourceSDRLab](https://www.aliexpress.com/store/4586015) | HackRF One and uConsole resale on AliExpress |
| [Flipper Zero](https://flipper.net/) | The official site and store |
| [JustCallMeKoko LLC](https://justcallmekokollc.com/) | ESP32 Marauder, wardriving gear, Flipper adapters |
| [Rabbit-Labs](https://rabbit-labs.com/) | RF, Wi-Fi, and accessories |
| [Lab401](https://lab401.com/) | Trusted RFID and pentesting gear, Flipper Zero to Proxmark |
| [HackerGadgets](https://hackergadgets.com/) | uConsole and Pi accessories |

*Resources*

| Tool | What it's for |
|---|---|
| [ALFA AWUS036ACS Driver](https://store.rokland.com/pages/alfa-awus036acs-kalipi-driver-install-instructions) | Driver install guide for the adapter everyone in Wi-Fi auditing owns |
| [Flipper Zero "Rolling Flaws"](https://www.youtube.com/watch?v=gMnGuDC9EQo&ab_channel=DerekJamison) | RF replay attack demo |
| [BadUSB / Digispark Wi-Fi Password Theft](https://www.youtube.com/watch?v=6Ciq5zmq150) | ATtiny85 payload walkthrough |
| [$3 Digispark BadUSB Script](https://www.youtube.com/watch?v=X6R8cveFz74&t=441s) | Proof that BadUSB doesn't need a big budget |

*Loose*

| Tool | What it's for |
|---|---|
| [FZEE Flasher](https://fzeeflasher.com/) | Flashes ESP32 firmware straight from the browser |

</details>

<details>
<summary><b>🤖 AI & Chatbots</b></summary>

*Visuals*

| Tool | What it's for |
|---|---|
| [Higgsfield AI](https://higgsfield.ai/) | AI video and creative generation suite |
| [Nano-Banana (Gemini)](https://gemini.google.com/app) | Google's image generation model, inside Gemini |
| [ChatGPT Images 2.0](https://chatgpt.com/images/) | OpenAI's image generator |

*Loose*

| Tool | What it's for |
|---|---|
| [Grok](https://grok.com/) | xAI's assistant |
| [Perplexity](https://www.perplexity.ai/) | AI search that cites its sources |
| [ChatGPT](https://chat.openai.com/) | OpenAI's assistant |
| [Claude](https://claude.ai/) | Anthropic's assistant, the one that keeps getting asked to edit this README |
| [Google Gemini](https://gemini.google.com/app) | Google's assistant |
| [Microsoft Copilot](https://copilot.microsoft.com/) | Microsoft's assistant |
| [Meta AI](https://www.meta.ai/) | Meta's assistant |
| [DeepSeek](https://chat.deepseek.com/sign_in) | DeepSeek's assistant |
| [Cytd](https://www.cytd.ai/) | Tracks how visible a brand is across AI answers |

</details>

<details>
<summary><b>🕵️ Privacy & Anonymity</b></summary>

*Browsers*

| Tool | What it's for |
|---|---|
| [Tor Project](https://www.torproject.org/) | Anonymity network and browser |
| [DuckDuckGo](https://duckduckgo.com/) | Search that isn't building a profile on you |
| [Brave](https://brave.com/) | Privacy-focused browser |

*Loose*

| Tool | What it's for |
|---|---|
| [Windscribe](https://windscribe.com/) | Free-tier VPN |
| [Bitwarden](https://bitwarden.com/download/) | Free password manager |
| [Proton Mail](https://proton.me/mail) | Encrypted email |
| [Tails](https://tails.net/) | Amnesic live OS, boots from USB and forgets everything after |
| [Cryptgeon](https://cryptgeon.com/) | Self-destructing notes for sharing a secret exactly once |

</details>

<details>
<summary><b>📚 Learning & Community</b></summary>

*Creators & Educators → YouTube*

| Tool | What it's for |
|---|---|
| [Null Byte](https://www.youtube.com/@NullByteWHT/videos) | Long-running hacking tutorial channel |
| [NetworkChuck](https://www.youtube.com/@NetworkChuck) | Networking and cybersecurity tutorials |
| [Darknet Diaries](https://www.youtube.com/@JackRhysider) | True cybercrime stories, hosted by Jack Rhysider |

*CTF & Practice Labs → Labs*

| Tool | What it's for |
|---|---|
| [TryHackMe](https://tryhackme.com/) | Guided labs, good on-ramp if you're newer to this |
| [Web Security Academy](https://portswigger.net/web-security) | Free, deep web security training from the Burp Suite folks |
| [CyLab Security Academy (picoCTF)](https://cylabacademy.org/) | Quick browser-based labs, no VM required |
| [WeChall](https://www.wechall.net/active_sites) | A list of active challenge sites so you don't have to hunt for them |
| [Hack The Box](https://www.hackthebox.com/) | The other big one, less hand-holding |
| [OverTheWire](https://overthewire.org/wargames/) | Wargames, old-school and still sharp |
| [UnderTheWire](https://underthewire.tech/) | Same idea, but PowerShell instead of bash |
| [PentesterLab](https://pentesterlab.com/) | Paid and free web hacking exercises, code review included |
| [Merlin](https://hackmerlin.io/) | A game where you prompt-inject a password out of an LLM |

*CTF & Practice Labs → Vulnerable Sites*

| Tool | What it's for |
|---|---|
| [OWASP Juice Shop](https://juice-shop.herokuapp.com/#/) | The intentionally broken app everyone learns on eventually |
| [pwnable.kr](https://pwnable.kr/) | Binary exploitation wargame |
| [Altoro Mutual](https://demo.testfire.net/index.jsp) | IBM's ancient but still-useful SQLi demo bank |

*CTF & Practice Labs → Online CTFs*

| Tool | What it's for |
|---|---|
| [Google CTF](https://www.capturetheflag.withgoogle.com/) | Google's annual capture-the-flag competition |

*CTF & Practice Labs → Loose*

| Tool | What it's for |
|---|---|
| [CTF101](https://ctf101.org/) | Fundamentals, start here if CTFs are new to you |
| [Capture-The-Flag 101](https://www.youtube.com/watch?v=QHPFbrJ_olg&t=428s) | A video walkthrough of the whole idea |

*Loose*

| Tool | What it's for |
|---|---|
| [DEF CON](https://defcon.org/) | The conference's home page |
| [2600 Magazine Store](https://store.2600.com/) | The Hacker Quarterly, still going after all these years |

</details>

<details>
<summary><b>📄 Reference Manuals</b></summary>

| Tool | What it's for |
|---|---|
| [Google Dorks List](https://www.boxpiper.com/posts/google-dork-list/) | Curated dork reference for search-engine recon |
| [Geoleaks Codebook (PDF)](https://sukado.dk/onewebmedia/Geoleaks%20Codebook%20-%20KD-30-01-2020.pdf) | Geolocation OSINT codebook |
| [Hacking Books (tanc7)](https://github.com/tanc7/hacking-books) | A small repo of hacking book PDFs, not just the Kali command list below |
| [All Kali Linux Commands (PDF)](https://github.com/tanc7/hacking-books/blob/master/All%20Kali%20Linux%20Commands.pdf) | Command reference, good for when you blank on syntax |
| [XSS Cheat Sheet](https://portswigger.net/web-security/cross-site-scripting/cheat-sheet) | The reference for every XSS vector worth trying |

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

I'm picky about three things: 
1. **It has to be mostly free** (or at least free-tier). Some exceptions can be made if it utilizes an externally payed service (e.g. API Tokens, Third-Party tool for a popular payed services, etc.)

2. **Usable straight from a browser**. Some exceptions are: Downloadable documents/ressources (e.g. Cheatsheets), and some Installers to REALLY useful tools.

3. **MUST BE LEGAL** (most importantly). Any illegal, inappropriate, or malicious entries will be denied and reported.

---

## Disclaimer

These links exist for education and authorized security research. Full stop. A good chunk of this list is dual-use by nature (vulnerable demo apps, hash crackers, BadUSB payloads, OSINT lookups), so point them at systems and data you own or are cleared to test, and nowhere else. What you do with them, and whether it's legal where you're doing it, is on you.

---

## 📄 License

MIT. See [LICENSE](./LICENSE).
