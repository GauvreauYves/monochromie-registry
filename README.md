# Colorimetric Baseline Registry — Yves Gauvreau

Open registry of measurements for fine-art photographic editions where each copy carries a physical reference target. The intent is longitudinal: holding institutions or researchers remeasure their copies' targets over time, contributing data here. Over years and decades, the accumulated record makes print stability under real storage conditions empirically observable.

## Books

- [`Monochromie_la_serie/`](Monochromie_la_serie/) — five-copy edition, 2026

(Other books will be added as separate folders as they are produced.)

## Repository structure

```
README.md             — this file
LICENSE               — terms of use (CC0 1.0 Universal)
<book_slug>/          — one folder per book
  README.md           — book-level description, copy holdings, measurement history
  Copy_registry/      — per-copy metadata files (added when copies are placed)
  Measurements/       — measurement files in CGATS format, plus a README
```

## Hosting and persistence

- **Primary:** github.com/GauvreauYves/monochromie-registry
- **Mirror:** codeberg.org/GauvreauYves/monochromie-registry
- **Long-term archive:** Software Heritage Archive automatically mirrors public GitHub repositories on a regular schedule.

If GitHub becomes inaccessible, the Codeberg mirror or any clone of the repository contains the full history. Software Heritage provides persistent identifiers (SWHIDs) for any commit, independent of which host is currently authoritative.

## Maintainership

The original author and current maintainer is Yves Gauvreau. The project is designed to outlive its author. Whichever institution accumulates the most contributed measurements over time becomes the project's de facto maintainer ("parrain"). Succession happens through activity, not appointment.

If you are an institution holding a copy and you wish to take a more active role — coordinating measurement campaigns, hosting the canonical fork, etc. — please open an issue or submit a pull request stating your intent.

## License

Data in this registry is dedicated to the public domain under CC0 1.0 Universal. See `LICENSE` for the full text.

The original photographs in any referenced book are subject to copyright held by their author and are not part of this registry. Only the measurement data, holdings records, and registry documentation are CC0.
