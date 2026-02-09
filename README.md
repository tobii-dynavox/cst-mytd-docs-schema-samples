# cst-mytd-docs-schema-samples

This repository contains sample documentation files for the MyTD project, including a root directory file and fictional product entries. Use it to validate JSON schemas, test enum values for document kinds, and explore optional grouping/tags with shuffled data for public sharing.

Schema rule note for product document links:
- PDF-only is allowed per language (a language entry may include only `pdf`).
- Null links are not allowed (`html` and `pdf`, when present, must be non-null `https://` URIs).
