---
navigation:
  title: "附属模组：AppliedE"
  position: 150
---

# AppliedE

<GameScene zoom="4" background="transparent">
  <ImportStructure src="assemblies/appliede.snbt" />
  <IsometricCamera yaw="195" pitch="30" />
</GameScene>

一款为 [*应用能源 2*](https://github.com/AppliedEnergistics/Applied-Energistics-2) 和 
[*ProjectE*](https://www.curseforge.com/minecraft/mc-mods/projecte) 设计的 Minecraft 联动模组，专注于强化两者的深度整合。  
与传统整合方式不同，AppliedE 将 ProjectE 的 **EMC** 转化为可通过 ME 网络独立管理的资源——  
支持实时显示、统计与操作，并允许通过应用能源的自动化合成设施及一系列新型设备直接调用炼金能量，按需将 EMC 转换为物品。

### 快速入门
你需要先制作一个 <ItemLink id="emc_module" />，并将其接入 ME 网络。  
此后，你的网络将能够通过专用存储系统调用炼金术知识与 EMC 资源，  
既支持自动化合成，也可通过 AppliedE 提供的全套[转化设备](transmutation_devices.md)实现高效物质转换。
