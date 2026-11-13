# Agent and Skills Notes — vLLM Fork

## Instruction precedence

Upstream root and nested AGENTS.md files are authoritative. Do not replace or contradict them. This file adds portfolio-specific constraints only.

## Bounded work

- Read applicable upstream guidance and inspect open issues/PRs first.
- Keep changes limited to the assigned component and add focused tests.
- Do not run destructive deployment, publish packages or change production model endpoints.
- Record exact environment and reproducible benchmarks.
- Avoid edits to vendored/generated files or unrelated CUDA/engine code.
- Open reviewable PRs; human maintainers control merges and releases.

## Skill areas

- LLM serving architecture and request scheduling.
- GPU/CUDA runtime and memory profiling.
- Benchmark methodology: TTFT, ITL, throughput, memory and error rate.
- Distributed systems and reliability testing.
- Upstream fork sync, licence and contribution provenance.
