# early-radar 选题雷达 · 2026-10-15

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 111 个，细查前 20 个 · 比上次 = 和 2026-10-14 那次比 · 生成于 2026-10-15 04:13 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 0 个 · Show HN ✅ 29 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 0 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 8 个 · 🟡 在降温 3 个 · 🔵 已被发现 3 个 · 💤 不活跃 0 个 · 🔴 先核对 6 个
- **今天新出现 3 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) 平均每天 +1603，见 [爆发](#爆发)
- **最值得今天试的**：
  - [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) — Let an AI model use a real iPhone with a $7 ESP32: AirPlay e…（近 7 天 +2145，刚发布一周内）
  - [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) — Your company's data, connected into one ontology, on your ow…（近 7 天 +1335，比前 7 天快 9.7 倍，在加速）
  - [Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth) — An agent skill that finds where a photo was taken — OpenStre…（近 7 天 +1343，比前 7 天快 1.5 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 21 个（star 合计 21521），代表：[Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：8 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Guitoro, a virtual guitar you strum with your keyboard](https://guitoro.com/) — 553 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) | 10819 | 1603 | +2316 | 6.8 | — | anatomy · wheresryan22 anatomy · ryan anatomy | An agent skill for creating detailed, interactive isometric… |
| [openai/math](https://github.com/openai/math) | 14836 | 1794 | +131 | 8.3 | [342](https://news.ycombinator.com/item?id=50003107) | math · openai math |  |
| ✅ [storytold/wordcraft](https://github.com/storytold/wordcraft) | 12537 | 1603 | +1203 | 7.8 | [101](https://news.ycombinator.com/item?id=50050370) | wordcraft · storytold wordcraft · artcraft wordcraft | An open-source, clean-room reimplementation of Microsoft Wor… |
| [ARahim3/DigUp](https://github.com/ARahim3/DigUp) | 3734 | 591 | +1111 | 6.3 | [5](https://news.ycombinator.com/item?id=50045015) | digup · arahim3 digup · abdur digup | Search your computer by what's in your files: photos, PDFs,… |
| [jhaizhou-ops/d2r-mobile](https://github.com/jhaizhou-ops/d2r-mobile) | 2328 | 827 | +1091 | 2.8 | — | d2r mobile · jhaizhou-ops d2r mobile | Open-source iOS / macOS compatibility layer for Diablo II: R… |
| 🆕 [T-Auto/dsh-ops](https://github.com/T-Auto/dsh-ops) | 1764 | 256 | +889 | 6.9 | — | dsh ops · t-auto dsh ops | A toolkit for low-level operations in DSH, designed to reduc… |
| [Arekejoker/qwen21-nsfw-pose-skill](https://github.com/Arekejoker/qwen21-nsfw-pose-skill) | 1362 | 666 | +412 | 2 | — | qwen21 nsfw pose skill · arekejoker qwen21 nsfw pose skill | Qwen-Image 2.1 NSFW/姿势出图 skill：作者级提示词配方 + NSFW LoRA + 136 姿势… |
| [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) | 2145 | 635 | +489 | 3.4 | — | esp32 iphone agent · onehumanbeing esp32 iphone agent · henry esp32 iphone agent | Let an AI model use a real iPhone with a $7 ESP32: AirPlay e… |
| ✅ [storytold/gridcraft](https://github.com/storytold/gridcraft) | 4918 | 618 | +405 | 8 | — | gridcraft · storytold gridcraft · artcraft gridcraft | GridCraft: an open-source, clean-room spreadsheet (Microsoft… |
| ✅ [storytold/cadcraft](https://github.com/storytold/cadcraft) | 4873 | 613 | +567 | 8 | — | cadcraft · storytold cadcraft · artcraft cadcraft | CADCraft: computer-aided design and drafting — an open-sourc… |
| [mhtsec/ARTEX](https://github.com/mhtsec/ARTEX) | 4133 | 595 | +207 | 6.9 | — | artex · mhtsec artex · mht artex | AI 自主渗透测试系统 / 百度“agent+”攻防挑战赛冠军项目 |
| [liseami/CCBaga](https://github.com/liseami/CCBaga) | 2273 | 566 | +172 | 4 | — | ccbaga · liseami ccbaga · purefantasyzhao ccbaga |  |
| [bherbruck/solidcraft](https://github.com/bherbruck/solidcraft) | 2450 | 332 | +564 | 7.4 | [140](https://news.ycombinator.com/item?id=50064840) | solidcraft · bherbruck solidcraft | SolidCraft: an open-source parametric 3D CAD application bui… |
| ✅ [storytold/figcraft](https://github.com/storytold/figcraft) | 1010 | 183 | +561 | 5.5 | [3](https://news.ycombinator.com/item?id=50069000) | figcraft · storytold figcraft · artcraft figcraft | FigCraft: interface design and prototyping; an open-source,… |
| 🆕 [HeyPuter/everything](https://github.com/HeyPuter/everything) | 794 | 531 | — | 1.5 | [7](https://news.ycombinator.com/item?id=50075719) | everything · heyputer everything · puter everything | We're rebuilding and open-sourcing the world’s software from… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 92.3 | ✅ 🟢 窗口内 | [storytold/soundcraft](https://github.com/storytold/soundcraft) | Rust | 2828 | +210 | +2189 | +639 | `·····▄▆▇▆█▆▅▄·` | 7 | — | — |
| 2 | 92.1 | 🟢 窗口内 | [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) | C | 2145 | +489 | +2145 | +0 | `·········▁█▇▄·` | 3 | — | — |
| 3 | 87.7 | ✅ 🟢 窗口内 | [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) | Python | 2630 | +187 | +1487 | +1143 | `·▆▆▅▅▆▇███▇▇▅·` | 11 | — | — |
| 4 | 86.4 | 🟢 窗口内 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) | TypeScript | 1472 | +64 | +1335 | +137 | `······▃█▇▄▂▂▂·` | 7 | — | — |
| 5 | 86.4 | 🆕 🟢 窗口内 | [Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth) | Python | 2821 | +400 | +1343 | +901 | `▁▁▂▂▂█▄▃▂▆▄▄▆·` | 26 | — | — |
| 6 | 85.2 | 🟢 窗口内 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | Python | 1254 | +111 | +1216 | +38 | `·····▁▁▁▂█▆▃▂·` | 9 | [10](https://news.ycombinator.com/item?id=50037852) | — |
| 7 | 83.9 | 🟢 窗口内 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 1084 | +249 | +1084 | +0 | `·········▁▆█▄·` | 4 | — | — |
| 8 | 72.9 | 🟢 窗口内 | [tobi/disktree](https://github.com/tobi/disktree) | Rust | 2936 | +35 | +435 | +386 | `▃▃▃▂▂▃▂▂▂█▃▂▂·` | 20 | [3](https://news.ycombinator.com/item?id=49841155) | — |
| 9 | 60.5 | 🟡 在降温 | [feitangyuan/onetake](https://github.com/feitangyuan/onetake) | Python | 2400 | +88 | +422 | +805 | `█▄▄▆▆▅▄▄▃▃▄▄▄·` | 18 | — | — |
| 10 | 53.2 | 🟡 在降温 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) | Python | 1974 | +22 | +204 | +718 | `█▆▅▆▆▄▃▃▂▃▃▂▂·` | 14 | — | — |
| 11 | 52.9 | 🟡 在降温 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep) | TypeScript | 2678 | +5 | +198 | +467 | `▅█▅▄▃▅▅▄▃▅▃▃▁·` | 19 | [5](https://news.ycombinator.com/item?id=49880146) | — |
| 12 | 46.8 | 🔵 已被发现 | [bherbruck/solidcraft](https://github.com/bherbruck/solidcraft) | Rust | 2450 | +564 | +2450 | +0 | `·······▁▂▆▆█▆·` | 7 | [140](https://news.ycombinator.com/item?id=50064840) | — |
| 13 | 41.5 | 🔵 已被发现 | [rociiu/talorys](https://github.com/rociiu/talorys) | TypeScript | 1003 | +38 | +1003 | +0 | `········█▅▃▂▂·` | 4 | [329](https://news.ycombinator.com/item?id=50031614) | — |
| 14 | 41.5 | ✅ 🔴 先核对 | [storytold/figcraft](https://github.com/storytold/figcraft) | Rust | 1010 | +561 | +1010 | +0 | `·······▁··▁█▇·` | 5 | [3](https://news.ycombinator.com/item?id=50069000) | 一天进了一半以上的 star，但 HN 上没火过 |
| 15 | 41.3 | 🔴 先核对 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 973 | +87 | +973 | +0 | `··········█▃▂·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 16 | 41 | 🆕 🔴 先核对 | [marclou/mailcheap](https://github.com/marclou/mailcheap) | JavaScript | 933 | +33 | +933 | +0 | `········█▄▂▂▁·` | 4 | [2](https://news.ycombinator.com/item?id=50033695) | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 34 | 🆕 🔴 先核对 | [spideymooon/McOracle](https://github.com/spideymooon/McOracle) | Python | 287 | — | +287 | +0 | `··········▁█▄·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 30.9 | 🔵 已被发现 | [pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust) | Rust | 1215 | +44 | +486 | +730 | `·····█▄▂▃▂▂▂▂·` | 7 | [118](https://news.ycombinator.com/item?id=50000676) | — |
| 19 | 22.4 | 🔴 先核对 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) | Python | 2750 | -17 | +88 | +290 | `█▂▂▂▂▁▃▂▂▂▂▁▁·` | 15 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 21.3 | 🔴 先核对 | [trhhubsd/ARTEXX](https://github.com/trhhubsd/ARTEXX) | Go | 1198 | -9 | +1196 | +2 | `······▁▁▁▁█▆▁·` | 6 | — | 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1% |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 512 | 30 | 43747 | [Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep) |
| `mcp` | 162 | 30 | 19597 | [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp)、[bherbruck/solidcraft](https://github.com/bherbruck/solidcraft)、[leemysw/yovoice](https://github.com/leemysw/yovoice) |
| `rust` | 132 | 30 | 23815 | [tobi/disktree](https://github.com/tobi/disktree)、[storytold/soundcraft](https://github.com/storytold/soundcraft)、[bherbruck/solidcraft](https://github.com/bherbruck/solidcraft) |
| `local-first` | 57 | 30 | 12565 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[glanderness/BeefTV](https://github.com/glanderness/BeefTV) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 21 | 21521 | [Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) |
| `ai-agents` | 21 | 11778 | [Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill) |
| `codex` | 18 | 17017 | [Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) |
| `llm` | 14 | 10131 | [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `macos` | 14 | 8666 | [leemysw/yovoice](https://github.com/leemysw/yovoice)、[freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui) |
| `agent-skills` | 13 | 15444 | [Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth)、[Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) |
| `windows` | 10 | 6489 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[leemysw/yovoice](https://github.com/leemysw/yovoice)、[jev-chat/jev-chat-windows](https://github.com/jev-chat/jev-chat-windows) |
| `developer-tools` | 9 | 7359 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[penso/herdr-gpui](https://github.com/penso/herdr-gpui)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill) |
| `jev` | 9 | 6992 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[ollaya-dev/ollaya](https://github.com/ollaya-dev/ollaya)、[jev-chat/jev-chat-windows](https://github.com/jev-chat/jev-chat-windows) |
| `python` | 9 | 6120 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[yakuikai/tokentab](https://github.com/yakuikai/tokentab)、[jev-chat/jev-chat-windows](https://github.com/jev-chat/jev-chat-windows) |
| `ai-agent` | 8 | 7070 | [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent)、[freestylefly/WeChatBridge](https://github.com/freestylefly/WeChatBridge)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `linux` | 8 | 5857 | [RubinLabs26/ISpotify](https://github.com/RubinLabs26/ISpotify)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[amontlabs/lcu](https://github.com/amontlabs/lcu) |

**语言分布**：Python 36 · Rust 29 · TypeScript 21 · JavaScript 8 · Go 4 · Swift 4 · C 1 · C++ 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. ✅ [storytold/soundcraft](https://github.com/storytold/soundcraft) · 🟢 窗口内 · 92.3 分

> An open-source, clean-room reimplementation of Avid Pro Tools in pure Rust

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2828 | +2189 | +639 | 1777 | 304 | Rust | Apache-2.0 | 10-07（7 天前） | 今天 |

- **近 14 天每天新增**：`·····▄▆▇▆█▆▅▄·` 0 0 0 0 0 239 400 411 351 520 401 309 197 0
- **势头**：比前 7 天快 3.4 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://getartcraft.com/apps/soundcraft>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) · 🟢 窗口内 · 92.1 分

> Let an AI model use a real iPhone with a $7 ESP32: AirPlay eyes, USB HID hands, any OpenAI-compatible vision model. No Mac, no developer account, no jailbreak.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2145 | +2145 | +0 | 288 | 3 | C | MIT | 10-11（3 天前） | 今天 |

- **近 14 天每天新增**：`·········▁█▇▄·` 0 0 0 0 0 0 0 0 0 39 922 805 379 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `airplay` `automation` `computer-use` `esp32` `esp32-s3` `iphone` `llm` `usb-hid`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. ✅ [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) · 🟢 窗口内 · 87.7 分

> Eleven free Claude skills that clone any app: reverse-engineer it, rebuild it, test it for bugs, then fix what its users hate. Free, MIT.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2630 | +1487 | +1143 | 390 | 7 | Python | MIT | 10-03（11 天前） | 11 天前 |

- **近 14 天每天新增**：`·▆▆▅▅▆▇███▇▇▅·` 0 186 217 156 168 188 228 278 267 270 254 255 163 0
- **势头**：比前 7 天快 1.3 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent` `agent-skills` `app-clone` `claude` `claude-code` `claude-skills` `indie-hacker` `reverse-engineering` `saas`
- **主页**：<https://opusjake.ai>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) · 🟢 窗口内 · 86.4 分

> Your company's data, connected into one ontology, on your own computer. A local-first data workspace built on HelixDB and DuckDB.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1472 | +1335 | +137 | 224 | 13 | TypeScript | Apache-2.0 | 10-07（7 天前） | 1 天前 |

- **近 14 天每天新增**：`······▃█▇▄▂▂▂·` 0 0 0 0 0 0 137 504 427 180 99 66 59 0
- **势头**：比前 7 天快 9.7 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. 🆕 [Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth) · 🟢 窗口内 · 86.4 分

> An agent skill that finds where a photo was taken — OpenStreetMap geometry, elevation skylines, satellite imagery and street view — and shows its work. Works with Claude Code, Codex, Cursor, Gemini CLI, OpenCode and GitHub Copilot.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2821 | +1343 | +901 | 366 | 8 | Python | MIT | 09-18（26 天前） | 今天 |

- **近 14 天每天新增**：`▁▁▂▂▂█▄▃▂▆▄▄▆·` 23 24 42 85 60 485 182 121 101 312 236 192 381 0
- **势头**：比前 7 天快 1.5 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-agents` `claude-code` `codex` `computer-vision` `cursor` `gemini-cli` `geoguessr` `geoint` `geolocation` `github-copilot` `image-geolocation` `opencode` `openstreetmap` `osint` `photo-geolocation` `reverse-image-search` `satellite-imagery`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [academa-labs/manimgx](https://github.com/academa-labs/manimgx) · 🟢 窗口内 · 85.2 分

> The animation engine for agents: blazingly fast math and 3D videos with Manim's Python API, on a Rust GPU core.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1254 | +1216 | +38 | 85 | 8 | Python | MIT | 10-05（9 天前） | 今天 |

- **近 14 天每天新增**：`·····▁▁▁▂█▆▃▂·` 0 0 0 0 0 7 31 11 41 567 370 125 102 0
- **势头**：比前 7 天快 32.0 倍，在加速
- **HN**：发过 1 次，最高 10 分（[讨论](https://news.ycombinator.com/item?id=50037852)）
- **主页**：<https://manimgx.academa.ai>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [opengeos/RustGIS](https://github.com/opengeos/RustGIS) · 🟢 窗口内 · 83.9 分

> A fast, free and open-source GIS in pure Rust.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1084 | +1084 | +0 | 148 | 27 | Rust | Apache-2.0 | 10-10（4 天前） | 今天 |

- **近 14 天每天新增**：`·········▁▆█▄·` 0 0 0 0 0 0 0 0 0 2 372 493 217 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`geospatial` `gis` `remote-sensing` `rust` `rust-lang`
- **主页**：<https://rustgis.app>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [tobi/disktree](https://github.com/tobi/disktree) · 🟢 窗口内 · 72.9 分

> A treemap for finding and removing what fills your disk, for Omarchy. Rust + GPUI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2936 | +435 | +386 | 181 | 51 | Rust | MIT | 09-24（20 天前） | 10 天前 |

- **近 14 天每天新增**：`▃▃▃▂▂▃▂▂▂█▃▂▂·` 84 70 58 33 46 56 39 31 36 239 63 37 29 0
- **势头**：比前 7 天快 1.1 倍，在加速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=49841155)）
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 9. [feitangyuan/onetake](https://github.com/feitangyuan/onetake) · 🟡 在降温 · 60.5 分

> Motion films that never cut to the next slide: every beat grows out of the one before, one continuous camera, continuity measured by an oracle. Product launch films and feature demos, made with a coding agent.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2400 | +422 | +805 | 153 | 3 | Python | — | 09-26（18 天前） | 2 天前 |

- **近 14 天每天新增**：`█▄▄▆▆▅▄▄▃▃▄▄▄·` 187 92 85 123 122 119 77 69 58 50 86 80 79 0
- **势头**：只有前 7 天的 52%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `animation` `canvas` `claude-skill` `launch-video` `motion-graphics` `video`
- **主页**：<https://onetakemotion.com>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) · 🟡 在降温 · 53.2 分

> AI生成の日本語を自然な日本語へ推敲するAgent Skill / Agent Skill for Refining AI-Generated Japanese into Natural Japanese

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1974 | +204 | +718 | 50 | 0 | Python | MIT | 09-30（14 天前） | 2 天前 |

- **近 14 天每天新增**：`█▆▅▆▆▄▃▃▂▃▃▂▂·` 172 115 93 112 111 78 37 47 23 37 49 33 15 0
- **势头**：只有前 7 天的 28%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-writing` `antigravity` `claude-code` `codex` `cursor` `gemini` `japanese` `linter` `llm` `nlp` `writing` `writing-assistant` `writing-tool`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [storytold/figcraft](https://github.com/storytold/figcraft) — 一天进了一半以上的 star，但 HN 上没火过
- [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) — 一天进了一半以上的 star，但 HN 上没火过
- [marclou/mailcheap](https://github.com/marclou/mailcheap) — 一天进了一半以上的 star，但 HN 上没火过
- [spideymooon/McOracle](https://github.com/spideymooon/McOracle) — 一天进了一半以上的 star，但 HN 上没火过
- [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) — 一天进了一半以上的 star，但 HN 上没火过
- [trhhubsd/ARTEXX](https://github.com/trhhubsd/ARTEXX) — 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1%

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 553 | 155 | [Show HN: Guitoro, a virtual guitar you strum with your keyboard](https://guitoro.com/) | [HN](https://news.ycombinator.com/item?id=50077020) |
| 431 | 55 | [Show HN: Carrier-Explode: iPhone, Pixel and Galaxy carrier settings decoded](https://carrierexplode.com/) | [HN](https://news.ycombinator.com/item?id=50024499) |
| 419 | 195 | [Show HN: Let your AI agents paint big arrows, boxes and text on your screen](https://github.com/franzenzenhofer/big-arrow-on-the-screen) | [HN](https://news.ycombinator.com/item?id=50018817) |
| 310 | 158 | [Show HN: PS2 games statically recompiled to WebAssembly](https://github.com/snuri00/ps2-web-recomp) | [HN](https://news.ycombinator.com/item?id=50052251) |
| 286 | 125 | [Show HN: WallHop – 12ft.io is gone, so I built a replacement](https://wallhop.io/) | [HN](https://news.ycombinator.com/item?id=50038634) |
| 241 | 181 | [Show HN: Quake ported to safe Rust, playable in browser](https://quake-srp.pages.dev/) | [HN](https://news.ycombinator.com/item?id=50016312) |
| 222 | 37 | [Show HN: Making a flexible "neon" t-shirt with LED filaments](http://scottbezek.blogspot.com/2026/10/making-flexible-neon-t-shirt-with-leds.html) | [HN](https://news.ycombinator.com/item?id=50008047) |
| 218 | 126 | [Show HN: BetterWispr – Free, open-source dictation for Mac](https://betterwispr.com/) | [HN](https://news.ycombinator.com/item?id=50042333) |
| 209 | 116 | [Show HN: How random are you?](https://lab.specr.net/rigged-draw/) | [HN](https://news.ycombinator.com/item?id=50074909) |
| 190 | 66 | [Show HN: The rarest tech books and docs you've probably never read](https://readrare.com/) | [HN](https://news.ycombinator.com/item?id=50024055) |
| 170 | 90 | [Show HN: Use your OpenAI subscription to create audiobooks](https://pdftomp3.com/connect-ai/) | [HN](https://news.ycombinator.com/item?id=50069337) |
| 140 | 51 | [Show HN: SolidCraft – Open-Source Parametric CAD in Rust (With MCP Support)](https://github.com/bherbruck/solidcraft) | [HN](https://news.ycombinator.com/item?id=50064840) |
| 135 | 34 | [Show HN: Petal, open-source CoScreen/ScreenHero finally free](https://petal.live/) | [HN](https://news.ycombinator.com/item?id=50092470) |
| 122 | 46 | [Show HN: Proton Drive for Linux](https://oss.lsantos.dev/proton-drive-linux-fs/) | [HN](https://news.ycombinator.com/item?id=50003545) |
| 116 | 76 | [Show HN: I built a tool to track what AI leaders say and how their views change](https://blumify.io/people) | [HN](https://news.ycombinator.com/item?id=50081151) |
| 115 | 70 | [Show HN: Pulse Local, a Mac budgeting app whose AI models run on your machine](https://pulseos.finance) | [HN](https://news.ycombinator.com/item?id=50080275) |
| 115 | 30 | [Show HN: Atticus – Hold-to-talk voice assistant for macOS that runs on Claude -p](https://github.com/SaarthurR/atticus-mac) | [HN](https://news.ycombinator.com/item?id=50049588) |
| 93 | 73 | [Show HN: I wrote an email app that accepts only one sender per inbox](https://clova.email/) | [HN](https://news.ycombinator.com/item?id=50090932) |
| 92 | 20 | [Show HN: Happy Hangul Day! An RNN for Generating Korean Handwriting Strokes](https://hangul.ink/blog/hangul-day) | [HN](https://news.ycombinator.com/item?id=50015833) |
| 87 | 18 | [Show HN: Spotatui, a Spotify TUI/GUI without web API rate limits](https://github.com/LargeModGames/spotatui) | [HN](https://news.ycombinator.com/item?id=50070010) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 25 | [AutoDev: Automated AI-Driven Development](https://huggingface.co/papers/2403.08299) | AutoDev is an AI-driven software development framework that automates complex engineering tasks within a secure Docker environment, achievin… | [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi) 29111★ |
| 45 | [RSI-Anything: Unlocking Recursive Self-Improvement with World Models](https://huggingface.co/papers/2610.13912) | Recursive self-improvement (RSI) aims to transform interaction experience into persistent improvements, yet external feedback is costly and… | 💡 [Gen-Verse/RSI-Anything](https://github.com/Gen-Verse/RSI-Anything) 711★ |
| 27 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Mixture-of-experts (MoE) inference on consumer hardware is bounded by weight memory: a 35B-class model is 19.5GB at 4-bit, and sparsity shri… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 4850★ |
| 111 | [Urbex: Agentic Spatial Grounding for City-Scale 3D Scenes](https://huggingface.co/papers/2610.18356) | City-scale 3D grounding is commonly formulated as candidate ranking, which requires precomputed instance proposals and becomes inefficient i… | 💡 [AMAP-ML/Urbex](https://github.com/AMAP-ML/Urbex) 79★ |
| 151 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 111157★ |
| 236 | [YuE2: Unifying Symbolic and Audio Music Generation at Frontier Quality](https://huggingface.co/papers/2609.33757) | Symbolic models make melody, harmony, rhythm, and form explicit but typically stop before a finished recording; audio models produce complet… | [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE) 11950★ |
| 113 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 1190★ |
| 18 | [Bitnet.cpp: Efficient Edge Inference for Ternary LLMs](https://huggingface.co/papers/2502.11880) | Bitnet.cpp enhances edge inference for ternary LLMs using a novel mixed-precision matrix multiplication library, achieving significant speed… | [microsoft/BitNet](https://github.com/microsoft/BitNet) 41157★ |
| 199 | [VideoJev: System One Model for Video Understanding and Interaction](https://huggingface.co/papers/2610.18615) | Visual agents must turn video observations into timely decisions to track progress and choose what to do next. | 💡 [MCG-NJU/VideoJev](https://github.com/MCG-NJU/VideoJev) 52★ |
| 93 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 27375★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 90914★ |
| 268 | [Jeva: System One Models from First Principles](https://huggingface.co/papers/2610.18773) | System one models enable direct, low-latency decision-making. | 💡 [LiQiiiii/Jeva](https://github.com/LiQiiiii/Jeva) 63★ |
| 195 | [Agent-Reflex: Teaching Language Agents to Act Reflectively](https://huggingface.co/papers/2610.17953) | Large language models have evolved from single-turn chatbots into interactive agents capable of long-horizon reasoning. | 💡 [RUC-NLPIR/Agent-Reflex](https://github.com/RUC-NLPIR/Agent-Reflex) 55★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 34 | [HuggingFace's Transformers: State-of-the-art Natural Language Processing](https://huggingface.co/papers/1910.03771) | Transformers library provides state-of-the-art Transformer architectures and pretrained models for natural language processing tasks with a… | [huggingface/transformers](https://github.com/huggingface/transformers) 167677★ |
| 56 | [Multics: Generative Multi-Player World Model with Hierarchical Communication](https://huggingface.co/papers/2610.17201) | Multi-player interactive world models aim to simulate shared environments from multiple players' perspectives, but achieving robust generati… | 💡 [TencentARC/Multics](https://github.com/TencentARC/Multics) 57★ |
| 180 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 81752★ |
| 34 | [FlashVSR+: Efficient Video Super-Resolution via Hybrid Attention and Reward-Yield Distribution Match…](https://huggingface.co/papers/2610.17552) | Recent video super-resolution (VSR) models achieve efficient one-step generation through diffusion distillation. | 💡 [OpenImagingLab/FlashVSR_Plus](https://github.com/OpenImagingLab/FlashVSR_Plus) 46★ |
| 315 | [DiffusionART: Efficient, Stable and Scalable Reinforcement of Diffusion Models](https://huggingface.co/papers/2610.12572) | Online reinforcement learning (RL) fine-tunes diffusion models with black-box rewards, but reverse-process methods such as Flow-GRPO are lim… | 💡 [vanzll/DiffusionART](https://github.com/vanzll/DiffusionART) 124★ |
| 59 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 40753★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

_这次没有（新上榜 0 个）。_

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 59 | 27 | [Anthropic's Scion is heavily inspired by Mononoke](https://sunshowers.io/posts/anthropic-mononoke/) | `vcs` `vibecoding` | [讨论](https://lobste.rs/s/plcgps/anthropic_s_scion_is_heavily_inspired_by) |
| 108 | 31 | [Introducing Firefox Enterprise](https://blog.mozilla.org/en/firefox/introducing-firefox-enterprise/) | `browsers` `release` `web` | [讨论](https://lobste.rs/s/7xg9rm/introducing_firefox_enterprise) |
| 39 | 32 | [What I Self-Host](https://viceconsole.fyi/blog/2026/10/10/what-i-self-host/) | `devops` | [讨论](https://lobste.rs/s/j4tlzg/what_i_self_host) |
| 66 | 4 | [Plasma 6.8 released (KDE's 30th birthday)](https://kde.org/announcements/plasma/6/6.8.0/) | `linux` `release` | [讨论](https://lobste.rs/s/d1c8zn/plasma_6_8_released_kde_s_30th_birthday) |
| 23 | 8 | [Awesome Gaming on Linux Without Cheating](https://onlineservices.epicgames.com/news/introducing-easy-anti-cheat-linux-v2) | `games` `linux` `security` | [讨论](https://lobste.rs/s/x9fqa4/awesome_gaming_on_linux_without_cheating) |
| 50 | 22 | [Fancy Curl Sites](https://nytpu.com/gemlog/2026-03-18) | `web` | [讨论](https://lobste.rs/s/zitobg/fancy_curl_sites) |
| 7 | 2 | [Fixing C Strings With String Views](https://eliasebner.com/blog/guides/fixing-strings-in-c/) | `c` | [讨论](https://lobste.rs/s/5j4bwx/fixing_c_strings_with_string_views) |
| 20 | 4 | [GitLab warns of max severity code execution vulnerability](https://www.bleepingcomputer.com/news/security/gitlab-warns-of-max-severity-rce-flaw-in-regex-compiler-engine/) | `security` `vcs` | [讨论](https://lobste.rs/s/tehays/gitlab_warns_max_severity_code_execution) |
| 30 | 6 | [Factor 0.102 now available](https://re.factorcode.org/2026/10/factor-0-102-now-available.html) | `concatenative` `release` | [讨论](https://lobste.rs/s/a4ljnh/factor_0_102_now_available) |
| 30 | 8 | [Ledger confirms spy chip implant behind wallet crypto thefts](https://www.bleepingcomputer.com/news/security/ledger-confirms-hardware-wallet-spy-implant-behind-crypto-thefts/) | `cryptography` `security` | [讨论](https://lobste.rs/s/cwota8/ledger_confirms_spy_chip_implant_behind) |
| 30 | 2 | [yet another place where a linux man page is inaccurate](https://sebsite.pw/w/20261014-initstate.html) | `c` `linux` | [讨论](https://lobste.rs/s/tsjuje/yet_another_place_where_linux_man_page_is) |
| 19 | 0 | [Better HTTP/1 connection reuse](https://go.dev/blog/http-connection-reuse) | `go` | [讨论](https://lobste.rs/s/mkq3x9/better_http_1_connection_reuse) |
| 10 | 6 | [ZXC: Lossless compression built for ultra-fast decode](https://libzxc.org/) | `compsci` `vibecoding` | [讨论](https://lobste.rs/s/mf3tmv/zxc_lossless_compression_built_for_ultra) |
| 30 | 24 | [Apple: Switch to Safari (from Chrome)](https://www.apple.com/safari/switch/) | `browsers` | [讨论](https://lobste.rs/s/dyypvf/apple_switch_safari_from_chrome) |
| 23 | 1 | [My Game's Procedural Dialogue System](https://www.youtube.com/watch?v=NaW0d7Tghw0) | `games` `video` | [讨论](https://lobste.rs/s/stmtap/my_game_s_procedural_dialogue_system) |
| 5 | 2 | [The DelightQL Query Language](https://delightql.org) | `databases` `rust` `show` `vibecoding` | [讨论](https://lobste.rs/s/ireiaf/delightql_query_language) |
| 96 | 71 | [A plea not to use uv-build](https://blogs.gentoo.org/mgorny/2026/10/12/a-plea-not-to-use-uv-build/) | `devops` `python` | [讨论](https://lobste.rs/s/73ssw1/plea_not_use_uv_build) |
| 16 | 4 | [A UAF turned RCE](https://daniel.haxx.se/blog/2026/10/14/a-uaf-turned-rce/) | `security` | [讨论](https://lobste.rs/s/g46xkj/uaf_turned_rce) |
| 3 | 4 | [ito - build terminal ui in lua](https://uji.sh/ito) | `lua` `rust` `vibecoding` | [讨论](https://lobste.rs/s/9lqyul/ito_build_terminal_ui_lua) |
| 90 | 12 | [Did Ente Locker copy my code without attribution?](https://fairscan.org/blog/did-ente-locker-copy-my-code-without-attribution/) | `law` | [讨论](https://lobste.rs/s/uiulqe/did_ente_locker_copy_my_code_without) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

_还没有到 14 天的，30 个在等。_

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
