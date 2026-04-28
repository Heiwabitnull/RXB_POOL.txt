Now Available Public Mining Pool

The RXB public mining pool is now open to all miners. 
Use any ASIC or GPU you have available. 
Every hash counts.

Pool address: 
stratum+tcp://135.181.255.219:3333

Worker: YOUR_RXB_LEGACY_ADDRESS
Password: x

Important: Please compile from source code only. Binaries are outdated and must not be used. The current source code version is v0.2.0.
Latest source code: https://github.com/Heiwabitnull/rxb-core

To get a legacy address after compiling:
./rxb-cli getnewaddress "mining" legacy

CPU, GPU and small home ASICs are all welcome. Every miner and every node strengthens the network.

Quick start via daemon:
./rxbd -daemon
./rxb-cli startmining "YOUR_ADDRESS" 2

Alternatively connect your miner directly to the pool using the stratum address provided above. Please use ASIC or GPU.

Thank you for supporting RXB.

Heiwabitnull
