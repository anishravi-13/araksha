# ARAKSHA – Industrial AR Safety Training & Competency Verification

**Smart India Hackathon (SIH 2026)** · Problem Statement ID: **SIH26041**  
**Team Techwolves (ID: 139519)**

---

## 📌 Overview

**ARAKSHA** is an offline-first, mobile-accessible 3D/AR practical safety training and certification system engineered for underground coal/metal mines and heavy industrial plants. It replaces ineffective static paper manuals with hands-on, sequential 3D emergency simulations that run on standard ₹10,000 Android smartphones without requiring expensive VR hardware.

Every completed scenario produces a tamper-proof, QR-verifiable certificate cryptographically linked to the candidate's verified 3D action trajectory log.

---

## 🚀 Key Features

* **Real Interactive 3D Scenarios (Three.js WebGL / Unity ARCore):**
  * 🔥 **Fire & Evacuation:** Trigger emergency pull stations, select electrical-grade $\text{CO}_2$ suppression, extinguish flame base, and escape via pressurized green exit portals.
  * ☁️ **Gas Leak Protocol:** Real-time multi-gas detection ($2.4\%\ \text{CH}_4$ alarm threshold), master electrical spark isolation, SCSR oxygen apparatus fitting, and evacuation to intake air shafts.
  * 👷 **Mandatory PPE Inspection:** Scan and fit compliant safety gear (certified helmets, dust respirators, leather gloves, steel-toe boots) while rejecting defective or non-compliant items.
  * ⚙️ **Machinery Lockout-Tagout (LOTO):** Conveyor jam emergency stopping, master isolator disconnect, individual padlock application, and high-visibility danger tag fastening.
* **Hands-on Action Verification:** 
  * Direct 3D mesh raycasting interaction paired with a quick-response interactive equipment tray.
  * Real-time 3D tracking tags projected over safety equipment in the viewport.
* **Approval & Certification Engine:**
  * Candidates scoring $\ge 70\%$ are awarded **APPROVED & CERTIFIED** status.
  * Automatic generation of unique Certificate IDs (e.g. `ARK-XXXXXX`) and 3D Action Audit Hashes.
* **Public QR Verification & Audit Portal:**
  * Self-contained SVG QR code matrix generator linking to the verification registry.
  * Real-time statutory compliance verification adhering to DGMS OSH Code 2020 & Mines Act 1952.
* **Supervisor Operations Console:**
  * Real-time crew rosters, dynamic site risk index calculation, automated safety alerts for new recruits ($<30$ days), and downloadable statutory CSV reports.
* **Offline-First Resilience:**
  * Full functionality without cellular/internet connectivity deep underground; automatic syncing to the central ledger when reconnecting.
* **Bilingual Guidance:**
  * Instant toggle between English and Hindi with Web Speech API audio synthesis.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Custom Properties & Safe Area Insets), Vanilla ES6+
* **3D & Graphics:** Three.js (r128), WebGL shaders, raycasting, dynamic lighting & fog
* **Data & Storage:** LocalStorage / IndexedDB / offline caching
* **Typography:** Google Fonts (Barlow, Barlow Condensed, JetBrains Mono)
* **Standards & Compliance:** DGMS OSH Code 2020, Factories Act 1948, Mines Act 1952

---

## 💻 Running Locally

1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Google Chrome, Microsoft Edge, Firefox, Safari).
   ```bash
   # Or serve via a simple local server:
   npx serve .
   # or
   python -m http.server 8080
   ```
3. Navigate through the 3D scenarios, pass the test, and verify your certificate.

---

## 👥 Authors
* **Team Techwolves (ID 139519)**
* Smart India Hackathon 2026
