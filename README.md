# 🗳️ Pathakunkam Voter Finder (పాతకుంకం గ్రామ పంచాయతీ ఓటర్ల శోధన)

Interactive digital electoral roll and voter slip search portal for **Pathakunkam Gram Panchayat**, Laveru Mandal, Srikakulam District, Andhra Pradesh.

* **Developer**: **Vishal Dangudubiyyapu (విశాల్ దంగుడుబియ్యపు)**
* **Elections**: SEC Andhra Pradesh · Gram Panchayat Casual Elections 2026
* **Constituency**: 7-Etcherla Assembly Constituency · Polling Station 67
* **Total Voters**: 1,274 (635 Male, 639 Female)
* **Wards**: Wards 1 through 8 (House door numbers 1-1 to 2-144)

---

## 🔒 Security PIN Protection

This voter portal is protected with a **4-digit access PIN**. Every time the page is refreshed or visited, it asks for the 4-digit PIN.

* **Current Active PIN**: `2311`

### How to Update the PIN in Code
The PIN is strictly controlled in code (not accessible by normal users from the UI):
1. Open `index.html`.
2. Locate the setting near the top of the `<script>` tag:
   ```javascript
   const ACCESS_PIN = "2311";
   ```
3. Change `"2311"` to your new 4-digit PIN (e.g., `"9876"`).
4. Commit and push to GitHub:
   ```bash
   git commit -am "Update access PIN" && git push
   ```

---

## 🌐 Live Free Hosting on GitHub Pages

👉 **[https://vshaldb.github.io/Pathakunkam-Vote-Finder/](https://vshaldb.github.io/Pathakunkam-Vote-Finder/)**

---

## ✨ Features
* **Phonetic & Telugu Search**: Search by name or relative in English or Telugu (e.g. *Budumuru*, *బుడుమూరు*, *Pandranki*, *పాండ్రంకి*).
* **House Door Grouping**: Click any door number (`🏠 1-1`) to instantly view all family members residing at that address.
* **Ward Quick Filter**: One-click summary chips for Wards 1 to 8 with live voter counts.
* **Filters & Sort**: Filter by gender, age group (18-25, 26-40, 41-60, 61+), and sort by serial, name, house no., or age.
* **Copy Voter ID**: One-click copy for EPIC numbers with animated visual feedback.
* **Custom Andhra Emerald & Sapphire Theme**: Modern typography, cards, and automatic responsive dark/light mode.
