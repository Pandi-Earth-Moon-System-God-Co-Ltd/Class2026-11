# 🎮 Future Terraria

## 项目简介

Future Terraria 是一款基于 Phaser 3 + TypeScript 开发的 2D 沙盒生存游戏。

游戏背景设定在未来废土世界，玩家需要通过采集资源、挖掘矿石、制作装备、建造基地以及挑战机械 Boss 来生存与成长。

项目灵感来源于 Terraria，并结合未来科技与废土探索元素进行创新设计。

---

# 项目目标

开发一款具有完整核心玩法循环的沙盒游戏：

探索世界

↓

采集资源

↓

制作工具

↓

强化装备

↓

挑战 Boss

↓

解锁新区域

---

# 核心功能

## 世界系统

- 方块地图
- 地形生成
- 矿石生成
- 挖掘与放置方块

## 玩家系统

- 移动
- 跳跃
- 重力
- 生命值管理

## 背包系统

- 物品管理
- 装备管理
- 快捷栏

## 战斗系统

- 敌人 AI
- 武器攻击
- Boss 战斗

## 建造系统

- 放置方块
- 基地建设

---

# 技术栈

| 技术 | 用途 |
|--------|--------|
| TypeScript | 游戏逻辑开发 |
| Phaser 3 | 游戏引擎 |
| Vite | 项目构建 |
| GitHub | 版本管理与协作 |
| VS Code | 开发环境 |

---

# 项目结构

```text
src/

├── scenes/
│   └── GameScene.ts
│
├── world/
│   ├── World.ts
│   ├── Block.ts
│   └── WorldGenerator.ts
│
├── player/
│   ├── Player.ts
│   ├── PlayerController.ts
│   └── PlayerStats.ts
│
├── enemy/
│   ├── Robot.ts
│   ├── EnemyManager.ts
│   └── Boss.ts
│
├── inventory/
│   └── Inventory.ts
│
├── item/
│   ├── Item.ts
│   └── Recipe.ts
│
├── ui/
│   ├── Hud.ts
│   ├── MainMenu.ts
│   └── InventoryUI.ts
│
└── main.ts
```

---

# 团队分工

| 成员 | 模块 | 主要负责内容 |
|--------|--------|--------|
| 成员1 | 世界系统 | 地图生成、方块系统、矿石生成 |
| 成员2 | 玩家系统 | 移动、跳跃、生命值 |
| 成员3 | 敌人系统 | AI、战斗、Boss |
| 成员4 | 背包系统 | 物品、装备、合成 |
| 成员5 | UI系统 | 菜单、HUD、界面交互 |

---

# 开发计划

## 第一阶段（基础框架）

- [x] 项目初始化
- [x] Phaser环境搭建
- [x] 玩家生成
- [x] 基础移动

## 第二阶段（世界系统）

- [ ] 世界数组
- [ ] 方块地图
- [ ] 地形生成
- [ ] 挖矿系统

## 第三阶段（核心玩法）

- [ ] 背包系统
- [ ] 放置方块
- [ ] 合成系统
- [ ] 装备系统

## 第四阶段（战斗）

- [ ] 敌人 AI
- [ ] 武器系统
- [ ] Boss 战斗

## 第五阶段（发布准备）

- [ ] 存档系统
- [ ] 角色自定义
- [ ] BUG 修复
- [ ] 试玩测试

---

# Git 协作规范

## 分支管理

```text
main
develop

feature/world
feature/player
feature/enemy
feature/inventory
feature/ui
```

## Commit 规范

新增功能：

```text
feat: 添加世界生成系统
feat: 添加玩家移动
```

修复问题：

```text
fix: 修复跳跃判定错误
fix: 修复背包显示异常
```

文档更新：

```text
docs: 更新README
```

---

# 项目愿景

打造一款具有未来科技风格的 Terraria 类沙盒游戏。

开发过程中注重：

- 清晰的代码结构
- 良好的团队协作
- 模块化设计
- 可扩展性

最终实现一个能够在校内展示和试玩的完整作品。

---

© Future Terraria Team
