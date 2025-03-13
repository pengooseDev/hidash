# Benchmark Results

Latest benchmark results comparing hidash vs lodash performance.

| Method | Test | Performance Comparison | `hidash` ops/sec | `lodash@4.17.21` ops/sec |
|--------|------|----------------------|----------------|----------------|
| [assign](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/assign.ts) | src/assign.bench.ts > assign performance | hidash is 2.57x faster | 27.39 🏆 | 10.66 |
| [chunk](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/chunk.ts) | src/chunk.bench.ts | hidash is 2.47x faster | 644.51 🏆 | 260.52 |
| [clamp](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/clamp.ts) | src/clamp.bench.ts > clamp performance | hidash is 2.43x faster | 111.19 🏆 | 45.74 |
| [clone](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/clone.ts) | src/clone.bench.ts > clone performance | hidash is 16.85x faster | 56.27 🏆 | 3.34 |
| [cloneDeep](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/cloneDeep.ts) | src/cloneDeep.bench.ts > cloneDeep performance | hidash is 2.33x faster | 2.04 🏆 | 0.88 |
| [difference](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/difference.ts) | src/difference.bench.ts > difference performance | hidash is 3.26x faster | 300.80 🏆 | 92.30 |
| [every](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/every.ts) | src/every.bench.ts > every performance | hidash is 1.85x faster | 50.12 🏆 | 27.09 |
| [filter](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/filter.ts) | src/filter.bench.ts > filter performance | hidash is 2.89x faster | 11.88 🏆 | 4.12 |
| [findIndex](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/findIndex.ts) | src/findIndex.bench.ts > findIndex performance | hidash is 4.67x faster | 4689.17 🏆 | 1004.94 |
| [findLastIndex](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/findLastIndex.ts) | src/findLastIndex.bench.ts > findLastIndex performance | hidash is 4.46x faster | 4672.18 🏆 | 1047.54 |
| [flatten](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/flatten.ts) | src/flatten.bench.ts > flatten performance | hidash is 1.27x faster | 73.25 🏆 | 57.68 |
| [groupBy](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/groupBy.ts) ⚠️ | src/groupBy.bench.ts > groupBy performance comparison | lodash is 1.23x faster | 1107.15 | 1365.54 🏆 |
| [gt](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/gt.ts) | src/gt.bench.ts > gt performance | hidash is 3.17x faster | 157.07 🏆 | 49.56 |
| [has](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/has.ts) | src/has.bench.ts > has performance | hidash is 2.48x faster | 494.93 🏆 | 199.44 |
| [includes](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/includes.ts) | src/includes.bench.ts > includes performance | hidash is 6.66x faster | 39.83 🏆 | 5.98 |
| [isEmpty](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/isEmpty.ts) | src/isEmpty.bench.ts > isEmpty performance | hidash is 10.77x faster | 211.14 🏆 | 19.61 |
| [isEqual](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/isEqual.ts) | src/isEqual.bench.ts > isEqual performance | hidash is 6.40x faster | 5.43 🏆 | 0.85 |
| [keys](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/keys.ts) | src/keys.bench.ts > keys performance | hidash is 2.98x faster | 15.68 🏆 | 5.26 |
| [lt](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/lt.ts) | src/lt.bench.ts > lt performance | hidash is 3.16x faster | 162.57 🏆 | 51.42 |
| [map](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/map.ts) | src/map.bench.ts > map performance | hidash is 1.67x faster | 610.61 🏆 | 365.31 |
| [mapValues](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/mapValues.ts) | src/mapValues.bench.ts > mapValues performance | hidash is 1.51x faster | 492.42 🏆 | 325.35 |
| [merge](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/merge.ts) | src/merge.bench.ts > merge performance | hidash is 1.27x faster | 273.83 🏆 | 214.94 |
| [omit](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/omit.ts) | src/omit.bench.ts > omit performance | hidash is 4.07x faster | 110.60 🏆 | 27.18 |
| [pick](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/pick.ts) | src/pick.bench.ts > pick performance | hidash is 5.04x faster | 163.30 🏆 | 32.38 |
| [pickBy](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/pickBy.ts) | src/pickBy.bench.ts > pickBy performance | hidash is 1.22x faster | 2.29 🏆 | 1.88 |
| [range](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/range.ts) | src/range.bench.ts > range performance | hidash is 1.57x faster | 30.66 🏆 | 19.57 |
| [repeat](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/repeat.ts) | src/repeat.bench.ts > repeat performance | hidash is 2.70x faster | 1681.96 🏆 | 623.85 |
| [shuffle](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/shuffle.ts) | src/shuffle.bench.ts > shuffle performance | hidash is 2.91x faster | 18.73 🏆 | 6.43 |
| [size](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/size.ts) | src/size.bench.ts > size performance | hidash is 1.01x faster | 62.96 🏆 | 62.04 |
| [some](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/some.ts) | src/some.bench.ts > some performance | hidash is 3.48x faster | 18.75 🏆 | 5.39 |
| [sum](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/sum.ts) | src/sum.bench.ts > sum performance | hidash is 2.58x faster | 154.34 🏆 | 59.77 |
| [sumBy](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/sumBy.ts) | src/sumBy.bench.ts > sumBy performance | hidash is 1.35x faster | 136.81 🏆 | 101.60 |
| [toNumber](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/toNumber.ts) | src/toNumber.bench.ts > toNumber performance | hidash is 8.17x faster | 96.02 🏆 | 11.75 |
| [toPairs](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/toPairs.ts) | src/toPairs.bench.ts > toPairs performance | hidash is 2.96x faster | 91.95 🏆 | 31.08 |
| [toString](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/toString.ts) | src/toString.bench.ts > toString performance | hidash is 2.12x faster | 36.21 🏆 | 17.08 |
| [transform](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/transform.ts) | src/transform.bench.ts > transform performance | hidash is 2.95x faster | 245.10 🏆 | 82.99 |
| [trim](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/trim.ts) | src/trim.bench.ts > trim performance | hidash is 2.97x faster | 34.60 🏆 | 11.66 |
| [union](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/union.ts) | src/union.bench.ts > union performance | hidash is 1.77x faster | 94.66 🏆 | 53.39 |
| [uniq](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/uniq.ts) | src/uniq.bench.ts > uniq performance | hidash is 1.45x faster | 114.81 🏆 | 79.33 |
| [uniqBy](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/uniqBy.ts) | src/uniqBy.bench.ts > uniqBy performance | hidash is 1.83x faster | 64.64 🏆 | 35.35 |
| [uniqWith](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/uniqWith.ts) ⚠️ | src/uniqWith.bench.ts > uniqWith performance | lodash is 1.05x faster | 16.28 | 17.10 🏆 |
| [values](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/values.ts) | src/values.bench.ts > values performance | hidash is 22.05x faster | 134.39 🏆 | 6.09 |
| [zip](https://github.com/pengooseDev/hidash/blob/7e4caae7c8141f48556fde30b03d209f005d1f96/src/zip.ts) | src/zip.bench.ts > zip performance | hidash is 1.13x faster | 49.10 🏆 | 43.35 |

> Note: Higher operations per second (ops/sec) numbers are better. Each test compares hidash vs lodash implementation.
>
> ⚠️ indicates where hidash is slower than lodash.
>
> 🏆 indicates the faster implementation.

_Last updated: 2025-03-13_
