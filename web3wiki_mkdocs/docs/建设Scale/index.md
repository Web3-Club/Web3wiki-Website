# 建设scale
由于区块链内置的每秒交易 (TPS) 数量有限，因此出现了许多替代机制和技术来帮助扩展区块链 dApp。

## 状态和支付渠道
状态通道是指用户直接在区块链之外或“链下”进行交易的过程，并大大减少了他们对“链上”操作的使用。
                
### 状态通道基础
[The Basics of State Channels](https://education.district0x.io/general-topics/understanding-ethereum/basics-state-channels/)

### 状态通道：链下交易简介
[State Channels: An Introduction to Off-chain Transactions](https://www.talentica.com/blogs/state-channels-an-introduction-to-off-chain-transactions/)

## Optimistic Rollups 和 Fraud Proofs
Optimistic rollups 是第 2 层 (L2) 结构，它通过将计算和数据存储移到链外来提高以太坊基础层的吞吐量和延迟。 乐观汇总处理以太坊主网之外的交易，减少基础层的拥塞并提高可扩展性。Optimistic rollups 允许任何人在不提供有效性证明的情况下发布区块。 然而，为了确保链条保持安全，optimistic rollups 指定了一个时间窗口，在此期间任何人都可以对状态转换提出异议。

### Optimistic Rollups 如何工作（完整指南）
[How Do Optimistic Rollups Work (The Complete Guide)](https://www.alchemy.com/overviews/optimistic-rollups)

## 零知识汇总和零知识证明
零知识汇总 (ZK-rollups) 是第 2 层扩展解决方案，可通过将计算和状态存储移至链外来提高区块链的吞吐量。
                
### 零知识汇总 - 以太坊
[Zero-Knowledge Rollups - Ethereum](https://ethereum.org/en/developers/docs/scaling/zk-rollups)

### 什么是 zk-SNATRK ，以及 zk-SNARK 是怎么运作的
[Why and How zk-SNARK Works](https://medium.com/@imolfar/why-and-how-zk-snark-works-1-introduction-the-medium-of-a-proof-d946e931160)

### zk-SNARK 简介
[Introduction to zk-SNARKs](https://vitalik.ca/general/2021/01/26/snarks.html)
        
## Validium
Validium 是一种扩展解决方案，它使用诸如 ZK-rollups 之类的有效性证明来强制执行交易的完整性，但不会将交易数据存储在以太坊主网上。 虽然链下数据可用性带来了权衡取舍，但它可以带来可扩展性的巨大改进。
                
### Validium - 以太坊
[Validium - Ethereum](https://ethereum.org/en/developers/docs/scaling/validium/)

## Plasma 
Plasma 是一个框架，它允许创建使用以太坊主链作为信任和仲裁层的子区块链。 在 Plasma 中，可以设计子链以满足特定用例的要求，特别是那些目前在以太坊上不可行的用例。
                
### Plasma 链 - 以太坊
[Plasma Chains - Ethereum](https://ethereum.org/en/developers/docs/scaling/plasma/)
        
## Sidechains
Sidechains是一个独立的区块链网络，通过双向挂钩连接到另一个区块链——称为父区块链或主网。
                
### Sidechains - 以太坊
[Sidechains - Ethereum](https://ethereum.org/en/developers/docs/scaling/sidechains/)

### Sidechains简介
[An Introduction to Sidechains](https://ethereum.org/en/developers/docs/scaling/sidechains/)