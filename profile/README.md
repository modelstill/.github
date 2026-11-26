## ModelStill

**The release gate for LLM changes.** An open-source LLM eval framework for CI: regression-test
every prompt and model change against a golden dataset, and ship only when the gate passes.

- **Regression checks on every prompt and model update**, compared with the accepted baseline case
  by case: which cases a change fixed and which it broke.
- **Golden datasets** built from the calls you already log, versioned, with a human review queue.
- **LLM-as-a-judge you can trust:** agreement with human labels (Cohen's kappa), verdict stability,
  and pairwise judging in both orders.
- **Confidence intervals** on every score, plus flip rate, cost and p95 latency in the same decision.
- **Evals in CI:** exit code 0 or 2, a GitHub Action that comments on the pull request, and a pytest
  plugin.
- **Works with what you log:** OpenTelemetry GenAI spans, Langfuse, Braintrust, LiteLLM and JSONL.
  Self-hosted and vendor-neutral. Apache-2.0.

[Repository](https://github.com/modelstill/modelstill) ·
[Documentation](https://docs.modelstill.com) ·
[Quickstart](https://docs.modelstill.com/quickstart) ·
[Website](https://modelstill.com)
