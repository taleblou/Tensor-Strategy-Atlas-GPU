# Architecture inventory

`ARCHITECTURE_INVENTORY.csv` is the authoritative list of gpu architecture packages.

Use one row per implementation identity. Do not inflate counts by treating tuning configurations, wrappers or duplicated packages as independent algorithms.

Recommended status vocabulary:

- development_state: `planned | implemented | deprecated`
- verification_status: `not_checked | pass | fail | unsupported`
- benchmark_status: `not_run | measured | invalidated | blocked`
- item_type: `algorithm | variant | wrapper | fallback | reference`
