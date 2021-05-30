| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --no-sort --max-depth=1 tmp.sample` | 121.6 ± 4.1 | 114.3 | 129.8 | 1.00 |
| `dua --apparent-size tmp.sample` | 243.4 ± 17.4 | 223.1 | 279.7 | 2.00 ± 0.16 |
| `ncdu -o /dev/null -0 tmp.sample` | 201.9 ± 5.4 | 193.1 | 210.3 | 1.66 ± 0.07 |
| `gdu --show-apparent-size --non-interactive --no-progress tmp.sample` | 313.9 ± 15.7 | 285.3 | 331.0 | 2.58 ± 0.16 |
| `du --apparent-size --total tmp.sample` | 187.8 ± 10.3 | 171.7 | 210.9 | 1.54 ± 0.10 |
