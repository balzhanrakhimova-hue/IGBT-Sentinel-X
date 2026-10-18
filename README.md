# IGBT Sentinel X — TwinPulse Fingerprint Lab

Interactive offline/browser software proof of concept for the NU–Wabtec Hackathon 2026.

## Open the demo

Open [index.html](index.html) directly, or activate GitHub Pages under **Settings → Pages → Deploy from a branch → main → /(root)**. The website will then appear at `https://YOUR_USERNAME.github.io/IGBT-Sentinel-X/` (subject to your repository name and GitHub Pages settings).

## Demo walkthrough

1. Select **Healthy reference** and **Adaptive**, then click **Start diagnosis**.
2. Choose **Collector leakage** and repeat to see the fault triage.
3. Try **Thermal drift (subtle)** with Adaptive screening.
4. Choose **High uncertainty** to demonstrate **RETEST**.
5. Export JSON or CSV, or print to PDF.

## Files

- `index.html` — standalone frontend; no server or installation needed.
- `docs/Sentinel_X_Pitch_Deck.pptx` — jury pitch.
- `docs/Technical_Proposal.pdf` — technical proposal.
- `docs/Budget_Estimate.csv` — illustrative budget.
- `docs/Sentinel_X_Guide_RU.md` — Russian guide.

## Important limitation

**Simulation only.** All measurements, fault signatures, limits, scores and timing are synthetic, not collected from Wabtec hardware. No IGBT is controlled or electrically tested. The prototype is **not** an approved acceptance test or basis for installation. Actual testing requires manufacturer specifications, validated instrumentation and professional safety controls.
