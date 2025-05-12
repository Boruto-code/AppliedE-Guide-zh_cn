---
navigation:
  parent: appliede-index.md
  title: 转化终端
  icon: transmutation_terminal
  position: 20
categories:
  - appliede
item_ids:
  - appliede:transmutation_terminal
  - appliede:wireless_transmutation_terminal
---

# 转化终端

<GameScene zoom="8" background="transparent">
  <ImportStructure src="assemblies/transmutation_terminal.snbt" />
</GameScene>

通过自动化合成与 [转化设备](transmutation_devices.md)，ME 网络已能实现 EMC 与物品的转换。  
但玩家如何直接操作网络中的 EMC？答案便是 **ME转化终端**——  
它将 ProjectE 的 <ItemLink id="projecte:transmutation_table" /> 功能集成至 ME 网络。

通过终端，玩家可直接从 EMC 存储中提取已知物品（无需预先存入实体），并可充/放卡莱恩能量之星等 EMC 容器。

![可转化物品示意图](diagrams/transmutable_item.png)
![卡莱恩星充能示意图](diagrams/klein_star_filling.png)

终端界面保留了转化桌的「火焰槽」用于物品转 EMC，并新增两个功能按钮：

![终端界面示意图](diagrams/terminal_ui.png)

- **箭头按钮**：切换 Shift-单击物品的流向。  
  ↑ 箭头：物品存入常规存储；  
  ← 箭头：物品转化为 EMC（同时自动学习未记录物品）。
  
- **奇点按钮**：一键学习存储中所有未记录物品。  
  **警告**：此操作会消耗至少一个对应物品（转化为 EMC），可能引发巨额能量消耗。  
  点击后将弹出 <ItemLink id="gui.appliede.are_you_sure">确认窗口</ItemLink>。

![确认窗口](diagrams/are_you_sure.png)

## 合成配方

<RecipeFor id="appliede:transmutation_terminal" />
