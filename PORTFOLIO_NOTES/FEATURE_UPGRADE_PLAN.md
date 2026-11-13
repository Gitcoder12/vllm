# vLLM Fork — Feature and Benchmark Plan

## Objective

Create reproducible evidence about LLM serving performance and reliability while maintaining a clean, attribution-safe fork.

## P0 — reproducible baseline

- [ ] Create a reproducible single-node serving baseline with model ID/revision, GPU, driver/CUDA, vLLM version, request mix and concurrency recorded.
- [ ] Measure time-to-first-token, inter-token latency, throughput, memory and error rate under a fixed workload.

## P1 — controlled optimisation studies

- [ ] Compare batching, parallelism, memory and cache settings one at a time.
- [ ] Include warmup, repeated trials, confidence/variance and error rates.
- [ ] Record all config changes and revert experiments that are not reproducibly beneficial.

## P2 — upstream contributions

- [ ] Compare one configuration change at a time; retain the unmodified upstream baseline and report variance.
- [ ] Keep local scripts/results under a distinct portfolio experiment path and avoid modifying upstream core files for cosmetic purposes.
- [ ] For upstream bugs, reproduce against a pinned commit, add tests and follow upstream review processes.

## Definition of done

- [ ] Baseline includes exact model/runtime/hardware/workload.
- [ ] Results are reproducible and report latency and throughput, not only a single peak number.
- [ ] Local experiment code is isolated from upstream core.
- [ ] Upstream fixes have focused tests and explicit attribution.
