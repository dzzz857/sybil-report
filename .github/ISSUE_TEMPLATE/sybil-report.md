---
name: l0 女巫集群
about: Report Sybil Activity on LayerZero
title: "[Sybil Report]"
labels: under review
assignees: LayerZero-GH

---

# Reported Addresses  0x8366ac92e9adaae8d0e38f317517e844f5005f52

# Description 该地址集群在多个网络中交互行为一致例如zksync 中首次eth 充值后几分钟内会mint 特定的nft 且又在同一时间claim 特定代币，在多个交互金额在一个范围内，在多个网络中交易金额又通过脚本添加了随机数例如 0.715843  0.602623 0.613185 且存在大量异常交易 例如 op桥接到arb时 一两分钟又从 arb桥接回op 数据来源于区块浏览器

# Detailed Methodology & Walkthrough：以zksync为例 该地址集群在zksync 网络中首次充入 eth 后迅速与 0x0bf0d6260fb4f4fc77b143eaff9e4fe51dd08c83 该合约地址交互，在几乎同一时间 与 0x7d54a311d56957fa3c9a3e397ca9dc6061113ab3 进行交互，在几乎同一时间与：0xa269031037b4d5fa3f771c401d19e57def6cb491此合约交互且金额在 0.6eth到0.8eth之间 同样添加了随机数例如  0.715843 在 l0 协议中该集群在特定的时间范围内 进行一两分钟op-arb arb -op 的桥接金额添加随机数 tx： 0xe385a77b51268ccc6f9eec8e4a98bcd68887d7e09852d45d3b265d5f093b0ad5 因此我判断该地址集群由一家实体控制

# Reward Address (If Eligible)
0x711930e4bdb064017d99a7145c0489247f61060a
