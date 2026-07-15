# 🍅 The Big Comfy Tomato

A cozy Pomodoro focus timer where a tomato keeps the time and a small T-Rex tends the room.
One self-contained HTML file. No build step, no dependencies, no tracking. Just open it and focus.

**You set your own intervals.** It opens on a classic 25 minutes of focus and 10 of break, but
those are just defaults. Change the focus length, the break length, and your daily check-in times
to whatever fits your day, right in Settings.

> A focus stretch on the couch of concentration, then a Clock Stretch to rest,
> at whatever lengths fit your day. The tomato keeps time. You keep going.

## What it does

- **Focus and break cycles on your own intervals.** Starts at 25 on / 10 off, but you set both
  (and the daily check-in times) to whatever suits you in Settings.
- **A tomato with a personality arc.** It cycles through ten distinct emotions during a focus
  block (determined, curious, gritted, proud, and more, eyebrows included), stretches at the
  halfway mark, sweats in the last minute, and pulses like a heartbeat in the final ten seconds.
- **Tiered wind-down alarms.** Real screen-taking dialogs, not corner toasts: a motivational
  checkpoint at halfway, a pressing "find a stopping point" at five minutes, and a high alert at
  one minute with a flashing backdrop, ringing shake, and urgent tone. Breaks get a gentler
  one-minute "drift back" version. Tiers auto-skip on short custom blocks so they never stack.
- **Alerts that reach outside the app.** Desktop notifications, a full-screen edge glow in the
  final seconds, and a flashing window title and icon ("WIND DOWN" / "TIME'S UP") that keeps
  blinking in your taskbar until you come back, for when you're working in another window.
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
