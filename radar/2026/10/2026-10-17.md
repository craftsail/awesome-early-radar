# early-radar 选题雷达 · 2026-10-17

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 112 个，细查前 20 个 · 比上次 = 和 2026-10-16 那次比 · 生成于 2026-10-17 03:59 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 4 个 · Show HN ✅ 26 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 0 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 5 个 · 🟡 在降温 5 个 · 🔵 已被发现 2 个 · 💤 不活跃 0 个 · 🔴 先核对 8 个
- **今天新出现 4 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) 平均每天 +1612，见 [爆发](#爆发)
- **最值得今天试的**：
  - [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) — Let an AI model use a real iPhone with a $7 ESP32: AirPlay e…（近 7 天 +2882，刚发布一周内）
  - [academa-labs/manimgx](https://github.com/academa-labs/manimgx) — The animation engine for agents: blazingly fast math and 3D…（近 7 天 +1543，比前 7 天快 17.3 倍，在加速）
  - [opengeos/RustGIS](https://github.com/opengeos/RustGIS) — A fast, free and open-source GIS in pure Rust.（近 7 天 +1370，刚发布一周内）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 22 个（star 合计 20078），代表：[Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：8 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Guitoro, a virtual guitar you strum with your keyboard](https://guitoro.com/) — 569 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) | 14087 | 1612 | +1068 | 8.7 | — | anatomy · wheresryan22 anatomy · ryan anatomy | An agent skill for creating detailed, interactive isometric… |
| [openai/math](https://github.com/openai/math) | 15040 | 1466 | +78 | 10.3 | [342](https://news.ycombinator.com/item?id=50003107) | math · openai math |  |
| ✅ [storytold/wordcraft](https://github.com/storytold/wordcraft) | 13704 | 1397 | +430 | 9.8 | [101](https://news.ycombinator.com/item?id=50050370) | wordcraft · storytold wordcraft · artcraft wordcraft | An open-source, clean-room reimplementation of Microsoft Wor… |
| [chenglou/handwired](https://github.com/chenglou/handwired) | 1583 | 764 | +423 | 2.1 | [3](https://news.ycombinator.com/item?id=50105735) | handwired · chenglou handwired · cheng handwired | Turn your regular JavaScript code into a neural net. |
| [jhaizhou-ops/d2r-mobile](https://github.com/jhaizhou-ops/d2r-mobile) | 3558 | 741 | +306 | 4.8 | — | d2r mobile · jhaizhou-ops d2r mobile | Open-source iOS / macOS compatibility layer for Diablo II: R… |
| [ahwootech/BRUTAL](https://github.com/ahwootech/BRUTAL) | 1596 | 679 | +367 | 2.4 | [9](https://news.ycombinator.com/item?id=50100170) | brutal · ahwootech brutal · ahwoo brutal | A free, open source C# framework for making games, or your o… |
| ✅ [storytold/figcraft](https://github.com/storytold/figcraft) | 2110 | 281 | +660 | 7.5 | [3](https://news.ycombinator.com/item?id=50069000) | figcraft · storytold figcraft · artcraft figcraft | FigCraft: interface design and prototyping; an open-source,… |
| 🆕 [feder-cr/git-ai](https://github.com/feder-cr/git-ai) | 1067 | 660 | — | 1.6 | — | git ai · feder-cr git ai · federico git ai | Git designed for AI agents. |
| [Arekejoker/qwen21-nsfw-pose-skill](https://github.com/Arekejoker/qwen21-nsfw-pose-skill) | 2545 | 631 | +421 | 4 | — | qwen21 nsfw pose skill · arekejoker qwen21 nsfw pose skill | Qwen-Image 2.1 NSFW/姿势出图 skill：作者级提示词配方 + NSFW LoRA + 136 姿势… |
| ✅ [storytold/gridcraft](https://github.com/storytold/gridcraft) | 5425 | 545 | +205 | 9.9 | [3](https://news.ycombinator.com/item?id=50117408) | gridcraft · storytold gridcraft · artcraft gridcraft | GridCraft: an open-source, clean-room spreadsheet (Microsoft… |
| ✅ [storytold/cadcraft](https://github.com/storytold/cadcraft) | 5423 | 545 | +237 | 9.9 | — | cadcraft · storytold cadcraft · artcraft cadcraft | CADCraft: computer-aided design and drafting — an open-sourc… |
| [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) | 2882 | 537 | +306 | 5.4 | [3](https://news.ycombinator.com/item?id=50102527) | esp32 iphone agent · onehumanbeing esp32 iphone agent · henry esp32 iphone agent | Let an AI model use a real iPhone with a $7 ESP32: AirPlay e… |
| [ARahim3/DigUp](https://github.com/ARahim3/DigUp) | 4352 | 524 | +212 | 8.3 | [5](https://news.ycombinator.com/item?id=50045015) | digup · arahim3 digup · abdur digup | Search your computer by what's in your files: photos, PDFs,… |
| [HeyPuter/everything](https://github.com/HeyPuter/everything) | 1770 | 508 | +409 | 3.5 | [8](https://news.ycombinator.com/item?id=50075719) | everything · heyputer everything · puter everything | We're rebuilding and open-sourcing the world’s software from… |
| [Supermedo/uncharted_pc](https://github.com/Supermedo/uncharted_pc) | 1044 | 485 | +318 | 2.2 | — | uncharted pc · supermedo uncharted pc | Uncharted: The Nathan Drake Collection running natively on W… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 95.6 | 🟢 窗口内 | [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) | C | 2882 | +306 | +2882 | +0 | `·······▁█▇▄▅▃·` | 5 | [3](https://news.ycombinator.com/item?id=50102527) | — |
| 2 | 91.9 | ✅ 🟢 窗口内 | [storytold/figcraft](https://github.com/storytold/figcraft) | Rust | 2110 | +660 | +2109 | +1 | `·····▁··▁▇▇▆█·` | 7 | [3](https://news.ycombinator.com/item?id=50069000) | — |
| 3 | 88.1 | 🟢 窗口内 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | Python | 1632 | +174 | +1543 | +89 | `···▁▁▁▁█▆▃▂▄▃·` | 11 | [10](https://news.ycombinator.com/item?id=50037852) | — |
| 4 | 86.7 | 🟢 窗口内 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 1370 | +137 | +1370 | +0 | `·······▁▆█▄▃▃·` | 6 | — | — |
| 5 | 76.8 | 🟢 窗口内 | [marclou/mailcheap](https://github.com/marclou/mailcheap) | JavaScript | 1173 | +109 | +601 | +572 | `······█▄▂▂▁▃▂·` | 6 | [2](https://news.ycombinator.com/item?id=50033695) | — |
| 6 | 71.4 | ✅ 🟡 在降温 | [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) | Python | 2941 | +170 | +1255 | +1500 | `▆▅▅▆▇███▇▇▅▅▅·` | 13 | — | — |
| 7 | 61 | 🟡 在降温 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) | TypeScript | 1514 | +25 | +446 | +1068 | `····▃█▇▄▂▂▂▁▁·` | 9 | — | — |
| 8 | 60.8 | 🟡 在降温 | [feitangyuan/onetake](https://github.com/feitangyuan/onetake) | Python | 2541 | +75 | +437 | +652 | `▆███▅▅▄▄▆▆▆▅▅·` | 20 | — | — |
| 9 | 55.1 | 🟡 在降温 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) | Python | 2082 | +88 | +246 | +501 | `▇██▆▃▄▂▃▄▃▂▂▆·` | 16 | — | — |
| 10 | 53.1 | 🟡 在降温 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep) | TypeScript | 2755 | +31 | +201 | +360 | `█▆▅█▇▆▄▇▄▄▂▆▃·` | 20 | [5](https://news.ycombinator.com/item?id=49880146) | — |
| 11 | 42.5 | 🆕 🔴 先核对 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) | Go | 1209 | — | +1198 | +11 | `····▁▁▁▁█▆▁▁▁·` | 8 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 12 | 41.8 | 🆕 🔴 先核对 | [feder-cr/git-ai](https://github.com/feder-cr/git-ai) | Go | 1067 | — | +1067 | +0 | `···········█▁·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 13 | 41.8 | 🔴 先核对 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 1067 | +35 | +1067 | +0 | `········█▃▂▂▁·` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 14 | 40.8 | 🔴 先核对 | [outcrawlai/scout](https://github.com/outcrawlai/scout) | TypeScript | 900 | +60 | +900 | +0 | `··········█▂▁·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 15 | 39.9 | 🔵 已被发现 | [rociiu/talorys](https://github.com/rociiu/talorys) | TypeScript | 1257 | +76 | +768 | +489 | `······█▅▃▂▂▄▂·` | 6 | [329](https://news.ycombinator.com/item?id=50031614) | — |
| 16 | 35.4 | 🆕 🔴 先核对 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) | Python | 367 | — | +367 | +0 | `···········▄█·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 34.4 | 🆕 🔴 先核对 | [anujasid/mcp-for-blender-pro](https://github.com/anujasid/mcp-for-blender-pro) | Python | 306 | — | +306 | +0 | `············█·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 31.7 | 🔴 先核对 | [Graphicle-AI/graphicle](https://github.com/Graphicle-AI/graphicle) | Rust | 197 | +21 | +197 | +0 | `··········█▃▂·` | 2 | [47](https://news.ycombinator.com/item?id=50088713) | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 28.8 | 🔵 已被发现 | [pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust) | Rust | 1304 | +48 | +314 | +990 | `···█▄▂▃▂▂▂▂▂▂·` | 9 | [119](https://news.ycombinator.com/item?id=50000676) | — |
| 20 | 19.9 | 🔴 先核对 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) | Python | 2761 | +3 | +52 | +160 | `▅▃▃▂█▄▆▃▃▂▂▃▂·` | 17 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 538 | 30 | 44754 | [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill)、[onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent)、[feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) |
| `mcp` | 173 | 30 | 18031 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `rust` | 140 | 30 | 18740 | [storytold/figcraft](https://github.com/storytold/figcraft)、[academa-labs/manimgx](https://github.com/academa-labs/manimgx)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui) |
| `local-first` | 58 | 30 | 13493 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[glanderness/BeefTV](https://github.com/glanderness/BeefTV) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 22 | 20078 | [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) |
| `ai-agents` | 22 | 11347 | [penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `llm` | 17 | 12908 | [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `codex` | 16 | 12763 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) |
| `agent-skills` | 13 | 14480 | [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) |
| `macos` | 13 | 7685 | [freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[amontlabs/lcu](https://github.com/amontlabs/lcu) |
| `ai-agent` | 11 | 11056 | [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent)、[freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `mcp-server` | 11 | 7694 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `developer-tools` | 10 | 7834 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill) |
| `typescript` | 9 | 8012 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `coding-agents` | 9 | 7332 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[devswha/herdr-web-ui](https://github.com/devswha/herdr-web-ui)、[feder-cr/git-ai](https://github.com/feder-cr/git-ai) |
| `python` | 9 | 5666 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[Harvil1/codeAgent](https://github.com/Harvil1/codeAgent)、[jev-chat/jev-chat-windows](https://github.com/jev-chat/jev-chat-windows) |

**语言分布**：Python 33 · Rust 30 · TypeScript 21 · JavaScript 9 · Go 5 · Swift 4 · Astro 1 · C 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) · 🟢 窗口内 · 95.6 分

> Let an AI model use a real iPhone with a $7 ESP32: AirPlay eyes, USB HID hands, any OpenAI-compatible vision model. No Mac, no developer account, no jailbreak.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2882 | +2882 | +0 | 371 | 6 | C | MIT | 10-11（5 天前） | 今天 |

- **近 14 天每天新增**：`·······▁█▇▄▅▃·` 0 0 0 0 0 0 0 39 922 803 421 468 229 0
- **势头**：刚发布一周内
- **HN**：发过 2 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=50102527)）
- **topics**：`ai-agent` `airplay` `automation` `computer-use` `esp32` `esp32-s3` `iphone` `llm` `usb-hid`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. ✅ [storytold/figcraft](https://github.com/storytold/figcraft) · 🟢 窗口内 · 91.9 分

> FigCraft: interface design and prototyping; an open-source, clean-room reimplementation of collaborative design workflows in pure Rust

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2110 | +2109 | +1 | 781 | 228 | Rust | Apache-2.0 | 10-09（7 天前） | 今天 |

- **近 14 天每天新增**：`·····▁··▁▇▇▆█·` 0 0 0 0 0 1 0 0 3 529 544 405 628 0
- **势头**：比前 7 天快 2109.0 倍，在加速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=50069000)）
- **topics**：`design` `rust` `tools`
- **主页**：<https://getartcraft.com/apps/figcraft>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [academa-labs/manimgx](https://github.com/academa-labs/manimgx) · 🟢 窗口内 · 88.1 分

> The animation engine for agents: blazingly fast math and 3D videos with Manim's Python API, on a Rust GPU core.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1632 | +1543 | +89 | 115 | 10 | Python | MIT | 10-05（11 天前） | 1 天前 |

- **近 14 天每天新增**：`···▁▁▁▁█▆▃▂▄▃·` 0 0 0 7 31 11 40 567 368 125 106 235 142 0
- **势头**：比前 7 天快 17.3 倍，在加速
- **HN**：发过 1 次，最高 10 分（[讨论](https://news.ycombinator.com/item?id=50037852)）
- **主页**：<https://manimgx.academa.ai>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [opengeos/RustGIS](https://github.com/opengeos/RustGIS) · 🟢 窗口内 · 86.7 分

> A fast, free and open-source GIS in pure Rust.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1370 | +1370 | +0 | 190 | 34 | Rust | Apache-2.0 | 10-10（6 天前） | 今天 |

- **近 14 天每天新增**：`·······▁▆█▄▃▃·` 0 0 0 0 0 0 0 2 372 493 237 143 123 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`geospatial` `gis` `remote-sensing` `rust` `rust-lang`
- **主页**：<https://rustgis.app>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [marclou/mailcheap](https://github.com/marclou/mailcheap) · 🟢 窗口内 · 76.8 分

> Newsletters where you pay for the emails you send, not for dormant subscribers, at a fraction of the price of beehiiv and the like. Open source: self-host it, or use mailcheap.ai.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1173 | +601 | +572 | 295 | 11 | JavaScript | AGPL-3.0 | 10-10（6 天前） | 今天 |

- **近 14 天每天新增**：`······█▄▂▂▁▃▂·` 0 0 0 0 0 0 572 213 52 63 30 147 96 0
- **势头**：比前 7 天快 1.1 倍，在加速
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50033695)）
- **topics**：`ai-agents` `amazon-ses` `beehiiv-alternative` `email` `email-marketing` `mailchimp-alternative` `mcp` `mcp-server` `mongodb` `newsletter` `nextjs` `self-hosted` `substack-alternative`
- **主页**：<https://mailcheap.ai>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. ✅ [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) · 🟡 在降温 · 71.4 分

> Eleven free Claude skills that clone any app: reverse-engineer it, rebuild it, test it for bugs, then fix what its users hate. Free, MIT.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2941 | +1255 | +1500 | 447 | 7 | Python | MIT | 10-03（13 天前） | 13 天前 |

- **近 14 天每天新增**：`▆▅▅▆▇███▇▇▅▅▅·` 216 156 168 188 228 277 267 270 254 255 176 143 157 0
- **势头**：只有前 7 天的 84%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent` `agent-skills` `app-clone` `claude` `claude-code` `claude-skills` `indie-hacker` `reverse-engineering` `saas`
- **主页**：<https://opusjake.ai>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 7. [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) · 🟡 在降温 · 61 分

> Your company's data, connected into one ontology, on your own computer. A local-first data workspace built on HelixDB and DuckDB.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1514 | +446 | +1068 | 231 | 16 | TypeScript | Apache-2.0 | 10-07（9 天前） | 3 天前 |

- **近 14 天每天新增**：`····▃█▇▄▂▂▂▁▁·` 0 0 0 0 137 504 427 180 99 66 60 19 22 0
- **势头**：只有前 7 天的 42%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [feitangyuan/onetake](https://github.com/feitangyuan/onetake) · 🟡 在降温 · 60.8 分

> Motion films that never cut to the next slide: every beat grows out of the one before, one continuous camera, continuity measured by an oracle. Product launch films and feature demos, made with a coding agent.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2541 | +437 | +652 | 167 | 3 | Python | — | 09-26（20 天前） | 4 天前 |

- **近 14 天每天新增**：`▆███▅▅▄▄▆▆▆▅▅·` 85 123 122 118 77 69 58 50 86 80 84 73 64 0
- **势头**：只有前 7 天的 67%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `animation` `canvas` `claude-skill` `launch-video` `motion-graphics` `video`
- **主页**：<https://onetakemotion.com>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) · 🟡 在降温 · 55.1 分

> AI生成の日本語を自然な日本語へ推敲するAgent Skill / Agent Skill for Refining AI-Generated Japanese into Natural Japanese

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2082 | +246 | +501 | 61 | 0 | Python | MIT | 09-30（16 天前） | 今天 |

- **近 14 天每天新增**：`▇██▆▃▄▂▃▄▃▂▂▆·` 93 112 111 78 37 47 23 37 49 33 18 22 87 0
- **势头**：只有前 7 天的 49%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-writing` `antigravity` `claude-code` `codex` `cursor` `gemini` `japanese` `linter` `llm` `nlp` `writing` `writing-assistant` `writing-tool`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [dzhng/jevgrep](https://github.com/dzhng/jevgrep) · 🟡 在降温 · 53.1 分

> Find code by asking what it does. A CLI for coding agents that uses Jev to discover relevant files and source context.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2755 | +201 | +360 | 206 | 32 | TypeScript | MIT | 09-26（20 天前） | 1 天前 |

- **近 14 天每天新增**：`█▆▅█▇▆▄▇▄▄▂▆▃·` 70 53 35 69 59 45 29 58 31 31 5 52 24 0
- **势头**：只有前 7 天的 56%，在减速
- **HN**：发过 1 次，最高 5 分（[讨论](https://news.ycombinator.com/item?id=49880146)）
- **topics**：`ai-sdk` `claude-code` `cli` `code-search` `codex` `coding-agents` `context-retrieval` `developer-tools` `jev` `semantic-search` `typescript` `vercel-ai-gateway`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) — 一天进了一半以上的 star，但 HN 上没火过
- [feder-cr/git-ai](https://github.com/feder-cr/git-ai) — 一天进了一半以上的 star，但 HN 上没火过
- [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) — 一天进了一半以上的 star，但 HN 上没火过
- [outcrawlai/scout](https://github.com/outcrawlai/scout) — 一天进了一半以上的 star，但 HN 上没火过
- [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) — 一天进了一半以上的 star，但 HN 上没火过
- [anujasid/mcp-for-blender-pro](https://github.com/anujasid/mcp-for-blender-pro) — 一天进了一半以上的 star，但 HN 上没火过
- [Graphicle-AI/graphicle](https://github.com/Graphicle-AI/graphicle) — 一天进了一半以上的 star，但 HN 上没火过
- [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 569 | 161 | [Show HN: Guitoro, a virtual guitar you strum with your keyboard](https://guitoro.com/) | [HN](https://news.ycombinator.com/item?id=50077020) |
| 314 | 158 | [Show HN: PS2 games statically recompiled to WebAssembly](https://github.com/snuri00/ps2-web-recomp) | [HN](https://news.ycombinator.com/item?id=50052251) |
| 311 | 197 | [Show HN: Unfenced – Land for sale that borders public land](https://unfenced.land/) | [HN](https://news.ycombinator.com/item?id=50102247) |
| 286 | 130 | [Show HN: WallHop – 12ft.io is gone, so I built a replacement](https://wallhop.io/) | [HN](https://news.ycombinator.com/item?id=50038634) |
| 220 | 127 | [Show HN: BetterWispr – Free, open-source dictation for Mac](https://betterwispr.com/) | [HN](https://news.ycombinator.com/item?id=50042333) |
| 220 | 41 | [Show HN: Petal, open-source CoScreen/ScreenHero finally free](https://petal.live/) | [HN](https://news.ycombinator.com/item?id=50092470) |
| 215 | 120 | [Show HN: How random are you?](https://lab.specr.net/rigged-draw/) | [HN](https://news.ycombinator.com/item?id=50074909) |
| 197 | 89 | [Show HN: Gemini 4 Argon plays StarCraft](https://starskirmish.com/bench/v0-2/) | [HN](https://news.ycombinator.com/item?id=50118688) |
| 174 | 90 | [Show HN: Use your OpenAI subscription to create audiobooks](https://pdftomp3.com/connect-ai/) | [HN](https://news.ycombinator.com/item?id=50069337) |
| 141 | 51 | [Show HN: SolidCraft – Open-Source Parametric CAD in Rust (With MCP Support)](https://github.com/bherbruck/solidcraft) | [HN](https://news.ycombinator.com/item?id=50064840) |
| 137 | 66 | [Show HN: Flipflop – Iroh-powered persistent tunnels for filesharing](https://github.com/andunieee/flipflop) | [HN](https://news.ycombinator.com/item?id=50099136) |
| 121 | 71 | [Show HN: Pulse Local, a Mac budgeting app whose AI models run on your machine](https://pulseos.finance) | [HN](https://news.ycombinator.com/item?id=50080275) |
| 118 | 44 | [Show HN: Indigene – Native plants for where you stand](https://indigene.app/) | [HN](https://news.ycombinator.com/item?id=50064470) |
| 117 | 76 | [Show HN: I built a tool to track what AI leaders say and how their views change](https://blumify.io/people) | [HN](https://news.ycombinator.com/item?id=50081151) |
| 115 | 30 | [Show HN: Atticus – Hold-to-talk voice assistant for macOS that runs on Claude -p](https://github.com/SaarthurR/atticus-mac) | [HN](https://news.ycombinator.com/item?id=50049588) |
| 114 | 96 | [Show HN: I wrote an email app that accepts only one sender per inbox](https://clova.email/) | [HN](https://news.ycombinator.com/item?id=50090932) |
| 104 | 34 | [Show HN: Proa – A Rust web framework with fast SSR and multi-target rendering](https://proa.so/) | [HN](https://news.ycombinator.com/item?id=50105467) |
| 91 | 19 | [Show HN: Spotatui, a Spotify TUI/GUI without web API rate limits](https://github.com/LargeModGames/spotatui) | [HN](https://news.ycombinator.com/item?id=50070010) |
| 90 | 41 | [Show HN: A guided 3D Leonardo da Vinci museum, built in code](https://museumofages.org/w/vinci) | [HN](https://news.ycombinator.com/item?id=50085022) |
| 85 | 83 | [Show HN: XY Music Notation](https://music.xy.dev/) | [HN](https://news.ycombinator.com/item?id=50075665) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 28 | [AutoDev: Automated AI-Driven Development](https://huggingface.co/papers/2403.08299) | AutoDev is an AI-driven software development framework that automates complex engineering tasks within a secure Docker environment, achievin… | [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi) 30705★ |
| 47 | [RSI-Anything: Unlocking Recursive Self-Improvement with World Models](https://huggingface.co/papers/2610.13912) | RSI-Anything leverages predictive world models to guide action selection and adaptive learning, enabling recursive self-improvement across c… | 💡 [Gen-Verse/RSI-Anything](https://github.com/Gen-Verse/RSI-Anything) 772★ |
| 27 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 5357★ |
| 103 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | 💡 [google-research/harness2](https://github.com/google-research/harness2) 660★ |
| 341 | [Any Time, Any Space: A World-State-Centric Framework for Agentic Video Generation](https://huggingface.co/papers/2610.20571) | ATAS improves long-form video consistency by compiling screenplays into referenced shot requests, retrieving spatial and temporal evidence f… | 💡 [ziplab/ATAS](https://github.com/ziplab/ATAS) 237★ |
| 152 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 111485★ |
| 93 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 27672★ |
| 332 | [Player-1: Learning to Play from Synthetic Experience](https://huggingface.co/papers/2610.20584) | Player-1 improves game control by combining supervised fine-tuning on gameplay trajectories with reinforcement learning across synthetic env… | 💡 [TencentARC/Player-1](https://github.com/TencentARC/Player-1) 103★ |
| 116 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 1333★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 91073★ |
| 121 | [Urbex: Agentic Spatial Grounding for City-Scale 3D Scenes](https://huggingface.co/papers/2610.18356) | Urbex reframes city-scale 3D grounding as an active search process using a vision-language agent with reinforcement learning, improving accu… | 💡 [AMAP-ML/Urbex](https://github.com/AMAP-ML/Urbex) 97★ |
| 237 | [YuE2: Unifying Symbolic and Audio Music Generation at Frontier Quality](https://huggingface.co/papers/2609.33757) | YuE2 unifies symbolic and audio music generation via symbolic planning, producing readable scores and full-song audio with state-of-the-art… | [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE) 12037★ |
| 190 | [Self-Evolving Agent Harness](https://huggingface.co/papers/2610.18813) | A framework for self-evolving agent harnesses uses feedback-driven revisions and evolutionary optimization with theoretical generalization g… | 💡 [zgcagi/Harness-RSI](https://github.com/zgcagi/Harness-RSI) 112★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 351 | [VideoJev: System One Model for Video Understanding and Interaction](https://huggingface.co/papers/2610.18615) | VideoJev converts video observations into structured decisions by scoring temporal intervals and text options, enabling efficient reusable i… | 💡 [MCG-NJU/VideoJev](https://github.com/MCG-NJU/VideoJev) 153★ |
| 180 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 81873★ |
| 31 | [Internal Safety Collapse in Frontier Large Language Models](https://huggingface.co/papers/2603.23509) | Frontier large language models exhibit Internal Safety Collapse, where they generate harmful content under specific task conditions, reveali… | [wuyoscar/ISC-Bench](https://github.com/wuyoscar/ISC-Bench) 1497★ |
| 32 | [Towards Agentic Robots: Model, Data, Environment, and Harness](https://huggingface.co/papers/2610.20442) | This survey unifies research on agentic robots by tracing the evolution from robot policies to integrated systems using vision-language-acti… | 💡 [chonghanqin/Awesome-Agentic-Robots](https://github.com/chonghanqin/Awesome-Agentic-Robots) 76★ |
| 13 | [PyTorch Distributed: Experiences on Accelerating Data Parallel Training](https://huggingface.co/papers/2006.15704) | The PyTorch distributed data parallel module optimizes large-scale model training using techniques like gradient bucketing, computation-comm… | [pytorch/pytorch](https://github.com/pytorch/pytorch) 104804★ |
| 34 | [HuggingFace's Transformers: State-of-the-art Natural Language Processing](https://huggingface.co/papers/1910.03771) | Transformers library provides state-of-the-art Transformer architectures and pretrained models for natural language processing tasks with a… | [huggingface/transformers](https://github.com/huggingface/transformers) 167765★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 31 | [moss image](https://huggingface.co/OpenMOSS-Team/MOSS-Image-Base) | text-to-image | 149 | 1 |
| 34 | [moss image sft](https://huggingface.co/OpenMOSS-Team/MOSS-Image-SFT) | text-to-image | 148 | 1 |
| 39 | [hy memory](https://huggingface.co/tencent/Hy-Memory-30B-A3B) | text-generation | 126 | 1 |
| 50 | [beam 1.0](https://huggingface.co/reflection/Beam-1.0-501B-A23B) | text-generation | 114 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 58 | 10 | [The NIST Elliptic Curves Seeds Bounty Has Been Claimed](https://words.filippo.io/seeds-solved/) | `cryptography` | [讨论](https://lobste.rs/s/ddtqtn/nist_elliptic_curves_seeds_bounty_has) |
| 18 | 9 | [The Decoherence Trap: When AI slop drowns out the signal in an endless sea of noise](https://maevyn.codes/decoherence) | `vibecoding` | [讨论](https://lobste.rs/s/vjmn84/decoherence_trap_when_ai_slop_drowns_out) |
| 49 | 11 | [The road to iroh 1.0](https://www.iroh.computer/blog/the-road-to-iroh-1-0) | `networking` | [讨论](https://lobste.rs/s/6laoto/road_iroh_1_0) |
| 91 | 13 | [Why are we even doing all this?](https://terrytao.wordpress.com/2026/10/15/why-are-we-even-doing-all-this/) | `math` `vibecoding` | [讨论](https://lobste.rs/s/qvomvk/why_are_we_even_doing_all_this) |
| 85 | 149 | [Linus Torvalds on AI-assisted kernel contributions](https://lore.kernel.org/lkml/CAHk-=whTs09_ozN+e09GU68N1wPP56MUzDjrg9rnKxQUa0A_4Q@mail.gmail.com/) | `linux` `vibecoding` | [讨论](https://lobste.rs/s/xiq59t/linus_torvalds_on_ai_assisted_kernel) |
| 38 | 9 | [Making a 88x31 button book using ImageMagick](https://k.sosnierz.me/08-11-24/) | `art` | [讨论](https://lobste.rs/s/v6hhdr/making_88x31_button_book_using) |
| 28 | 0 | [Big Fish: Exploiting a 37-Year-Old Kernel Bug in OpenBSD](https://calif.io/research/big-fish) | `openbsd` `security` | [讨论](https://lobste.rs/s/cxlrc5/big_fish_exploiting_37_year_old_kernel_bug) |
| 17 | 1 | [Getting Canceled](https://www.youtube.com/watch?v=5zIOfBLQ3U4) | `video` `zig` | [讨论](https://lobste.rs/s/tty7hm/getting_canceled) |
| 12 | 8 | [Mull: note-taking with a language server / vscode extension](https://github.com/stepchowfun/mull) | `editors` | [讨论](https://lobste.rs/s/xcacrh/mull_note_taking_with_language_server) |
| 14 | 2 | [Introducing GNOME OS Preview](https://blogs.gnome.org/adrianvovk/2026/10/16/gnome-os-preview/) | `linux` `release` | [讨论](https://lobste.rs/s/xwng6u/introducing_gnome_os_preview) |
| 100 | 30 | [JPEG XL vs AVIF for web use-cases](https://jakearchibald.com/2026/jpeg-xl-vs-avif/) | `compsci` `web` | [讨论](https://lobste.rs/s/uejdwj/jpeg_xl_vs_avif_for_web_use_cases) |
| 14 | 0 | [We're sunsetting Codeberg Pages v2](https://blog.codeberg.org/migrate-your-site-to-the-new-git-pages-backed-codeberg-pages-now-were-sunsetting-codeberg-pages-v2.html) | `web` | [讨论](https://lobste.rs/s/e7rvsp/we_re_sunsetting_codeberg_pages_v2) |
| 11 | 0 | [Ubuntu 26.10 (Stonking Stingray) released](https://lists.ubuntu.com/archives/ubuntu-announce/2026-October/000330.html) | `linux` `release` | [讨论](https://lobste.rs/s/61ujum/ubuntu_26_10_stonking_stingray_released) |
| 62 | 15 | [My C23 Conventions](https://abner.page/post/c23-conventions-1/) | `c` | [讨论](https://lobste.rs/s/umdbht/my_c23_conventions) |
| 4 | 4 | [There's never been a better time to go into math](https://www.youtube.com/watch?v=LKrwhjOI8Nc) | `math` `video` | [讨论](https://lobste.rs/s/wzgadv/there_s_never_been_better_time_go_into_math) |
| 36 | 20 | [Epic's EAC2 v2 seems fairly easily bypassable](https://codon.org.uk/~mjg59/blog/p/epics-eac2-v2-seems-fairly-easily-bypassable/) | `linux` `security` | [讨论](https://lobste.rs/s/1iin5o/epic_s_eac2_v2_seems_fairly_easily) |
| 3 | 1 | [Do you let LLMs write both your tests and your code?](https://lobste.rs/s/miwcai) | `vibecoding` | [讨论](https://lobste.rs/s/miwcai/do_you_let_llms_write_both_your_tests_your) |
| 12 | 26 | [What are you doing this weekend?](https://lobste.rs/s/hounpx) | `ask` `programming` | [讨论](https://lobste.rs/s/hounpx/what_are_you_doing_this_weekend) |
| 3 | 0 | [Interactive refactoring in gopls](https://go.dev/blog/interactive-refactoring) | `editors` `go` | [讨论](https://lobste.rs/s/wn293o/interactive_refactoring_gopls) |
| 30 | 7 | [Announcing Rust 1.99.1](https://blog.rust-lang.org/2026/10/15/Rust-1.99.1/) | `release` `rust` | [讨论](https://lobste.rs/s/ttcx5k/announcing_rust_1_99_1) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

_还没有到 14 天的，40 个在等。_

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
