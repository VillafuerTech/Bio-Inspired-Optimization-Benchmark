# Verified quick-suite output

This compact artifact was captured from a clean checkout on 2026-08-28 with Python 3.14.5:

```bash
python -m bioopt_bench suite --suite quick --repeat 1 --save
```

| Task | Variant | Algorithm | Seed | Iterations | Best fitness |
| --- | --- | --- | ---: | ---: | ---: |
| functions | beale | PSO | 42 | 50 | 0.0036258686 |
| tsp | random | ACO | 42 | 20 | 352.3181764619 |
| scheduling | default | GWO | 42 | 50 | 5 |

The run completed three experiments and wrote `reports/results.csv` plus per-run configuration,
metric, curve, solution, and figure artifacts. Runtime is intentionally omitted because it is
machine-dependent. Fitness values are reproducible for the recorded seed and current code, but
they are task-specific and should not be interpreted as a cross-algorithm ranking.
