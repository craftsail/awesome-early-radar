# early-radar 选题雷达 · 2026-10-20

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 107 个，细查前 20 个 · 比上次 = 和 2026-10-19 那次比 · 生成于 2026-10-20 04:27 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 2 个 · Show HN ✅ 30 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 0 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 8 个 · 🟡 在降温 6 个 · 🔵 已被发现 1 个 · 💤 不活跃 0 个 · 🔴 先核对 5 个
- **今天新出现 2 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [google-research/harness2](https://github.com/google-research/harness2) 平均每天 +943，见 [爆发](#爆发)
- **最值得今天试的**：
  - [feder-cr/git-ai](https://github.com/feder-cr/git-ai) — Git designed for AI agents.（近 7 天 +2469，刚发布一周内）
  - [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) — Ears for coding agents: let AI hear, review and make sound.…（近 7 天 +1609，刚发布一周内）
  - [aicodeking/leanrea](https://github.com/aicodeking/leanrea) — One 8 KB skill that replaces REA (Reverse Engineer Anything)…（近 7 天 +1012，刚发布一周内）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 22 个（star 合计 20750），代表：[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：7 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Guitoro, a virtual guitar you strum with your keyboard](https://guitoro.com/) — 572 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [google-research/harness2](https://github.com/google-research/harness2) | 12520 | 943 | +5175 | 13.3 | [74](https://news.ycombinator.com/item?id=50151059) | harness2 · google-research harness2 · google harness2 |  |
| 🆕 [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) | 6282 | 2209 | — | 2.8 | — | cleanyourtv · gathin23 cleanyourtv · gathin cleanyourtv | Debloat any Android or Google TV over Wi-Fi and get an Apple… |
| [tangency-labs/solidcraft](https://github.com/tangency-labs/solidcraft) | 7464 | 602 | +1542 | 12.4 | — | solidcraft · tangency-labs solidcraft · tangency solidcraft | SolidCraft: an open-source parametric 3D CAD application bui… |
| [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) | 17024 | 1448 | +821 | 11.8 | — | anatomy · wheresryan22 anatomy · ryan anatomy | An agent skill for creating detailed, interactive isometric… |
| ✅ [storytold/wordcraft](https://github.com/storytold/wordcraft) | 14820 | 1155 | +380 | 12.8 | [101](https://news.ycombinator.com/item?id=50050370) | wordcraft · storytold wordcraft · artcraft wordcraft | An open-source, clean-room reimplementation of Microsoft Wor… |
| [openai/math](https://github.com/openai/math) | 15238 | 1148 | +57 | 13.3 | [342](https://news.ycombinator.com/item?id=50003107) | math · openai math |  |
| [ly05010419/MacNativeGames](https://github.com/ly05010419/MacNativeGames) | 1941 | 823 | +944 | 2.4 | — | macnativegames · ly05010419 macnativegames · yong macnativegames |  |
| [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) | 1609 | 328 | +723 | 4.9 | — | earshot · leonxlnx earshot · leon earshot | Ears for coding agents: let AI hear, review and make sound.… |
| [xiaoyang111222/cn-math-taxonomy](https://github.com/xiaoyang111222/cn-math-taxonomy) | 1085 | 600 | +575 | 1.8 | — | cn math taxonomy · xiaoyang111222 cn math taxonomy | 中小学数学知识图谱 + 前置诊断：课标对齐、人教版一–九年级、531 知识点、2271 题、自适应诊断 |
| [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | 987 | 590 | +497 | 1.7 | — | huashu motion · alchaincyf huashu motion | 让你的agent一键直出商业级产品宣传片：会作曲，能指着画面改。Commercial-grade launch film… |
| [feder-cr/git-ai](https://github.com/feder-cr/git-ai) | 2469 | 533 | +159 | 4.6 | — | git ai · feder-cr git ai · federico git ai | Git designed for AI agents. |
| [jhaizhou-ops/d2r-mobile](https://github.com/jhaizhou-ops/d2r-mobile) | 4073 | 521 | +172 | 7.8 | — | d2r mobile · jhaizhou-ops d2r mobile | Open-source iOS / macOS compatibility layer for Diablo II: R… |
| [Arekejoker/qwen21-nsfw-pose-skill](https://github.com/Arekejoker/qwen21-nsfw-pose-skill) | 3405 | 483 | +366 | 7.1 | — | qwen21 nsfw pose skill · arekejoker qwen21 nsfw pose skill | Qwen-Image 2.1 NSFW/姿势出图 skill：作者级提示词配方 + NSFW LoRA + 136 姿势… |
| 🆕 [simbasjungles/free-my-tv](https://github.com/simbasjungles/free-my-tv) | 481 | 481 | — | 1 | — | free my tv · simbasjungles free my tv · simba free my tv | A fast, ad-free home screen for Google TV. Open source, buil… |
| ✅ [storytold/cadcraft](https://github.com/storytold/cadcraft) | 6023 | 465 | +207 | 13 | — | cadcraft · storytold cadcraft · artcraft cadcraft | CADCraft: computer-aided design and drafting — an open-sourc… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 93.7 | 🟢 窗口内 | [feder-cr/git-ai](https://github.com/feder-cr/git-ai) | Go | 2469 | +159 | +2469 | +0 | `········▇▁▁█▂·` | 4 | — | — |
| 2 | 93 | ✅ 🟢 窗口内 | [storytold/figcraft](https://github.com/storytold/figcraft) | Rust | 2845 | +168 | +2312 | +533 | `··▁··▁▆▆▅█▄▃▃·` | 10 | [3](https://news.ycombinator.com/item?id=50069000) | — |
| 3 | 88.6 | 🟢 窗口内 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) | Python | 1609 | +723 | +1609 | +0 | `········▂▄▄▄█·` | 4 | — | — |
| 4 | 83 | 🟢 窗口内 | [aicodeking/leanrea](https://github.com/aicodeking/leanrea) | Python | 1012 | +352 | +1012 | +0 | `·········▁█▄▅·` | 3 | — | — |
| 5 | 81.9 | 🟢 窗口内 | [LiCinCan/blender-ai-mcp-addon](https://github.com/LiCinCan/blender-ai-mcp-addon) | Python | 921 | +133 | +921 | +0 | `·········▆█▅▄·` | 4 | — | — |
| 6 | 76.7 | 🟢 窗口内 | [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) | C | 594 | +165 | +594 | +0 | `·········▃▅█▅·` | 3 | — | — |
| 7 | 74.7 | 🟢 窗口内 | [reason-machines/reason-network](https://github.com/reason-machines/reason-network) | Rust | 505 | +67 | +505 | +0 | `·········▅█▇▃·` | 3 | — | — |
| 8 | 74.7 | 🆕 🟢 窗口内 | [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) | Python | 505 | +152 | +505 | +0 | `········▂▃▅█▆·` | 4 | — | — |
| 9 | 67.1 | 🟡 在降温 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 1682 | +78 | +818 | +864 | `····▁▆█▄▃▃▃▂▂·` | 9 | — | — |
| 10 | 66.1 | 🟡 在降温 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | Python | 1892 | +73 | +743 | +1149 | `▁▁▁▁█▆▃▂▄▃▂▂▂·` | 14 | [10](https://news.ycombinator.com/item?id=50037852) | — |
| 11 | 58.8 | 🟡 在降温 | [marclou/mailcheap](https://github.com/marclou/mailcheap) | JavaScript | 1257 | +20 | +357 | +900 | `···█▄▂▂▁▃▂▁▁▁·` | 9 | [2](https://news.ycombinator.com/item?id=50033695) | — |
| 12 | 58.1 | 🟡 在降温 | [jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) | Python | 1096 | +63 | +334 | +762 | `····█▄▇▂▁▁▄▃▂·` | 8 | — | — |
| 13 | 53.7 | 🟡 在降温 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) | TypeScript | 1626 | +13 | +213 | +1413 | `·▃█▇▄▂▂▂▁▁▂▁▁·` | 12 | — | — |
| 14 | 50.6 | 🟡 在降温 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) | Go | 1352 | +87 | +156 | +1196 | `·▁▁▁▁█▆▁▁▁▁▁▂·` | 11 | — | — |
| 15 | 41.4 | 🔴 先核对 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 987 | +497 | +987 | +0 | `···········█▆·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 16 | 41.2 | 🔴 先核对 | [outcrawlai/scout](https://github.com/outcrawlai/scout) | TypeScript | 953 | +7 | +953 | +0 | `·······█▂▁▁▁▁·` | 6 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 30.3 | 🆕 🔴 先核对 | [nichochar/ari](https://github.com/nichochar/ari) | TypeScript | 154 | — | +154 | +0 | `···········▆█·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 29.7 | 🔵 已被发现 | [rociiu/talorys](https://github.com/rociiu/talorys) | TypeScript | 1342 | +12 | +378 | +964 | `···█▅▃▂▂▄▂▂▁▁·` | 9 | [331](https://news.ycombinator.com/item?id=50031614) | — |
| 19 | 27.6 | 🔴 先核对 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 1136 | +24 | +250 | +886 | `·····█▃▂▂▁▁▁▁·` | 7 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 18.8 | 🔴 先核对 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) | Python | 2773 | +0 | +42 | +136 | `▂█▄▆▃▃▂▂▃▂▂▂▂·` | 20 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 529 | 30 | 46466 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[feitangyuan/onetake](https://github.com/feitangyuan/onetake) |
| `mcp` | 187 | 30 | 25779 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[amontlabs/lcu](https://github.com/amontlabs/lcu) |
| `rust` | 166 | 30 | 20589 | [storytold/figcraft](https://github.com/storytold/figcraft)、[academa-labs/manimgx](https://github.com/academa-labs/manimgx)、[opengeos/RustGIS](https://github.com/opengeos/RustGIS) |
| `local-first` | 61 | 30 | 12860 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[glanderness/BeefTV](https://github.com/glanderness/BeefTV) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 22 | 20750 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) |
| `ai-agents` | 19 | 14121 | [feder-cr/git-ai](https://github.com/feder-cr/git-ai)、[Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui) |
| `llm` | 18 | 12531 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) |
| `codex` | 15 | 13779 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) |
| `ai-agent` | 13 | 9773 | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) |
| `agent-skills` | 12 | 13771 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[amontlabs/lcu](https://github.com/amontlabs/lcu) |
| `mcp-server` | 12 | 9659 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `macos` | 12 | 8116 | [amontlabs/lcu](https://github.com/amontlabs/lcu)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge) |
| `developer-tools` | 10 | 8999 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill) |
| `python` | 10 | 8020 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai)、[Harvil1/codeAgent](https://github.com/Harvil1/codeAgent) |
| `coding-agents` | 7 | 8224 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[feder-cr/git-ai](https://github.com/feder-cr/git-ai)、[openfilm/openfilm](https://github.com/openfilm/openfilm) |
| `typescript` | 7 | 7033 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust)、[rociiu/talorys](https://github.com/rociiu/talorys) |

**语言分布**：Python 33 · Rust 30 · TypeScript 20 · JavaScript 9 · Go 4 · Swift 4 · Astro 1 · C 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [feder-cr/git-ai](https://github.com/feder-cr/git-ai) · 🟢 窗口内 · 93.7 分

> Git designed for AI agents.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2469 | +2469 | +0 | 271 | 0 | Go | — | 10-15（4 天前） | 今天 |

- **近 14 天每天新增**：`········▇▁▁█▂·` 0 0 0 0 0 0 0 0 1013 60 77 1170 149 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `coding-agents` `git` `golang` `scion` `version-control`
- **主页**：<https://www.anthropic.com/engineering/redesigning-source-control>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. ✅ [storytold/figcraft](https://github.com/storytold/figcraft) · 🟢 窗口内 · 93 分

> FigCraft: interface design and prototyping; an open-source, clean-room reimplementation of collaborative design workflows in pure Rust

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2845 | +2312 | +533 | 1098 | 149 | Rust | Apache-2.0 | 10-09（10 天前） | 今天 |

- **近 14 天每天新增**：`··▁··▁▆▆▅█▄▃▃·` 0 0 1 0 0 3 529 543 404 700 323 191 151 0
- **势头**：比前 7 天快 4.3 倍，在加速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=50069000)）
- **topics**：`design` `rust` `tools`
- **主页**：<https://getartcraft.com/apps/figcraft>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) · 🟢 窗口内 · 88.6 分

> Ears for coding agents: let AI hear, review and make sound. CPU-only, open source.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1609 | +1609 | +0 | 94 | 3 | Python | MIT | 10-15（4 天前） | 1 天前 |

- **近 14 天每天新增**：`········▂▄▄▄█·` 0 0 0 0 0 0 0 0 113 309 285 263 639 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `audio` `claude-code` `mcp` `sound-design`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [aicodeking/leanrea](https://github.com/aicodeking/leanrea) · 🟢 窗口内 · 83 分

> One 8 KB skill that replaces REA (Reverse Engineer Anything): plain CLI tools, no MCP. Benchmarked: 38% faster, 35% cheaper.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1012 | +1012 | +0 | 154 | 6 | Python | MIT | 10-17（3 天前） | 今天 |

- **近 14 天每天新增**：`·········▁█▄▅·` 0 0 0 0 0 0 0 0 0 26 468 220 298 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [LiCinCan/blender-ai-mcp-addon](https://github.com/LiCinCan/blender-ai-mcp-addon) · 🟢 窗口内 · 81.9 分

> AI assistant and MCP server for Blender: visual chat, scene tools, multi-agent workflows. Works with OpenAI, ChatGPT, Claude, Gemini, Ollama, OpenCode. Blender AI addon and plugin, copilot for 3D, bpy Python scripting, MCP integration.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 921 | +921 | +0 | 383 | 31 | Python | MIT | 10-15（4 天前） | 今天 |

- **近 14 天每天新增**：`·········▆█▅▄·` 0 0 0 0 0 0 0 0 0 256 336 197 132 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-assistant` `blender` `blender-addon` `blender-ai` `blender-automation` `blender-extension` `blender-mcp` `blender-plugin` `blender-python` `blender-scripting` `bpy` `chatgpt` `gpt` `llm` `mcp` `mcp-for-blender` `mcp-server` `model-context-protocol` `opencode` `python`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) · 🟢 窗口内 · 76.7 分

> Co-op Anything: point your AI agent at any single-player game and play it with friends (online and/or splitscreen!). MCP server and playbook to let you reverse engineer, fix, test, ship and share what it learns.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 594 | +594 | +0 | 59 | 46 | C | MIT | 10-16（3 天前） | 今天 |

- **近 14 天每天新增**：`·········▃▅█▅·` 0 0 0 0 0 0 0 0 0 81 131 234 148 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [reason-machines/reason-network](https://github.com/reason-machines/reason-network) · 🟢 窗口内 · 74.7 分

> Reason Network: your team's coding agents, talking to each other. The engine behind `reason network`.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 505 | +505 | +0 | 44 | 7 | Rust | Apache-2.0 | 10-16（3 天前） | 今天 |

- **近 14 天每天新增**：`·········▅█▇▃·` 0 0 0 0 0 0 0 0 0 108 180 157 60 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`coding-agents` `iroh` `mcp` `peer-to-peer` `reason`
- **主页**：<https://reasonmachines.com>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. 🆕 [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) · 🟢 窗口内 · 74.7 分

> 麦当劳 MCP 聚会/团餐组织助手 — 基于 Model Context Protocol 的派对预订与团餐规划 CLI/Skill

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 505 | +505 | +0 | 23 | 0 | Python | MIT | 10-15（4 天前） | 今天 |

- **近 14 天每天新增**：`········▂▃▅█▆·` 0 0 0 0 0 0 0 0 16 57 103 188 141 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 9. [opengeos/RustGIS](https://github.com/opengeos/RustGIS) · 🟡 在降温 · 67.1 分

> A fast, free and open-source GIS in pure Rust.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1682 | +818 | +864 | 239 | 25 | Rust | Apache-2.0 | 10-10（9 天前） | 今天 |

- **近 14 天每天新增**：`····▁▆█▄▃▃▃▂▂·` 0 0 0 0 2 371 491 237 143 150 116 103 69 0
- **势头**：只有前 7 天的 95%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`geospatial` `gis` `remote-sensing` `rust` `rust-lang`
- **主页**：<https://rustgis.app>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [academa-labs/manimgx](https://github.com/academa-labs/manimgx) · 🟡 在降温 · 66.1 分

> The animation engine for agents: blazingly fast math and 3D videos with Manim's Python API, on a Rust GPU core.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1892 | +743 | +1149 | 134 | 22 | Python | MIT | 10-05（14 天前） | 今天 |

- **近 14 天每天新增**：`▁▁▁▁█▆▃▂▄▃▂▂▂·` 7 31 11 40 567 368 125 106 235 159 84 98 61 0
- **势头**：只有前 7 天的 65%，在减速
- **HN**：发过 1 次，最高 10 分（[讨论](https://news.ycombinator.com/item?id=50037852)）
- **主页**：<https://manimgx.academa.ai>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) — 一天进了一半以上的 star，但 HN 上没火过
- [outcrawlai/scout](https://github.com/outcrawlai/scout) — 一天进了一半以上的 star，但 HN 上没火过
- [nichochar/ari](https://github.com/nichochar/ari) — 一天进了一半以上的 star，但 HN 上没火过
- [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) — 一天进了一半以上的 star，但 HN 上没火过
- [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 572 | 161 | [Show HN: Guitoro, a virtual guitar you strum with your keyboard](https://guitoro.com/) | [HN](https://news.ycombinator.com/item?id=50077020) |
| 329 | 86 | [Show HN: Llmspeed – feel how fast a local LLM runs before you buy the hardware](https://llmspeed.dev/) | [HN](https://news.ycombinator.com/item?id=50127979) |
| 318 | 200 | [Show HN: Unfenced – Land for sale that borders public land](https://unfenced.land/) | [HN](https://news.ycombinator.com/item?id=50102247) |
| 252 | 111 | [Show HN: Gemini 4 Argon plays StarCraft](https://starskirmish.com/bench/v0-2/) | [HN](https://news.ycombinator.com/item?id=50118688) |
| 252 | 89 | [Show HN: Sphinx – A hook that quizzes you on your AI's code before shipping](https://sphinx-six-theta.vercel.app/) | [HN](https://news.ycombinator.com/item?id=50137950) |
| 227 | 41 | [Show HN: Petal, open-source CoScreen/ScreenHero finally free](https://petal.live/) | [HN](https://news.ycombinator.com/item?id=50092470) |
| 216 | 120 | [Show HN: How random are you?](https://lab.specr.net/rigged-draw/) | [HN](https://news.ycombinator.com/item?id=50074909) |
| 215 | 126 | [Show HN: The Zelda timeline to catch up before the Ocarina of Time remake](https://legendofhyrule.com/) | [HN](https://news.ycombinator.com/item?id=50140769) |
| 205 | 46 | [Show HN: Esp32sim – Run ESP32 firmware in the browser](https://github.com/mikroverk/esp32sim) | [HN](https://news.ycombinator.com/item?id=50131189) |
| 175 | 44 | [Show HN: High-quality duck audio synthesizer](https://celphase.github.io/duck-pond/) | [HN](https://news.ycombinator.com/item?id=50131006) |
| 174 | 91 | [Show HN: Use your OpenAI subscription to create audiobooks](https://pdftomp3.com/connect-ai/) | [HN](https://news.ycombinator.com/item?id=50069337) |
| 147 | 73 | [Show HN: Flipflop – Iroh-powered persistent tunnels for filesharing](https://github.com/andunieee/flipflop) | [HN](https://news.ycombinator.com/item?id=50099136) |
| 146 | 79 | [Show HN: WhatsApp MCP running free on Cloudflare](https://github.com/finereli/whatsapp-mcp) | [HN](https://news.ycombinator.com/item?id=50145715) |
| 145 | 108 | [Show HN: Qwen3-4B with the AI writing tics trained out](https://100toolkit.com/blog/deslop-model/) | [HN](https://news.ycombinator.com/item?id=50151928) |
| 122 | 97 | [Show HN: Wonderhop – A daily game: guess what most people say, or what none do](https://wonderhop.io/en/) | [HN](https://news.ycombinator.com/item?id=50080246) |
| 121 | 71 | [Show HN: Pulse Local, a Mac budgeting app whose AI models run on your machine](https://pulseos.finance) | [HN](https://news.ycombinator.com/item?id=50080275) |
| 119 | 76 | [Show HN: I built a tool to track what AI leaders say and how their views change](https://blumify.io/people) | [HN](https://news.ycombinator.com/item?id=50081151) |
| 114 | 99 | [Show HN: I wrote an email app that accepts only one sender per inbox](https://clova.email/) | [HN](https://news.ycombinator.com/item?id=50090932) |
| 107 | 36 | [Show HN: Proa – A Rust web framework with fast SSR and multi-target rendering](https://proa.so/) | [HN](https://news.ycombinator.com/item?id=50105467) |
| 92 | 19 | [Show HN: Spotatui, a Spotify TUI/GUI without web API rate limits](https://github.com/LargeModGames/spotatui) | [HN](https://news.ycombinator.com/item?id=50070010) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 112 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 11906★ |
| 23 | [MOSS-Image Technical Report](https://huggingface.co/papers/2610.23374) | MOSS-Image is an open diffusion transformer that combines high-fidelity synthesis with intent-aware prompt enhancement to generate text-rich… | 💡 [OpenMOSS/MOSS-Image](https://github.com/OpenMOSS/MOSS-Image) 967★ |
| 60 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 41687★ |
| 28 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 6032★ |
| 153 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 112157★ |
| 266 | [Has GPT-6-Astra Achieved Embodied Intelligence?](https://huggingface.co/papers/2610.22471) | GPT-6-Astra achieves high performance across diverse robotic tasks via in-context learning, yet real-world deployment reveals gaps in demons… | 💡 [OpenSenseNova/SenseNova-RoboRSI](https://github.com/OpenSenseNova/SenseNova-RoboRSI) 151★ |
| 222 | [YuE2: Unifying Symbolic and Audio Music Generation at Frontier Quality](https://huggingface.co/papers/2609.33757) | YuE2 unifies symbolic and audio music generation via symbolic planning, producing readable scores and full-song audio with state-of-the-art… | [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE) 12302★ |
| 93 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 27891★ |
| 31 | [Internal Safety Collapse in Frontier Large Language Models](https://huggingface.co/papers/2603.23509) | Frontier large language models exhibit Internal Safety Collapse, where they generate harmful content under specific task conditions, reveali… | [wuyoscar/ISC-Bench](https://github.com/wuyoscar/ISC-Bench) 1820★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 91293★ |
| 360 | [Any Time, Any Space: A World-State-Centric Framework for Agentic Video Generation](https://huggingface.co/papers/2610.20571) | ATAS improves long-form video consistency by compiling screenplays into referenced shot requests, retrieving spatial and temporal evidence f… | 💡 [ziplab/ATAS](https://github.com/ziplab/ATAS) 292★ |
| 52 | [RSI-Anything: Unlocking Recursive Self-Improvement with World Models](https://huggingface.co/papers/2610.13912) | RSI-Anything leverages predictive world models to guide action selection and adaptive learning, enabling recursive self-improvement across c… | 💡 [Gen-Verse/RSI-Anything](https://github.com/Gen-Verse/RSI-Anything) 801★ |
| 20 | [StartLux-Decision: AutoThink Decision Models with Reinforcement Learning for Calibrated Deliberative…](https://huggingface.co/papers/2610.17309) | StartLux-Decision introduces efficient and adaptive decision models using single-pass prediction and confidence-guided reasoning, trained vi… | 💡 [StartLuxLabs/StartLux-Decision](https://github.com/StartLuxLabs/StartLux-Decision) 830★ |
| 14 | [DiscoveryRSI: Recursively Learning to Discover Valuable Hypotheses](https://huggingface.co/papers/2610.23839) | DiscoveryRSI uses multi-agent evolutionary search and recursive learning to generate testable scientific hypotheses, improving quality throu… | 💡 [Gen-Verse/DiscoveryRSI](https://github.com/Gen-Verse/DiscoveryRSI) 72★ |
| 115 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 1524★ |
| 9 | [Native and Compact Structured Latents for 3D Generation](https://huggingface.co/papers/2512.14692) | A new sparse voxel representation called O-Voxel enables high-quality 3D generative modeling with efficient inference and robust topology ha… | [microsoft/TRELLIS.2](https://github.com/microsoft/TRELLIS.2) 12305★ |
| 38 | [Hybrid Reasoning Agents](https://huggingface.co/papers/2610.18861) | Hybrid Reasoning Agents combine latent internal reasoning with text-based external interaction via a unified architecture and specialized po… | 💡 [togethercomputer/HybridAgent](https://github.com/togethercomputer/HybridAgent) 281★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 82059★ |
| 84 | [RAG-Anything: All-in-One RAG Framework](https://huggingface.co/papers/2510.12323) | RAG-Anything is a unified framework that enhances multimodal knowledge retrieval by integrating cross-modal relationships and semantic match… | [HKUDS/RAG-Anything](https://github.com/HKUDS/RAG-Anything) 23871★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 46 | [kromoss](https://huggingface.co/lodestones/Kromoss) | text-to-image | 125 | 1 |
| 50 | [naive n0.5 flash](https://huggingface.co/NaiveAI/Naive-N0.5-Flash) | text-generation | 290 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 323 | 274 | [Updates to site guidelines and AI/LLM tags](https://lobste.rs/s/h0eate) | `announce` `meta` | [讨论](https://lobste.rs/s/h0eate/updates_site_guidelines_ai_llm_tags) |
| 87 | 13 | [Wine ported to OpenBSD](https://marc.info/?l=openbsd-ports&m=179236125692175) | `openbsd` | [讨论](https://lobste.rs/s/gqepzd/wine_ported_openbsd) |
| 46 | 8 | [One Hash Bloom Filters](https://www.calabro.io/ohbf) | `compsci` `databases` | [讨论](https://lobste.rs/s/mpytbn/one_hash_bloom_filters) |
| 14 | 2 | [OpenBSD 8.0](https://www.openbsd.org/80.html) | `openbsd` `release` | [讨论](https://lobste.rs/s/sqdhu7/openbsd_8_0) |
| 39 | 2 | [Making all divisions slower to fix a bug in 0.000000000000000000542% of cases](https://futhark-lang.org/blog/2026-10-14-defining-division.html) | `c` `compilers` | [讨论](https://lobste.rs/s/a9f6z1/making_all_divisions_slower_fix_bug_0) |
| 18 | 11 | [A5 v1.0](https://a5geo.org/blog/2026/10/14/a5-v1) | `compsci` `math` `rust` `visualization` | [讨论](https://lobste.rs/s/wtthju/a5_v1_0) |
| 19 | 4 | [2026 is an exciting year for the Rust compiler (and me)](https://yoyo-code.com/2026-is-exciting-year-for-rust-compiler-and-me/) | `compilers` `rust` | [讨论](https://lobste.rs/s/c2ouz0/2026_is_exciting_year_for_rust_compiler_me) |
| 23 | 39 | [What are you doing this week?](https://lobste.rs/s/vyfegx) | `ask` `programming` | [讨论](https://lobste.rs/s/vyfegx/what_are_you_doing_this_week) |
| 16 | 6 | [In Context](https://www.youtube.com/watch?v=P5eO7BNyJao) | `programming` `video` | [讨论](https://lobste.rs/s/b36ixw/context) |
| 3 | 1 | [Do web components have a future if nobody is writing them?](https://nolanlawson.com/2026/10/19/do-web-components-have-a-future-if-nobody-is-writing-them/) | `ai-tooling` `web` | [讨论](https://lobste.rs/s/dpjkzz/do_web_components_have_future_if_nobody_is) |
| 30 | 21 | [Beginning of the Ende (a community Deno fork)](https://blog.webb.page/WM-105) | `javascript` | [讨论](https://lobste.rs/s/8ejwsp/beginning_ende_community_deno_fork) |
| 33 | 5 | [Tor VPN Beta: What we've learned building our own VPN for Android from scratch](https://blog.torproject.org/tor-vpn-beta/) | `android` `networking` `security` | [讨论](https://lobste.rs/s/s3w7hd/tor_vpn_beta_what_we_ve_learned_building) |
| 14 | 0 | [Hanami, Why?: Model Citizens](https://aaronmallen.me/writing/hanami-why-model-citizens) | `ruby` | [讨论](https://lobste.rs/s/ygp18d/hanami_why_model_citizens) |
| 5 | 0 | [OpenBSD 8.0: released](https://marc.info/?l=openbsd-announce&m=179245843570316&w=2) | `openbsd` | [讨论](https://lobste.rs/s/7qhwfi/openbsd_8_0_released) |
| 17 | 4 | [Making dns_erlang Fast: Binary Tricks for the BEAM](https://blog.dnsimple.com/2026/10/making-dns-erlang-fast/) | `erlang` | [讨论](https://lobste.rs/s/p3pruv/making_dns_erlang_fast_binary_tricks_for) |
| 28 | 3 | [Finding a home amidst the wreckage](https://blog.zerodogg.org/2026/10/18/finding-a-home-amidst-the-wreckage/) | `culture` `linux` | [讨论](https://lobste.rs/s/mpdk1e/finding_home_amidst_wreckage) |
| 10 | 0 | [The Netherlands is building its own Linux OS to break free from Microsoft](https://www.techspot.com/news/114018-netherlands-building-own-linux-os-break-free-microsoft.html) | `linux` `windows` | [讨论](https://lobste.rs/s/nne5uh/netherlands_is_building_its_own_linux_os) |
| 30 | 6 | [What the heck is /pkg?](https://anderegg.ca/2026/10/18/what-the-heck-is-pkg) | `mac` `unix` | [讨论](https://lobste.rs/s/w6xosj/what_heck_is_pkg) |
| 14 | 0 | [Borrow Checking Zero-Cost Cyclic Mutability](https://antelang.org/blog/safe_cyclic_mutability/) | `plt` | [讨论](https://lobste.rs/s/qo8flp/borrow_checking_zero_cost_cyclic) |
| 18 | 3 | [The 7.3 kernel has been released](https://lwn.net/Articles/1101143/) | `linux` `release` | [讨论](https://lobste.rs/s/4oz3sk/7_3_kernel_has_been_released) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

_还没有到 14 天的，58 个在等。_

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

🆕 = 今天第一次出现在选题单里 · ✅ = 已经写过（`--known`）· 比上次 = 和上一次运行比多了多少 star

**接下来人做的事**：挑 1–2 个 → 在容器里装一下、跑一下、截图 → 用第一人称写你试出来的东西。自动化找和收，不自动化写和发。

每一节怎么读见 [awesome-early-radar](https://github.com/craftsail/awesome-early-radar)。分数只用来排序，不代表项目好或不好。
