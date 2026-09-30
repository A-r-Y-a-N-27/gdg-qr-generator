# QR Code Generator & Designer

**Live Deployment:** [https://nimble-zabaione-e4062b.netlify.app/](https://nimble-zabaione-e4062b.netlify.app/)

This repository contains the Frontend task submission for the **GDG on Campus SRM Recruitments 2026-27 (Technical Domain)**. It is a fully browser-based application that allows users to generate, customize, preview, and download QR codes in real-time, operating entirely without a backend.

## Screenshots

![Application View](https://raw.githubusercontent.com/A-r-Y-a-N-27/gdg-qr-generator/main/screenshot-2026-09-30-210918.png)

## Features Implemented

*   **Real-time Generation & Multiple Types:** Supports instant QR code generation for Plain Text, URLs, Emails, Phone Numbers, and Wi-Fi networks with dynamic input fields based on the selected type.
*   **Deep Customization:** Users can modify foreground/background colors, select export sizes (up to 1024px), and adjust Error Correction levels (L, M, Q, H).
*   **Visual Presets:** Includes one-click visual presets (Classic, Bubblegum, Oceanic, Forest) to quickly apply appealing color combinations.
*   **Reliable High-Res Download:** Downloads exactly what is previewed as a crisp PNG file. The visual UI preview stays uniformly sized while the background engine generates the requested high-resolution file.
*   **Validation & Scan Reliability:** Validates user inputs (e.g., checking for valid HTTP links and Wi-Fi SSIDs) and displays real-time warnings if the user selects low-contrast colors that might affect readability[cite: 2].
*   **Persistent History:** Recently generated QR codes are stored locally using browser `localStorage` and persist even after the page is refreshed[cite: 2].
*   **Responsive Design:** Fully fluid UI that adapts perfectly to both desktop and mobile screens[cite: 2].

## Technologies Used

*   **HTML5**
*   **Tailwind CSS** (via CDN for rapid, responsive styling)[cite: 2]
*   **Vanilla JavaScript** (No complex frameworks required, logic runs entirely in the browser)[cite: 2]
*   **QRCode.js** (via CDN for canvas-based QR rendering)[cite: 2]
*   **Phosphor Icons** (for modern SVG iconography)

## How to Run Locally

Because this application relies entirely on frontend technologies and CDN links, no build steps or backend servers are required[cite: 2]. 

1. Clone this repository:
   ```bash
   git clone [https://github.com/A-r-Y-a-N-27/gdg-qr-generator.git](https://github.com/A-r-Y-a-N-27/gdg-qr-generator.git)
