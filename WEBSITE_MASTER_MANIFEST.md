# FRANK LEO KROTO IV | WEBSITE MASTER MANIFEST
## LAST UPDATED: Tuesday, April 7, 2026

This document serves as the persistent memory and technical specification for the Advanced Agentic Portfolio. JARVIS MUST reference this file before and after every modification to ensure continuity and prevent regression.

---

## I. CORE IDENTITY & BRANDING
- **Full Professional Title:** Frank Leo Kroto IV
- **Academic Affiliation:** Xavier University '27 (Business Management & Applied AI Strategy)
- **Primary Course:** MGMT 342
- **Icon/Headshot:** `frankkrotoicon.jpg`
- **Fallback URL:** `https://ui-avatars.com/api/?name=Frank+Leo+Kroto+IV&background=0C2340&color=fff&size=512`
- **Navigation Branding:** `FK.IV` (font-weight: bold, font-size: 1.5rem, color: var(--xav-blue))

## II. VISUAL DESIGN LANGUAGE
### CSS Variables (The "Source of Truth")
```css
:root {
    --xav-blue: #0C2340;      /* Xavier Navy */
    --xav-silver: #9EA2A2;    /* Xavier Silver */
    --xav-light: #F0F4F8;     /* Xavier Light BG */
    --gua-red: #E31937;       /* Guardians Red */
    --gua-navy: #0C2340;      /* Guardians Navy */
    --bg-color: #f8fafc;      /* Default Light BG */
    --card-bg: #ffffff;       /* Card BG */
    --text-main: #0f172a;     /* Main Text */
    --text-light: #475569;    /* Light Text */
    --accent: #3b82f6;        /* UI Accent Blue */
    --border-color: #e2e8f0;  /* Subtle Borders */
    --nav-bg: rgba(255, 255, 255, 0.9); /* Nav Glassmorphism */
}

[data-theme="dark"] {
    --bg-color: #0f172a;
    --card-bg: #1e293b;
    --text-main: #f8fafc;
    --text-light: #94a3b8;
    --border-color: #334155;
    --nav-bg: rgba(15, 23, 42, 0.9);
}
```

### Aesthetic Standards
- **Section Headers:** `font-size: 2.5rem`, `color: var(--xav-blue)`, border-bottom: `4px solid var(--gua-red)`.
- **Hero Section:** Linear gradient (`135deg`, `var(--xav-blue)` to `#1e3a8a`), `8px solid var(--xav-silver)` bottom border.
- **Typography:** `Segoe UI`, `system-ui`, `sans-serif`. `line-height: 1.6`.

---

## III. FUNCTIONAL SPECIFICATIONS
### 1. Theme Orchestration
- **Persistence:** Attribute `data-theme` on `body`.
- **Logic:** `document.body.toggleAttribute('data-theme')`.
- **Icon Swap:** Moon (`fas fa-moon`) to Sun (`fas fa-sun`).

### 2. Interactive Progress Hub
- **Task Array Structure:** `[{ text: '...', done: true/false }]`.
- **SVG Math:** `stroke-dasharray: 565`; `stroke-dashoffset: 565 - (565 * percent / 100)`.
- **Calculation:** `Math.round((completed/tasks.length)*100)`.

### 3. Guardians 2026 Data Hub (The "Agentic Proof")
- **Player Card Data:** 
  - `name`, `pos`, `num`, `id` (MLB People ID for headshots).
  - `s1`, `s2`, `s3` (Verbatim 2026 projections/metrics).
- **Headshot Logic:** `https://img.mlbstatic.com/mlb-photos/image/upload/d_player_profile_default_image.png/w_426,q_auto:best/v1/people/${p.id}/headshot/67/current`.
- **Card Interaction:** 180-degree rotation on click (`.player-card.flipped`).
- **Filtering Logic:** `p.group === filter` with groups: `Infielders`, `Outfielders`, `Pitchers`, `Catchers`.

---

## IV. PERMANENT DIRECTIVES (CRITICAL)
1. **Middle Name Integrity:** "Leo" is non-negotiable in all identity strings.
2. **Rationale Preservation:** The "Why the Guardians Database?" section MUST explain **Agentic Data Orchestration** and **Dynamic DOM Manipulation**.
3. **Hybrid Branding:** Do NOT separate Xavier Blue from Guardians Red; they must coexist as a unified professional aesthetic.
4. **Interactive Reliability:** Every build must include working Progress Hub and Flip-Card functionality.
5. **Version Tracking:** Footer must state `Autonomous Deployment v5.2` (or current increment).

---

## V. UPDATE LOG
- **v5.2:** Integrated middle name "Leo". Established Master Manifest. Cleaned legacy test files (`joke.md`, `joke.docx`). Synchronized GitHub repository.
