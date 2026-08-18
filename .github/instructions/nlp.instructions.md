# NLP Competition Instructions

## Determine the task first

Possible tasks:

- classification;
- sentiment;
- toxicity;
- NER;
- retrieval;
- ranking;
- labeling;
- generation.

Do not assume the task is classification.

---

## Baseline

Prefer a simple measurable baseline before a transformer-heavy solution.

When appropriate, consider:

- TF-IDF;
- character n-grams;
- word n-grams;
- linear models.

These are baselines, not universal rules.

---

## Metrics

Verify the official metric before model selection.

Possible metrics include:

- Accuracy;
- Macro-F1;
- Log Loss;
- MRR.

Do not assume which metric is used.

---

## Error Analysis

Inspect:

- class imbalance;
- confusing classes;
- short text;
- noisy text;
- spelling variation;
- duplicated samples;
- label inconsistencies.

Do not invent labels.

---

## LLM Usage

LLMs may assist with:

- code;
- analysis;
- debugging;
- prompt experimentation;
- error analysis.

Do not use LLM-generated labels or external information if the competition rules prohibit them.
