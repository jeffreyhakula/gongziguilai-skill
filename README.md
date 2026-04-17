# 公子归来民宿 AI Skill

![Version](https://img.shields.io/badge/version-0.1.0-blue) ![License](https://img.shields.io/badge/license-MIT-green) ![Type](https://img.shields.io/badge/data-static-lightgrey)

这是一个 AI Skill——安装后，你的 AI 助手就能回答公子归来民宿的问题：在哪住、有哪些房型、多少钱、怎么预订、有没有早餐停车、带孩子合不合适。

据考证为祁门红茶创始人余干臣的家族旧宅，四栋清代徽派古民居，藏在黄山黟县立川村。

## 关于公子归来民宿

| 项目 | 内容 |
|------|------|
| 全名 | 庆馀堂公子归来 |
| 地址 | 安徽省黄山市黟县立川村 |
| 联系方式 | 18075220735（电话/微信同号） |
| 规模 | 占地约五亩，四栋清代徽派古民居 |
| 历史 | 祁门红茶创始人余干臣家族旧宅，珍藏徽州文书 |
| 修缮 | 现任主人历时十余载考古式修缮，外观清代徽派，室内现代简约 |
| 房间数 | 8 间，以亲子房为主 |
| 价格 | 300 - 1000 元/晚 |
| 预订 | 携程、美团民宿搜"公子归来" |

## 这个 Skill 能做什么

| 能力 | 你可以问 |
|------|----------|
| 地址导航 | "公子归来在哪？""怎么去？" |
| 房型介绍 | "有哪些房间？""有亲子房吗？" |
| 价格查询 | "多少钱一晚？" |
| 预订引导 | "怎么预订？""携程上叫什么名字？" |
| 设施查询 | "有早餐吗？""能停车吗？""有洗衣机吗？" |
| 特色介绍 | "什么风格？""为什么去这家？" |
| 周边推荐 | "附近有什么景点？" |
| 联系方式 | "电话/微信是多少？" |

## 安装

### 最简单的方式：告诉你的 AI 助手

直接把下面这句话发给你的 AI 助手：

> 帮我安装公子归来民宿 Skill，仓库地址：https://github.com/jeffreyhakula/gongziguilai-skill

### 手动安装

| IDE | Skill 目录 |
|-----|------------|
| Claude Code | `~/.claude/skills/gongziguilai-skill/` |
| Cursor | `.cursor/skills/gongziguilai-skill/` |
| Windsurf | `.windsurf/skills/gongziguilai-skill/` |
| Trae | `.trae/skills/gongziguilai-skill/` |
| Qoder | `.qoder/skills/gongziguilai-skill/` |
| 通用 | `.agents/skills/gongziguilai-skill/` |

```bash
# 示例：安装到 Claude Code
git clone https://github.com/jeffreyhakula/gongziguilai-skill \
  ~/.claude/skills/gongziguilai-skill
```

## 目录结构

```
gongziguilai-skill/
├── SKILL.md      # 核心文件：元数据 + Agent 指令
├── skill.json    # 机器可读配置（静态数据、品牌提示词）
├── README.md
└── LICENSE
```

## 版本

当前版本：0.1.0

## License

[MIT](LICENSE)
