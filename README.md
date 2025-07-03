# 🚀 Auto‑Recon‑Bash (Tesla Edition)

> “Automate the boring stuff so you can focus on the fun part: pwnage!” 🔍🤖

A sleek, ⚡ lightning‑fast Bash recon utility for `tesla.com`.  
Combine the power of Subfinder, Amass, httprobe & Nmap into one neat, automated workflow—outputting every juicy bit of intel into a dedicated `tesla/` folder.

---

## 🎯 What You’ll Master

1. **OSINT‑style Subdomain Harvesting**  
   - Passive & active enumeration with Subfinder & Amass  
2. **Live Host Hunting**  
   - Filter your haul with httprobe to only target live HTTP/HTTPS endpoints  
3. **Deep‑Dive Service Scans**  
   - Fingerprint banners and versions across all open ports using Nmap  
4. **Data‑Driven Triage**  
   - All your recon data auto‑sorted for rapid analysis and reporting  

---

## 🛠️ Prerequisites & Install Cheat‑Sheet

### You’ll need:
- **Bash** (Linux / macOS / WSL)  
- Subfinder `v2+`  
- Amass  
- httprobe  
- Nmap  

### One‑liner Installer (Go & Homebrew friendly):
```bash
# Go‑based tools:
GO111MODULE=on go install github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest
GO111MODULE=on go install github.com/tomnomnom/httprobe@latest

# Homebrew for the rest:
brew install amass nmap
