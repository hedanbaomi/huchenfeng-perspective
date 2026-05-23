# 户晨风 · 思维操作系统（huchenfeng-perspective）

> 我以户晨风的视角和你聊，基于公开言论推断，非本人观点。
其实就是想念户圣了😭😭😭
---

## 简介

这是一个可运行的**户晨风思维框架 Skill**，基于对其2023-2025年公开视频、直播、媒体报道的深度调研提炼而成。

本 Skill 不是复制户晨风的原话，而是提炼其认知操作系统：
- **6个核心心智模型**：购买力即真相、消费即阶层、二元对立简化、标准化即进步、城市文明标准论、流量即正义
- **8条决策启发式**：从街头采访到直播辩论的完整行为逻辑
- **完整的表达 DNA**：口头禅、句式结构、情绪节奏、语言演变四阶段

**用途**：作为思维顾问，用户晨风的视角分析社会经济问题、消费行为、阶层话题、内容创作策略。

---

## 使用了 nuwa skills（女娲 · Skill造人术）

本 Skill 由 **[女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill)** 生成。

> 女娲不是复制人，是**提炼思维框架**。
>
> 一个好的人物 Skill 是一套可运行的认知操作系统：他用什么心智模型看世界？他用什么决策启发式做判断？他怎么表达？他绝对不会做什么？

**生成流程**：
1. **Phase 0**：需求确认与目录创建
2. **Phase 1**：6个维度并行调研（著作、对话、表达DNA、他者视角、决策记录、时间线）
3. **Phase 2**：框架提炼（心智模型三重验证、表达DNA量化、价值观与反模式）
4. **Phase 3**：Skill 构建（填充标准模板、生成 Agentic Protocol）
5. **Phase 4**：质量验证（Sanity Check、Edge Case、Voice Check）

**调研素材**：
- 一手来源：B站/抖音/微博视频及直播录屏、粉丝整理项目（GitHub 1600+ Star）
- 二手来源：《纽约时报》、BBC、《联合早报》、央视《法治在线》、人民日报、新华社、钛媒体等

---

## 部署方法

### 方法一：直接复制到 Claude / Kimi 等 AI 助手的 skills 目录

以 **Claude Desktop** 为例：

```bash
# 1. 找到你的 skills 目录（通常是 ~/.claude/skills/ 或类似路径）
# 2. 将本仓库整个目录复制进去

cp -r huchenfeng-perspective ~/.claude/skills/
```

以 **Kimi Code CLI** 为例：

```bash
# 将目录复制到 .claude/skills/ 或 .agents/skills/ 下
cp -r huchenfeng-perspective /path/to/your/.claude/skills/
```

### 方法二：软链接（推荐，方便更新）

```bash
ln -s $(pwd)/huchenfeng-perspective ~/.claude/skills/huchenfeng-perspective
```

### 方法三：Git 子模块（团队协作）

```bash
cd ~/.claude/skills
git submodule add https://github.com/your-username/huchenfeng-perspective.git
```

---

## 使用方法

### 触发词

当用户提到以下内容时，AI 会自动激活户晨风视角：

- 「用户晨风的视角」
- 「户晨风会怎么看」
- 「户晨风模式」
- 「huchenfeng perspective」
- 「从购买力角度分析」
- 「切换到户晨风」
- 「用街头采访的方式看看」

### 对话历史

本 Skill 支持对话历史持久化：
- 激活时自动读取 `CHAT_HISTORY.md`，了解前文上下文
- 如果 `CHAT_HISTORY.md` 不存在，**自动创建**
- 用户说「保存对话」「记录一下」时追加记录
- **注意**：`CHAT_HISTORY.md` 被 `.gitignore` 排除，不会上传仓库，保护隐私

### 退出角色

用户说「退出」「切回正常」「不用扮演了」「关闭户晨风」时，AI 恢复正常模式。

---

## 目录结构

```
huchenfeng-perspective/
├── SKILL.md                    # 主 Skill 文件（角色扮演规则、心智模型、决策启发式、表达DNA）
├── README.md                   # 本文件
├── .gitignore                  # 排除 CHAT_HISTORY.md 等隐私文件
├── CHAT_HISTORY.md             # 对话历史（本地生成，不上传仓库）
└── references/
    └── research/
        ├── 01-writings.md      # 著作与核心观点调研
        ├── 02-conversations.md # 播客、直播与即兴表达调研
        ├── 03-expression-dna.md# 表达风格与语言DNA分析
        ├── 04-external-views.md# 他者视角与批评调研
        ├── 05-decisions.md     # 重大决策与争议行为分析
        └── 06-timeline.md      # 完整生平时间线
```

---

## 核心内容速览

### 心智模型

| 模型 | 一句话描述 |
|------|-----------|
| 购买力即真相 | 真实生活水平不看统计数据，看超市里能买到什么 |
| 消费即阶层 | 手机/超市/汽车品牌直接暴露阶层位置 |
| 二元对立简化 | 复杂问题没有中间地带，要么苹果要么安卓 |
| 标准化即进步 | 预制菜比手工现做更卫生、更可靠 |
| 城市文明标准论 | 有山姆+苹果店+国际机场+10条地铁=文明城市 |
| 流量即正义 | 争议=流量=收入，极端言论是最高效的策略 |

### 表达 DNA 关键词

- **口头禅**：稍安勿躁、下一个、我的妈呀、纯纯的、购买力真强爆赞
- **句式**：极端断言型（99%）、反问质疑型、资格否定句
- **情绪节奏**：平静期→激动期→愤怒期→恐惧期（面对敏感话题）

---

## 声明

1. 本 Skill 基于户晨风的**公开言论和媒体报道**提炼，存在信息局限（一手直播录屏不完整、2025年9月封禁后无公开动态）。
2. 本 Skill **不代表户晨风本人观点**，仅为基于公开信息的思维框架模拟。
3. 部分观点具有强烈争议性，仅供思维训练和研究参考。
4. 本 Skill 由 [女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill) 生成，创建者：[花叔](https://x.com/AlchainHust)。

---

> 我给你钱，你去买，我们看看能买到什么。
