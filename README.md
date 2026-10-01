# codex-pets-七海nana7mi

小七海（七海 Nana7mi）风格的 Codex 桌宠，提供普通服和鲨鱼服两版。仓库仅包含桌宠成品、安装说明与两张预览动图。

| 普通服 | 鲨鱼服 |
| :---: | :---: |
| ![小七海普通服读书动作预览](previews/normal.gif) | ![小七海鲨鱼服读书动作预览](previews/shark.gif) |

读书动作循环预览；实际播放节奏以 Codex 客户端为准。

```text
xiaoqihai-normal/
  pet.json
  spritesheet.webp
xiaoqihai-shark/
  pet.json
  spritesheet.webp
```

## 安装

1. 点击 **Code → Download ZIP** 下载并解压。
2. 将 `xiaoqihai-normal`、`xiaoqihai-shark` 文件夹复制到 Codex 的 `pets` 目录：
   - Windows：`%USERPROFILE%\.codex\pets\`
   - macOS / Linux：`~/.codex/pets/`
   - 自定义了 `CODEX_HOME` 时，使用其下的 `pets/`。
3. 在 Codex **设置 → Pets** 中刷新，选择 **小七海·普通服** 或 **小七海·鲨鱼服**。

每个文件夹内的 `pet.json` 和 `spritesheet.webp` 需要同时保留。已有同名文件夹时先备份。

两版均为 v2 图集，包含九种动作状态和十六个视线方向。工作动作包含看书、翻页和拿笔思考；鲨鱼服的外露袖口为肤色人手。

帧率、循环方式和交互触发由 Codex 客户端控制。制作时核对的版本会在工作动画播放三轮后转为待机画面；修改宠物图片或 `pet.json` 不能改变这一播放策略。
