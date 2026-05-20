![Stardelt](https://docs.stardelt.io/img/logo.svg)

# Stardelt

**The open-source data platform you actually own.**

Lakehouse · Batch ETL · Streaming · ML/AI on any Kubernetes cluster — permissive OSI licenses only, zero phone-home.

---

## Where to start

| Resource | Description |
|---|---|
| [stardelt-docs](https://docs.stardelt.io) | Architecture, roadmap, and design spec |
| [stardelt-www](https://stardelt.io) | Marketing site |

---

## The codebase

| Repo | Description |
|---|---|
| [stardelt-www](https://github.com/stardelt/stardelt-www) | Marketing site (stardelt.io) |
| [stardelt-docs](https://github.com/stardelt/stardelt-docs) | Documentation site (docs.stardelt.io) |
| [stardelt-nova](https://github.com/stardelt/stardelt-nova) | Unified UI and API gateway — the control-plane front door |
| [stardelt-operator](https://github.com/stardelt/stardelt-operator) | Kubernetes operator reconciling Stardelt CRDs (Phase 1+) |
| [stardelt-platform](https://github.com/stardelt/stardelt-platform) | Production-shape Helm values, manifests, and install scripts |
| [stardelt-demos](https://github.com/stardelt/stardelt-demos) | kind/k3s laptop demos and sample workloads |

---

## Status

**Phase 0** — design complete. The MVP lakehouse slice (Trino + Lakekeeper + Iceberg + SeaweedFS + Airflow + Superset + Nova) runs end-to-end on kind. The Kubernetes operator (Phase 1, Stage 4) is the next milestone.

---

## Get involved

- Open an issue in the relevant repo
- Read the architecture and design spec at [docs.stardelt.io](https://docs.stardelt.io)
- Star the repos you want to follow

---

## License

Apache 2.0. All distributed upstream components carry permissive OSI licenses — see [stardelt-docs](https://docs.stardelt.io) for the full license matrix.

---

<sub>*Stardelt is a community project, not affiliated with any vendor or foundation.*</sub>
