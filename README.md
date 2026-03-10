# 🍄 Shroomulator 🍄

**Magic Mushroom dosage calculator.**

→ **[shroomulator.app](https://headpot.github.io/Mushroom-Dosage-Calculator/)**

---

## Why this exists

Most psilocybin calculators out there are either too vague, ignore potency differences between species entirely, or are clearly just copied from each other. This started as a personal frustration and turned into a proper project — a funnel for random bursts of research and inspiration, built iteratively with AI as a thinking partner.

The strain data is sourced from peer-reviewed HPLC/HPTLC assays, competition lab results, and curated community data — not vibes.

---

## Formula

```
dose = (base × weight / 70) / potency × lemonTek
```

Adapted from established harm-reduction dosage tables (Erowid, PsychonautWiki) and scaled by potency multipliers from published HPLC/HPTLC assay data. The 70 kg reference body weight is standard in pharmacological dosing literature.

---

## Harm reduction

This calculator gives a ballpark, not a prescription. Real potency shifts with the strain, the batch, how you dried it, what you've eaten, your tolerance, and your headspace — none of which a formula can know.

**Always start lower than the number shown**, especially with anything you haven't tried before.

Psilocybin is a controlled substance in most jurisdictions. Know your local laws.

---

## Technical

Single self-contained HTML file. No frameworks, no build step, no external JS dependencies beyond:
- **Google Fonts** (Orbitron) — typography
- **ipapi.co** — country detection for kg/lb auto-toggle
- **GoatCounter** — anonymous, privacy-respecting visit counter (no cookies, no fingerprinting, GDPR compliant). Stats are private and visible only to the author.


---

## License

Copyright (c) 2025 headpot. All rights reserved. See [LICENSE](LICENSE).
