# VeriVox SIH 2026

Tech Titans' prototype for SIH26104, AI-powered real-time detection and prevention of voice-cloning impersonation attacks.

## Files

- `verivox_prototype.html` is the complete, self-contained site and interactive browser demo.
- `verivox-preview.png` is the 1200 x 630 social preview image used by the live site.

No build tools or third-party libraries are required. Open the HTML file in a modern browser. Microphone access requires HTTPS or localhost; audio file analysis runs in the browser.

## Important limitation

The demo includes a compact trained audio-spoof baseline. It reports 73.1% balanced accuracy and a 39.1% false-positive rate on genuine clips in a sampled, held-out set of 2,000 ASVspoof 2019 clips. Treat this as a prototype benchmark, not real-world or Indian-language validation. Speaker matching, prosody, and transaction context remain heuristic; no output establishes identity or proves fraud.

Live demo: <https://verivox-demo.pages.bu.app/>
