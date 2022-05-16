# Advanced Sample Hardhat Project
Structure scripts to: 

smart contract 0xA6095460053275317b0B4316A134BB0F581cAb8f deploy on ropsten, owner 0xAf4aA595aC49d5bCba5df3d3Fe122f322631e4E7

- Deploy

deployment2.ts
txhash 0x4a4d6a46538d6ceeb46b17bdbc3040d6b088c81eb7f93ae11b11a317ce757e3e

- Query proposals

- Give vote right passing an address as input

giveVotingRights.ts
txhash 0x9b84d88584a872281893f92769fe0fa98f6f34d8576f809dac93769b8f706d75

- Cast a vote to a ballot passing contract address and proposal as input and using the wallet in * environment

castVote.ts
txhash 0x34467962707e6be7114657b73b94c5cd1a001f7e3d699d01270ac1608bfb78f7

- Delegate my vote passing user address as input and using the wallet in environment

txhash: 0xb634cf6f2a70824ea2760e7ddbf57c8ee0ccf19395c81883ab93ba84c8491b6e

yarn run ts-node --files ./scripts/Ballot/delegateVote.ts 0xA6095460053275317b0B4316A134BB0F581cAb8f 0x63FaC9201494f0bd17B9892B9fae4d52fe3BD377

Using address 0x1d2E7324a49C54e26b33E580b74524AFE8Db3e6c
Wallet balance 2.9870123689440207
Attaching ballot contract interface to address 0xA6095460053275317b0B4316A134BB0F581cAb8f
Delegate to vote to 0x63FaC9201494f0bd17B9892B9fae4d52fe3BD377



- Query voting result and print to console
queryVotingResult.ts



