# parcy-dice-grove

A FreeWebStore template for **nonprofit.environment** by **@Aa11rn**.

# Parcy~Dice — Bird of Paradise Garden

"The bird that blooms." A warm, single-page community botanical-garden
template built around the Bird of Paradise (Strelitzia): deep grove-green
and cream surfaces, Strelitzia-orange CTAs, blue-petal accents, a soft
Fraunces display serif, and SVG-only art.

## Features

- BloomBoard ribbon with cycling garden feed, live canopy clock, pause + dismiss
- Sticky nav with orange "Join the Grove" CTA + mobile drawer menu
- Hero with live grower counter, bloom-season status chip, and Strelitzia emblem
- The Collection: four Bird of Paradise varieties with bloom-season and rarity badges
- Animated count-up statistics band
- Conservation Care Checklist (centerpiece): four persisted lists (new-plant,
  weekly water & feed, monthly bloom care, seasonal) with per-list progress
  bars, overall progress, and reset
- "Join the Grove" signup: validated email + growing environment + channels
  (SMS / Email / WhatsApp), loading, success, duplicate-email, and reset states
  with a persisted grower counter + social-proof avatar stack
- Garden helpline cards and share tools (copy-link + social intents)
- Scroll-reveal animations with prefers-reduced-motion support
- Toast notifications, mobile CTA bar, and back-to-top
- Fully slot-annotated (`data-fws-slot`) for FreeWebStore content editing

## Included Files

```
parcy-dice-grove/
├── index.html            # Main template page
├── package.json          # Node dependency file (FWS CLI)
├── template.config.json  # FWS template metadata
├── tailwind.config.js    # Tailwind design tokens reference
├── preview.png           # Template preview image (add your own)
└── README.md             # This file
```

## Customization

All editable content regions are marked with `data-fws-slot` attributes. Edit
these directly in the HTML or via the FreeWebStore editor after publishing.
See `slots.md` for the slot reference used by this template.

## Publishing

```sh
npx @freewebstore/cli doctor     # local validation
npx @freewebstore/cli login      # one-time GitHub App install
npx @freewebstore/cli publish    # upload + create repo + queue for review
```

## License

MIT (auto-set by `fws init`). FreeWebStore requires MIT for community
templates — see CONTRIBUTING.md in the platform docs for the why.
MIT — see `template.config.json` for details.