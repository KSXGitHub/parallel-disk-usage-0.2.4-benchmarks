| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --quantity=len tmp.sample` | 127.4 ± 6.5 | 115.6 | 141.2 | 1.00 |
| `dust --apparent-size tmp.sample` | 518.3 ± 38.7 | 464.8 | 598.7 | 4.07 ± 0.37 |
| `dutree tmp.sample` | 3807.0 ± 126.6 | 3619.2 | 3982.2 | 29.89 ± 1.82 |
| `dua --apparent-size tmp.sample` | 237.3 ± 13.5 | 216.0 | 267.4 | 1.86 ± 0.14 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 197.0 ± 5.4 | 189.8 | 205.6 | 1.55 ± 0.09 |
| `gdu --show-apparent-size --non-interactive --no-progress tmp.sample` | 297.2 ± 11.0 | 280.2 | 312.5 | 2.33 ± 0.15 |
| `du --apparent-size tmp.sample` | 182.1 ± 6.7 | 173.0 | 194.9 | 1.43 ± 0.09 |
