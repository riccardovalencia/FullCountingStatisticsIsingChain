# FullCountingStatisticsIsingChain

FullCountingStatisticsIsingChain contains the codes for reproducing the results contained in https://arxiv.org/abs/2005.01679.

The codes are written in C++, with taylored functions writte on top of the ITensor v2.1.0 library for tensor network methods.

## Descriptions

Contains C++ codes (src folder) for computing the dynamics of an Ising chain with transverse and longitudinal field, together with C++ codes for computing expectation values of observables of interest in post-processing.

The EXEC_ folders contains .sh file for launching simulations. Designed both for organizing data locally, or in a cluster based on PBS.

## Prerequisites
C++ ITensor v2.1.0 library: You need the ITensor v2.1.0 library to be installed. See the ITensor Installation Guide for details https://itensor.org/docs.cgi?vers=cppv3&page=install

If ITensor v2.1.0+ is used, it might be necessary to partially modify the syntax. As detailed in https://itensor.org/docs.cgi?vers=cppv3&page=upgrade2to3

C++11: This library requires a C++11-compliant compiler.


## Installation

Clone the repository:
```bash
git clone https://github.com/rvalencia1995/FullCountingStatisticsIsingChain.git
```

## Usage

Modify path to your ITensor library in order to compile via 'make' command the .cpp codes.

## License

[MIT](https://choosealicense.com/licenses/mit/)
