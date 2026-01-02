# 地铁冒险游戏 (Subway Adventure Game)

基于 Scratch 3.0 制作的地铁冒险游戏。

A subway adventure game made with Scratch 3.0.

## 游戏说明 (How to Play)

1. 在 [Scratch 官网](https://scratch.mit.edu/) 打开项目
   - 点击 "创作" (Create)
   - 选择 "文件" > "从电脑中上传" (File > Load from your computer)
   - 选择 `subway-adventure.sb3` 文件

2. 点击绿旗，然后按空格键开始游戏
3. 使用方向键控制角色移动:
   - ↑ 向上躲避
   - ↓ 向下躲避
   - ← 向左移动
   - → 向右移动

4. 收集金币增加分数（每个+10分）
5. 躲避人群障碍物（碰到会失去1条生命）
6. 成功躲避障碍物可获得+5分
7. 生命值为0时游戏结束

### Instructions (English)

1. Open the project at [Scratch website](https://scratch.mit.edu/)
   - Click "Create"
   - Select "File" > "Load from your computer"
   - Choose the `subway-adventure.sb3` file

2. Click the green flag, then press SPACE to start
3. Use arrow keys to control the character:
   - ↑ Move up to dodge
   - ↓ Move down to dodge
   - ← Move left
   - → Move right

4. Collect coins to increase score (+10 each)
5. Avoid crowd obstacles (touching loses 1 life)
6. Successfully dodging obstacles gives +5 points
7. Game ends when lives reach 0

## 游戏特性 (Features)

- 🚇 地铁站场景背景 (Subway station backdrop)
- 🧑 可控制的乘客角色 (Controllable passenger character)
- 💰 金币收集系统 (Coin collection system)
- 👥 人群障碍物 (Crowd obstacles)
- ❤️ 生命值系统（3条生命）(Life system - 3 lives)
- 📊 实时分数显示 (Real-time score display)
- 🎮 经典横版跑酷玩法 (Classic side-scrolling gameplay)

## 项目结构 (Project Structure)

### 角色 (Sprites)
- **Player**: 玩家角色（背包旅客）
- **Coin**: 可收集的金币
- **Obstacle**: 障碍物（人群/栅栏/闸机）
- **GameController**: 游戏控制器

### 变量 (Variables)
- **score**: 当前分数
- **lives**: 剩余生命值
- **level**: 当前等级
- **speed**: 游戏速度
- **gameOver**: 游戏结束标志

## 许可证 (License)

本项目遵循仓库的开源许可证 (GNU LGPL v2.1)
