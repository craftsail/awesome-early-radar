# early-radar 选题雷达 · 2026-11-21

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 98 个，细查前 20 个 · 比上次 = 和 2026-11-20 那次比 · 生成于 2026-11-21 06:45 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 4 个 · Show HN ✅ 27 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 4 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 4 个 · 🟡 在降温 11 个 · 🔵 已被发现 1 个 · 💤 不活跃 0 个 · 🔴 先核对 4 个
- **今天新出现 2 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [erkamyaman/rust-anything](https://github.com/erkamyaman/rust-anything) 平均每天 +1434，见 [爆发](#爆发)
- **复盘**：🚀 爆发 51/70 · 🔴 先核对 21/38 · 🟡 在降温 0/6 · 🔵 已被发现 1/3 · 💤 不活跃 0/1 · 🟢 窗口内 10/22（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) — Agent skill for hill-climbing local LLM serving speed (decod…（近 7 天 +1378，刚发布一周内）
  - [huggingface/pybot](https://github.com/huggingface/pybot) — PyBot: a chatbot written in pure Python by a swarm of agents…（近 7 天 +1047，比前 7 天快 523.5 倍，在加速）
  - [Lemxy/WinRust](https://github.com/Lemxy/WinRust) — Windows shell replacement in Rust: taskbar, file manager, NT…（近 7 天 +795，刚发布一周内）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 25 个（star 合计 29005），代表：[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DIYgod/pinky](https://github.com/DIYgod/pinky)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：4 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: DeepSeek V3 in ~200 lines of pure Jax](https://github.com/Vaibhaav-Tiwari/deepseek-v3-jax) — 276 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [erkamyaman/rust-anything](https://github.com/erkamyaman/rust-anything) | 6845 | 1434 | +1256 | 4.8 | [1](https://news.ycombinator.com/item?id=50558549) | rust anything · erkamyaman rust anything · erkam rust anything | Rewrite your whole app in Rust, one piece at a time, checked… |
| [krisgfx9/Wireless-Device-Battery-Monitor](https://github.com/krisgfx9/Wireless-Device-Battery-Monitor) | 5433 | 1215 | +661 | 4.5 | [1](https://news.ycombinator.com/item?id=50543820) | wireless device battery monitor · krisgfx9 wireless device battery monitor · krisgfx wireless device battery monitor | Show the battery level of wireless mice, headsets, keyboards… |
| [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon) | 1854 | 1111 | +980 | 1.7 | — | blender ai mcp addon · bookwjitchieni1986 blender ai mcp addon | AI assistant and MCP server for Blender: visual chat, scene… |
| [simplexai-labs/linger](https://github.com/simplexai-labs/linger) | 3031 | 273 | +923 | 11.1 | — | linger · simplexai-labs linger · simplexai linger | Linger is An Open-Source Personal Agent That Runs Fully on Y… |
| [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) | 1351 | 725 | +755 | 1.9 | — | neonclipping · iamajmeena neonclipping | Paste a link, get captioned 9:16 clips in ~2 min. Free, loca… |
| [imxieyi/Kernarium](https://github.com/imxieyi/Kernarium) | 2151 | 157 | +752 | 13.7 | [1](https://news.ycombinator.com/item?id=50580281) | kernarium · imxieyi kernarium · yi kernarium | Run real Linux kernel natively on iOS |
| [huami1314/GestaltX](https://github.com/huami1314/GestaltX) | 8667 | 719 | +83 | 12.1 | — | gestaltx · huami1314 gestaltx | An MobileGestalt editor for iOS 27.x, featuring region-code… |
| [gylive/google-ultra](https://github.com/gylive/google-ultra) | 2551 | 663 | +73 | 3.8 | — | google ultra · gylive google ultra |  |
| 🆕 [XinaTian/MROffice](https://github.com/XinaTian/MROffice) | 1121 | 106 | +656 | 10.5 | [4](https://news.ycombinator.com/item?id=50546074) | mroffice · xinatian mroffice · xina mroffice | MR Office: open-source document, spreadsheet, presentation,… |
| [deepseek-ai/chat-demo](https://github.com/deepseek-ai/chat-demo) | 5150 | 576 | +86 | 8.9 | [2](https://news.ycombinator.com/item?id=50509966) | chat demo · deepseek-ai chat demo · deepseek chat demo | Chat Demo |
| 🆕 [hatsunemiku-ai/google-one-tools](https://github.com/hatsunemiku-ai/google-one-tools) | 381 | 381 | — | 1 | — | google one tools · hatsunemiku-ai google one tools |  |
| [ersinkoc/phonebox](https://github.com/ersinkoc/phonebox) | 4313 | 318 | +370 | 13.6 | — | phonebox · ersinkoc phonebox · ersin phonebox | Turn an old Android phone into a customizable desk panel and… |
| [Hut-hzf/ung220z-tool](https://github.com/Hut-hzf/ung220z-tool) | 2081 | 358 | +242 | 5.8 | — | ung220z tool · hut-hzf ung220z tool | ung220z-tool 是一个针对 UNG220Z（九联/Unionman 中国移动光猫）的一键凭据提取工具，仅限在你… |
| [MSNightmare/FastUnlock](https://github.com/MSNightmare/FastUnlock) | 602 | 343 | +175 | 1.8 | [8](https://news.ycombinator.com/item?id=50560543) | fastunlock · msnightmare fastunlock · birb fastunlock | FastUnlock : Windows Narrator LockScreen Bypass 0day Vulnera… |
| 🆕 [CocoSgt/riemann-hypothesis-lean](https://github.com/CocoSgt/riemann-hypothesis-lean) | 342 | 342 | — | 1 | — | riemann hypothesis lean · cocosgt riemann hypothesis lean | Mirror of Levent Alpöge's Lean proof of the Riemann Hypothes… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 86.7 | 🟢 窗口内 | [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) | Python | 1378 | +102 | +1378 | +0 | `········▆█▃▂▂·` | 4 | — | — |
| 2 | 83.5 | 🟢 窗口内 | [huggingface/pybot](https://github.com/huggingface/pybot) | Python | 1049 | +73 | +1047 | +2 | `····▁···▇█▃▃▂·` | 8 | [7](https://news.ycombinator.com/item?id=50517920) | — |
| 3 | 80.2 | 🟢 窗口内 | [Lemxy/WinRust](https://github.com/Lemxy/WinRust) | Rust | 795 | +302 | +795 | +0 | `·········▃▂█▇·` | 3 | — | — |
| 4 | 79.5 | 🆕 🟢 窗口内 | [boringmarketer/boring-marketing-skills](https://github.com/boringmarketer/boring-marketing-skills) | Python | 750 | +25 | +750 | +0 | `········██▃▂▂·` | 4 | — | — |
| 5 | 62.5 | 🟡 在降温 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Rust | 2382 | +362 | +519 | +573 | `▃▃▂▂▃▂▂▁▂▂▂▂█·` | 19 | — | — |
| 6 | 61.1 | 🟡 在降温 | [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) | TypeScript | 1864 | +97 | +448 | +1416 | `···██▂▂▃▂▂▁▁▂·` | 12 | — | — |
| 7 | 60.9 | 🟡 在降温 | [DIYgod/pinky](https://github.com/DIYgod/pinky) | Go | 2610 | +52 | +442 | +1948 | `█▄▃▂▂▂▂▂▂▂▂▂▁·` | 14 | — | — |
| 8 | 60.3 | 🟡 在降温 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki) | Swift | 1704 | +28 | +414 | +756 | `▄█▅▃▃▅▇▅▆▃▂▄▂·` | 15 | — | — |
| 9 | 57.1 | 🟡 在降温 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode) | Python | 2819 | +30 | +300 | +1445 | `█▄▂▃▂▂▂▂▂▂▂▂▁·` | 17 | — | — |
| 10 | 56.7 | 🟡 在降温 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 2778 | +29 | +288 | +431 | `▆█▆█▆▄▆▆▄▆▅▇▃·` | 26 | [2](https://news.ycombinator.com/item?id=50272846) | — |
| 11 | 54.2 | 🟡 在降温 | [alexeyw/lot-map](https://github.com/alexeyw/lot-map) | TypeScript | 1067 | +38 | +226 | +840 | `··▄█▅▄▃▂▂▂▂▁▂·` | 11 | — | — |
| 12 | 53.3 | 🟡 在降温 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 2705 | +18 | +205 | +347 | `▇▇▆▄▃▅█▅▄▄▆▄▂·` | 26 | — | — |
| 13 | 52.3 | 🟡 在降温 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | TypeScript | 2688 | +22 | +186 | +422 | `▅▄▄█▃▂▂▂▂▃▃▂▂·` | 20 | — | — |
| 14 | 49.3 | 🟡 在降温 | [lexifina/global-law](https://github.com/lexifina/global-law) | HTML | 2152 | +29 | +138 | +150 | `▅▄▅▄▄▄▇█▅▅▃▅▅·` | 23 | [1](https://news.ycombinator.com/item?id=50418651) | — |
| 15 | 45.2 | 🔴 先核对 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon) | — | 1854 | +980 | +1854 | +0 | `···········██·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 16 | 45 | 🟡 在降温 | [voyager-so/vork](https://github.com/voyager-so/vork) | Rust | 1668 | +19 | +89 | +616 | `█▅▂▄▂▂▃▁▁▂▁▁▂·` | 15 | [8](https://news.ycombinator.com/item?id=50396650) | — |
| 17 | 43.3 | 🔴 先核对 | [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) | Python | 1351 | +755 | +1350 | +0 | `···········██·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 36.6 | 🔴 先核对 | [Illson/RustText](https://github.com/Illson/RustText) | C# | 447 | +33 | +447 | +0 | `·········█▅▂▂·` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 35.7 | 🔵 已被发现 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt) | TypeScript | 2794 | +144 | +1268 | +1526 | `···█▇▄▃▃▃▃▅▃▃·` | 10 | [307](https://news.ycombinator.com/item?id=50454625) | — |
| 20 | 30.2 | 🆕 🔴 先核对 | [prajwaljeevan50-web/openclaw-personal-workspace](https://github.com/prajwaljeevan50-web/openclaw-personal-workspace) | JavaScript | 152 | — | +152 | +0 | `············█·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 1093 | 30 | 44907 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) |
| `mcp` | 226 | 30 | 32075 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[DIYgod/pinky](https://github.com/DIYgod/pinky)、[lexifina/global-law](https://github.com/lexifina/global-law) |
| `rust` | 198 | 30 | 28507 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker)、[s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) |
| `local-first` | 76 | 30 | 15377 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[yjid/kensaku](https://github.com/yjid/kensaku) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 25 | 29005 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DIYgod/pinky](https://github.com/DIYgod/pinky) |
| `ai-agents` | 22 | 20196 | [daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[yjid/kensaku](https://github.com/yjid/kensaku)、[agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) |
| `codex` | 19 | 20151 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[ZiChuanLan/agent-purge](https://github.com/ZiChuanLan/agent-purge) |
| `mcp-server` | 15 | 11482 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) |
| `model-context-protocol` | 15 | 11422 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[JosssphZhou/poki](https://github.com/JosssphZhou/poki)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) |
| `windows` | 13 | 11444 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[yjid/kensaku](https://github.com/yjid/kensaku)、[Renly1994/xiaotang-daozai](https://github.com/Renly1994/xiaotang-daozai) |
| `agent-skills` | 11 | 14597 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) |
| `developer-tools` | 10 | 3599 | [alexeyw/lot-map](https://github.com/alexeyw/lot-map)、[jazzenchen/agent-hud-open](https://github.com/jazzenchen/agent-hud-open)、[chutingyean/Agent-Cockpit](https://github.com/chutingyean/Agent-Cockpit) |
| `macos` | 9 | 8778 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[simpsoka/zigzag](https://github.com/simpsoka/zigzag) |
| `blender` | 8 | 5432 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[racdeufindurch198812/Blender-AI-MCP-Studio](https://github.com/racdeufindurch198812/Blender-AI-MCP-Studio)、[credoksopho1984/blender-ai-copilot-studio](https://github.com/credoksopho1984/blender-ai-copilot-studio) |
| `blender-addon` | 8 | 5432 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[racdeufindurch198812/Blender-AI-MCP-Studio](https://github.com/racdeufindurch198812/Blender-AI-MCP-Studio)、[credoksopho1984/blender-ai-copilot-studio](https://github.com/credoksopho1984/blender-ai-copilot-studio) |
| `blender-ai` | 8 | 5432 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[racdeufindurch198812/Blender-AI-MCP-Studio](https://github.com/racdeufindurch198812/Blender-AI-MCP-Studio)、[credoksopho1984/blender-ai-copilot-studio](https://github.com/credoksopho1984/blender-ai-copilot-studio) |

**语言分布**：Rust 27 · Python 20 · TypeScript 18 · JavaScript 8 · Go 5 · HTML 3 · Dart 2 · Swift 2

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) · 🟢 窗口内 · 86.7 分

> Agent skill for hill-climbing local LLM serving speed (decode, speculative decoding, prefill, KV, startup, TTFT) on any hardware and quantization

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1378 | +1378 | +0 | 124 | 7 | Python | MIT | 11-16（4 天前） | 4 天前 |

- **近 14 天每天新增**：`········▆█▃▂▂·` 0 0 0 0 0 0 0 0 404 579 180 113 102 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `benchmarking` `claude-code` `inference` `llm` `speculative-decoding`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [huggingface/pybot](https://github.com/huggingface/pybot) · 🟢 窗口内 · 83.5 分

> PyBot: a chatbot written in pure Python by a swarm of agents. No weights, no training, just rules.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1049 | +1047 | +2 | 114 | 11 | Python | Apache-2.0 | 11-12（8 天前） | 4 天前 |

- **近 14 天每天新增**：`····▁···▇█▃▃▂·` 0 0 0 0 2 0 0 0 325 408 134 114 66 0
- **势头**：比前 7 天快 523.5 倍，在加速
- **HN**：发过 2 次，最高 7 分（[讨论](https://news.ycombinator.com/item?id=50517920)）
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [Lemxy/WinRust](https://github.com/Lemxy/WinRust) · 🟢 窗口内 · 80.2 分

> Windows shell replacement in Rust: taskbar, file manager, NTFS search, task manager, disk cleaner. One installer exe.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 795 | +795 | +0 | 40 | 31 | Rust | Apache-2.0 | 11-17（3 天前） | 今天 |

- **近 14 天每天新增**：`·········▃▂█▇·` 0 0 0 0 0 0 0 0 0 82 74 352 287 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. 🆕 [boringmarketer/boring-marketing-skills](https://github.com/boringmarketer/boring-marketing-skills) · 🟢 窗口内 · 79.5 分

> 32 free marketing skills for your AI agent: research, positioning, copy, pages, SEO, AI search, ads, email and content, plus a deep local-business pack. MIT.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 750 | +750 | +0 | 274 | 1 | Python | MIT | 11-16（4 天前） | 3 天前 |

- **近 14 天每天新增**：`········██▃▂▂·` 0 0 0 0 0 0 0 0 283 303 91 49 24 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-agents` `claude-code` `codex` `copywriting` `local-seo` `marketing` `seo`
- **主页**：<https://boringmarketing.com>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) · 🟡 在降温 · 62.5 分

> Blazing-fast native notes app and rich-text editor for macOS, Windows, and Linux. Built with Rust + GPUI. Local-first and beautifully designed.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2382 | +519 | +573 | 201 | 82 | Rust | MIT | 11-01（19 天前） | 今天 |

- **近 14 天每天新增**：`▃▃▂▂▃▂▂▁▂▂▂▂█·` 125 116 52 62 87 64 67 21 26 47 34 29 362 0
- **势头**：只有前 7 天的 91%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://quiet.md>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 6. [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) · 🟡 在降温 · 61.1 分

> Open-source, self-hosted Slack alternative where your team and AI agents work together in channels and DMs. Agents run on Claude, ChatGPT/Codex, Gemini or Grok, with MCP tools, their own computer and browser, routines, memory and approvals. Web, desktop and phone apps. Docker Compose + Postgres. AGPL-3.0.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1864 | +448 | +1416 | 357 | 388 | TypeScript | AGPL-3.0 | 11-09（12 天前） | 今天 |

- **近 14 天每天新增**：`···██▂▂▃▂▂▁▁▂·` 0 0 0 606 635 108 67 148 83 46 34 44 93 0
- **势头**：只有前 7 天的 32%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agentic-ai` `ai-agents` `browser-automation` `chat` `claude` `claude-code` `codex` `collaboration` `computer-use` `docker-compose` `gemini` `grok` `human-in-the-loop` `llm` `mcp` `multi-agent` `openai` `self-hosted` `slack-alternative` `team-chat`
- **主页**：<https://agentes.chat>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 7. [DIYgod/pinky](https://github.com/DIYgod/pinky) · 🟡 在降温 · 60.9 分

> Let AI use your iPhone or Android phone, with you in the loop: any MCP agent from macOS, Windows or Linux, or Pinky itself, right on the phone.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2610 | +442 | +1948 | 274 | 17 | Go | Apache-2.0 | 11-06（14 天前） | 今天 |

- **近 14 天每天新增**：`█▄▃▂▂▂▂▂▂▂▂▂▁·` 901 419 219 142 129 67 71 78 73 92 82 68 49 0
- **势头**：只有前 7 天的 23%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `android` `claude-code` `ios` `iphone` `mcp` `mcp-server` `phone-automation`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [JosssphZhou/poki](https://github.com/JosssphZhou/poki) · 🟡 在降温 · 60.3 分

> Poki uses your iPhone like you do. An open-source agent app that runs on your iPhone, reads the screen, and taps, types and swipes in real apps with your own model account.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1704 | +414 | +756 | 266 | 111 | Swift | AGPL-3.0 | 11-05（15 天前） | 今天 |

- **近 14 天每天新增**：`▄█▅▃▃▅▇▅▆▃▂▄▂·` 90 191 120 48 48 101 158 98 145 46 28 71 26 0
- **势头**：只有前 7 天的 55%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `ai-assistant` `automation` `claude-code` `computer-use` `gui-agent` `ios` `ios-app` `iphone` `llm` `mcp` `mobile-agent` `model-context-protocol` `open-source` `phone-agent` `swift` `voice-assistant`
- **主页**：<https://poki.bot>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [sarpstar/cinecode](https://github.com/sarpstar/cinecode) · 🟡 在降温 · 57.1 分

> Films made with code. Short films, long YouTube videos, ads, explainers and music videos: an AI coding agent writes the script, builds every frame in code, designs the sound and hands you an MP4.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2819 | +300 | +1445 | 474 | 14 | Python | MIT | 11-03（17 天前） | 8 天前 |

- **近 14 天每天新增**：`█▄▂▃▂▂▂▂▂▂▂▂▁·` 615 265 119 172 117 86 71 57 47 63 50 53 30 0
- **势头**：只有前 7 天的 21%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://x.com/sarpstar>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) · 🟡 在降温 · 56.7 分

> UEFI pre-driver NVIDIA GPU unlocker for Windows Linux Hackintosh and all EFI-bootable system (Rust): SEC2 scrubber -> FWSEC/WPR2 -> signed Booter -> V67 four-write payload, read-back verified. Verified on most RTX 20 30 40 Series.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2778 | +288 | +431 | 254 | 18 | Rust | GPL-2.0 | 10-26（26 天前） | 今天 |

- **近 14 天每天新增**：`▆█▆█▆▄▆▆▄▆▅▇▃·` 62 80 61 77 55 38 58 62 33 54 46 65 28 0
- **势头**：只有前 7 天的 67%，在减速
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50272846)）
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon) — 一天进了一半以上的 star，但 HN 上没火过
- [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) — 一天进了一半以上的 star，但 HN 上没火过
- [Illson/RustText](https://github.com/Illson/RustText) — 一天进了一半以上的 star，但 HN 上没火过
- [prajwaljeevan50-web/openclaw-personal-workspace](https://github.com/prajwaljeevan50-web/openclaw-personal-workspace) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 276 | 30 | [Show HN: DeepSeek V3 in ~200 lines of pure Jax](https://github.com/Vaibhaav-Tiwari/deepseek-v3-jax) | [HN](https://news.ycombinator.com/item?id=50497589) |
| 269 | 56 | [Show HN: I made an audio-to-MIDI model 60x more efficient](https://kobi.music/research/dettato) | [HN](https://news.ycombinator.com/item?id=50526023) |
| 250 | 93 | [Show HN: ExitPath – Open-source ways out of Slack, Notion and Microsoft 365](https://exitpath-ruddy.vercel.app/) | [HN](https://news.ycombinator.com/item?id=50547980) |
| 238 | 60 | [Show HN: Take Voyager 1 apart, down to a single memory chip](https://rshekhar.com/voyager/) | [HN](https://news.ycombinator.com/item?id=50548161) |
| 235 | 119 | [Show HN: Cornhole News – A Hacker News inspired site for news across the Midwest](https://cornholenews.news) | [HN](https://news.ycombinator.com/item?id=50561515) |
| 211 | 40 | [Show HN: Alloy CSS, dialogs, menus and tabs that work with JavaScript off](https://alloyhtml.com/example.html) | [HN](https://news.ycombinator.com/item?id=50532385) |
| 173 | 44 | [Show HN: A terminal-native idle factory game, written in Rust with ratatui](https://gitlab.com/snipedbywifi/terminactory) | [HN](https://news.ycombinator.com/item?id=50497132) |
| 154 | 43 | [Show HN: Mastra Factory, the open-source software factory we use to build Mastra](https://news.ycombinator.com/item?id=50548660) | [HN](https://news.ycombinator.com/item?id=50548660) |
| 152 | 109 | [Show HN: Tinnitus frequency finder and audio notch tool](https://trynotched.com/find) | [HN](https://news.ycombinator.com/item?id=50541568) |
| 148 | 71 | [Show HN: Type Fighter 2](https://typefighter2.com/) | [HN](https://news.ycombinator.com/item?id=50544821) |
| 127 | 33 | [Show HN: Fast deterministic natural language search for OpenStreetMap data](https://hippomaps.ch/?q=cafes+by+the+Limmat+100+m+from+the+lake+in+zurich#map=15.02/47.36708/8.54935) | [HN](https://news.ycombinator.com/item?id=50561199) |
| 123 | 75 | [Show HN: Zigzag, a native Mac browser for people leaving Arc](https://github.com/ZigaoWang/zigzag) | [HN](https://news.ycombinator.com/item?id=50496787) |
| 123 | 15 | [Show HN: Open-source, real-time object tracking for live video feeds](https://github.com/aryamandarda/tamserve) | [HN](https://news.ycombinator.com/item?id=50523377) |
| 119 | 92 | [Show HN: Foolscap – a writing app that reads your book and never writes for you](https://foolscap.works/) | [HN](https://news.ycombinator.com/item?id=50559749) |
| 109 | 37 | [Show HN: Agweb – a browser for agents that stays out of your way](https://github.com/paul-nameless/agweb) | [HN](https://news.ycombinator.com/item?id=50497147) |
| 96 | 24 | [Show HN: OpenComputer – an open source alternative to Devin](https://github.com/diggerhq/opencomputer) | [HN](https://news.ycombinator.com/item?id=50581403) |
| 89 | 21 | [Show HN: The Last Complication, a Zachtronics-style watchmaking puzzle game](https://lastcomplication.com/) | [HN](https://news.ycombinator.com/item?id=50511718) |
| 86 | 39 | [Show HN: Fursoy – Out-of-order RV64IMAFDV core in SystemVerilog (Linux 6.6)](https://github.com/FURSOY/fursoy-cpu) | [HN](https://news.ycombinator.com/item?id=50497137) |
| 73 | 11 | [Show HN: An API for word timestamps from speech, 75% within 20ms](https://quebec.yarn.so) | [HN](https://news.ycombinator.com/item?id=50532515) |
| 72 | 36 | [Show HN: Sutra-OS – A self-hosted ontology platform](https://github.com/0nelight/sutra-os) | [HN](https://news.ycombinator.com/item?id=50525052) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 11 | [PaperOrchestra: A Multi-Agent Framework for Automated AI Research Paper Writing](https://huggingface.co/papers/2604.05018) | PaperOrchestra is a multi-agent framework that converts unstructured research materials into complete LaTeX manuscripts with literature synt… | [google-research/paper-orchestra](https://github.com/google-research/paper-orchestra) 5380★ |
| 28 | [Depth Pro 2: Sharp and Temporally Consistent Metric Monocular Depth](https://huggingface.co/papers/2611.26603) | A single scalable network estimates dense metric depth for images and video at native resolution, jointly improving metric accuracy, boundar… | 💡 [apple-aiml-research/ml-depth-pro-2](https://github.com/apple-aiml-research/ml-depth-pro-2) 205★ |
| 144 | [Gamer: A Generalist Vision-Language-Action Foundation Model for Long-Horizon Real-Time Game Agent](https://huggingface.co/papers/2611.18397) | Gamer is a generalist agent framework that integrates perception, memory, and multi-step reasoning, trained through continued pre-training,… | [RainBowLuoCS/Gamer](https://github.com/RainBowLuoCS/Gamer) 1152★ |
| 21 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 7850★ |
| 18 | [π^4: A Foundation Model for 4D Scene Geometry and Motion](https://huggingface.co/papers/2611.23144) | This unified foundation model enables the recovery of dense geometry, camera poses, and object tracking from diverse, uncalibrated observati… | 💡 [yyfz/Pi4](https://github.com/yyfz/Pi4) 391★ |
| 36 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 12140★ |
| 22 | [Bitnet.cpp: Efficient Edge Inference for Ternary LLMs](https://huggingface.co/papers/2502.11880) | Bitnet.cpp enhances edge inference for ternary LLMs using a novel mixed-precision matrix multiplication library, achieving significant speed… | [microsoft/BitNet](https://github.com/microsoft/BitNet) 42345★ |
| 169 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 123277★ |
| 70 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 24603★ |
| 78 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 87 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 93927★ |
| 39 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 36379★ |
| 73 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 36379★ |
| 185 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 84063★ |
| 40 | [WeMM-Video: Pushing the Frontiers of Open-Source Omni-Modal Video Understanding](https://huggingface.co/papers/2611.26409) | WeMM-Video is a family of Chinese-English bilingual omni-modal foundation models that unify text, image, audio, and video processing for joi… | 💡 [Tencent/WeMM-Video](https://github.com/Tencent/WeMM-Video) 55★ |
| 2 | [LittleBit: Ultra Low-Bit Quantization via Latent Factorization](https://huggingface.co/papers/2506.13771) | LittleBit is a novel method for extreme compression of large language models using low-rank factorization and multi-scale compensation, achi… | 💡 [SamsungLabs/LittleBit](https://github.com/SamsungLabs/LittleBit) 605★ |
| 40 | [Geometric Context Transformer for Streaming 3D Reconstruction](https://huggingface.co/papers/2604.14141) | LingBot-Map is a feed-forward 3D foundation model that reconstructs scenes from video streams using a geometric context transformer architec… | [robbyant/lingbot-map](https://github.com/robbyant/lingbot-map) 18883★ |
| 187 | [VibeVoice Technical Report](https://huggingface.co/papers/2508.19205) | VibeVoice synthesizes long-form multi-speaker speech using next-token diffusion and a highly efficient continuous speech tokenizer, achievin… | [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice) 57403★ |
| 35 | [HuggingFace's Transformers: State-of-the-art Natural Language Processing](https://huggingface.co/papers/1910.03771) | Transformers library provides state-of-the-art Transformer architectures and pretrained models for natural language processing tasks with a… | [huggingface/transformers](https://github.com/huggingface/transformers) 169327★ |
| 79 | [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://huggingface.co/papers/2504.19413) | Mem0, a memory-centric architecture with graph-based memory, enhances long-term conversational coherence in LLMs by efficiently extracting,… | [mem0ai/mem0](https://github.com/mem0ai/mem0) 69282★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 1 | [inkling 2 mini](https://huggingface.co/thinkingmachines/Inkling-2-Mini) | image-text-to-text | 1225 | 2 |
| 14 | [depthpro2](https://huggingface.co/apple/DepthPro2) | depth-estimation | 139 | 1 |
| 44 | [seedreamstyle h3 6k](https://huggingface.co/Nebsh/Seedreamstyle-H3-6K) | text-to-image | 78 | 1 |
| 49 | [qwen image 2.1](https://huggingface.co/Qwen/Qwen-Image-2.1) | text-to-image | 3697 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 76 | 33 | [Levent Alpoge Claims Proof of Riemann Hypothesis](https://alpo.ge/remark.pdf) | `math` `pdf` | [讨论](https://lobste.rs/s/cmifpg/levent_alpoge_claims_proof_riemann) |
| 57 | 10 | [Vim Classic 8.3.1 released](https://vim-classic.org/news/vim-8.3.1-released.html) | `editors` `release` | [讨论](https://lobste.rs/s/kkglbw/vim_classic_8_3_1_released) |
| 46 | 27 | [Announcing jj-musubi: live sync for Jujutsu](https://www.serpentine.com/posts/2026/announcing-jj-musubi/) | `release` `vcs` | [讨论](https://lobste.rs/s/tj1j4b/announcing_jj_musubi_live_sync_for) |
| 60 | 7 | [Removing binder.c](https://lwn.net/Articles/1102982/) | `android` `linux` `rust` | [讨论](https://lobste.rs/s/vo5jve/removing_binder_c) |
| 47 | 6 | [Internet Archive Staffers Are Unionizing](https://cwa-union.org/news/releases/internet-archive-workers-launch-union-campaign-communications-workers-america) | `culture` | [讨论](https://lobste.rs/s/o5coeq/internet_archive_staffers_are) |
| 17 | 3 | [Alice v0.6.0](https://www.alicecaml.org/blog/alice-v0-6-0/) | `ml` `release` | [讨论](https://lobste.rs/s/18c0lq/alice_v0_6_0) |
| 29 | 6 | [Visited links are purple](https://dbushell.com/2026/11/16/visited-links/) | `a11y` `web` | [讨论](https://lobste.rs/s/hcahbx/visited_links_are_purple) |
| 24 | 3 | [DreamCoder: coding harness and IDE from the author of Mastering Emacs](https://www.masteringemacs.org/article/announcing-dreamcoder) | `building-ai-tooling` `emacs` `historical` | [讨论](https://lobste.rs/s/ocdhli/dreamcoder_coding_harness_ide_from) |
| 40 | 9 | [Garage Door Spam](https://blog.harrison.page/garage-door-spam/) | `hardware` | [讨论](https://lobste.rs/s/tr5ghf/garage_door_spam) |
| 7 | 0 | [Verifying formal models of Raft implementations](https://antithesis.com/blog/2026/verifying-formal-models/) | `formalmethods` | [讨论](https://lobste.rs/s/4qcr3k/verifying_formal_models_raft) |
| 13 | 24 | [What are you doing this weekend?](https://lobste.rs/s/hneb5m) | `ask` `programming` | [讨论](https://lobste.rs/s/hneb5m/what_are_you_doing_this_weekend) |
| 38 | 4 | [Jujutsu Primer](https://ethanlowman.com/posts/jj-primer/) | `vcs` | [讨论](https://lobste.rs/s/i6dn7g/jujutsu_primer) |
| 2 | 0 | [Scaling Git horizontally: how we moved beyond Multi-Raft](https://enroute.sh/blog/scaling-horizontally-how-we-moved-beyond-multi-raft) | `vcs` | [讨论](https://lobste.rs/s/79x708/scaling_git_horizontally_how_we_moved) |
| 50 | 29 | [Design for Understandability](https://jschuster.org/blog/2026/11/19/design-for-understandability/) | `api` `plt` `practices` `slides` | [讨论](https://lobste.rs/s/qsrnot/design_for_understandability) |
| 15 | 0 | [Lisp Game Jam devlog: Polydraw](https://spritely.institute/news/lisp-game-jam-devlog-polydraw.html) | `games` `lisp` | [讨论](https://lobste.rs/s/irqtic/lisp_game_jam_devlog_polydraw) |
| 5 | 3 | [Slopstrap: Make your site look hastily vibecoded](https://slopstrap.mikelacher.com/l) | `css` `satire` `web` | [讨论](https://lobste.rs/s/1n8fzn/slopstrap_make_your_site_look_hastily) |
| 87 | 3 | [PostgreSQL 19 Released](https://www.postgresql.org/about/news/postgresql-19-released-3449/) | `databases` `release` | [讨论](https://lobste.rs/s/pqyuhk/postgresql_19_released) |
| 1 | 0 | [From Skiplists to B+ Trees: Making Valkey Sorted Sets More Memory Efficient](https://valkey.io/blog/from-skiplist-to-b+tree/) | `compsci` `databases` `performance` | [讨论](https://lobste.rs/s/ixhrac/from_skiplists_b_trees_making_valkey) |
| 202 | 76 | [We Need Smart People Who Give a Shit](https://violetpixel.com/blog/2026-11-17-we-need-smart-people-who-give-a-shit/) | `culture` | [讨论](https://lobste.rs/s/rzuasm/we_need_smart_people_who_give_shit) |
| 1 | 0 | [DNS Stamps Specification](https://dnscrypt.info/stamps-specifications/) | `networking` | [讨论](https://lobste.rs/s/1qkbmq/dns_stamps_specification) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 93 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 70 | 51 | 72% | — |
| 🔴 先核对 | 38 | 21 | 55% | — |
| 🟡 在降温 | 6 | 0 | 0% | — |
| 🔵 已被发现 | 3 | 1 | 33% | — |
| 💤 不活跃 | 1 | 0 | 0% | — |
| 🟢 窗口内 | 22 | 10 | 45% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [JenkinWoo/sheeridVerify](https://github.com/JenkinWoo/sheeridVerify) | 2026-11-07 | 🚀 爆发 | 1060 | 3974 | 0 | ✅ 起来了 |
| [Lowbetweentrim/crypto-portfolio-tracker](https://github.com/Lowbetweentrim/crypto-portfolio-tracker) | 2026-11-07 | 🔴 先核对 | 425 | 0 | 0 | 仓库没了 |
| [Minireel/HGhub](https://github.com/Minireel/HGhub) | 2026-11-07 | 🚀 爆发 | 1804 | 10488 | 0 | ✅ 起来了 |
| [sqlpxc/airhand](https://github.com/sqlpxc/airhand) | 2026-11-07 | 🟢 窗口内 | 627 | 1404 | 0 | ✅ 起来了 |

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
