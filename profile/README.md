<img src="logo-wordmark.svg" alt="stardelt" height="64" />

# stardelt

**The open-source data platform you actually own.**

SQL over Iceberg tables, notebooks, schedules and dashboards with one sign-in, on any Kubernetes cluster. Permissive licenses only, no phone-home, no license server.


If you like our work [⭐ star this repository](https://github.com/stardelt/stardelt) 
---

## Where to start

| | |
|---|---|
| [Quickstart](https://stardelt.io/docs/getting-started/quickstart) | Install the core, load a file, query it |
| [How it works](https://stardelt.io/docs/architecture/how-it-works) | One picture of the platform |
| [Roadmap](https://stardelt.io/docs/roadmap) | What works today and what comes next |
| [Contribute](https://stardelt.io/docs/developer) | Repositories, checks and good first steps |

---

## The repositories

| Repository | What it is |
|---|---|
| [⭐ stardelt](https://github.com/stardelt/stardelt) | Start here: releases, the install manifest, questions and reports |
| [stardelt-platform](https://github.com/stardelt/stardelt-platform) | Helm values, manifests and the one-command install |
| [stardelt-nova](https://github.com/stardelt/stardelt-nova) | The interface and API: catalog, SQL editor, pipelines, query log, lineage |
| [stardelt-operator](https://github.com/stardelt/stardelt-operator) | The Kubernetes operator and its resources |
| [stardelt-python](https://github.com/stardelt/stardelt-python) | The Python package, command line and MCP server |
| [stardelt-demos](https://github.com/stardelt/stardelt-demos) | Sample pipelines and the Airflow image |
| [stardelt-docs](https://github.com/stardelt/stardelt-docs) | The documentation at [stardelt.io](https://stardelt.io) |

---

## Status

stardelt runs end to end: object storage, the Iceberg catalog, Trino, sign-in with table permissions by group, notebooks, scheduled pipelines and dashboards, installed with one command. There is no tagged release yet, so APIs and resources can still change. See the [roadmap](https://stardelt.io/docs/roadmap).

---

## Get involved

- Try the [Quickstart](https://stardelt.io/docs/getting-started/quickstart) and tell us what went wrong
- Open an issue in the repository it concerns
- Read [how to contribute](https://stardelt.io/docs/developer)

---

## License

Apache 2.0. Every component stardelt installs carries a permissive OSI license, with one documented exception: see the [license policy](https://stardelt.io/docs/architecture/licenses).

---

<sub>*stardelt is a community project, not affiliated with any vendor or foundation.*</sub>
