# early-radar 选题雷达 · 2026-10-16

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 112 个，细查前 20 个 · 比上次 = 和 2026-10-15 那次比 · 生成于 2026-10-16 04:09 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 4 个 · Show HN ✅ 28 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 0 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 7 个 · 🟡 在降温 4 个 · 🔵 已被发现 3 个 · 💤 不活跃 0 个 · 🔴 先核对 6 个
- **今天新出现 2 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) 平均每天 +1680，见 [爆发](#爆发)
- **最值得今天试的**：
  - [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) — Let an AI model use a real iPhone with a $7 ESP32: AirPlay e…（近 7 天 +2576，刚发布一周内）
  - [academa-labs/manimgx](https://github.com/academa-labs/manimgx) — The animation engine for agents: blazingly fast math and 3D…（近 7 天 +1409，比前 7 天快 28.8 倍，在加速）
  - [opengeos/RustGIS](https://github.com/opengeos/RustGIS) — A fast, free and open-source GIS in pure Rust.（近 7 天 +1233，刚发布一周内）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 22 个（star 合计 19218），代表：[Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：8 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Guitoro, a virtual guitar you strum with your keyboard](https://guitoro.com/) — 566 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) | 13019 | 1680 | +2200 | 7.7 | — | anatomy · wheresryan22 anatomy · ryan anatomy | An agent skill for creating detailed, interactive isometric… |
| [openai/math](https://github.com/openai/math) | 14962 | 1615 | +126 | 9.3 | [342](https://news.ycombinator.com/item?id=50003107) | math · openai math |  |
| ✅ [storytold/wordcraft](https://github.com/storytold/wordcraft) | 13274 | 1506 | +737 | 8.8 | [101](https://news.ycombinator.com/item?id=50050370) | wordcraft · storytold wordcraft · artcraft wordcraft | An open-source, clean-room reimplementation of Microsoft Wor… |
| 🆕 [chenglou/handwired](https://github.com/chenglou/handwired) | 1160 | 1075 | — | 1.1 | [3](https://news.ycombinator.com/item?id=50105735) | handwired · chenglou handwired · cheng handwired | Turn your regular JavaScript code into a neural net. |
| [jhaizhou-ops/d2r-mobile](https://github.com/jhaizhou-ops/d2r-mobile) | 3252 | 853 | +924 | 3.8 | — | d2r mobile · jhaizhou-ops d2r mobile | Open-source iOS / macOS compatibility layer for Diablo II: R… |
| 🆕 [ahwootech/BRUTAL](https://github.com/ahwootech/BRUTAL) | 1229 | 905 | — | 1.4 | [9](https://news.ycombinator.com/item?id=50100170) | brutal · ahwootech brutal · ahwoo brutal | A free, open source C# framework for making games, or your o… |
| [Arekejoker/qwen21-nsfw-pose-skill](https://github.com/Arekejoker/qwen21-nsfw-pose-skill) | 2124 | 698 | +762 | 3 | — | qwen21 nsfw pose skill · arekejoker qwen21 nsfw pose skill | Qwen-Image 2.1 NSFW/姿势出图 skill：作者级提示词配方 + NSFW LoRA + 136 姿势… |
| 🆕 [feder-cr/open_scion](https://github.com/feder-cr/open_scion) | 739 | 739 | — | 1 | — | open scion · feder-cr open scion · federico open scion | Open-source version of Scion: version control built for codi… |
| 🆕 [Supermedo/uncharted_pc](https://github.com/Supermedo/uncharted_pc) | 726 | 625 | — | 1.2 | — | uncharted pc · supermedo uncharted pc | Uncharted: The Nathan Drake Collection running natively on W… |
| [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) | 2576 | 589 | +431 | 4.4 | [2](https://news.ycombinator.com/item?id=50102527) | esp32 iphone agent · onehumanbeing esp32 iphone agent · henry esp32 iphone agent | Let an AI model use a real iPhone with a $7 ESP32: AirPlay e… |
| ✅ [storytold/gridcraft](https://github.com/storytold/gridcraft) | 5220 | 583 | +302 | 9 | — | gridcraft · storytold gridcraft · artcraft gridcraft | GridCraft: an open-source, clean-room spreadsheet (Microsoft… |
| ✅ [storytold/cadcraft](https://github.com/storytold/cadcraft) | 5186 | 580 | +313 | 8.9 | — | cadcraft · storytold cadcraft · artcraft cadcraft | CADCraft: computer-aided design and drafting — an open-sourc… |
| [HeyPuter/everything](https://github.com/HeyPuter/everything) | 1361 | 546 | +567 | 2.5 | [7](https://news.ycombinator.com/item?id=50075719) | everything · heyputer everything · puter everything | We're rebuilding and open-sourcing the world’s software from… |
| [ARahim3/DigUp](https://github.com/ARahim3/DigUp) | 4140 | 566 | +406 | 7.3 | [5](https://news.ycombinator.com/item?id=50045015) | digup · arahim3 digup · abdur digup | Search your computer by what's in your files: photos, PDFs,… |
| [T-Auto/dsh-ops](https://github.com/T-Auto/dsh-ops) | 2328 | 296 | +564 | 7.9 | — | dsh ops · t-auto dsh ops | A toolkit for low-level operations in DSH, designed to reduc… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 94.3 | 🟢 窗口内 | [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) | C | 2576 | +431 | +2576 | +0 | `········▁█▇▄▄·` | 4 | [2](https://news.ycombinator.com/item?id=50102527) | — |
| 2 | 90.7 | ✅ 🟢 窗口内 | [storytold/soundcraft](https://github.com/storytold/soundcraft) | Rust | 2971 | +143 | +1923 | +1048 | `····▄▆▇▆█▆▅▄▃·` | 8 | — | — |
| 3 | 87.4 | ✅ 🟢 窗口内 | [storytold/figcraft](https://github.com/storytold/figcraft) | Rust | 1450 | +440 | +1449 | +1 | `······▁··▁██▆·` | 6 | [3](https://news.ycombinator.com/item?id=50069000) | — |
| 4 | 87 | 🟢 窗口内 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | Python | 1458 | +204 | +1409 | +49 | `····▁▁▁▂█▆▃▂▃·` | 10 | [10](https://news.ycombinator.com/item?id=50037852) | — |
| 5 | 85.4 | 🟢 窗口内 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 1233 | +149 | +1233 | +0 | `········▁▆█▄▃·` | 5 | — | — |
| 6 | 80.9 | 🟢 窗口内 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) | TypeScript | 1489 | +17 | +848 | +641 | `·····▃█▇▄▂▂▂▁·` | 8 | — | — |
| 7 | 72.9 | 🟢 窗口内 | [tobi/disktree](https://github.com/tobi/disktree) | Rust | 2965 | +29 | +433 | +333 | `▃▃▂▂▃▂▂▂█▃▂▂▂·` | 21 | [3](https://news.ycombinator.com/item?id=49841155) | — |
| 8 | 72.1 | ✅ 🟡 在降温 | [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) | Python | 2771 | +141 | +1351 | +1420 | `▆▆▅▅▆▇███▇▇▅▄·` | 12 | — | — |
| 9 | 60.4 | 🟡 在降温 | [feitangyuan/onetake](https://github.com/feitangyuan/onetake) | Python | 2466 | +66 | +419 | +687 | `▆▆███▅▅▄▄▆▆▆▄·` | 19 | — | — |
| 10 | 53 | 🟡 在降温 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep) | TypeScript | 2724 | +46 | +199 | +447 | `█▅▄▃▅▅▄▃▅▃▃▁▄·` | 20 | [5](https://news.ycombinator.com/item?id=49880146) | — |
| 11 | 51.9 | 🟡 在降温 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) | Python | 1994 | +20 | +179 | +593 | `█▇██▆▃▄▂▃▄▃▂▂·` | 15 | — | — |
| 12 | 47.5 | 🔵 已被发现 | [bherbruck/solidcraft](https://github.com/bherbruck/solidcraft) | Rust | 2788 | +338 | +2742 | +46 | `······▁▂▆▆█▆▄·` | 8 | [141](https://news.ycombinator.com/item?id=50064840) | — |
| 13 | 42.4 | 🔵 已被发现 | [rociiu/talorys](https://github.com/rociiu/talorys) | TypeScript | 1181 | +178 | +1181 | +0 | `·······█▅▃▂▂▃·` | 5 | [329](https://news.ycombinator.com/item?id=50031614) | — |
| 14 | 41.8 | 🔴 先核对 | [marclou/mailcheap](https://github.com/marclou/mailcheap) | JavaScript | 1064 | +131 | +1064 | +0 | `·······█▄▂▂▁▃·` | 5 | [2](https://news.ycombinator.com/item?id=50033695) | 一天进了一半以上的 star，但 HN 上没火过 |
| 15 | 41.6 | 🔴 先核对 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 1032 | +59 | +1032 | +0 | `·········█▃▂▂·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 16 | 40.4 | 🆕 🔴 先核对 | [outcrawlai/scout](https://github.com/outcrawlai/scout) | TypeScript | 840 | +156 | +840 | +0 | `···········█▂·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 31.1 | 🆕 🔴 先核对 | [Graphicle-AI/graphicle](https://github.com/Graphicle-AI/graphicle) | Rust | 176 | — | +176 | +0 | `···········█▃·` | 1 | [47](https://news.ycombinator.com/item?id=50088713) | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 30.3 | 🔵 已被发现 | [pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust) | Rust | 1256 | +40 | +427 | +829 | `····█▄▂▃▂▂▂▂▁·` | 8 | [118](https://news.ycombinator.com/item?id=50000676) | — |
| 19 | 22 | 🔴 先核对 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) | Python | 2758 | +8 | +80 | +150 | `▅▅▃▃▂█▄▆▃▃▂▂▃·` | 16 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 21.3 | 🔴 先核对 | [trhhubsd/ARTEXX](https://github.com/trhhubsd/ARTEXX) | Go | 1201 | +3 | +1198 | +3 | `·····▁▁▁▁█▆▁▁·` | 7 | — | 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1% |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 524 | 30 | 43014 | [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill)、[feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep) |
| `mcp` | 166 | 30 | 19671 | [bherbruck/solidcraft](https://github.com/bherbruck/solidcraft)、[feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `rust` | 135 | 30 | 25593 | [storytold/soundcraft](https://github.com/storytold/soundcraft)、[tobi/disktree](https://github.com/tobi/disktree)、[bherbruck/solidcraft](https://github.com/bherbruck/solidcraft) |
| `local-first` | 58 | 30 | 12180 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[glanderness/BeefTV](https://github.com/glanderness/BeefTV) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 22 | 19218 | [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) |
| `ai-agents` | 20 | 9933 | [penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `codex` | 18 | 13769 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) |
| `llm` | 14 | 10852 | [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `agent-skills` | 13 | 13836 | [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) |
| `macos` | 12 | 7212 | [freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[amontlabs/lcu](https://github.com/amontlabs/lcu) |
| `ai-agent` | 10 | 9158 | [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent)、[freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `developer-tools` | 10 | 7710 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill) |
| `mcp-server` | 10 | 7105 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `jev` | 9 | 7071 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[ollaya-dev/ollaya](https://github.com/ollaya-dev/ollaya)、[jev-chat/jev-chat-windows](https://github.com/jev-chat/jev-chat-windows) |
| `python` | 9 | 5555 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[jev-chat/jev-chat-windows](https://github.com/jev-chat/jev-chat-windows)、[Harvil1/codeAgent](https://github.com/Harvil1/codeAgent) |
| `coding-agents` | 8 | 6036 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[devswha/herdr-web-ui](https://github.com/devswha/herdr-web-ui)、[sno-ai/sno-station](https://github.com/sno-ai/sno-station) |

**语言分布**：Python 37 · Rust 29 · TypeScript 20 · JavaScript 8 · Go 4 · Swift 4 · Astro 1 · C 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) · 🟢 窗口内 · 94.3 分

> Let an AI model use a real iPhone with a $7 ESP32: AirPlay eyes, USB HID hands, any OpenAI-compatible vision model. No Mac, no developer account, no jailbreak.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2576 | +2576 | +0 | 339 | 4 | C | MIT | 10-11（4 天前） | 今天 |

- **近 14 天每天新增**：`········▁█▇▄▄·` 0 0 0 0 0 0 0 0 39 922 804 421 390 0
- **势头**：刚发布一周内
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50102527)）
- **topics**：`ai-agent` `airplay` `automation` `computer-use` `esp32` `esp32-s3` `iphone` `llm` `usb-hid`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. ✅ [storytold/soundcraft](https://github.com/storytold/soundcraft) · 🟢 窗口内 · 90.7 分

> An open-source, clean-room reimplementation of Avid Pro Tools in pure Rust

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2971 | +1923 | +1048 | 1867 | 351 | Rust | Apache-2.0 | 10-07（8 天前） | 今天 |

- **近 14 天每天新增**：`····▄▆▇▆█▆▅▄▃·` 0 0 0 0 238 400 410 350 520 400 309 212 132 0
- **势头**：比前 7 天快 1.8 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://getartcraft.com/apps/soundcraft>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. ✅ [storytold/figcraft](https://github.com/storytold/figcraft) · 🟢 窗口内 · 87.4 分

> FigCraft: interface design and prototyping; an open-source, clean-room reimplementation of collaborative design workflows in pure Rust

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1450 | +1449 | +1 | 642 | 153 | Rust | Apache-2.0 | 10-09（6 天前） | 今天 |

- **近 14 天每天新增**：`······▁··▁██▆·` 0 0 0 0 0 0 1 0 0 3 529 545 372 0
- **势头**：比前 7 天快 1449.0 倍，在加速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=50069000)）
- **topics**：`design` `rust` `tools`
- **主页**：<https://getartcraft.com/apps/figcraft>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [academa-labs/manimgx](https://github.com/academa-labs/manimgx) · 🟢 窗口内 · 87 分

> The animation engine for agents: blazingly fast math and 3D videos with Manim's Python API, on a Rust GPU core.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1458 | +1409 | +49 | 103 | 9 | Python | MIT | 10-05（10 天前） | 今天 |

- **近 14 天每天新增**：`····▁▁▁▂█▆▃▂▃·` 0 0 0 0 7 31 11 41 567 368 125 106 202 0
- **势头**：比前 7 天快 28.8 倍，在加速
- **HN**：发过 1 次，最高 10 分（[讨论](https://news.ycombinator.com/item?id=50037852)）
- **主页**：<https://manimgx.academa.ai>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [opengeos/RustGIS](https://github.com/opengeos/RustGIS) · 🟢 窗口内 · 85.4 分

> A fast, free and open-source GIS in pure Rust.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1233 | +1233 | +0 | 170 | 27 | Rust | Apache-2.0 | 10-10（5 天前） | 今天 |

- **近 14 天每天新增**：`········▁▆█▄▃·` 0 0 0 0 0 0 0 0 2 372 493 237 129 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`geospatial` `gis` `remote-sensing` `rust` `rust-lang`
- **主页**：<https://rustgis.app>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) · 🟢 窗口内 · 80.9 分

> Your company's data, connected into one ontology, on your own computer. A local-first data workspace built on HelixDB and DuckDB.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1489 | +848 | +641 | 228 | 14 | TypeScript | Apache-2.0 | 10-07（8 天前） | 2 天前 |

- **近 14 天每天新增**：`·····▃█▇▄▂▂▂▁·` 0 0 0 0 0 137 504 427 180 99 66 60 16 0
- **势头**：比前 7 天快 1.3 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [tobi/disktree](https://github.com/tobi/disktree) · 🟢 窗口内 · 72.9 分

> A treemap for finding and removing what fills your disk, for Omarchy. Rust + GPUI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2965 | +433 | +333 | 182 | 52 | Rust | MIT | 09-24（21 天前） | 11 天前 |

- **近 14 天每天新增**：`▃▃▂▂▃▂▂▂█▃▂▂▂·` 70 58 33 46 56 39 31 36 239 63 37 34 24 0
- **势头**：比前 7 天快 1.3 倍，在加速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=49841155)）
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. ✅ [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) · 🟡 在降温 · 72.1 分

> Eleven free Claude skills that clone any app: reverse-engineer it, rebuild it, test it for bugs, then fix what its users hate. Free, MIT.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2771 | +1351 | +1420 | 415 | 7 | Python | MIT | 10-03（12 天前） | 12 天前 |

- **近 14 天每天新增**：`▆▆▅▅▆▇███▇▇▅▄·` 186 216 156 168 188 228 278 267 270 254 255 177 128 0
- **势头**：和前 7 天差不多
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent` `agent-skills` `app-clone` `claude` `claude-code` `claude-skills` `indie-hacker` `reverse-engineering` `saas`
- **主页**：<https://opusjake.ai>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [feitangyuan/onetake](https://github.com/feitangyuan/onetake) · 🟡 在降温 · 60.4 分

> Motion films that never cut to the next slide: every beat grows out of the one before, one continuous camera, continuity measured by an oracle. Product launch films and feature demos, made with a coding agent.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2466 | +419 | +687 | 163 | 3 | Python | — | 09-26（19 天前） | 3 天前 |

- **近 14 天每天新增**：`▆▆███▅▅▄▄▆▆▆▄·` 92 85 123 122 119 77 69 58 50 86 80 84 61 0
- **势头**：只有前 7 天的 61%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `animation` `canvas` `claude-skill` `launch-video` `motion-graphics` `video`
- **主页**：<https://onetakemotion.com>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [dzhng/jevgrep](https://github.com/dzhng/jevgrep) · 🟡 在降温 · 53 分

> Find code by asking what it does. A CLI for coding agents that uses Jev to discover relevant files and source context.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2724 | +199 | +447 | 203 | 30 | TypeScript | MIT | 09-26（20 天前） | 今天 |

- **近 14 天每天新增**：`█▅▄▃▅▅▄▃▅▃▃▁▄·` 116 70 53 35 69 59 45 29 58 31 31 5 45 0
- **势头**：只有前 7 天的 45%，在减速
- **HN**：发过 1 次，最高 5 分（[讨论](https://news.ycombinator.com/item?id=49880146)）
- **topics**：`ai-sdk` `claude-code` `cli` `code-search` `codex` `coding-agents` `context-retrieval` `developer-tools` `jev` `semantic-search` `typescript` `vercel-ai-gateway`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [marclou/mailcheap](https://github.com/marclou/mailcheap) — 一天进了一半以上的 star，但 HN 上没火过
- [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) — 一天进了一半以上的 star，但 HN 上没火过
- [outcrawlai/scout](https://github.com/outcrawlai/scout) — 一天进了一半以上的 star，但 HN 上没火过
- [Graphicle-AI/graphicle](https://github.com/Graphicle-AI/graphicle) — 一天进了一半以上的 star，但 HN 上没火过
- [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) — 一天进了一半以上的 star，但 HN 上没火过
- [trhhubsd/ARTEXX](https://github.com/trhhubsd/ARTEXX) — 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1%

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 566 | 161 | [Show HN: Guitoro, a virtual guitar you strum with your keyboard](https://guitoro.com/) | [HN](https://news.ycombinator.com/item?id=50077020) |
| 431 | 55 | [Show HN: Carrier-Explode: iPhone, Pixel and Galaxy carrier settings decoded](https://carrierexplode.com/) | [HN](https://news.ycombinator.com/item?id=50024499) |
| 419 | 195 | [Show HN: Let your AI agents paint big arrows, boxes and text on your screen](https://github.com/franzenzenhofer/big-arrow-on-the-screen) | [HN](https://news.ycombinator.com/item?id=50018817) |
| 312 | 158 | [Show HN: PS2 games statically recompiled to WebAssembly](https://github.com/snuri00/ps2-web-recomp) | [HN](https://news.ycombinator.com/item?id=50052251) |
| 286 | 126 | [Show HN: WallHop – 12ft.io is gone, so I built a replacement](https://wallhop.io/) | [HN](https://news.ycombinator.com/item?id=50038634) |
| 277 | 187 | [Show HN: Unfenced – Land for sale that borders public land](https://unfenced.land/) | [HN](https://news.ycombinator.com/item?id=50102247) |
| 241 | 181 | [Show HN: Quake ported to safe Rust, playable in browser](https://quake-srp.pages.dev/) | [HN](https://news.ycombinator.com/item?id=50016312) |
| 220 | 127 | [Show HN: BetterWispr – Free, open-source dictation for Mac](https://betterwispr.com/) | [HN](https://news.ycombinator.com/item?id=50042333) |
| 214 | 119 | [Show HN: How random are you?](https://lab.specr.net/rigged-draw/) | [HN](https://news.ycombinator.com/item?id=50074909) |
| 213 | 41 | [Show HN: Petal, open-source CoScreen/ScreenHero finally free](https://petal.live/) | [HN](https://news.ycombinator.com/item?id=50092470) |
| 190 | 67 | [Show HN: The rarest tech books and docs you've probably never read](https://readrare.com/) | [HN](https://news.ycombinator.com/item?id=50024055) |
| 172 | 90 | [Show HN: Use your OpenAI subscription to create audiobooks](https://pdftomp3.com/connect-ai/) | [HN](https://news.ycombinator.com/item?id=50069337) |
| 141 | 51 | [Show HN: SolidCraft – Open-Source Parametric CAD in Rust (With MCP Support)](https://github.com/bherbruck/solidcraft) | [HN](https://news.ycombinator.com/item?id=50064840) |
| 119 | 71 | [Show HN: Pulse Local, a Mac budgeting app whose AI models run on your machine](https://pulseos.finance) | [HN](https://news.ycombinator.com/item?id=50080275) |
| 117 | 77 | [Show HN: I built a tool to track what AI leaders say and how their views change](https://blumify.io/people) | [HN](https://news.ycombinator.com/item?id=50081151) |
| 117 | 62 | [Show HN: Flipflop – Iroh-powered persistent tunnels for filesharing](https://github.com/andunieee/flipflop) | [HN](https://news.ycombinator.com/item?id=50099136) |
| 115 | 30 | [Show HN: Atticus – Hold-to-talk voice assistant for macOS that runs on Claude -p](https://github.com/SaarthurR/atticus-mac) | [HN](https://news.ycombinator.com/item?id=50049588) |
| 110 | 93 | [Show HN: I wrote an email app that accepts only one sender per inbox](https://clova.email/) | [HN](https://news.ycombinator.com/item?id=50090932) |
| 108 | 38 | [Show HN: Indigene – Native plants for where you stand](https://indigene.app/) | [HN](https://news.ycombinator.com/item?id=50064470) |
| 94 | 26 | [Show HN: Proa – A Rust web framework with fast SSR and multi-target rendering](https://proa.so/) | [HN](https://news.ycombinator.com/item?id=50105467) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 26 | [AutoDev: Automated AI-Driven Development](https://huggingface.co/papers/2403.08299) | AutoDev is an AI-driven software development framework that automates complex engineering tasks within a secure Docker environment, achievin… | [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi) 30394★ |
| 46 | [RSI-Anything: Unlocking Recursive Self-Improvement with World Models](https://huggingface.co/papers/2610.13912) | RSI-Anything leverages predictive world models to guide action selection and adaptive learning, enabling recursive self-improvement across c… | 💡 [Gen-Verse/RSI-Anything](https://github.com/Gen-Verse/RSI-Anything) 751★ |
| 332 | [Any Time, Any Space: A World-State-Centric Framework for Agentic Video Generation](https://huggingface.co/papers/2610.20571) | ATAS improves long-form video consistency by compiling screenplays into referenced shot requests, retrieving spatial and temporal evidence f… | 💡 [ziplab/ATAS](https://github.com/ziplab/ATAS) 208★ |
| 27 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 5142★ |
| 152 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 111334★ |
| 283 | [Player-1: Learning to Play from Synthetic Experience](https://huggingface.co/papers/2610.20584) | Player-1 improves game control by combining supervised fine-tuning on gameplay trajectories with reinforcement learning across synthetic env… | 💡 [TencentARC/Player-1](https://github.com/TencentARC/Player-1) 91★ |
| 118 | [Urbex: Agentic Spatial Grounding for City-Scale 3D Scenes](https://huggingface.co/papers/2610.18356) | Urbex reframes city-scale 3D grounding as an active search process using a vision-language agent with reinforcement learning, improving accu… | 💡 [AMAP-ML/Urbex](https://github.com/AMAP-ML/Urbex) 92★ |
| 116 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 1266★ |
| 93 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 27509★ |
| 237 | [YuE2: Unifying Symbolic and Audio Music Generation at Frontier Quality](https://huggingface.co/papers/2609.33757) | YuE2 unifies symbolic and audio music generation via symbolic planning, producing readable scores and full-song audio with state-of-the-art… | [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE) 11997★ |
| 155 | [VideoJev: System One Model for Video Understanding and Interaction](https://huggingface.co/papers/2610.18615) | VideoJev converts video observations into structured decisions by scoring temporal intervals and text options, enabling efficient reusable i… | 💡 [MCG-NJU/VideoJev](https://github.com/MCG-NJU/VideoJev) 123★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 90992★ |
| 31 | [Towards Agentic Robots: Model, Data, Environment, and Harness](https://huggingface.co/papers/2610.20442) | This survey unifies research on agentic robots by tracing the evolution from robot policies to integrated systems using vision-language-acti… | 💡 [chonghanqin/Awesome-Agentic-Robots](https://github.com/chonghanqin/Awesome-Agentic-Robots) 66★ |
| 18 | [Bitnet.cpp: Efficient Edge Inference for Ternary LLMs](https://huggingface.co/papers/2502.11880) | Bitnet.cpp enhances edge inference for ternary LLMs using a novel mixed-precision matrix multiplication library, achieving significant speed… | [microsoft/BitNet](https://github.com/microsoft/BitNet) 41171★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 180 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 81815★ |
| 279 | [Jeva: System One Models from First Principles](https://huggingface.co/papers/2610.18773) | Jeva is a decision-native architecture that jointly enforces null-awareness, permutation invariance, option scalability, and cross-request c… | 💡 [LiQiiiii/Jeva](https://github.com/LiQiiiii/Jeva) 76★ |
| 50 | [Agent-Reflex: Teaching Language Agents to Act Reflectively](https://huggingface.co/papers/2610.17953) | Agent-Reflex trains interactive agents to reflect and recover from noisy tool feedback and user corrections through skill discovery, supervi… | 💡 [RUC-NLPIR/Agent-Reflex](https://github.com/RUC-NLPIR/Agent-Reflex) 75★ |
| 34 | [HuggingFace's Transformers: State-of-the-art Natural Language Processing](https://huggingface.co/papers/1910.03771) | Transformers library provides state-of-the-art Transformer architectures and pretrained models for natural language processing tasks with a… | [huggingface/transformers](https://github.com/huggingface/transformers) 167715★ |
| 59 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 40804★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 14 | [muse spark open](https://huggingface.co/meta-models/Muse-Spark-Open-816B-A42B) | image-text-to-text | 285 | 1 |
| 16 | [flux 3 image klein](https://huggingface.co/black-forest-labs/flux-3-image-klein) | image-to-image | 269 | 1 |
| 18 | [flux 3 image klein comfy](https://huggingface.co/black-forest-labs/flux-3-image-klein-comfy) | image-to-image | 250 | 1 |
| 50 | [muse spark open nvfp4](https://huggingface.co/meta-models/Muse-Spark-Open-816B-A42B-NVFP4) | image-text-to-text | 109 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 51 | 15 | [JPEG XL vs AVIF for web use-cases](https://jakearchibald.com/2026/jpeg-xl-vs-avif/) | `compsci` `web` | [讨论](https://lobste.rs/s/uejdwj/jpeg_xl_vs_avif_for_web_use_cases) |
| 39 | 8 | [My C23 Conventions](https://abner.page/post/c23-conventions-1/) | `c` | [讨论](https://lobste.rs/s/umdbht/my_c23_conventions) |
| 59 | 14 | [Sunsetting decomp.dev](https://decomp.dev/) | `games` `reversing` `vibecoding` | [讨论](https://lobste.rs/s/kaerns/sunsetting_decomp_dev) |
| 10 | 5 | [Announcing Rust 1.99.1](https://blog.rust-lang.org/2026/10/15/Rust-1.99.1/) | `release` `rust` | [讨论](https://lobste.rs/s/ttcx5k/announcing_rust_1_99_1) |
| 49 | 21 | [Haxy on Haxy](https://try.haxy.net/haxy:haxy) | `practices` `vcs` `zig` | [讨论](https://lobste.rs/s/bcaopz/haxy_on_haxy) |
| 25 | 0 | [Forgejo v17.0 is available](https://forgejo.org/2026-10-release-v17-0/) | `release` `vcs` | [讨论](https://lobste.rs/s/vemho2/forgejo_v17_0_is_available) |
| 140 | 48 | [Anthropic's Scion is heavily inspired by Mononoke](https://sunshowers.io/posts/anthropic-mononoke/) | `vcs` `vibecoding` | [讨论](https://lobste.rs/s/plcgps/anthropic_s_scion_is_heavily_inspired_by) |
| 13 | 3 | [About time](https://www.bipm.org/en/cgpm-2026/resolution-5) | `science` | [讨论](https://lobste.rs/s/ipyrkv/about_time) |
| 4 | 3 | [Linus Torvalds on AI-assisted kernel contributions](https://lore.kernel.org/lkml/CAHk-=whTs09_ozN+e09GU68N1wPP56MUzDjrg9rnKxQUa0A_4Q@mail.gmail.com/) | `linux` `vibecoding` | [讨论](https://lobste.rs/s/xiq59t/linus_torvalds_on_ai_assisted_kernel) |
| 41 | 0 | [The Costa GUI](https://costa.jacobpalm.dk) | `retrocomputing` | [讨论](https://lobste.rs/s/uqugjk/costa_gui) |
| 24 | 1 | [End-to-end encrypted relays for OCapN](https://spritely.institute/news/end-to-end-encrypted-relays-for-ocapn.html) | `distributed` | [讨论](https://lobste.rs/s/yxnovw/end_end_encrypted_relays_for_ocapn) |
| 9 | 2 | [Epic's EAC2 v2 seems fairly easily bypassable](https://codon.org.uk/~mjg59/blog/p/epics-eac2-v2-seems-fairly-easily-bypassable/) | `linux` `security` | [讨论](https://lobste.rs/s/1iin5o/epic_s_eac2_v2_seems_fairly_easily) |
| 18 | 11 | [Microsoft Defender for Linux](https://techcommunity.microsoft.com/blog/microsoftdefenderatpblog/secure-linux-desktops-with-microsoft-defender/4560822) | `linux` | [讨论](https://lobste.rs/s/46dcms/microsoft_defender_for_linux) |
| 11 | 1 | [Gleam case exhaustiveness, as a fan](https://oyster.pckt.blog/gleam-case-exhaustiveness-as-a-fan-fd4whyp) | `compilers` `gleam` | [讨论](https://lobste.rs/s/vyo9n2/gleam_case_exhaustiveness_as_fan) |
| 15 | 6 | [sslx: A fast, modern alternative to OpenSSL's CLI](https://github.com/glincker/sslx) | `security` `vibecoding` | [讨论](https://lobste.rs/s/p7tf7i/sslx_fast_modern_alternative_openssl_s) |
| 32 | 43 | [Remote Attestation Should Not Be Tolerated](https://lumi.codeberg.page/blog/remote-attestation.html) | `culture` `security` | [讨论](https://lobste.rs/s/s8bo3z/remote_attestation_should_not_be) |
| 21 | 4 | [Haxy.net is live! — HAXY (git forge) devlog](https://youtu.be/89yAiqYEwKg) | `vcs` `video` | [讨论](https://lobste.rs/s/o0ixth/haxy_net_is_live_haxy_git_forge_devlog) |
| 13 | 3 | [Libreboot 26.10 “Ominous Olive” released with full UEFI support](https://libreboot.org/news/libreboot2610.html) | `release` | [讨论](https://lobste.rs/s/9xticb/libreboot_26_10_ominous_olive_released) |
| 131 | 35 | [Introducing Firefox Enterprise](https://blog.mozilla.org/en/firefox/introducing-firefox-enterprise/) | `browsers` `release` `web` | [讨论](https://lobste.rs/s/7xg9rm/introducing_firefox_enterprise) |
| 80 | 47 | [What I Self-Host](https://viceconsole.fyi/blog/2026/10/10/what-i-self-host/) | `devops` | [讨论](https://lobste.rs/s/j4tlzg/what_i_self_host) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

_还没有到 14 天的，36 个在等。_

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
