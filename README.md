# 🍅 The Big Comfy Tomato

A cozy Pomodoro focus timer where a tomato keeps the time and a small T-Rex tends the room.
One self-contained HTML file. No build step, no dependencies, no tracking. Just open it and focus.

> Twenty-five minutes on the couch of concentration, ten minutes of Clock Stretch.
> The tomato keeps time. You keep going.

## What it does

- **25 / 10 Pomodoro cycles** (fully adjustable in Settings) with focus and break phases.
- **A tomato that reacts to the countdown.** It stretches at the halfway mark, sweats a little
  in the last minute, and pulses like a heartbeat in the final ten seconds.
- **Stay-aware alerts.** A one-minute warning (toast, chime, and desktop notification if allowed),
  plus a full-screen edge glow in the final seconds so you catch it from the corner of your eye.
- **An end-of-phase dialog** that tells you, in the app's own voice, that it is time to switch off.
- **Real daily check-ins** on your actual clock (default 11:00, 1:30, 3:30), each editable.
- **Rotating quotes** from real people (Angelou, Picasso, van Gogh, Twain, and more).
- **Real nervous-system regulation tips** on breaks: physiological sigh, box breathing,
  5-4-3-2-1 grounding, extended exhale, vagal humming, and others, each with the why.
- **A resident T-Rex** who reads, waves, naps, and waters his little sprout, on a calm loop.
- **Light and dark themes**, sound toggle, and reduced-motion support.

## How to use it

Open `index.html` in any modern browser. That is the whole thing.

**Run it as a desktop app (no install needed):** in Chrome, open the page, then
`⋮` menu → Cast, save, and share → Create shortcut → check "Open as window." You get a
windowed app with its own icon that you can pin to the taskbar.

## Tech

- A single `index.html`: vanilla JavaScript, hand-authored SVG, and the WebAudio API for chimes.
- No frameworks, no bundler, no external requests. Works fully offline.
- Settings persist in `localStorage`. Check-ins run off the browser clock.

## Credits

Built by Tiffany Rexach with Claude Code. Concept is a love letter to *The Big Comfy Couch*,
reimagined with a tomato as the clock.

## License

MIT. See [LICENSE](LICENSE).
