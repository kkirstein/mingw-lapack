# mingw-lapack

This projects contains the reference __LAPACK__ library with an adjusted `Makefile` for the mingw64 toolchain. It generates both static and shared variants of __LAPACK__.


## LAPACK

Currently, version 3.6.0 of the [LAPACK](http://www.netlib.org/lapack/index.html) library is used.


## BUILD & INSTALL

1. Check and edit if necessary `make.inc`

2. `make lib` (if you only need to build LAPACK not the included reference BLAS & CLBLAS)

3. Copy the generated library files (`liblapack.a`, `liblapack.dll.a` and `liblapack.dll`) to the desired folders.


## TODO

* add switches to compile for either `x86_64` or `i686` architecture.
* implement `make install`


## License

__LAPACK__ uses a modified BSD license. Details can be found [here](http://www.netlib.org/lapack/index.html#_licensing).

