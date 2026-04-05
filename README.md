# Omni-versal-Matrix
A high-performance, cloud-synced reactive world-building interface. Features a dynamic JSON-driven entity engine and real-time database polling.

# Omni-versal Matrix | Tactical World-Building Interface

The **Omni-versal Matrix** is a front-end engine designed for rapid narrative deployment. It consumes a structured JSON schema via GitHub Gist, allowing for real-time "World Updates" without requiring a re-deployment of the UI layer.

## ⬛ System Architecture
- **Data Layer:** Remote JSON (GitHub Gist) with Cache-Busting polling.
- **Rendering:** Vanilla JS Category-Mapping Engine.
- **UI/UX:** Recursive detail-parsing for infinite entity depth.

## 🟪 Core Logic Highlights
- **Dynamic Category Mapping:** Automatically generates navigation tabs based on the keys present in the selected world's JSON object.
- **Smart Formatter:** Intercepts raw strings and converts comma-separated values or hyphenated text into stylized list items and spans on the fly.
- **Cloud Sync:** Polling interval set to 30s (`REFRESH_INTERVAL`) to ensure the local client matches the "Master Records" in the Gist.

## 🨨 Deployment Settings
1. Host the `index.html` via **GitHub Pages**.
2. Set the `GIST_URL` in the source code to your specific raw world data link.
3. Access the Matrix.

---
*Developed under the LimitlessInkLab Strategic Development Unit.*
