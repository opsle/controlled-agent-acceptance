# Controlled Agent Acceptance

> Experimental Opsle research. Claims are hypotheses until evidence supports them.

## Problem

Real-agent acceptance can accidentally exceed provider budgets, target the wrong revision, conflict with work, or leave reusable authority and residue.

## Hypothesis

An immutable run manifest plus exact one-shot activation and fail-closed restoration can test real autonomy without widening authority.

## Mechanism

Bind immutable run identity, fixture, software/target/route revisions, provider budget, Pause state, and zero-conflict preflight; activate once by CAS; restore Pause; preserve evidence; reconcile residue.

## Why it matters

The Opsle thesis asks: **What if we stopped using intelligence for work that doesn’t require intelligence?** This project isolates one candidate boundary so it can be falsified and measured independently.

## Non-goals

A reusable provider authorization, retrying failed acceptance silently, or equating harness correctness with system-under-test success.

## Current maturity

**THEORY** under the [Opsle maturity model](https://github.com/opsle/research/blob/main/MATURITY.md).

## Existing evidence

Multiple controlled runs exposed real lease, handoff, and review-route defects while preserving first-failure semantics.

## Evidence still missing

Independent harness implementation, formal interruption model, non-reusable credential grants, and replication across runtimes.

## Benchmark strategy

Correctness gates every comparison. Planned measures:

- preflight accuracy
- budget adherence
- restore success
- evidence preservation
- stale authority rejection
- residue

See [BENCHMARK.md](BENCHMARK.md) for experiment rules. No benchmark numbers are claimed.

## Relationship to other Opsle research

This project is part of [Opsle Research](https://github.com/opsle/research). Opsle Tasks is the future public name of the integrated reference system from which several ideas emerged. Its active development migration to the Opsle organization is intentionally deferred.

## Relationship to future Opsle Tasks

Future Opsle Tasks may consume this project through an adapter only after evidence supports integration. The active predecessor, Taslos Tasks, remains unchanged and has no dependency on this repository.

## Installation status

No installable production package is justified yet. The repository is theory/specification-first.

## Known limitations

Independent harness implementation, formal interruption model, non-reusable credential grants, and replication across runtimes.

## License

Apache-2.0. See [LICENSE](LICENSE).
