# sparkinfer-log

Immutable, public **evaluation log** for [sparkinfer](https://github.com/gittensor-ai-lab/sparkinfer) (SN74).

Every PR evaluation's raw `log.txt` + `result.json` (+ `receipt.json` / `attestation.json` when
Polaris TDX attested) is committed here — one directory per run under
[`runs/`](runs) — and rendered at a **unique URL** by the GitHub Pages viewer:

- **Index:** https://gittensor-ai-lab.github.io/sparkinfer-log/
- **Per run:** `https://gittensor-ai-lab.github.io/sparkinfer-log/?run=<id>`

The page is only a *view* — the committed files are the record, and git history is the timestamp.
Reproduce any result from source: see
**[EVAL-TRUST.md](https://github.com/gittensor-ai-lab/sparkinfer/blob/main/EVAL-TRUST.md)**.

Written by the eval bot after each run.
