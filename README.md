# THOT

**Introducing THOT by MORFMOD INC.**
Your AI team for building apps, analyzing documents, and automating everyday work.
Connect your AI account, describe your goal, and let multiple agents work together. Track progress and open finished files in Prize drop.

---

### Releases & Downloads

- **Windows x64 Build:** [Assistant-Windows-x64-Signed.zip](https://github.com/evtrapper/THOT/releases/download/v0.19.0-alpha.56/Assistant-Windows-x64-Signed.zip)
- **Root Certificate:** [MORFMOD_Root.cer](https://github.com/evtrapper/THOT/releases/download/v0.19.0-alpha.56/MORFMOD_Root.cer)
- **Checksum Verification:** [SHA256SUMS.txt](https://github.com/evtrapper/THOT/releases/download/v0.19.0-alpha.56/SHA256SUMS.txt)

---

### Installation & Trust
1. Download and extract ``Assistant-Windows-x64-Signed.zip``.
2. Launch ``Assistant.exe``.
3. *(Optional for external test machines)* To trust MORFMOD INC binaries:
   ```powershell
   Import-Certificate -FilePath .\MORFMOD_Root.cer -CertStoreLocation Cert:\LocalMachine\TrustedPublisher
   ```
