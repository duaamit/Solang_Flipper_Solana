# SolangonSolana

Baisc implementtaion of flipper contract using Solang. Solang can compile Solidity for Solana, Substrate, and ewasm. 
Solang is source compatible with Solidity 0.8.

Steps:

#Install Solang for Mac:

```
brew install hyperledger-labs/solang/solang
```

#build using below command to produce `flipper.abi` and `bundle.so`:

```
solang --target solana flipper.sol
```

#now run:
```
node flipper.js
```
