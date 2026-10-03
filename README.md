# VeriVox SIH 2026

Tech Titans' prototype for SIH26104, AI-powered real-time detection and prevention of voice-cloning impersonation attacks.

## Files

- `verivox_prototype.html` is the complete, self-contained site and interactive browser demo.
- `verivox-preview.png` is the 1200 x 630 social preview image used by the live site.

No build tools or third-party libraries are required. Open the HTML file in a modern browser. Microphone access requires HTTPS or localhost; audio file analysis runs in the browser.

## Important limitation

The demo uses heuristic audio features. It does not include trained AASIST, RawNet2, or ECAPA-TDNN models, and its risk score is illustrative rather than a validated deepfake or speaker-identity result.

Live demo: <https://verivox-demo.pages.bu.app/>
