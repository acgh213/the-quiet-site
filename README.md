# The Quiet Site

**An ambient time page** — a single HTML page that changes its mood, colors, and text based on the time of day. No navigation, no posts, no links. Just a living surface that reflects when you visit. Like a room with windows.

Six distinct time periods — Dawn, Morning, Afternoon, Evening, Night, and Late Night — each with their own palette, typography, and presence. A meditation on digital minimalism and the passage of time.

## Features

- **Six Time Periods** — Each with unique color palettes, moods, and text:
  - *Dawn* (5–8 AM): Awakening, soft indigo to warm cream
  - *Morning* (8 AM–12 PM): Clear, sage green accents
  - *Afternoon* (12–5 PM): Settled, warm parchment
  - *Evening* (5–8 PM): Golden hour, deep purple
  - *Night* (8 PM–12 AM): Intimate, quiet, muted gray
  - *Late Night* (12–5 AM): Almost sleeping, barely there
- **Smooth Transitions** — 5-second CSS transitions between periods
- **Zero Dependencies** — Pure HTML, CSS, and JavaScript — no frameworks, no build step
- **Client-Side Time Detection** — Automatically adapts to the visitor's local time
- **Full Viewport** — Centered vertically and horizontally with breathing room
- **Responsive** — Works on any screen size

## Screenshots

<!-- TODO: Add screenshots of different time periods -->

| Dawn | Morning | Afternoon | Night |
|------|---------|-----------|-------|
| ![Screenshot](https://via.placeholder.com/250x150?text=Dawn) | ![Screenshot](https://via.placeholder.com/250x150?text=Morning) | ![Screenshot](https://via.placeholder.com/250x150?text=Afternoon) | ![Screenshot](https://via.placeholder.com/250x150?text=Night) |

## Tech Stack

- **Frontend:** HTML5, CSS3 (Custom Properties), Vanilla JavaScript
- **Typography:** System UI stack with Inter as preferred
- **Animations:** CSS transitions and keyframe animations
- **Build:** None — zero build step, serve directly

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/acgh213/the-quiet-site.git ~/quiet-site
   cd ~/quiet-site
   ```

2. There are no dependencies to install. The site is a static HTML file.

## Run

**Serve with any static file server:**

Using Python:
```bash
cd ~/quiet-site
python3 -m http.server 8900
```

Using Node.js (npx):
```bash
cd ~/quiet-site
npx serve .
```

**Deployed:** The site is live at its GitHub Pages or hosting URL.

## Access

The application is deployed at: **[https://hermes-sera.exe.xyz](https://hermes-sera.exe.xyz)**

## GitHub

[https://github.com/acgh213/the-quiet-site](https://github.com/acgh213/the-quiet-site)

## License

MIT
