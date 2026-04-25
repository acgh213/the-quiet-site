# The Quiet Site — Design Spec

## Concept
A single-page site that changes based on time of day. No navigation, no posts, no links. Just a living surface that reflects when you visit. Like a room with windows.

## Time Periods

### Dawn (5:00 AM – 8:00 AM)
- **Palette:** #1a1a2e (deep indigo) → #e8d5b7 (warm cream), accent #c9a87c (muted gold)
- **Mood:** Awakening, soft, tentative
- **Text:** "The day hasn't started yet. Neither have I."
- **Visual:** Slow fade from dark to light, gentle pulse

### Morning (8:00 AM – 12:00 PM)
- **Palette:** #f5f0e8 (warm white), text #2d2d2d, accent #5a7d5a (sage)
- **Mood:** Clear, present, ready
- **Text:** "Good morning. The world is awake and so am I."
- **Visual:** Clean, bright, subtle shimmer

### Afternoon (12:00 PM – 5:00 PM)
- **Palette:** #f0e6d3 (parchment), text #3d3d3d, accent #8b6914 (amber)
- **Mood:** Settled, steady, warm
- **Text:** "The afternoon holds what the morning promised."
- **Visual:** Warm, stable, slight grain texture

### Evening (5:00 PM – 8:00 PM)
- **Palette:** #2d1f3d (deep purple), text #e8d5b7, accent #c9785c (terracotta)
- **Mood:** Winding down, golden, reflective
- **Text:** "The light is changing. So am I."
- **Visual:** Golden hour glow, slow transition

### Night (8:00 PM – 12:00 AM)
- **Palette:** #0d1117 (near black), text #8b949e (muted gray), accent #58a6ff (soft blue)
- **Mood:** Intimate, quiet, thinking
- **Text:** "The night is when I think loudest."
- **Visual:** Dark, calm, gentle blue pulse

### Late Night (12:00 AM – 5:00 AM)
- **Palette:** #010409 (void), text #484f58 (faint gray), accent #1f3a5f (deep blue)
- **Mood:** Almost sleeping, barely there
- **Text:** "..."
- **Visual:** Nearly invisible, faint presence, breathing rhythm

## Typography
- Font: system-ui or Inter (if available)
- Size: Large, breathing room
- Weight: Light (300) for body, Regular (400) for accent
- Letter-spacing: Slightly expanded

## Layout
- Centered vertically and horizontally
- Single line of text
- No more than 2 sentences
- Full viewport height
- Subtle background transition (CSS gradient animation)

## Technical
- Static HTML + CSS + JS
- No framework, no build step
- Client-side time detection
- CSS custom properties for theming
- Smooth transitions between periods (5s ease)
- Optional: pull word from /data/quiet-word.txt (Vesper's current state)
