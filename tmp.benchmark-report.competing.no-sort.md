| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --no-sort tmp.sample` | 127.9 ± 4.0 | 119.6 | 135.3 | 1.00 |
| `du --apparent-size tmp.sample` | 188.3 ± 6.6 | 174.0 | 196.6 | 1.47 ± 0.07 |
| `dua --apparent-size tmp.sample` | 244.5 ± 14.3 | 223.7 | 267.3 | 1.91 ± 0.13 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 201.9 ± 8.5 | 191.8 | 217.9 | 1.58 ± 0.08 |
| `gdu --show-apparent-size --non-interactive --no-progress tmp.sample` | 295.9 ± 9.9 | 281.7 | 315.0 | 2.31 ± 0.11 |
