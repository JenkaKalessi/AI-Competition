# Python Coding Instructions

## Objective

Write Python that is:

- correct;
- readable;
- testable;
- reasonably fast;
- reproducible.

Do not optimize prematurely.

---

## Before coding

Inspect:

- existing project structure;
- Python version;
- dependency files;
- existing utilities;
- existing tests;
- public interfaces.

Do not assume package availability.

---

## Implementation

Prefer:

- standard library when sufficient;
- existing project dependencies;
- explicit types;
- small functions;
- clear names;
- deterministic behavior.

Avoid:

- unnecessary classes;
- unnecessary abstractions;
- hidden state;
- unnecessary dependencies;
- duplicated logic.

---

## Error handling

Handle expected failures explicitly.

Do not silently catch all exceptions.

Avoid:

```python
except Exception:
    pass
