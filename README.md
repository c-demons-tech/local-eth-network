# About project

The aim of repository is to set up ethereum network locally using Docker. Huge amount of works was taken from [medium article](https://medium.com/scb-digital/running-a-private-ethereum-blockchain-using-docker-589c8e6a4fe8)

## Requirements
* Knowledge related to Docker
* Theoretical knowledge about blockchain

## How to run

1. `docker-compose build` for create custom docker image to bootstrap ethereum network
2. `docker-compose up` for run the whole Ethereum network

## How to test

The file `Local blockchain.postman_collection.json` contains postman collection with requests in order to test Blockchain network