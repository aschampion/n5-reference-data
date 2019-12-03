# N5 Reference Data

This is a [DVC](https://dvc.org/) [data registry](https://dvc.org/doc/use-cases/data-registry) for test and verification datasets for the [N5 tensor filesystem format](https://github.com/saalfeldlab/n5).

## Datasets
- `data.n5`
  - `t1-head-raw` N5 encodings of an [MRI dataset from ImageJ](https://imagej.nih.gov/ij/images/t1-head-raw.zip), produced by Java N5 in all of its core compression formats. This was produced with `mvn -Dtest=N5Benchmark test`.

