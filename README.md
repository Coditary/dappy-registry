# dappy-registry

Catalog for Dappy packages installable through [rqp-plugin-dappy](https://github.com/Coditary/rqp-plugin-dappy).

## Files

| Path | Purpose |
|------|---------|
| `packages.json` | Aggregated Dappy plugin catalog |
| `registry/<letter>/<id>.json` | Per-package metadata (ReqPack-style layout) |

## Usage

```bash
rqp install ./path/to/rqp-plugin-dappy
rqp install dappy python
rqp install dappy gdbserver
```

Sync content from the Coditary dev workspace `registry/dappy/` folder when publishing updates.
