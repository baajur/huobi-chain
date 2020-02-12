# 测试网信息

## 测试网节点 IP 地址和端口

该测试网由 %%% 个节点组成，各节点的 ip 地址和端口如下：

```
node 1:
node 2:
node 3:
```

## 测试网经济模型

测试网在当前阶段并未设置原生代币。为防止停机问题的出现，测试网在链级别限制了每个区块的 `cycles_limit = %%%`, 用户发送交易时填写比这小的数值即可。

注：每个交易执行都会消耗 cycles(相当于 ETH 的 gas），cycles_limits 限制了每个区块所能包含的交易。