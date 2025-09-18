# The_magic_compressor

[Project proposal] (https://docs.google.com/document/d/1ENyeXnjHYGd9Sm9kyOUTWaT3NVKQS43ljHRGCcOJ80g/edit?tab=t.0#heading=h.3xohrz35ie05)

## Comp/decomp
1. develop a basic DPDK environment
2. add network layer configuration
3. develop basic state machine
4. develop ROHC + http handshake for
5. implement full ROHC context algorithm UDP then TCP
6. add to handshake comp support
7. add options for comp algo
8. add different compression algorithms
9. add simple encryption algo on the compressed data


## Simulator
1. develop a basic pcap simulator with scapy
2. add sending pcap files through comp and decomp


## REST API
1. create a simple rest api with a server and client
2. make simple logic of profile + comp algo request
3. develop simulation request from server to simulator
4. build JSON report of the analyzed data from the simulator
5. send it to frontend to display


## Database mongoDB
1. build a MongoDB server for saving reports
2. added queries for finding reports based on profile and comp algo
3. make comparison between reports logic - graphs / tables
4. add to client comparison request