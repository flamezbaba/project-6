# Fair Trade Coffee Supply Chain

Prove the authenticity of coffee using the Ethereum blockchain.

## Project Write-Up

### UML Diagrams

[Activity Diagram](./uml/Activity%20Diagram.jpg)<br>
[Sequence Diagram](./uml/Sequence%20Diagram.jpg)<br>
[State Diagram](./uml/State%20Diagram.jpg)<br>
[Data Modelling](./uml/Data%20Modelling.jpg)<br>

### Libraries

**Truffle**: Used for developing, testing, and deploying my smart contracts

## Smart Contract

SupplyChain Tx hash: [0x40731a8662deafc5d826f8b9d233baa20d1f87f0cad5e39b097291e05536ea2e](https://rinkeby.etherscan.io/tx/0x40731a8662deafc5d826f8b9d233baa20d1f87f0cad5e39b097291e05536ea2e)<br>
SupplyChain Contract address: [0x68fa9A55F0ac1D02D9CDF5ccBf11aDCD76620527](https://rinkeby.etherscan.io/address/0x68fa9A55F0ac1D02D9CDF5ccBf11aDCD76620527)<br>

### Full Migrations Output

```
Starting migrations...
======================
> Network name:    'rinkeby'
> Network id:      4
> Block gas limit: 29970705 (0x1c95111)


1_initial_migration.js
======================

   Deploying 'Migrations'
   ----------------------
   > transaction hash:    0x35e0cce8bb8d4d2c8062f672c5800060d299eea85ee0333ac5bebfd81937e09d
   > Blocks: 1            Seconds: 18
   > contract address:    0xB5BFA6519c70098Cf627B994C6c2A2b1B8446396
   > block number:        9358935
   > block timestamp:     1632640873
   > account:             0x328f1d9F170d490035f57ffcf08146bb8166f621
   > balance:             18.701851147
   > gas used:            239894 (0x3a916)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00239894 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.00239894 ETH


2_deploy_contracts.js
=====================

   Deploying 'FarmerRole'
   ----------------------
   > transaction hash:    0x2ed4515c38f6e313e9bc51e4821a846b7b6eeefe896a85846aeb3e0243bb01c8
   > Blocks: 1            Seconds: 10
   > contract address:    0x42184DE8E62f2680EE59242CF32Ef91650241EAe
   > block number:        9358937
   > block timestamp:     1632640903
   > account:             0x328f1d9F170d490035f57ffcf08146bb8166f621
   > balance:             18.698249457
   > gas used:            314421 (0x4cc35)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00314421 ETH


   Deploying 'DistributorRole'
   ---------------------------
   > transaction hash:    0x0b55de472240424e79d386178461c1d60668903dc14caca06f37532070624263
   > Blocks: 0            Seconds: 0
   > contract address:    0x19385E3FCeeD520338708dF3aa7C22550b9E1DCe
   > block number:        9358938
   > block timestamp:     1632640918
   > account:             0x328f1d9F170d490035f57ffcf08146bb8166f621
   > balance:             18.694801047
   > gas used:            344841 (0x54309)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00344841 ETH


   Deploying 'RetailerRole'
   ------------------------
   > transaction hash:    0x935e3dbf7169d71710da0a8c7f5dc53181cc5142f7fddb7603cd04e7404f0895
   > Blocks: 2            Seconds: 32
   > contract address:    0x2a8766c14332C52e9899E00616c6fD6508Ec0fcD
   > block number:        9358939
   > block timestamp:     1632640933
   > account:             0x328f1d9F170d490035f57ffcf08146bb8166f621
   > balance:             18.691352877
   > gas used:            344817 (0x542f1)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00344817 ETH


   Deploying 'ConsumerRole'
   ------------------------
   > transaction hash:    0x9c6b6197ec7481a6117a7de946c870295156995bae2033ab5da6e16cfc7a9e16
   > Blocks: 1            Seconds: 5
   > contract address:    0x8aA42F481b0da8928E6AC0Cb38CC695a556a7E4a
   > block number:        9358944
   > block timestamp:     1632641008
   > account:             0x328f1d9F170d490035f57ffcf08146bb8166f621
   > balance:             18.687904827
   > gas used:            344805 (0x542e5)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00344805 ETH


   Deploying 'SupplyChain'
   -----------------------
   > transaction hash:    0x40731a8662deafc5d826f8b9d233baa20d1f87f0cad5e39b097291e05536ea2e
   > Blocks: 2            Seconds: 24
   > contract address:    0x68fa9A55F0ac1D02D9CDF5ccBf11aDCD76620527
   > block number:        9358946
   > block timestamp:     1632641038
   > account:             0x328f1d9F170d490035f57ffcf08146bb8166f621
   > balance:             18.663140507
   > gas used:            2476432 (0x25c990)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.02476432 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.03825316 ETH


Summary
=======
> Total deployments:   6
> Final cost:          0.0406521 ETH

```

## Development Notes

Truffle v5.0.31 (core: 5.0.31)<br>
Solidity v0.4.0 (solc-js)<br>
Node v10.16.0<br>
Web3.js v1.2.1<br>

