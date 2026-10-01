# CK Dataset

This repository documents the CSV files distributed in `ck_original.zip`.

## Download

Download [ck_original.zip (v1.0.0)](https://github.com/zyfyz666/ck-dataset/releases/download/v1.0.0/ck_original.zip), or open the [Releases page](https://github.com/zyfyz666/ck-dataset/releases). The automatically generated GitHub source-code archives do not contain the dataset.

| Property | Value |
| --- | --- |
| Archive | `ck_original.zip` |
| Archive size | 440,653,384 bytes (420.24 MiB) |
| CSV files | 306 |
| Total uncompressed file size | 2,092,655,854 bytes (1.95 GiB) |
| Top-level archive directory | `ck_original/` |
| Release version | `v1.0.0` |

## File organization

All 306 file names follow the pattern `p<number>_f<number>_m<number>.csv`, for example:

```text
ck_original/
  p10_f33_m1.csv
  p10_f33_m2.csv
  p10_f33_m3.csv
  ...
```

The file names contain 31 distinct `p` values, 102 distinct `f` values, and `m` values of 1, 2, and 3. These are counts of file-name identifiers; their scientific meanings have not yet been documented.

The first three inspected lines of `p10_f33_m1.csv` contain five comma-separated numeric values and no header. The column meanings, units, sampling characteristics, collection methods, and intended applications still need to be documented by the dataset author. This observation is not a validation of every row in the archive.

See [manifest.json](manifest.json) for the complete file list and uncompressed file sizes.

## Verify the download

SHA-256 of `ck_original.zip`:

```text
68690ad381a488d58303b8f0d3029e475db5234001542d015e77590b665da463
```

On Windows PowerShell:

```powershell
Get-FileHash -LiteralPath .\ck_original.zip -Algorithm SHA256
```

On Linux:

```bash
sha256sum -c SHA256SUMS.txt
```

## License

The data license has not yet been specified. Public download availability alone does not grant a general license to reuse or redistribute the data.
