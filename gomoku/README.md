# 五子棋 (Gomoku / Five in a Row)

基于 Scratch 3.0 制作的五子棋游戏。

A Gomoku game made with Scratch 3.0.

## 游戏说明 (How to Play)

1. 在 [Scratch 官网](https://scratch.mit.edu/) 打开项目
   - 点击 "创作" (Create)
   - 选择 "文件" > "从电脑中上传" (File > Load from your computer)
   - 选择 `gomoku.sb3` 文件

2. 点击绿旗开始游戏
3. 点击棋盘上的交叉点放置棋子
4. 变量 "turn" 显示当前回合 (1=黑子, 2=白子)

### Instructions (English)

1. Open the project at [Scratch website](https://scratch.mit.edu/)
   - Click "Create"
   - Select "File" > "Load from your computer"
   - Choose the `gomoku.sb3` file

2. Click the green flag to start
3. Click on the board intersections to place pieces
4. The "turn" variable shows the current turn (1=Black, 2=White)

## 游戏规则 (Game Rules)

| 规则 Rule | 说明 Description |
|-----------|------------------|
| 棋盘大小 Board Size | 15×15 交叉点 / 15×15 intersections |
| 先手 First Move | 黑子先行 / Black moves first |
| 胜利条件 Win Condition | 横、竖或斜方向连成五子 / Get 5 in a row (horizontally, vertically, or diagonally) |

## 游戏特性 (Features)

- ♟️ 经典五子棋玩法 (Classic Gomoku gameplay)
- 🎯 15×15 标准棋盘 (Standard 15×15 board)
- ⚫ 黑白双方轮流下棋 (Alternating black and white turns)
- 📊 回合显示 (Turn indicator)
- 🏆 胜负判定 (Win detection)

## 项目结构 (Project Structure)

### 角色 (Sprites)
- **Board**: 棋盘背景
- **Piece**: 棋子（黑/白）
- **Controller**: 游戏控制器

### 变量 (Variables)
- **turn**: 当前回合 (1=黑子, 2=白子)
- **winner**: 获胜方

## 许可证 (License)

本项目遵循仓库的开源许可证 (GNU LGPL v2.1)
