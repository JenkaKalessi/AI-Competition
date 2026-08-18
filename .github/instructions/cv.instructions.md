# Computer Vision Instructions

## Before choosing a model

Determine:

TASK TYPE
INPUT
OUTPUT
METRIC
DATA SIZE
IMAGE SIZE
RESOURCE LIMIT
SUBMISSION FORMAT

Do not assume every CV task is detection.

Possible tasks:

- classification;
- detection;
- segmentation;
- regression;
- density estimation;
- counting;
- keypoint/pose.

---

## Model Selection

Choose the simplest competitive baseline that matches the task.

Do not assume:

- encoder-decoder;
- ReLU output;
- MSE;
- target scaling;
- fixed output shape;
- pretrained weights.

These are task-dependent.

---

## Tensor Safety

Always verify:

- batch dimension;
- channel order;
- spatial dimensions;
- dtype;
- device;
- output shape;
- target shape.

Before training, run a forward-shape test.

---

## Data Safety

Verify:

- train/validation separation;
- label format;
- class mapping;
- preprocessing consistency;
- augmentation behavior.

Do not use test ground truth.

---

## Inference

Benchmark actual inference.

Do not claim one model is faster without measurement.

For GPU inference, distinguish:

- preprocessing;
- host-to-device transfer;
- model inference;
- postprocessing.

When useful, benchmark each component separately.

---

## Density / Counting

Density-map assumptions are NOT universal CV rules.

Only use density-specific techniques when the task actually requires density estimation/counting.
