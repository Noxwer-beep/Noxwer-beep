<div align="center">
  <img src="assets/banner.png" alt="Maximilian Jatzkowski — infrastructure, security and the tools that hold them together" width="100%">
</div>

<br>

I'm Max, 25, studying IT in Germany. I run a homelab and I build the tools I keep
needing for it — a scanner, a health checker, a shift toolbox. It's all written by
hand, tested, and documented well enough that someone else could pick it up.

I'm looking for a **security analyst role**.

---

### What I'm working on

| Project | What it is | Stack |
|---|---|---|
| **[Bastet](https://github.com/Noxwer-beep/bastet)** | The night-shift toolbox: IOC triage, log analysis, CVE and ATT&CK lookup, case notes. One prompt instead of nine tabs. | `Python` `SOC` `ATT&CK` |
| **[Vantage](https://github.com/Noxwer-beep/vantage)** | A scanner I point at my own network. Refuses to run without a scope, and keeps confirmed findings apart from guesses. | `Python` `nmap` `SQLite` |
| **[Warden](https://github.com/Noxwer-beep/warden)** | One TOML file says what should be running in the lab; Warden checks it over TCP/UDP/HTTP/TLS, remembers every run, and reports what changed. | `Python` `TOML` `SQLite` |
| **[Homelab](https://github.com/Noxwer-beep/homelab-infrastructure)** | Proxmox, OPNsense, VLANs — and the reasoning behind each decision. | `Docs` |
| **[Portfolio](https://github.com/Noxwer-beep/portfolio)** | The site itself. Hand-written, no build step. [Live](https://noxwer-beep.github.io/portfolio/) | `HTML` `CSS` `JS` |
| **[Showcase](https://github.com/Noxwer-beep/showcase)** | Eight layouts for the same page, to see how much the layout decides. [Live](https://noxwer-beep.github.io/showcase/) | `HTML` `CSS` `JS` |
| **[Blueprint](https://github.com/Noxwer-beep/blueprint)** · **[Aurora](https://github.com/Noxwer-beep/aurora)** · **[Ledger](https://github.com/Noxwer-beep/ledger)** | Three of those layouts, published on their own with the reasoning written down. | `HTML` `CSS` `JS` |

---

### Right now

- Learning the analyst side properly: triage, evidence, and writing it up so someone
  else can follow it.
- Running **Warden** on a schedule against the real lab, with the digest dropped into
  the vault.
- Scanning my own Metasploitable box with **Vantage** and checking the tool against a
  target that is supposed to be broken.

### How I work

- **Read the thing.** The XML, the RFC, the actual header — not the blog post about it.
- **Test against reality.** Real sockets, real logs, real TLS. Mocks agree with you.
- **Write it down.** The runbook is for whoever is on at 3am, usually me.
- **Deny by default.** Firewall rules, scope gates, feature flags.
- **Small tools.** If I can't read it end to end, I can't trust it mid-incident.

### Tools I reach for

`Linux` · `Python` · `Bash` · `nmap` · `Wireshark` · `MITRE ATT&CK` · `Proxmox` ·
`OPNsense` · `SQLite` · `Git` · `Obsidian`

---

<div align="center">
  <sub>
    <a href="https://noxwer-beep.github.io/portfolio/">portfolio</a> ·
    <a href="mailto:jatzkowski.maximilian@gmail.com">email</a>
  </sub>
</div>
