# NOR-诺尔生态协议

## 1. 引言

诺尔协议（NOR Protocol）旨在通过整合先进的奖励系统、模型和再投资策略，彻底革新区块链生态系统的运作方式。我们的目标是为数字经济提供一个无缝、可扩展且高效的系统。

我们将去中心化金融（DeFi）与智能合约相结合，利用区块链技术的优势，为用户提供安全、透明、高效的金融解决方案。
![资产流动](https://raw.githubusercontent.com/NORprotocol/NOR/main/images/asset_flow.png.png)
---

## 2. 协议系统概述

NOR协议系统是诺尔生态的核心。通过此系统，用户可以获得与其贡献程度相关的专属福利。不仅允许用户参与协议内部的活动，还能够通过推荐、团队合作等方式获得奖励。

### 会员权重及福利：

1. **空投会员**：注册并参与协议活动，享受基础奖励。
2. **正式会员**：通过更高的参与度，获得额外奖励，如分红和奖励。
3. **铸造会员**：复利资产以获得长期奖励，享受更高的回报率。

![会员系统](https://raw.githubusercontent.com/NORprotocol/NOR/main/images/membership_table.png)

---

## 3. 奖励与激励系统

### 3.1 推荐奖励

推荐奖励制度：旨在鼓励用户推荐新成员加入协议。用户根据推荐的业绩，获得不同层级的奖励。

![推荐奖励](https://raw.githubusercontent.com/NORprotocol/NOR/main/images/bonus_referral_table.png)

### 3.2 团队奖励

团队奖励制度：鼓励用户通过团队合作获得奖励，团队成员的表现将直接影响到整体团队的奖励。

![团队奖励](https://raw.githubusercontent.com/NORprotocol/NOR/main/images/bonus_team_table.png)

---

## 4. 资产流动与自动复投机制

资产流动与自动复投机制确保了协议的可持续性和资产的增值。用户SWAP70%资产提取到链上，30%资产自动加持铸造本金。

### 自动生息说明：

- 用户选择自动生息后，每日铸造的NOR将会被自动投入到生息池中，产生300%额外收益。
- 所有生息复利收益将以 **3倍收益** 的方式加速增长，确保长期稳定的回报。

![资产流动](https://raw.githubusercontent.com/NORprotocol/NOR/main/images/asset_flow.png.png)

---

## 5. 经济循环模型

诺尔协议的经济循环模型：通过智能合约控制市场的供应和需求，确保协议在长期内的稳定发展和持续盈利。模型包括资产的流动，复利、收益分配等多个环节。

### 经济循环模型细节：

1. **资金池的利用**：协议通过流动池的复利和增长，为用户提供持续回报。
2. **市场调整机制**：根据市场情况，智能合约会自动调整奖励机制和资产流动，确保市场的平衡和稳定。

![经济循环模型](https://raw.githubusercontent.com/NORprotocol/NOR/main/images/economic_cycle.png.png)

---

## 6. 代币经济学（Tokenomics）

代币经济学是诺尔协议设计中的关键因素之一。通过合理的代币发行、分配和流通机制，确保协议的健康运行和可持续发展。

### 代币分配说明：

- **种子投资者**：占总供应量的 20%。
- **团队与顾问**：占总供应量的 15%。
- **流动性奖励**：占总供应量的 40%。
- **平台发展基金**：占总供应量的 25%。

![代币经济学](https://raw.githubusercontent.com/NORprotocol/NOR/main/images/tokenomics.png.png)



---

## 7.NOR-（诺尔冒险岛屿）游戏（My Neighbor NOR Game）

**NOR 冒险岛屿**：结合时尚与奇幻，玩家将在虚拟世界中体验冒险，同时参与 **NFT 系统** 收集与交易独特的虚拟资产。

### 游戏机制：

- **NFT功能**：玩家可以购买、销售和交易 NFT，获得独家虚拟物品。
- **虚拟任务和奖励**：完成任务和挑战，获得丰厚奖励，提升游戏中的地位。

![游戏图片](https://raw.githubusercontent.com/NORprotocol/NOR/main/images/My_Neighbor_NOR_game_image.png.png)

---

## 8. 锁仓会员制度（Contract-Oriented Specification）

本章节从智能合约与协议逻辑的角度，详细描述诺尔锁仓会员体系。该系统完全独立于其他协议模块，提供高效且透明的用户体验。

铸造会员系统不依赖、不继承、不影响免费空投或付费空投逻辑，是一套完全独立运行的协议模块。

---

## 9. 用户流程图与总结

诺尔协议的用户流程图展示了用户如何从注册到投资，享受各种奖励机制。该流程简洁直观，帮助用户快速上手。

![用户流程图](https://raw.githubusercontent.com/NORprotocol/NOR/main/images/tokenomics.png)

---

## 10. NOR分账逻辑

当用户进行一次有效入金时，系统以 100% 同一基数进行一次性分账，具体如下：

### 分账比例：
| 模块  | 合约用途       | 分配比例 |
| ----- | -------------- | -------- |
| A     | 入金接收合约   | 100%     |
| B     | 协议营销与系统维护合约 | 5%      |
| C     | 内部 SWAP 与收益释放资金合约 | 80%      |
| D     | 外部流动性与底池支持合约  | 5%       |
| E     | 推荐奖励分配合约   | 6%-14%（平均10%） |

此表格展示了如何通过不同模块分配入金资金，确保协议的透明度，可持续性和公平性。

![NOR分账逻辑](https://raw.githubusercontent.com/NORprotocol/NOR/main/images/nor_division_logic.png)

