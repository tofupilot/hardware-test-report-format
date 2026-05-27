# OpenHTF sample

OpenHTF (Open Hardware Testing Framework) is Google's open-source Python test framework.
Its JSON output is the in-memory `TestRecord` serialized by the `OutputToJSON` callback.

- **`sample.openhtf.json`** — a complete record: top-level `dut_id`, `start_time_millis`,
  `outcome`, and a `phases[]` array with measurements and limits.

Import guide: https://www.tofupilot.com/docs/import/openhtf
