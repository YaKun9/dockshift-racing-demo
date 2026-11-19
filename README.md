# Dockshift Racing Demo · 赛车俱乐部

一款在浏览器里运行的 3D 赛车试玩。第一条赛道「雨港环线」（Rainport Circuit）穿过雨夜的集装箱堆场、岸吊和滨水道路。选一辆车，和另外三位车手跑完三圈。

**[在线试玩](https://yakun9.github.io/dockshift-racing-demo/)**

## 怎么玩

在首页选择赛道和车型，点击「发车」。雨港环线单圈 3.06 km，比赛时可以从仪表查看实时车速、圈数和小地图。画面卡顿时可在首页调低画质。

| 操作 | 键盘 |
| --- | --- |
| 加速 | `W` / `↑` |
| 刹车 | `S` / `↓` |
| 左转 / 右转 | `A` / `D` 或 `←` / `→` |
| 手刹 | `Space` |

触屏设备可使用屏幕上的方向、油门、刹车和手刹按钮。更多操作见游戏内的「驾驶指南」。

## 本地运行

这是静态 Web Demo，不需要安装 npm 依赖或执行构建。在仓库根目录启动一个静态服务器：

```sh
python3 -m http.server 8000
```

然后在浏览器打开 <http://localhost:8000>。入口是 `index.html`，脚本、样式和模型资源位于 `assets/`。

## 制作与素材

- 作者：亚坤。3D 渲染使用 [Three.js](https://github.com/mrdoob/three.js)（MIT）。
- 部分车辆模型来自第三方，各自适用原素材许可。具体作者、来源、修改说明和许可链接见 [`index.html` 中的「车辆模型与制作署名」](./index.html)。
- 小米 SU7 Ultra 改编模型沿用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)；车辆商标归各自权利人。
