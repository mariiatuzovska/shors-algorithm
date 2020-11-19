# shors-algorithm

Shor's algorithm can be thought of as a hybrid algorithm. The quantum computer is used to perform a computationally hard task known as period finding. The results from period finding are then classically processed to estimate the factors.

## Useful links

* [Shors algorithm](https://docs.microsoft.com/en-us/quantum/user-guide/libraries/standard/applications#shors-algorithm)
* [Original integer factorization git project](https://github.com/microsoft/Quantum/tree/main/samples/algorithms/integer-factorization)
* [Quantum Furier transform](https://docs.microsoft.com/en-us/quantum/user-guide/libraries/standard/algorithms#quantum-fourier-transform)
* [Quantum phase estimation](https://docs.microsoft.com/en-us/quantum/user-guide/libraries/standard/algorithms#quantum-phase-estimation)

## how I create a Q# project

0. Init dotnet's Q# project:

`dotnet new console -lang Q#`

1. Build project:

`dotnet build`

2. Run:

`dotnet run --number 437 --use-robust-phase-estimation true`