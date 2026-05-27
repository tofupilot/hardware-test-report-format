# ATML samples

ATML (Automatic Test Markup Language) is an IEEE 1671 family of XML schemas for exchanging
ATE test results. TofuPilot imports the `TestResults` schema. The root element and
namespace differ by version, so there is one sample per supported version.

- **`sample.atml-2.02.xml`** — ATML 2.02. Root `tr:TestResults`, namespace
  `http://www.ieee.org/ATML/2007/TestResults`.
- **`sample.atml-5.00.xml`** — ATML 5.00. Root `trc:TestResultsCollection`, namespace
  `urn:IEEE-1636.1:2011:01:*`.
- **`sample.atml-6.01.xml`** — ATML 6.01. Root `trc:TestResultsCollection`, namespace
  `urn:IEEE-1636.1:2013:*`.

Each holds a `UUT` serial number and a `TestGroup` of `Test` elements with values and
`TestLimit` bounds.

Import guide: https://www.tofupilot.com/docs/import/atml
