# Architecture package contract

Each architecture should live in:

`architectures/<family>/<architecture_id>/`

Recommended contents:

```text
<architecture_id>/
├── README.md
├── src/
├── tests/
└── metadata.yaml
```

`README.md` should state operation semantics, assumptions, supported shapes/layouts/dtypes and known limitations.

`metadata.yaml` should identify the architecture ID, family, backend, provenance, license, support mode and source revision.

Measured results should not be stored as hand-edited claims inside source metadata. Reproducible measurements belong in the Lab repository.
