# Seoul Bound — Korea Trip Dashboard

A single-page trip dashboard for a March 2026 Korea trip (Stockholm → Seoul via Copenhagen).

## Deploy

This is a single `index.html` file — no build step, no dependencies, no framework.

### GitHub Pages

1. Push this repo
2. Go to **Settings → Pages**
3. Set source to **main** branch, root (`/`)
4. Site will be live at `https://<username>.github.io/<repo-name>/`

### Alternatively

Open `index.html` in any browser. Everything works offline except:
- Google Fonts (falls back to system fonts gracefully)
- Live weather widget (fetches from wttr.in)
- Outbound links (Wikipedia, Google Maps, App Store, etc.)

## What's in it

| Section | Description |
|---|---|
| **Countdown** | Live countdown to departure (Mar 3 2026, 21:00 CET) |
| **Flights** | Outbound/return tabs with SAS flight details, lounges, meals |
| **Hotels** | 3 stays — Incheon, Pohang, Seoul — with copy-to-clipboard addresses and Google Maps links |
| **Timeline** | Visual trip timeline (vertical on mobile) |
| **Currency** | SEK ↔ KRW live calculator with quick-reference amounts |
| **Weather** | Live weather for Seoul & Pohang via wttr.in |
| **Phrases** | 9 Korean survival phrases with hangul, romanization, English |
| **Daily Word** | Rotating Korean vocabulary with example sentences |
| **Checklist** | Interactive packing/prep checklist with localStorage persistence |
| **Emergency** | Korean emergency numbers + Swedish Embassy |
| **Useful Links** | Kakao T, Naver Maps, Subway Korea, SIM card, plug type |
| **Cultural Canon** | 46 insider-level entries across Film, TV, Music, Literature, Food, History — curated for depth, not tourist-level familiarity |

## Tech

- Pure HTML/CSS/JS — no dependencies
- CSS Grid layout (6-column → 2-column → 1-column responsive)
- Google Fonts: Sora, Libre Baskerville, IBM Plex Mono, Noto Sans KR
- Mobile-optimized with vertical timeline, stacked cards, touch-friendly targets
- Dark warm palette inspired by Dieter Rams / analog design

## File structure

```
├── index.html    ← everything
└── README.md
```

That's it. One file.
