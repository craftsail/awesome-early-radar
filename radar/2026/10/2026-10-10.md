# 选题雷达 · 2026-10-10

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 112 个，细查前 20 个 · 生成于 2026-10-10 16:12 UTC

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 3 个 · 🟡 在降温 6 个 · 🔵 已被发现 1 个 · 💤 不活跃 0 个 · 🔴 先核对 10 个
- **最值得今天试的**：
  - [mhtsec/ARTEX](https://github.com/mhtsec/ARTEX) — AI 自主渗透测试系统 / 百度“agent+”攻防挑战赛冠军项目（近 7 天 +2842，刚发布一周内）
  - [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html) — Answer me with HTML — an agent skill that answers hard quest…（近 7 天 +2147，比前 7 天快 3.8 倍，在加速）
  - [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) — Eleven free Claude skills that clone any app: reverse-engine…（近 7 天 +1345，比前 7 天快 7.2 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 26 个（star 合计 19349），代表：[QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：7 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Bigwords.page – Turn any screen into a sign. The URL is the app](https://bigwords.page/) — 716 分

**目录**：[GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [Lobsters](#七lobsters-热门) · [怎么读](#怎么读这份选题单)

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 95.4 | 🟢 窗口内 | [mhtsec/ARTEX](https://github.com/mhtsec/ARTEX) | Go | 2842 | +2842 | +0 | `···········██▃` | 2 | — | — |
| 2 | 92.1 | 🟢 窗口内 | [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html) | JavaScript | 2718 | +2147 | +571 | `·····▁██▅▅▅▃▄▂` | 8 | — | — |
| 3 | 86.5 | 🟢 窗口内 | [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) | Python | 1532 | +1345 | +187 | `······▆▆▅▅▆▇█▄` | 7 | — | — |
| 4 | 67.3 | 🟡 在降温 | [kaankiziltug/logo-design-skill](https://github.com/kaankiziltug/logo-design-skill) | HTML | 2564 | +839 | +1643 | `▄██▇▅▅▄▄▄▄▃▃▃▃` | 14 | — | — |
| 5 | 64.3 | 🟡 在降温 | [feitangyuan/onetake](https://github.com/feitangyuan/onetake) | Python | 2074 | +620 | +1139 | `▇█▄▃▃▅▃▃▄▄▄▃▃▂` | 14 | — | — |
| 6 | 62 | 🟡 在降温 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) | Python | 1830 | +491 | +1339 | `···█▆▃▂▂▂▂▂▁▂▁` | 10 | — | — |
| 7 | 58.4 | 🟡 在降温 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep) | TypeScript | 2539 | +344 | +1952 | `██▄▂▂▂▂▂▂▁▂▂▁▁` | 14 | [5](https://news.ycombinator.com/item?id=49880146) | — |
| 8 | 56.1 | 🟡 在降温 | [tobi/disktree](https://github.com/tobi/disktree) | Rust | 2543 | +272 | +918 | `█▄▃▃▃▃▂▂▂▂▂▂▂▁` | 15 | [3](https://news.ycombinator.com/item?id=49841155) | — |
| 9 | 55.8 | 🟡 在降温 | [openai/mcp-extensions](https://github.com/openai/mcp-extensions) | TypeScript | 997 | +265 | +732 | `··█▆▅▂▂▂▂▁▁▄▂▂` | 11 | [2](https://news.ycombinator.com/item?id=49911638) | — |
| 10 | 47.6 | 🔴 先核对 | [storytold/wordcraft](https://github.com/storytold/wordcraft) | Rust | 2798 | +2798 | +0 | `··········▃▅█▅` | 3 | — | 同一作者这批里有 5 个仓库 |
| 11 | 44.5 | 🔴 先核对 | [storytold/cadcraft](https://github.com/storytold/cadcraft) | Rust | 1668 | +1668 | +0 | `··········▅██▃` | 3 | — | 同一作者这批里有 5 个仓库 |
| 12 | 44.3 | 🔴 先核对 | [storytold/gridcraft](https://github.com/storytold/gridcraft) | Rust | 1614 | +1614 | +0 | `··········▃▆█▄` | 3 | — | 同一作者这批里有 5 个仓库 |
| 13 | 42.9 | 🔴 先核对 | [storytold/deckcraft](https://github.com/storytold/deckcraft) | Rust | 1269 | +1269 | +0 | `·········▁▄▆█▄` | 3 | — | 同一作者这批里有 5 个仓库 |
| 14 | 42.5 | 🔴 先核对 | [storytold/soundcraft](https://github.com/storytold/soundcraft) | Rust | 1199 | +1199 | +0 | `··········▅██▃` | 3 | — | 同一作者这批里有 5 个仓库 |
| 15 | 41 | 🔵 已被发现 | [pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust) | Rust | 920 | +920 | +0 | `··········█▄▂▂` | 3 | [112](https://news.ycombinator.com/item?id=50000676) | — |
| 16 | 40.4 | 🔴 先核对 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) | TypeScript | 832 | +832 | +0 | `···········▃█▄` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 39.7 | 🔴 先核对 | [wuyoscar/AISafetyHot-Hub](https://github.com/wuyoscar/AISafetyHot-Hub) | TeX | 818 | +747 | +71 | `····▁▁▂▂▁▁▃█▂▄` | 9 | — | fork 不到 star 的 1% |
| 18 | 29.3 | 🔴 先核对 | [unreallabsai/unreal-agent](https://github.com/unreallabsai/unreal-agent) | Go | 2184 | +132 | +95 | `▅▃▃▂▂▂▂▂▂█▆▂▁▂` | 18 | [1](https://news.ycombinator.com/item?id=49812351) | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 24.9 | 🔴 先核对 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) | Python | 2722 | +145 | +2577 | `··▃█▃▂▁▁▁▁▁▁▁▁` | 10 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 2.7 | 🔴 先核对 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify) | Python | 1900 | +2 | +1896 | `···█······▁···` | 20 | — | 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1% |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 481 | 30 | 43469 | [mhtsec/ARTEX](https://github.com/mhtsec/ARTEX)、[feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html) |
| `mcp` | 139 | 30 | 14914 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[youngyangyang04/llm-master](https://github.com/youngyangyang04/llm-master)、[qiz029/dscode](https://github.com/qiz029/dscode) |
| `rust` | 121 | 30 | 23532 | [storytold/wordcraft](https://github.com/storytold/wordcraft)、[tobi/disktree](https://github.com/tobi/disktree)、[storytold/cadcraft](https://github.com/storytold/cadcraft) |
| `local-first` | 60 | 30 | 11273 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[glanderness/BeefTV](https://github.com/glanderness/BeefTV)、[HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 26 | 19349 | [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) |
| `ai-agents` | 25 | 11939 | [Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[Clearailhc/clearai-dsh](https://github.com/Clearailhc/clearai-dsh)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill) |
| `codex` | 23 | 17212 | [kaankiziltug/logo-design-skill](https://github.com/kaankiziltug/logo-design-skill)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) |
| `llm` | 17 | 12223 | [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[youngyangyang04/llm-master](https://github.com/youngyangyang04/llm-master) |
| `macos` | 15 | 7635 | [freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[qiz029/dscode](https://github.com/qiz029/dscode) |
| `developer-tools` | 13 | 8325 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui) |
| `agent-skills` | 11 | 12133 | [kaankiziltug/logo-design-skill](https://github.com/kaankiziltug/logo-design-skill)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth) |
| `jev` | 10 | 7692 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[ollaya-dev/ollaya](https://github.com/ollaya-dev/ollaya)、[qiz029/dscode](https://github.com/qiz029/dscode) |
| `linux` | 9 | 5084 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[amontlabs/lcu](https://github.com/amontlabs/lcu)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `ai-agent` | 8 | 6615 | [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html)、[freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[qiz029/dscode](https://github.com/qiz029/dscode) |
| `typescript` | 8 | 5096 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust)、[sno-ai/sno-station](https://github.com/sno-ai/sno-station) |
| `python` | 8 | 4454 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[jev-chat/jev-chat-windows](https://github.com/jev-chat/jev-chat-windows)、[jev-chat/jev-chat-jarvis-mac](https://github.com/jev-chat/jev-chat-jarvis-mac) |

**语言分布**：Python 34 · Rust 29 · TypeScript 20 · Go 7 · JavaScript 7 · Swift 4 · HTML 2 · CSS 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [mhtsec/ARTEX](https://github.com/mhtsec/ARTEX) · 🟢 窗口内 · 95.4 分

> AI 自主渗透测试系统 | 百度“agent+”攻防挑战赛冠军项目

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2842 | +2842 | +0 | 5266 | 0 | Go | AGPL-3.0 | 10-08（2 天前） | 今天 |

- **近 14 天每天新增**：`···········██▃` 0 0 0 0 0 0 0 0 0 0 0 1294 1227 321
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html) · 🟢 窗口内 · 92.1 分

> Answer me with HTML — an agent skill that answers hard questions with a one-page HTML you can actually read. 让 AI Agent 用一页 HTML 回答复杂问题。

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2718 | +2147 | +571 | 185 | 4 | JavaScript | MIT | 10-02（8 天前） | 今天 |

- **近 14 天每天新增**：`·····▁██▅▅▅▃▄▂` 0 0 0 0 0 9 562 603 356 313 340 199 241 95
- **势头**：比前 7 天快 3.8 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `ai-agent` `claude-code` `claude-code-skill` `claude-skill` `claude-skills` `cli` `diagram` `explainer` `html` `llm` `ste100`
- **主页**：<https://answer-me-with-html.com/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) · 🟢 窗口内 · 86.5 分

> Eleven free Claude skills that clone any app: reverse-engineer it, rebuild it, test it for bugs, then fix what its users hate. Free, MIT.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1532 | +1345 | +187 | 207 | 5 | Python | MIT | 10-03（7 天前） | 7 天前 |

- **近 14 天每天新增**：`······▆▆▅▅▆▇█▄` 0 0 0 0 0 0 187 218 156 170 188 229 281 103
- **势头**：比前 7 天快 7.2 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent` `agent-skills` `app-clone` `claude` `claude-code` `claude-skills` `indie-hacker` `reverse-engineering` `saas`
- **主页**：<https://opusjake.ai>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [kaankiziltug/logo-design-skill](https://github.com/kaankiziltug/logo-design-skill) · 🟡 在降温 · 67.3 分

> A comprehensive logo-design skill for Claude, Gemini CLI, Codex and other AI agents: principles, process, SVG craft, testing tools and a 1,400+ logo reference library.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2564 | +839 | +1643 | 178 | 0 | HTML | MIT | 09-26（14 天前） | 9 天前 |

- **近 14 天每天新增**：`▄██▇▅▅▄▄▄▄▃▃▃▃` 140 328 341 285 201 184 164 162 164 143 111 86 89 84
- **势头**：只有前 7 天的 51%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `branding` `claude` `claude-skills` `codex` `gemini-cli` `logo-design` `svg`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 5. [feitangyuan/onetake](https://github.com/feitangyuan/onetake) · 🟡 在降温 · 64.3 分

> Motion films that never cut to the next slide: every beat grows out of the one before, one continuous camera, continuity measured by an oracle. Product launch films and feature demos, made with a coding agent.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2074 | +620 | +1139 | 130 | 3 | Python | — | 09-26（14 天前） | 今天 |

- **近 14 天每天新增**：`▇█▄▃▃▅▃▃▄▄▄▃▃▂` 271 294 108 88 98 188 92 85 123 122 119 77 69 25
- **势头**：只有前 7 天的 54%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `animation` `canvas` `claude-skill` `launch-video` `motion-graphics` `video`
- **主页**：<https://onetakemotion.com>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 6. [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) · 🟡 在降温 · 62 分

> AI生成の日本語を自然な日本語へ推敲するAgent Skill / Agent Skill for Refining AI-Generated Japanese into Natural Japanese

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1830 | +491 | +1339 | 40 | 0 | Python | MIT | 09-30（10 天前） | 1 天前 |

- **近 14 天每天新增**：`···█▆▃▂▂▂▂▂▁▂▁` 0 0 0 623 429 172 115 93 112 111 78 37 47 13
- **势头**：只有前 7 天的 37%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-writing` `antigravity` `claude-code` `codex` `cursor` `gemini` `japanese` `linter` `llm` `nlp` `writing` `writing-assistant` `writing-tool`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 7. [dzhng/jevgrep](https://github.com/dzhng/jevgrep) · 🟡 在降温 · 58.4 分

> Find code by asking what it does. A CLI for coding agents that uses Jev to discover relevant files and source context.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2539 | +344 | +1952 | 186 | 29 | TypeScript | MIT | 09-26（14 天前） | 7 天前 |

- **近 14 天每天新增**：`██▄▂▂▂▂▂▂▁▂▂▁▁` 658 631 274 113 96 65 115 70 53 35 69 59 45 13
- **势头**：只有前 7 天的 18%，在减速
- **HN**：发过 1 次，最高 5 分（[讨论](https://news.ycombinator.com/item?id=49880146)）
- **topics**：`ai-sdk` `claude-code` `cli` `code-search` `codex` `coding-agents` `context-retrieval` `developer-tools` `jev` `semantic-search` `typescript` `vercel-ai-gateway`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [tobi/disktree](https://github.com/tobi/disktree) · 🟡 在降温 · 56.1 分

> A treemap for finding and removing what fills your disk, for Omarchy. Rust + GPUI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2543 | +272 | +918 | 162 | 27 | Rust | MIT | 09-24（15 天前） | 5 天前 |

- **近 14 天每天新增**：`█▄▃▃▃▃▂▂▂▂▂▂▂▁` 329 155 89 107 83 85 70 58 33 46 56 39 31 9
- **势头**：只有前 7 天的 30%，在减速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=49841155)）
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [openai/mcp-extensions](https://github.com/openai/mcp-extensions) · 🟡 在降温 · 55.8 分

> Build plugins that feel like native, first-class features of ChatGPT.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 997 | +265 | +732 | 51 | 10 | TypeScript | Apache-2.0 | 09-29（11 天前） | 今天 |

- **近 14 天每天新增**：`··█▆▅▂▂▂▂▁▁▄▂▂` 0 0 300 197 151 60 24 22 25 10 9 136 23 40
- **势头**：只有前 7 天的 36%，在减速
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=49911638)）
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [storytold/wordcraft](https://github.com/storytold/wordcraft) · 🔴 先核对 · 47.6 分

> An open-source, clean-room reimplementation of Microsoft Word in pure Rust

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2798 | +2798 | +0 | 810 | 124 | Rust | Apache-2.0 | 10-07（3 天前） | 今天 |

- **近 14 天每天新增**：`··········▃▅█▅` 0 0 0 0 0 0 0 0 0 0 354 624 1194 626
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://getartcraft.com/apps/wordcraft>
- **疑点**：同一作者这批里有 5 个仓库
- **判断**：有疑点：看看 issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [storytold/wordcraft](https://github.com/storytold/wordcraft) — 同一作者这批里有 5 个仓库
- [storytold/cadcraft](https://github.com/storytold/cadcraft) — 同一作者这批里有 5 个仓库
- [storytold/gridcraft](https://github.com/storytold/gridcraft) — 同一作者这批里有 5 个仓库
- [storytold/deckcraft](https://github.com/storytold/deckcraft) — 同一作者这批里有 5 个仓库
- [storytold/soundcraft](https://github.com/storytold/soundcraft) — 同一作者这批里有 5 个仓库
- [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) — 一天进了一半以上的 star，但 HN 上没火过
- [wuyoscar/AISafetyHot-Hub](https://github.com/wuyoscar/AISafetyHot-Hub) — fork 不到 star 的 1%
- [unreallabsai/unreal-agent](https://github.com/unreallabsai/unreal-agent) — 一天进了一半以上的 star，但 HN 上没火过
- [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) — 一天进了一半以上的 star，但 HN 上没火过
- [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify) — 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1%

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 716 | 163 | [Show HN: Bigwords.page – Turn any screen into a sign. The URL is the app](https://bigwords.page/) | [HN](https://news.ycombinator.com/item?id=49994443) |
| 403 | 183 | [Show HN: Let your AI agents paint big arrows, boxes and text on your screen](https://github.com/franzenzenhofer/big-arrow-on-the-screen) | [HN](https://news.ycombinator.com/item?id=50018817) |
| 378 | 45 | [Show HN: Carrier-Explode: iPhone, Pixel and Galaxy carrier settings decoded](https://carrierexplode.com/) | [HN](https://news.ycombinator.com/item?id=50024499) |
| 230 | 176 | [Show HN: Quake ported to safe Rust, playable in browser](https://quake-srp.pages.dev/) | [HN](https://news.ycombinator.com/item?id=50016312) |
| 219 | 37 | [Show HN: Making a flexible "neon" t-shirt with LED filaments](http://scottbezek.blogspot.com/2026/10/making-flexible-neon-t-shirt-with-leds.html) | [HN](https://news.ycombinator.com/item?id=50008047) |
| 183 | 74 | [Show HN: AI search for every photo and every frame of video on macOS](https://github.com/allenv0/SCM) | [HN](https://news.ycombinator.com/item?id=49952111) |
| 172 | 66 | [Show HN: A walkable 3D art history museum built from Wikipedia](https://artmuseum.artfrompixels.com/) | [HN](https://news.ycombinator.com/item?id=49992057) |
| 154 | 57 | [Show HN: The rarest tech books and docs you've probably never read](https://readrare.com/) | [HN](https://news.ycombinator.com/item?id=50024055) |
| 110 | 39 | [Show HN: Proton Drive for Linux](https://oss.lsantos.dev/proton-drive-linux-fs/) | [HN](https://news.ycombinator.com/item?id=50003545) |
| 99 | 31 | [Show HN: AstroHelm – Use your phone camera to aim a telescope or telephoto lens](https://astrohelm.app/) | [HN](https://news.ycombinator.com/item?id=49954015) |
| 89 | 28 | [Show HN: Nightwatch – a Mac menu-bar app that tells you when tonight is clear](https://github.com/rsutcliffe/nightwatch) | [HN](https://news.ycombinator.com/item?id=49952148) |
| 88 | 24 | [Show HN: Parseable, an open observability datalake, handles 100M time-series/min](https://www.parseable.com) | [HN](https://news.ycombinator.com/item?id=49978171) |
| 86 | 39 | [Show HN: I turned my iPhone and a $20 smart plug into an f-stop timer](https://peterszentkiralyi.eu/darkplug/) | [HN](https://news.ycombinator.com/item?id=49978595) |
| 76 | 23 | [Show HN: Jevman – AI decision models play Pac-Man](https://opper.ai/jevman-benchmark/) | [HN](https://news.ycombinator.com/item?id=50007993) |
| 75 | 0 | [Show HN: MailAccess – the true Email OSINT framework](https://mailaccess.pro) | [HN](https://news.ycombinator.com/item?id=49977385) |
| 72 | 49 | [Show HN: Agent.reviews – Where AI agents read and write reviews on tools](https://agent.reviews/) | [HN](https://news.ycombinator.com/item?id=49995539) |
| 68 | 53 | [Show HN: K10s – A Clickable Kubernetes TUI (Go, Bubble Tea)](https://github.com/p10node/k10s) | [HN](https://news.ycombinator.com/item?id=50009904) |
| 65 | 21 | [Show HN: NanoMuse – An open-source AI agent for your phone and computer](https://github.com/nano-muse/nanoMuse) | [HN](https://news.ycombinator.com/item?id=49987765) |
| 65 | 2 | [Show HN: Apogee: Rebuilding Mozilla's Orbit, fully local and private](https://github.com/darshi1337/apogee) | [HN](https://news.ycombinator.com/item?id=50017301) |
| 60 | 25 | [Show HN: Procinsh – A 3D Linux process inspector](https://github.com/akawashiro/procinsh) | [HN](https://news.ycombinator.com/item?id=49991986) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 101 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | 💡 [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 700★ |
| 26 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Mixture-of-experts (MoE) inference on consumer hardware is bounded by weight memory: a 35B-class model is 19.5GB at 4-bit, and sparsity shri… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 4066★ |
| 39 | [Geometric Context Transformer for Streaming 3D Reconstruction](https://huggingface.co/papers/2604.14141) | LingBot-Map is a feed-forward 3D foundation model that reconstructs scenes from video streams using a geometric context transformer architec… | [robbyant/lingbot-map](https://github.com/robbyant/lingbot-map) 17901★ |
| 151 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 110428★ |
| 277 | [VisionHOPE: Visual Backbones as Self-Modifying Learning Systems](https://huggingface.co/papers/2609.33325) | Visual backbones have evolved from Convolutional Neural Networks (CNNs) with local aggregation to Vision Transformers (ViTs) with global int… | [PSRben/VisionHOPE](https://github.com/PSRben/VisionHOPE) 1204★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 90454★ |
| 162 | [Kandinsky 6.0 Video: Foundation Models for Synchronized Video and Audio Generation](https://huggingface.co/papers/2610.05608) | We present Kandinsky 6.0 Video, a family of foundation diffusion models for synchronized text-to-audio-video generation, comprising Kandinsk… | 💡 [kandinskylab/kandinsky-6](https://github.com/kandinskylab/kandinsky-6) 251★ |
| 76 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 59 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 40431★ |
| 141 | [AgentGarten: Code Worlds for Evolving Agents](https://huggingface.co/papers/2610.12374) | Interactive virtual worlds allow agents to learn through exploration and interaction. | 💡 [MirroS-Lab/AgentGarten](https://github.com/MirroS-Lab/AgentGarten) 140★ |
| 65 | [SuperNav: An Agentic Navigation System for Any Task in Any Scene](https://huggingface.co/papers/2610.12126) | General-purpose service robots need navigation systems that can handle diverse human requests in unfamiliar environments, combining task gen… | 💡 [zju3dv/SuperNav](https://github.com/zju3dv/SuperNav) 94★ |
| 9 | [Iris-3B: Going Beyond the Latent with Pixel-Space Diffusion Training, Conversion and Fine-Tuning](https://huggingface.co/papers/2610.09450) | Pixel-space diffusion models avoid the lossy VAE of latent models, which suggests an advantage on downstream tasks where fine-grained detail… | 💡 [speridlabs/iris-3b](https://github.com/speridlabs/iris-3b) 82★ |
| 7 | [Native and Compact Structured Latents for 3D Generation](https://huggingface.co/papers/2512.14692) | A new sparse voxel representation called O-Voxel enables high-quality 3D generative modeling with efficient inference and robust topology ha… | [microsoft/TRELLIS.2](https://github.com/microsoft/TRELLIS.2) 11729★ |
| 33 | [WorldSonus: Bringing Sound to Worlds](https://huggingface.co/papers/2610.08760) | Recent advances in world models have enabled increasingly realistic visual synthesis. | 💡 [NoizAI/WorldSonus](https://github.com/NoizAI/WorldSonus) 120★ |
| 74 | [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://huggingface.co/papers/2504.19413) | Mem0, a memory-centric architecture with graph-based memory, enhances long-term conversational coherence in LLMs by efficiently extracting,… | [mem0ai/mem0](https://github.com/mem0ai/mem0) 66917★ |
| 54 | [UniWAM: Unified World-Action Model](https://huggingface.co/papers/2610.02054) | Vision-language-action models benefit from the understanding and reasoning capabilities of pretrained vision-language models, but action-onl… | 💡 [UniWAM/UniWAM](https://github.com/UniWAM/UniWAM) 112★ |
| 58 | [Prime Agent: A Self-Improving RLM Harness](https://huggingface.co/papers/2608.23552) | Prime Agent is an open-source harness that uses recursive subagents, persistent computation, and agent-to-agent coordination to extend langu… | [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) 21787★ |
| 180 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 81399★ |
| 24 | [UniMate: One Unified Model to Animate Diverse Skeletons](https://huggingface.co/papers/2609.05415) | UniMate is a unified diffusion transformer that generates articulated motion for arbitrary skeletons from text and rigged 3D assets without… | [Friedrich-M/UniMate](https://github.com/Friedrich-M/UniMate) 1676★ |
| 13 | [PyTorch Distributed: Experiences on Accelerating Data Parallel Training](https://huggingface.co/papers/2006.15704) | The PyTorch distributed data parallel module optimizes large-scale model training using techniques like gradient bucketing, computation-comm… | [pytorch/pytorch](https://github.com/pytorch/pytorch) 104022★ |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 37 | 5 | [oh, apparently it's not possible to portably check for string-to-float conversion errors in standard…](https://sebsite.pw/w/20261009-strtod.html) | `c` | [讨论](https://lobste.rs/s/rb2ulg/oh_apparently_it_s_not_possible_portably) |
| 43 | 11 | [No Man Is an Island](https://borretti.me/article/no-man-is-an-island) | `philosophy` `vibecoding` | [讨论](https://lobste.rs/s/nxspz6/no_man_is_island) |
| 17 | 5 | [There's little that's "inevitable" about AI](https://deadsimpletech.com/blog/llms-arent-inevitable) | `vibecoding` | [讨论](https://lobste.rs/s/lgxq91/there_s_little_s_inevitable_about_ai) |
| 40 | 14 | [A tale of four theorem provers, or: A (reasonably) opinionated comparison of Isabelle/HOL, Lean, HOL…](https://blueberrywren.dev/blog/primes/) | `design` `plt` | [讨论](https://lobste.rs/s/4dwrz0/tale_four_theorem_provers_reasonably) |
| 76 | 46 | [Programming Isn’t Special](https://blog.glyph.im/2026/10/programming-isnt-special.html) | `art` `vibecoding` | [讨论](https://lobste.rs/s/ily7as/programming_isn_t_special) |
| 56 | 5 | [Python 3.15.0](https://www.python.org/downloads/release/python-3150/) | `python` `release` | [讨论](https://lobste.rs/s/rpiwtb/python_3_15_0) |
| 37 | 18 | [Why Are Coding Agents So Dumb?](https://mtlynch.io/why-are-coding-agents-so-dumb/) | `rant` `vibecoding` | [讨论](https://lobste.rs/s/t5htlf/why_are_coding_agents_so_dumb) |
| 50 | 2 | [Unison Cloud is now open source](https://www.unison-lang.org/blog/unison-cloud-open-source/) | `release` | [讨论](https://lobste.rs/s/zubabn/unison_cloud_is_now_open_source) |
| 51 | 12 | [Cloudflare shutting down Deno is news, not just PR](https://lobste.rs/s/8rrtma) | `meta` | [讨论](https://lobste.rs/s/8rrtma/cloudflare_shutting_down_deno_is_news_not) |
| 4 | 1 | [Mars Pathfinder Priority Inversion Bug: What Really Happened](https://nerdyelectronics.com/mars-pathfinder-what-really-happened/) | `compsci` `debugging` | [讨论](https://lobste.rs/s/pmwc4h/mars_pathfinder_priority_inversion_bug) |
| 7 | 1 | [1-click MMI execution in Android](https://karansaini.com/mmi-android/) | `android` `security` | [讨论](https://lobste.rs/s/txa6dj/1_click_mmi_execution_android) |
| 1 | 0 | [culpert - rust heap profiling with span awareness and regression tooling](https://github.com/rupert648/culpert) | `performance` `rust` `vibecoding` | [讨论](https://lobste.rs/s/a1ser9/culpert_rust_heap_profiling_with_span) |
| 4 | 5 | [Adding Go's defer to the TypeScript Compiler](https://healeycodes.com/adding-defer-to-the-typescript-compiler) | `compilers` `go` `javascript` | [讨论](https://lobste.rs/s/skpliy/adding_go_s_defer_typescript_compiler) |
| 3 | 0 | [Iframes that finally fit their content](https://alfy.blog/2026/10/09/iframe-that-finally-fit-their-content.html) | `css` `web` | [讨论](https://lobste.rs/s/ka6d0y/iframes_finally_fit_their_content) |
| 1 | 0 | [dasSDL3: Idiomatic SDL3 bindings for daslang](https://spiiin.github.io/blog/339855472/) | `graphics` | [讨论](https://lobste.rs/s/ptnq74/dassdl3_idiomatic_sdl3_bindings_for) |
| 23 | 0 | [Branches in branch-free code](https://00f.net/2026/10/09/llvm-compiles-branch-free-code-into-branches-on-risc-v/) | `assembly` `c` `compilers` `rust` `zig` | [讨论](https://lobste.rs/s/dsbt5a/branches_branch_free_code) |
| 9 | 0 | [Lifeguard: A static analyzer for Python lazy imports compatibility](https://github.com/Facebook/lifeguard) | `python` | [讨论](https://lobste.rs/s/qwqne6/lifeguard_static_analyzer_for_python) |
| 3 | 0 | [The Lightbulb Computer: Reimagining Spatial & Ambient Computing with Projectors](https://lightbulbcomputer.com/) | `design` `vibecoding` | [讨论](https://lobste.rs/s/0g9ctg/lightbulb_computer_reimagining_spatial) |
| 19 | 5 | [There are many themes, but this one is yours](https://earendil.com/posts/system-theme/) | `a11y` `design` `vibecoding` | [讨论](https://lobste.rs/s/3zcaxw/there_are_many_themes_this_one_is_yours) |
| 18 | 5 | ["Robot" Is A Social Construct: Why Your Dishwasher Is Not A Robot](https://robotgirlgang.com/2026/10/08/robot-is-a-social-construct-why-your-dishwasher-is-not-a-robot/) | `philosophy` | [讨论](https://lobste.rs/s/ha0qt7/robot_is_social_construct_why_your) |

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
