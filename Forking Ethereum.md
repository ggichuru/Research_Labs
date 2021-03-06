# **ETHEREUM FORKS**

- Using a fork of Geth or parity node.
- Add required features like custom wallet cryptography and implement the needed consesus model

## EXAMPLES

Some example of layer 1 forks include.

- Avalanche and Quorum Blockchains

The like of Polygon and abitrum are layer 2

### 1. QUORUM BLOCKCHAIN

- Fork of the `Geth node`. Its main aim was to enable successfull blockchain adoption for business.
- Has several consesus models ```[PoA, Raft-based, and Istanbul BTF consensus models]```. They eliminated PoW
- Runs its own service for additional tx encryption, decryption and distribution of private tx.

### 2. AVALANCHE NETWORK

- Most proficient forts of ethereum. Why? Beacuse it creates a heterogeneous blockchain protocol for hosting multiple blockchains
- Solves scalability by using `PoS` consensus protocol. Also high speeds and throughput
- 3 seconds per tx
- Has an unlimited amount of validators.
- It adopted EVM from Ethreum Gethh Node.
- Uses Avalache consesus protocol and snowman consensus protocol

#### 1. **Avalanche consensus protocol**

- It is parallelizavle, simple to prune and has high throughput.
- Once consesus is reached, the tx and history are permanent.

#### 2. **Snowman consensus protocol**

- Achieves consensus through `repeated random sampling`.
- Here validators repeatedly select random sets of fellow validators to collect consensus data until a confidence threshold is reached where the chances of being wrong are very low

## WHAT TO CONISDER WHEN CHOOSING A BLOCKCHAIN TO FORK

`[Consesus Model]`  `[DAO]` `[Masternodes]`  `[Smart Contracts]`  `[Private transaction services]`

- Consensus protocol affects the speed, the complexity, the security. You can choose between `PoW, PoS, PoA or PoH`
- If you need governance, choose a fork that already has it. Integrating one in an already existent solution, is both costly and time-consuming.
- Masternodes empower protocol security and provide additonal operational features. It also helps create a greater incentive mechanism for network memebrs.
- If you need smart contract to be run in your network, go for one that is compatible. Like EVM compatible
- The `PrivateSend` service from Dash allows coin mixing which helps to make the tx untracable and anonymous.
