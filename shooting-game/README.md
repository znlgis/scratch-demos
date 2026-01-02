# 射击打靶游戏 (Shooting Target Game)

## 项目简介

这是一个基于 Scratch 3.0 的射击打靶游戏。玩家需要在限定时间内用鼠标点击移动的靶子来获得尽可能高的分数。

This is a shooting target game made with Scratch 3.0. Players need to click on moving targets with the mouse to score as many points as possible within the time limit.

## 游戏特性 (Features)

- 🎯 **瞄准系统**: 准星跟随鼠标移动
- 🎯 **Aiming System**: Crosshair follows mouse movement
- 🎪 **移动靶子**: 靶子随机出现在屏幕各处
- 🎪 **Moving Targets**: Targets appear randomly on screen
- ⏱️ **计时系统**: 30秒游戏时间限制
- ⏱️ **Timer System**: 30-second game time limit
- 📊 **得分系统**: 每击中一个靶子得10分
- 📊 **Scoring System**: Score 10 points per target hit
- 🏆 **最高分记录**: 记录历史最高分
- 🏆 **High Score**: Tracks your best score
- 🔊 **音效反馈**: 击中靶子时播放音效
- 🔊 **Sound Feedback**: Sound plays when hitting targets

## 使用方法 (How to Play)

### 1. 打开项目 (Open Project)

1. 访问 [Scratch 官网](https://scratch.mit.edu)
2. 点击"创作"进入编辑器
3. 选择"文件" → "从你的电脑中上传"
4. 选择 `shooting-game.sb3` 文件上传

**English:**
1. Visit [Scratch website](https://scratch.mit.edu)
2. Click "Create" to enter the editor
3. Select "File" → "Load from your computer"
4. Upload the `shooting-game.sb3` file

### 2. 开始游戏 (Start Game)

1. 点击绿旗 🚩 初始化游戏
2. 按 **空格键** 开始游戏
3. 移动鼠标瞄准靶子
4. **点击鼠标**射击靶子

**English:**
1. Click the green flag 🚩 to initialize
2. Press **SPACE** to start the game
3. Move mouse to aim at targets
4. **Click** to shoot targets

### 3. 游戏规则 (Game Rules)

| 规则 Rule | 说明 Description |
|-----------|------------------|
| 时间限制 Time Limit | 30秒 / 30 seconds |
| 得分 Score | 每个靶子10分 / 10 points per target |
| 目标 Goal | 在时间结束前获得最高分 / Get highest score before time runs out |

## 项目结构 (Project Structure)

### 角色 (Sprites)

| 角色名 Sprite | 功能 Function |
|--------------|---------------|
| Crosshair (准星) | 跟随鼠标移动的瞄准器 / Aiming cursor that follows mouse |
| Target (靶子) | 随机出现的射击目标 / Random shooting target |
| GameController | 控制游戏逻辑（不可见）/ Controls game logic (invisible) |

### 变量 (Variables)

| 变量名 Variable | 说明 Description |
|----------------|------------------|
| score (分数) | 当前得分 / Current score |
| timeLeft (剩余时间) | 游戏剩余秒数 / Remaining seconds |
| highScore (最高分) | 历史最高分 / All-time high score |
| gameRunning | 游戏是否运行中 / Whether game is running |

### 广播消息 (Broadcasts)

| 消息 Message | 用途 Purpose |
|-------------|--------------|
| startGame | 开始新游戏 / Start new game |
| gameOver | 游戏结束 / Game ended |
| hit | 击中靶子 / Target was hit |

## 游戏流程 (Game Flow)

```
点击绿旗 (Click green flag)
      ↓
显示提示 "按空格键开始游戏"
(Show "Press SPACE to start")
      ↓
按空格键 (Press SPACE)
      ↓
游戏开始，计时器倒计时
(Game starts, timer counts down)
      ↓
靶子随机移动，玩家点击射击
(Target moves randomly, player clicks to shoot)
      ↓
时间到，显示最终得分
(Time up, show final score)
      ↓
可以按空格键重新开始
(Press SPACE to play again)
```

## 技术细节 (Technical Details)

### 项目信息
- **Scratch 版本**: 3.0
- **文件格式**: .sb3
- **文件大小**: ~9 KB

### 核心逻辑

**准星跟随鼠标:**
```
当绿旗被点击
  显示
  移到最前面
  重复执行
    移到 (鼠标指针)
```

**靶子被点击:**
```
当角色被点击
  如果 <游戏运行中 = 1> 那么
    将 [分数] 增加 10
    播放声音 [pop]
    移到 x:(随机 -200 到 200) y:(随机 -140 到 140)
```

**计时器:**
```
当接收到 [开始游戏]
  重复执行直到 <剩余时间 < 1>
    等待 1 秒
    将 [剩余时间] 增加 -1
  广播 [游戏结束]
```

## 扩展建议 (Extension Ideas)

如果想进一步改进游戏，可以考虑：

1. 🎯 添加不同大小的靶子（小靶子分数更高）
2. 🚀 添加难度递增（靶子移动速度随时间加快）
3. 💥 添加击中特效动画
4. 🎵 添加背景音乐
5. 🏅 添加关卡系统
6. ⭐ 添加连击奖励
7. 🎨 添加更多靶子造型
8. 📱 优化移动端触摸操作

## 许可证 (License)

本项目遵循仓库的开源许可证 (GNU LGPL v2.1)。

## 贡献 (Contributing)

欢迎提交问题报告和改进建议！

---

🎮 **祝您游戏愉快！Have fun playing!** 🎯
