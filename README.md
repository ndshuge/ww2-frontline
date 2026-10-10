# 西线前线 · WW2 Frontline

> **项目迁移公告（2026-10-10）**：此仓库作为历史版本保存。当前维护入口为 [西线前线](https://ndshuge.github.io/ndshuge-game/games/ww2-frontline/)，统一代码在 [新仓库](https://github.com/ndshuge/ndshuge-game/tree/main/games/ww2-frontline)。旧版本代码、历史记录与独立网页仍保留，不会强制跳转。

---


> 一款使用 Three.js 与原生 JavaScript 开发的浏览器二战题材 3D FPS 实验。

**[在线试玩 →](https://ndshuge.github.io/ww2-frontline/)**

## 项目内容

- 第一人称射击视角、武器射击反馈与战斗 HUD
- 血量、弹药、计时器、雷达、任务目标提示
- 敌人模型、语音与战斗音效
- 附带 `敌人模型图鉴.html` 作为可视化参考页面

## 本地启动

```bash
git clone https://github.com/ndshuge/ww2-frontline.git
cd ww2-frontline
python -m http.server 8000
```

浏览器打开 `http://localhost:8000/`。推荐 Chrome 或 Edge，需浏览器支持 WebGL。首次交互后浏览器可能才允许鼠标锁定与音效。

## 文件结构

```text
index.html        # 页面布局与战斗 HUD
game.js           # 游戏状态与玩法
three.min.js      # 本地 3D 渲染依赖
models/           # 模型与音频资源
敌人模型图鉴.html # 角色预览
```

## 维护和版权说明

需要进一步做跨设备操作测试、帧率验收与第三方资源的授权清点。仓库整体许可证尚待确认；请勿假定模型、音乐与其他素材自动允许二次分发。

问题反馈：[GitHub Issues](https://github.com/ndshuge/ww2-frontline/issues)。

## 安全与素材审查

[第三方依赖与音视频来源清单](docs/ASSET_PROVENANCE.md)
