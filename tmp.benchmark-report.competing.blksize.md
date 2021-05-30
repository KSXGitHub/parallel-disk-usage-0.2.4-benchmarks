| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --quantity=blksize tmp.sample` | 122.4 ± 3.2 | 114.8 | 130.3 | 1.00 |
| `dust tmp.sample` | 791.6 ± 15.1 | 771.9 | 812.2 | 6.47 ± 0.21 |
| `dutree --usage tmp.sample` | 3706.1 ± 79.0 | 3566.2 | 3790.5 | 30.28 ± 1.03 |
| `dua tmp.sample` | 265.5 ± 15.8 | 249.4 | 306.3 | 2.17 ± 0.14 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 204.3 ± 5.8 | 192.4 | 212.1 | 1.67 ± 0.07 |
| `gdu --non-interactive --no-progress tmp.sample` | 300.0 ± 9.0 | 286.2 | 311.8 | 2.45 ± 0.10 |
| `du tmp.sample` | 192.1 ± 9.1 | 178.1 | 213.9 | 1.57 ± 0.09 |
