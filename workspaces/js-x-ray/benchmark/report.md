# Benchmark Report

- **Timestamp:** 2026-11-08T05:12:16.034Z
- **Runtime:** node
- **CPU:** AMD EPYC 9V74 80-Core Processor (~3.49 GHz)

| Benchmark | min | max | p25 | p50 | p75 | p99 | p999 | avg | samples | heap (avg) | gc (avg) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Small File (jscrush.js - 1.03KB) | 157.36 µs | 1.40 ms | 185.57 µs | 211.82 µs | 305.83 µs | 899.50 µs | 1.18 ms | 263.20 µs | 2647 | 267.97 KB | — |
| Small File (npm-audit.js - 1.46KB) | 415.57 µs | 2.14 ms | 469.46 µs | 509.41 µs | 700.18 µs | 1.26 ms | 1.62 ms | 593.49 µs | 1175 | 442.33 KB | — |
| Small File (forbes-skimmer.js - 2.15KB) | 1.13 ms | 3.64 ms | 1.19 ms | 1.25 ms | 1.56 ms | 2.64 ms | 3.48 ms | 1.44 ms | 483 | 708.54 KB | — |
| Small File (rate-map.js - 2.21KB) | 1.12 ms | 4.48 ms | 1.18 ms | 1.26 ms | 1.52 ms | 2.98 ms | 3.22 ms | 1.42 ms | 488 | 731.12 KB | — |
| Small File (event-stream.js - 3.76KB) | 1.20 ms | 3.13 ms | 1.28 ms | 1.44 ms | 1.65 ms | 2.54 ms | 2.91 ms | 1.51 ms | 458 | 877.38 KB | — |
| Small File (modrrnize.js - 9.28KB) | 849.73 µs | 2.75 ms | 917.54 µs | 990.38 µs | 1.18 ms | 1.98 ms | 2.45 ms | 1.08 ms | 647 | 763.49 KB | — |
| Small File (smith.js - 9.28KB) | 828.50 µs | 2.23 ms | 894.77 µs | 934.15 µs | 1.09 ms | 1.70 ms | 2.16 ms | 1.02 ms | 683 | 755.12 KB | — |
| Medium File (kopiluwak.js - 15.45KB) | 1.73 ms | 4.21 ms | 1.80 ms | 2.02 ms | 2.17 ms | 3.45 ms | 4.19 ms | 2.09 ms | 331 | 1.33 MB | — |
| Large File (obfuscate.js - 89.57KB) | 64.26 ms | 69.12 ms | 64.91 ms | 66.69 ms | 68.52 ms | 68.71 ms | 68.71 ms | 66.88 ms | 12 | 31.61 MB | 12.39 ms |
| jscrush.js | 172.12 µs | 985.00 µs | 198.80 µs | 223.95 µs | 308.70 µs | 565.58 µs | 856.95 µs | 263.33 µs | 2651 | 263.54 KB | — |
| obfuscate.js | 36.69 ms | 48.50 ms | 39.88 ms | 41.51 ms | 44.70 ms | 47.93 ms | 47.93 ms | 42.12 ms | 13 | 19.87 MB | — |
