## Introduction

The goal of this project is to provide support for quantum-safe cryptography on Go SDK. With these, we then look into capturing different performance metrics to denote how viable post-quantum cryptography is in real-world applications.

Our project consists of 4 different components:
- qs509 Library
- Client Application
- Server Application
- Mininet Topologies

The qs509 library is used to provide Go functionality for post-quantum X.509 certificate generation and verification. This library is employed by the client and server applications to form a quantum-safe tunnel. With our tunnel, we use Mininet to test the performance on a variety of network configurations. 

## Requirements

This code has been run and tested using the following internal and external components

Environment
•	Ubuntu v20.04+
•	Docker Engine v25.0+
•   OpenSSL v3.3 (development)
•   OQS-provider v3.X
•   Mininet

Program
•	Go v1.20+
•	Python v3.11+

## External Deps

- Docker - Download latest version at https://www.docker.com/products/docker-desktop
- Git - Download latest version at https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
- Mininet - Download latest version at https://mininet.org/download/
- GitHub Desktop (Not needed, but HELPFUL) at https://desktop.github.com/

## Documentation

Our product and sprint backlog can be found in Jira, with organization name "L3Harris" and project name "Post Quantum Cryptography".

For exhaustive documentation on the system, please visit: https://github.com/CSCE482QuantumCryptography/turnover/tree/main/docs/conops

For exhaustive documentation on building, please visit: https://github.com/CSCE482QuantumCryptography/turnover/tree/main/docs/building

## Installation

For detailed instructions on installing our project, please visit: 
- Docker instructions: https://github.com/CSCE482QuantumCryptography/turnover/blob/main/docs/building/Build%20From%20Docker.pdf
- Build from Source: https://github.com/CSCE482QuantumCryptography/turnover/blob/main/docs/building/Build%20From%20Source.pdf

## Tests

To run unit tests, navigate towards qs509 and run with:

`go test -v -run Test_FunctionName`

For detailed instructions on conducting unit testing, visit: https://github.com/CSCE482QuantumCryptography/turnover/blob/main/docs/conops/Running%20Our%20Program.pdf

## Execute Code

For detailed instructions on running our code, please visit: https://github.com/CSCE482QuantumCryptography/turnover/blob/main/docs/conops/Running%20Our%20Program.pdf

## Environmental Variables/Files

If you built from docker, all environment variables have been set for you! If you chose to build from source, please follow instructions here: https://github.com/CSCE482QuantumCryptography/turnover/blob/main/docs/building/Build%20From%20Source.pdf

## CI/CD

This project does not require CI/CD as it is a standalone, local networking application. 

## Support

The support of this app has been officially closed. There is nothing more important left to develop. 

## Extra Help

Please contact Pauline Wade paulinewade@tamu.edu for any questions on the app.

## References ##

- https://mininet.org/