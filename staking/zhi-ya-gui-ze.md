# 质押规则



* 合约地址：0x1111111111111111111111111111111111111111
* 合约代码：[contracts/masternode/contract/masternode.sol](https://github.com/rolong/mychain/blob/main/contracts/masternode/contract/masternode.sol)
* 节点合约是一个特殊的合约，在构建创世块（0区块）时进行初始化，并写入21个创世节点。
* 创世节点的初始质押币为0，创世节点的挖矿收益直接进入质押池，直至质押币数量达到最大值。
