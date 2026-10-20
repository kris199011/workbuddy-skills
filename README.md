# WorkBuddy Skills

个人沉淀的 WorkBuddy 技能库（Skill），共 14 个申论方法论技能。
每个技能是一个独立文件夹，内含一个 `SKILL.md`，遵循 WorkBuddy 技能规范，可直接导入使用。

## 技能清单

| 技能 | 说明 |
|---|---|
| `bailu-shenlun-perspective` | 白鹭：申论思维框架，审题预判 / 材料阅读 / 四大题型 / 大作文 |
| `bud-shenlun-perspective` | BUD：广东申论思维操作系统与实战教学人格 |
| `dudu-shenlun-perspective` | dudu：广东省考申论解题体系与讲课风格 |
| `feiyang-shenlun-perspective` | 飞扬：申论作答体系与讲课风格 |
| `kiwi-shenlun-perspective` | Kiwi：申论全题型解题思维系统 |
| `lcl-perspective` | 李崇立：申论全题型方法论与批改思维 |
| `limengyuan-shenlun-perspective` | 李梦圆：申论解题体系（理论速览 + 国考精讲精练） |
| `tangdi-shenlun-perspective` | 唐棣：江苏申论教学方法论与解题思维 |
| `xianglijun-shenlun-perspective` | 相丽君：申论解题体系（解题思维集训营） |
| `xiaomage-shenlun-perspective` | 小马哥：申论思维操作系统与教学人格 |
| `yuandong-perspective` | 袁东（东哥）：申论思维操作系统，7 个心智模型 / 22 条决策启发式 |
| `zhangxiaolong-shenlun-perspective` | 张小龙：申论解题体系与讲课风格 |
| `zhongjun-shenlun-perspective` | 钟君：申论解题体系与讲课风格 |
| `zhoutairan-perspective` | 周泰然：申论全题型方法论与批改思维 |

## 目录结构

```
.
├── README.md
└── skills/
    ├── bailu-shenlun-perspective/
    │   └── SKILL.md          # YAML frontmatter + 正文方法论
    ├── kiwi-shenlun-perspective/
    │   └── SKILL.md
    └── ...（共 14 个技能目录）
```

每个 `SKILL.md` 顶部是 YAML frontmatter，`name` 与 `description` 决定技能的标识和触发时机：

```yaml
---
name: skill-name
description: 这个技能做什么、什么时候该用它（写好这里，模型才能正确触发）
---
```

## 如何安装

**方式一：界面导入（单个）**

WorkBuddy → 左侧「专家 / 技能 / 连接器」→ 技能 → 「导入技能」→ 选择技能文件夹或 ZIP。
注意一个 ZIP 只能装一个技能（解压后第一层必须是 `SKILL.md`）。

**方式二：整仓库批量安装（推荐）**

把本仓库地址交给 WorkBuddy 对话，说一句"把这套技能全装上"，它会批量拉取并注册。

**方式三：手动拷贝**

```bash
# macOS / Linux
cp -r skills/* ~/.workbuddy/skills/

# Windows (PowerShell)
Copy-Item -Recurse skills\* "$env:USERPROFILE\.workbuddy\skills\"
```

拷贝后重启 WorkBuddy 即可在技能列表中看到。

## 使用提示

这 14 个技能的方法论高度互补，但触发词（申论 / 批改 / 归纳概括 / 大作文）大量重叠。
同时安装时，提问建议点名老师以避免模型挑错，例如：

- "用袁东的方法分析这道题"
- "按白鹭的框架批改这份答案"
- "参考李崇立的批改思路"

## 声明

本仓库内容为 AI 学习与辅助工具的提示词整理，提炼自公开课程 / 讲义中的方法论，仅供个人学习参考，
与原作者本人无关，不代表其观点。相关内容的著作权归原作者所有，请勿用于商业用途。
