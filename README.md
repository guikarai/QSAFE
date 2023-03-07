# Building a Quantum-Safe dashboard on IBM zSystems

Quantum computers of a sufficient size will threaten the very basis of cryptography, rendering digital signatures and cryptographic protocols like TLS (HTTPS) insecure.

While nobody knows whether or when a sufficiently large quantum computer will exist, their impact would be immense, and the threat of harvesting encrypted data today for later decryption is very real. To be prepared today, IBM already provides quantum safe technology with the IBM zSystems® and LinuxONE systems. The IBM z16 system uses quantum safe methods inside its hardware and firmware to protect customer hardware investments against potential quantum threats. Starting with Crypto Express 7S, adapters in CCA or EP11 mode provide first versions of quantum-safe cryptographic algorithms accessible to Linux software.

IBM zSystems has been designed for not being an obsolete technology regarding the Quantum threat. Since decades, cryptographic activities performed by IBM zSystems and their applications can be accuratetly traced, logged, and analyzed thanks to the historical log systems in place.

This github entry to help to consume crypto based operational data and logs in order to create Quantum-Safe dashboards that matter to monitor, to follow, to track encryption activities at risk in the IBM zSystems and LinuxONE infrastructure.

## Architecture
## Included components
* [IBM zSystems](https://www.ibm.com/z)
* [LinuxONE](https://www.ibm.com/linuxone)
* [Quantum-Safe IBM zSystems](https://www.ibm.com/downloads/cas/G5NNXDOA)
* [z/OS Container Extension](https://www.ibm.com/support/z-content-solutions/container-extensions/)
* [System Management Facility (SMF)](https://www.ibm.com/docs/en/zos/2.1.0?topic=smf-abstract-mvs-system-management-facility)
* [Elastic](https://www.elastic.co/)
* [Github](https://github.com/linux-on-ibm-z/dockerfile-examples)
* [Docker](https://www.docker.com/)

## Steps
### Step 1 : Building required docker images for s390x
### Step 2 : Running Elastic stack on s390x processor architecture
* Creating docker network

We will make sure that Kibana and Elasticsearch are in the same isolated network, and that Kibana will attach to a user defined network (useful for connecting to other services (e.g. Elasticsearch)). If network has not yet been created, this can be done with the following command:
# $ docker network create somenetwork

* Starting Elasticsearch
* Starting Kibana with an alternate configuration yaml
* Connecting to Elasticsearch for the first time
* Connecting to Kibana for the first time
### Step 3 : Listing essential crypto operational data that matter for building a Quantum-Safe dashboard
### Step 4 : Feeding Elastic stack with Quantum-Safe operational data
### Step 5 : Building essential dashboards to exploit Quantum-Safe operational data
## To be beyond
