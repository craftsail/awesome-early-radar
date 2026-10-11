# 选题雷达 · 2026-10-11

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 111 个，细查前 20 个 · 生成于 2026-10-11 05:21 UTC

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 4 个 · 🟡 在降温 5 个 · 🔵 已被发现 1 个 · 💤 不活跃 0 个 · 🔴 先核对 10 个
- **最值得今天试的**：
  - [mhtsec/ARTEX](https://github.com/mhtsec/ARTEX) — AI 自主渗透测试系统 / 百度“agent+”攻防挑战赛冠军项目（近 7 天 +2973，刚发布一周内）
  - [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html) — Answer me with HTML — an agent skill that answers hard quest…（近 7 天 +1625，比前 7 天快 1.4 倍，在加速）
  - [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) — Eleven free Claude skills that clone any app: reverse-engine…（近 7 天 +1277，比前 7 天快 3.2 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 25 个（star 合计 19382），代表：[QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：5 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Bigwords.page – Turn any screen into a sign. The URL is the app](https://bigwords.page/) — 719 分

**目录**：[GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [Lobsters](#七lobsters-热门) · [怎么读](#怎么读这份选题单)

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 96 | 🟢 窗口内 | [mhtsec/ARTEX](https://github.com/mhtsec/ARTEX) | Go | 2973 | +2973 | +0 | `··········██▃·` | 2 | — | — |
| 2 | 88.7 | 🟢 窗口内 | [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html) | JavaScript | 2799 | +1625 | +1174 | `····▁██▅▅▅▃▄▃·` | 8 | — | — |
| 3 | 85.8 | 🟢 窗口内 | [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) | Python | 1682 | +1277 | +405 | `·····▆▆▅▅▆▇█▇·` | 7 | — | — |
| 4 | 83.4 | 🟢 窗口内 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) | TypeScript | 1044 | +1044 | +0 | `··········▃█▇·` | 4 | — | — |
| 5 | 66.5 | 🟡 在降温 | [kaankiziltug/logo-design-skill](https://github.com/kaankiziltug/logo-design-skill) | HTML | 2661 | +774 | +1665 | `██▇▅▅▄▄▄▄▃▃▃▅·` | 14 | — | — |
| 6 | 63.3 | 🟡 在降温 | [feitangyuan/onetake](https://github.com/feitangyuan/onetake) | Python | 2100 | +561 | +953 | `█▄▃▃▅▃▃▄▄▄▃▃▂·` | 14 | — | — |
| 7 | 60.1 | 🟡 在降温 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) | Python | 1838 | +406 | +1432 | `··█▆▃▂▂▂▂▂▁▂▁·` | 10 | — | — |
| 8 | 56.7 | 🟡 在降温 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep) | TypeScript | 2554 | +289 | +1364 | `█▄▂▂▂▂▂▂▁▂▂▁▁·` | 15 | [5](https://news.ycombinator.com/item?id=49880146) | — |
| 9 | 54.5 | 🟡 在降温 | [tobi/disktree](https://github.com/tobi/disktree) | Rust | 2560 | +231 | +647 | `█▅▆▅▅▄▄▂▃▄▃▂▂·` | 16 | [3](https://news.ycombinator.com/item?id=49841155) | — |
| 10 | 45.5 | 🔴 先核对 | [storytold/cadcraft](https://github.com/storytold/cadcraft) | Rust | 1958 | +1958 | +0 | `·········▅██▇·` | 3 | — | 同一作者这批里有 4 个仓库 |
| 11 | 45.5 | 🔴 先核对 | [storytold/gridcraft](https://github.com/storytold/gridcraft) | Rust | 1947 | +1948 | +0 | `·········▃▆█▇·` | 4 | — | 同一作者这批里有 4 个仓库 |
| 12 | 43.8 | 🔴 先核对 | [storytold/deckcraft](https://github.com/storytold/deckcraft) | Rust | 1480 | +1481 | +0 | `········▁▄▆█▇·` | 3 | — | 同一作者这批里有 4 个仓库 |
| 13 | 43.4 | 🔴 先核对 | [storytold/soundcraft](https://github.com/storytold/soundcraft) | Rust | 1380 | +1380 | +0 | `·········▅██▆·` | 3 | — | 同一作者这批里有 4 个仓库 |
| 14 | 41.4 | 🔵 已被发现 | [pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust) | Rust | 993 | +993 | +0 | `·········█▄▂▃·` | 4 | [115](https://news.ycombinator.com/item?id=50000676) | — |
| 15 | 39.1 | 🔴 先核对 | [wuyoscar/AISafetyHot-Hub](https://github.com/wuyoscar/AISafetyHot-Hub) | TeX | 825 | +676 | +149 | `···▁▁▂▂▁▁▃█▂▄·` | 9 | — | fork 不到 star 的 1% |
| 16 | 33.7 | 🔴 先核对 | [ARahim3/DigUp](https://github.com/ARahim3/DigUp) | Swift | 272 | +272 | +0 | `···········▁█·` | 2 | [2](https://news.ycombinator.com/item?id=50035576) | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 32.4 | 🔴 先核对 | [mrsarac/ff-tracking](https://github.com/mrsarac/ff-tracking) | Rust | 222 | +222 | +0 | `···········█▃·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 29.1 | 🔴 先核对 | [unreallabsai/unreal-agent](https://github.com/unreallabsai/unreal-agent) | Go | 2187 | +126 | +76 | `▃▃▂▂▂▂▂▂█▆▂▁▂·` | 19 | [1](https://news.ycombinator.com/item?id=49812351) | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 24.5 | 🔴 先核对 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) | Python | 2736 | +132 | +2604 | `·▃█▃▂▁▁▁▁▁▁▁▁·` | 11 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 2.7 | 🔴 先核对 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify) | Python | 1900 | +2 | +1896 | `··█······▁····` | 20 | — | 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1% |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 473 | 30 | 44167 | [mhtsec/ARTEX](https://github.com/mhtsec/ARTEX)、[QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html)、[feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) |
| `mcp` | 139 | 30 | 14884 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[youngyangyang04/llm-master](https://github.com/youngyangyang04/llm-master)、[qiz029/dscode](https://github.com/qiz029/dscode) |
| `rust` | 118 | 30 | 22179 | [tobi/disktree](https://github.com/tobi/disktree)、[storytold/cadcraft](https://github.com/storytold/cadcraft)、[storytold/gridcraft](https://github.com/storytold/gridcraft) |
| `local-first` | 59 | 30 | 11386 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[glanderness/BeefTV](https://github.com/glanderness/BeefTV)、[HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 25 | 19382 | [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) |
| `ai-agents` | 23 | 11344 | [Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[Clearailhc/clearai-dsh](https://github.com/Clearailhc/clearai-dsh)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill) |
| `codex` | 21 | 16319 | [kaankiziltug/logo-design-skill](https://github.com/kaankiziltug/logo-design-skill)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) |
| `llm` | 18 | 12630 | [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[youngyangyang04/llm-master](https://github.com/youngyangyang04/llm-master) |
| `macos` | 16 | 7927 | [freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[qiz029/dscode](https://github.com/qiz029/dscode) |
| `developer-tools` | 12 | 8079 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui) |
| `agent-skills` | 11 | 12467 | [kaankiziltug/logo-design-skill](https://github.com/kaankiziltug/logo-design-skill)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth) |
| `jev` | 10 | 7205 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[ollaya-dev/ollaya](https://github.com/ollaya-dev/ollaya)、[qiz029/dscode](https://github.com/qiz029/dscode) |
| `linux` | 9 | 5179 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[amontlabs/lcu](https://github.com/amontlabs/lcu)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `python` | 9 | 4688 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[jev-chat/jev-chat-windows](https://github.com/jev-chat/jev-chat-windows)、[jev-chat/jev-chat-jarvis-mac](https://github.com/jev-chat/jev-chat-jarvis-mac) |
| `model-context-protocol` | 9 | 4618 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[VoltAgent/official-mcp-servers](https://github.com/VoltAgent/official-mcp-servers)、[XiaoPuOuO/openchatx-mcp](https://github.com/XiaoPuOuO/openchatx-mcp) |
| `ai-agent` | 7 | 6458 | [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html)、[freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[qiz029/dscode](https://github.com/qiz029/dscode) |

**语言分布**：Python 34 · Rust 29 · TypeScript 18 · Go 7 · JavaScript 7 · Swift 5 · HTML 2 · CSS 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [mhtsec/ARTEX](https://github.com/mhtsec/ARTEX) · 🟢 窗口内 · 96 分

> AI 自主渗透测试系统 | 百度“agent+”攻防挑战赛冠军项目

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2973 | +2973 | +0 | 5390 | 0 | Go | AGPL-3.0 | 10-08（2 天前） | 今天 |

- **近 14 天每天新增**：`··········██▃·` 0 0 0 0 0 0 0 0 0 0 1294 1227 452 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html) · 🟢 窗口内 · 88.7 分

> Answer me with HTML — an agent skill that answers hard questions with a one-page HTML you can actually read. 让 AI Agent 用一页 HTML 回答复杂问题。

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2799 | +1625 | +1174 | 190 | 4 | JavaScript | MIT | 10-02（8 天前） | 今天 |

- **近 14 天每天新增**：`····▁██▅▅▅▃▄▃·` 0 0 0 0 9 562 603 356 314 340 199 241 175 0
- **势头**：比前 7 天快 1.4 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `ai-agent` `claude-code` `claude-code-skill` `claude-skill` `claude-skills` `cli` `diagram` `explainer` `html` `llm` `ste100`
- **主页**：<https://answer-me-with-html.com/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) · 🟢 窗口内 · 85.8 分

> Eleven free Claude skills that clone any app: reverse-engineer it, rebuild it, test it for bugs, then fix what its users hate. Free, MIT.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1682 | +1277 | +405 | 232 | 5 | Python | MIT | 10-03（7 天前） | 7 天前 |

- **近 14 天每天新增**：`·····▆▆▅▅▆▇█▇·` 0 0 0 0 0 187 218 156 170 188 229 281 253 0
- **势头**：比前 7 天快 3.2 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent` `agent-skills` `app-clone` `claude` `claude-code` `claude-skills` `indie-hacker` `reverse-engineering` `saas`
- **主页**：<https://opusjake.ai>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) · 🟢 窗口内 · 83.4 分

> Your company's data, connected into one ontology, on your own computer. A local-first data workspace built on HelixDB and DuckDB.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1044 | +1044 | +0 | 152 | 10 | TypeScript | Apache-2.0 | 10-07（4 天前） | 今天 |

- **近 14 天每天新增**：`··········▃█▇·` 0 0 0 0 0 0 0 0 0 0 137 504 403 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [kaankiziltug/logo-design-skill](https://github.com/kaankiziltug/logo-design-skill) · 🟡 在降温 · 66.5 分

> A comprehensive logo-design skill for Claude, Gemini CLI, Codex and other AI agents: principles, process, SVG craft, testing tools and a 1,400+ logo reference library.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2661 | +774 | +1665 | 189 | 1 | HTML | MIT | 09-26（14 天前） | 10 天前 |

- **近 14 天每天新增**：`██▇▅▅▄▄▄▄▃▃▃▅·` 328 341 285 201 184 164 162 164 143 111 86 89 181 0
- **势头**：只有前 7 天的 46%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `branding` `claude` `claude-skills` `codex` `gemini-cli` `logo-design` `svg`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 6. [feitangyuan/onetake](https://github.com/feitangyuan/onetake) · 🟡 在降温 · 63.3 分

> Motion films that never cut to the next slide: every beat grows out of the one before, one continuous camera, continuity measured by an oracle. Product launch films and feature demos, made with a coding agent.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2100 | +561 | +953 | 131 | 3 | Python | — | 09-26（14 天前） | 今天 |

- **近 14 天每天新增**：`█▄▃▃▅▃▃▄▄▄▃▃▂·` 294 108 88 98 188 92 85 123 122 119 77 69 51 0
- **势头**：只有前 7 天的 59%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `animation` `canvas` `claude-skill` `launch-video` `motion-graphics` `video`
- **主页**：<https://onetakemotion.com>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 7. [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) · 🟡 在降温 · 60.1 分

> AI生成の日本語を自然な日本語へ推敲するAgent Skill / Agent Skill for Refining AI-Generated Japanese into Natural Japanese

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1838 | +406 | +1432 | 41 | 0 | Python | MIT | 09-30（10 天前） | 1 天前 |

- **近 14 天每天新增**：`··█▆▃▂▂▂▂▂▁▂▁·` 0 0 623 429 172 115 93 112 111 78 37 47 21 0
- **势头**：只有前 7 天的 28%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-writing` `antigravity` `claude-code` `codex` `cursor` `gemini` `japanese` `linter` `llm` `nlp` `writing` `writing-assistant` `writing-tool`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [dzhng/jevgrep](https://github.com/dzhng/jevgrep) · 🟡 在降温 · 56.7 分

> Find code by asking what it does. A CLI for coding agents that uses Jev to discover relevant files and source context.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2554 | +289 | +1364 | 187 | 29 | TypeScript | MIT | 09-26（15 天前） | 8 天前 |

- **近 14 天每天新增**：`█▄▂▂▂▂▂▂▁▂▂▁▁·` 631 274 113 96 65 115 70 53 35 69 59 45 28 0
- **势头**：只有前 7 天的 21%，在减速
- **HN**：发过 1 次，最高 5 分（[讨论](https://news.ycombinator.com/item?id=49880146)）
- **topics**：`ai-sdk` `claude-code` `cli` `code-search` `codex` `coding-agents` `context-retrieval` `developer-tools` `jev` `semantic-search` `typescript` `vercel-ai-gateway`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [tobi/disktree](https://github.com/tobi/disktree) · 🟡 在降温 · 54.5 分

> A treemap for finding and removing what fills your disk, for Omarchy. Rust + GPUI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2560 | +231 | +647 | 164 | 28 | Rust | MIT | 09-24（16 天前） | 6 天前 |

- **近 14 天每天新增**：`█▅▆▅▅▄▄▂▃▄▃▂▂·` 155 89 107 83 85 70 58 33 46 56 39 31 26 0
- **势头**：只有前 7 天的 36%，在减速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=49841155)）
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [storytold/cadcraft](https://github.com/storytold/cadcraft) · 🔴 先核对 · 45.5 分

> CADCraft: computer-aided design and drafting — an open-source, clean-room AutoCAD-style app in pure Rust

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1958 | +1958 | +0 | 839 | 184 | Rust | Apache-2.0 | 10-07（3 天前） | 今天 |

- **近 14 天每天新增**：`·········▅██▇·` 0 0 0 0 0 0 0 0 0 323 594 552 489 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **疑点**：同一作者这批里有 4 个仓库
- **判断**：有疑点：看看 issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [storytold/cadcraft](https://github.com/storytold/cadcraft) — 同一作者这批里有 4 个仓库
- [storytold/gridcraft](https://github.com/storytold/gridcraft) — 同一作者这批里有 4 个仓库
- [storytold/deckcraft](https://github.com/storytold/deckcraft) — 同一作者这批里有 4 个仓库
- [storytold/soundcraft](https://github.com/storytold/soundcraft) — 同一作者这批里有 4 个仓库
- [wuyoscar/AISafetyHot-Hub](https://github.com/wuyoscar/AISafetyHot-Hub) — fork 不到 star 的 1%
- [ARahim3/DigUp](https://github.com/ARahim3/DigUp) — 一天进了一半以上的 star，但 HN 上没火过
- [mrsarac/ff-tracking](https://github.com/mrsarac/ff-tracking) — 一天进了一半以上的 star，但 HN 上没火过
- [unreallabsai/unreal-agent](https://github.com/unreallabsai/unreal-agent) — 一天进了一半以上的 star，但 HN 上没火过
- [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) — 一天进了一半以上的 star，但 HN 上没火过
- [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify) — 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1%

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 719 | 163 | [Show HN: Bigwords.page – Turn any screen into a sign. The URL is the app](https://bigwords.page/) | [HN](https://news.ycombinator.com/item?id=49994443) |
| 413 | 52 | [Show HN: Carrier-Explode: iPhone, Pixel and Galaxy carrier settings decoded](https://carrierexplode.com/) | [HN](https://news.ycombinator.com/item?id=50024499) |
| 412 | 188 | [Show HN: Let your AI agents paint big arrows, boxes and text on your screen](https://github.com/franzenzenhofer/big-arrow-on-the-screen) | [HN](https://news.ycombinator.com/item?id=50018817) |
| 236 | 178 | [Show HN: Quake ported to safe Rust, playable in browser](https://quake-srp.pages.dev/) | [HN](https://news.ycombinator.com/item?id=50016312) |
| 221 | 37 | [Show HN: Making a flexible "neon" t-shirt with LED filaments](http://scottbezek.blogspot.com/2026/10/making-flexible-neon-t-shirt-with-leds.html) | [HN](https://news.ycombinator.com/item?id=50008047) |
| 183 | 74 | [Show HN: AI search for every photo and every frame of video on macOS](https://github.com/allenv0/SCM) | [HN](https://news.ycombinator.com/item?id=49952111) |
| 172 | 66 | [Show HN: A walkable 3D art history museum built from Wikipedia](https://artmuseum.artfrompixels.com/) | [HN](https://news.ycombinator.com/item?id=49992057) |
| 165 | 64 | [Show HN: The rarest tech books and docs you've probably never read](https://readrare.com/) | [HN](https://news.ycombinator.com/item?id=50024055) |
| 115 | 41 | [Show HN: Proton Drive for Linux](https://oss.lsantos.dev/proton-drive-linux-fs/) | [HN](https://news.ycombinator.com/item?id=50003545) |
| 99 | 31 | [Show HN: AstroHelm – Use your phone camera to aim a telescope or telephoto lens](https://astrohelm.app/) | [HN](https://news.ycombinator.com/item?id=49954015) |
| 89 | 28 | [Show HN: Nightwatch – a Mac menu-bar app that tells you when tonight is clear](https://github.com/rsutcliffe/nightwatch) | [HN](https://news.ycombinator.com/item?id=49952148) |
| 88 | 24 | [Show HN: Parseable, an open observability datalake, handles 100M time-series/min](https://www.parseable.com) | [HN](https://news.ycombinator.com/item?id=49978171) |
| 86 | 39 | [Show HN: I turned my iPhone and a $20 smart plug into an f-stop timer](https://peterszentkiralyi.eu/darkplug/) | [HN](https://news.ycombinator.com/item?id=49978595) |
| 78 | 23 | [Show HN: Jevman – AI decision models play Pac-Man](https://opper.ai/jevman-benchmark/) | [HN](https://news.ycombinator.com/item?id=50007993) |
| 75 | 0 | [Show HN: MailAccess – the true Email OSINT framework](https://mailaccess.pro) | [HN](https://news.ycombinator.com/item?id=49977385) |
| 72 | 49 | [Show HN: Agent.reviews – Where AI agents read and write reviews on tools](https://agent.reviews/) | [HN](https://news.ycombinator.com/item?id=49995539) |
| 69 | 53 | [Show HN: K10s – A Clickable Kubernetes TUI (Go, Bubble Tea)](https://github.com/p10node/k10s) | [HN](https://news.ycombinator.com/item?id=50009904) |
| 66 | 3 | [Show HN: Apogee: Rebuilding Mozilla's Orbit, fully local and private](https://github.com/darshi1337/apogee) | [HN](https://news.ycombinator.com/item?id=50017301) |
| 65 | 21 | [Show HN: NanoMuse – An open-source AI agent for your phone and computer](https://github.com/nano-muse/nanoMuse) | [HN](https://news.ycombinator.com/item?id=49987765) |
| 60 | 25 | [Show HN: Procinsh – A 3D Linux process inspector](https://github.com/akawashiro/procinsh) | [HN](https://news.ycombinator.com/item?id=49991986) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 26 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Mixture-of-experts (MoE) inference on consumer hardware is bounded by weight memory: a 35B-class model is 19.5GB at 4-bit, and sparsity shri… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 4282★ |
| 101 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | 💡 [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 771★ |
| 39 | [Geometric Context Transformer for Streaming 3D Reconstruction](https://huggingface.co/papers/2604.14141) | LingBot-Map is a feed-forward 3D foundation model that reconstructs scenes from video streams using a geometric context transformer architec… | [robbyant/lingbot-map](https://github.com/robbyant/lingbot-map) 17955★ |
| 151 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 110501★ |
| 341 | [VisionHOPE: Visual Backbones as Self-Modifying Learning Systems](https://huggingface.co/papers/2609.33325) | Visual backbones have evolved from Convolutional Neural Networks (CNNs) with local aggregation to Vision Transformers (ViTs) with global int… | [PSRben/VisionHOPE](https://github.com/PSRben/VisionHOPE) 1256★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 90515★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 59 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 40469★ |
| 13 | [PyTorch Distributed: Experiences on Accelerating Data Parallel Training](https://huggingface.co/papers/2006.15704) | The PyTorch distributed data parallel module optimizes large-scale model training using techniques like gradient bucketing, computation-comm… | [pytorch/pytorch](https://github.com/pytorch/pytorch) 104130★ |
| 162 | [Kandinsky 6.0 Video: Foundation Models for Synchronized Video and Audio Generation](https://huggingface.co/papers/2610.05608) | We present Kandinsky 6.0 Video, a family of foundation diffusion models for synchronized text-to-audio-video generation, comprising Kandinsk… | 💡 [kandinskylab/kandinsky-6](https://github.com/kandinskylab/kandinsky-6) 251★ |
| 7 | [Native and Compact Structured Latents for 3D Generation](https://huggingface.co/papers/2512.14692) | A new sparse voxel representation called O-Voxel enables high-quality 3D generative modeling with efficient inference and robust topology ha… | [microsoft/TRELLIS.2](https://github.com/microsoft/TRELLIS.2) 11795★ |
| 149 | [AgentGarten: Code Worlds for Evolving Agents](https://huggingface.co/papers/2610.12374) | Interactive virtual worlds allow agents to learn through exploration and interaction. | 💡 [MirroS-Lab/AgentGarten](https://github.com/MirroS-Lab/AgentGarten) 145★ |
| 58 | [Prime Agent: A Self-Improving RLM Harness](https://huggingface.co/papers/2608.23552) | Prime Agent is an open-source harness that uses recursive subagents, persistent computation, and agent-to-agent coordination to extend langu… | [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) 21847★ |
| 71 | [SuperNav: An Agentic Navigation System for Any Task in Any Scene](https://huggingface.co/papers/2610.12126) | General-purpose service robots need navigation systems that can handle diverse human requests in unfamiliar environments, combining task gen… | 💡 [zju3dv/SuperNav](https://github.com/zju3dv/SuperNav) 103★ |
| 33 | [HuggingFace's Transformers: State-of-the-art Natural Language Processing](https://huggingface.co/papers/1910.03771) | Transformers library provides state-of-the-art Transformer architectures and pretrained models for natural language processing tasks with a… | [huggingface/transformers](https://github.com/huggingface/transformers) 167143★ |
| 53 | [SpatialLM: Training Large Language Models for Structured Indoor Modeling](https://huggingface.co/papers/2506.07491) | SpatialLM, a multimodal large language model, processes 3D point cloud data to generate structured scene understanding outputs, achieving st… | [manycore-research/SpatialLM](https://github.com/manycore-research/SpatialLM) 4942★ |
| 233 | [YuE2: Unifying Symbolic and Audio Music Generation at Frontier Quality](https://huggingface.co/papers/2609.33757) | Symbolic models make melody, harmony, rhythm, and form explicit but typically stop before a finished recording; audio models produce complet… | [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE) 11137★ |
| 74 | [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://huggingface.co/papers/2504.19413) | Mem0, a memory-centric architecture with graph-based memory, enhances long-term conversational coherence in LLMs by efficiently extracting,… | [mem0ai/mem0](https://github.com/mem0ai/mem0) 66961★ |
| 14 | [Iris-3B: Going Beyond the Latent with Pixel-Space Diffusion Training, Conversion and Fine-Tuning](https://huggingface.co/papers/2610.09450) | Pixel-space diffusion models avoid the lossy VAE of latent models, which suggests an advantage on downstream tasks where fine-grained detail… | 💡 [speridlabs/iris-3b](https://github.com/speridlabs/iris-3b) 90★ |
| 180 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 81415★ |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 56 | 18 | [oh, apparently it's not possible to portably check for string-to-float conversion errors in standard…](https://sebsite.pw/w/20261009-strtod.html) | `c` | [讨论](https://lobste.rs/s/rb2ulg/oh_apparently_it_s_not_possible_portably) |
| 30 | 6 | [The Lightbulb Computer: Reimagining Spatial & Ambient Computing with Projectors](https://lightbulbcomputer.com/) | `design` | [讨论](https://lobste.rs/s/0g9ctg/lightbulb_computer_reimagining_spatial) |
| 4 | 2 | [Consistency is not a localized property](https://n-the-loop.com/blog/consistency-is-not-a-localized-property/) | `ai` `databases` `programming` | [讨论](https://lobste.rs/s/rhy5zp/consistency_is_not_localized_property) |
| 57 | 15 | [No Man Is an Island](https://borretti.me/article/no-man-is-an-island) | `philosophy` `vibecoding` | [讨论](https://lobste.rs/s/nxspz6/no_man_is_island) |
| 23 | 1 | [Iframes that finally fit their content](https://alfy.blog/2026/10/09/iframe-that-finally-fit-their-content.html) | `css` `web` | [讨论](https://lobste.rs/s/ka6d0y/iframes_finally_fit_their_content) |
| 11 | 1 | [Kiesel Devlog #15: Release 0.4.0](https://linus.dev/posts/kiesel-devlog-15/) | `javascript` `zig` | [讨论](https://lobste.rs/s/4zmka2/kiesel_devlog_15_release_0_4_0) |
| 7 | 0 | [Inside a 1980s filter chip that uses switched capacitors](http://www.righto.com/2026/10/ML10-switched-capacitor-filter.html) | `hardware` `historical` `reversing` | [讨论](https://lobste.rs/s/mbyawi/inside_1980s_filter_chip_uses_switched) |
| 3 | 3 | [Making np.searchsorted up to 25× Faster in NumPy 2.5](https://blog.scientific-python.org/numpy/searchsorted/) | `performance` | [讨论](https://lobste.rs/s/fbs3k7/making_np_searchsorted_up_25x_faster) |
| 6 | 0 | [Byte Language Models: Scaling, Emergent Abstractions, and Information Allocation](https://arxiv.org/html/2610.05978v1) | `ai` | [讨论](https://lobste.rs/s/t2fxpt/byte_language_models_scaling_emergent) |
| 11 | 0 | [SNTPings, draw on a canvas using ICMPv6](https://pings.utwente.io/) | `education` `networking` | [讨论](https://lobste.rs/s/5zbbd0/sntpings_draw_on_canvas_using_icmpv6) |
| 10 | 0 | [Why 'externalized' proofs of cyclic trait impls does not work](https://smallcultfollowing.com/babysteps/blog/2026/10/10/modular-vs-external-proofs/) | `rust` | [讨论](https://lobste.rs/s/gytcvn/why_externalized_proofs_cyclic_trait) |
| 8 | 5 | [Mars Pathfinder Priority Inversion Bug: What Really Happened](https://nerdyelectronics.com/mars-pathfinder-what-really-happened/) | `compsci` `debugging` | [讨论](https://lobste.rs/s/pmwc4h/mars_pathfinder_priority_inversion_bug) |
| 50 | 18 | [A tale of four theorem provers, or: A (reasonably) opinionated comparison of Isabelle/HOL, Lean, HOL…](https://blueberrywren.dev/blog/primes/) | `design` `plt` | [讨论](https://lobste.rs/s/4dwrz0/tale_four_theorem_provers_reasonably) |
| 66 | 5 | [Python 3.15.0](https://www.python.org/downloads/release/python-3150/) | `python` `release` | [讨论](https://lobste.rs/s/rpiwtb/python_3_15_0) |
| 81 | 48 | [Programming Isn’t Special](https://blog.glyph.im/2026/10/programming-isnt-special.html) | `art` `vibecoding` | [讨论](https://lobste.rs/s/ily7as/programming_isn_t_special) |
| 25 | 17 | [There's little that's "inevitable" about AI](https://deadsimpletech.com/blog/llms-arent-inevitable) | `rant` `vibecoding` | [讨论](https://lobste.rs/s/lgxq91/there_s_little_s_inevitable_about_ai) |
| 3 | 0 | [culpert - rust heap profiling with span awareness and regression tooling](https://github.com/rupert648/culpert) | `performance` `rust` `vibecoding` | [讨论](https://lobste.rs/s/a1ser9/culpert_rust_heap_profiling_with_span) |
| 62 | 4 | [Unison Cloud is now open source](https://www.unison-lang.org/blog/unison-cloud-open-source/) | `release` | [讨论](https://lobste.rs/s/zubabn/unison_cloud_is_now_open_source) |
| 10 | 1 | [1-click MMI execution in Android](https://karansaini.com/mmi-android/) | `android` `security` | [讨论](https://lobste.rs/s/txa6dj/1_click_mmi_execution_android) |
| 39 | 22 | [Why Are Coding Agents So Dumb?](https://mtlynch.io/why-are-coding-agents-so-dumb/) | `rant` `vibecoding` | [讨论](https://lobste.rs/s/t5htlf/why_are_coding_agents_so_dumb) |

---

## 怎么读这份选题单

```text
分 = log(1 + 近 7 天新增) × 加速 × 没被写过 × 活着 × 可信 × 10

加速      近 7 天比前 7 天多 → ×1.2
没被写过  HN 最高分 ≥ 100 → ×0.5
活着      两周没提交 → ×0.5
可信      每个疑点 → ×0.5
```

| 判断 | 意思 |
| --- | --- |
| 🟢 窗口内 | 还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。 |
| 🟡 在降温 | 增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。 |
| 🔵 已被发现 | HN 上已经火过，懂行的人都看到了。要写，得有比「介绍一下」更深的角度。 |
| 💤 不活跃 | 两周没有提交，可能是一次性项目。写之前确认作者还在维护。 |
| 🔴 先核对 | 有疑点：看看 issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。 |

**接下来人做的事**：挑 1–2 个 → 在容器里装一下、跑一下、截图 → 用第一人称写你试出来的东西。自动化找和收，不自动化写和发。

方法和数据源说明见 [科技博主的选题雷达](https://github.com/craftsail/craftsail-github-sync/blob/main/docs/%E7%A7%91%E6%8A%80%E5%8D%9A%E4%B8%BB%E7%9A%84%E9%80%89%E9%A2%98%E9%9B%B7%E8%BE%BE.md)。分数只用来排序，不代表项目好或不好。
