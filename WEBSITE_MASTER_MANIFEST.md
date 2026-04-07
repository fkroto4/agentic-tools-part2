# FRANK LEO KROTO IV | WEBSITE MASTER MANIFEST
## LAST UPDATED: Tuesday, April 7, 2026

This document serves as the persistent memory and technical specification for the Advanced Agentic Portfolio. JARVIS MUST reference this file before and after every modification to ensure continuity and prevent regression.

---

## I. CORE IDENTITY & BRANDING
- **Full Professional Title:** Frank Leo Kroto IV
- **Academic Affiliation:** Xavier University '27 (Business Management & Applied AI Strategy)
- **Agentic Hub:** Agentic Strategy Command Center (Interactive Dashboard)
- **MLB Focus:** Live League Orchestrator (v6.0 - Real-Time API Integration)
- **Primary Course:** MGMT 342
- **Aesthetic:** Pro-Analytics Dark-Glass (Inter / Fira Code Typography)

## II. VISUAL DESIGN LANGUAGE
### CSS Variables (The "Source of Truth")
```css
:root {
    --xav-blue: #0C2340;
    --bg-dark: #020617;
    --glass-bg: rgba(30, 41, 59, 0.7);
    --glass-border: rgba(255, 255, 255, 0.1);
    --accent: #38bdf8; /* Dynamic MLB Accent Color */
}
```

## III. FUNCTIONAL SPECIFICATIONS
### 1. Live League Orchestrator (v6.0)
- **Architecture:** Asynchronous `fetch` calls to `statsapi.mlb.com`.
- **Live Rosters:** Dynamically fetches active roster for all 30 MLB teams.
- **Real-Time Scoreboard:** Fetches daily schedule and displays live game states (Live/Final/Scheduled).
- **Interactive Player Cards:** Renders as many players as returned by the API with MLB headshots.
- **Dynamic Theming:** Updates `--accent` color and hub titles based on `switchTeam(abbr)`.

### 2. Agentic Strategy Command Center
- **Interface:** Dual-column grid (Strategy Hub + JARVIS Sidebar).
- **Interactive Nodes:** Four strategy cards triggering `updateAgent()` briefings.
- **JARVIS Overlay:** Dynamic text updates, pulsing agent animation, and status monitoring.

---

## IV. PERMANENT DIRECTIVES (CRITICAL)
1. **Middle Name Integrity:** "Leo" is non-negotiable in all identity strings.
2. **API Autonomy:** NEVER revert to hardcoded rosters; the site must remain a portal for live global data streams.
3. **Hybrid Branding:** Xavier branding is the anchor; MLB accents must be dynamic.
4. **Universal Support:** All 30 MLB teams must be supported in the `teamMap` and selector.
5. **Version Tracking:** Footer must state `Autonomous Deployment v6.0`.

---

## V. UPDATE LOG
- **v6.0:** Transitioned to **Real-Time MLB Stats API**. Implemented live rosters, live game tracking, and a "Pro-Analytics" visual overhaul.
- **v5.5:** Implemented the MLB 2026 Universal Engine (Simulated).
- **v5.4:** Upgraded Professional Identity to Agentic Command Center.
- **v5.2:** Established Master Manifest.
