# What is GameChain?

在以太坊的代码里，实现了一套PoA算法，主要用于开发和测试网络使用，也很多人拿来做侧链，BSC就是用里这套现成的PoA算法，只有经过中心化授权的节点才允许参与出块。

Gamechain共识算法是在 go-ethereum v1.10.12 代码基础上进行二次开发的，把PoA算法改成了以主节点为单位的PoS算法，不需要授权，只要运行Gamechain节点，质押 10000 GAM 即可成为一个主节点参与出块。质押币存储在主节点合约，随时可以取回，节点服务器上不会存储用户的币和私钥，保障资产安全。
