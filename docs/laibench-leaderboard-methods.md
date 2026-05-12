# LAIBench Public Leaderboard Method

This public mirror is a technical preview. It ships the harness, schemas,
documentation, paper materials, and a synthetic demo suite only.

No official clinical leaderboard is published in this repository.

## Public Demo Scope

The public suite is `lite-public.pt-BR`. It points to synthetic demo cases under
`cases/public/synthetic-demo.pt-BR.json`.

The demo suite is intended for:

- installation checks;
- CLI smoke tests;
- submission-format review;
- scoring-contract inspection;
- local integration experiments.

The demo suite is not a clinical corpus, not a hidden test set, and not a basis
for clinical validation claims.

## Official Evaluation

Official rows require controlled or hosted evaluation. A submission must include
frozen outputs, suite hashes, disclosure metadata, system class, cost/latency
metadata when available, and eligibility review.

The clinical corpus, private hidden test set, answer keys, and private scoring
criteria are not distributed in this public mirror.

## Reporting Rules

Public reporting should distinguish:

- synthetic demo runs;
- controlled-access evaluations;
- hosted hidden-test evaluations;
- raw-model baselines;
- mini-agent scaffolds;
- product or custom-agent workflows.

Incompatible rows must not be presented as directly comparable. Demo scores must
not be described as clinical validation, regulatory approval, deployment
readiness, or proof of safety.

## Privacy And Governance

Do not expose raw reports, real-derived case text, private prompts, product
routes, credentials, private file paths, raw validation ID lists, hidden judge
configuration, answer keys, private scoring criteria, or private test content.

The method is public. The clinical corpus is controlled. Official evaluation is
gated.
