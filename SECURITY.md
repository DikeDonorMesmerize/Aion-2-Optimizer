# Security Policy

## Supported Versions

Only the latest release of **Aion 2 Optimizer** receives security updates. Older versions are not maintained.

| Version | Supported          |
|---------|--------------------|
| 1.0.x   | ✅ Yes             |
| < 1.0   | ❌ No              |

---

## Reporting a Vulnerability

If you discover a security issue in **Aion 2 Optimizer**, please **do not open a public issue**. Instead, report it privately so we can address it before disclosure.

### How to report

- **Email:** `portkreheed40@protonmail.com` (replace with your actual contact email if different)
- **GitHub Security Advisories:** Use the [private vulnerability reporting](https://github.com/Portkreheed40/Aion2Optimizer/security/advisories/new) feature (preferred).

Please include:

| Information | Description |
|-------------|-------------|
| **Description** | A clear summary of the vulnerability. |
| **Steps to reproduce** | Exact steps or a proof‑of‑concept. |
| **Impact** | What an attacker could achieve. |
| **Affected version(s)** | Which release(s) are vulnerable. |
| **Environment** | OS version, .NET/runtime version (if applicable). |

### What to expect

- **Acknowledgement** within 48 hours.
- **Status update** within 7 days.
- **Fix & disclosure** – we aim to release a patch within 30 days. You will be credited in the release notes unless you prefer to remain anonymous.

We follow **coordinated disclosure**. Please give us reasonable time to fix the issue before publishing details.

---

## Security Best Practices for Users

Aion 2 Optimizer modifies Windows settings to improve game performance. To use it safely:

| Recommendation | Why |
|----------------|-----|
| **Download only from the official Releases page** | Third‑party mirrors may contain malware. |
| **Verify the archive password** – `8025381933` | The password protects against automatic scanning and tampering. |
| **Run as Administrator** | Required for system tweaks, but only after you trust the source. |
| **Create a restore point** | The tool does this automatically, but a manual backup is extra safety. |
| **Check the SHA‑256 hash** | Compare the hash published in the release notes with the file you downloaded. |
| **Do not disable your antivirus** | False positives can occur; add an exclusion only if you fully trust the build. |

---

## What the Tool Does **Not** Do

- ❌ No telemetry, analytics, or data collection.
- ❌ No background services or scheduled tasks.
- ❌ No network connections except optional update checks (can be disabled).
- ❌ No permanent system modifications without a restore point.

---

## Scope

This security policy covers the **Aion2Optimizer.exe** binary and the scripts included in the release archive. It does **not** cover:

- Third‑party tools or mods.
- The Aion 2 game client itself.
- GitHub’s platform security (report those to GitHub directly).

---

## Acknowledgements

We thank the security researchers who help keep Aion 2 Optimizer safe. Responsible disclosures will be listed here (with permission).

---

*Last updated: 2026‑10‑22*
