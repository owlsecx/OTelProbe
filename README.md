# 🦉 OTelProbe

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OwlSec-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OTelProbe** — OTelProbe — OwlSec security tool

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OTelProbe is a Telnet security audit suite for credential auditing, banner grabbing, CVE checks and interactive command execution. It uses a raw-socket Telnet implementation with a full IAC/option-negotiation engine (replacing the deprecated telnetlib), supports combo-list and multi-user audit modes, and rate-limits attempts. Found credentials and CVE results can be exported to TXT, JSON or CSV, and remote targets require explicit authorization.

---

## ✨ Features


- Multi-threaded credential auditing with combo-list and multi-user modes
- Raw-socket Telnet with a full IAC / option-negotiation engine (no deprecated telnetlib)
- Banner grabber and service fingerprinting
- CVE vulnerability checks with a scan-all runner
- Interactive terminal with command history and a port-probe utility
- Rate limiting, stop-on-first-hit and TXT/JSON/CSV export; remote targets require authorization confirm

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OTelProbe
./OTelProbe --probe-local
./OTelProbe --version
./OTelProbe --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
