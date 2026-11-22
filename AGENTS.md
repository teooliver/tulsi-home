# Tulsi — Home Repo

Home for agent work on Tulsi, a task-management app (Rust API, React client,
homelab deployment, observability stack). Run the agent from here. Each repo
below is its own git repo: commit inside that repo, not here.

## Shared docs

- `GLOSSARY.md`: Tulsi's domain language. Use its terms in code, docs and
  replies in every repo, and avoid the synonyms it lists.

## Other Repos

Paths are relative to this repo; the repos sit beside it in the parent `tulsi` folder.

- tulsi-rust-backend (Rust/Axum/Postgres API): `../backend/tulsi-rust-backend`.
  Clone from https://github.com/teooliver/tulsi-backend-rust.git if missing.
  Read its AGENTS.md first.
- tulsi-web (TanStack Start React client for the API): `../clients/tulsi-web`.
  Clone from https://github.com/teooliver/tulsi-web-client.git if missing.
  Read its AGENTS.md first. Regenerating its API client needs the backend on :8080.
- homelab-k3s (K3s manifests deploying Tulsi to a Raspberry Pi): `../homelab-k3s`.
  Clone from git@github.com:teooliver/homelab-k3s.git if missing (private repo).
- observability (Docker Compose Grafana/Prometheus/Tempo/Loki stack for the
  backend): `../observability`. Clone from https://github.com/teooliver/tulsi-grafana.git if missing.
