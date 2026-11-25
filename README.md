# Disconfirm

> Status: concept repository - future work

A hypothesis-testing engine designed to falsify plausible explanations.

## Objective

Generate competing explanations for an observed problem and design experiments that distinguish between them.

## Proposed scope

- Represent competing hypotheses and their predictions
- Select discriminating experiments
- Collect and rank evidence
- Update confidence without hiding contradictory results

## Technical direction

Bayesian inference, causal graphs, isolated execution, and language models.

The technologies above are candidates, not commitments. Selection will follow evidence from the smallest useful prototype.

## Open questions

- What observable result would make the first prototype useful?
- Which assumptions need controlled experiments before implementation?
- What independent oracle can determine whether an experiment succeeded?
- What is the smallest reproducible dataset or workload?

## Repository status

This repository reserves the project identity and records the initial concept. It contains no production implementation, published roadmap, or stable API.
