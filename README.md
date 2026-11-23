# 🗳️ Pathakunkam Voter Finder (పాతకుంకం గ్రామ పంచాయతీ ఓటర్ల శోధన)

Interactive digital electoral roll and voter slip finder for **Pathakunkam Gram Panchayat**, Laveru Mandal, Srikakulam District, Andhra Pradesh.

* **Elections**: SEC Andhra Pradesh · Gram Panchayat Casual Elections 2026
* **Constituency**: 7-Etcherla Assembly Constituency · Polling Station 67
* **Total Voters**: 1,274 (635 Male, 639 Female)
* **Wards**: Wards 1 through 8 (House numbers 1-1 to 2-144)

---

## 🔒 Security PIN Access

This voter directory is secured with a **4-digit access PIN**. On every page load or refresh, visitors are prompted to enter the 4-digit PIN before the voter slips can be viewed.

* **Default 4-digit PIN**: `2026`

### How to Change the PIN
1. **Directly on the website (instant)**:
   * Click **⚙️ Change PIN** on the lock screen or in the top header.
   * Enter the current PIN (`2026`), then choose and confirm your new 4-digit PIN.
   * The new PIN will immediately apply to your browser session.

2. **Globally for all visitors (permanent on GitHub Pages)**:
   * Open `index.html`.
   * Find the line near the top of the `<script>` tag:
     ```javascript
     const DEFAULT_PIN = "2026";
     ```
   * Change `"2026"` to your desired 4-digit PIN (e.g., `"1234"`).
   * Commit and push to GitHub. All visitors will immediately require the updated PIN.

---

## 🌐 Live Free Hosting on GitHub Pages

This repository is hosted using GitHub Pages:

👉 **[https://vshaldb.github.io/Pathakunkam-Vote-Finder/](https://vshaldb.github.io/Pathakunkam-Vote-Finder/)**

### Enabling GitHub Pages (if not already enabled)
1. Go to your repository on GitHub: `https://github.com/vshaldb/Pathakunkam-Vote-Finder`
2. Click **Settings** (top tab) ➔ **Pages** (left sidebar).
3. Under **Build and deployment**:
   * **Source**: `Deploy from a branch`
   * **Branch**: Select `main` and folder `/ (root)`
   * Click **Save**.
4. Within 1–2 minutes, your website will be live at the URL above!

---

## ✨ Features
* **Phonetic & Telugu Search**: Search by name or relative in English or Telugu (e.g. *Budumuru*, *బుడుమూరు*, *Pandranki*, *పాండ్రంకి*).
* **House Number Grouping**: Click on any house door number to instantly view all family members residing at that address.
* **Ward Quick Filter**: One-click summary chips for Wards 1 to 8 with live voter counts.
* **Filters & Sort**: Filter by gender, age group (18-25, 26-40, 41-60, 61+), and sort by serial, name, house no., or age.
* **Copy Voter ID**: One-click copy for EPIC numbers with visual feedback.
* **Responsive Dark/Light Theme**: Auto-detects device mode and supports on-screen touch numeric keypad on mobile.
