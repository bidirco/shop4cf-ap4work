# SHOP4CF Ap4Work

This repository holds instructions and the docker compose file to run a testing version of the Ap4Work component.

## Requirements

1. [Docker](https://www.docker.com/)
2. Available TCP ports: 8080, 5432, 9080, 9443, 1025, 1026

## Instructions

1. On a command line, open this directory
1. Run the command: `./services example`, or `./services ap4work`
1. Wait for the message '⚡ Ap4Work is now available!' and then navigate to: [http://localhost:8080](http://localhost:8080)

### Troubleshoot
1. Run the command: `./services logs`
