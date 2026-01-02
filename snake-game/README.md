# 贪吃蛇游戏 (Snake Game)

基于 Scratch 3.0 制作的经典贪吃蛇游戏。

A classic snake game made with Scratch 3.0.

## 游戏说明 (How to Play)

1. 在 [Scratch 官网](https://scratch.mit.edu/) 打开项目
   - 点击 "创作" (Create)
   - 选择 "文件" > "从电脑中上传" (File > Load from your computer)
   - 选择 `snake-game.sb3` 文件

2. 点击绿旗，然后按空格键开始游戏
3. 使用方向键控制蛇的移动:
   - ↑ 向上
   - ↓ 向下
   - ← 向左
   - → 向右

4. 吃到食物（红苹果）增加分数和蛇身长度
5. 撞到墙壁游戏结束

### Instructions (English)

1. Open the project at [Scratch website](https://scratch.mit.edu/)
   - Click "Create"
   - Select "File" > "Load from your computer"
   - Choose the `snake-game.sb3` file

2. Click the green flag, then press SPACE to start the game
3. Use arrow keys to control the snake:
   - ↑ Up
   - ↓ Down
   - ← Left
   - → Right

4. Eating food (red apple) increases score and snake length
5. Hitting the wall ends the game

## 游戏特性 (Features)

- 🎮 经典贪吃蛇玩法 (Classic snake gameplay)
- 🍎 随机出现的食物 (Randomly spawning food)
- 📊 实时分数显示 (Real-time score display)
- 🚧 边界碰撞检测 (Wall collision detection)
- 🐍 蛇身跟随移动 (Snake body follows head)

## 项目结构 (Project Structure)

### 角色 (Sprites)
- **Snake Head**: 蛇头，响应玩家方向键控制
- **Snake Body**: 蛇身，跟随蛇头移动
- **Food**: 食物（红苹果），随机出现
- **GameController**: 游戏控制器

### 变量 (Variables)
- **score**: 当前分数
- **direction**: 蛇的移动方向
- **gameOver**: 游戏结束标志

## 游戏规则 (Game Rules)

| 规则 Rule | 说明 Description |
|-----------|------------------|
| 控制方式 Controls | 方向键 / Arrow keys |
| 得分方式 Scoring | 吃到食物 +1 / Eat food +1 |
| 结束条件 Game Over | 撞到墙壁 / Hit the wall |

## 许可证 (License)

本项目遵循仓库的开源许可证 (GNU LGPL v2.1)
