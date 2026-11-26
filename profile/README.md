## ModelStill

**The release gate for LLM changes.** Open-source LLM evals for CI that compare every model or
prompt change with your accepted baseline, case by case, and tell you whether it is safe to ship.

- **Paired comparison** against the baseline: which cases a change fixed and which it broke.
- **Confidence intervals** on every score, so noise is not mistaken for progress or a regression.
- **One decision** that also checks flip rate, cost and p95 latency, with exit code 0 or 2 for CI
  and a pull request comment from the GitHub Action.
- **Works with what you log:** Langfuse, Braintrust, OpenTelemetry GenAI spans, LiteLLM and JSONL.
- **Self-hosted and vendor-neutral.** Apache-2.0.

[Repository](https://github.com/modelstill/modelstill) ·
[Documentation](https://docs.modelstill.com) ·
[Quickstart](https://docs.modelstill.com/quickstart) ·
[Website](https://modelstill.com)
