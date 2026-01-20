# 🔒 OpenSSL AES-256-CBC Technical Laboratory

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-blue.svg)](http://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Status: Operational](https://img.shields.io/badge/Status-Operational-success.svg)]()
[![Platform: Web](https://img.shields.io/badge/Platform-Web-orange.svg)]()

A high-performance, privacy-focused technical ecosystem specializing in **symmetric cryptography**, **industrial data analytics**, and **voxel-based simulations**. 

> **Live Lab Environment:** [kevinyibochen.com](http://kevinyibochen.com)

---

## 🚀 Core Research Modules

### 1. Secure Decryptor (Symmetric Cryptography)
A 100% client-side implementation of the OpenSSL salted decryption standard.
* **Zero-Upload Architecture:** All computations are performed locally using the browser's native `Web Crypto API` (`window.crypto.subtle`).
* **Legacy Compatibility:** Implements a custom JavaScript-based `EVP_BytesToKey` derivation logic (MD5-based) to match OpenSSL CLI output.
* **Security Margin:** Specifically targets **AES-256-CBC**, providing high-grade resistance against unauthorized data access.

### 2. MWAR (MakerWorld Analytics Report)
A data-driven analytics engine designed for 3D printing creators.
* Visualizes engagement metrics and model performance.
* Helps creators optimize their community presence through historical data analysis.

### 3. MWG (MakerPlan Optimization)
A production scheduling and material forecasting engine for additive manufacturing.
* Real-time interface for batch production planning.
* Predictive modeling for filament consumption to reduce industrial waste.

### 4. Voxel Simulation (Graphics Engineering)
A high-performance Minecraft-style voxel engine built for the web.
* **Procedural Generation:** Utilizing Perlin Noise for natural terrain synthesis.
* **Optimization:** Implements Dynamic Level of Detail (LOD) and AABB collision detection to maintain high FPS on various hardware.

---

## 💻 Technical Infrastructure

* **Frontend:** HTML5, CSS3 (Tailwind CSS), JavaScript (ES6+).
* **Security:** Web Crypto API, custom MD5/EVP key derivation.
* **Visualization:** Chart.js for industrial analytics.
* **Graphics:** Canvas/WebGL for 3D simulation.

---

## 🔒 Security & Privacy Philosophy

In an era of increasing data centralization, this laboratory advocates for **Localized Computing**:
1.  **Stateless Operation:** No databases are used; your data exists only in your device's volatile memory.
2.  **No Telemetry:** We do not track, store, or log any cryptographic operations or input data.
3.  **Auditability:** This repository serves as an open-source reference to ensure mathematical transparency.

---

## 📂 File Structure

| File | Description |
| :--- | :--- |
| `index.html` | Core Laboratory Interface & Decryption Tool |
| `MWAR.html` | MakerWorld Analytics Module |
| `MWG.html` | MakerPlan Optimization Engine |
| `Minecraft.html` | Voxel Engine Simulation Environment |
| `Privacy.html` | Compliance & Data Protection Policy |
| `Terms.html` | Usage Terms & Open Source Licensing |

---

## 📄 License

This project is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**. 

---
© 2026 **OpenSSL AES-256-CBC Technical Laboratory**. All rights reserved.
