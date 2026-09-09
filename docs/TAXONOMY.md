# Architecture taxonomy

Each implementation has exactly one primary family and may have additional descriptive tags.

1. Core tensor / layout / views
2. Memory / data movement
3. Elementwise / fusion
4. Reduction / scan / statistics
5. Sort / selection / search
6. Dense linear algebra
7. Convolution / stencil / spatial
8. Sparse / graph / irregular
9. Indexing / scatter / histogram
10. Attention / sequence / embedding / MoE
11. Quantization / low precision
12. Runtime / scheduling / communication
13. Spectral transforms

Tags may describe methods such as tiled, SIMD, atomic, hierarchical, fused, strided, blocked, sparse, packed or mixed precision.
