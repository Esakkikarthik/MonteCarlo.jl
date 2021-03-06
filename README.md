# MonteCarlo.jl

[![](https://img.shields.io/badge/docs-latest-blue.svg)](https://crstnbr.github.io/MonteCarlo.jl/latest)
[![travis][travis-img]](https://travis-ci.org/crstnbr/MonteCarlo.jl)
[![appveyor][appveyor-img]](https://ci.appveyor.com/project/crstnbr/montecarlo-jl/branch/master)
[![codecov][codecov-img]](http://codecov.io/github/crstnbr/MonteCarlo.jl?branch=master)

[travis-img]: https://img.shields.io/travis/crstnbr/MonteCarlo.jl/master.svg?label=Linux+/+macOS
[appveyor-img]: https://img.shields.io/appveyor/ci/crstnbr/montecarlo-jl/master.svg?label=Windows
[codecov-img]: https://img.shields.io/codecov/c/github/crstnbr/MonteCarlo.jl/master.svg?label=codecov

This is a package for numerically simulating physical systems in Julia. The purpose of this package is to supply efficient Julia implementations of Monte Carlo flavors for the study of physical models of spins, bosons and/or fermions. Examples that ship with the package are

* Ising spin model simulated by Monte Carlo
* Fermionic Hubbard model simulated by variants of determinant quantum Monte Carlo

In Julia REPL:
```julia
Pkg.clone("https://github.com/crstnbr/MonteCarlo.jl")
using MonteCarlo
```

Look at the [documentation](https://crstnbr.github.io/MonteCarlo.jl/latest/) for more information.

## Authors

* Carsten Bauer ([github](https://github.com/crstnbr))
