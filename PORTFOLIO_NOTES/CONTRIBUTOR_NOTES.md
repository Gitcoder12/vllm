# Contributor Notes — vLLM Fork

This is a fork of vllm-project/vllm. Follow upstream contributing instructions and code-owner guidance.

1. Read the upstream README, CONTRIBUTING.md, licence and every applicable AGENTS.md file.
2. Confirm your working tree/branch and upstream base commit before edits.
3. Prefer a separate portfolio experiment directory for local scripts, configs and results.
4. For core fixes, reproduce on a pinned commit and create a focused test.
5. Do not change CUDA kernels, schedulers or engine internals without a precise issue and benchmark.
6. Record hardware, runtime, model revision and workload for every performance claim.
7. Submit upstream contributions to the upstream repository when appropriate; do not imply a local fork PR was accepted upstream.
