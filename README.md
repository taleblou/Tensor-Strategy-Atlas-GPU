# Tensor Strategy Atlas — GPU Atlas

Open-source reference implementations for studying workload-aware tensor strategies on **GPU Atlas** with Mojo.

This repository is one backend of the independent **Tensor Strategy Atlas** research project. It is not part of Momijo and is not an official Modular repository.

## Purpose

The repository stores tensor implementation candidates, provenance, correctness status and benchmark readiness. Direct performance comparisons are only valid when implementations share the same semantic workload contract.

## Repository layout

`architectures/<family>/<architecture_id>/` — architecture source folders  
`manifests/ARCHITECTURE_INVENTORY.csv` — authoritative inventory  
`docs/TAXONOMY.md` — family definitions  
`docs/ARCHITECTURE_PACKAGE_CONTRACT.md` — required contents of each architecture folder  
`tests/` — backend correctness tests  
`examples/` — minimal usage examples

## Architecture status

The existing corpus is pre-grant work and is being audited. A folder's presence does **not** mean it is validated or benchmarked. Use the inventory fields to distinguish implemented, validated, benchmarked, duplicate, fallback and unsupported items.

## License

Apache License 2.0. Only code with verified provenance and rights to publish should be added.
