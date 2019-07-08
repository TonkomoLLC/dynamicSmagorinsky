# dynamicSmagorinsky
Implementation of the dynamic Smagorinsky model as proposed by Lilly (1992) for OpenFOAM 6

The model compiles with OpenFOAM 7, but presently it has not been tested with OpenFOAM 7.

Based on:

[Alberto Passalacqua's](https://github.com/AlbertoPa/dynamicSmagorinsky) implementation for OpenFOAM 2.3.x

[syavash20's](https://github.com/syavash20/TurbLab) update of the above to OpenFOAM 4.1. Reportedly works with [OpenFOAM 5](https://www.cfd-online.com/Forums/openfoam-pre-processing/207719-dynamic-smagorinsky-model-how-implement.html), too.


The model presented in this repository works with OpenFOAM 6

The resulting library is "libdynamicSmagorinskyModel.so".  Add to controlDict in the usual way, and select "dynamicSmagorinsky" as the turbulence model.








