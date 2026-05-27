# supercollector_Twilight_zone
Here’s a ready‑to‑drop `README.md` for the repo that holds this Supercollector / Twilight Zone EP page.

***

# XTincT – Twilight Zone EP · Supercollector UI

Custom CRT / Fallout‑inspired web skin for the **Twilight Zone EP** release page on [Supercollector](https://release.supercollector.xyz). This repository contains the HTML/CSS used to transform the default Supercollector embed into a white‑noise terminal with LED bus‑sign accents and reactive “Play / Collect” controls. [release.supercollector](https://release.supercollector.xyz)

## Features

- White‑noise CRT background with scanlines, vignette, and subtle flicker layered behind the Supercollector release block. [claude](https://claude.ai/chat/794e0126-cc34-4453-a241-267689b7c631)
- LED‑style “SIGNAL ACTIVE — ZONE ONLINE” strip with a pulsing status dot and horizontally scrolling marquee text, inspired by bus/train destination signs. [claude](https://claude.ai/chat/794e0126-cc34-4453-a241-267689b7c631)
- Artwork and track tiles styled as mini CRT panes, including per‑tile scanlines and left‑edge LED accent bars on hover. [claude](https://claude.ai/chat/794e0126-cc34-4453-a241-267689b7c631)
- Reactive **Play** and **Collect** buttons whose active states glow with the same LED matrix aesthetic as the signal strip for cohesive feedback. [claude](https://claude.ai/chat/794e0126-cc34-4453-a241-267689b7c631)
- Fully themeable via CSS custom properties (colors, glow intensity, noise strength, typography) so other releases can reuse the skin with minimal tweaks. [claude](https://claude.ai/chat/794e0126-cc34-4453-a241-267689b7c631)

## Tech stack

- HTML + CSS only (no build step required).  
- Uses Google Fonts: `VT323`, `Share Tech Mono`, `Orbitron`, and optionally `Bebas Neue` for display headlines. [claude](https://claude.ai/chat/794e0126-cc34-4453-a241-267689b7c631)
- Designed to layer on top of the default Supercollector release markup via its “Custom CSS” field. [release.supercollector](https://release.supercollector.xyz)

## Getting started

1. Clone the repo:

   ```bash
   git clone https://github.com/<your-username>/twilight-zone-supercollector-ui.git
   cd twilight-zone-supercollector-ui
   ```

2. Open `index.html` in a browser to preview the standalone version of the UI.

3. For Supercollector integration, copy the CSS from `supercollector.css` (or the relevant section) into the **Custom CSS** box for your release on [release.supercollector.xyz](https://release.supercollector.xyz). [release.supercollector](https://release.supercollector.xyz)

4. Adjust the `:root` variables at the top of the CSS to tune colors, glow, and typography to another project if needed. [claude](https://claude.ai/chat/794e0126-cc34-4453-a241-267689b7c631)

## Key files

| File                | Description                                           |
|---------------------|-------------------------------------------------------|
| `index.html`        | Standalone demo using static HTML + CSS. [claude](https://claude.ai/chat/794e0126-cc34-4453-a241-267689b7c631)      |
| `supercollector.css`| CSS overrides meant to be pasted into Supercollector’s custom CSS field. [claude](https://claude.ai/chat/794e0126-cc34-4453-a241-267689b7c631) |
| `README.md`         | Project overview and integration instructions.        |

## Customization

You can quickly reskin the page by changing the CSS variables in `:root`:

- `--background-color` – overall page background (CRT base).  
- `--led-color` – primary LED / signal color for the strip, accent bars, and button glow.  
- `--font-family` and HUD font imports – control whether the interface leans more “Pip‑Boy terminal” or “IRL bus destination sign.” [claude](https://claude.ai/chat/794e0126-cc34-4453-a241-267689b7c631)

For deeper changes (layout, extra panels, new copy), modify the HTML in `index.html`, then port the relevant CSS back into Supercollector once you’re happy with it. [freecodecamp](https://www.freecodecamp.org/news/how-to-structure-your-readme-file/)

## License

all rights reserved.
