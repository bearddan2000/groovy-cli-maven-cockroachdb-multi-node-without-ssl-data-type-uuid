# groovy-cli-maven-cockroachdb-multi-node-without-ssl-data-type-uuid

## Description
Creates a small table `dog` that uses
an uuid data type.

A groovy maven build, that connects to 3 node cluster
cockroach database without ssl.

## Tech stack
- groovy
- maven
  - postgres drivers

## Docker stack
- cockroachdb/cockroach:v19.2.2
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- [Master node webui](http://localhost:8000)
- [Slave node 1 webui](http://localhost:8001)
- [Slave node 2 webui](http://localhost:8002)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Cockroach setup](https://github.com/s0rg/cockroach-compose)
