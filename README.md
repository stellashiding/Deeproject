# Deeproject

**Product version:** Production Version 1  
**Current implementation:** Interactive product version for research publication, user testing, and early startup validation

## What Deeproject is

Deeproject is a behavioral assurance platform for evaluating **long-horizon, human-facing AI interactions**.

It connects:

```text
User experience
→ interaction trace
→ behavioral framework evaluation
→ human review
→ improvement action
```

The main goal is to help teams identify when an AI system begins to lose a user’s goals, constraints, or context across multiple turns.

## Behavioral evaluation framework

Deeproject uses a structured behavioral evaluation framework with:

- stable core evaluation dimensions;
- guided domain-specific criteria;
- failure tags;
- evidence requirements;
- anchored rating scales;
- calibration examples;
- human review and validation.

Researchers may adapt the framework to different domains without changing the meaning of its core constructs.

Specific internal framework names, unpublished dimensions, and research methods should not be included in public-facing product materials until the related research is no longer under anonymous review.

## What Production Version 1 includes

- **Experience View** — reconstructs what the user saw and did
- **Research Console** — trace search, long-horizon analysis, framework scores, evidence, and telemetry
- **Framework Builder** — guided customization of domain criteria
- **Review Governance** — multiple reviewers, reliability, disagreement, and adjudication
- **Dataset Studio** — converts validated failures into reusable artifacts
- **Integrations** — illustrates SDK, API, OpenTelemetry, and JSON/JSONL ingestion

Production Version 1 is currently implemented as a single-file interactive front end. Some scores, metrics, predictions, and statistics are illustrative.

## Current research direction

The central research question is:

> How can structured, evidence-linked behavioral evaluation help researchers inspect and act on long-horizon failures in human-facing AI systems?

Current research topics include:

- failure onset and propagation across turns;
- stable evaluation constructs with domain-specific adaptation;
- evidence localization;
- human–AI evaluator disagreement;
- reviewer reliability and adjudication;
- movement from aggregate patterns to individual traces;
- conversion of confirmed failures into concrete actions.

## Research publication focus

The product can support research publications on:

- design requirements for long-horizon AI evaluation tools;
- connecting user experience with system evidence;
- balancing standardized evaluation with domain adaptation;
- presenting automated scores and human disagreement;
- supporting evidence-based human review;
- turning evaluation findings into model or product improvement;
- researcher and practitioner workflows for behavioral AI assurance.

Suggested study tasks:

1. Inspect a user-facing interaction.
2. Open the linked trace.
3. Identify where the failure begins.
4. Review behavioral scores and evidence.
5. Agree with or override an evaluation.
6. Examine reviewer disagreement.
7. Customize or critique one domain criterion.
8. Decide what action should follow.

## Current startup focus

The startup workflow should remain narrower than the complete research product.

```text
Import a real trace
→ detect or flag a long-horizon failure
→ localize evidence
→ human confirms or overrides
→ save as a regression test
→ replay on a candidate version
```

The sharpest startup positioning is:

> Deeproject helps AI teams find long-horizon failures in human-facing agents and turn confirmed evidence into regression tests before release.

## What is real today

- structured behavioral evaluation framework;
- long-horizon evaluation concept;
- failure tags and evidence turns;
- EarSketch curriculum-RAG context;
- human annotation and reliability workflow;
- interactive product interface;
- baseline/candidate comparison;
- framework customization design;
- local study-mode interaction logging.

## What is currently illustrative

- automated framework-evaluation outputs;
- evaluator confidence;
- model-based evaluator comparisons;
- predictions;
- latency, cost, and retrieval metrics;
- stakeholder weighting outcomes;
- SDK/API behavior;
- automated release gates;
- post-training exports;
- cross-domain performance claims.

Illustrative components should not be presented as validated production results.

## Future research

- formative studies with AI researchers and practitioners;
- larger annotated datasets;
- automated behavioral evaluation;
- failure-tag and evidence-turn prediction;
- calibration and uncertainty;
- human–AI evaluator disagreement;
- cross-domain validation;
- multimodal and multi-agent evaluation.

## Future product

- production SDK and API;
- scalable trace ingestion;
- authentication and permissions;
- reviewer assignment;
- versioned regression suites;
- CI/CD quality gates;
- customer-feedback integrations;
- validated prediction;
- post-training export;
- multimodal and multi-agent support.

## Current non-goals

Deeproject is not currently:

- an agent runtime;
- a generic observability platform;
- a general data warehouse;
- a model-based-evaluator-only system;
- a fully automated governance authority;
- a generic annotation platform;
- a customer-facing chatbot.

## Team decision guide

Label each feature as:

- `CURRENT-RESEARCH`
- `CURRENT-STARTUP`
- `SHARED-CORE`
- `FUTURE-RESEARCH`
- `FUTURE-PRODUCT`
- `ILLUSTRATIVE-ONLY`
- `OUT-OF-SCOPE`

Before adding a feature, ask:

1. Does it help detect a long-horizon failure?
2. Does it connect the failure to evidence?
3. Does it improve human review or reliability?
4. Does it support an actionable next step?
5. Is it needed now, or is it future work?
6. Does it expose unpublished research details?

## Current priority

1. Connect at least one real trace-ingestion path.
2. Improve long-horizon evidence visualization.
3. Support human confirmation and override.
4. Export confirmed failures as regression cases.
5. Run studies with researchers and practitioners.
6. Validate the narrow startup workflow with real AI teams.
7. Keep anonymous research details separate from public product materials.

## Project principle

> Build the broad product needed to support research and discovery, but commercialize the narrowest workflow that delivers clear value.
