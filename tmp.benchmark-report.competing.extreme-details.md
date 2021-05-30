| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --min-ratio=0 tmp.sample` | 711.8 ± 17.6 | 677.9 | 737.4 | 3.77 ± 0.12 |
| `dutree tmp.sample` | 3729.2 ± 109.3 | 3454.0 | 3848.3 | 19.74 ± 0.70 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 200.6 ± 5.6 | 186.4 | 208.1 | 1.06 ± 0.04 |
| `du --apparent-size tmp.sample` | 188.9 ± 3.7 | 184.7 | 196.1 | 1.00 |
