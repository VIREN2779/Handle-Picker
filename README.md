# Handle-Picker

Design a modern Username(working name) that generates trendy, Reddit-style random usernames on demand.

**Purpose:** Users click a button to instantly get a random, catchy username in the "Adjective-Noun-Number" or "Adjective_Noun_Number" style (e.g. "BudgetAggravating566", "Intelligent-Fly-2700"). They can regenerate, copy, save favorites, and pick a style/format.

**Tech context (for layout feasibility, not for Stitch to render):** React + TypeScript frontend, Material UI components, deployed on Cloudflare Pages/Workers.

**Screens to design:**
1. **Home / Generator screen**
2. **History / Favorites panel**
3. **Style/Theme**
4. **App bar**

---

## Related concept to add to the site

**Style Packs / Persona Modes** — instead of one generic name style, let users pick a "pack" that changes the word banks and format:
- **Reddit Classic** — Adjective+Noun+Number
- **Gamer Tag** — edgier/aggressive words, leetspeak-ish numbers (e.g. "ShadowReaper_X99")
- **Professional** — clean, LinkedIn-safe handles (e.g. "MarketingPro2847")
- **Aesthetic/Minimal** — lowercase, dot-separated, soft words (e.g. "quiet.orbit.14")