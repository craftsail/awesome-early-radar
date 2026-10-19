# early-radar 选题雷达 · 2026-10-19

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 109 个，细查前 20 个 · 比上次 = 和 2026-10-18 那次比 · 生成于 2026-10-19 04:15 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 0 个 · Show HN ✅ 32 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 0 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 6 个 · 🟡 在降温 5 个 · 🔵 已被发现 2 个 · 💤 不活跃 0 个 · 🔴 先核对 7 个
- **今天新出现 3 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [google-research/harness2](https://github.com/google-research/harness2) 平均每天 +599，见 [爆发](#爆发)
- **最值得今天试的**：
  - [opengeos/RustGIS](https://github.com/opengeos/RustGIS) — A fast, free and open-source GIS in pure Rust.（近 7 天 +1230，比前 7 天快 3.3 倍，在加速）
  - [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) — Ears for coding agents: let AI hear, review and make sound.…（近 7 天 +886，刚发布一周内）
  - [LiCinCan/blender-ai-mcp-addon](https://github.com/LiCinCan/blender-ai-mcp-addon) — AI assistant and MCP server for Blender: visual chat, scene…（近 7 天 +788，刚发布一周内）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 22 个（star 合计 18763），代表：[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：6 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Guitoro, a virtual guitar you strum with your keyboard](https://guitoro.com/) — 572 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [google-research/harness2](https://github.com/google-research/harness2) | 7345 | 599 | +5657 | 12.3 | [4](https://news.ycombinator.com/item?id=50146503) | harness2 · google-research harness2 · google harness2 |  |
| 🆕 [Gathin23/tv-vibehack](https://github.com/Gathin23/tv-vibehack) | 2325 | 1267 | +1962 | 1.8 | — | tv vibehack · gathin23 tv vibehack · gathin tv vibehack | Your TV, minus the ads. Debloat any Android TV over ADB and… |
| [tangency-labs/solidcraft](https://github.com/tangency-labs/solidcraft) | 5922 | 520 | +1513 | 11.4 | — | solidcraft · tangency-labs solidcraft · tangency solidcraft | SolidCraft: an open-source parametric 3D CAD application bui… |
| [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) | 16203 | 1507 | +946 | 10.8 | — | anatomy · wheresryan22 anatomy · ryan anatomy | An agent skill for creating detailed, interactive isometric… |
| [openai/math](https://github.com/openai/math) | 15181 | 1237 | +66 | 12.3 | [342](https://news.ycombinator.com/item?id=50003107) | math · openai math |  |
| ✅ [storytold/wordcraft](https://github.com/storytold/wordcraft) | 14440 | 1222 | +350 | 11.8 | [101](https://news.ycombinator.com/item?id=50050370) | wordcraft · storytold wordcraft · artcraft wordcraft | An open-source, clean-room reimplementation of Microsoft Wor… |
| [feder-cr/git-ai](https://github.com/feder-cr/git-ai) | 2310 | 637 | +1167 | 3.6 | — | git ai · feder-cr git ai · federico git ai | Git designed for AI agents. |
| 🆕 [obsidianmd/pele](https://github.com/obsidianmd/pele) | 1972 | 149 | +1069 | 13.2 | — | pele · obsidianmd pele | Renders Mermaid diagrams faster than you'd run from a volcan… |
| 🆕 [ly05010419/MacNativeGames](https://github.com/ly05010419/MacNativeGames) | 997 | 739 | — | 1.3 | — | macnativegames · ly05010419 macnativegames · yong macnativegames |  |
| [jhaizhou-ops/d2r-mobile](https://github.com/jhaizhou-ops/d2r-mobile) | 3901 | 572 | +167 | 6.8 | — | d2r mobile · jhaizhou-ops d2r mobile | Open-source iOS / macOS compatibility layer for Diablo II: R… |
| 🆕 [xiaoyang111222/cn-math-taxonomy](https://github.com/xiaoyang111222/cn-math-taxonomy) | 510 | 510 | — | 1 | — | cn math taxonomy · xiaoyang111222 cn math taxonomy | 初中数学知识图谱 + 前置诊断：课标对齐、人教版七–九、333 知识点、自适应诊断 |
| [Arekejoker/qwen21-nsfw-pose-skill](https://github.com/Arekejoker/qwen21-nsfw-pose-skill) | 3039 | 503 | +380 | 6 | — | qwen21 nsfw pose skill · arekejoker qwen21 nsfw pose skill | Qwen-Image 2.1 NSFW/姿势出图 skill：作者级提示词配方 + NSFW LoRA + 136 姿势… |
| 🆕 [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | 490 | 490 | — | 1 | — | huashu motion · alchaincyf huashu motion | 让你的agent一键直出商业级产品宣传片：会作曲，能指着画面改。Commercial-grade launch film… |
| ✅ [storytold/cadcraft](https://github.com/storytold/cadcraft) | 5816 | 487 | +197 | 12 | — | cadcraft · storytold cadcraft · artcraft cadcraft | CADCraft: computer-aided design and drafting — an open-sourc… |
| ✅ [storytold/gridcraft](https://github.com/storytold/gridcraft) | 5772 | 483 | +149 | 12 | [3](https://news.ycombinator.com/item?id=50117408) | gridcraft · storytold gridcraft · artcraft gridcraft | GridCraft: an open-source, clean-room spreadsheet (Microsoft… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 94.7 | ✅ 🟢 窗口内 | [storytold/figcraft](https://github.com/storytold/figcraft) | Rust | 2677 | +195 | +2673 | +4 | `···▁··▁▆▆▅█▄▃·` | 9 | [3](https://news.ycombinator.com/item?id=50069000) | — |
| 2 | 85.4 | 🟢 窗口内 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 1604 | +99 | +1230 | +374 | `·····▁▆█▄▃▃▃▂·` | 8 | — | — |
| 3 | 81.5 | 🟢 窗口内 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) | Python | 886 | +192 | +886 | +0 | `·········▄██▅·` | 3 | — | — |
| 4 | 80 | 🆕 🟢 窗口内 | [LiCinCan/blender-ai-mcp-addon](https://github.com/LiCinCan/blender-ai-mcp-addon) | Python | 788 | — | +788 | +0 | `··········▆█▅·` | 3 | — | — |
| 5 | 76.2 | 🟢 窗口内 | [jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) | Python | 1033 | +95 | +570 | +463 | `·····█▄▇▂▁▁▄▃·` | 7 | — | — |
| 6 | 73 | 🆕 🟢 窗口内 | [reason-machines/reason-network](https://github.com/reason-machines/reason-network) | Rust | 438 | — | +438 | +0 | `··········▅█▇·` | 2 | — | — |
| 7 | 66.8 | 🟡 在降温 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | Python | 1819 | +97 | +795 | +1024 | `·▁▁▁▁█▆▃▂▄▃▂▂·` | 13 | [10](https://news.ycombinator.com/item?id=50037852) | — |
| 8 | 59.9 | 🟡 在降温 | [marclou/mailcheap](https://github.com/marclou/mailcheap) | JavaScript | 1237 | +27 | +400 | +837 | `····█▄▂▂▁▃▂▁▁·` | 8 | [2](https://news.ycombinator.com/item?id=50033695) | — |
| 9 | 57.6 | 🟡 在降温 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) | Python | 2237 | +40 | +316 | +382 | `█▆▃▄▂▃▄▃▂▂█▇▃·` | 18 | — | — |
| 10 | 55.9 | 🟡 在降温 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) | TypeScript | 1613 | +29 | +266 | +1347 | `··▃█▇▄▂▂▂▁▁▂▁·` | 11 | — | — |
| 11 | 50.3 | 🟡 在降温 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep) | TypeScript | 2795 | +26 | +152 | +326 | `▅█▇▆▄▇▄▄▂▆▄▂▃·` | 23 | [5](https://news.ycombinator.com/item?id=49880146) | — |
| 12 | 46.5 | 🔴 先核对 | [feder-cr/git-ai](https://github.com/feder-cr/git-ai) | Go | 2310 | +1167 | +2310 | +0 | `·········▇▁▁█·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 13 | 41.1 | 🔴 先核对 | [outcrawlai/scout](https://github.com/outcrawlai/scout) | TypeScript | 946 | +5 | +946 | +0 | `········█▂▁▁▁·` | 5 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 14 | 39 | 🔴 先核对 | [aicodeking/leanrea](https://github.com/aicodeking/leanrea) | Python | 660 | +198 | +660 | +0 | `··········▁█▃·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 15 | 36.4 | 🆕 🔴 先核对 | [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) | C | 429 | — | +429 | +0 | `··········▄▅█·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 16 | 31.8 | 🔴 先核对 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) | Go | 1265 | +36 | +580 | +685 | `··▁▁▁▁█▆▁▁▁▁▁·` | 10 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 30.2 | 🔵 已被发现 | [rociiu/talorys](https://github.com/rociiu/talorys) | TypeScript | 1330 | +25 | +421 | +909 | `····█▅▃▂▂▄▂▂▁·` | 8 | [329](https://news.ycombinator.com/item?id=50031614) | — |
| 18 | 30 | 🔴 先核对 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 1112 | +27 | +399 | +713 | `······█▃▂▂▁▁▁·` | 6 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 27.4 | 🔵 已被发现 | [pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust) | Rust | 1364 | +26 | +238 | +1126 | `·█▄▂▃▂▂▂▂▂▂▁▁·` | 11 | [119](https://news.ycombinator.com/item?id=50000676) | — |
| 20 | 18.9 | 🔴 先核对 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) | Python | 2773 | +7 | +43 | +145 | `▃▂█▄▆▃▃▂▂▃▂▂▂·` | 19 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 526 | 30 | 43880 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[feitangyuan/onetake](https://github.com/feitangyuan/onetake) |
| `mcp` | 181 | 30 | 22751 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) |
| `rust` | 153 | 30 | 19847 | [storytold/figcraft](https://github.com/storytold/figcraft)、[academa-labs/manimgx](https://github.com/academa-labs/manimgx)、[opengeos/RustGIS](https://github.com/opengeos/RustGIS) |
| `local-first` | 57 | 30 | 14002 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[glanderness/BeefTV](https://github.com/glanderness/BeefTV) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 22 | 18763 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) |
| `llm` | 20 | 13437 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) |
| `ai-agents` | 18 | 12876 | [feder-cr/git-ai](https://github.com/feder-cr/git-ai)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill) |
| `codex` | 15 | 13148 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) |
| `agent-skills` | 12 | 12663 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `mcp-server` | 12 | 9150 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `macos` | 12 | 7591 | [freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[amontlabs/lcu](https://github.com/amontlabs/lcu) |
| `ai-agent` | 11 | 9096 | [freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `developer-tools` | 10 | 8891 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill) |
| `python` | 10 | 7621 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai)、[Harvil1/codeAgent](https://github.com/Harvil1/codeAgent) |
| `coding-agents` | 7 | 7847 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[feder-cr/git-ai](https://github.com/feder-cr/git-ai)、[openfilm/openfilm](https://github.com/openfilm/openfilm) |
| `typescript` | 7 | 7805 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust)、[rociiu/talorys](https://github.com/rociiu/talorys) |

**语言分布**：Python 32 · Rust 32 · TypeScript 20 · JavaScript 8 · Go 4 · Swift 4 · Astro 1 · C 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. ✅ [storytold/figcraft](https://github.com/storytold/figcraft) · 🟢 窗口内 · 94.7 分

> FigCraft: interface design and prototyping; an open-source, clean-room reimplementation of collaborative design workflows in pure Rust

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2677 | +2673 | +4 | 1019 | 179 | Rust | Apache-2.0 | 10-09（9 天前） | 今天 |

- **近 14 天每天新增**：`···▁··▁▆▆▅█▄▃·` 0 0 0 1 0 0 3 529 543 404 700 324 173 0
- **势头**：比前 7 天快 668.2 倍，在加速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=50069000)）
- **topics**：`design` `rust` `tools`
- **主页**：<https://getartcraft.com/apps/figcraft>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [opengeos/RustGIS](https://github.com/opengeos/RustGIS) · 🟢 窗口内 · 85.4 分

> A fast, free and open-source GIS in pure Rust.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1604 | +1230 | +374 | 224 | 16 | Rust | Apache-2.0 | 10-10（8 天前） | 今天 |

- **近 14 天每天新增**：`·····▁▆█▄▃▃▃▂·` 0 0 0 0 0 2 372 492 237 143 150 116 92 0
- **势头**：比前 7 天快 3.3 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`geospatial` `gis` `remote-sensing` `rust` `rust-lang`
- **主页**：<https://rustgis.app>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) · 🟢 窗口内 · 81.5 分

> Ears for coding agents: let AI hear, review and make sound. CPU-only, open source.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 886 | +886 | +0 | 52 | 0 | Python | MIT | 10-15（3 天前） | 今天 |

- **近 14 天每天新增**：`·········▄██▅·` 0 0 0 0 0 0 0 0 0 113 309 287 177 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `audio` `claude-code` `mcp` `sound-design`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. 🆕 [LiCinCan/blender-ai-mcp-addon](https://github.com/LiCinCan/blender-ai-mcp-addon) · 🟢 窗口内 · 80 分

> AI assistant and MCP server for Blender: visual chat, scene tools, multi-agent workflows. Works with OpenAI, ChatGPT, Claude, Gemini, Ollama, OpenCode. Blender AI addon and plugin, copilot for 3D, bpy Python scripting, MCP integration.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 788 | +788 | +0 | 377 | 31 | Python | MIT | 10-15（3 天前） | 今天 |

- **近 14 天每天新增**：`··········▆█▅·` 0 0 0 0 0 0 0 0 0 0 257 336 195 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-assistant` `blender` `blender-addon` `blender-ai` `blender-automation` `blender-extension` `blender-mcp` `blender-plugin` `blender-python` `blender-scripting` `bpy` `chatgpt` `gpt` `llm` `mcp` `mcp-for-blender` `mcp-server` `model-context-protocol` `opencode` `python`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) · 🟢 窗口内 · 76.2 分

> Trace-native CI/CD for AI agents: grade production traces, cluster failures, freeze them into replayable regression tests, and block PRs that regress. Self-hostable.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1033 | +570 | +463 | 143 | 20 | Python | MIT | 10-11（7 天前） | 3 天前 |

- **近 14 天每天新增**：`·····█▄▇▂▁▁▄▃·` 0 0 0 0 0 331 132 300 50 8 5 126 81 0
- **势头**：比前 7 天快 1.2 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-evaluation` `ai-agents` `ai-testing` `ci-cd` `clickhouse` `developer-tools` `llm-evaluation` `llm-observability` `llmops` `mcp` `observability` `python` `regression-testing` `self-hosted` `tracing`
- **主页**：<https://tracely-ai.com>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. 🆕 [reason-machines/reason-network](https://github.com/reason-machines/reason-network) · 🟢 窗口内 · 73 分

> Reason Network: your team's coding agents, talking to each other. The engine behind `reason network`.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 438 | +438 | +0 | 32 | 0 | Rust | Apache-2.0 | 10-16（2 天前） | 今天 |

- **近 14 天每天新增**：`··········▅█▇·` 0 0 0 0 0 0 0 0 0 0 108 180 150 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`coding-agents` `iroh` `mcp` `peer-to-peer` `reason`
- **主页**：<https://reasonmachines.com>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [academa-labs/manimgx](https://github.com/academa-labs/manimgx) · 🟡 在降温 · 66.8 分

> The animation engine for agents: blazingly fast math and 3D videos with Manim's Python API, on a Rust GPU core.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1819 | +795 | +1024 | 128 | 24 | Python | MIT | 10-05（13 天前） | 3 天前 |

- **近 14 天每天新增**：`·▁▁▁▁█▆▃▂▄▃▂▂·` 0 7 31 11 40 567 368 125 106 235 159 84 86 0
- **势头**：只有前 7 天的 78%，在减速
- **HN**：发过 1 次，最高 10 分（[讨论](https://news.ycombinator.com/item?id=50037852)）
- **主页**：<https://manimgx.academa.ai>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [marclou/mailcheap](https://github.com/marclou/mailcheap) · 🟡 在降温 · 59.9 分

> Newsletters where you pay for the emails you send, not for dormant subscribers, at a fraction of the price of beehiiv and the like. Open source: self-host it, or use mailcheap.ai.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1237 | +400 | +837 | 316 | 12 | JavaScript | AGPL-3.0 | 10-10（8 天前） | 今天 |

- **近 14 天每天新增**：`····█▄▂▂▁▃▂▁▁·` 0 0 0 0 572 213 52 63 30 147 107 27 26 0
- **势头**：只有前 7 天的 48%，在减速
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50033695)）
- **topics**：`ai-agents` `amazon-ses` `beehiiv-alternative` `email` `email-marketing` `mailchimp-alternative` `mcp` `mcp-server` `mongodb` `newsletter` `nextjs` `self-hosted` `substack-alternative`
- **主页**：<https://mailcheap.ai>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) · 🟡 在降温 · 57.6 分

> AI生成の日本語を自然な日本語へ推敲するAgent Skill / Agent Skill for Refining AI-Generated Japanese into Natural Japanese

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2237 | +316 | +382 | 74 | 0 | Python | MIT | 09-30（18 天前） | 今天 |

- **近 14 天每天新增**：`█▆▃▄▂▃▄▃▂▂█▇▃·` 111 78 37 47 23 37 49 33 18 22 115 91 37 0
- **势头**：只有前 7 天的 83%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-writing` `antigravity` `claude-code` `codex` `cursor` `gemini` `japanese` `linter` `llm` `nlp` `writing` `writing-assistant` `writing-tool`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) · 🟡 在降温 · 55.9 分

> Your company's data, connected into one ontology, on your own computer. A local-first data workspace built on HelixDB and DuckDB.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1613 | +266 | +1347 | 243 | 17 | TypeScript | Apache-2.0 | 10-07（11 天前） | 5 天前 |

- **近 14 天每天新增**：`··▃█▇▄▂▂▂▁▁▂▁·` 0 0 137 504 427 180 99 66 60 19 29 68 24 0
- **势头**：只有前 7 天的 20%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [feder-cr/git-ai](https://github.com/feder-cr/git-ai) — 一天进了一半以上的 star，但 HN 上没火过
- [outcrawlai/scout](https://github.com/outcrawlai/scout) — 一天进了一半以上的 star，但 HN 上没火过
- [aicodeking/leanrea](https://github.com/aicodeking/leanrea) — 一天进了一半以上的 star，但 HN 上没火过
- [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) — 一天进了一半以上的 star，但 HN 上没火过
- [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) — 一天进了一半以上的 star，但 HN 上没火过
- [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) — 一天进了一半以上的 star，但 HN 上没火过
- [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 572 | 161 | [Show HN: Guitoro, a virtual guitar you strum with your keyboard](https://guitoro.com/) | [HN](https://news.ycombinator.com/item?id=50077020) |
| 322 | 86 | [Show HN: Llmspeed – feel how fast a local LLM runs before you buy the hardware](https://llmspeed.dev/) | [HN](https://news.ycombinator.com/item?id=50127979) |
| 316 | 200 | [Show HN: Unfenced – Land for sale that borders public land](https://unfenced.land/) | [HN](https://news.ycombinator.com/item?id=50102247) |
| 314 | 158 | [Show HN: PS2 games statically recompiled to WebAssembly](https://github.com/snuri00/ps2-web-recomp) | [HN](https://news.ycombinator.com/item?id=50052251) |
| 249 | 111 | [Show HN: Gemini 4 Argon plays StarCraft](https://starskirmish.com/bench/v0-2/) | [HN](https://news.ycombinator.com/item?id=50118688) |
| 242 | 85 | [Show HN: Sphinx – A hook that quizzes you on your AI's code before shipping](https://sphinx-six-theta.vercel.app/) | [HN](https://news.ycombinator.com/item?id=50137950) |
| 226 | 41 | [Show HN: Petal, open-source CoScreen/ScreenHero finally free](https://petal.live/) | [HN](https://news.ycombinator.com/item?id=50092470) |
| 216 | 120 | [Show HN: How random are you?](https://lab.specr.net/rigged-draw/) | [HN](https://news.ycombinator.com/item?id=50074909) |
| 193 | 41 | [Show HN: Esp32sim – Run ESP32 firmware in the browser](https://github.com/mikroverk/esp32sim) | [HN](https://news.ycombinator.com/item?id=50131189) |
| 174 | 91 | [Show HN: Use your OpenAI subscription to create audiobooks](https://pdftomp3.com/connect-ai/) | [HN](https://news.ycombinator.com/item?id=50069337) |
| 172 | 103 | [Show HN: The Zelda timeline to catch up before the Ocarina of Time remake](https://legendofhyrule.com/) | [HN](https://news.ycombinator.com/item?id=50140769) |
| 170 | 43 | [Show HN: High-quality duck audio synthesizer](https://celphase.github.io/duck-pond/) | [HN](https://news.ycombinator.com/item?id=50131006) |
| 146 | 71 | [Show HN: Flipflop – Iroh-powered persistent tunnels for filesharing](https://github.com/andunieee/flipflop) | [HN](https://news.ycombinator.com/item?id=50099136) |
| 144 | 51 | [Show HN: SolidCraft – Open-Source Parametric CAD in Rust (With MCP Support)](https://github.com/bherbruck/solidcraft) | [HN](https://news.ycombinator.com/item?id=50064840) |
| 121 | 71 | [Show HN: Pulse Local, a Mac budgeting app whose AI models run on your machine](https://pulseos.finance) | [HN](https://news.ycombinator.com/item?id=50080275) |
| 119 | 95 | [Show HN: Wonderhop – A daily game: guess what most people say, or what none do](https://wonderhop.io/en/) | [HN](https://news.ycombinator.com/item?id=50080246) |
| 119 | 76 | [Show HN: I built a tool to track what AI leaders say and how their views change](https://blumify.io/people) | [HN](https://news.ycombinator.com/item?id=50081151) |
| 119 | 48 | [Show HN: Indigene – Native plants for where you stand](https://indigene.app/) | [HN](https://news.ycombinator.com/item?id=50064470) |
| 114 | 99 | [Show HN: I wrote an email app that accepts only one sender per inbox](https://clova.email/) | [HN](https://news.ycombinator.com/item?id=50090932) |
| 107 | 36 | [Show HN: Proa – A Rust web framework with fast SSR and multi-target rendering](https://proa.so/) | [HN](https://news.ycombinator.com/item?id=50105467) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 115 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 6479★ |
| 28 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 5791★ |
| 153 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 111866★ |
| 60 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 41147★ |
| 344 | [Any Time, Any Space: A World-State-Centric Framework for Agentic Video Generation](https://huggingface.co/papers/2610.20571) | ATAS improves long-form video consistency by compiling screenplays into referenced shot requests, retrieving spatial and temporal evidence f… | 💡 [ziplab/ATAS](https://github.com/ziplab/ATAS) 280★ |
| 50 | [RSI-Anything: Unlocking Recursive Self-Improvement with World Models](https://huggingface.co/papers/2610.13912) | RSI-Anything leverages predictive world models to guide action selection and adaptive learning, enabling recursive self-improvement across c… | 💡 [Gen-Verse/RSI-Anything](https://github.com/Gen-Verse/RSI-Anything) 785★ |
| 93 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 27821★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 116 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 1462★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 91205★ |
| 31 | [Internal Safety Collapse in Frontier Large Language Models](https://huggingface.co/papers/2603.23509) | Frontier large language models exhibit Internal Safety Collapse, where they generate harmful content under specific task conditions, reveali… | [wuyoscar/ISC-Bench](https://github.com/wuyoscar/ISC-Bench) 1703★ |
| 238 | [YuE2: Unifying Symbolic and Audio Music Generation at Frontier Quality](https://huggingface.co/papers/2609.33757) | YuE2 unifies symbolic and audio music generation via symbolic planning, producing readable scores and full-song audio with state-of-the-art… | [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE) 12135★ |
| 9 | [Native and Compact Structured Latents for 3D Generation](https://huggingface.co/papers/2512.14692) | A new sparse voxel representation called O-Voxel enables high-quality 3D generative modeling with efficient inference and robust topology ha… | [microsoft/TRELLIS.2](https://github.com/microsoft/TRELLIS.2) 12229★ |
| 336 | [Player-1: Learning to Play from Synthetic Experience](https://huggingface.co/papers/2610.20584) | Player-1 improves game control by combining supervised fine-tuning on gameplay trajectories with reinforcement learning across synthetic env… | 💡 [TencentARC/Player-1](https://github.com/TencentARC/Player-1) 155★ |
| 203 | [Self-Evolving Agent Harness](https://huggingface.co/papers/2610.18813) | A framework for self-evolving agent harnesses uses feedback-driven revisions and evolutionary optimization with theoretical generalization g… | 💡 [zgcagi/Harness-RSI](https://github.com/zgcagi/Harness-RSI) 206★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 81982★ |
| 84 | [RAG-Anything: All-in-One RAG Framework](https://huggingface.co/papers/2510.12323) | RAG-Anything is a unified framework that enhances multimodal knowledge retrieval by integrating cross-modal relationships and semantic match… | [HKUDS/RAG-Anything](https://github.com/HKUDS/RAG-Anything) 23814★ |
| 14 | [StartLux-Decision: AutoThink Decision Models with Reinforcement Learning for Calibrated Deliberative…](https://huggingface.co/papers/2610.17309) | StartLux-Decision introduces efficient and adaptive decision models using single-pass prediction and confidence-guided reasoning, trained vi… | 💡 [StartLuxLabs/StartLux-Decision](https://github.com/StartLuxLabs/StartLux-Decision) 689★ |
| 213 | [Agent-Reflex: Teaching Language Agents to Act Reflectively](https://huggingface.co/papers/2610.17953) | Agent-Reflex trains interactive agents to reflect and recover from noisy tool feedback and user corrections through skill discovery, supervi… | 💡 [RUC-NLPIR/Agent-Reflex](https://github.com/RUC-NLPIR/Agent-Reflex) 230★ |
| 343 | [VisionHOPE: Visual Backbones as Self-Modifying Learning Systems](https://huggingface.co/papers/2609.33325) | VisionHOPE introduces a self-modifying visual backbone where memory and learning co-evolve through coupled memories and stability-controlled… | [PSRben/VisionHOPE](https://github.com/PSRben/VisionHOPE) 1272★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

_这次没有（新上榜 0 个）。_

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 67 | 40 | [Updates to site guidelines and AI/LLM tags](https://lobste.rs/s/h0eate) | `announce` `meta` | [讨论](https://lobste.rs/s/h0eate/updates_site_guidelines_ai_llm_tags) |
| 264 | 254 | [It's enough - vibecoding tag crossed from useless to harmful](https://lobste.rs/s/ggpwfi) | `meta` `vibecoding` | [讨论](https://lobste.rs/s/ggpwfi/it_s_enough_vibecoding_tag_crossed_from) |
| 35 | 13 | [ARP! Tell your network to explain itself](https://benjcal.space/blog/arp-tell-your-network-to-explain-itself/) | `networking` | [讨论](https://lobste.rs/s/mmvhup/arp_tell_your_network_explain_itself) |
| 32 | 3 | [A New Way to Think About Borrow Checking (In Reverse)](https://verdagon.dev/blog/reverse-borrow-checking) | `compilers` | [讨论](https://lobste.rs/s/vwgrix/new_way_think_about_borrow_checking) |
| 60 | 7 | [Men in tech #YesAllMen](https://media.ccc.de/v/emf2026-240-1-men-in-tech-yesallmen) | `culture` `video` | [讨论](https://lobste.rs/s/mp8qye/men_tech_yesallmen) |
| 26 | 0 | [Outside the Scope of Our Support](https://fireborn.mataroa.blog/blog/outside-the-scope-of-our-support/) | `a11y` `android` | [讨论](https://lobste.rs/s/brrnpm/outside_scope_our_support) |
| 11 | 0 | [QML for C & Zig](https://gist.github.com/rcalixte/d2de5c816fc1de3970cc501b5ae9706e) | `c` `zig` | [讨论](https://lobste.rs/s/izjf9o/qml_for_c_zig) |
| 13 | 10 | [My obituary for programming](https://dumbmatter.com/2026/10/programming-obituary/) | `vibecoding` | [讨论](https://lobste.rs/s/wtobpt/my_obituary_for_programming) |
| 15 | 2 | [High performance policy routed IPsec mesh SD-WAN](https://ranet3.com/) | `networking` | [讨论](https://lobste.rs/s/np6czp/high_performance_policy_routed_ipsec) |
| 10 | 0 | [Superoptimizing an FPU emulator](https://purplesyringa.moe/blog/superoptimizing-an-fpu-emulator/) | `performance` `rust` | [讨论](https://lobste.rs/s/1s3dve/superoptimizing_fpu_emulator) |
| 9 | 1 | [How Discover-Tech turned targeted ads into a pipeline for zero-click spywares](https://citizenlab.ca/research/how-discover-tech-turned-targeted-ads-into-a-pipeline-for-spyware/) | `privacy` `security` | [讨论](https://lobste.rs/s/zytoux/how_discover_tech_turned_targeted_ads) |
| 38 | 14 | [The Brain Sandwich](https://terriblesoftware.org/2026/10/02/the-brain-sandwich/) | `vibecoding` | [讨论](https://lobste.rs/s/k5omum/brain_sandwich) |
| 15 | 0 | [Inside the Intel 8087 chip: floating-point addition and subtraction](https://www.righto.com/2026/10/8087-addition-subtraction-microcode.html) | `hardware` | [讨论](https://lobste.rs/s/nbxnh7/inside_intel_8087_chip_floating_point) |
| 6 | 0 | [Inline rendering with document.currentScript](https://leanrada.com/notes/inline-rendering-currentscript/) | `javascript` | [讨论](https://lobste.rs/s/ogp1wf/inline_rendering_with_document) |
| 7 | 0 | [August in Servo: CSS Grid, text selection, and more](https://servo.org/blog/2026/10/09/august-in-servo/) | `browsers` | [讨论](https://lobste.rs/s/ilul4v/august_servo_css_grid_text_selection_more) |
| 8 | 4 | [The Problem with C++ Safety: Why “It Works” Isn’t Good Enough](https://www.modernescpp.com/index.php/cpp-and-memory-safety-part-1/) | `c++` | [讨论](https://lobste.rs/s/koipdp/problem_with_c_safety_why_it_works_isn_t) |
| 8 | 1 | [Ghidra + CBMC = Assembly Model Checker](https://www.philipzucker.com/asmc_cpp/) | `formalmethods` | [讨论](https://lobste.rs/s/br0hd7/ghidra_cbmc_assembly_model_checker) |
| 2 | 0 | [What the heck is /pkg?](https://anderegg.ca/2026/10/18/what-the-heck-is-pkg) | `mac` `unix` | [讨论](https://lobste.rs/s/w6xosj/what_heck_is_pkg) |
| 4 | 0 | [Real-time Software On Linux: How Hard Can It Be?](https://www.youtube.com/watch?v=-0D0rFdU6HY) | `linux` `video` `zig` | [讨论](https://lobste.rs/s/jp6tfb/real_time_software_on_linux_how_hard_can_it) |
| 2 | 0 | [Dynamic Packages](https://www.getlazarus.org/dynamic/) | `editors` `release` | [讨论](https://lobste.rs/s/dc2efo/dynamic_packages) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

_还没有到 14 天的，54 个在等。_

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
