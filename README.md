# Hardware test report format samples

Sample hardware test report files in every major format used in electronics and
semiconductor manufacturing: OpenHTF, WATS (WSJF/WSXF), ATML, NI TestStand, STDF, and
ATDF. Each file is a small, valid, original example you can download to inspect the
format or import into [TofuPilot](https://www.tofupilot.com).

> Suggested GitHub repo description: `Sample hardware test report files — OpenHTF, WATS (WSJF/WSXF), ATML, NI TestStand, STDF, ATDF. Free downloads + import guides.`

## Formats

| Format | Folder | File | Guide |
|--------|--------|------|-------|
| OpenHTF | [`openhtf/`](./openhtf) | `sample.openhtf.json` | [OpenHTF](https://www.tofupilot.com/docs/import/openhtf) |
| WATS WSJF | [`wats/`](./wats) | `sample.wsjf.json` | [WSJF](https://www.tofupilot.com/docs/import/wsjf) |
| WATS WSXF | [`wats/`](./wats) | `sample.wsxf.xml` | [WSXF](https://www.tofupilot.com/docs/import/wsxf) |
| ATML | [`atml/`](./atml) | `sample.atml-2.02.xml`, `sample.atml-5.00.xml`, `sample.atml-6.01.xml` | [ATML](https://www.tofupilot.com/docs/import/atml) |
| NI TestStand | [`teststand/`](./teststand) | `sample.teststand.xml` | [TestStand](https://www.tofupilot.com/docs/import/teststand) |
| STDF / ATDF | [`stdf/`](./stdf) | `sample.stdf`, `sample.atdf` | [STDF](https://www.tofupilot.com/docs/import/stdf), [ATDF](https://www.tofupilot.com/docs/import/atdf) |

## About these files

Every file is original, hand-authored to match each format's structure and schema, and
describes the same simple test: one board (`TP-DEMO-1`, serial `SN-0001`) with two
passing measurements (a supply voltage and a TX power). They are intentionally minimal
so the format is easy to read.

Full per-format documentation, including history and field-by-field structure, lives in
the [TofuPilot import guides](https://www.tofupilot.com/docs/import).

## License

These sample files are released under the MIT License. See [`LICENSE`](./LICENSE).
