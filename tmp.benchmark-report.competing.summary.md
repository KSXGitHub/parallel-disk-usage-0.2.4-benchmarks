| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --max-depth=1 tmp.sample` | 124.6 ± 6.4 | 119.4 | 152.2 | 1.00 |
| `dutree --summary tmp.sample` | 313.3 ± 7.0 | 305.6 | 325.9 | 2.51 ± 0.14 |
| `dua --apparent-size tmp.sample` | 257.3 ± 10.7 | 239.8 | 274.6 | 2.06 ± 0.14 |
| `ncdu -o /dev/null -0 tmp.sample` | 204.6 ± 18.0 | 185.8 | 253.4 | 1.64 ± 0.17 |
| `du --apparent-size --total tmp.sample` | 182.3 ± 5.5 | 173.3 | 192.1 | 1.46 ± 0.09 |
