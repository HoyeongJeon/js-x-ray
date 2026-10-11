# Benchmark Report

- **Timestamp:** 2026-10-11T04:50:19.978Z
- **Runtime:** node
- **CPU:** AMD EPYC 7763 64-Core Processor (~3.09 GHz)

| Benchmark | min | max | p25 | p50 | p75 | p99 | p999 | avg | samples | heap (avg) | gc (avg) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Small File (jscrush.js - 1.03KB) | 235.81 µs | 1.61 ms | 265.38 µs | 299.04 µs | 367.48 µs | 840.11 µs | 1.30 ms | 349.83 µs | 1986 | 270.13 KB | — |
| Small File (npm-audit.js - 1.46KB) | 611.70 µs | 2.42 ms | 667.47 µs | 701.98 µs | 950.72 µs | 1.56 ms | 2.17 ms | 831.58 µs | 836 | 427.43 KB | — |
| Small File (forbes-skimmer.js - 2.15KB) | 1.89 ms | 5.70 ms | 1.98 ms | 2.07 ms | 2.55 ms | 4.24 ms | 4.62 ms | 2.35 ms | 293 | 737.70 KB | — |
| Small File (rate-map.js - 2.21KB) | 1.51 ms | 4.08 ms | 1.61 ms | 1.71 ms | 2.11 ms | 3.71 ms | 4.02 ms | 1.92 ms | 358 | 717.67 KB | — |
| Small File (event-stream.js - 3.76KB) | 1.69 ms | 4.88 ms | 1.81 ms | 2.13 ms | 2.40 ms | 4.12 ms | 4.59 ms | 2.20 ms | 312 | 908.00 KB | — |
| Small File (modrrnize.js - 9.28KB) | 1.10 ms | 3.23 ms | 1.17 ms | 1.24 ms | 1.55 ms | 2.24 ms | 2.93 ms | 1.38 ms | 503 | 761.47 KB | — |
| Small File (smith.js - 9.28KB) | 1.11 ms | 3.37 ms | 1.19 ms | 1.30 ms | 1.61 ms | 2.73 ms | 3.34 ms | 1.43 ms | 484 | 772.23 KB | — |
| Medium File (kopiluwak.js - 15.45KB) | 2.34 ms | 5.47 ms | 2.44 ms | 2.81 ms | 3.00 ms | 4.83 ms | 5.23 ms | 2.84 ms | 241 | 1.34 MB | — |
| Large File (obfuscate.js - 89.57KB) | 81.96 ms | 99.81 ms | 88.93 ms | 91.59 ms | 95.20 ms | 97.95 ms | 97.95 ms | 91.69 ms | 12 | 31.30 MB | 15.53 ms |
| jscrush.js | 268.00 µs | 1.29 ms | 307.75 µs | 346.40 µs | 475.82 µs | 838.75 µs | 1.04 ms | 402.53 µs | 1730 | 272.26 KB | — |
| obfuscate.js | 49.91 ms | 90.05 ms | 50.83 ms | 55.71 ms | 64.04 ms | 66.09 ms | 66.09 ms | 60.30 ms | 12 | 20.68 MB | — |
