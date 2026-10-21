# 🛡️ Bitseeker LLC Software Disclaimer & Limitation of Liability

[![Version](https://img.shields.io/badge/version-1.1.1-blue.svg)](https://github.com/cjtsh/software-disclaimer/releases/tag/v1.1.1)
[![License: MIT](https://img.shields.io/badge/Default_License-MIT-blue.svg)](LICENSE)
[![License: Apache 2.0](https://img.shields.io/badge/Alternative_License-Apache_2.0-green.svg)](licenses/LICENSE-APACHE-2.0)
[![Status: Active Standard](https://img.shields.io/badge/Legal_Notice-Active_Standard-critical.svg)](DISCLAIMER.md)

> **Disclaimer, warranty, risk, and licensing reference for software, scripts, binaries, AI tools, and documentation published by Bitseeker LLC. The repository is maintained through the [`@cjtsh`](https://github.com/cjtsh) GitHub account.**

---

## ⚠️ 1. Universal Disclaimer & Limitation of Liability

This software and all associated repositories, binaries, disk images (`.dmg`), scripts, and documentation (collectively, the **"Software"**) are experimental and provided solely for educational, testing, research, and personal utility purposes.

```text
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

This notice accompanies software published by **Bitseeker LLC**. A posted notice does not by itself establish that every contractual term was accepted; see the [integration guidance](templates/CORPORATE-SHIELD-GUIDE.md).

1. **You Run This Software Entirely at Your Own Risk:** You assume full and sole responsibility for any consequences resulting from the installation, configuration, or execution of the Software on your hardware, operating system, network, or environment.
2. **Limitation of Liability:** To the maximum extent permitted by law, Bitseeker LLC and the other protected parties disclaim liability for the categories of damages described in [`DISCLAIMER.md`](DISCLAIMER.md). No disclaimer eliminates liability that applicable law does not allow a party to exclude.
3. **Data & System Backups:** You are solely responsible for backing up your data, credentials, and configurations, and for verifying that your system is appropriate before running experimental code.
4. **No Support or Maintenance Commitment:** All open-source projects are provided free of charge without any service-level agreement (SLA), warranty, or guarantee of ongoing maintenance, security patching, or future OS/hardware compatibility.
5. **Informational Use Only:** Any telemetry, diagnostics, memory estimates, security checks, or analytical outputs displayed by our tools are strictly informational and do not constitute professional engineering, cybersecurity, financial, or legal advice.
6. **Automated Execution:** AI agents, generated code, and automated commands or API calls may act incorrectly or destructively. Users are responsible for review, sandboxing, and supervision.
7. **Restricted Uses & Compliance:** The Software is not intended for life-safety or other mission-critical uses. It provides no financial, legal, tax, or regulatory advice. Users are responsible for applicable legal compliance.
8. **Additional Terms:** The full disclaimer describes the intended scope of indemnity and Florida law/forum terms. Whether those provisions are enforceable depends on applicable law and, where contract assent is required, how users are shown and accept them.

👉 **Read the full standalone legal notice:** [**`DISCLAIMER.md`**](DISCLAIMER.md)

## Releases

**Current version: [v1.1.1](https://github.com/cjtsh/software-disclaimer/releases/tag/v1.1.1)**, released October 21, 2026. See the [changelog](CHANGELOG.md) for the changes in this version and future releases on the [GitHub Releases page](https://github.com/cjtsh/software-disclaimer/releases).

---

## 📜 2. The Standard MIT License Text

UCC Article 2 concerns sales of goods. Whether its warranty rules apply to software depends on the transaction and governing law; all-caps formatting alone does not make a disclaimer enforceable. Where applicable, Florida Statutes § 672.316 requires conspicuous written language for certain warranty exclusions. See the [full disclaimer](DISCLAIMER.md) and [integration guide](templates/CORPORATE-SHIELD-GUIDE.md).

Unless otherwise noted in a specific repository, our projects are distributed under the canonical **MIT License**:

```text
MIT License

Copyright (c) 2026 Bitseeker LLC

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

* **`"AS IS"` WITHOUT WARRANTY:** States that the software is provided without warranties, subject to limits imposed by applicable law.
* **LIMITATION OF LIABILITY:** States the limits described in the license and disclaimer; it does not guarantee immunity from tort claims or claims that law does not allow a party to waive.

---

## ⚖️ 3. MIT vs. Apache 2.0: License Selection Standard

While the **MIT License** is our standard for clean developer utilities, **Apache License 2.0** provides additional explicit corporate legal language for sensitive tools:

| Feature | MIT License ([`licenses/LICENSE-MIT`](licenses/LICENSE-MIT)) | Apache 2.0 ([`licenses/LICENSE-APACHE-2.0`](licenses/LICENSE-APACHE-2.0)) |
| :--- | :--- | :--- |
| **Length** | ~170 words (short, clean) | ~1,200 words (comprehensive) |
| **Warranty Disclaimer** | Robust `"AS IS"` clause | Robust `"AS IS"` clause (Section 7) |
| **Liability Limitation** | Covers general damages | Explicitly enumerates loss of goodwill, work stoppage, computer failure, or malfunction (Section 8) |
| **Patent Protection** | Silent / implied license | Explicit reciprocal patent grant & retaliation clause (Section 3) |
| **Best For** | Clean developer utilities, fast sharing | Tools handling sensitive operations, keys, network operations, or local hardware/system modifications |

---

## 🧩 4. How to Reference or Incorporate This Disclaimer in Projects

### Option A: Use the README Disclaimer Template

Copy [`templates/README-DISCLAIMER-SNIPPET.md`](templates/README-DISCLAIMER-SNIPPET.md) into your project. Link to the full terms. A public link is useful notice but may not establish acceptance of contractual clauses; products relying on such terms should present them before use and obtain affirmative assent where appropriate.

### Option B: 1-Line Badges for Project Header

```markdown
[![Disclaimer](https://img.shields.io/badge/Legal-Standard_Disclaimer-critical.svg)](https://github.com/cjtsh/software-disclaimer)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/cjtsh/software-disclaimer/blob/main/LICENSE)
```

### Option C: 1-Command Terminal Fetch into Any New Repo

Run this inside any project directory to pull the standard `LICENSE` and `DISCLAIMER.md` directly from this repository:

```bash
curl -sSL https://raw.githubusercontent.com/cjtsh/software-disclaimer/main/LICENSE -o LICENSE && \
curl -sSL https://raw.githubusercontent.com/cjtsh/software-disclaimer/main/DISCLAIMER.md -o DISCLAIMER.md
```

---

## 🖥️ 5. Application-Level Defenses (DMG / GUI / CLI)

For desktop binaries (macOS `.dmg` / `.app`, Linux `AppImage`, Windows executables) and CLI installers:

1. **In-App "About" / First Launch Screen:** Include a scrolling terms view or an explicit **"Accept & Continue"** acknowledgment on first launch displaying [`templates/FIRST-RUN-NOTICE.txt`](templates/FIRST-RUN-NOTICE.txt). Clear notice matters, and contractual terms may require affirmative assent; the software must actually show the terms and make use conditional on acceptance if that is the intended agreement flow.
2. **macOS DMG License Agreement (SLA):** Embed the Software License Agreement into the `.dmg` container (e.g., via `create-dmg --eula templates/FIRST-RUN-NOTICE.txt` or `hdiutil`) and/or bundle `LICENSE` and `DISCLAIMER.md` inside the mounted disk image to improve notice before installation; packaging alone does not guarantee contractual assent.
3. **Corporate Shield:** When distributing under an LLC (such as **Bitseeker LLC**), publish and sign the software and copyright notice under the corporate entity (`Copyright (c) 2026 Bitseeker LLC`) only for rights the LLC owns or has received by assignment. An LLC attribution does not eliminate a person’s liability for their own wrongful acts.

---

## 📂 Repository Contents

| File | Purpose |
| :--- | :--- |
| [`README.md`](README.md) | Overview, universal disclaimer, MIT vs. Apache 2.0 guide, and integration snippets |
| [`DISCLAIMER.md`](DISCLAIMER.md) | Standalone universal Software Disclaimer, Assumption of Risk & Limitation of Liability |
| [`LICENSE`](LICENSE) | Default canonical MIT License (`Bitseeker LLC`) |
| [`licenses/LICENSE-MIT`](licenses/LICENSE-MIT) | Standard MIT License template |
| [`licenses/LICENSE-APACHE-2.0`](licenses/LICENSE-APACHE-2.0) | Standard Apache License 2.0 template |
| [`templates/README-DISCLAIMER-SNIPPET.md`](templates/README-DISCLAIMER-SNIPPET.md) | Drop-in Markdown disclaimer block for project `README.md` files |
| [`templates/FIRST-RUN-NOTICE.txt`](templates/FIRST-RUN-NOTICE.txt) | Plaintext conspicuous notice for GUI First-Run dialogs, CLI banners, and DMG SLAs |
| [`templates/CORPORATE-SHIELD-GUIDE.md`](templates/CORPORATE-SHIELD-GUIDE.md) | Guidance on ownership, notice, assent, disclaimers, and LLC attribution |
