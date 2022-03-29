# Edited version of Keyston Enclave

This project is based on Keystone enclave, an open-source enclave framework for RISC-V processors.
The edited version comes from the need to have different requirements for my Thesis project.
All the differences from the original project will be described in the next section.

# Edited version of Keyston Enclave: Differences 

#1. The phase of Secure Boot (done in the bootrom) is now performing the hash of the SM and validating it with a golden value.


Documentation of Keystone Enclave in the next sections.

# Keystone: An Open-Source Secure Enclave Framework for RISC-V Processors

![Documentation Status](https://readthedocs.org/projects/keystone-enclave/badge/)
[![Build Status](https://travis-ci.org/keystone-enclave/keystone.svg?branch=master)](https://travis-ci.org/keystone-enclave/keystone/)

Visit [Project Website](https://keystone-enclave.org) for more information.

`master` branch is for public releases.
`dev` branch is for development use (up-to-date but may not fully documented until merged into `master`).

# Documentation

See [docs](http://docs.keystone-enclave.org) for getting started.

# Contributing

See CONTRIBUTING.md

# Citation

If you want to cite the project, please use the following bibtex:

```
@inproceedings{lee2019keystone,
    title={Keystone: An Open Framework for Architecting Trusted Execution Environments},
    author={Dayeol Lee and David Kohlbrenner and Shweta Shinde and Krste Asanovic and Dawn Song},
    year={2020},
    booktitle = {Proceedings of the Fifteenth European Conference on Computer Systems},
    series = {EuroSys’20}
}
```
