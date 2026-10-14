# early-radar 选题雷达 · 2026-10-14

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 112 个，细查前 20 个 · 比上次 = 和 2026-10-13 那次比 · 生成于 2026-10-14 04:31 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 2 个 · Show HN ✅ 30 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 0 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 7 个 · 🟡 在降温 4 个 · 🔵 已被发现 3 个 · 💤 不活跃 0 个 · 🔴 先核对 6 个
- **今天新出现 0 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [storytold/photocraft](https://github.com/storytold/photocraft) 平均每天 +4293，见 [爆发](#爆发)
- **最值得今天试的**：
  - [ARahim3/DigUp](https://github.com/ARahim3/DigUp) — Search your Mac by what's in your files: photos, PDFs, recor…（近 7 天 +2623，刚发布一周内）
  - [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) — Your company's data, connected into one ontology, on your ow…（近 7 天 +1408，刚发布一周内）
  - [academa-labs/manimgx](https://github.com/academa-labs/manimgx) — The animation engine for agents: blazingly fast math and 3D…（近 7 天 +1136，比前 7 天快 162.3 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 24 个（star 合计 21476），代表：[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill)、[Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：2 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Bigwords.page – Turn any screen into a sign. The URL is the app](https://bigwords.page/) — 727 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| ✅ [storytold/photocraft](https://github.com/storytold/photocraft) | 58475 | 4293 | +2220 | 13.6 | [140](https://news.ycombinator.com/item?id=49981449) | photocraft · storytold photocraft · artcraft photocraft | PhotoCraft: An open-source, photo editor written by scratch… |
| [openai/math](https://github.com/openai/math) | 14705 | 2020 | +119 | 7.3 | [342](https://news.ycombinator.com/item?id=50003107) | math · openai math |  |
| ✅ [storytold/wordcraft](https://github.com/storytold/wordcraft) | 11334 | 1659 | +976 | 6.8 | [101](https://news.ycombinator.com/item?id=50050370) | wordcraft · storytold wordcraft · artcraft wordcraft | An open-source, clean-room reimplementation of Microsoft Wor… |
| [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) | 8503 | 1475 | +920 | 5.8 | — | anatomy · wheresryan22 anatomy · ryan anatomy | An agent skill for creating detailed, interactive isometric… |
| ✅ [storytold/pdfcraft](https://github.com/storytold/pdfcraft) | 12932 | 950 | +706 | 13.6 | — | pdfcraft · storytold pdfcraft · artcraft pdfcraft | PdfCraft: An open-source PDF reader and editor written by sc… |
| ✅ [storytold/filmcraft](https://github.com/storytold/filmcraft) | 12685 | 931 | +557 | 13.6 | [3](https://news.ycombinator.com/item?id=50069000) | filmcraft · storytold filmcraft · artcraft filmcraft | FilmCraft: An open-source, nonlinear video editor written by… |
| 🆕 [Arekejoker/qwen21-nsfw-pose-skill](https://github.com/Arekejoker/qwen21-nsfw-pose-skill) | 950 | 899 | +414 | 1.1 | — | qwen21 nsfw pose skill · arekejoker qwen21 nsfw pose skill | Qwen-Image 2.1 NSFW/姿势出图 skill：作者级提示词配方 + NSFW LoRA + 136 姿势… |
| ✅ [storytold/lightcraft](https://github.com/storytold/lightcraft) | 12095 | 889 | +382 | 13.6 | — | lightcraft · storytold lightcraft · artcraft lightcraft | LightCraft: An open-source non-destructive photo editor writ… |
| [liseami/CCBaga](https://github.com/liseami/CCBaga) | 2101 | 693 | +114 | 3 | — | ccbaga · liseami ccbaga · purefantasyzhao ccbaga |  |
| [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) | 1656 | 693 | +373 | 2.4 | — | esp32 iphone agent · onehumanbeing esp32 iphone agent · henry esp32 iphone agent | Let an AI model use a real iPhone with a $7 ESP32: AirPlay e… |
| [jhaizhou-ops/d2r-mobile](https://github.com/jhaizhou-ops/d2r-mobile) | 1237 | 677 | +216 | 1.8 | — | d2r mobile · jhaizhou-ops d2r mobile | Open-source iOS / macOS compatibility layer for Diablo II: R… |
| [mhtsec/ARTEX](https://github.com/mhtsec/ARTEX) | 3926 | 659 | +94 | 6 | — | artex · mhtsec artex · mht artex | AI 自主渗透测试系统 / 百度“agent+”攻防挑战赛冠军项目 |
| ✅ [storytold/gridcraft](https://github.com/storytold/gridcraft) | 4513 | 648 | +287 | 7 | — | gridcraft · storytold gridcraft · artcraft gridcraft | GridCraft: an open-source, clean-room spreadsheet (Microsoft… |
| ✅ [storytold/vectorcraft](https://github.com/storytold/vectorcraft) | 8563 | 629 | +333 | 13.6 | — | vectorcraft · storytold vectorcraft · artcraft vectorcraft | VectorCraft: An open-source, vector art tool written by scra… |
| ✅ [storytold/cadcraft](https://github.com/storytold/cadcraft) | 4306 | 618 | +383 | 7 | — | cadcraft · storytold cadcraft · artcraft cadcraft | CADCraft: computer-aided design and drafting — an open-sourc… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 94.5 | 🟢 窗口内 | [ARahim3/DigUp](https://github.com/ARahim3/DigUp) | Swift | 2623 | +492 | +2623 | +0 | `········▁▃█▆▅·` | 5 | [4](https://news.ycombinator.com/item?id=50045015) | — |
| 2 | 93.3 | ✅ 🟢 窗口内 | [storytold/soundcraft](https://github.com/storytold/soundcraft) | Rust | 2618 | +187 | +2378 | +240 | `······▄▆▇▆█▆▅·` | 6 | — | — |
| 3 | 88 | ✅ 🟢 窗口内 | [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) | Python | 2443 | +157 | +1527 | +916 | `··▆▆▅▅▆▇███▇▇·` | 10 | — | — |
| 4 | 87 | 🟢 窗口内 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) | TypeScript | 1408 | +34 | +1408 | +0 | `·······▃█▇▄▂▂·` | 6 | — | — |
| 5 | 84.4 | 🟢 窗口内 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | Python | 1143 | +67 | +1136 | +7 | `······▁▁▁▂█▆▂·` | 8 | [10](https://news.ycombinator.com/item?id=50037852) | — |
| 6 | 73 | 🟢 窗口内 | [tobi/disktree](https://github.com/tobi/disktree) | Rust | 2901 | +20 | +439 | +430 | `▃▃▃▃▂▂▃▂▂▂█▃▂·` | 19 | [3](https://news.ycombinator.com/item?id=49841155) | — |
| 7 | 72.9 | 🟢 窗口内 | [morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering) | — | 435 | +63 | +435 | +0 | `········▂▂▅█▅·` | 4 | — | — |
| 8 | 60.2 | 🟡 在降温 | [feitangyuan/onetake](https://github.com/feitangyuan/onetake) | Python | 2312 | +45 | +411 | +826 | `▅█▄▄▆▆▅▄▄▃▃▄▄·` | 17 | — | — |
| 9 | 60.2 | 🟡 在降温 | [oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) | Python | 1446 | +26 | +411 | +969 | `▂▂▇▅▄█▄▃▃▂▃▄▂·` | 14 | — | — |
| 10 | 55.3 | 🟡 在降温 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep) | TypeScript | 2673 | +15 | +252 | +504 | `▇▅█▅▄▃▅▅▄▃▅▃▃·` | 18 | [5](https://news.ycombinator.com/item?id=49880146) | — |
| 11 | 53.9 | 🟡 在降温 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) | Python | 1952 | +13 | +219 | +1110 | `█▄▃▃▃▃▂▂▂▁▂▂▁·` | 13 | — | — |
| 12 | 45.3 | 🔵 已被发现 | [bherbruck/solidcraft](https://github.com/bherbruck/solidcraft) | Rust | 1886 | +374 | +1886 | +0 | `········▁▂▇▆█·` | 6 | [133](https://news.ycombinator.com/item?id=50064840) | — |
| 13 | 44.5 | 🔴 先核对 | [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) | Python | 1656 | +373 | +1656 | +0 | `··········▁█▆·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 14 | 41.2 | 🔵 已被发现 | [rociiu/talorys](https://github.com/rociiu/talorys) | TypeScript | 965 | +35 | +965 | +0 | `·········█▅▃▂·` | 3 | [329](https://news.ycombinator.com/item?id=50031614) | — |
| 15 | 40.7 | 🔴 先核对 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 886 | +71 | +886 | +0 | `···········█▃·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 16 | 40.4 | 🔴 先核对 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 835 | +242 | +835 | +0 | `··········▁▇█·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 38.8 | 🔵 已被发现 | [pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust) | Rust | 1171 | +26 | +640 | +531 | `······█▄▂▃▂▂▂·` | 6 | [118](https://news.ycombinator.com/item?id=50000676) | — |
| 18 | 36.7 | ✅ 🔴 先核对 | [storytold/figcraft](https://github.com/storytold/figcraft) | Rust | 449 | — | +449 | +0 | `········▁··▁█·` | 4 | [3](https://news.ycombinator.com/item?id=50069000) | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 24.2 | 🔴 先核对 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) | Python | 2767 | +2 | +125 | +688 | `█▄▁▁▁▁▁▂▁▂▁▁▁·` | 14 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 21.3 | 🔴 先核对 | [trhhubsd/ARTEXX](https://github.com/trhhubsd/ARTEXX) | Go | 1207 | +362 | +1207 | +0 | `·······▁▁▁▁█▆·` | 5 | — | 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1% |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 504 | 30 | 42190 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) |
| `mcp` | 161 | 30 | 17472 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[bherbruck/solidcraft](https://github.com/bherbruck/solidcraft)、[leemysw/yovoice](https://github.com/leemysw/yovoice) |
| `rust` | 126 | 30 | 21753 | [tobi/disktree](https://github.com/tobi/disktree)、[storytold/soundcraft](https://github.com/storytold/soundcraft)、[bherbruck/solidcraft](https://github.com/bherbruck/solidcraft) |
| `local-first` | 63 | 30 | 14466 | [ARahim3/DigUp](https://github.com/ARahim3/DigUp)、[RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 24 | 21476 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill)、[Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth) |
| `ai-agents` | 21 | 11231 | [Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[krishhgg/Insomnia](https://github.com/krishhgg/Insomnia)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui) |
| `codex` | 20 | 17212 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) |
| `macos` | 17 | 12816 | [ARahim3/DigUp](https://github.com/ARahim3/DigUp)、[freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[leemysw/yovoice](https://github.com/leemysw/yovoice) |
| `llm` | 16 | 9601 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `agent-skills` | 14 | 14674 | [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill)、[Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) |
| `developer-tools` | 10 | 7446 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill) |
| `jev` | 10 | 7188 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[ollaya-dev/ollaya](https://github.com/ollaya-dev/ollaya)、[jev-chat/jev-chat-windows](https://github.com/jev-chat/jev-chat-windows) |
| `windows` | 10 | 6236 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[leemysw/yovoice](https://github.com/leemysw/yovoice)、[jev-chat/jev-chat-windows](https://github.com/jev-chat/jev-chat-windows) |
| `ai-agent` | 9 | 6331 | [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent)、[freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `python` | 9 | 5356 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[jev-chat/jev-chat-windows](https://github.com/jev-chat/jev-chat-windows)、[yakuikai/tokentab](https://github.com/yakuikai/tokentab) |
| `linux` | 8 | 5865 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[amontlabs/lcu](https://github.com/amontlabs/lcu) |

**语言分布**：Python 36 · Rust 28 · TypeScript 21 · JavaScript 7 · Swift 7 · Go 5 · C++ 1 · Java 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [ARahim3/DigUp](https://github.com/ARahim3/DigUp) · 🟢 窗口内 · 94.5 分

> Search your Mac by what's in your files: photos, PDFs, recordings, videos and code. On-device, built on Google DeepMind's EmbeddingGemma 2.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2623 | +2623 | +0 | 188 | 54 | Swift | MIT | 10-08（5 天前） | 1 天前 |

- **近 14 天每天新增**：`········▁▃█▆▅·` 0 0 0 0 0 0 0 0 1 308 1034 667 613 0
- **势头**：刚发布一周内
- **HN**：发过 2 次，最高 4 分（[讨论](https://news.ycombinator.com/item?id=50045015)）
- **topics**：`embeddinggemma` `embeddings` `llama-cpp` `local-first` `macos` `menubar-app` `multimodal` `on-device` `semantic-search` `swift`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. ✅ [storytold/soundcraft](https://github.com/storytold/soundcraft) · 🟢 窗口内 · 93.3 分

> An open-source, clean-room reimplementation of Avid Pro Tools in pure Rust

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2618 | +2378 | +240 | 1617 | 238 | Rust | Apache-2.0 | 10-07（6 天前） | 今天 |

- **近 14 天每天新增**：`······▄▆▇▆█▆▅·` 0 0 0 0 0 0 240 400 411 351 521 402 293 0
- **势头**：比前 7 天快 9.9 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://getartcraft.com/apps/soundcraft>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. ✅ [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) · 🟢 窗口内 · 88 分

> Eleven free Claude skills that clone any app: reverse-engineer it, rebuild it, test it for bugs, then fix what its users hate. Free, MIT.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2443 | +1527 | +916 | 360 | 6 | Python | MIT | 10-03（10 天前） | 10 天前 |

- **近 14 天每天新增**：`··▆▆▅▅▆▇███▇▇·` 0 0 187 217 156 168 188 229 278 267 270 254 229 0
- **势头**：比前 7 天快 1.7 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent` `agent-skills` `app-clone` `claude` `claude-code` `claude-skills` `indie-hacker` `reverse-engineering` `saas`
- **主页**：<https://opusjake.ai>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) · 🟢 窗口内 · 87 分

> Your company's data, connected into one ontology, on your own computer. A local-first data workspace built on HelixDB and DuckDB.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1408 | +1408 | +0 | 217 | 9 | TypeScript | Apache-2.0 | 10-07（6 天前） | 今天 |

- **近 14 天每天新增**：`·······▃█▇▄▂▂·` 0 0 0 0 0 0 0 137 504 427 180 99 61 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [academa-labs/manimgx](https://github.com/academa-labs/manimgx) · 🟢 窗口内 · 84.4 分

> The animation engine for agents: blazingly fast math and 3D videos with Manim's Python API, on a Rust GPU core.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1143 | +1136 | +7 | 74 | 0 | Python | MIT | 10-05（8 天前） | 1 天前 |

- **近 14 天每天新增**：`······▁▁▁▂█▆▂·` 0 0 0 0 0 0 7 31 11 41 568 370 115 0
- **势头**：比前 7 天快 162.3 倍，在加速
- **HN**：发过 1 次，最高 10 分（[讨论](https://news.ycombinator.com/item?id=50037852)）
- **主页**：<https://manimgx.academa.ai>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [tobi/disktree](https://github.com/tobi/disktree) · 🟢 窗口内 · 73 分

> A treemap for finding and removing what fills your disk, for Omarchy. Rust + GPUI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2901 | +439 | +430 | 178 | 47 | Rust | MIT | 09-24（19 天前） | 9 天前 |

- **近 14 天每天新增**：`▃▃▃▃▂▂▃▂▂▂█▃▂·` 83 84 70 58 33 46 56 39 31 36 239 63 31 0
- **势头**：和前 7 天差不多
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=49841155)）
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering) · 🟢 窗口内 · 72.9 分

> Curated reverse-engineering tools and learning resources for binaries, apps, firmware, formats, and protocols.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 435 | +435 | +0 | 90 | 1 | — | CC0-1.0 | 10-09（4 天前） | 今天 |

- **近 14 天每天新增**：`········▂▂▅█▅·` 0 0 0 0 0 0 0 0 29 36 100 170 100 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-agents` `awesome` `awesome-list` `binary-analysis` `ctf` `cybersecurity` `debugging` `decompiler` `disassembler` `dynamic-analysis` `firmware` `frida` `ghidra` `malware-analysis` `mcp` `reverse-engineering` `security` `security-tools` `static-analysis`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [feitangyuan/onetake](https://github.com/feitangyuan/onetake) · 🟡 在降温 · 60.2 分

> Motion films that never cut to the next slide: every beat grows out of the one before, one continuous camera, continuity measured by an oracle. Product launch films and feature demos, made with a coding agent.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2312 | +411 | +826 | 148 | 3 | Python | — | 09-26（17 天前） | 1 天前 |

- **近 14 天每天新增**：`▅█▄▄▆▆▅▄▄▃▃▄▄·` 98 187 92 85 123 122 119 77 69 57 50 86 72 0
- **势头**：只有前 7 天的 50%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `animation` `canvas` `claude-skill` `launch-video` `motion-graphics` `video`
- **主页**：<https://onetakemotion.com>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) · 🟡 在降温 · 60.2 分

> UI design skill for Claude Code, Codex and other AI agents: explore distinct directions, compare them side by side, refine against real screenshots. 给 AI Agent 用的 UI 设计 Skill。

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1446 | +411 | +969 | 79 | 0 | Python | MIT | 09-30（14 天前） | 今天 |

- **近 14 天每天新增**：`▂▂▇▅▄█▄▃▃▂▃▄▂·` 23 48 232 161 117 267 121 63 68 54 71 110 45 0
- **势头**：只有前 7 天的 42%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-design` `claude-code` `claude-skills` `codex` `frontend` `ui-design` `ux-design`
- **主页**：<https://ui.oiloil.org>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [dzhng/jevgrep](https://github.com/dzhng/jevgrep) · 🟡 在降温 · 55.3 分

> Find code by asking what it does. A CLI for coding agents that uses Jev to discover relevant files and source context.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2673 | +252 | +504 | 197 | 29 | TypeScript | MIT | 09-26（18 天前） | 今天 |

- **近 14 天每天新增**：`▇▅█▅▄▃▅▅▄▃▅▃▃·` 96 65 116 70 53 35 69 59 45 29 58 31 30 0
- **势头**：只有前 7 天的 50%，在减速
- **HN**：发过 1 次，最高 5 分（[讨论](https://news.ycombinator.com/item?id=49880146)）
- **topics**：`ai-sdk` `claude-code` `cli` `code-search` `codex` `coding-agents` `context-retrieval` `developer-tools` `jev` `semantic-search` `typescript` `vercel-ai-gateway`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) — 一天进了一半以上的 star，但 HN 上没火过
- [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) — 一天进了一半以上的 star，但 HN 上没火过
- [opengeos/RustGIS](https://github.com/opengeos/RustGIS) — 一天进了一半以上的 star，但 HN 上没火过
- [storytold/figcraft](https://github.com/storytold/figcraft) — 一天进了一半以上的 star，但 HN 上没火过
- [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) — 一天进了一半以上的 star，但 HN 上没火过
- [trhhubsd/ARTEXX](https://github.com/trhhubsd/ARTEXX) — 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1%

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 727 | 165 | [Show HN: Bigwords.page – Turn any screen into a sign. The URL is the app](https://bigwords.page/) | [HN](https://news.ycombinator.com/item?id=49994443) |
| 431 | 55 | [Show HN: Carrier-Explode: iPhone, Pixel and Galaxy carrier settings decoded](https://carrierexplode.com/) | [HN](https://news.ycombinator.com/item?id=50024499) |
| 419 | 196 | [Show HN: Let your AI agents paint big arrows, boxes and text on your screen](https://github.com/franzenzenhofer/big-arrow-on-the-screen) | [HN](https://news.ycombinator.com/item?id=50018817) |
| 346 | 96 | [Show HN: Guitoro, a virtual guitar you strum with your keyboard](https://guitoro.com/) | [HN](https://news.ycombinator.com/item?id=50077020) |
| 306 | 158 | [Show HN: PS2 games statically recompiled to WebAssembly](https://github.com/snuri00/ps2-web-recomp) | [HN](https://news.ycombinator.com/item?id=50052251) |
| 286 | 125 | [Show HN: WallHop – 12ft.io is gone, so I built a replacement](https://wallhop.io/) | [HN](https://news.ycombinator.com/item?id=50038634) |
| 241 | 181 | [Show HN: Quake ported to safe Rust, playable in browser](https://quake-srp.pages.dev/) | [HN](https://news.ycombinator.com/item?id=50016312) |
| 222 | 37 | [Show HN: Making a flexible "neon" t-shirt with LED filaments](http://scottbezek.blogspot.com/2026/10/making-flexible-neon-t-shirt-with-leds.html) | [HN](https://news.ycombinator.com/item?id=50008047) |
| 214 | 126 | [Show HN: BetterWispr – Free, open-source dictation for Mac](https://betterwispr.com/) | [HN](https://news.ycombinator.com/item?id=50042333) |
| 189 | 66 | [Show HN: The rarest tech books and docs you've probably never read](https://readrare.com/) | [HN](https://news.ycombinator.com/item?id=50024055) |
| 174 | 68 | [Show HN: A walkable 3D art history museum built from Wikipedia](https://artmuseum.artfrompixels.com/) | [HN](https://news.ycombinator.com/item?id=49992057) |
| 160 | 81 | [Show HN: Use your OpenAI subscription to create audiobooks](https://pdftomp3.com/connect-ai/) | [HN](https://news.ycombinator.com/item?id=50069337) |
| 133 | 45 | [Show HN: SolidCraft – Open-Source Parametric CAD in Rust (With MCP Support)](https://github.com/bherbruck/solidcraft) | [HN](https://news.ycombinator.com/item?id=50064840) |
| 122 | 45 | [Show HN: Proton Drive for Linux](https://oss.lsantos.dev/proton-drive-linux-fs/) | [HN](https://news.ycombinator.com/item?id=50003545) |
| 114 | 28 | [Show HN: Atticus – Hold-to-talk voice assistant for macOS that runs on Claude -p](https://github.com/SaarthurR/atticus-mac) | [HN](https://news.ycombinator.com/item?id=50049588) |
| 99 | 58 | [Show HN: How random are you?](https://lab.specr.net/rigged-draw/) | [HN](https://news.ycombinator.com/item?id=50074909) |
| 92 | 20 | [Show HN: Happy Hangul Day! An RNN for Generating Korean Handwriting Strokes](https://hangul.ink/blog/hangul-day) | [HN](https://news.ycombinator.com/item?id=50015833) |
| 83 | 39 | [Show HN: An experimental pattern-first DAW that supports MCP](https://github.com/andrewfader/blokkily) | [HN](https://news.ycombinator.com/item?id=50064438) |
| 81 | 23 | [Show HN: Jevman – AI decision models play Pac-Man](https://opper.ai/jevman-benchmark/) | [HN](https://news.ycombinator.com/item?id=50007993) |
| 80 | 47 | [Show HN: Pulse Local, a Mac budgeting app whose AI models run on your machine](https://pulseos.finance) | [HN](https://news.ycombinator.com/item?id=50080275) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 23 | [AutoDev: Automated AI-Driven Development](https://huggingface.co/papers/2403.08299) | AutoDev is an AI-driven software development framework that automates complex engineering tasks within a secure Docker environment, achievin… | [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi) 28056★ |
| 33 | [RSI-Anything: Unlocking Recursive Self-Improvement with World Models](https://huggingface.co/papers/2610.13912) | Recursive self-improvement (RSI) aims to transform interaction experience into persistent improvements, yet external feedback is costly and… | 💡 [Gen-Verse/RSI-Anything](https://github.com/Gen-Verse/RSI-Anything) 632★ |
| 13 | [PyTorch Distributed: Experiences on Accelerating Data Parallel Training](https://huggingface.co/papers/2006.15704) | The PyTorch distributed data parallel module optimizes large-scale model training using techniques like gradient bucketing, computation-comm… | [pytorch/pytorch](https://github.com/pytorch/pytorch) 104851★ |
| 151 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 110998★ |
| 234 | [YuE2: Unifying Symbolic and Audio Music Generation at Frontier Quality](https://huggingface.co/papers/2609.33757) | Symbolic models make melody, harmony, rhythm, and form explicit but typically stop before a finished recording; audio models produce complet… | [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE) 11887★ |
| 18 | [Bitnet.cpp: Efficient Edge Inference for Ternary LLMs](https://huggingface.co/papers/2502.11880) | Bitnet.cpp enhances edge inference for ternary LLMs using a novel mixed-precision matrix multiplication library, achieving significant speed… | [microsoft/BitNet](https://github.com/microsoft/BitNet) 41124★ |
| 27 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Mixture-of-experts (MoE) inference on consumer hardware is bounded by weight memory: a 35B-class model is 19.5GB at 4-bit, and sparsity shri… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 4646★ |
| 113 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 1082★ |
| 34 | [HuggingFace's Transformers: State-of-the-art Natural Language Processing](https://huggingface.co/papers/1910.03771) | Transformers library provides state-of-the-art Transformer architectures and pretrained models for natural language processing tasks with a… | [huggingface/transformers](https://github.com/huggingface/transformers) 167690★ |
| 92 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 27311★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 90823★ |
| 245 | [DiffusionART: Efficient, Stable and Scalable Reinforcement of Diffusion Models](https://huggingface.co/papers/2610.12572) | Online reinforcement learning (RL) fine-tunes diffusion models with black-box rewards, but reverse-process methods such as Flow-GRPO are lim… | 💡 [vanzll/DiffusionART](https://github.com/vanzll/DiffusionART) 110★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 39 | [Geometric Context Transformer for Streaming 3D Reconstruction](https://huggingface.co/papers/2604.14141) | LingBot-Map is a feed-forward 3D foundation model that reconstructs scenes from video streams using a geometric context transformer architec… | [robbyant/lingbot-map](https://github.com/robbyant/lingbot-map) 18072★ |
| 59 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 40693★ |
| 180 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 81661★ |
| 47 | [A decoder-only foundation model for time-series forecasting](https://huggingface.co/papers/2310.10688) | A large language model adapted for time-series forecasting achieves near-optimal zero-shot performance on diverse datasets across different… | [google-research/timesfm](https://github.com/google-research/timesfm) 34454★ |
| 8 | [Native and Compact Structured Latents for 3D Generation](https://huggingface.co/papers/2512.14692) | A new sparse voxel representation called O-Voxel enables high-quality 3D generative modeling with efficient inference and robust topology ha… | [microsoft/TRELLIS.2](https://github.com/microsoft/TRELLIS.2) 11959★ |
| 74 | [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://huggingface.co/papers/2504.19413) | Mem0, a memory-centric architecture with graph-based memory, enhances long-term conversational coherence in LLMs by efficiently extracting,… | [mem0ai/mem0](https://github.com/mem0ai/mem0) 67137★ |
| 47 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 33180★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 21 | [lfm2.5](https://huggingface.co/LiquidAI/LFM2.5-24B-A2B) | text-generation | 193 | 1 |
| 39 | [drama 3](https://huggingface.co/fishaudio/drama-3) | text-to-speech | 133 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 72 | 28 | [A plea not to use uv-build](https://blogs.gentoo.org/mgorny/2026/10/12/a-plea-not-to-use-uv-build/) | `devops` `python` | [讨论](https://lobste.rs/s/73ssw1/plea_not_use_uv_build) |
| 69 | 7 | [Did Ente Locker copy my code without attribution?](https://fairscan.org/blog/did-ente-locker-copy-my-code-without-attribution/) | `law` | [讨论](https://lobste.rs/s/uiulqe/did_ente_locker_copy_my_code_without) |
| 75 | 14 | [Who is vfmaddrnd231pd??](https://purplesyringa.moe/blog/who-is-vfmaddrnd231pd/) | `assembly` | [讨论](https://lobste.rs/s/2h9opx/who_is_vfmaddrnd231pd) |
| 44 | 7 | [The reverts will continue until morale improves](http://peter.eisentraut.org/blog/2026/10/09/the-reverts-will-continue-until-morale-improves) | `databases` | [讨论](https://lobste.rs/s/aasanp/reverts_will_continue_until_morale) |
| 38 | 57 | [Where is all the new, good software?](https://www.natemeyvis.com/where-is-all-the-new-good-software/) | `practices` `vibecoding` | [讨论](https://lobste.rs/s/hjhufj/where_is_all_new_good_software) |
| 13 | 3 | [Redesigning source control at Anthropic](https://www.anthropic.com/engineering/redesigning-source-control) | `vcs` `vibecoding` | [讨论](https://lobste.rs/s/5ucftp/redesigning_source_control_at_anthropic) |
| 14 | 2 | [Announcing Lix 2.96 “Bingsu”](https://lix.systems/blog/2026-10-13-lix-2.96-release/) | `nix` `release` | [讨论](https://lobste.rs/s/y65egs/announcing_lix_2_96_bingsu) |
| 95 | 3 | [Vi Hart's Big Navier-Stokes Post](https://www.patreon.com/vihart/posts/vi-harts-big-171939430) | `math` `vibecoding` | [讨论](https://lobste.rs/s/j30pg4/vi_hart_s_big_navier_stokes_post) |
| 19 | 16 | [Lotus Improv on the NeXT](https://stonetools.ghost.io/lotusimprov-next/) | `historical` | [讨论](https://lobste.rs/s/zmuawx/lotus_improv_on_next) |
| 16 | 6 | [Creusot 0.14.0 release - Contracts for Rust, formally proved](https://devlog.creusot.rs/v0-14-0/) | `formalmethods` `release` `rust` | [讨论](https://lobste.rs/s/6tbd2o/creusot_0_14_0_release_contracts_for_rust) |
| 34 | 1 | [A slightly faster slimmer curl](https://daniel.haxx.se/blog/2026/10/13/a-slightly-faster-slimmer-curl/) | `performance` | [讨论](https://lobste.rs/s/d9rpcl/slightly_faster_slimmer_curl) |
| 9 | 1 | [Easylang: A Simple, Browser-Based Programming Language in the Spirit of the Old Home Computer BASIC](https://easylang.online/ide) | `education` `programming` `show` | [讨论](https://lobste.rs/s/oq6nhr/easylang_simple_browser_based) |
| 3 | 1 | [Bru: Send and read SMS from the browser](https://sverre.me/projects/bru/) | `android` | [讨论](https://lobste.rs/s/a0jmkh/bru_send_read_sms_from_browser) |
| 3 | 1 | [Please stop hashing the public key first (or: ML-DSA's µ annoys me)](https://blog.erincandescent.net/2026/10/mu-annoys-me/) | `cryptography` | [讨论](https://lobste.rs/s/xatiaj/please_stop_hashing_public_key_first_ml) |
| 7 | 0 | [Data-oriented Design for Mortals](https://www.youtube.com/watch?v=uI1Yx1CJAB0) | `video` | [讨论](https://lobste.rs/s/es1vaj/data_oriented_design_for_mortals) |
| 58 | 30 | [Living in the Weimar era of Ruby](https://blog.julik.nl/2026/10/the-weimar-of-ruby) | `ruby` `vibecoding` | [讨论](https://lobste.rs/s/lfen2h/living_weimar_era_ruby) |
| 5 | 1 | [Can Ease of Creation Lead to Decrease in Quality & Value?](https://pikuma.com/blog/ease-creation-decrease-quality-value) | `art` `programming` `vibecoding` | [讨论](https://lobste.rs/s/jecehj/can_ease_creation_lead_decrease_quality) |
| 4 | 0 | [The 2026 Maintainers Summit](https://lwn.net/SubscriberLink/1099594/fba1c2268c3e2fb5/) | `linux` `practices` `vibecoding` | [讨论](https://lobste.rs/s/fppgkl/2026_maintainers_summit) |
| 9 | 0 | [Chasing a -O2 pessimization in antcc](https://386s.org/w/lua-antcc-pessimization/) | `c` `compilers` | [讨论](https://lobste.rs/s/g2ktrq/chasing_o2_pessimization_antcc) |
| 4 | 0 | [Accelerating the Zig Tokenizer (with AVX-512)](https://www.youtube.com/watch?v=E6dWIwPLx3s) | `plt` `video` `zig` | [讨论](https://lobste.rs/s/jref3l/accelerating_zig_tokenizer_with_avx_512) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

_还没有到 14 天的，25 个在等。_

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
