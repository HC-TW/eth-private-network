# Ethereum PoA private network
A Docker based implementation of blockchain network for testing and development purposes including:
- 1 Bootnode
- 2 Ethereum node
- 3 Ethereum miner nodes
- [Ethereum Network Status Dashboard](https://github.com/goerli/ethstats-server)

Using Proof-of-Authority consensus instead of Proof-of-Work.
New block creates every second.

## Prerequisites
You should have installed Docker and Docker Compose in your machine.

## Run
```bash
git clone https://github.com/HC-TW/eth-private-network.git
cd eth-private-network
docker-compose up
```

After all you can find:
- Ethereum Network Stats at [http://localhost:3000](http://localhost:3000)
- Node 1 RPC access at [http://localhost:8545](http://localhost:8545)
- Node 2 RPC access at [http://localhost:8546](http://localhost:8546)
- Node 3 (miner) RPC access at [http://localhost:8547](http://localhost:8547)
- Node 4 (miner) RPC access at [http://localhost:8548](http://localhost:8548)
- Node 5 (miner) RPC access at [http://localhost:8549](http://localhost:8549)
