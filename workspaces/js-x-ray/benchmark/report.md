# Benchmark Report

- **Timestamp:** 2026-10-18T03:43:04.125Z
- **Runtime:** node
- **CPU:** AMD EPYC 7763 64-Core Processor (~3.05 GHz)

| Benchmark | min | max | p25 | p50 | p75 | p99 | p999 | avg | samples | heap (avg) | gc (avg) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Small File (jscrush.js - 1.03KB) | 244.49 µs | 1.40 ms | 279.63 µs | 320.55 µs | 460.76 µs | 841.75 µs | 1.22 ms | 378.32 µs | 1838 | 277.69 KB | — |
| Small File (npm-audit.js - 1.46KB) | 599.47 µs | 1.92 ms | 666.63 µs | 701.70 µs | 999.09 µs | 1.58 ms | 1.90 ms | 837.04 µs | 832 | 424.72 KB | — |
| Small File (forbes-skimmer.js - 2.15KB) | 1.85 ms | 5.63 ms | 1.95 ms | 2.07 ms | 2.55 ms | 4.27 ms | 4.42 ms | 2.34 ms | 295 | 743.36 KB | — |
| Small File (rate-map.js - 2.21KB) | 1.51 ms | 4.40 ms | 1.61 ms | 1.94 ms | 2.27 ms | 4.06 ms | 4.27 ms | 2.05 ms | 337 | 760.12 KB | — |
| Small File (event-stream.js - 3.76KB) | 1.72 ms | 4.40 ms | 1.86 ms | 2.34 ms | 2.75 ms | 4.10 ms | 4.25 ms | 2.39 ms | 288 | 923.85 KB | — |
| Small File (modrrnize.js - 9.28KB) | 1.10 ms | 5.88 ms | 1.19 ms | 1.49 ms | 1.90 ms | 2.68 ms | 5.84 ms | 1.58 ms | 437 | 783.35 KB | — |
| Small File (smith.js - 9.28KB) | 1.11 ms | 3.76 ms | 1.22 ms | 1.52 ms | 1.72 ms | 3.06 ms | 3.43 ms | 1.56 ms | 445 | 773.08 KB | — |
| Medium File (kopiluwak.js - 15.45KB) | 2.29 ms | 6.81 ms | 2.38 ms | 2.83 ms | 3.12 ms | 5.91 ms | 6.64 ms | 2.93 ms | 233 | 1.35 MB | — |
| Large File (obfuscate.js - 89.57KB) | 81.26 ms | 122.55 ms | 94.52 ms | 99.31 ms | 103.71 ms | 111.60 ms | 111.60 ms | 101.21 ms | 12 | 30.92 MB | 18.77 ms |
| jscrush.js | 273.49 µs | 2.16 ms | 309.49 µs | 345.48 µs | 442.35 µs | 839.10 µs | 1.35 ms | 401.29 µs | 1733 | 275.37 KB | — |
| obfuscate.js | 49.72 ms | 63.46 ms | 51.58 ms | 53.57 ms | 54.31 ms | 61.24 ms | 61.24 ms | 54.45 ms | 9 | 20.83 MB | — |
