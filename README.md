# 🍄 Shroomulator 🍄

**Magic Mushroom dosage calculator.**

→ **[shroomulator.app](https://headpot.github.io/Mushroom-Dosage-Calculator/)**

---

## Why this exists


Passion project. Wanted to make something I actually liked — something that felt considered, looked good, and didn't cut corners on the data. Built it in random bursts whenever the inspiration hit, using AI as a sounding board to research strains, chase down lab papers, and work through the design decisions.
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
- **ipapi.co** — country detection for kg/lb auto-toggle
- **GoatCounter** — anonymous, privacy-respecting visit counter (no cookies, no fingerprinting, GDPR compliant). Stats are private and visible only to the author.


---

## License

Licensed under the **MIT License with Commons Clause**.

- Personal, non-commercial use is allowed (download, run locally/offline, modify for yourself).
- Commercial use, selling, monetizing, or profiting from the software (or derivatives) is prohibited.
- See full details in [LICENSE](./LICENSE).

For the best experience → **[shroomulator.app](https://headpot.github.io/Mushroom-Dosage-Calculator/)**
