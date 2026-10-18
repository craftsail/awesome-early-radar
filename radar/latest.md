# early-radar 选题雷达 · 2026-10-18

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 111 个，细查前 20 个 · 比上次 = 和 2026-10-17 那次比 · 生成于 2026-10-18 04:06 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 1 个 · Show HN ✅ 29 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 0 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 5 个 · 🟡 在降温 6 个 · 🔵 已被发现 2 个 · 💤 不活跃 0 个 · 🔴 先核对 7 个
- **今天新出现 3 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) 平均每天 +1566，见 [爆发](#爆发)
- **最值得今天试的**：
  - [opengeos/RustGIS](https://github.com/opengeos/RustGIS) — A fast, free and open-source GIS in pure Rust.（近 7 天 +1503，比前 7 天快 751.5 倍，在加速）
  - [academa-labs/manimgx](https://github.com/academa-labs/manimgx) — The animation engine for agents: blazingly fast math and 3D…（近 7 天 +1066，比前 7 天快 1.6 倍，在加速）
  - [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) — Ears for coding agents: let AI hear, review and make sound.…（近 7 天 +694，刚发布一周内）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 20 个（star 合计 16807），代表：[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：6 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Guitoro, a virtual guitar you strum with your keyboard](https://guitoro.com/) — 571 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) | 15257 | 1566 | +1170 | 9.7 | — | anatomy · wheresryan22 anatomy · ryan anatomy | An agent skill for creating detailed, interactive isometric… |
| [openai/math](https://github.com/openai/math) | 15115 | 1342 | +75 | 11.3 | [342](https://news.ycombinator.com/item?id=50003107) | math · openai math |  |
| ✅ [storytold/wordcraft](https://github.com/storytold/wordcraft) | 14090 | 1303 | +386 | 10.8 | [101](https://news.ycombinator.com/item?id=50050370) | wordcraft · storytold wordcraft · artcraft wordcraft | An open-source, clean-room reimplementation of Microsoft Wor… |
| 🆕 [tangency-labs/solidcraft](https://github.com/tangency-labs/solidcraft) | 4409 | 425 | +1283 | 10.4 | — | solidcraft · tangency-labs solidcraft · tangency solidcraft | SolidCraft: an open-source parametric 3D CAD application bui… |
| 🆕 [google-research/harness2](https://github.com/google-research/harness2) | 1688 | 150 | +1010 | 11.3 | — | harness2 · google-research harness2 · google harness2 |  |
| [jhaizhou-ops/d2r-mobile](https://github.com/jhaizhou-ops/d2r-mobile) | 3734 | 643 | +176 | 5.8 | — | d2r mobile · jhaizhou-ops d2r mobile | Open-source iOS / macOS compatibility layer for Diablo II: R… |
| [chenglou/handwired](https://github.com/chenglou/handwired) | 1683 | 547 | +100 | 3.1 | [3](https://news.ycombinator.com/item?id=50105735) | handwired · chenglou handwired · cheng handwired | Turn your regular JavaScript code into a neural net. |
| [ahwootech/BRUTAL](https://github.com/ahwootech/BRUTAL) | 1805 | 538 | +209 | 3.4 | [9](https://news.ycombinator.com/item?id=50100170) | brutal · ahwootech brutal · ahwoo brutal | A free, open source C# framework for making games, or your o… |
| [Arekejoker/qwen21-nsfw-pose-skill](https://github.com/Arekejoker/qwen21-nsfw-pose-skill) | 2659 | 528 | +114 | 5 | — | qwen21 nsfw pose skill · arekejoker qwen21 nsfw pose skill | Qwen-Image 2.1 NSFW/姿势出图 skill：作者级提示词配方 + NSFW LoRA + 136 姿势… |
| ✅ [storytold/gridcraft](https://github.com/storytold/gridcraft) | 5623 | 514 | +198 | 11 | [3](https://news.ycombinator.com/item?id=50117408) | gridcraft · storytold gridcraft · artcraft gridcraft | GridCraft: an open-source, clean-room spreadsheet (Microsoft… |
| ✅ [storytold/cadcraft](https://github.com/storytold/cadcraft) | 5619 | 513 | +196 | 10.9 | — | cadcraft · storytold cadcraft · artcraft cadcraft | CADCraft: computer-aided design and drafting — an open-sourc… |
| [ARahim3/DigUp](https://github.com/ARahim3/DigUp) | 4614 | 496 | +262 | 9.3 | [5](https://news.ycombinator.com/item?id=50045015) | digup · arahim3 digup · abdur digup | Search your computer by what's in your files: photos, PDFs,… |
| 🆕 [xscreensaver-official/xscreensaver](https://github.com/xscreensaver-official/xscreensaver) | 737 | 496 | +435 | 1.5 | — | xscreensaver · xscreensaver-official xscreensaver · xscreensaver xscreensaver | There is no official XScreenSaver GitHub repository. |
| [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) | 3015 | 473 | +133 | 6.4 | [3](https://news.ycombinator.com/item?id=50102527) | esp32 iphone agent · onehumanbeing esp32 iphone agent · henry esp32 iphone agent | Let an AI model use a real iPhone with a $7 ESP32: AirPlay e… |
| [HeyPuter/everything](https://github.com/HeyPuter/everything) | 2073 | 462 | +303 | 4.5 | [8](https://news.ycombinator.com/item?id=50075719) | everything · heyputer everything · puter everything | We're rebuilding and open-sourcing the world’s software from… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 93.8 | ✅ 🟢 窗口内 | [storytold/figcraft](https://github.com/storytold/figcraft) | Rust | 2482 | +372 | +2481 | +1 | `····▁··▁▆▆▅█▄·` | 8 | [3](https://news.ycombinator.com/item?id=50069000) | — |
| 2 | 87.8 | 🟢 窗口内 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 1505 | +135 | +1503 | +2 | `······▁▆█▄▃▃▃·` | 7 | — | — |
| 3 | 83.7 | 🟢 窗口内 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | Python | 1722 | +90 | +1066 | +656 | `··▁▁▁▁█▆▃▂▄▃▂·` | 12 | [10](https://news.ycombinator.com/item?id=50037852) | — |
| 4 | 78.5 | 🟢 窗口内 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) | Python | 694 | +327 | +694 | +0 | `··········▄█▇·` | 2 | — | — |
| 5 | 76.9 | 🆕 🟢 窗口内 | [jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) | Python | 938 | +109 | +606 | +332 | `······█▄▇▂▁▁▃·` | 6 | — | — |
| 6 | 61 | 🟡 在降温 | [feitangyuan/onetake](https://github.com/feitangyuan/onetake) | Python | 2600 | +59 | +446 | +618 | `███▅▅▄▄▆▆▆▅▅▄·` | 21 | — | — |
| 7 | 60.5 | 🟡 在降温 | [marclou/mailcheap](https://github.com/marclou/mailcheap) | JavaScript | 1210 | +37 | +425 | +785 | `·····█▄▂▂▁▃▂▁·` | 7 | [2](https://news.ycombinator.com/item?id=50033695) | — |
| 8 | 60.1 | 🟡 在降温 | [oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) | Python | 1696 | +57 | +407 | +760 | `▄█▄▃▃▂▃▄▂▂▂▄▂·` | 18 | — | — |
| 9 | 58.2 | 🟡 在降温 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) | TypeScript | 1584 | +70 | +336 | +1248 | `···▃█▇▄▂▂▂▁▁▂·` | 10 | — | — |
| 10 | 57.9 | 🟡 在降温 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) | Python | 2197 | +115 | +325 | +444 | `██▆▃▄▂▃▄▃▂▂█▆·` | 17 | — | — |
| 11 | 50.6 | 🟡 在降温 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep) | TypeScript | 2769 | +14 | +157 | +348 | `▆▅█▇▆▄▇▄▄▂▆▄▂·` | 21 | [5](https://news.ycombinator.com/item?id=49880146) | — |
| 12 | 42.6 | 🔴 先核对 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) | Go | 1229 | +20 | +1216 | +13 | `···▁▁▁▁█▆▁▁▁▁·` | 9 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 13 | 42.3 | 🔴 先核对 | [feder-cr/git-ai](https://github.com/feder-cr/git-ai) | Go | 1143 | +76 | +1143 | +0 | `··········█▁▁·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 14 | 41.9 | 🔴 先核对 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 1085 | +18 | +1085 | +0 | `·······█▃▂▂▁▁·` | 5 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 15 | 41.1 | 🔴 先核对 | [outcrawlai/scout](https://github.com/outcrawlai/scout) | TypeScript | 941 | +41 | +941 | +0 | `·········█▂▁▁·` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 16 | 38.8 | 🆕 🔴 先核对 | [anujasid/blender-ai-mcp-addon](https://github.com/anujasid/blender-ai-mcp-addon) | Python | 642 | — | +642 | +0 | `···········▆█·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 36.8 | 🆕 🔴 先核对 | [aicodeking/leanrea](https://github.com/aicodeking/leanrea) | Python | 462 | — | +462 | +0 | `···········▁█·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 31.3 | 🔵 已被发现 | [rociiu/talorys](https://github.com/rociiu/talorys) | TypeScript | 1305 | +48 | +523 | +782 | `·····█▅▃▂▂▄▂▂·` | 7 | [329](https://news.ycombinator.com/item?id=50031614) | — |
| 19 | 28 | 🔵 已被发现 | [pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust) | Rust | 1338 | +34 | +272 | +1066 | `··█▄▂▃▂▂▂▂▂▂▁·` | 10 | [119](https://news.ycombinator.com/item?id=50000676) | — |
| 20 | 19.4 | 🔴 先核对 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) | Python | 2766 | +5 | +47 | +147 | `▃▃▂█▄▆▃▃▂▂▃▂▂·` | 18 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 530 | 30 | 41624 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[feitangyuan/onetake](https://github.com/feitangyuan/onetake) |
| `mcp` | 178 | 30 | 19952 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `rust` | 150 | 30 | 19294 | [storytold/figcraft](https://github.com/storytold/figcraft)、[academa-labs/manimgx](https://github.com/academa-labs/manimgx)、[opengeos/RustGIS](https://github.com/opengeos/RustGIS) |
| `local-first` | 57 | 30 | 13667 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[glanderness/BeefTV](https://github.com/glanderness/BeefTV) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 20 | 16807 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) |
| `ai-agents` | 20 | 11716 | [penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `llm` | 19 | 11390 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[receptron/laya](https://github.com/receptron/laya) |
| `codex` | 13 | 11561 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) |
| `macos` | 13 | 7801 | [freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[amontlabs/lcu](https://github.com/amontlabs/lcu) |
| `agent-skills` | 12 | 11957 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `ai-agent` | 12 | 8776 | [freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `mcp-server` | 11 | 8296 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `python` | 11 | 7468 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai)、[Harvil1/codeAgent](https://github.com/Harvil1/codeAgent) |
| `developer-tools` | 9 | 8460 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill) |
| `typescript` | 8 | 7831 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `model-context-protocol` | 8 | 5419 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[anujasid/blender-ai-mcp-addon](https://github.com/anujasid/blender-ai-mcp-addon)、[graygnatconsole/mcp-audit-tool](https://github.com/graygnatconsole/mcp-audit-tool) |

**语言分布**：Python 34 · Rust 31 · TypeScript 21 · JavaScript 8 · Go 4 · Swift 4 · Astro 1 · C++ 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. ✅ [storytold/figcraft](https://github.com/storytold/figcraft) · 🟢 窗口内 · 93.8 分

> FigCraft: interface design and prototyping; an open-source, clean-room reimplementation of collaborative design workflows in pure Rust

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2482 | +2481 | +1 | 911 | 146 | Rust | Apache-2.0 | 10-09（8 天前） | 今天 |

- **近 14 天每天新增**：`····▁··▁▆▆▅█▄·` 0 0 0 0 1 0 0 3 529 545 405 700 299 0
- **势头**：比前 7 天快 2481.0 倍，在加速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=50069000)）
- **topics**：`design` `rust` `tools`
- **主页**：<https://getartcraft.com/apps/figcraft>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [opengeos/RustGIS](https://github.com/opengeos/RustGIS) · 🟢 窗口内 · 87.8 分

> A fast, free and open-source GIS in pure Rust.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1505 | +1503 | +2 | 205 | 20 | Rust | Apache-2.0 | 10-10（7 天前） | 今天 |

- **近 14 天每天新增**：`······▁▆█▄▃▃▃·` 0 0 0 0 0 0 2 372 492 237 143 150 109 0
- **势头**：比前 7 天快 751.5 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`geospatial` `gis` `remote-sensing` `rust` `rust-lang`
- **主页**：<https://rustgis.app>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [academa-labs/manimgx](https://github.com/academa-labs/manimgx) · 🟢 窗口内 · 83.7 分

> The animation engine for agents: blazingly fast math and 3D videos with Manim's Python API, on a Rust GPU core.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1722 | +1066 | +656 | 120 | 24 | Python | MIT | 10-05（12 天前） | 2 天前 |

- **近 14 天每天新增**：`··▁▁▁▁█▆▃▂▄▃▂·` 0 0 7 31 11 40 567 368 125 106 235 159 73 0
- **势头**：比前 7 天快 1.6 倍，在加速
- **HN**：发过 1 次，最高 10 分（[讨论](https://news.ycombinator.com/item?id=50037852)）
- **主页**：<https://manimgx.academa.ai>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) · 🟢 窗口内 · 78.5 分

> Ears for coding agents: let AI hear, review and make sound. CPU-only, open source.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 694 | +694 | +0 | 42 | 0 | Python | MIT | 10-15（2 天前） | 今天 |

- **近 14 天每天新增**：`··········▄█▇·` 0 0 0 0 0 0 0 0 0 0 113 309 272 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `audio` `claude-code` `mcp` `sound-design`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. 🆕 [jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) · 🟢 窗口内 · 76.9 分

> Trace-native CI/CD for AI agents: grade production traces, cluster failures, freeze them into replayable regression tests, and block PRs that regress. Self-hostable.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 938 | +606 | +332 | 139 | 19 | Python | MIT | 10-11（6 天前） | 2 天前 |

- **近 14 天每天新增**：`······█▄▇▂▁▁▃·` 0 0 0 0 0 0 332 132 300 50 8 5 111 0
- **势头**：比前 7 天快 1.8 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-evaluation` `ai-agents` `ai-testing` `ci-cd` `clickhouse` `developer-tools` `llm-evaluation` `llm-observability` `llmops` `mcp` `observability` `python` `regression-testing` `self-hosted` `tracing`
- **主页**：<https://tracely-ai.com>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [feitangyuan/onetake](https://github.com/feitangyuan/onetake) · 🟡 在降温 · 61 分

> Motion films that never cut to the next slide: every beat grows out of the one before, one continuous camera, continuity measured by an oracle. Product launch films and feature demos, made with a coding agent.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2600 | +446 | +618 | 172 | 3 | Python | — | 09-26（21 天前） | 5 天前 |

- **近 14 天每天新增**：`███▅▅▄▄▆▆▆▅▅▄·` 123 122 119 77 69 58 50 86 80 84 73 73 50 0
- **势头**：只有前 7 天的 72%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `animation` `canvas` `claude-skill` `launch-video` `motion-graphics` `video`
- **主页**：<https://onetakemotion.com>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 7. [marclou/mailcheap](https://github.com/marclou/mailcheap) · 🟡 在降温 · 60.5 分

> Newsletters where you pay for the emails you send, not for dormant subscribers, at a fraction of the price of beehiiv and the like. Open source: self-host it, or use mailcheap.ai.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1210 | +425 | +785 | 309 | 12 | JavaScript | AGPL-3.0 | 10-10（7 天前） | 今天 |

- **近 14 天每天新增**：`·····█▄▂▂▁▃▂▁·` 0 0 0 0 0 572 213 52 63 30 147 107 26 0
- **势头**：只有前 7 天的 54%，在减速
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50033695)）
- **topics**：`ai-agents` `amazon-ses` `beehiiv-alternative` `email` `email-marketing` `mailchimp-alternative` `mcp` `mcp-server` `mongodb` `newsletter` `nextjs` `self-hosted` `substack-alternative`
- **主页**：<https://mailcheap.ai>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) · 🟡 在降温 · 60.1 分

> UI design skill for Claude Code, Codex and other AI agents: explore distinct directions, compare them side by side, refine against real screenshots. 给 AI Agent 用的 UI 设计 Skill。

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1696 | +407 | +760 | 96 | 0 | Python | MIT | 09-30（18 天前） | 今天 |

- **近 14 天每天新增**：`▄█▄▃▃▂▃▄▂▂▂▄▂·` 117 267 121 63 67 54 71 109 50 41 44 118 45 0
- **势头**：只有前 7 天的 54%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-design` `claude-code` `claude-skills` `codex` `frontend` `ui-design` `ux-design`
- **主页**：<https://ui.oiloil.org>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) · 🟡 在降温 · 58.2 分

> Your company's data, connected into one ontology, on your own computer. A local-first data workspace built on HelixDB and DuckDB.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1584 | +336 | +1248 | 239 | 16 | TypeScript | Apache-2.0 | 10-07（10 天前） | 4 天前 |

- **近 14 天每天新增**：`···▃█▇▄▂▂▂▁▁▂·` 0 0 0 137 504 427 180 99 66 60 19 29 63 0
- **势头**：只有前 7 天的 27%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) · 🟡 在降温 · 57.9 分

> AI生成の日本語を自然な日本語へ推敲するAgent Skill / Agent Skill for Refining AI-Generated Japanese into Natural Japanese

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2197 | +325 | +444 | 68 | 0 | Python | MIT | 09-30（17 天前） | 今天 |

- **近 14 天每天新增**：`██▆▃▄▂▃▄▃▂▂█▆·` 111 111 78 37 47 23 37 49 33 18 22 115 88 0
- **势头**：只有前 7 天的 73%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-writing` `antigravity` `claude-code` `codex` `cursor` `gemini` `japanese` `linter` `llm` `nlp` `writing` `writing-assistant` `writing-tool`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) — 一天进了一半以上的 star，但 HN 上没火过
- [feder-cr/git-ai](https://github.com/feder-cr/git-ai) — 一天进了一半以上的 star，但 HN 上没火过
- [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) — 一天进了一半以上的 star，但 HN 上没火过
- [outcrawlai/scout](https://github.com/outcrawlai/scout) — 一天进了一半以上的 star，但 HN 上没火过
- [anujasid/blender-ai-mcp-addon](https://github.com/anujasid/blender-ai-mcp-addon) — 一天进了一半以上的 star，但 HN 上没火过
- [aicodeking/leanrea](https://github.com/aicodeking/leanrea) — 一天进了一半以上的 star，但 HN 上没火过
- [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 571 | 161 | [Show HN: Guitoro, a virtual guitar you strum with your keyboard](https://guitoro.com/) | [HN](https://news.ycombinator.com/item?id=50077020) |
| 314 | 200 | [Show HN: Unfenced – Land for sale that borders public land](https://unfenced.land/) | [HN](https://news.ycombinator.com/item?id=50102247) |
| 314 | 158 | [Show HN: PS2 games statically recompiled to WebAssembly](https://github.com/snuri00/ps2-web-recomp) | [HN](https://news.ycombinator.com/item?id=50052251) |
| 264 | 77 | [Show HN: Llmspeed – feel how fast a local LLM runs before you buy the hardware](https://llmspeed.dev/) | [HN](https://news.ycombinator.com/item?id=50127979) |
| 242 | 108 | [Show HN: Gemini 4 Argon plays StarCraft](https://starskirmish.com/bench/v0-2/) | [HN](https://news.ycombinator.com/item?id=50118688) |
| 224 | 41 | [Show HN: Petal, open-source CoScreen/ScreenHero finally free](https://petal.live/) | [HN](https://news.ycombinator.com/item?id=50092470) |
| 220 | 127 | [Show HN: BetterWispr – Free, open-source dictation for Mac](https://betterwispr.com/) | [HN](https://news.ycombinator.com/item?id=50042333) |
| 215 | 120 | [Show HN: How random are you?](https://lab.specr.net/rigged-draw/) | [HN](https://news.ycombinator.com/item?id=50074909) |
| 174 | 90 | [Show HN: Use your OpenAI subscription to create audiobooks](https://pdftomp3.com/connect-ai/) | [HN](https://news.ycombinator.com/item?id=50069337) |
| 145 | 71 | [Show HN: Flipflop – Iroh-powered persistent tunnels for filesharing](https://github.com/andunieee/flipflop) | [HN](https://news.ycombinator.com/item?id=50099136) |
| 142 | 51 | [Show HN: SolidCraft – Open-Source Parametric CAD in Rust (With MCP Support)](https://github.com/bherbruck/solidcraft) | [HN](https://news.ycombinator.com/item?id=50064840) |
| 141 | 13 | [Show HN: Esp32sim – Run ESP32 firmware in the browser](https://github.com/mikroverk/esp32sim) | [HN](https://news.ycombinator.com/item?id=50131189) |
| 121 | 71 | [Show HN: Pulse Local, a Mac budgeting app whose AI models run on your machine](https://pulseos.finance) | [HN](https://news.ycombinator.com/item?id=50080275) |
| 119 | 76 | [Show HN: I built a tool to track what AI leaders say and how their views change](https://blumify.io/people) | [HN](https://news.ycombinator.com/item?id=50081151) |
| 119 | 48 | [Show HN: Indigene – Native plants for where you stand](https://indigene.app/) | [HN](https://news.ycombinator.com/item?id=50064470) |
| 115 | 92 | [Show HN: Wonderhop – A daily game: guess what most people say, or what none do](https://wonderhop.io/en/) | [HN](https://news.ycombinator.com/item?id=50080246) |
| 115 | 30 | [Show HN: Atticus – Hold-to-talk voice assistant for macOS that runs on Claude -p](https://github.com/SaarthurR/atticus-mac) | [HN](https://news.ycombinator.com/item?id=50049588) |
| 114 | 98 | [Show HN: I wrote an email app that accepts only one sender per inbox](https://clova.email/) | [HN](https://news.ycombinator.com/item?id=50090932) |
| 107 | 34 | [Show HN: Proa – A Rust web framework with fast SSR and multi-target rendering](https://proa.so/) | [HN](https://news.ycombinator.com/item?id=50105467) |
| 106 | 26 | [Show HN: High-quality duck audio synthesizer](https://celphase.github.io/duck-pond/) | [HN](https://news.ycombinator.com/item?id=50131006) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 29 | [AutoDev: Automated AI-Driven Development](https://huggingface.co/papers/2403.08299) | AutoDev is an AI-driven software development framework that automates complex engineering tasks within a secure Docker environment, achievin… | [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi) 30869★ |
| 108 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 1444★ |
| 28 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 5564★ |
| 153 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 111683★ |
| 47 | [RSI-Anything: Unlocking Recursive Self-Improvement with World Models](https://huggingface.co/papers/2610.13912) | RSI-Anything leverages predictive world models to guide action selection and adaptive learning, enabling recursive self-improvement across c… | 💡 [Gen-Verse/RSI-Anything](https://github.com/Gen-Verse/RSI-Anything) 774★ |
| 343 | [Any Time, Any Space: A World-State-Centric Framework for Agentic Video Generation](https://huggingface.co/papers/2610.20571) | ATAS improves long-form video consistency by compiling screenplays into referenced shot requests, retrieving spatial and temporal evidence f… | 💡 [ziplab/ATAS](https://github.com/ziplab/ATAS) 244★ |
| 93 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 27747★ |
| 116 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 1391★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 91133★ |
| 334 | [Player-1: Learning to Play from Synthetic Experience](https://huggingface.co/papers/2610.20584) | Player-1 improves game control by combining supervised fine-tuning on gameplay trajectories with reinforcement learning across synthetic env… | 💡 [TencentARC/Player-1](https://github.com/TencentARC/Player-1) 118★ |
| 198 | [Self-Evolving Agent Harness](https://huggingface.co/papers/2610.18813) | A framework for self-evolving agent harnesses uses feedback-driven revisions and evolutionary optimization with theoretical generalization g… | 💡 [zgcagi/Harness-RSI](https://github.com/zgcagi/Harness-RSI) 173★ |
| 207 | [Agent-Reflex: Teaching Language Agents to Act Reflectively](https://huggingface.co/papers/2610.17953) | Agent-Reflex trains interactive agents to reflect and recover from noisy tool feedback and user corrections through skill discovery, supervi… | 💡 [RUC-NLPIR/Agent-Reflex](https://github.com/RUC-NLPIR/Agent-Reflex) 229★ |
| 238 | [YuE2: Unifying Symbolic and Audio Music Generation at Frontier Quality](https://huggingface.co/papers/2609.33757) | YuE2 unifies symbolic and audio music generation via symbolic planning, producing readable scores and full-song audio with state-of-the-art… | [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE) 12079★ |
| 31 | [Internal Safety Collapse in Frontier Large Language Models](https://huggingface.co/papers/2603.23509) | Frontier large language models exhibit Internal Safety Collapse, where they generate harmful content under specific task conditions, reveali… | [wuyoscar/ISC-Bench](https://github.com/wuyoscar/ISC-Bench) 1571★ |
| 128 | [Urbex: Agentic Spatial Grounding for City-Scale 3D Scenes](https://huggingface.co/papers/2610.18356) | Urbex reframes city-scale 3D grounding as an active search process using a vision-language agent with reinforcement learning, improving accu… | 💡 [AMAP-ML/Urbex](https://github.com/AMAP-ML/Urbex) 99★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 81926★ |
| 60 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 40906★ |
| 48 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 33422★ |
| 74 | [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://huggingface.co/papers/2504.19413) | Mem0, a memory-centric architecture with graph-based memory, enhances long-term conversational coherence in LLMs by efficiently extracting,… | [mem0ai/mem0](https://github.com/mem0ai/mem0) 67364★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 1 | [deepseek v4.1 flash 1017](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash-1017) | image-text-to-text | 1028 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 103 | 21 | [The NIST Elliptic Curves Seeds Bounty Has Been Claimed](https://words.filippo.io/seeds-solved/) | `cryptography` `vibecoding` | [讨论](https://lobste.rs/s/ddtqtn/nist_elliptic_curves_seeds_bounty_has) |
| 19 | 8 | [Intuitive concurrent programming in any language](https://www.lf-lang.org/) | `programming` | [讨论](https://lobste.rs/s/srao9u/intuitive_concurrent_programming_any) |
| 14 | 1 | [It took me nine years to hack my Xbox 360](https://kennedn.com/blog/posts/glitching/) | `hardware` `reversing` | [讨论](https://lobste.rs/s/wceg2u/it_took_me_nine_years_hack_my_xbox_360) |
| 47 | 18 | [The Decoherence Trap: When AI slop drowns out the signal in an endless sea of noise](https://maevyn.codes/decoherence) | `vibecoding` | [讨论](https://lobste.rs/s/vjmn84/decoherence_trap_when_ai_slop_drowns_out) |
| 5 | 2 | [PwnEscape: Guest-to-Host KVM Escape (CVE-2026-99999)](https://pwn.ai/blog/pwnescape) | `linux` `security` `vibecoding` `virtualization` | [讨论](https://lobste.rs/s/np84oh/pwnescape_guest_host_kvm_escape_cve_2026) |
| 2 | 0 | [Does moving a GPU server's request loop into the kernel save CPU?](https://eunomia.dev/blog/2026/10/17/bpf-gpu-server/) | `ai` `linux` | [讨论](https://lobste.rs/s/6himy4/does_moving_gpu_server_s_request_loop_into) |
| 2 | 0 | [Making Hybrid Images (2014)](https://www.jeremykun.com/2014/09/29/hybrid-images/) | `graphics` `math` | [讨论](https://lobste.rs/s/16tsvr/making_hybrid_images_2014) |
| 2 | 0 | [The Brain Sandwich](https://terriblesoftware.org/2026/10/02/the-brain-sandwich/) | `vibecoding` | [讨论](https://lobste.rs/s/k5omum/brain_sandwich) |
| 2 | 0 | [It's time to talk about TEEs](https://alinush.github.io//tee) | `hardware` `security` | [讨论](https://lobste.rs/s/edli0x/it_s_time_talk_about_tees) |
| 23 | 7 | [Interactive refactoring in gopls](https://go.dev/blog/interactive-refactoring) | `editors` `go` | [讨论](https://lobste.rs/s/wn293o/interactive_refactoring_gopls) |
| 64 | 15 | [The road to iroh 1.0](https://www.iroh.computer/blog/the-road-to-iroh-1-0) | `networking` | [讨论](https://lobste.rs/s/6laoto/road_iroh_1_0) |
| 8 | 0 | [Abolish AI! Manifesto](https://abolish-ai.net/abolish-ai-a-manifesto/) | `ai` `culture` | [讨论](https://lobste.rs/s/1kesjm/abolish_ai_manifesto) |
| 16 | 13 | [Do you let LLMs write both your tests and your code?](https://lobste.rs/s/miwcai) | `ask` `vibecoding` | [讨论](https://lobste.rs/s/miwcai/do_you_let_llms_write_both_your_tests_your) |
| 125 | 20 | [Why are we even doing all this?](https://terrytao.wordpress.com/2026/10/15/why-are-we-even-doing-all-this/) | `math` `vibecoding` | [讨论](https://lobste.rs/s/qvomvk/why_are_we_even_doing_all_this) |
| 27 | 11 | [Introducing GNOME OS Preview](https://blogs.gnome.org/adrianvovk/2026/10/16/gnome-os-preview/) | `linux` `release` | [讨论](https://lobste.rs/s/xwng6u/introducing_gnome_os_preview) |
| 38 | 1 | [Getting Canceled](https://www.youtube.com/watch?v=5zIOfBLQ3U4) | `video` `zig` | [讨论](https://lobste.rs/s/tty7hm/getting_canceled) |
| 50 | 14 | [Making a 88x31 button book using ImageMagick](https://k.sosnierz.me/08-11-24/) | `art` | [讨论](https://lobste.rs/s/v6hhdr/making_88x31_button_book_using) |
| 4 | 0 | [Ship Your Interpreter](https://www.basis.ai/blog/ship-your-interpreters/) | `formalmethods` `vibecoding` | [讨论](https://lobste.rs/s/rtd5gq/ship_your_interpreter) |
| 5 | 6 | [Some quick thoughts on Unit Testing ActivityPub](https://shkspr.mobi/blog/2026/10/some-thoughts-on-unit-testing-activitypub/) | `php` `testing` `web` | [讨论](https://lobste.rs/s/gwuebx/some_quick_thoughts_on_unit_testing) |
| 6 | 2 | [Developing for Debugging (2025)](https://www.davepacheco.net/blog/2025/developing-for-debugging-dns-propagation/) | `practices` | [讨论](https://lobste.rs/s/a0og2j/developing_for_debugging_2025) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

_还没有到 14 天的，46 个在等。_

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
