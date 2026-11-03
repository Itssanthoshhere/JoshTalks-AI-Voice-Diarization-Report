<div align="center">

  <img src="logo.png" alt="Josh Talks Logo" width="90" height="90" />

  # 🎙️ Josh Talks AI Voice Diarization Report (125 Hours Project)

  <p align="center">
    <a href="https://diarization-report-web.vercel.app" target="_blank">
      <img src="https://img.shields.io/badge/🟢_LIVE_DEMO-diarization--report--web.vercel.app-a4161a?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Web Report" />
    </a>
    <a href="https://diarization-report-web.vercel.app">
      <img src="https://img.shields.io/badge/Project_Status-Complete_Through_Nov_3-059669?style=for-the-badge" alt="Project Status" />
    </a>
    <a href="https://diarization-report-web.vercel.app">
      <img src="https://img.shields.io/badge/Total_Duration-56h_38m_29s-8b1116?style=for-the-badge" alt="Total Duration" />
    </a>
    <a href="https://diarization-report-web.vercel.app">
      <img src="https://img.shields.io/badge/Total_Sessions-169_Audio_Files-d4af37?style=for-the-badge" alt="Total Sessions" />
    </a>
  </p>

  <h3>
    🌐 <strong>Live Report:</strong> 
    <a href="https://diarization-report-web.vercel.app" target="_blank">
      https://diarization-report-web.vercel.app
    </a>
  </h3>

  <p align="center">
    <em>Interactive audit dashboard and reporting repository for the 125 Hours Multi-Speaker Diarization Project (4 October – 3 November 2026). Features multi-column dynamic sorting, quick presets, category filters, and acoustic room telemetry.</em>
  </p>

</div>

---

## 📌 Executive Summary

This repository hosts the official interactive tracking report for internal operations at Josh Talks. It documents **169 audio recording sessions** totaling **3,398 minutes 29 seconds** (~56 hours 38 minutes) across 31 project days.

### Key Milestones
- **Weeks 1–3 (4–24 Oct):** Core data collection across 2, 3, and 4-speaker configurations at Bennett University and Josh Talks facilities (126 sessions, 2,297m 48s).
- **Week 4 (26–31 Oct):** Kickoff of the dedicated 8-Speaker (8 SPK) collection phase at Bennett University GD rooms and Josh Talks HQ Leap Studio (32 sessions, 813m 19s).
- **Week 5 (1–3 Nov):** High-density multi-speaker studio sessions at Josh Talks HQ Basement Studio and Leap Gurgaon (11 sessions, 287m 22s).
- **2 November 2026 Milestone:** Dedicated **Quality Check (QC)** milestone conducted across all accumulated multi-speaker recordings.

---

## 📊 Summary Statistics & Phase Breakdown

| Phase / Period | Dates | Sessions | Duration | Key Focus & Environment |
| :--- | :--- | :---: | :--- | :--- |
| **Week 1** | 4–10 October 2026 | **57** | 868m 52s (14h 28m 52s) | 2, 3, 4 SPK; Classrooms & Faculty Cabins |
| **Week 2** | 11–18 October 2026 | **42** | 806m 39s (13h 26m 39s) | 2, 3, 4 SPK + 3 × 5 SPK; Conference Rooms |
| **Week 3** | 20–24 October 2026 | **27** | 622m 17s (10h 22m 17s) | 4 SPK focus; Music Rooms & Hatchery |
| **Week 4** | 26–31 October 2026 | **32** | 813m 19s (13h 33m 19s) | 8 SPK phase kickoff (30 × 8SPK, 2 × 7SPK) |
| **Week 5** | 1–3 November 2026 | **11** | 287m 22s (4h 47m 22s) | 8 SPK HQ Studios (Basement & Leap) |
| **Quality Check** | 2 November 2026 | **—** | — | Quality Check (QC) conducted |
| **Total Cumulative** | **4 Oct – 3 Nov 2026** | **169** | **3,398m 29s (56h 38m 29s)** | **31 Calendar Days (26 Active, 1 QC, 4 Breaks)** |

*(Note: In accordance with project audit conventions, the single 14m 33s folder identified on 13 October is cataloged but excluded from the running operational subtotal).*

---

## ✨ Features & Interactive Capabilities

1. **Multi-Column Interactive Sorting**:
   - Click any table header to toggle ascending/descending order:
     - 📅 **Date** (Timestamp sort)
     - 👥 **Speaker Columns** (2 SPK, 3 SPK, 4 SPK, 5 SPK, 7 SPK, 8 SPK)
     - 🔢 **Total Sessions**
     - ⏱️ **Duration** (Parsed exact seconds)
     - 📍 **Notes & Locations** (Alphabetical)
   - Visual sort direction indicators (`▲` / `▼` / `↕`).

2. **Quick-Sort Presets**:
   - ⚡ **Newest First**: View most recent sessions first (3 Nov on top).
   - 📅 **Oldest First**: Full chronological overview from 4 Oct.
   - ⏱️ **Longest Duration**: Highlights heavy-recording session days.
   - 🔢 **Highest Session Count**: Sorts days by total sessions completed.

3. **Filter Pills & Real-Time Search**:
   - One-click filters: **All Days (31)**, **8 SPK Phase (8)**, and **QC & Breaks (4)**.
   - Instant live text search matching date, room telemetry, or team notes.

4. **Design & Brand Alignment**:
   - Pure light aesthetic (`#ffffff` / `bg-white`) with high-contrast slate typography (`#111827`, `#334155`).
   - Crimson primary brand color (`#a4161a`) and warm gold accents (`#d4af37`), matching the `medi-voice-ai` design system.
   - Elegant typography pairing: **Plus Jakarta Sans** for crisp data tables and **Playfair Display** for executive headings.
   - Official Josh Talks logo and favicon integrated via embedded SVG / base64 and static assets.
   - Custom pointer/caret styled to project theme.

5. **Print & PDF Optimization**:
   - Clean `@media print` styles strip UI controls, navigation, and shadows for clean PDF export.

---

## 🏛️ Room Telemetry & Recording Locations

The project captures acoustic diarization data across diverse real-world environments:

- **Josh Talks HQ – Leap Studio (Gurgaon)**: Acoustically treated studio environment with multi-mic arrays.
- **Josh Talks HQ – Basement Studio (Gurgaon)**: Controlled studio space for high-density 8-speaker sessions.
- **Bennett University – Office GD Room (P-Block)**: 5.5m × 4m × 3m glass-door conference space with ambient HVAC.
- **Bennett University – PCC - 121**: 8m × 6m × 3.5m academic lecture hall with natural classroom reverberation.
- **Bennett University – Bennett Hatchery**: 12m × 8m × 3.5m open-plan innovation hub with varied background activity.
- **Bennett University – Faculty Cabin (P-Block)**: 4m × 3.5m × 3m compact faculty office setting.
- **Bennett University – Music Room**: 6m × 5m × 3m damp acoustic room.

---

## 🛠️ Repository Structure

```
diarization-report-web/
├── index.html       # Single-page interactive report (HTML5, Tailwind CDN, Vanilla JS)
├── logo.png         # Official Josh Talks logo (56x56 PNG)
├── favicon.png      # High-resolution favicon
├── favicon.ico      # Fallback favicon
├── .gitignore       # Git ignore rules (.vercel, .DS_Store, logs)
└── README.md        # Detailed project documentation and audit logs
```

---

## 🚀 Running Locally

This dashboard is a lightweight, zero-dependency static web application:

1. Clone the repository:
   ```bash
   git clone https://github.com/Itssanthoshhere/diarization-report-web.git
   cd diarization-report-web
   ```

2. Open in any modern web browser:
   ```bash
   open index.html
   ```
   *Or serve with any static web server:*
   ```bash
   npx serve .
   # or
   python3 -m http.server 8000
   ```

---

## 🌐 Deployment

The site is configured for continuous zero-config deployment on Vercel:

```bash
vercel --prod
```

---

## 👤 Author & Internal Contact

- **Prepared by:** Santhosh VS ([@Itssanthoshhere](https://github.com/Itssanthoshhere))
- **Organization:** Josh Talks
- **Project:** 125 Hours Multi-Speaker AI Voice Diarization

---
*Last Updated: 4 November 2026*
