# Eye Diagram Lab

An interactive animation that shows how an eye diagram is built in digital communication.

**Open it here:** https://abdullah-alahmadi.github.io/eye-diagram-lab/

The received baseband waveform scrolls across the top screen. Each 2T slice, centred on a sampling instant, is then drawn on top of the earlier slices in the eye diagram below, so students can see the eye build up one slice at a time.

## What you can change

- Modulation: binary (2-PAM) or 4-PAM
- Pulse shape: raised cosine (with roll-off factor α) or rectangular NRZ
- Channel bandwidth (inter-symbol interference)
- Additive noise σ (with the matching SNR)
- Timing jitter
- Receiver sampling instant
- Animation speed, step one symbol, clear the eye
- Preset scenarios: Clean, Noisy, Band-limited (ISI), Jitter, Closed eye

The eye shows live measurements: eye height, eye width, the spread of the crossings, and the number of decision errors. The page also has notes on reading an eye diagram and five exercises for students.

## Running it locally

It is one self-contained HTML file with no build step. Open `index.html` in a browser.
