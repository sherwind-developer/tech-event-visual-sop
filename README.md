# Tech Event Visual SOP

一个用于技术活动、品牌延展物料和社区传播视觉资产生产的 Codex Skill。

它适合没有足够资深设计资源、但需要快速产出统一且高质量视觉物料的团队：先确定主视觉，再把活动信息结构化，最后用 AI/Figma/人工校对协作生成邀请函、议程图、嘉宾卡、公众号封面、长图海报和社媒传播图。

## What It Does

- 建立主视觉优先的视觉延展流程
- 规范活动 brief、嘉宾信息、议程、传播渠道与交付规格
- 生成海报、邀请函、议程图、嘉宾个人海报、公众号头图/次条图等物料清单
- 支持有主视觉、只有参考图、完全无设计资产三种起点
- 提供 WRC 开源具身智能论坛案例资产作为视觉 benchmark
- 提供策划/组织者可填写的 intake brief 模板

## Repository Structure

```text
.
├── SKILL.md
├── references/
│   └── workflow-details.md
└── assets/
    ├── brief-template/
    │   └── technical-event-visual-brief-template.md
    ├── signal-after-dark-case/
    │   ├── ASSET_INDEX.md
    │   ├── main-poster-3x4.svg
    │   ├── long-invite.svg
    │   ├── wechat-cover-pack.svg
    │   ├── agenda-card.svg
    │   ├── demo-project-cards.svg
    │   ├── speaker-portraits/
    │   └── previews/
    └── wrc-open-source-forum/
        ├── ASSET_INDEX.md
        ├── main-visual/
        └── speaker-cards/
```

## Install Locally

```bash
mkdir -p ~/.codex/skills
cp -R /path/to/tech-event-visual-sop ~/.codex/skills/tech-event-visual-sop
```

安装后，在 Codex 中提出“使用 tech-event-visual-sop 做活动视觉物料 / 海报 SOP / 品牌延展物料”等需求即可触发。

## Suggested Workflow

1. 填写 `assets/brief-template/technical-event-visual-brief-template.md`。
2. 判断是否已有高质量主视觉。
3. 锁定主视觉系统：构图、色彩、字体、光影、品牌露出和禁用元素。
4. 结构化活动信息：主题、时间地点、嘉宾、议程、CTA、渠道规格。
5. 批量延展物料：3:4 海报、长图、议程图、嘉宾卡、公众号封面、社媒图。
6. 进入 Figma 或同类协作工具分图层微调。
7. 做最终 QA：信息准确性、可读性、品牌一致性、各渠道裁切安全。

## Example Case: Signal After Dark

`assets/signal-after-dark-case/` 是一个完整的虚构测试案例，用来验证这个 skill 能否从简短 brief 延展出一套统一的技术活动视觉物料。

**测试 brief**

- 活动名称：Signal After Dark｜Tech Afterparty
- 活动类型：技术大会 afterparty / Demo & Networking
- 视觉方向：紫色 + 灰色科技感，夜间实验室、信号界面、builder 社交
- 虚构组织方：Nullbase Studio / Open Builders Club
- 虚构 Demo 项目：Orbit Agent Console、HoloHand Kit、MotionSeed Lab、Whisper Dock
- 关键输出：主海报、长图邀请函、公众号封面拼图、议程图、Demo 项目卡、4 位虚构嘉宾头像

**预览**

![Signal After Dark agenda preview](assets/signal-after-dark-case/previews/agenda-card.svg.png)

![Signal After Dark demo project preview](assets/signal-after-dark-case/previews/demo-project-cards.svg.png)

这个案例也暴露并补进了一个重要 QA 点：凡是生成 speaker/project portrait，必须确认 `头像资产存在`、`设计稿实际引用`、`预览渲染可见`、`头像不与文字重合`。

## Notes

`assets/wrc-open-source-forum/` 和 `assets/signal-after-dark-case/` 中的素材仅作为案例 benchmark 和流程参考。实际项目应替换为对应品牌授权素材与活动信息。
