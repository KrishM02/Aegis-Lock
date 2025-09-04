# 🔐 Aegis-Lock

**Aegis-Lock** is a **local-only password manager** built as a browser extension.  
It uses **Go (compiled to WebAssembly)** for cryptographic operations, **React** for the UI, and **WebExtension APIs** for secure storage.  

All credentials are encrypted and stored **locally** — no external servers are involved.  

---

## 🚀 Features
- Local-only credential storage  
- AES-GCM encryption (Go → WASM)  
- Master password vault unlock  
- React + Tailwind popup UI  
- Auto-lock on inactivity  
- Clipboard auto-clear after copy  

Planned:
- Autofill login forms  
- Strong password generator  
- Vault import/export  
- Security audit for weak/reused passwords  

---

## 🛠 Tech Stack
- **Go (WASM)** → cryptographic engine (AES-GCM, PBKDF2/Argon2, SHA-256)  
- **React + TypeScript** → extension popup & options UI  
- **TailwindCSS** → lightweight styling  
- **WebExtension APIs** → encrypted storage in `chrome.storage.local`  
- **Manifest V3** → extension packaging  

---

