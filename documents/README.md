# Documents

An archive of public documents related to datacenter planning in Denmark — municipal applications, local plans, environmental assessments, and similar records.

## Index

All documents are indexed in [`documents.csv`](documents.csv) with the following columns:

| Column | Description |
|---|---|
| `title` | Document title, e.g. `Datacenter ved Stovstrup - anmodning om plangrundlag` |
| `datacenter_name` | Optional — matches an entry in `data/datacenters.csv` if the project is known |
| `company` | Optional — company behind the datacenter project |
| `municipality` | Municipality that issued or received the document |
| `document_type` | Type of document — e.g. `plangrundlag`, `lokalplan`, `VVM`, `miljøvurdering`, `tilladelse` |
| `date` | Publication date (`YYYY-MM-DD`, `YYYY-MM`, or `YYYY`) |
| `original_url` | Original URL — may be a dead link |
| `local_file` | Path to a file stored in this repository, relative to the repo root |
| `notes` | Anything else relevant |

## Contributing

To submit a document, [open an issue](../../issues/new/choose) and select **Submit a document**. You can provide a link, attach a file you have locally, or both.
