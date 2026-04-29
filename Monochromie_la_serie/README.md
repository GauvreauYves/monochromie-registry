# Monochromie, la série

Five-copy fine-art photography edition by Yves Gauvreau (Sainte-Adèle, Québec, 2026), comprising three black-and-white photographic series, a technical document on production conditions, and the colorimetric baseline contribution that makes this registry possible.

A target of 52 neutral patches (R = G = B values from 0 to 255 in steps of 5) is bound into each copy, immediately following the *Fine Art Inkjet Practice* technical section. Day 0 measurements were taken at the time of production with an X-Rite i1Pro 2 spectrophotometer (M0, M1, M2 modes; D50 illuminant; 2° observer). Future researchers, conservators, or holding institutions are invited to remeasure the targets over time and contribute their data here.

Status: edition not yet printed. This folder will be populated with per-copy holdings and Day 0 measurement files at the time of production.

## Folder structure

```
README.md           — this file
Copy_registry/      — one file per copy, added when each copy is placed (ISBN,
                      current holder, acquisition date, prior holders, notes)
Measurements/       — CGATS measurement files, with a README explaining the
                      file format and naming convention
```

## Measurement file naming

`copyNN_MX_YYYY-MM.txt` where:

- `NN` — copy number (01–05)
- `X` — measurement mode (`0` = M0 / UV-included, `1` = M1, `2` = M2)
- `YYYY-MM` — year and month of measurement; omit for Day 0

Examples:

- `copy01_M0.txt` — Day 0 baseline of copy 01 in M0
- `copy01_M1_2046-04.txt` — copy 01 remeasured in M1 in April 2046

## Contribution protocol

If you hold a copy and want to contribute a re-measurement:

1. Open the book carefully (handling instructions are inside the clamshell lid). The reference target is bound at the end of the technical section.
2. Measure the 52 patches with a calibrated spectrophotometer. M0 is the canonical mode for this registry. M1 and M2 are also welcome.
3. Save the measurement as a CGATS-format `.txt` file using the naming convention above.
4. Update your copy's file in `Copy_registry/` to reflect the new measurement date and measurer.
5. Submit a pull request, or contact the current maintainer.

If you are not familiar with git: email the file to whoever last contributed (visible in the file's commit history) and they will commit on your behalf.

## References

- *Monochromie, la série* — printed edition, 5 copies, 2026 (ISBN to be assigned)
- *Fine Art Inkjet Practice* — technical document detailing production conditions, included as the technical section of the volume
- Legal deposit: Bibliothèque et Archives nationales du Québec (BAnQ), 2026
- Wilhelm Imaging Research, *Epson SureColor P700 and P900 — Print Permanence Ratings*, 2023
