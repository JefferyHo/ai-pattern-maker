# AI Pattern Maker

[English](README.md) | 简体中文

`ai-pattern-maker` 是一个 Codex skill，用于把灵感、关键词、主题或参考图转化为原创平面图案设计方向。

它会帮助 Codex 先理解灵感，再提供多个风格方向，然后输出图案概念、设计说明、图像生成提示词和实用风险提示。

## 适用场景

- 平面图案设计
- 纹样与视觉符号探索
- 表面图形设计
- 海报、服装、包装、贴纸、徽章、社交媒体视觉概念
- 大师或设计流派风格参考选择
- 原创图案的图像生成提示词
- 作品名称与设计理念撰写

## 30 秒开始

```bash
npx skills add https://github.com/JefferyHo/ai-pattern-maker --skill ai-pattern-maker
```

也可以直接把这段话发给有 shell 权限的 AI Agent：

```text
帮我安装 ai-pattern-maker。请把 https://github.com/JefferyHo/ai-pattern-maker 克隆到 ~/.codex/skills/ai-pattern-maker，安装完成后检查 SKILL.md、agents/openai.yaml、examples/example-request.md 是否存在。
```

已经安装过的话，用这段话更新：

```text
帮我更新 ai-pattern-maker。请进入 ~/.codex/skills/ai-pattern-maker 执行 git pull，然后告诉我当前最新 commit。
```

安装后直接对 Agent 说：

```text
帮我用 ai-pattern-maker，把“城市更新与未来生活”这个灵感发展成一套原创平面图案设计，先给我几个大师或流派风格参考方向。
```

## 注意事项

- 这个 skill 不包含私有客户案例、品牌资产或生成图片。
- 它不提供法律清理；风险提示只是实用设计建议，不是法律意见。
- 商用、比赛、客户项目或品牌敏感用途，仍然需要人工审核和必要的法律审核。
- 如果需要使用官方 logo、授权字体、品牌资产或第三方素材，请使用原始授权文件，并确认使用权限。
- 风格参考只作为设计史、流派和视觉语言参考，不应复制具体受保护作品、角色、logo 或在世艺术家的精确表达。

完整风险说明见 [LEGAL.md](LEGAL.md)。

## License

本项目使用 **Apache License, Version 2.0**。完整条款见 [LICENSE](LICENSE)。
