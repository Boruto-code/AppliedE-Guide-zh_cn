---
navigation:
  parent: appliede-index.md
  title: 转化设备
  icon: emc_interface
  position: 10
categories:
  - appliede
item_ids:
  - appliede:emc_interface
  - appliede:cable_emc_interface
  - appliede:emc_export_bus
  - appliede:emc_import_bus
  - appliede:learning_card
---

# 转化设备

<GameScene zoom="4" background="transparent">
  <ImportStructure src="assemblies/transmutation_devices.snbt" />
  <IsometricCamera yaw="195" pitch="30" />
</GameScene>

作为对 AE2 原版 <ItemLink id="ae2:interface" />、<ItemLink id="ae2:export_bus" />和<ItemLink id="ae2:import_bus" />的补充，AppliedE 提供了功能相近的专用设备。
这些设备与常规物品兼容，但关键区别在于：所有物品在操作时均会与 **EMC** 相互转化。

每个设备均可设置物品过滤，但仅当物品已被网络中至少一名玩家（通过 <ItemLink id="appliede:emc_module"></ItemLink> 追踪）学习时，设备才能执行相应功能。  
例如，<ItemLink id="appliede:emc_interface" />仅接受已学习且被网络识别的物品存入其内部存储以转化为 EMC；  
同理，<ItemLink id="appliede:emc_import_bus" />不会拉取未学习的物品。

## 炼金掌控卡

<ItemImage id="learning_card" scale="4" />

若每次自动化转化前都需手动学习物品，操作将十分繁琐。为此，可将 <ItemLink id="appliede:learning_card" />（炼金掌控卡）安装至 <ItemLink id="appliede:emc_interface" /> 或 <ItemLink id="appliede:emc_import_bus" /> 中，使设备自动学习输入的物品（需物品本身具有 EMC 值）。

需注意：物品的学习权限归属于设备所有者，即放置输入总线、接口或向接口发送物品的玩家。

## 合成配方

<Recipe id="appliede:emc_interface" />
<RecipeFor id="appliede:emc_export_bus" />
<RecipeFor id="appliede:emc_import_bus" />
<RecipeFor id="appliede:learning_card" />
