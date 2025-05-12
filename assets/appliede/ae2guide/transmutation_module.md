---
navigation:
  parent: appliede-index.md
  title: 转化模块
  icon: emc_module
  position: 0
categories:
  - appliede
item_ids:
  - appliede:emc_module
---

# 转化模块

<GameScene zoom="8" background="transparent">
  <ImportStructure src="assemblies/transmutation_module.snbt" />
</GameScene>

**ME转化模块** 是 ME 网络操控 EMC 与炼金术的起点。将其接入网络任意位置后，模块将绑定放置者的炼金知识与 EMC 储量，使网络能够直接调用 EMC 进行自动化合成与转化操作。模块还会根据 EMC 等价原则，自动生成物品的合成配方。

![EMC存储示意图](diagrams/emc_storage.png)

同一网络中可放置多个模块（不同玩家所有），但每名炼金师仅有一个模块贡献 EMC 与可合成物品。  
多模块共存时，所有 EMC 将汇总为统一存储池，存取操作会按比例分配至各贡献者。

模块还引入了 **层级系统** 以防止 EMC 溢出：  
EMC 按 10^12 单位划分层级（不同层级以颜色区分），高阶 EMC 可按需拆分以应对复杂转化任务。

![EMC层级示意图](diagrams/emc_tiers.png)

默认能耗为 **25 AE/tick**（可通过配置文件配置）。

## 合成配方

<RecipeFor id="appliede:emc_module" />
