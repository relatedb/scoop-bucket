# relatedb/scoop-bucket

Scoop bucket for [Relate](https://relatedb.ai/) — the embedded openCypher
graph database in a single binary.

```powershell
scoop bucket add relate https://github.com/relatedb/scoop-bucket
scoop install relate
```

The `bucket/relate.json` manifest is generated from each release's signed
asset manifest ([ADR-0659](https://github.com/relatedb/relate/blob/main/docs/adr/0659-package-manager-distribution-channels.md))
and pushed by the release workflow. Don't edit it by hand; a release
overwrite is authoritative.

Upgrade with `scoop update relate` — a Scoop install is package-managed,
and `relate upgrade` defers to the package manager.
