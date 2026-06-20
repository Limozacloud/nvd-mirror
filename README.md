# nvd-mirror

NVD CVE JSON mirror, updated every 4 hours.

## Structure

```
data/
└── CVE-{year}/
    └── CVE-{year}-{bucket}xx/
        └── CVE-{year}-{id}.json
_state.csv   — cve, sha256, imported_at, updated_at
```

## Usage

Clone and use `_state.csv` to track changes incrementally.

```bash
git clone --depth=1 https://github.com/Limozacloud/nvd-mirror
```
