<img src="logo-wordmark.svg" alt="stardelt" height="64" />

# stardelt

**The open-source data platform you actually own.**

Lakehouse · Batch ETL · Streaming · ML/AI on any Kubernetes cluster — permissive OSI licenses only, zero phone-home.

> ⚠️ **Pre-alpha.** stardelt is in an MVP / vibecoding phase — moving fast, iterating in the open, and breaking things on purpose. Expect rough edges, hard-coded defaults, and APIs that will change without notice. Not ready for any kind of production use.

---

## Where to start

| Resource | Description |
|---|---|
| [stardelt-docs](https://stardelt.io) | Architecture, roadmap, and design spec |

---

## The codebase

| Repo | Description |
|---|---|
| [stardelt-docs](https://github.com/stardelt/stardelt-docs) | Documentation site (stardelt.io) |
| [stardelt-nova](https://github.com/stardelt/stardelt-nova) | Unified UI and API gateway — the control-plane front door |
| [stardelt-operator](https://github.com/stardelt/stardelt-operator) | Kubernetes operator reconciling stardelt CRDs (Phase 1+) |
| [stardelt-platform](https://github.com/stardelt/stardelt-platform) | Production-shape Helm values, manifests, and install scripts |
| [stardelt-demos](https://github.com/stardelt/stardelt-demos) | kind/k3s laptop demos and sample workloads |

---

## Status

**Pre-alpha · MVP / vibecoding phase.** The lakehouse slice (SeaweedFS + CloudNative-PG + Lakekeeper + Trino + Nova, with JupyterHub) runs end-to-end on a single-node k3s dev cluster (Hetzner) and on kind. The Kubernetes operator already reconciles `Tenant`, `PlatformInstance` and `Lakehouse` resources (dry-run by default); making it the platform's baseline install is the current milestone. Development is fast and unstable — pin your own versions if you experiment with it.

---

## Get involved

- Open an issue in the relevant repo
- Read the architecture and design spec at [stardelt.io](https://stardelt.io)
- Star the repos you want to follow

---

## License

Apache 2.0. All distributed upstream components carry permissive OSI licenses — see [stardelt-docs](https://stardelt.io) for the full license matrix.

---

<sub>*stardelt is a community project, not affiliated with any vendor or foundation.*</sub>
