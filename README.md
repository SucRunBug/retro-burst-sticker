# 复古爆炸贴纸 Skill

把指定文字制作成红色椭圆、白色爆炸形与复古红色粗体字的透明贴纸，适合用于视频步骤提示、标题和标签。

![复古爆炸贴纸参考样式](retro-burst-sticker/assets/series-reference.png)

技能内附原始参考图和系列成品参考图。默认输出透明 PNG，可按需要调整文案、尺寸和构图。使用时需要能调用图片生成或编辑工具的环境。

## 安装到 Codex

在终端执行：

```bash
git clone https://github.com/SucRunBug/retro-burst-sticker.git
mkdir -p "$HOME/.codex/skills"
cp -R retro-burst-sticker/retro-burst-sticker "$HOME/.codex/skills/"
```

如果已有同名技能，请先备份，再安装。然后新建对话并输入：

```text
$retro-burst-sticker 文字是：第五步 发布上线
```

## 目录

- `retro-burst-sticker/SKILL.md`：风格规范与生成流程。
- `retro-burst-sticker/assets/`：风格参考图。
- `retro-burst-sticker/agents/openai.yaml`：技能的界面信息。
