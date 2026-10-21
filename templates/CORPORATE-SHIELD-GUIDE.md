# Software Licensing, Disclaimers & Application-Level Defenses

This guide documents the legal and technical standards used across [`cjtsh`](https://github.com/cjtsh) repositories and desktop distributions.

---

## 1. Statutory Basis (US Uniform Commercial Code)

In US law, statutory protections under the **Uniform Commercial Code (UCC § 2-316 & § 2-719)** allow software licensors to disclaim implied warranties (*merchantability*, *fitness for a particular purpose*) and exclude incidental or consequential damages, **provided the language is conspicuous** (which is why open-source disclaimers are written in **ALL CAPS**).

The capitalized section of our licenses and disclaimers provides two primary legal shields:
* **"AS IS" WITHOUT WARRANTY**: Completely negates any implied claim that the software is bug-free, safe, or fit to run on a user's hardware.
* **LIMITATION OF LIABILITY**: Explicitly waives claims for tort, negligence, or breach of contract arising from data loss, bricked machines, or financial loss.

---

## 2. MIT vs. Apache 2.0: Choosing the Right License

While the **MIT License** is our default standard for maximum permissiveness and clean sharing, **Apache License 2.0** provides more explicit corporate legal language for sensitive tools:

| Feature | MIT License ([`LICENSE-MIT`](../licenses/LICENSE-MIT)) | Apache 2.0 ([`LICENSE-APACHE-2.0`](../licenses/LICENSE-APACHE-2.0)) |
| :--- | :--- | :--- |
| **Length** | ~170 words (short, clean) | ~1,200 words (comprehensive) |
| **Warranty Disclaimer** | Robust `"AS IS"` clause | Robust `"AS IS"` clause (Section 7) |
| **Liability Limitation** | Covers general damages | Explicitly enumerates loss of goodwill, work stoppage, computer failure, or malfunction (Section 8) |
| **Patent Protection** | Silent / implied license | Explicit reciprocal patent grant & retaliation clause (Section 3) |
| **Best For** | Clean developer utilities, scripts, fast sharing | Tools handling sensitive operations, cryptographic keys, network operations, or complex system/hardware modifications |

---

## 3. Multi-Layer Notice Strategy

To ensure no user can claim *"they never opened the LICENSE file,"* include conspicuous notices at three levels:

1. **Repository Root (`LICENSE` & `DISCLAIMER.md`)**: Include the canonical license and link to [`cjtsh/software-disclaimer`](https://github.com/cjtsh/software-disclaimer).
2. **Top/Header of `README.md`**: Embed [`templates/README-DISCLAIMER-SNIPPET.md`](README-DISCLAIMER-SNIPPET.md) near the top of the README before installation instructions.
3. **Application-Level Defenses (DMG / GUI / CLI)**:
   * **In-App "About" / First Launch Screen**: Include a scrolling terms box or an explicit **"Accept & Continue"** acknowledgment on the first run displaying the warranty disclaimer ([`templates/FIRST-RUN-NOTICE.txt`](FIRST-RUN-NOTICE.txt)). Courts evaluate whether the user had reasonable notice of the disclaimer before running the code.
   * **macOS DMG License Agreement (SLA)**: When packaging macOS `.dmg` files, embed a Software License Agreement directly into the DMG container (or include `LICENSE` and `TERMS.md` inside the mounted volume) using `create-dmg --eula` or `hdiutil` so the user is presented with the license agreement before mounting/installing.

---

## 4. Corporate Shield Attribution

When publishing commercial-grade utilities or signed binaries under an LLC (such as **Bitseeker LLC**), publish and sign the software and copyright notice under the corporate entity name (or dual attribution):

```text
Copyright (c) 2026 Bitseeker LLC
```
or
```text
Copyright (c) 2026 Chris J Terry (cjtsh) / Bitseeker LLC
```

This ensures that legal notice and any potential dispute are directed at the corporate entity rather than personal assets.
