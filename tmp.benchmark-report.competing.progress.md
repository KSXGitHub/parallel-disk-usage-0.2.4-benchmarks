| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --progress tmp.sample` | 207.8 ± 1.4 | 206.6 | 212.3 | 1.02 ± 0.03 |
| `ncdu -o /dev/stdout -1 tmp.sample` | 202.8 ± 6.6 | 192.3 | 216.2 | 1.00 |
| `gdu --show-apparent-size --non-interactive tmp.sample` | 305.3 ± 10.1 | 285.8 | 315.2 | 1.51 ± 0.07 |
