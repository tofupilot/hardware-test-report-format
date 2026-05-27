# WATS samples (WSJF + WSXF)

WATS is Virinco's manufacturing-data system. It defines two interchange formats for the
same UUT/UUR test-report model: WSJF (JSON) and WSXF (XML).

- **`sample.wsjf.json`** — WATS Standard JSON Format. Top-level `sn`/`pn`/`result`/`start`
  with a `root.steps[]` tree carrying `numericMeas[]`.
- **`sample.wsxf.xml`** — WATS Standard XML Format. A `<Reports>` root in the
  `wats.virinco.com/schemas/WATS/Report/wsxf` namespace, with the same step/measurement tree.

Import guides:
- WSJF: https://www.tofupilot.com/docs/import/wsjf
- WSXF: https://www.tofupilot.com/docs/import/wsxf
