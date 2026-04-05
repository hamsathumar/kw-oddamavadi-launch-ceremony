LAUNCH CEREMONY DISPLAY — OPERATOR GUIDE
=========================================

Koralaipattu West Oddamavadi Development Plan 2026–2035
Launching Ceremony & Initial Stakeholder Meeting
07 April 2026

─────────────────────────────────────────────────────────────────

SETUP
─────
1. Copy the entire folder to a USB drive
2. Plug USB into the smartboard computer
3. Open Chrome browser
4. Press F11 for fullscreen mode
5. Open index.html (File → Open File, or drag into browser)

─────────────────────────────────────────────────────────────────

RUNNING THE CEREMONY
────────────────────
6. The ceremony screen fills the display automatically
7. Each guest approaches and presses the gold button once
8. Proceed in order — 7 guests, 7 presses
9. On the 7th press, the celebration launches automatically

─────────────────────────────────────────────────────────────────

TO RESET / REHEARSE
───────────────────
Press Ctrl+Shift+R to reload and start over

─────────────────────────────────────────────────────────────────

FILE STRUCTURE
──────────────
launch-ceremony/
├── index.html        ← Main ceremony file (open this)
├── logos/
│   ├── uda-logo.png  ← Urban Development Authority logo
│   └── kw-ps-logo.png← KW Pradeshiya Shaba logo
└── README.md         ← This file

─────────────────────────────────────────────────────────────────

ADDING LOGOS
────────────
Place logo images in the logos/ folder:
- uda-logo.png     (Urban Development Authority)
- kw-ps-logo.png   (KW Pradeshiya Shaba, Oddamavadi)

PNG or SVG format recommended. If logos are missing,
the display will still work — logo area is hidden gracefully.

─────────────────────────────────────────────────────────────────

TROUBLESHOOTING
───────────────
• Fonts look wrong
  → Ensure internet is connected for Google Fonts
  → OR accept the fallback serif font (Georgia)

• Logos not showing
  → Check that logo files are in the logos/ folder
  → File names must match exactly: uda-logo.png, kw-ps-logo.png

• Confetti not showing
  → Ensure internet is available for CDN
  → OR download confetti.browser.min.js and update the script src

• Button not responding
  → Wait for current animation to complete (~700ms)
  → Refresh page if stuck (Ctrl+Shift+R)

• Screen not fullscreen
  → Press F11 in Chrome/Edge
  → Or right-click → "Enter Full Screen"

─────────────────────────────────────────────────────────────────

OFFLINE MODE
────────────
For fully offline operation:
1. Download canvas-confetti library:
   https://cdn.jsdelivr.net/npm/canvas-confetti@1.9.3/dist/confetti.browser.min.js
2. Save as confetti.min.js in same folder as index.html
3. Edit index.html: change the script src to "./confetti.min.js"

─────────────────────────────────────────────────────────────────

TECHNICAL NOTES
───────────────
• Designed for 1920×1080 displays (scales to any resolution)
• Touch-optimized for smartboard interaction
• No server required — runs directly from file system
• Works in Chrome, Edge, Firefox, Safari

─────────────────────────────────────────────────────────────────

Contact: Urban Development Authority
Event: 07 April 2026
Venue: Gathering Center, Koralaipattu West Pradeshiya Shaba, Oddamavadi
