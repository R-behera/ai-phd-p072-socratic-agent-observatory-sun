# Unique Prototype Algorithm

## Algorithm

**SunConstraintNlpRouteEngine** (`P072-Sun-Nlp`)

## Professor Alignment

- Professor: Huan Sun
- Research area: NLP, biomedical NLP, question answering, LLMs
- Focus terms: NLP, biomedical NLP, question answering, LLMs

## Core Mechanism

This prototype prioritizes high-acquisition scientific candidates using score, uncertainty, and cost.

## Decision Rule

Rank seed cases by science-specific priority score with Sun-aligned focus term 'NLP'.

## What The Code Adds

- A unique algorithm spec in `src/proposed_method.py`.
- A scoring function for the repo's `science` data schema.
- A ranked list of cases that should be reviewed, repaired, reproduced, or expanded first.
- Integration into `src/value_add.py`, so demo output includes the proposed method.

## Honest Status

This is a runnable algorithmic prototype. It is not a validated contribution to Huan Sun's published work until the seed data is replaced with real public/lab-relevant data and the resulting claims are evaluated.

## Run

```bash
python src/proposed_method.py
python src/value_add.py --write-report reports/demo_results.json
python -m unittest discover -s tests
```
