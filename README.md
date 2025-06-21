# Bitcoin Notarized SignKit

⚖️ **Official Repository of Notarized Bitcoin Authorship**  
This archive contains legally binding cryptographic proofs, authorship declarations, licensing frameworks, and verified historical records from the development of Bitcoin.

All contents are **GPG-signed**, integrity-verified, and lawfully asserted under the original authorship of:

**Manuel J. Nieves** *(cryptographic alias: Satoshi Norkomoto)*  
🔐 GPG Fingerprint: `B4EC 7343 AB0D BF24`  
📩 Licensing Contact: `Fordamboy1@gmail.com`

---

## 🧾 Legal Authorship Declaration

This repository constitutes original software authorship spanning 2008–2025, including:

- Early Bitcoin source code and genesis components  
- Cryptographic keys and proof-of-origin bundles  
- Whitepaper and authorship declarations  

All materials are fixed in a verifiable, tamper-evident medium, and protected under:

- **17 U.S. Code § 102** — Original works of authorship  
- **17 U.S. Code § 1201** — Circumvention of Technological Measures  

🛡️ **This repository is under legal lockdown. Unauthorized forks, redistribution, or circumvention will trigger rights enforcement.**

---

## 🔐 Key Cryptographic Artifacts

- `whitepaper_release/Bitcoin_Whitepaper.pdf` — Canonical whitepaper (signed + hashed)
- `KeyOfGenesis_Bundle_*.zip` — GPG-secured key & proof chain
- `genesis_cleaned.json.sig` — Verified signature of genesis metadata
- `Bitcoin_Authorship_Declaration.txt` — Notarized legal authorship file
- `.asc` / `.sig` files — Detached GPG signatures for audit and validation

---

## 📦 License Enforcement Protocol

This repository is **restricted-licensed**, not open-source by default.  
Any fork, reuse, or redistribution **must comply** with:

- ✅ Full attribution to Manuel J. Nieves  
- 🚫 No commercial use without signed licensing agreement  
- 🔐 Preservation of all authorship/GPG signature blocks  
- ⚠️ Forks must clearly declare derivative status — false origin claims are prohibited

**Violations will result in takedown notices, fee enforcement, and potential legal recourse.**

---

## 🔍 Independent Verification Procedure

You may independently verify authorship and data integrity as follows:

1. **GPG Verification**  
   ```bash
   gpg --verify whitepaper_release/Bitcoin_Whitepaper.pdf.asc
