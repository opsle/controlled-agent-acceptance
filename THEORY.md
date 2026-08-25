# Theory

## Observation

Real-agent acceptance can accidentally exceed provider budgets, target the wrong revision, conflict with work, or leave reusable authority and residue.

## Hypothesis

An immutable run manifest plus exact one-shot activation and fail-closed restoration can test real autonomy without widening authority.

## Proposed mechanism

Bind immutable run identity, fixture, software/target/route revisions, provider budget, Pause state, and zero-conflict preflight; activate once by CAS; restore Pause; preserve evidence; reconcile residue.

## Falsifiable requirements

1. Run identity is non-reusable.
2. The exact provider budget is literal.
3. Pause restoration is interruption- and restart-safe.
4. Harness verdict and system-under-test verdict remain distinct.

## Disconfirming results

The hypothesis should be weakened or rejected if a comparable baseline passes the same correctness gate and this mechanism provides no repeatable benefit, or if the mechanism introduces safety/correctness failures that bounded revisions do not resolve. Negative results remain in `experiments/`.

## Uncertainty

Independent harness implementation, formal interruption model, non-reusable credential grants, and replication across runtimes.
