---
name: l0 sybil
about: Report Sybil Activity on LayerZero
title: "[Sybil Report]"
labels: under review
assignees: LayerZero-GH

---

# Reported Addresses  0x8366ac92e9adaae8d0e38f317517e844f5005f52

# Description The address cluster exhibits consistent behavior across multiple networks. For instance, in ZkSync, shortly after the first Ethereum deposit, it mints specific NFTs and simultaneously claims specific tokens. Transaction amounts across various interactions fall within a certain range, and random numbers are introduced via scripts across multiple networks, like 0.715843, 0.602623, and 0.613185. Additionally, there are numerous anomalous transactions, such as bridging from Optimistic rollup (op) to Arbitrum (arb), then back to op within a minute or two. Data is sourced from blockchain explorers.

# Detailed Methodology & Walkthrough：Taking ZkSync as an example, after the initial deposit of ETH, the address cluster swiftly interacts with the contract address 0x0bf0d6260fb4f4fc77b143eaff9e4fe51dd08c83. Almost simultaneously, it engages with 0x7d54a311d56957fa3c9a3e397ca9dc6061113ab3. Around the same time, it interacts with the contract address 0xa269031037b4d5fa3f771c401d19e57def6cb491, with transaction amounts ranging between 0.6 ETH to 0.8 ETH, also incorporating random numbers like 0.715843. Additionally, in the L0 protocol, within a specific time frame (one to two minutes), the cluster bridges between op-arb and arb-op with randomized transaction amounts, as seen in transaction 0xe385a77b51268ccc6f9eec8e4a98bcd68887d7e09852d45d3b265d5f093b0ad5. Therefore, I deduce that this address cluster is controlled by a single entity.

# Reward Address (If Eligible)
0x711930e4bdb064017d99a7145c0489247f61060a
