
# 1. bitcoin: a peer-to-peer electronic cash system

## 1.1 摘要

比特币是一种纯粹的点对点版本的电子支付方式，它无需第三方金融机构担保即可实现电子支付。

数字签名能够解决部分的问题，但是这解决不了重复支付的问题，如果仍然需要可信的金融机构来解决重复支付的问题，那么比特币的最大的优势将消失。


因此，我们基于点对点的网络提出一种解决重复支付问题的解决方案。

这个网络计算交易信息的哈希值并将其加入到一条持续的基于哈希运算的工作证明链中，形成一条记录，如果不重新做工作证明，那么这个记录的信息将难以被更改。

最长的一条链不仅仅作为事件序列的证明，也证明它是来自最大的cpu算力池。

只要网络当中大部分的cpu算力资源不被攻击者掌控，那么网络就会产生正常的链并且使攻击者的攻击无效。

网络本身需要最小化的数据结构。信息将以最佳的工作方式被广播，所有节点都可以自由地加入或者离开网络，节点接受最大的链最为证明，证明在它们离开网络的时候发生了哪些交易。

## 1.2 介绍

互联网上的商业几乎完全依赖金融机构作为可信的第三方来处理电子支付。在大部分交易中，这些系统都能够工作良好，但它任然具有基于信任模型的内在缺点。完全的不可改变的交易信息记录是不可能的，因为金融机构有能力私自将交易记录进行修改。这大大增加了交易的代价，限制了最小可实际交易的大小，并且切断了小型的偶然的交易的可能性。

我们需要的是基于加密证明而不是信任的电子支付手段。

交易信息在计算方面不可逆能够在真正避免销售者被诈骗，而常规的由第三方机构保管的方法能够简单的保护消费者。

# 2. ethereum： A SECURE DECENTRALISED GENERALISED TRANSACTION LEDGER

##  2.1 摘要

当与加密安全的交易结合时，区块链范例通过一些项目(尤其是比特币)展示了它的作用。每个这样的项目可以被视为去中心化的、在单个计算机资源上的简单应用。我们可以将此模式称为具有共享状态的事务单例机器。

# 3. making smart contracts smarter

## 3.1 摘要



