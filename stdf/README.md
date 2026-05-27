# STDF + ATDF samples

STDF (Standard Test Data Format) is the de-facto binary datalog format for semiconductor
ATE. ATDF is its human-readable ASCII twin: the same records, as text. Both carry the
same record set (FAR, MIR, PIR/PRR, PTR, MRR).

- **`sample.stdf`** — a valid binary STDF V4 file (little-endian, CPU type 2).
- **`sample.atdf`** — the same lot in ASCII: `FAR:A|...` first line, then
  `REC_TYPE:field|field|...` per record.

Both describe one part (`SN-0001`, `TP-DEMO-1`) with two passing parametric tests.

Import guides:
- STDF: https://www.tofupilot.com/docs/import/stdf
- ATDF: https://www.tofupilot.com/docs/import/atdf
