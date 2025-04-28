# image ingestion pipeline examples

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="pictures/ingest-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="pictures/ingest-light.png">
  <img alt="Cross-domain image promotion" src="pictures/ingest-light.png">
</picture>

Two paths are shown here, more as a demo than anything else.

1. [`ingest.sh`](ingest.sh) is a simple shell script that runs as acceptance criteria checks to pull from one source (Chainguard registry), run the checks above, then push to another (any OCI compliant registry)
2. [`.github/workflows/ingest.yaml`](.github/workflows/ingest.yaml) is the same workflow and checks, but run within GitHub Actions to show a demo of it working in a CI pipeline.
