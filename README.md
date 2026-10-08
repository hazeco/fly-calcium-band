# Fly Brain — Calcium Imaging Toy

An interactive art toy by **hazeco**: click neurons, watch them glow like
calcium imaging, and hear every spike become a note.

**Play it:** https://fly-calcium-band.pages.dev

## What is this?

A single-file web toy that simulates a field of neurons under a microscope.
Neurons fire spontaneously, excite their synaptic neighbors, and glow green
as calcium floods in — then fade slowly as it clears, just like the real
indicator dyes (jGCaMP8f, GCaMP6f, GCaMP6s — switchable in the panel).

Every spike lands on the sixteenth-note grid and becomes a musical note,
locked into C minor pentatonic or D Dorian. Click any cell to make it fire.
Downbeats snap to the chord the brain just played; bass and pads follow along.

## Features

- 🪰 Click-to-stimulate neuron field with live synaptic propagation
- 🧠 Three calcium indicators with different decay speeds
- 🎹 Real-time WebAudio sonification (lead + bass + chords)
- 💾 Export your take as a 2-track MIDI file (up to 32 bars)
- 🌗 Dark/light mode, Fire/Green colormaps, adjustable tempo and coupling
- 📱 Works on mobile — everything runs 100% in the browser, no server,
  no tracking, no uploads

## Run it locally

Just open `index.html` in a browser. (Internet needed for Google Fonts.)

## Honest notes

All neural wiring is **synthetic** — this is an art toy, not real brain data.
Concept inspired by the FlyWire whole-brain connectome and whole-brain
calcium imaging in behaving *Drosophila* (Aimon et al., *PLOS Biology* 2019).

## Credits

- Typefaces via Google Fonts: Familjen Grotesk, Hanken Grotesk, JetBrains Mono
- Built with vanilla JS + WebAudio — no frameworks, no build step

## License

MIT © 2026 hazeco. Free to share and remix — see [LICENSE](LICENSE).
