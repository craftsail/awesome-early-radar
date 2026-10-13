# early-radar 选题雷达 · 2026-10-13

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 112 个，细查前 20 个 · 生成于 2026-10-13 09:59 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 第一次，只记下榜单 · Show HN ✅ 28 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 0 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 9 个 · 🟡 在降温 4 个 · 🔵 已被发现 2 个 · 💤 不活跃 0 个 · 🔴 先核对 5 个
- **第一次运行**：只记下今天的 star 和榜单，下次开始有「比上次」、🆕 和 HF 新上榜
- **🚀 爆发 15 个**：最快的 [storytold/photocraft](https://github.com/storytold/photocraft) 平均每天 +4308，见 [爆发](#爆发)
- **最值得今天试的**：
  - [ARahim3/DigUp](https://github.com/ARahim3/DigUp) — Search your Mac by what's in your files: photos, PDFs, recor…（近 7 天 +2071，刚发布一周内）
  - [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) — Your company's data, connected into one ontology, on your ow…（近 7 天 +1362，刚发布一周内）
  - [bherbruck/solidcraft](https://github.com/bherbruck/solidcraft) — SolidCraft: an open-source parametric 3D CAD application bui…（近 7 天 +1330，刚发布一周内）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 25 个（star 合计 20634），代表：[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：4 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Bigwords.page – Turn any screen into a sign. The URL is the app](https://bigwords.page/) — 725 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| ✅ [storytold/photocraft](https://github.com/storytold/photocraft) | 55351 | 4308 | — | 12.8 | [140](https://news.ycombinator.com/item?id=49981449) | photocraft · storytold photocraft · artcraft photocraft | PhotoCraft: An open-source, photo editor written by scratch… |
| [openai/math](https://github.com/openai/math) | 14551 | 2236 | — | 6.5 | [342](https://news.ycombinator.com/item?id=50003107) | math · openai math |  |
| ✅ [storytold/wordcraft](https://github.com/storytold/wordcraft) | 9968 | 1645 | — | 6.1 | [100](https://news.ycombinator.com/item?id=50050370) | wordcraft · storytold wordcraft · artcraft wordcraft | An open-source, clean-room reimplementation of Microsoft Wor… |
| [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) | 7146 | 1432 | — | 5 | — | anatomy · wheresryan22 anatomy · ryan anatomy | An agent skill for creating detailed, interactive isometric… |
| ✅ [storytold/pdfcraft](https://github.com/storytold/pdfcraft) | 11968 | 932 | — | 12.8 | — | pdfcraft · storytold pdfcraft · artcraft pdfcraft | PdfCraft: An open-source PDF reader and editor written by sc… |
| ✅ [storytold/filmcraft](https://github.com/storytold/filmcraft) | 11924 | 928 | — | 12.8 | [2](https://news.ycombinator.com/item?id=50069000) | filmcraft · storytold filmcraft · artcraft filmcraft | FilmCraft: An open-source, nonlinear video editor written by… |
| [jhaizhou-ops/d2r-mobile](https://github.com/jhaizhou-ops/d2r-mobile) | 960 | 911 | — | 1.1 | — | d2r mobile · jhaizhou-ops d2r mobile | Open-source iOS compatibility layer for Diablo II: Resurrect… |
| ✅ [storytold/lightcraft](https://github.com/storytold/lightcraft) | 11560 | 901 | — | 12.8 | — | lightcraft · storytold lightcraft · artcraft lightcraft | LightCraft: An open-source non-destructive photo editor writ… |
| [liseami/CCBaga](https://github.com/liseami/CCBaga) | 1894 | 839 | — | 2.3 | — | ccbaga · liseami ccbaga · purefantasyzhao ccbaga |  |
| [mhtsec/ARTEX](https://github.com/mhtsec/ARTEX) | 3778 | 729 | — | 5.2 | — | artex · mhtsec artex · mht artex | AI 自主渗透测试系统 / 百度“agent+”攻防挑战赛冠军项目 |
| [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) | 1113 | 688 | — | 1.6 | — | esp32 iphone agent · onehumanbeing esp32 iphone agent · henry esp32 iphone agent | Let an AI model use a real iPhone with a $7 ESP32: AirPlay e… |
| [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | 758 | 679 | — | 1.1 | — | new term radar · zhuyansen new term radar · jasonzhu new term radar | Daily radar for new AI terms: names of new models, products… |
| ✅ [storytold/gridcraft](https://github.com/storytold/gridcraft) | 4090 | 660 | — | 6.2 | — | gridcraft · storytold gridcraft · artcraft gridcraft | GridCraft: an open-source, clean-room spreadsheet (Microsoft… |
| ✅ [storytold/vectorcraft](https://github.com/storytold/vectorcraft) | 8119 | 632 | — | 12.8 | — | vectorcraft · storytold vectorcraft · artcraft vectorcraft | VectorCraft: An open-source, vector art tool written by scra… |
| ✅ [storytold/cadcraft](https://github.com/storytold/cadcraft) | 3750 | 606 | — | 6.2 | — | cadcraft · storytold cadcraft · artcraft cadcraft | CADCraft: computer-aided design and drafting — an open-sourc… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 94.9 | ✅ 🟢 窗口内 | [storytold/deckcraft](https://github.com/storytold/deckcraft) | Rust | 2734 | — | +2722 | +12 | `······▁▃▅▇▆█▇▂` | 6 | — | — |
| 2 | 93.2 | ✅ 🟢 窗口内 | [storytold/soundcraft](https://github.com/storytold/soundcraft) | Rust | 2365 | — | +2365 | +0 | `·······▄▆▇▆█▆▁` | 6 | — | — |
| 3 | 91.6 | 🟢 窗口内 | [ARahim3/DigUp](https://github.com/ARahim3/DigUp) | Swift | 2071 | — | +2071 | +0 | `·········▁▃█▆▁` | 4 | [4](https://news.ycombinator.com/item?id=50045015) | — |
| 4 | 87.9 | ✅ 🟢 窗口内 | [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) | Python | 2241 | — | +1513 | +728 | `···▆▆▅▅▆▇███▇▂` | 9 | — | — |
| 5 | 86.6 | 🟢 窗口内 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) | TypeScript | 1362 | — | +1362 | +0 | `········▃█▇▄▂▁` | 6 | — | — |
| 6 | 86.3 | 🟢 窗口内 | [bherbruck/solidcraft](https://github.com/bherbruck/solidcraft) | Rust | 1330 | — | +1330 | +0 | `·········▂▂█▇▂` | 5 | [59](https://news.ycombinator.com/item?id=50064840) | — |
| 7 | 70.4 | 🟢 窗口内 | [mrsarac/ff-tracking](https://github.com/mrsarac/ff-tracking) | Rust | 351 | — | +351 | +0 | `·········█▄▄▃▁` | 3 | — | — |
| 8 | 70.3 | 🟢 窗口内 | [morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering) | — | 349 | — | +349 | +0 | `·········▂▂▅█▂` | 3 | — | — |
| 9 | 66.6 | 🟢 窗口内 | [Ayzzz123/mcd-coupon-strategist](https://github.com/Ayzzz123/mcd-coupon-strategist) | Python | 256 | — | +256 | +0 | `··········█▇▇▁` | 2 | — | — |
| 10 | 61.5 | 🟡 在降温 | [tobi/disktree](https://github.com/tobi/disktree) | Rust | 2876 | — | +470 | +481 | `▄▃▃▃▃▂▂▃▂▂▂█▃▁` | 18 | [3](https://news.ycombinator.com/item?id=49841155) | — |
| 11 | 61.5 | 🟡 在降温 | [feitangyuan/onetake](https://github.com/feitangyuan/onetake) | Python | 2249 | — | +467 | +795 | `▄▅█▄▄▆▆▅▄▄▃▃▄▁` | 17 | — | — |
| 12 | 57 | 🟡 在降温 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep) | TypeScript | 2651 | — | +297 | +548 | `█▇▅█▅▄▃▅▅▄▃▅▃▁` | 17 | [5](https://news.ycombinator.com/item?id=49880146) | — |
| 13 | 56.2 | 🟡 在降温 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) | Python | 1929 | — | +274 | +1655 | `█▆▃▂▂▂▂▂▁▂▁▁▂▁` | 12 | — | — |
| 14 | 42.2 | 🔵 已被发现 | [pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust) | Rust | 1139 | — | +1139 | +0 | `·······█▄▂▃▂▂▁` | 6 | [118](https://news.ycombinator.com/item?id=50000676) | — |
| 15 | 42.1 | 🔴 先核对 | [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) | Python | 1113 | — | +1113 | +0 | `···········▁█▂` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 16 | 41.8 | 🔴 先核对 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | Python | 1057 | — | +1057 | +0 | `·······▁▁▁▂█▆▁` | 7 | [10](https://news.ycombinator.com/item?id=50037852) | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 41 | 🔵 已被发现 | [rociiu/talorys](https://github.com/rociiu/talorys) | TypeScript | 920 | — | +920 | +0 | `··········█▅▃▁` | 3 | [328](https://news.ycombinator.com/item?id=50031614) | — |
| 18 | 39.8 | 🔴 先核对 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 758 | — | +758 | +0 | `············█▁` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 36.9 | 🔴 先核对 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 469 | — | +469 | +0 | `···········▁█▃` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 24.4 | 🔴 先核对 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) | Python | 2764 | — | +131 | +2162 | `█▃▂▁▁▁▁▁▁▁▁▁▁▁` | 13 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 494 | 30 | 40663 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth) |
| `mcp` | 154 | 30 | 16202 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[bherbruck/solidcraft](https://github.com/bherbruck/solidcraft)、[leemysw/yovoice](https://github.com/leemysw/yovoice) |
| `rust` | 119 | 30 | 23480 | [tobi/disktree](https://github.com/tobi/disktree)、[storytold/deckcraft](https://github.com/storytold/deckcraft)、[storytold/soundcraft](https://github.com/storytold/soundcraft) |
| `local-first` | 62 | 30 | 13527 | [ARahim3/DigUp](https://github.com/ARahim3/DigUp)、[RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 25 | 20634 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) |
| `codex` | 20 | 16643 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) |
| `ai-agents` | 20 | 10588 | [Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill)、[krishhgg/Insomnia](https://github.com/krishhgg/Insomnia) |
| `macos` | 18 | 11957 | [ARahim3/DigUp](https://github.com/ARahim3/DigUp)、[freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[krishhgg/Insomnia](https://github.com/krishhgg/Insomnia) |
| `llm` | 15 | 8587 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `agent-skills` | 14 | 13924 | [Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) |
| `developer-tools` | 10 | 7252 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui) |
| `jev` | 10 | 7139 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[ollaya-dev/ollaya](https://github.com/ollaya-dev/ollaya)、[jev-chat/jev-chat-windows](https://github.com/jev-chat/jev-chat-windows) |
| `windows` | 10 | 6253 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[leemysw/yovoice](https://github.com/leemysw/yovoice)、[jev-chat/jev-chat-windows](https://github.com/jev-chat/jev-chat-windows) |
| `linux` | 9 | 5833 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[amontlabs/lcu](https://github.com/amontlabs/lcu)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `ai-agent` | 9 | 5482 | [freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `python` | 9 | 4948 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[jev-chat/jev-chat-windows](https://github.com/jev-chat/jev-chat-windows)、[jev-chat/jev-chat-jarvis-mac](https://github.com/jev-chat/jev-chat-jarvis-mac) |

**语言分布**：Python 38 · Rust 28 · TypeScript 20 · Swift 7 · JavaScript 6 · Go 5 · C++ 1 · Lua 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. ✅ [storytold/deckcraft](https://github.com/storytold/deckcraft) · 🟢 窗口内 · 94.9 分

> Presentations and slide shows: an open-source, clean-room reimplementation of Microsoft PowerPoint in pure Rust. Part of the ArtCraft Crafting Apps.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2734 | +2722 | +12 | 1473 | 258 | Rust | Apache-2.0 | 10-07（6 天前） | 今天 |

- **近 14 天每天新增**：`······▁▃▅▇▆█▇▂` 0 0 0 0 0 0 12 200 344 495 459 629 544 51
- **势头**：比前 7 天快 226.8 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://getartcraft.com/apps/slidecraft>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. ✅ [storytold/soundcraft](https://github.com/storytold/soundcraft) · 🟢 窗口内 · 93.2 分

> An open-source, clean-room reimplementation of Avid Pro Tools in pure Rust

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2365 | +2365 | +0 | 1451 | 154 | Rust | Apache-2.0 | 10-07（6 天前） | 今天 |

- **近 14 天每天新增**：`·······▄▆▇▆█▆▁` 0 0 0 0 0 0 0 240 400 412 351 523 403 36
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://getartcraft.com/apps/soundcraft>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [ARahim3/DigUp](https://github.com/ARahim3/DigUp) · 🟢 窗口内 · 91.6 分

> Search your Mac by what's in your files: photos, PDFs, recordings, videos and code. On-device, built on Google DeepMind's EmbeddingGemma 2.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2071 | +2071 | +0 | 156 | 46 | Swift | MIT | 10-08（4 天前） | 今天 |

- **近 14 天每天新增**：`·········▁▃█▆▁` 0 0 0 0 0 0 0 0 0 1 309 1034 668 59
- **势头**：刚发布一周内
- **HN**：发过 2 次，最高 4 分（[讨论](https://news.ycombinator.com/item?id=50045015)）
- **topics**：`embeddinggemma` `embeddings` `llama-cpp` `local-first` `macos` `menubar-app` `multimodal` `on-device` `semantic-search` `swift`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. ✅ [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) · 🟢 窗口内 · 87.9 分

> Eleven free Claude skills that clone any app: reverse-engineer it, rebuild it, test it for bugs, then fix what its users hate. Free, MIT.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2241 | +1513 | +728 | 325 | 5 | Python | MIT | 10-03（9 天前） | 9 天前 |

- **近 14 天每天新增**：`···▆▆▅▅▆▇███▇▂` 0 0 0 187 217 156 168 188 229 279 267 270 255 25
- **势头**：比前 7 天快 2.1 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent` `agent-skills` `app-clone` `claude` `claude-code` `claude-skills` `indie-hacker` `reverse-engineering` `saas`
- **主页**：<https://opusjake.ai>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) · 🟢 窗口内 · 86.6 分

> Your company's data, connected into one ontology, on your own computer. A local-first data workspace built on HelixDB and DuckDB.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1362 | +1362 | +0 | 211 | 7 | TypeScript | Apache-2.0 | 10-07（6 天前） | 今天 |

- **近 14 天每天新增**：`········▃█▇▄▂▁` 0 0 0 0 0 0 0 0 137 504 428 180 99 14
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [bherbruck/solidcraft](https://github.com/bherbruck/solidcraft) · 🟢 窗口内 · 86.3 分

> SolidCraft: an open-source parametric 3D CAD application built in pure Rust. Desktop, web, and automation through MCP.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1330 | +1330 | +0 | 129 | 156 | Rust | Apache-2.0 | 10-07（5 天前） | 今天 |

- **近 14 天每天新增**：`·········▂▂█▇▂` 0 0 0 0 0 0 0 0 0 46 100 572 502 110
- **势头**：刚发布一周内
- **HN**：发过 1 次，最高 59 分（[讨论](https://news.ycombinator.com/item?id=50064840)）
- **topics**：`3d-modeling` `brep` `cad` `egui` `mcp` `parametric-cad` `rust` `step` `wasm`
- **主页**：<https://bherbruck.github.io/solidcraft/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [mrsarac/ff-tracking](https://github.com/mrsarac/ff-tracking) · 🟢 窗口内 · 70.4 分

> A virtual camera films an AI agent's screen while a tracker locks onto every glyph. Two fframes passes, one SkSL shader, all sound synthesized.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 351 | +351 | +0 | 21 | 0 | Rust | MIT | 10-09（3 天前） | 今天 |

- **近 14 天每天新增**：`·········█▄▄▃▁` 0 0 0 0 0 0 0 0 0 171 65 68 42 5
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`fframes` `generative-video` `hud` `motion-graphics` `rust` `shader` `skia` `sksl`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering) · 🟢 窗口内 · 70.3 分

> Curated reverse-engineering tools and learning resources for binaries, apps, firmware, formats, and protocols.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 349 | +349 | +0 | 74 | 1 | — | CC0-1.0 | 10-09（3 天前） | 今天 |

- **近 14 天每天新增**：`·········▂▂▅█▂` 0 0 0 0 0 0 0 0 0 29 35 100 170 15
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-agents` `awesome` `awesome-list` `binary-analysis` `ctf` `cybersecurity` `debugging` `decompiler` `disassembler` `dynamic-analysis` `firmware` `frida` `ghidra` `malware-analysis` `mcp` `reverse-engineering` `security` `security-tools` `static-analysis`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 9. [Ayzzz123/mcd-coupon-strategist](https://github.com/Ayzzz123/mcd-coupon-strategist) · 🟢 窗口内 · 66.6 分

> 麦麦省钱助手 —— 基于麦当劳 MCP 的点餐成本优化 Skill。算出当前门店最省钱的点餐方案，并主动提示凑单陷阱。

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 256 | +256 | +0 | 19 | 0 | Python | MIT | 10-10（2 天前） | 今天 |

- **近 14 天每天新增**：`··········█▇▇▁` 0 0 0 0 0 0 0 0 0 0 93 81 81 1
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent` `cost-optimization` `coupon` `llm` `mcd-mcp` `mcdonalds` `mcp` `python` `skill` `workbuddy`
- **主页**：<https://github.com/Ayzzz123/mcd-coupon-strategist/blob/main/MCP_INTEGRATION.md>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 10. [tobi/disktree](https://github.com/tobi/disktree) · 🟡 在降温 · 61.5 分

> A treemap for finding and removing what fills your disk, for Omarchy. Rust + GPUI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2876 | +470 | +481 | 178 | 47 | Rust | MIT | 09-24（18 天前） | 8 天前 |

- **近 14 天每天新增**：`▄▃▃▃▃▂▂▃▂▂▂█▃▁` 107 83 84 70 58 33 46 56 39 31 36 239 63 6
- **势头**：和前 7 天差不多
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=49841155)）
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) — 一天进了一半以上的 star，但 HN 上没火过
- [academa-labs/manimgx](https://github.com/academa-labs/manimgx) — 一天进了一半以上的 star，但 HN 上没火过
- [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) — 一天进了一半以上的 star，但 HN 上没火过
- [opengeos/RustGIS](https://github.com/opengeos/RustGIS) — 一天进了一半以上的 star，但 HN 上没火过
- [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 725 | 165 | [Show HN: Bigwords.page – Turn any screen into a sign. The URL is the app](https://bigwords.page/) | [HN](https://news.ycombinator.com/item?id=49994443) |
| 429 | 55 | [Show HN: Carrier-Explode: iPhone, Pixel and Galaxy carrier settings decoded](https://carrierexplode.com/) | [HN](https://news.ycombinator.com/item?id=50024499) |
| 417 | 196 | [Show HN: Let your AI agents paint big arrows, boxes and text on your screen](https://github.com/franzenzenhofer/big-arrow-on-the-screen) | [HN](https://news.ycombinator.com/item?id=50018817) |
| 291 | 156 | [Show HN: PS2 games statically recompiled to WebAssembly](https://github.com/snuri00/ps2-web-recomp) | [HN](https://news.ycombinator.com/item?id=50052251) |
| 285 | 124 | [Show HN: WallHop – 12ft.io is gone, so I built a replacement](https://wallhop.io/) | [HN](https://news.ycombinator.com/item?id=50038634) |
| 240 | 181 | [Show HN: Quake ported to safe Rust, playable in browser](https://quake-srp.pages.dev/) | [HN](https://news.ycombinator.com/item?id=50016312) |
| 222 | 37 | [Show HN: Making a flexible "neon" t-shirt with LED filaments](http://scottbezek.blogspot.com/2026/10/making-flexible-neon-t-shirt-with-leds.html) | [HN](https://news.ycombinator.com/item?id=50008047) |
| 209 | 126 | [Show HN: BetterWispr – Free, open-source dictation for Mac](https://betterwispr.com/) | [HN](https://news.ycombinator.com/item?id=50042333) |
| 186 | 66 | [Show HN: The rarest tech books and docs you've probably never read](https://readrare.com/) | [HN](https://news.ycombinator.com/item?id=50024055) |
| 174 | 68 | [Show HN: A walkable 3D art history museum built from Wikipedia](https://artmuseum.artfrompixels.com/) | [HN](https://news.ycombinator.com/item?id=49992057) |
| 122 | 45 | [Show HN: Proton Drive for Linux](https://oss.lsantos.dev/proton-drive-linux-fs/) | [HN](https://news.ycombinator.com/item?id=50003545) |
| 105 | 19 | [Show HN: Atticus – Hold-to-talk voice assistant for macOS that runs on Claude -p](https://github.com/SaarthurR/atticus-mac) | [HN](https://news.ycombinator.com/item?id=50049588) |
| 91 | 20 | [Show HN: Happy Hangul Day! An RNN for Generating Korean Handwriting Strokes](https://hangul.ink/blog/hangul-day) | [HN](https://news.ycombinator.com/item?id=50015833) |
| 88 | 25 | [Show HN: Parseable, an open observability datalake, handles 100M time-series/min](https://www.parseable.com) | [HN](https://news.ycombinator.com/item?id=49978171) |
| 86 | 39 | [Show HN: I turned my iPhone and a $20 smart plug into an f-stop timer](https://peterszentkiralyi.eu/darkplug/) | [HN](https://news.ycombinator.com/item?id=49978595) |
| 80 | 23 | [Show HN: Jevman – AI decision models play Pac-Man](https://opper.ai/jevman-benchmark/) | [HN](https://news.ycombinator.com/item?id=50007993) |
| 75 | 0 | [Show HN: MailAccess – the true Email OSINT framework](https://mailaccess.pro) | [HN](https://news.ycombinator.com/item?id=49977385) |
| 74 | 12 | [Show HN: Diffle, a keyboard-centric diff viewer with LSP support](https://github.com/moritzwilksch/diffle) | [HN](https://news.ycombinator.com/item?id=50006930) |
| 73 | 49 | [Show HN: Agent.reviews – Where AI agents read and write reviews on tools](https://agent.reviews/) | [HN](https://news.ycombinator.com/item?id=49995539) |
| 69 | 53 | [Show HN: K10s – A Clickable Kubernetes TUI (Go, Bubble Tea)](https://github.com/p10node/k10s) | [HN](https://news.ycombinator.com/item?id=50009904) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 32 | [RSI-Anything: Unlocking Recursive Self-Improvement with World Models](https://huggingface.co/papers/2610.13912) | Recursive self-improvement (RSI) aims to transform interaction experience into persistent improvements, yet external feedback is costly and… | 💡 [Gen-Verse/RSI-Anything](https://github.com/Gen-Verse/RSI-Anything) 446★ |
| 22 | [AutoDev: Automated AI-Driven Development](https://huggingface.co/papers/2403.08299) | AutoDev is an AI-driven software development framework that automates complex engineering tasks within a secure Docker environment, achievin… | [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi) 27432★ |
| 26 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Mixture-of-experts (MoE) inference on consumer hardware is bounded by weight memory: a 35B-class model is 19.5GB at 4-bit, and sparsity shri… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 4617★ |
| 13 | [PyTorch Distributed: Experiences on Accelerating Data Parallel Training](https://huggingface.co/papers/2006.15704) | The PyTorch distributed data parallel module optimizes large-scale model training using techniques like gradient bucketing, computation-comm… | [pytorch/pytorch](https://github.com/pytorch/pytorch) 104736★ |
| 234 | [YuE2: Unifying Symbolic and Audio Music Generation at Frontier Quality](https://huggingface.co/papers/2609.33757) | Symbolic models make melody, harmony, rhythm, and form explicit but typically stop before a finished recording; audio models produce complet… | [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE) 11841★ |
| 112 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | 💡 [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 967★ |
| 151 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 110884★ |
| 238 | [DiffusionART: Efficient, Stable and Scalable Reinforcement of Diffusion Models](https://huggingface.co/papers/2610.12572) | Online reinforcement learning (RL) fine-tunes diffusion models with black-box rewards, but reverse-process methods such as Flow-GRPO are lim… | 💡 [vanzll/DiffusionART](https://github.com/vanzll/DiffusionART) 89★ |
| 34 | [HuggingFace's Transformers: State-of-the-art Natural Language Processing](https://huggingface.co/papers/1910.03771) | Transformers library provides state-of-the-art Transformer architectures and pretrained models for natural language processing tasks with a… | [huggingface/transformers](https://github.com/huggingface/transformers) 167618★ |
| 18 | [Bitnet.cpp: Efficient Edge Inference for Ternary LLMs](https://huggingface.co/papers/2502.11880) | Bitnet.cpp enhances edge inference for ternary LLMs using a novel mixed-precision matrix multiplication library, achieving significant speed… | [microsoft/BitNet](https://github.com/microsoft/BitNet) 40880★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 90779★ |
| 39 | [Geometric Context Transformer for Streaming 3D Reconstruction](https://huggingface.co/papers/2604.14141) | LingBot-Map is a feed-forward 3D foundation model that reconstructs scenes from video streams using a geometric context transformer architec… | [robbyant/lingbot-map](https://github.com/robbyant/lingbot-map) 18036★ |
| 91 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 27124★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 59 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 40616★ |
| 8 | [Native and Compact Structured Latents for 3D Generation](https://huggingface.co/papers/2512.14692) | A new sparse voxel representation called O-Voxel enables high-quality 3D generative modeling with efficient inference and robust topology ha… | [microsoft/TRELLIS.2](https://github.com/microsoft/TRELLIS.2) 11910★ |
| 180 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 81562★ |
| 18 | [Towards Physically Grounded Articulated 3D Assets: A Multi-Agent Pipeline and Benchmark](https://huggingface.co/papers/2610.13947) | In this paper, we study physically grounded articulated 3D asset generation---moving the goal from reproducing how objects look to capturing… | 💡 [physicalvision/Artisan](https://github.com/physicalvision/Artisan) 62★ |
| 57 | [Prime Agent: A Self-Improving RLM Harness](https://huggingface.co/papers/2608.23552) | Prime Agent is an open-source harness that uses recursive subagents, persistent computation, and agent-to-agent coordination to extend langu… | [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) 21961★ |
| 47 | [A decoder-only foundation model for time-series forecasting](https://huggingface.co/papers/2310.10688) | A large language model adapted for time-series forecasting achieves near-optimal zero-shot performance on diverse datasets across different… | [google-research/timesfm](https://github.com/google-research/timesfm) 34383★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

_这次没有（第一次，只记下榜单）。_

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 54 | 20 | [Living in the Weimar era of Ruby](https://blog.julik.nl/2026/10/the-weimar-of-ruby) | `ruby` `vibecoding` | [讨论](https://lobste.rs/s/lfen2h/living_weimar_era_ruby) |
| 20 | 3 | [Who is vfmaddrnd231pd??](https://purplesyringa.moe/blog/who-is-vfmaddrnd231pd/) | `assembly` | [讨论](https://lobste.rs/s/2h9opx/who_is_vfmaddrnd231pd) |
| 30 | 1 | [Vi Hart's Big Navier-Stokes Post](https://www.patreon.com/vihart/posts/vi-harts-big-171939430) | `ai` `math` | [讨论](https://lobste.rs/s/j30pg4/vi_hart_s_big_navier_stokes_post) |
| 53 | 85 | [Linus Torvalds Working On A Hefty Linux Kernel Improvement With Claude Code](https://www.phoronix.com/news/Linus-Torvalds-Claude-Code) | `linux` `vibecoding` | [讨论](https://lobste.rs/s/iq5xtw/linus_torvalds_working_on_hefty_linux) |
| 61 | 3 | [(Post-Quantum) Cryptographic Right Answers](https://words.filippo.io/right-answers/) | `cryptography` | [讨论](https://lobste.rs/s/sozl9e/post_quantum_cryptographic_right) |
| 10 | 0 | [A slightly faster slimmer curl](https://daniel.haxx.se/blog/2026/10/13/a-slightly-faster-slimmer-curl/) | `performance` | [讨论](https://lobste.rs/s/d9rpcl/slightly_faster_slimmer_curl) |
| 29 | 3 | [Speeding up the Unreal editor by… not using unnecessarily secure hash methods](https://larstofus.com/2026/10/11/speeding-up-the-unreal-editor-by-not-using-unnecessarily-secure-hash-methods/) | `performance` | [讨论](https://lobste.rs/s/5feguu/speeding_up_unreal_editor_by_not_using) |
| 43 | 1 | [Finding a $90,000 Remote Code Execution Vulnerability in Google](https://simonkoeck.com/writeups/google-devsite-flask-session-pickle-rce) | `security` | [讨论](https://lobste.rs/s/mldt0o/finding_90_000_remote_code_execution) |
| 92 | 35 | ['AI' is Not a Tool](https://www.linkedin.com/pulse/ai-tool-rich-hickey-kjl8e) | `vibecoding` | [讨论](https://lobste.rs/s/ikk8ie/ai_is_not_tool) |
| 28 | 20 | [French supermarket chains say cyberattack forced refrigerator shutdown](https://www.afp.com/en/french-supermarket-chains-say-cyberattack-forced-refrigerator-shutdown) | `security` | [讨论](https://lobste.rs/s/u4vlin/french_supermarket_chains_say) |
| 3 | 0 | [Creusot 0.14.0 release - Contracts for Rust, formally proved](https://devlog.creusot.rs/v0-14-0/) | `formalmethods` `rust` | [讨论](https://lobste.rs/s/6tbd2o/creusot_0_14_0_release_contracts_for_rust) |
| 16 | 20 | [What are you doing this week?](https://lobste.rs/s/7vzgsl) | `ask` `programming` | [讨论](https://lobste.rs/s/7vzgsl/what_are_you_doing_this_week) |
| 33 | 20 | [Fingerprints are the new cookies](https://royfish.dev/fingerprints-are-the-new-cookies) | `privacy` | [讨论](https://lobste.rs/s/ml9xrb/fingerprints_are_new_cookies) |
| 2 | 2 | [Where is all the new, good software?](https://www.natemeyvis.com/where-is-all-the-new-good-software/) | `practices` `vibecoding` | [讨论](https://lobste.rs/s/hjhufj/where_is_all_new_good_software) |
| 21 | 2 | [your c is not standard c](https://sebsite.pw/w/20261012-notstdc.html) | `c` | [讨论](https://lobste.rs/s/0aocct/your_c_is_not_standard_c) |
| 14 | 10 | [Parsing JSON at tens of gigabytes per second… in Python](https://lemire.me/blog/2026/10/12/parsing-json-at-tens-of-gigabytes-per-second-in-python/) | `python` | [讨论](https://lobste.rs/s/iufma5/parsing_json_at_tens_gigabytes_per_second) |
| 12 | 7 | [What I've been seeing lately (in software)](https://mei.puppycat.house/w/seeing-261010) | `culture` `vibecoding` | [讨论](https://lobste.rs/s/awjqvn/what_i_ve_been_seeing_lately_software) |
| 29 | 0 | [Writing a Demoscene Intro for the ZX Spectrum](https://www.markround.com/blog/2026/zx-spectrum-intro) | `retrocomputing` | [讨论](https://lobste.rs/s/nroajo/writing_demoscene_intro_for_zx_spectrum) |
| 1 | 0 | [Chasing a -O2 pessimization in antcc](https://386s.org/w/lua-antcc-pessimization/) | `c` `compilers` | [讨论](https://lobste.rs/s/g2ktrq/chasing_o2_pessimization_antcc) |
| 3 | 0 | [Freeze the Controller, Defrost the Food: Uncovering Vulnerabilities in Danfoss Refrigeration Control…](https://claroty.com/team82/research/freeze-the-controller-defrost-the-food-uncovering-vulnerabilities-in-danfoss-refrigeration-controllers) | `security` | [讨论](https://lobste.rs/s/nsmm3j/freeze_controller_defrost_food) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

_还没有到 14 天的，22 个在等。_

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
