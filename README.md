# Dark Ecology Dataset

This repository provides metadata and schemas for the **Dark Ecology Dataset**, which contains radar-based ecological observations. The data itself is hosted on [Zenodo](#) and must be downloaded separately.

## Dataset Structure

The dataset consists of the following directories:

- **profiles/** – Yearly profile data
- **scan/** – Scan-level data (`scan.tar.bz2`)
- **5min/** – 5-minute aggregated data (`5min.tar.bz2`)
- **daily/** – Daily aggregated data (`daily.tar.bz2`)
- **meta/** – Metadata files (e.g., station information)

Each dataset follows a defined schema, available in:
- `schemas/profile.schema.json`
- `schemas/scan.schema.json`
- `schemas/5min.schema.json`
- `schemas/daily.schema.json`

## Usage

1. Download the necessary `.tar.bz2` files from [Zenodo](#).
2. Extract them into a common root directory.
3. Use the provided schemas for validation.

## License

The dataset is released under **CC-BY 4.0**. See [`LICENSE`](LICENSE) for details.
