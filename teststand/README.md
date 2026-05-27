# NI TestStand sample

The native NI TestStand XML report is a `PropertyObject` dump: a `<Reports>` root wraps
one or more `<Report>` elements, and the data is generic `<Prop>` nodes rather than named
test elements. The step tree lives under a `ResultList` array. (This is distinct from
ATML, which TestStand can also produce.)

- **`sample.teststand.xml`** — a UUT report with a `UUT` serial number and a `ResultList`
  of numeric-limit step results.

Import guide: https://www.tofupilot.com/docs/import/teststand
