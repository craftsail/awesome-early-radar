# early-radar 选题雷达 · 2026-11-19

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 98 个，细查前 20 个 · 比上次 = 和 2026-11-18 那次比 · 生成于 2026-11-19 06:57 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 7 个 · Show HN ✅ 28 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 5 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 6 个 · 🟡 在降温 10 个 · 🔵 已被发现 2 个 · 💤 不活跃 0 个 · 🔴 先核对 2 个
- **今天新出现 5 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [erkamyaman/rust-anything](https://github.com/erkamyaman/rust-anything) 平均每天 +1365，见 [爆发](#爆发)
- **复盘**：🚀 爆发 47/66 · 🔴 先核对 21/38 · 🟡 在降温 0/6 · 🔵 已被发现 1/3 · 💤 不活跃 0/1 · 🟢 窗口内 9/20（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) — Agent skill for hill-climbing local LLM serving speed (decod…（近 7 天 +1158，刚发布一周内）
  - [huggingface/pybot](https://github.com/huggingface/pybot) — PyBot: a chatbot written in pure Python by a swarm of agents…（近 7 天 +859，比前 7 天快 429.5 倍，在加速）
  - [Renly1994/xiaotang-daozai](https://github.com/Renly1994/xiaotang-daozai) — 岛仔 Daozai：Rust 构建的 Windows 桌面信息岛。音乐歌词、邮件验证码、日程提醒、待办与 AI 额度，让…（近 7 天 +672，比前 7 天快 1.6 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 20 个（star 合计 24182），代表：[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DIYgod/pinky](https://github.com/DIYgod/pinky)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：4 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: My $300 embroidery machine needed a subscription, so I built my own app](https://github.com/simpsoka/zigzag) — 742 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [erkamyaman/rust-anything](https://github.com/erkamyaman/rust-anything) | 3800 | 1365 | +1922 | 2.8 | — | rust anything · erkamyaman rust anything · erkam rust anything | Rewrite your whole app in Rust, one piece at a time, checked… |
| [krisgfx9/Wireless-Device-Battery-Monitor](https://github.com/krisgfx9/Wireless-Device-Battery-Monitor) | 4168 | 1681 | +1049 | 2.5 | [1](https://news.ycombinator.com/item?id=50543820) | wireless device battery monitor · krisgfx9 wireless device battery monitor · krisgfx wireless device battery monitor | Show the battery level of wireless mice, headsets, keyboards… |
| 🆕 [Hut-hzf/ung220z-tool](https://github.com/Hut-hzf/ung220z-tool) | 1452 | 380 | +860 | 3.8 | — | ung220z tool · hut-hzf ung220z tool | ung220z-tool 是一个针对 UNG220Z（九联/Unionman 中国移动光猫）的一键凭据提取工具，仅限在你… |
| 🆕 [huami1314/GestaltX](https://github.com/huami1314/GestaltX) | 8434 | 837 | — | 10.1 | — | gestaltx · huami1314 gestaltx | An MobileGestalt editor for iOS 27.x, featuring region-code… |
| [deepseek-ai/chat-demo](https://github.com/deepseek-ai/chat-demo) | 4908 | 706 | +288 | 7 | [2](https://news.ycombinator.com/item?id=50509966) | chat demo · deepseek-ai chat demo · deepseek chat demo | Chat Demo |
| 🆕 [HolyArrs/HolyArrs](https://github.com/HolyArrs/HolyArrs) | 2068 | 222 | +632 | 9.3 | [171](https://news.ycombinator.com/item?id=50439000) | holyarrs · holyarrs holyarrs | One self-hosted app for your shows, movies and music. |
| [ersinkoc/phonebox](https://github.com/ersinkoc/phonebox) | 3348 | 289 | +536 | 11.6 | — | phonebox · ersinkoc phonebox · ersin phonebox | Turn an old Android phone into a customizable desk panel and… |
| [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) | 1158 | 461 | +180 | 2.5 | [1](https://news.ycombinator.com/item?id=50542464) | inference optimisation skill · sybil-solutions inference optimisation skill · sybil inference optimisation skill | Agent skill for hill-climbing local LLM serving speed (decod… |
| 🆕 [zephyr4123/snug](https://github.com/zephyr4123/snug) | 1028 | 167 | +400 | 6.1 | — | snug · zephyr4123 snug · zephyr snug | 让远程 Mac 在任意设备上获得原生级体验。专为 UU远程 打造的显示与触控增强：手机、平板、电脑各有专属屏幕，画面铺满… |
| [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt) | 2465 | 292 | +381 | 8.5 | [306](https://news.ycombinator.com/item?id=50454625) | yogurt · frigadehq yogurt · frigade yogurt | Private AI meeting notes that stay on your computer. A free,… |
| [tangerineturtle1/NX2navi](https://github.com/tangerineturtle1/NX2navi) | 4324 | 364 | +16 | 11.9 | — | nx2navi · tangerineturtle1 nx2navi |  |
| [Noniv/abyssal-garden](https://github.com/Noniv/abyssal-garden) | 2427 | 362 | +187 | 6.7 | [49](https://news.ycombinator.com/item?id=50506767) | abyssal garden · noniv abyssal garden · maksymilian abyssal garden | A dreamy underwater world you can swim through in your brows… |
| [Immortal-Protocols/lastbook](https://github.com/Immortal-Protocols/lastbook) | 2223 | 353 | +323 | 6.3 | — | lastbook · immortal-protocols lastbook | Offline knowledge AI, maps and videos for survival and rebui… |
| [apex-compute/ANR](https://github.com/apex-compute/ANR) | 2670 | 329 | +58 | 8.1 | [2](https://news.ycombinator.com/item?id=50463533) | anr · apex-compute anr · apex anr | Apex Neural Rendering (ANR) by Apex Compute |
| [chuanqisun/spaceship](https://github.com/chuanqisun/spaceship) | 880 | 329 | +106 | 2.7 | [9](https://news.ycombinator.com/item?id=50519664) | spaceship · chuanqisun spaceship · sun spaceship | Steer your ideas in realtime |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 84.7 | 🟢 窗口内 | [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) | Python | 1158 | +180 | +1158 | +0 | `··········▆█▃·` | 2 | [1](https://news.ycombinator.com/item?id=50542464) | — |
| 2 | 81.1 | 🆕 🟢 窗口内 | [huggingface/pybot](https://github.com/huggingface/pybot) | Python | 861 | +133 | +859 | +2 | `······▁···▇█▃·` | 6 | [7](https://news.ycombinator.com/item?id=50517920) | — |
| 3 | 78.1 | 🆕 🟢 窗口内 | [Renly1994/xiaotang-daozai](https://github.com/Renly1994/xiaotang-daozai) | Rust | 1475 | +75 | +672 | +420 | `▃▂▃▂▄▂▅█▅▅▄▄▃·` | 16 | — | — |
| 4 | 76.9 | 🟢 窗口内 | [andrew-babo/muse4ai](https://github.com/andrew-babo/muse4ai) | TypeScript | 1319 | +127 | +604 | +510 | `▆▅▃▅▄▆▅▅▅▆▇█▇·` | 15 | — | — |
| 5 | 75.6 | 🆕 🟢 窗口内 | [Moh4696/cinematic-skill](https://github.com/Moh4696/cinematic-skill) | Python | 785 | +37 | +543 | +242 | `···▄▆▄▃▅▇▇█▆▃·` | 9 | — | — |
| 6 | 63.6 | 🟡 在降温 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki) | Swift | 1610 | +30 | +579 | +722 | `▆▄▄█▅▃▃▅▇▅▆▃▂·` | 13 | — | — |
| 7 | 61.9 | 🟡 在降温 | [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) | TypeScript | 1730 | +33 | +488 | +1242 | `·····██▂▂▃▂▂▁·` | 10 | [5](https://news.ycombinator.com/item?id=48217340) | — |
| 8 | 61.4 | 🟡 在降温 | [DIYgod/pinky](https://github.com/DIYgod/pinky) | Go | 2491 | +83 | +462 | +2029 | `·▃█▄▃▂▂▂▂▂▂▂▂·` | 12 | — | — |
| 9 | 59.8 | 🟢 窗口内 | [lexifina/global-law](https://github.com/lexifina/global-law) | HTML | 2105 | +9 | +145 | +135 | `▃▅▅▄▅▄▄▄▇█▅▅▃·` | 21 | [1](https://news.ycombinator.com/item?id=50418651) | — |
| 10 | 59.1 | 🟡 在降温 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode) | Python | 2731 | +49 | +368 | +1948 | `▂██▄▂▃▂▂▂▂▂▂▁·` | 15 | — | — |
| 11 | 56.5 | 🟡 在降温 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 2682 | +44 | +284 | +529 | `█▆▅▆▅▆▄▃▅▅▃▄▃·` | 24 | [2](https://news.ycombinator.com/item?id=50272846) | — |
| 12 | 56.2 | 🟡 在降温 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 2658 | +48 | +274 | +389 | `██▆▇▆▄▃▅▇▅▄▄▅·` | 24 | — | — |
| 13 | 55.6 | 🟡 在降温 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Rust | 1990 | +34 | +258 | +616 | `▆▆█▇▄▄▆▅▅▂▂▄▃·` | 17 | — | — |
| 14 | 51.8 | 🟡 在降温 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | TypeScript | 2638 | +42 | +176 | +580 | `▇▅▅▄▄█▃▂▂▂▂▃▃·` | 18 | — | — |
| 15 | 49.1 | 🟡 在降温 | [voyager-so/vork](https://github.com/voyager-so/vork) | Rust | 1633 | +9 | +135 | +1498 | `█▇▄▃▂▂▁▁▂▁▁▁▁·` | 13 | [8](https://news.ycombinator.com/item?id=50396650) | — |
| 16 | 48.4 | 🟡 在降温 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2993 | +23 | +126 | +326 | `▇▆███▅▃▃▃▃▃▄▄·` | 28 | [3](https://news.ycombinator.com/item?id=50207695) | — |
| 17 | 43.5 | 🔵 已被发现 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt) | TypeScript | 2465 | +381 | +1409 | +1056 | `·····█▇▄▃▃▃▃▅·` | 8 | [306](https://news.ycombinator.com/item?id=50454625) | — |
| 18 | 30.5 | 🆕 🔵 已被发现 | [Dodaios/ste80-humanizer](https://github.com/Dodaios/ste80-humanizer) | Python | 913 | +143 | +447 | +466 | `···█▇▄▃▂▇▄▃▂▇·` | 9 | [114](https://news.ycombinator.com/item?id=50429144) | — |
| 19 | 9.7 | 🆕 🔴 先核对 | [Illson/RustText](https://github.com/Illson/RustText) | Rust | 639 | +212 | +639 | +0 | `···········█▄·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1%；没有描述 |
| 20 | 0 | 🔴 先核对 | [SK-Dev666/rust-external-trainer-tool](https://github.com/SK-Dev666/rust-external-trainer-tool) | TypeScript | 1103 | +0 | +0 | +1103 | `·▃▂▃▄█········` | 12 | — | fork 不到 star 的 1% |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 1110 | 30 | 45772 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) |
| `mcp` | 236 | 30 | 31001 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[lexifina/global-law](https://github.com/lexifina/global-law) |
| `rust` | 207 | 30 | 30909 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker)、[morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) |
| `local-first` | 82 | 30 | 14020 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[yjid/kensaku](https://github.com/yjid/kensaku) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 20 | 24182 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DIYgod/pinky](https://github.com/DIYgod/pinky) |
| `ai-agents` | 18 | 16157 | [daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[yjid/kensaku](https://github.com/yjid/kensaku)、[agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) |
| `codex` | 16 | 18500 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[ZiChuanLan/agent-purge](https://github.com/ZiChuanLan/agent-purge) |
| `windows` | 14 | 14087 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[yjid/kensaku](https://github.com/yjid/kensaku) |
| `mcp-server` | 13 | 9087 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo)、[phone-harness/mcp](https://github.com/phone-harness/mcp) |
| `model-context-protocol` | 13 | 8870 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo)、[simpsoka/zigzag](https://github.com/simpsoka/zigzag) |
| `agent-skills` | 12 | 14838 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) |
| `macos` | 11 | 11413 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama) |
| `tauri` | 8 | 6088 | [yjid/kensaku](https://github.com/yjid/kensaku)、[torrentplayer/torrentplayer](https://github.com/torrentplayer/torrentplayer)、[harshsinghsv/swiftdl](https://github.com/harshsinghsv/swiftdl) |
| `developer-tools` | 8 | 3256 | [SK-Dev666/rust-external-trainer-tool](https://github.com/SK-Dev666/rust-external-trainer-tool)、[jazzenchen/agent-hud-open](https://github.com/jazzenchen/agent-hud-open)、[chutingyean/Agent-Cockpit](https://github.com/chutingyean/Agent-Cockpit) |
| `llm` | 7 | 5547 | [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat)、[sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill)、[Dodaios/ste80-humanizer](https://github.com/Dodaios/ste80-humanizer) |
| `python` | 7 | 3926 | [cutetailbud/ff-ruyijs](https://github.com/cutetailbud/ff-ruyijs)、[SK-Dev666/rust-external-trainer-tool](https://github.com/SK-Dev666/rust-external-trainer-tool)、[aa1143/NamiAgent](https://github.com/aa1143/NamiAgent) |

**语言分布**：Rust 27 · Python 20 · TypeScript 20 · JavaScript 10 · Go 6 · C++ 2 · Swift 2 · Dart 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) · 🟢 窗口内 · 84.7 分

> Agent skill for hill-climbing local LLM serving speed (decode, speculative decoding, prefill, KV, startup, TTFT) on any hardware and quantization

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1158 | +1158 | +0 | 108 | 6 | Python | MIT | 11-16（2 天前） | 2 天前 |

- **近 14 天每天新增**：`··········▆█▃·` 0 0 0 0 0 0 0 0 0 0 406 579 173 0
- **势头**：刚发布一周内
- **HN**：发过 1 次，最高 1 分（[讨论](https://news.ycombinator.com/item?id=50542464)）
- **topics**：`agent-skill` `benchmarking` `claude-code` `inference` `llm` `speculative-decoding`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. 🆕 [huggingface/pybot](https://github.com/huggingface/pybot) · 🟢 窗口内 · 81.1 分

> PyBot: a chatbot written in pure Python by a swarm of agents. No weights, no training, just rules.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 861 | +859 | +2 | 84 | 1 | Python | Apache-2.0 | 11-12（6 天前） | 2 天前 |

- **近 14 天每天新增**：`······▁···▇█▃·` 0 0 0 0 0 0 2 0 0 0 325 408 126 0
- **势头**：比前 7 天快 429.5 倍，在加速
- **HN**：发过 2 次，最高 7 分（[讨论](https://news.ycombinator.com/item?id=50517920)）
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. 🆕 [Renly1994/xiaotang-daozai](https://github.com/Renly1994/xiaotang-daozai) · 🟢 窗口内 · 78.1 分

> 岛仔 Daozai：Rust 构建的 Windows 桌面信息岛。音乐歌词、邮件验证码、日程提醒、待办与 AI 额度，让重要信息轻轻出现在屏幕顶部。

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1475 | +672 | +420 | 253 | 67 | Rust | MIT | 11-03（16 天前） | 1 天前 |

- **近 14 天每天新增**：`▃▂▃▂▄▂▅█▅▅▄▄▃·` 54 40 47 40 75 35 129 205 111 109 91 91 65 0
- **势头**：比前 7 天快 1.6 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`desktop-widget` `dynamic-island` `egui` `productivity` `rust` `windows`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [andrew-babo/muse4ai](https://github.com/andrew-babo/muse4ai) · 🟢 窗口内 · 76.9 分

> Muse4AI — let your AI agent make the pictures and the videos. Local Windows bridge for Muse via REST, MCP, and OAuth.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1319 | +604 | +510 | 73 | 6 | TypeScript | MIT | 11-03（15 天前） | 5 天前 |

- **近 14 天每天新增**：`▆▅▃▅▄▆▅▅▅▆▇█▇·` 88 80 42 78 52 90 80 68 74 97 117 129 119 0
- **势头**：比前 7 天快 1.2 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. 🆕 [Moh4696/cinematic-skill](https://github.com/Moh4696/cinematic-skill) · 🟢 窗口内 · 75.6 分

> Agent skill for narrated cinematic films built entirely from code: one continuous camera over photos, maps and cards, timed to the voice. Claude Code, Codex, Cursor, Gemini CLI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 785 | +543 | +242 | 122 | 1 | Python | MIT | 11-09（9 天前） | 9 天前 |

- **近 14 天每天新增**：`···▄▆▄▃▅▇▇█▆▃·` 0 0 0 59 99 54 30 68 114 114 129 83 35 0
- **势头**：比前 7 天快 2.2 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `claude-code` `codex` `documentary` `explainer-video` `motion-graphics` `skia` `video`
- **主页**：<https://x.com/exploraX_>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [JosssphZhou/poki](https://github.com/JosssphZhou/poki) · 🟡 在降温 · 63.6 分

> Poki uses your iPhone like you do. An open-source agent that sees your screen and taps, types, and swipes across any app on your real device. Runs locally, plugs right into Claude Code and any MCP agent.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1610 | +579 | +722 | 259 | 95 | Swift | AGPL-3.0 | 11-05（13 天前） | 今天 |

- **近 14 天每天新增**：`▆▄▄█▅▃▃▅▇▅▆▃▂·` 130 94 90 191 121 48 48 101 158 99 147 47 27 0
- **势头**：只有前 7 天的 80%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `automation` `ios` `iphone` `mcp` `model-context-protocol`
- **主页**：<https://poki.bot>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 7. [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) · 🟡 在降温 · 61.9 分

> Open-source, self-hosted Slack alternative where your team and AI agents work together in channels and DMs. Agents run on Claude, ChatGPT/Codex, Gemini or Grok, with MCP tools, their own computer and browser, routines, memory and approvals. Web, desktop and phone apps. Docker Compose + Postgres. AGPL-3.0.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1730 | +488 | +1242 | 320 | 319 | TypeScript | AGPL-3.0 | 11-09（10 天前） | 今天 |

- **近 14 天每天新增**：`·····██▂▂▃▂▂▁·` 0 0 0 0 0 606 636 108 68 148 84 46 34 0
- **势头**：只有前 7 天的 39%，在减速
- **HN**：发过 4 次，最高 5 分（[讨论](https://news.ycombinator.com/item?id=48217340)）
- **topics**：`agentic-ai` `ai-agents` `browser-automation` `chat` `claude` `claude-code` `codex` `collaboration` `computer-use` `docker-compose` `gemini` `grok` `human-in-the-loop` `llm` `mcp` `multi-agent` `openai` `self-hosted` `slack-alternative` `team-chat`
- **主页**：<https://agentes.chat>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [DIYgod/pinky](https://github.com/DIYgod/pinky) · 🟡 在降温 · 61.4 分

> Let AI use your iPhone or Android phone, with you in the loop: any MCP agent from macOS, Windows or Linux, or Pinky itself, right on the phone.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2491 | +462 | +2029 | 260 | 18 | Go | Apache-2.0 | 11-06（12 天前） | 今天 |

- **近 14 天每天新增**：`·▃█▄▃▂▂▂▂▂▂▂▂·` 0 218 901 419 219 142 130 67 71 78 74 92 80 0
- **势头**：只有前 7 天的 23%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `android` `claude-code` `ios` `iphone` `mcp` `mcp-server` `phone-automation`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [lexifina/global-law](https://github.com/lexifina/global-law) · 🟢 窗口内 · 59.8 分

> The world's law in git: any provision, any country, any date, and the law that wrote each word.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2105 | +145 | +135 | 191 | 1 | HTML | — | 10-28（21 天前） | 今天 |

- **近 14 天每天新增**：`▃▅▅▄▅▄▄▄▇█▅▅▃·` 14 24 25 18 20 17 17 18 36 40 21 21 9 0
- **势头**：比前 7 天快 1.1 倍，在加速
- **HN**：发过 2 次，最高 1 分（[讨论](https://news.ycombinator.com/item?id=50418651)）
- **topics**：`git` `law` `legal-tech` `legislation` `mcp` `open-data`
- **主页**：<https://lexifina.com>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 10. [sarpstar/cinecode](https://github.com/sarpstar/cinecode) · 🟡 在降温 · 59.1 分

> Films made with code. Short films, long YouTube videos, ads, explainers and music videos: an AI coding agent writes the script, builds every frame in code, designs the sound and hands you an MP4.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2731 | +368 | +1948 | 466 | 12 | Python | MIT | 11-03（15 天前） | 6 天前 |

- **近 14 天每天新增**：`▂██▄▂▃▂▂▂▂▂▂▁·` 75 584 615 265 120 172 117 86 72 58 47 63 42 0
- **势头**：只有前 7 天的 19%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://x.com/sarpstar>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [Illson/RustText](https://github.com/Illson/RustText) — 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1%；没有描述
- [SK-Dev666/rust-external-trainer-tool](https://github.com/SK-Dev666/rust-external-trainer-tool) — fork 不到 star 的 1%

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 742 | 258 | [Show HN: My $300 embroidery machine needed a subscription, so I built my own app](https://github.com/simpsoka/zigzag) | [HN](https://news.ycombinator.com/item?id=50470488) |
| 276 | 30 | [Show HN: DeepSeek V3 in ~200 lines of pure Jax](https://github.com/Vaibhaav-Tiwari/deepseek-v3-jax) | [HN](https://news.ycombinator.com/item?id=50497589) |
| 256 | 76 | [Show HN: Isometric SF – A pixel-art map of the SF Bay Area](https://isometricsf.com/) | [HN](https://news.ycombinator.com/item?id=50487228) |
| 220 | 27 | [Show HN: Live map of U.S. flights during tonight's FAA nationwide ground stop](https://grounds.top/) | [HN](https://news.ycombinator.com/item?id=50491545) |
| 208 | 37 | [Show HN: Alloy CSS, dialogs, menus and tabs that work with JavaScript off](https://alloyhtml.com/example.html) | [HN](https://news.ycombinator.com/item?id=50532385) |
| 200 | 60 | [Show HN: ExitPath – Open-source ways out of Slack, Notion and Microsoft 365](https://exitpath-ruddy.vercel.app/) | [HN](https://news.ycombinator.com/item?id=50547980) |
| 182 | 46 | [Show HN: Take Voyager 1 apart, down to a single memory chip](https://rshekhar.com/voyager/) | [HN](https://news.ycombinator.com/item?id=50548161) |
| 173 | 44 | [Show HN: A terminal-native idle factory game, written in Rust with ratatui](https://gitlab.com/snipedbywifi/terminactory) | [HN](https://news.ycombinator.com/item?id=50497132) |
| 138 | 41 | [Show HN: AgentRun – open-source, Self-improving Managed Agents](https://github.com/Parcha-ai/agentrun/blob/main/README.md) | [HN](https://news.ycombinator.com/item?id=50471650) |
| 133 | 58 | [Show HN: Type Fighter 2](https://typefighter2.com/) | [HN](https://news.ycombinator.com/item?id=50544821) |
| 120 | 74 | [Show HN: Zigzag, a native Mac browser for people leaving Arc](https://github.com/ZigaoWang/zigzag) | [HN](https://news.ycombinator.com/item?id=50496787) |
| 109 | 37 | [Show HN: Agweb – a browser for agents that stays out of your way](https://github.com/paul-nameless/agweb) | [HN](https://news.ycombinator.com/item?id=50497147) |
| 90 | 31 | [Show HN: Mastra Factory, the open-source software factory we use to build Mastra](https://news.ycombinator.com/item?id=50548660) | [HN](https://news.ycombinator.com/item?id=50548660) |
| 89 | 21 | [Show HN: The Last Complication, a Zachtronics-style watchmaking puzzle game](https://lastcomplication.com/) | [HN](https://news.ycombinator.com/item?id=50511718) |
| 88 | 3 | [Show HN: Carton Clock – A working pendulum clock made from empty drink cartons](https://www.niklasroy.com/carton-clock/) | [HN](https://news.ycombinator.com/item?id=50482279) |
| 86 | 39 | [Show HN: Fursoy – Out-of-order RV64IMAFDV core in SystemVerilog (Linux 6.6)](https://github.com/FURSOY/fursoy-cpu) | [HN](https://news.ycombinator.com/item?id=50497137) |
| 76 | 3 | [Show HN: Open-source, real-time object tracking for live video feeds](https://github.com/aryamandarda/tamserve) | [HN](https://news.ycombinator.com/item?id=50523377) |
| 72 | 61 | [Show HN: Fable52.games – Play and inspect Fable 5.2 single-file HTML games](https://fable52.games) | [HN](https://news.ycombinator.com/item?id=50469007) |
| 72 | 37 | [Show HN: Sutra-OS – A self-hosted ontology platform](https://github.com/0nelight/sutra-os) | [HN](https://news.ycombinator.com/item?id=50525052) |
| 67 | 62 | [Show HN: Gawain – Require type hints on all Python variables](https://github.com/matheuzgomes/gawain) | [HN](https://news.ycombinator.com/item?id=50504072) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 8 | [PaperOrchestra: A Multi-Agent Framework for Automated AI Research Paper Writing](https://huggingface.co/papers/2604.05018) | PaperOrchestra is a multi-agent framework that converts unstructured research materials into complete LaTeX manuscripts with literature synt… | [google-research/paper-orchestra](https://github.com/google-research/paper-orchestra) 4521★ |
| 18 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 7686★ |
| 13 | [π^4: A Foundation Model for 4D Scene Geometry and Motion](https://huggingface.co/papers/2611.23144) | This unified foundation model enables the recovery of dense geometry, camera poses, and object tracking from diverse, uncalibrated observati… | 💡 [yyfz/Pi4](https://github.com/yyfz/Pi4) 230★ |
| 34 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 12041★ |
| 132 | [Gamer: A Generalist Vision-Language-Action Foundation Model for Long-Horizon Real-Time Game Agent](https://huggingface.co/papers/2611.18397) | Gamer is a generalist agent framework that integrates perception, memory, and multi-step reasoning, trained through continued pre-training,… | 💡 [RainBowLuoCS/Gamer](https://github.com/RainBowLuoCS/Gamer) 734★ |
| 168 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 123068★ |
| 69 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 24412★ |
| 18 | [Bitnet.cpp: Efficient Edge Inference for Ternary LLMs](https://huggingface.co/papers/2502.11880) | Bitnet.cpp enhances edge inference for ternary LLMs using a novel mixed-precision matrix multiplication library, achieving significant speed… | [microsoft/BitNet](https://github.com/microsoft/BitNet) 42020★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 86 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 93766★ |
| 182 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 83948★ |
| 107 | [Learning Heterogeneous Tactile Representation for General Dexterous Manipulation](https://huggingface.co/papers/2611.12806) | LingBot-Touch is a tactile foundation model that learns a unified, extensible representation across heterogeneous tactile sensors, yielding… | 💡 [Robbyant/lingbot-touch](https://github.com/Robbyant/lingbot-touch) 766★ |
| 38 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 36243★ |
| 72 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 36245★ |
| 78 | [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://huggingface.co/papers/2504.19413) | Mem0, a memory-centric architecture with graph-based memory, enhances long-term conversational coherence in LLMs by efficiently extracting,… | [mem0ai/mem0](https://github.com/mem0ai/mem0) 69220★ |
| 157 | [ARIS: Autonomous Research via Adversarial Multi-Agent Collaboration](https://huggingface.co/papers/2605.03042) | ARIS is an open-source research harness that uses cross-model adversarial collaboration to ensure reliable long-term research outcomes throu… | [wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) 19444★ |
| 34 | [HuggingFace's Transformers: State-of-the-art Natural Language Processing](https://huggingface.co/papers/1910.03771) | Transformers library provides state-of-the-art Transformer architectures and pretrained models for natural language processing tasks with a… | [huggingface/transformers](https://github.com/huggingface/transformers) 169234★ |
| 15 | [MovieRoll: A Systematic Framework for Rolling Out Long-Form Videos](https://huggingface.co/papers/2611.21339) | Streaming video generation must sustain quality beyond the training horizon while handling self-generated history and growing cache costs. | 💡 [Tencent-Hunyuan/MovieRoll](https://github.com/Tencent-Hunyuan/MovieRoll) 83★ |
| 66 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 47978★ |
| 20 | [e-means: outperforming k-means (in one-tenth the epochs)](https://huggingface.co/papers/2611.09501) | Lloyd's k-means algorithm is a long-running standard for clustering, with applications in data analysis, retrieval, quantization and data cu… | [facebookresearch/faiss](https://github.com/facebookresearch/faiss) 41807★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 20 | [voice isolator](https://huggingface.co/inworld/voice-isolator) | audio-to-audio | 117 | 1 |
| 23 | [smolvlm2 256m video](https://huggingface.co/HuggingFaceTB/SmolVLM2-256M-Video-Instruct) | image-text-to-text | 227 | 1 |
| 28 | [rumble 2 flash](https://huggingface.co/Reson8/Rumble-2-Flash) | automatic-speech-recognition | 107 | 1 |
| 35 | [qwen3.5 qwen3.8 draft](https://huggingface.co/nvidia/Qwen3.5-4B-Qwen3.8-27B-Draft) | text-generation | 90 | 1 |
| 40 | [daisyrose](https://huggingface.co/RadixArk/DaisyRose-27B) | image-text-to-text | 87 | 1 |
| 45 | [hy4 flash](https://huggingface.co/AngelSlim/Hy4-flash-GGUF) | — | 61 | 1 |
| 49 | [tessera small](https://huggingface.co/thejagstudio/tessera-small) | text-to-image | 66 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 193 | 64 | [Codeberg's domain suddenly disappeared from their account, site is unreachable](https://social.anoxinon.de/@Codeberg/117636454915265360) | `vcs` | [讨论](https://lobste.rs/s/spmgsd/codeberg_s_domain_suddenly_disappeared) |
| 70 | 13 | [nginx2root](https://xint.io/blog/nginx2root-remote-code-execution) | `security` | [讨论](https://lobste.rs/s/wj2svg/nginx2root) |
| 28 | 12 | [Java4Shell is a reason to use Java](https://mccue.dev/pages/11-18-26-java4shell) | `java` `security` | [讨论](https://lobste.rs/s/a1uff5/java4shell_is_reason_use_java) |
| 21 | 5 | [Upcoming Critical PHP Security Release (18 Nov 2026)](https://www.php.net/index.php#2026-11-18-1) | `php` `security` | [讨论](https://lobste.rs/s/zr0hkw/upcoming_critical_php_security_release) |
| 37 | 27 | [Windows 11 collects data on which coding agents and dev tools you use](https://xusheng.dev/posts/windows-coding-agent-telemetry/) | `practices` `privacy` `security` | [讨论](https://lobste.rs/s/cwxmdw/windows_11_collects_data_on_which_coding) |
| 26 | 5 | [How I made a custom game engine for Satelital](https://spectralorbit.com/blog/satelital_game_engine) | `games` `graphics` | [讨论](https://lobste.rs/s/eklpkn/how_i_made_custom_game_engine_for) |
| 25 | 1 | [The Magic of Partial Evaluation](https://jimmyhmiller.com/magic-of-partial-evaluation) | `plt` | [讨论](https://lobste.rs/s/silxsl/magic_partial_evaluation) |
| 8 | 0 | [Security advisories: multiple vulnerabilities in Regexp and String case conversion](https://www.ruby-lang.org/en/news/2026/11/18/multiple-vulnerabilities-in-regexp-and-string/) | `ruby` `security` | [讨论](https://lobste.rs/s/hsmtyg/security_advisories_multiple) |
| 19 | 14 | [Solid 2.0](https://www.solidjs.com/blog/solid-2-0-the-long-hold) | `javascript` `web` | [讨论](https://lobste.rs/s/dpvrbv/solid_2_0) |
| 6 | 0 | [Stricter checks for uploaded distributions on PyPI](https://blog.pypi.org/posts/2026-11-18-stricter-checks-for-uploaded-sdists/) | `python` | [讨论](https://lobste.rs/s/kfpoos/stricter_checks_for_uploaded) |
| 13 | 1 | [IPv6 delegation, an unusually subtle failure mode](https://savyasacheejha.com/posts/why-odhcpd/) | `linux` `networking` | [讨论](https://lobste.rs/s/inj0dn/ipv6_delegation_unusually_subtle) |
| 1 | 0 | [Morty — Continue your AI agent from any browser](https://morty.build/) | `building-ai-tooling` `show` | [讨论](https://lobste.rs/s/k2gpni/morty_continue_your_ai_agent_from_any) |
| 9 | 2 | [markdownWeb](https://demo.bonbonweb.org/) | `web` | [讨论](https://lobste.rs/s/w78jvi/markdownweb) |
| 56 | 30 | [Java4Shell: Write once, RCE everywhere](https://calif.io/java4shell/) | `java` `security` | [讨论](https://lobste.rs/s/g0bf9i/java4shell_write_once_rce_everywhere) |
| 6 | 0 | [sysdeck: Raycast for Linux & BSD](https://xn--gckvb8fzb.com/sysdeck-raycast-for-linux-bsd/) | `freebsd` `linux` `netbsd` `openbsd` `release` | [讨论](https://lobste.rs/s/l70xc9/sysdeck_raycast_for_linux_bsd) |
| 114 | 61 | [Actual curl rewrites in rust](https://daniel.haxx.se/blog/2026/11/17/actual-curl-rewrites-in-rust/) | `rust` | [讨论](https://lobste.rs/s/1dj9w1/actual_curl_rewrites_rust) |
| 28 | 1 | [FreeBSD GUS](https://gregoire.dev/writing/gus/) | `freebsd` `mac` | [讨论](https://lobste.rs/s/bhfexs/freebsd_gus) |
| 8 | 11 | [Stacked diffs with Maiao](https://entropicthoughts.com/stacked-diffs-with-maiao) | `vcs` | [讨论](https://lobste.rs/s/bjmwt6/stacked_diffs_with_maiao) |
| 3 | 0 | [Incidents in the news](https://surfingcomplexity.blog/2026/11/18/incidents-in-the-news/) | `security` | [讨论](https://lobste.rs/s/gpqw7o/incidents_news) |
| 5 | 0 | [Reversing the Next-Page Prefetcher in Skylake-X](https://devsh0.github.io/microarchitecture,/intel,/computer-architecture/2026/11/17/reversing-the-next-page-prefetcher-in-skylake-x.html) | `hardware` `performance` | [讨论](https://lobste.rs/s/1tcjtd/reversing_next_page_prefetcher_skylake_x) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 84 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 66 | 47 | 71% | — |
| 🔴 先核对 | 38 | 21 | 55% | — |
| 🟡 在降温 | 6 | 0 | 0% | — |
| 🔵 已被发现 | 3 | 1 | 33% | — |
| 💤 不活跃 | 1 | 0 | 0% | — |
| 🟢 窗口内 | 20 | 9 | 45% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [Balanov/equal](https://github.com/Balanov/equal) | 2026-11-05 | 🔴 先核对 | 151 | 57 | 0 | 没起来 |
| [govijr/terminal-mac](https://github.com/govijr/terminal-mac) | 2026-11-05 | 🚀 爆发 | 1673 | 2863 | 1 | 没起来 |
| [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | 2026-11-05 | 🔴 先核对 | 782 | 1990 | 0 | ✅ 起来了 |
| [worldonlyu/Google_AI_Pro_2Year_ZeroCost_Auto](https://github.com/worldonlyu/Google_AI_Pro_2Year_ZeroCost_Auto) | 2026-11-05 | 🚀 爆发 | 1016 | 0 | 0 | 仓库没了 |
| [wquguru/cicada](https://github.com/wquguru/cicada) | 2026-11-05 | 🚀 爆发 | 1277 | 2416 | 0 | 没起来 |

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
