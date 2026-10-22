---
name: Bug report
about: Something in Gavà is broken or produces incorrect output
title: ""
labels: bug
---

**Describe the bug**
A clear description of what's wrong.

**Reproduction**
If this is a layout-quality issue, generation is deterministic given a seed
— please include the exact request:

```bash
gava generate --width ... --length ... --room ... --seed N
```

or the equivalent JSON body to `POST /api/v1/generate`.

**Expected behavior**
What you expected to happen instead.

**Environment**
- Gavà version / commit:
- Python version:
- OS:

**Additional context**
Screenshots, generated DXF/PNG/SVG, or anything else useful.
