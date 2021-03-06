# Future

Future 是一个 Minecraft 跨版本 Mod 开发 API，或者说是开发框架。  
为什么还要造轮子？  
因为众所周知的原因，Minecraft Mod 在跨版本迁移的时候，通常会遇到巨大的麻烦，有时候甚至需要完全重写。  
所以很多版本迁移成本特别高，这也是很多 Mod，永远的停留在某一 Minecraft 版本的主要原因。

但是话说回来，又是因为众所周知的原因，很多 Minecraft 一般会同时存在很多个 "活跃" 的版本。  
作为一个 Mod 开发者的话，自然很希望自己的 Mod 能被更多人游玩。  
但是维护多个 Minecraft 版本的 Mod 几乎是一件不可能的工程。  
甚至高版本还有 Forge 和 Fabric 在对垒。  
而且啊，Mod 开发起来又极其复杂。  
所以啊，这就是我为什么想造这个轮子。

我将尽可能的保证开发尽量简单，尽量减少重复性劳动。  
为了尽可能的与其他 Mod 兼容，API 将在 Forge 与 Fabric 上构建实现，并尽可能的兼容其生态。

## API
下面是目前在设计中的 API，有其他需求可以在 issue 中讨论。  
API 将使用 Kotlin + Java 混合开发，并完全保证对 Java 的兼容。

- 方块
  - 方块
  - 方块物品
  - 方块实体
  - 方块掉落物 (实体)
- 物品
  - 物品
  - 物品栈
  - 物品掉落物 (实体)
- 数据存储API
- 世界
  - 世界
    - 矿物生成
  - 区块
- 实体
- 事件
- 通讯
- 配方
  - 标准合成配方
    - 有序合成
    - 无序合成
  - 标准熔炼配方
  - 机械配方
- GUI
- Mod 交互
  - 矿物词典
  - 流体词典
  - 能量API
- 与其他 Mod 交互
  - 与其他 Mod 交互
  - 与外部 Mod 交互