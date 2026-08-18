
---

# 4. `competition.instructions.md`

Đây là layer quan trọng cho Olympic AI.

```md
# Competition Instructions

## Competition Workflow

Always prefer:

Problem Contract
→ Environment Probe
→ Metric Contract
→ Validation
→ Baseline
→ First Valid Submission
→ Error Analysis
→ Experiment
→ Best Model
→ Freeze
→ Final Submission
→ Reproducibility Check

Baseline before optimization.

---

## Official Sources

Competition-specific claims must use:

1. Official Regulation
2. Official Task
3. Official Scorer
4. Official Starter Code
5. Official Workshop
6. Team Evidence
7. General Knowledge
8. Inference

Never reverse this priority.

---

## Current FPTU Regulation Evidence

Verified:

Google Colab is the primary computational environment. [V]

LLM tools are permitted during the competition, subject to competition/task rules. [V]

Task-specific rules determine permitted data, pretrained models, parameter limits, submission limits, format and metric. [V]

External datasets, labels and unauthorized pretrained weights are prohibited. [V]

Private Test must not be used for retraining, fine-tuning, refitting, recalibration or adjustment. [V]

Predictions must be generated automatically; individual manual prediction editing is prohibited. [V]

Submission format requirements must be followed exactly. [V]

Source code, notebooks, training/inference code, checkpoints/weights and configuration must be retained for reproducibility. [V]

---

## Unknowns

Do not assume:

- exact contest duration;
- number of tasks;
- submission limits;
- package installation policy;
- internet policy;
- specific allowed pretrained models;
- specific LLM;
- token limits;
- private-test format.

These require task-specific or official evidence.

---

## Competition Decision Rule

If no valid submission exists:

Prioritize a valid baseline submission.

If a valid submission exists:

Perform measured experiments.

Near deadline:

Stop risky experiments.

Freeze:

- model;
- weights;
- preprocessing;
- thresholds;
- configuration.

Then validate and reproduce.
