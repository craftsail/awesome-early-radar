# 选题雷达 · 2026-10-12

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 111 个，细查前 20 个 · 生成于 2026-10-12 05:33 UTC

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 2 个 · 🟡 在降温 6 个 · 🔵 已被发现 2 个 · 💤 不活跃 0 个 · 🔴 先核对 10 个
- **最值得今天试的**：
  - [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) — Eleven free Claude skills that clone any app: reverse-engine…（近 7 天 +1395，比前 7 天快 2.5 倍，在加速）
  - [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) — Your company's data, connected into one ontology, on your ow…（近 7 天 +1240，刚发布一周内）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 24 个（star 合计 19458），代表：[QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：4 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Bigwords.page – Turn any screen into a sign. The URL is the app](https://bigwords.page/) — 722 分

**目录**：[GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [Lobsters](#七lobsters-热门) · [怎么读](#怎么读这份选题单)

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 86.9 | 🟢 窗口内 | [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) | Python | 1955 | +1395 | +560 | `····▆▆▅▅▆▇███·` | 8 | — | — |
| 2 | 85.5 | 🟢 窗口内 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) | TypeScript | 1240 | +1240 | +0 | `·········▃█▇▃·` | 5 | — | — |
| 3 | 72.4 | 🟡 在降温 | [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html) | JavaScript | 2929 | +1400 | +1529 | `···▁██▅▅▅▃▄▃▂·` | 9 | — | — |
| 4 | 66.1 | 🟡 在降温 | [kaankiziltug/logo-design-skill](https://github.com/kaankiziltug/logo-design-skill) | HTML | 2794 | +743 | +1501 | `█▇▅▅▄▄▄▄▃▃▃▅▃·` | 15 | — | — |
| 5 | 62 | 🟡 在降温 | [feitangyuan/onetake](https://github.com/feitangyuan/onetake) | Python | 2155 | +494 | +781 | `▅▄▅█▄▄▆▆▅▄▄▃▃·` | 15 | — | — |
| 6 | 60.8 | 🟡 在降温 | [tobi/disktree](https://github.com/tobi/disktree) | Rust | 2798 | +438 | +524 | `▄▄▄▄▃▃▂▂▃▂▂▂█·` | 17 | [3](https://news.ycombinator.com/item?id=49841155) | — |
| 7 | 58 | 🟡 在降温 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) | Python | 1873 | +329 | +1544 | `·█▆▃▂▂▂▂▂▁▂▁▁·` | 11 | — | — |
| 8 | 56.9 | 🟡 在降温 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep) | TypeScript | 2612 | +294 | +786 | `█▄▃▃▄▃▂▂▃▃▂▂▂·` | 16 | [5](https://news.ycombinator.com/item?id=49880146) | — |
| 9 | 47.7 | 🔴 先核对 | [storytold/cadcraft](https://github.com/storytold/cadcraft) | Rust | 2830 | +2830 | +0 | `········▄▆▆▅█·` | 5 | — | 同一作者这批里有 3 个仓库 |
| 10 | 45.9 | 🔴 先核对 | [storytold/deckcraft](https://github.com/storytold/deckcraft) | Rust | 2110 | +2110 | +0 | `·······▁▃▅▇▆█·` | 5 | — | 同一作者这批里有 3 个仓库 |
| 11 | 45.3 | 🔴 先核对 | [storytold/soundcraft](https://github.com/storytold/soundcraft) | Rust | 1895 | +1896 | +0 | `········▄▇▇▆█·` | 4 | — | 同一作者这批里有 3 个仓库 |
| 12 | 42.9 | 🔴 先核对 | [ARahim3/DigUp](https://github.com/ARahim3/DigUp) | Swift | 1275 | +1275 | +0 | `··········▁▃█·` | 3 | [4](https://news.ycombinator.com/item?id=50045015) | 一天进了一半以上的 star，但 HN 上没火过 |
| 13 | 41.8 | 🔵 已被发现 | [pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust) | Rust | 1065 | +1065 | +0 | `········█▄▂▃▂·` | 5 | [117](https://news.ycombinator.com/item?id=50000676) | — |
| 14 | 39.9 | 🔵 已被发现 | [rociiu/talorys](https://github.com/rociiu/talorys) | TypeScript | 777 | +777 | +0 | `···········█▅·` | 1 | [323](https://news.ycombinator.com/item?id=50031614) | — |
| 15 | 39.2 | 🔴 先核对 | [bherbruck/solidcraft](https://github.com/bherbruck/solidcraft) | Rust | 691 | +692 | +0 | `··········▂▂█·` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 16 | 38.7 | 🔴 先核对 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | Python | 633 | +633 | +0 | `········▁▁▁▂█·` | 6 | [8](https://news.ycombinator.com/item?id=50037852) | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 34.3 | 🔴 先核对 | [mrsarac/ff-tracking](https://github.com/mrsarac/ff-tracking) | Rust | 302 | +302 | +0 | `··········█▄▄·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 28.8 | 🔴 先核对 | [unreallabsai/unreal-agent](https://github.com/unreallabsai/unreal-agent) | Go | 2190 | +121 | +65 | `▃▂▂▂▂▂▂█▆▂▁▂▂·` | 20 | [1](https://news.ycombinator.com/item?id=49812351) | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 28.5 | 🔴 先核对 | [elstongun/leviathan](https://github.com/elstongun/leviathan) | Rust | 744 | +298 | +446 | `······█▄▁▁▁▁▁·` | 6 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 24.5 | 🔴 先核对 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) | Python | 2750 | +132 | +2618 | `▃█▃▂▁▁▁▁▁▁▁▁▁·` | 12 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 471 | 30 | 42542 | [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html)、[kaankiziltug/logo-design-skill](https://github.com/kaankiziltug/logo-design-skill)、[feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) |
| `mcp` | 136 | 30 | 14485 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[youngyangyang04/llm-master](https://github.com/youngyangyang04/llm-master)、[openai/mcp-extensions](https://github.com/openai/mcp-extensions) |
| `rust` | 113 | 30 | 24070 | [storytold/cadcraft](https://github.com/storytold/cadcraft)、[tobi/disktree](https://github.com/tobi/disktree)、[storytold/deckcraft](https://github.com/storytold/deckcraft) |
| `local-first` | 61 | 30 | 12801 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[ARahim3/DigUp](https://github.com/ARahim3/DigUp)、[HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 24 | 19458 | [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth) |
| `codex` | 21 | 16597 | [kaankiziltug/logo-design-skill](https://github.com/kaankiziltug/logo-design-skill)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth) |
| `ai-agents` | 20 | 9722 | [Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui) |
| `llm` | 16 | 11554 | [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[youngyangyang04/llm-master](https://github.com/youngyangyang04/llm-master) |
| `macos` | 16 | 8245 | [freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[ARahim3/DigUp](https://github.com/ARahim3/DigUp)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui) |
| `agent-skills` | 12 | 13182 | [kaankiziltug/logo-design-skill](https://github.com/kaankiziltug/logo-design-skill)、[Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) |
| `developer-tools` | 11 | 7306 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui) |
| `jev` | 10 | 7039 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[ollaya-dev/ollaya](https://github.com/ollaya-dev/ollaya)、[jev-chat/jev-chat-windows](https://github.com/jev-chat/jev-chat-windows) |
| `model-context-protocol` | 10 | 4906 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[VoltAgent/official-mcp-servers](https://github.com/VoltAgent/official-mcp-servers)、[XiaoPuOuO/openchatx-mcp](https://github.com/XiaoPuOuO/openchatx-mcp) |
| `linux` | 9 | 5438 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[amontlabs/lcu](https://github.com/amontlabs/lcu)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `python` | 9 | 4741 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[jev-chat/jev-chat-windows](https://github.com/jev-chat/jev-chat-windows)、[jev-chat/jev-chat-jarvis-mac](https://github.com/jev-chat/jev-chat-jarvis-mac) |
| `ai-agent` | 8 | 6701 | [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html)、[freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |

**语言分布**：Python 35 · Rust 28 · TypeScript 19 · JavaScript 7 · Swift 7 · Go 6 · C++ 1 · HTML 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) · 🟢 窗口内 · 86.9 分

> Eleven free Claude skills that clone any app: reverse-engineer it, rebuild it, test it for bugs, then fix what its users hate. Free, MIT.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1955 | +1395 | +560 | 280 | 5 | Python | MIT | 10-03（8 天前） | 8 天前 |

- **近 14 天每天新增**：`····▆▆▅▅▆▇███·` 0 0 0 0 187 217 156 169 188 229 280 268 261 0
- **势头**：比前 7 天快 2.5 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent` `agent-skills` `app-clone` `claude` `claude-code` `claude-skills` `indie-hacker` `reverse-engineering` `saas`
- **主页**：<https://opusjake.ai>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) · 🟢 窗口内 · 85.5 分

> Your company's data, connected into one ontology, on your own computer. A local-first data workspace built on HelixDB and DuckDB.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1240 | +1240 | +0 | 191 | 41 | TypeScript | Apache-2.0 | 10-07（5 天前） | 今天 |

- **近 14 天每天新增**：`·········▃█▇▃·` 0 0 0 0 0 0 0 0 0 137 504 429 170 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html) · 🟡 在降温 · 72.4 分

> Answer me with HTML — an agent skill that answers hard questions with a one-page HTML you can actually read. 让 AI Agent 用一页 HTML 回答复杂问题。

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2929 | +1400 | +1529 | 199 | 5 | JavaScript | MIT | 10-02（9 天前） | 今天 |

- **近 14 天每天新增**：`···▁██▅▅▅▃▄▃▂·` 0 0 0 9 561 603 356 314 339 199 241 187 120 0
- **势头**：只有前 7 天的 92%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `ai-agent` `claude-code` `claude-code-skill` `claude-skill` `claude-skills` `cli` `diagram` `explainer` `html` `llm` `ste100`
- **主页**：<https://answer-me-with-html.com/>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 4. [kaankiziltug/logo-design-skill](https://github.com/kaankiziltug/logo-design-skill) · 🟡 在降温 · 66.1 分

> A comprehensive logo-design skill for Claude, Gemini CLI, Codex and other AI agents: principles, process, SVG craft, testing tools and a 1,400+ logo reference library.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2794 | +743 | +1501 | 202 | 1 | HTML | MIT | 09-26（15 天前） | 11 天前 |

- **近 14 天每天新增**：`█▇▅▅▄▄▄▄▃▃▃▅▃·` 341 285 201 184 164 162 164 143 111 86 88 198 117 0
- **势头**：只有前 7 天的 50%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `branding` `claude` `claude-skills` `codex` `gemini-cli` `logo-design` `svg`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 5. [feitangyuan/onetake](https://github.com/feitangyuan/onetake) · 🟡 在降温 · 62 分

> Motion films that never cut to the next slide: every beat grows out of the one before, one continuous camera, continuity measured by an oracle. Product launch films and feature demos, made with a coding agent.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2155 | +494 | +781 | 138 | 3 | Python | — | 09-26（15 天前） | 1 天前 |

- **近 14 天每天新增**：`▅▄▅█▄▄▆▆▅▄▄▃▃·` 108 88 98 187 92 85 123 122 119 77 69 59 48 0
- **势头**：只有前 7 天的 63%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `animation` `canvas` `claude-skill` `launch-video` `motion-graphics` `video`
- **主页**：<https://onetakemotion.com>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 6. [tobi/disktree](https://github.com/tobi/disktree) · 🟡 在降温 · 60.8 分

> A treemap for finding and removing what fills your disk, for Omarchy. Rust + GPUI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2798 | +438 | +524 | 173 | 32 | Rust | MIT | 09-24（17 天前） | 7 天前 |

- **近 14 天每天新增**：`▄▄▄▄▃▃▂▂▃▂▂▂█·` 89 107 83 84 70 58 33 46 56 39 31 36 230 0
- **势头**：只有前 7 天的 84%，在减速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=49841155)）
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 7. [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) · 🟡 在降温 · 58 分

> AI生成の日本語を自然な日本語へ推敲するAgent Skill / Agent Skill for Refining AI-Generated Japanese into Natural Japanese

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1873 | +329 | +1544 | 42 | 0 | Python | MIT | 09-30（11 天前） | 今天 |

- **近 14 天每天新增**：`·█▆▃▂▂▂▂▂▁▂▁▁·` 0 623 429 172 115 93 112 111 78 37 47 23 33 0
- **势头**：只有前 7 天的 21%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-writing` `antigravity` `claude-code` `codex` `cursor` `gemini` `japanese` `linter` `llm` `nlp` `writing` `writing-assistant` `writing-tool`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [dzhng/jevgrep](https://github.com/dzhng/jevgrep) · 🟡 在降温 · 56.9 分

> Find code by asking what it does. A CLI for coding agents that uses Jev to discover relevant files and source context.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2612 | +294 | +786 | 191 | 29 | TypeScript | MIT | 09-26（16 天前） | 9 天前 |

- **近 14 天每天新增**：`█▄▃▃▄▃▂▂▃▃▂▂▂·` 274 113 96 65 115 70 53 35 69 59 45 29 57 0
- **势头**：只有前 7 天的 37%，在减速
- **HN**：发过 1 次，最高 5 分（[讨论](https://news.ycombinator.com/item?id=49880146)）
- **topics**：`ai-sdk` `claude-code` `cli` `code-search` `codex` `coding-agents` `context-retrieval` `developer-tools` `jev` `semantic-search` `typescript` `vercel-ai-gateway`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [storytold/cadcraft](https://github.com/storytold/cadcraft) · 🔴 先核对 · 47.7 分

> CADCraft: computer-aided design and drafting — an open-source, clean-room AutoCAD-style app in pure Rust

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2830 | +2830 | +0 | 1304 | 104 | Rust | Apache-2.0 | 10-07（5 天前） | 今天 |

- **近 14 天每天新增**：`········▄▆▆▅█·` 0 0 0 0 0 0 0 0 322 593 551 528 836 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **疑点**：同一作者这批里有 3 个仓库
- **判断**：有疑点：看看 issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。

### 10. [storytold/deckcraft](https://github.com/storytold/deckcraft) · 🔴 先核对 · 45.9 分

> Presentations and slide shows: an open-source, clean-room reimplementation of Microsoft PowerPoint in pure Rust. Part of the ArtCraft Crafting Apps.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2110 | +2110 | +0 | 1102 | 147 | Rust | Apache-2.0 | 10-07（5 天前） | 今天 |

- **近 14 天每天新增**：`·······▁▃▅▇▆█·` 0 0 0 0 0 0 0 12 200 344 497 462 595 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://getartcraft.com/apps/slidecraft>
- **疑点**：同一作者这批里有 3 个仓库
- **判断**：有疑点：看看 issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [storytold/cadcraft](https://github.com/storytold/cadcraft) — 同一作者这批里有 3 个仓库
- [storytold/deckcraft](https://github.com/storytold/deckcraft) — 同一作者这批里有 3 个仓库
- [storytold/soundcraft](https://github.com/storytold/soundcraft) — 同一作者这批里有 3 个仓库
- [ARahim3/DigUp](https://github.com/ARahim3/DigUp) — 一天进了一半以上的 star，但 HN 上没火过
- [bherbruck/solidcraft](https://github.com/bherbruck/solidcraft) — 一天进了一半以上的 star，但 HN 上没火过
- [academa-labs/manimgx](https://github.com/academa-labs/manimgx) — 一天进了一半以上的 star，但 HN 上没火过
- [mrsarac/ff-tracking](https://github.com/mrsarac/ff-tracking) — 一天进了一半以上的 star，但 HN 上没火过
- [unreallabsai/unreal-agent](https://github.com/unreallabsai/unreal-agent) — 一天进了一半以上的 star，但 HN 上没火过
- [elstongun/leviathan](https://github.com/elstongun/leviathan) — 一天进了一半以上的 star，但 HN 上没火过
- [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 722 | 166 | [Show HN: Bigwords.page – Turn any screen into a sign. The URL is the app](https://bigwords.page/) | [HN](https://news.ycombinator.com/item?id=49994443) |
| 424 | 55 | [Show HN: Carrier-Explode: iPhone, Pixel and Galaxy carrier settings decoded](https://carrierexplode.com/) | [HN](https://news.ycombinator.com/item?id=50024499) |
| 414 | 196 | [Show HN: Let your AI agents paint big arrows, boxes and text on your screen](https://github.com/franzenzenhofer/big-arrow-on-the-screen) | [HN](https://news.ycombinator.com/item?id=50018817) |
| 273 | 120 | [Show HN: WallHop – 12ft.io is gone, so I built a replacement](https://wallhop.io/) | [HN](https://news.ycombinator.com/item?id=50038634) |
| 239 | 180 | [Show HN: Quake ported to safe Rust, playable in browser](https://quake-srp.pages.dev/) | [HN](https://news.ycombinator.com/item?id=50016312) |
| 221 | 37 | [Show HN: Making a flexible "neon" t-shirt with LED filaments](http://scottbezek.blogspot.com/2026/10/making-flexible-neon-t-shirt-with-leds.html) | [HN](https://news.ycombinator.com/item?id=50008047) |
| 181 | 105 | [Show HN: BetterWispr – Free, open-source dictation for Mac](https://betterwispr.com/) | [HN](https://news.ycombinator.com/item?id=50042333) |
| 180 | 66 | [Show HN: The rarest tech books and docs you've probably never read](https://readrare.com/) | [HN](https://news.ycombinator.com/item?id=50024055) |
| 174 | 68 | [Show HN: A walkable 3D art history museum built from Wikipedia](https://artmuseum.artfrompixels.com/) | [HN](https://news.ycombinator.com/item?id=49992057) |
| 119 | 44 | [Show HN: Proton Drive for Linux](https://oss.lsantos.dev/proton-drive-linux-fs/) | [HN](https://news.ycombinator.com/item?id=50003545) |
| 90 | 17 | [Show HN: Happy Hangul Day! An RNN for Generating Korean Handwriting Strokes](https://hangul.ink/blog/hangul-day) | [HN](https://news.ycombinator.com/item?id=50015833) |
| 88 | 24 | [Show HN: Parseable, an open observability datalake, handles 100M time-series/min](https://www.parseable.com) | [HN](https://news.ycombinator.com/item?id=49978171) |
| 86 | 39 | [Show HN: I turned my iPhone and a $20 smart plug into an f-stop timer](https://peterszentkiralyi.eu/darkplug/) | [HN](https://news.ycombinator.com/item?id=49978595) |
| 79 | 23 | [Show HN: Jevman – AI decision models play Pac-Man](https://opper.ai/jevman-benchmark/) | [HN](https://news.ycombinator.com/item?id=50007993) |
| 75 | 0 | [Show HN: MailAccess – the true Email OSINT framework](https://mailaccess.pro) | [HN](https://news.ycombinator.com/item?id=49977385) |
| 73 | 49 | [Show HN: Agent.reviews – Where AI agents read and write reviews on tools](https://agent.reviews/) | [HN](https://news.ycombinator.com/item?id=49995539) |
| 69 | 53 | [Show HN: K10s – A Clickable Kubernetes TUI (Go, Bubble Tea)](https://github.com/p10node/k10s) | [HN](https://news.ycombinator.com/item?id=50009904) |
| 69 | 12 | [Show HN: Diffle, a keyboard-centric diff viewer with LSP support](https://github.com/moritzwilksch/diffle) | [HN](https://news.ycombinator.com/item?id=50006930) |
| 66 | 3 | [Show HN: Apogee: Rebuilding Mozilla's Orbit, fully local and private](https://github.com/darshi1337/apogee) | [HN](https://news.ycombinator.com/item?id=50017301) |
| 65 | 21 | [Show HN: NanoMuse – An open-source AI agent for your phone and computer](https://github.com/nano-muse/nanoMuse) | [HN](https://news.ycombinator.com/item?id=49987765) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 26 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Mixture-of-experts (MoE) inference on consumer hardware is bounded by weight memory: a 35B-class model is 19.5GB at 4-bit, and sparsity shri… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 4486★ |
| 233 | [YuE2: Unifying Symbolic and Audio Music Generation at Frontier Quality](https://huggingface.co/papers/2609.33757) | Symbolic models make melody, harmony, rhythm, and form explicit but typically stop before a finished recording; audio models produce complet… | [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE) 11603★ |
| 102 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | 💡 [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 867★ |
| 13 | [PyTorch Distributed: Experiences on Accelerating Data Parallel Training](https://huggingface.co/papers/2006.15704) | The PyTorch distributed data parallel module optimizes large-scale model training using techniques like gradient bucketing, computation-comm… | [pytorch/pytorch](https://github.com/pytorch/pytorch) 104444★ |
| 34 | [HuggingFace's Transformers: State-of-the-art Natural Language Processing](https://huggingface.co/papers/1910.03771) | Transformers library provides state-of-the-art Transformer architectures and pretrained models for natural language processing tasks with a… | [huggingface/transformers](https://github.com/huggingface/transformers) 167516★ |
| 151 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 110619★ |
| 39 | [Geometric Context Transformer for Streaming 3D Reconstruction](https://huggingface.co/papers/2604.14141) | LingBot-Map is a feed-forward 3D foundation model that reconstructs scenes from video streams using a geometric context transformer architec… | [robbyant/lingbot-map](https://github.com/robbyant/lingbot-map) 17990★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 90605★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 59 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 40560★ |
| 18 | [Bitnet.cpp: Efficient Edge Inference for Ternary LLMs](https://huggingface.co/papers/2502.11880) | Bitnet.cpp enhances edge inference for ternary LLMs using a novel mixed-precision matrix multiplication library, achieving significant speed… | [microsoft/BitNet](https://github.com/microsoft/BitNet) 40692★ |
| 7 | [Native and Compact Structured Latents for 3D Generation](https://huggingface.co/papers/2512.14692) | A new sparse voxel representation called O-Voxel enables high-quality 3D generative modeling with efficient inference and robust topology ha… | [microsoft/TRELLIS.2](https://github.com/microsoft/TRELLIS.2) 11852★ |
| 58 | [Prime Agent: A Self-Improving RLM Harness](https://huggingface.co/papers/2608.23552) | Prime Agent is an open-source harness that uses recursive subagents, persistent computation, and agent-to-agent coordination to extend langu… | [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) 21914★ |
| 53 | [SpatialLM: Training Large Language Models for Structured Indoor Modeling](https://huggingface.co/papers/2506.07491) | SpatialLM, a multimodal large language model, processes 3D point cloud data to generate structured scene understanding outputs, achieving st… | [manycore-research/SpatialLM](https://github.com/manycore-research/SpatialLM) 5021★ |
| 168 | [Kandinsky 6.0 Video: Foundation Models for Synchronized Video and Audio Generation](https://huggingface.co/papers/2610.05608) | We present Kandinsky 6.0 Video, a family of foundation diffusion models for synchronized text-to-audio-video generation, comprising Kandinsk… | 💡 [kandinskylab/kandinsky-6](https://github.com/kandinskylab/kandinsky-6) 268★ |
| 35 | [WorldSonus: Bringing Sound to Worlds](https://huggingface.co/papers/2610.08760) | Recent advances in world models have enabled increasingly realistic visual synthesis. | 💡 [NoizAI/WorldSonus](https://github.com/NoizAI/WorldSonus) 191★ |
| 91 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 26958★ |
| 74 | [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://huggingface.co/papers/2504.19413) | Mem0, a memory-centric architecture with graph-based memory, enhances long-term conversational coherence in LLMs by efficiently extracting,… | [mem0ai/mem0](https://github.com/mem0ai/mem0) 67011★ |
| 180 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 81467★ |
| 257 | [AgentGarten: Code Worlds for Evolving Agents](https://huggingface.co/papers/2610.12374) | Interactive virtual worlds allow agents to learn through exploration and interaction. | 💡 [MirroS-Lab/AgentGarten](https://github.com/MirroS-Lab/AgentGarten) 156★ |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 40 | 3 | [I'm sorry, but you still have to think](https://itsallaboutthebit.com/i-am-sorry-but-you-still-have-to-think/) | `vibecoding` | [讨论](https://lobste.rs/s/k2natg/i_m_sorry_you_still_have_think) |
| 107 | 29 | [I'm still around.. I'm just not writing here](https://rachelbythebay.com/w/2026/10/08/idle/) | `culture` | [讨论](https://lobste.rs/s/4ehrkn/i_m_still_around_i_m_just_not_writing_here) |
| 51 | 38 | [What's Wrong with GitHub](https://www.gnu.org/philosophy/whats-wrong-with-github.html) | `vcs` | [讨论](https://lobste.rs/s/u9ue6c/what_s_wrong_with_github) |
| 48 | 5 | [D-Bus Hell](https://dbushell.com/2026/10/11/d-bus-hell/) | `person` `satire` | [讨论](https://lobste.rs/s/qgybwb/d_bus_hell) |
| 10 | 2 | ['AI' is Not a Tool](https://www.linkedin.com/pulse/ai-tool-rich-hickey-kjl8e) | `vibecoding` | [讨论](https://lobste.rs/s/ikk8ie/ai_is_not_tool) |
| 25 | 5 | [Valen's Memory Safety: A New Kind of Borrow Checking](https://verdagon.dev/blog/valen-group-borrowing) | `compilers` `plt` | [讨论](https://lobste.rs/s/gmnqhj/valen_s_memory_safety_new_kind_borrow) |
| 12 | 2 | [Arena Allocators in C](https://eliasebner.com/blog/guides/arena-allocators-in-c/) | `c` | [讨论](https://lobste.rs/s/zziknb/arena_allocators_c) |
| 9 | 5 | [The wild west of polyglot docs sites](https://technicalwriting.dev/blog/2026/10/polyglot/index.html) | `c` `c++` `practices` `python` `rust` | [讨论](https://lobste.rs/s/wyxufm/wild_west_polyglot_docs_sites) |
| 9 | 1 | [Highlights from "I spent 6 years developing a game in Rust and it just shipped, AMA" (2024)](https://gamesbymason.com/blog/2024/6-years-in-rust-ama/#what-made-you-decide-to-use-rust) | `games` `rust` | [讨论](https://lobste.rs/s/dodzdb/highlights_from_i_spent_6_years) |
| 28 | 3 | [How big is a Git commit?](https://ratfactor.com/cards/git-commit-size) | `vcs` | [讨论](https://lobste.rs/s/9wcfld/how_big_is_git_commit) |
| 36 | 13 | [LineageOS 24.0 released](https://lineageos.org/Changelog-32/) | `android` `mobile` `release` | [讨论](https://lobste.rs/s/ecxril/lineageos_24_0_released) |
| 2 | 0 | [Refurb weekend II: Alpha Micro Eagle 300 and friends](https://oldvcr.blogspot.com/2026/10/refurb-weekend-ii-alpha-micro-eagle-300.html) | `retrocomputing` | [讨论](https://lobste.rs/s/cthze7/refurb_weekend_ii_alpha_micro_eagle_300) |
| 3 | 0 | [When LLM Decompilers Recompile More and Preserve Less](https://arxiv.org/abs/2609.05370) | `reversing` `vibecoding` | [讨论](https://lobste.rs/s/uzfa4k/when_llm_decompilers_recompile_more) |
| 7 | 0 | [The next-gen borrow checker, a drop-in replacement for Rust borrow checking](https://gist.github.com/FlameyosSnowy/a49a35ba006238be55d8c3e410c31061) | `compilers` `plt` `rust` | [讨论](https://lobste.rs/s/sqftld/next_gen_borrow_checker_drop_replacement) |
| 3 | 0 | [CSS for underlines](https://www.rubenerd.au/css-for-underlines/) | `css` | [讨论](https://lobste.rs/s/ezucf0/css_for_underlines) |
| 20 | 3 | [How shredding JSON is giving Logfire 1000x query speedups](https://pydantic.dev/articles/dynamic-shredding-2026-01-26) | `databases` `performance` | [讨论](https://lobste.rs/s/6vjx1k/how_shredding_json_is_giving_logfire) |
| 2 | 0 | [Tello's GameSir T1d controller as a Linux Xbox controller](https://blog.jacq.cc/guides/gamesir-t1d-linux-gamepad/) | `linux` `python` | [讨论](https://lobste.rs/s/dxftjg/tello_s_gamesir_t1d_controller_as_linux) |
| 1 | 0 | [3-2-1 Backup Strategy with restic and Backblaze B2](https://chuck.is/paranoid/) | `devops` `linux` | [讨论](https://lobste.rs/s/9zcxev/3_2_1_backup_strategy_with_restic) |
| 10 | 6 | [Consistency is not a localized property](https://n-the-loop.com/blog/consistency-is-not-a-localized-property/) | `ai` `databases` `programming` | [讨论](https://lobste.rs/s/rhy5zp/consistency_is_not_localized_property) |
| 65 | 32 | [oh, apparently it's not possible to portably check for string-to-float conversion errors in standard…](https://sebsite.pw/w/20261009-strtod.html) | `c` | [讨论](https://lobste.rs/s/rb2ulg/oh_apparently_it_s_not_possible_portably) |

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
