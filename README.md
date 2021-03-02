# TMFree (previously TMElide)
This repository contains code used to obtain the results of the paper submitted to IPDPS'20.

The repository is organized as follows:

* TMFree/ -- repository root.
  * clang/ -- modified version of Clang 6.0.1 with added support for TM and barrier elision.
  * llvm/ -- modified version of LLVM 6.0.1 with Transactify transformation passes.
  * benckmarks-and-libraries/ -- benchmarks used in the experimental evaluation.
    * stamp/ -- STAMP benchmarks.
    * libitm/ -- libitm runtime implementations.
    * scripts/ -- utility scripts to compile, execute and plot results.
