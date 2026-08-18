# Testing and Benchmark Instructions

## Core Rule

Never claim:

"works"

"fixed"

"faster"

"better"

unless there is appropriate evidence.

---

## Validation Levels

### Level 1 — Static

Check:

- syntax;
- imports;
- obvious type errors;
- interface consistency.

### Level 2 — Unit

Test changed functions.

### Level 3 — Integration

Test interaction between modules.

### Level 4 — Competition

Test:

- metric;
- output;
- submission format;
- preprocessing;
- inference pipeline.

### Level 5 — Benchmark

Measure:

- runtime;
- latency;
- throughput;
- memory;
- VRAM;
- metric.

---

## Performance Decision

Keep an optimization only when:

1. correctness is preserved;
2. metric is not degraded beyond the accepted threshold;
3. performance improvement is meaningful;
4. complexity/risk is justified.

Otherwise:

REJECT or DEFER.

---

## Benchmark Rules

Compare experiments using:

- same dataset;
- same validation split;
- same metric;
- same preprocessing;
- comparable hardware;
- comparable batch size;
- same measurement method.

Do not change the evaluation protocol to make an optimization appear better.
