# Review of Alastria Networks

There are two type of major networks under **Alastria**

- Alastria Red-T (Quorum technology)
- Alstria Red-B Network - this one is the one which is proposed in our framework
  - IBFT 2.0 Consensus Algorithm
  - Based on Hyperledger Besu Technology

## Setting up of Alastria Red-B Network

This requires two steps:

1. Installation & configuration based on the given steps using Docker
2. Get permissioned before using Alastria Network - this requires an electronic form to be filled and submitted.

## System Requirement:

- We need to have dedicated storage for node database which should be independent from the system database:
- OS - Ubuntu, and other Linux distributions
- Hosting: **Euro Zone; in order to complain with GDPR directives** _this means that we should have the development environment setup somewhere in this region with any cloud service such as AWS, Azure)_
- Docker and docker-compose should installed in the system
- The system should have CPU's minimum of 2GB and 4GB desired
- Memory of minimum of 4GB and recommended 8GB
- Hard Disk of minimum of 64GB and recommended of 256GB -- SSD Type

## Monitoring tools

- We can utilize **Grafana** and **Prometheus**; these are the monitoring tool for any activity in our node.
- Access is restricted to allowed hosts

## Connecting to the Network

- We can use **JSON RPC** **GraphQL** or **WebSocket** to connect to the development tools

## Development tools

- We have option to choose from **Hardhat**, **Truffle**, or **Remix**.

# ALSTRIA IDENTITY

_SSI Implementation of the on Alastria Network_

> developed and tested for Quorum (Geth) on the Alastria Red-T network.

If we are going to use the existing built-in SSI technology, perhaps we may need to rethink about the choice of the network as it is working only Alastria Red-T Network.

- they have Typescript Alastria Identity Library that we can utilize for our application in any specific use case.
