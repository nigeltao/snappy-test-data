# snappy-test-data

This is a mirror of [google/snappy](https://github.com/google/snappy)'s
`testdata` directory, copied here as `testdata_original`.

It has been augmented with extra files (in this repository's `testdata_extra`
directory) and with processed versions (e.g. compressed or hashed versions) of
the combined suite (`testdata_original` and `testdata_extra`) of test data
files.


## Copying

This repository's [Apache 2 LICENSE](./LICENSE) applies to source code in this
repository (including `*.sh` files in the top level directory, but excluding
files inside `testdata_*` directories).


### testdata\_original

The files in the `testdata_original` directory were copied from the
[google/snappy](https://github.com/google/snappy)'s `testdata` directory
(excluding `baddata?.snappy` files). That repository's `COPYING` file is copied
into this repository as `testdata\_original\_COPYING`.


### testdata\_extra

The files in the `testdata_extra` directory were added separately, and not
copied from [google/snappy](https://github.com/google/snappy)'s `testdata`
directory. See `testdata\_extra\_COPYING` for details.
