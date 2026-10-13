# CONTINUUM OBSIDIAN POLY

## Cream Instrument · Alpha 04

**An experimental, standalone, eight-voice polyphonic synthesiser built with Web Audio.**

Continuum Obsidian Poly is an expressive, browser-based instrument inspired by the tactile control philosophy of classic analogue polysynthesisers. Its distinctive cream-coloured faceplate, dark rotary knobs, restrained typography and wood-inspired enclosure are designed to make the instrument feel like dedicated hardware rather than a conventional software interface.

Obsidian Poly is part of the wider Continuum instrument family, but has its own visual and synthesis identity.

> **Status:** Alpha 04. An experimental prototype; some features are incomplete or browser-dependent. Begin at a low listening volume.

## Synthesis architecture

The current instrument includes:

- **Eight-voice polyphony**
- Two oscillators with selectable waveforms, octave and tuning controls
- Sub-oscillator and noise source
- Resonant multimode filter with selectable 2-pole / 4-pole configuration
- Dedicated filter and amplifier ADSR envelopes
- LFO with selectable waveform and modulation destination
- Stereo spread, chorus, delay and reverb
- Unison, hold and a basic arpeggiator
- Factory starting patches and JSON patch import/export

These are **Web Audio implementations** of synthesis concepts, not recreations of proprietary analogue circuitry.

## Performance interface

- 61-note on-screen keyboard with mouse/touch interaction
- Computer-keyboard note input
- Web MIDI input where supported by the browser
- XY expression surface with an additional pressure-style control
- Touch-sensitive ribbon-style control
- Pitch and modulation controls
- Assignable live modulation routes

The on-screen expressive controls are software interfaces. They do **not** reproduce the physical sensing capabilities of an MPE hardware keybed. Full per-note MPE, bi-timbral split/stack and parameter-level A/B morphing are **not yet implemented**.

## Design language

Obsidian Poly Alpha 04 establishes a cream-coloured, hardware-inspired visual identity:

- Warm cream faceplate and wood-inspired detailing
- Black control labels and thin black section outlines
- Black rotary knobs with white position indicators
- Small, consistent, squared **CONTINUUM OBSIDIAN** typography
- Dense, logically grouped synthesis controls
- No inherited blue Continuum Mosaic panel styling

This visual identity is a **design checkpoint** for subsequent Obsidian development.

## Getting started

1. Download `Continuum_Obsidian_Poly_Alpha_04_Cream_Instrument.html`.
2. Open it in a modern desktop or mobile browser with Web Audio support.
3. Select **START AUDIO** (or the equivalent audio-enable control on the instrument).
4. Play the on-screen keyboard or use a connected MIDI controller where supported.
5. Adjust oscillators, filters, envelopes, modulation and effects.
6. Use the patch controls to explore presets or export your settings.

Most browsers require a user gesture before audio playback begins. Web MIDI availability varies by browser, device and permissions.

## Current development limitations

Alpha 04 is primarily a front-end design milestone built around an existing synthesis engine. Some controls and synthesis behaviours remain experimental or incomplete. In particular, this build should not be described as a complete emulation of either the Arturia PolyBrute 12 or Sequential Prophet Rev2.

The HTML's JavaScript has undergone syntax checking, but comprehensive cross-browser and audio-behaviour testing has not yet been completed.

## Relationship to Continuum Mosaic

**Continuum Mosaic** is the broader modular research and integration environment. **Obsidian Poly** is a standalone instrument with its own hardware-inspired front panel. The long-term vision is for distinct Continuum instruments to be brought together in a connected virtual synthesis rack or signal chain.

## Creative direction and development

**Concept, architecture and creative direction:** Stefano Pollina.

Developed through iterative human–AI collaboration as part of the Continuum family of creative synthesis environments.

## Licence

**Licence decision pending.** Until a licence is published, public availability does not automatically grant permission to modify or redistribute the code.

Copyright © 2026 Stefano Pollina. All rights reserved unless and until a licence states otherwise.

---

*Continuum Obsidian Poly — a synthesiser pretending to be a website.*
