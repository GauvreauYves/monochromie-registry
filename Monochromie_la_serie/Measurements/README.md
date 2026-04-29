# Measurements

Measurement files for *Monochromie, la série*.

## Format

X-Rite standard CGATS.17 format (as supported by i1Profiler / i1Pro 2 spectrophotometers, 2025 specification). Saved with `.txt` extension because that is what most spectrophotometric software (i1Profiler, ArgyllCMS, ColorThink, BabelColor) expects on read.

CGATS files are self-describing: header fields specify originator, instrumentation, illuminant, observer, measurement mode (M0 / M1 / M2), date, and the column layout of the data block. See any X-Rite i1Profiler-exported file as a structural reference, or the technical section of the printed volume for a worked example.

## Naming convention

`copyNN_MX[_YYYY-MM].txt`

- `NN` — copy number (01–05)
- `X` — measurement mode (`0` = M0 / UV-included, `1` = M1, `2` = M2)
- `YYYY-MM` — year and month of measurement; omit for Day 0

Examples:

- `copy01_M0.txt` — Day 0 baseline of copy 01 in M0
- `copy01_M1_2046-04.txt` — copy 01 remeasured in M1 in April 2046

Day 0 files (no date suffix) are immutable once published. Subsequent measurements are appended as new files; old files are not overwritten.

## Target

Each copy contains a printed target of 52 neutral patches with R = G = B values of 0, 5, 10, ..., 255. The target is bound into the book at the end of the *Fine Art Inkjet Practice* technical section. Patch order in the printed target is documented in that section.
