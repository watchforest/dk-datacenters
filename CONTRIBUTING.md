# Contributing

Thank you for helping keep this dataset accurate and complete.

## How to contribute

[**Open an issue**](../../issues/new/choose) and choose the form that fits:

- **Submit a datacenter** — add a new facility or correct an existing entry in [`data/datacenters.csv`](data/datacenters.csv).
- **Submit a document** — share a public planning document such as a municipal application, local plan, or environmental assessment. These are archived in [`documents/`](documents/).
- **Submit a source** — suggest an article, report, database, or other resource to add to [`SOURCES.md`](SOURCES.md).

Fill in the form and submit. A maintainer will review it and add the information to the relevant file.

## Tips for datacenter submissions

- **Leave optional fields blank** if you don't know the value — don't guess.
- **Every submission must include a source URL** (e.g. datacentermap.com, the operator's own website, or a news article) so the information can be verified.
- **Boolean fields** (`iso27001`, `cctv`, etc.): use `Yes` or `No`. Leave blank if unknown.
- **Status values:** choose one of `Operational`, `Under Construction`, `Planned`, or `Decommissioned`.
- **If your market isn't in the dropdown**, select `Other` and specify it in the notes field.
- **Check for duplicates** before submitting — search the existing issues and `datacenters.csv` for the facility name.

## Tips for document submissions

- You can provide a URL, attach the file directly to the issue, or both.
- Dead links are fine to submit — record the original URL and attach the file if you have it.
- Documents do not need to relate to a named datacenter — planning documents for unnamed or early-stage projects are welcome.

## What not to submit

- Facilities or documents unrelated to Denmark.
- Entries you cannot back with a public source or a file.
- Personally identifiable information.
