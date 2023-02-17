# Building a Quantum-Safe dashboard on IBM zSystems

Quantum computers of a sufficient size will threaten the very basis of cryptography, rendering digital signatures and cryptographic protocols like TLS (HTTPS) insecure.

While nobody knows whether or when a sufficiently large quantum computer will exist, their impact would be immense, and the threat of harvesting encrypted data today for later decryption is very real. To be prepared today, IBM already provides quantum safe technology with the IBM Z® and LinuxONE systems. The IBM z16 system uses quantum safe methods inside its hardware and firmware to protect customer hardware investments against potential quantum threats. Starting with Crypto Express 7S, adapters in CCA or EP11 mode provide first versions of quantum-safe cryptographic algorithms accessible to Linux software.

IBM zSystems has been designed for not being an obsolete technology regarding the Quantum threat. Since decades, cryptographic activities performed by IBM zSystems and their applications can be accuratetly traced, logged, and analyzed thanks to the historical log systems in place.

This github entry to help to consume crypto based operational data and logs in order to create Quantum-Safe dashboards that matter to monitor, to follow, to track encryption activities at risk in the IBM zSystems and LinuxONE infrastructure.

## Architecture
## Included components
## Steps
### Step 1 : Building required docker images for s390x
### Step 2 : Running Elastic stack on s390x processor architecture
### Step 3 : Feeding Elastic stack with Quantum-Safe operational data
### Step 4 : Building essential dashboards to exploit Quantum-Safe operational data
## To be beyond
