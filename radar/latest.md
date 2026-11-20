# early-radar 选题雷达 · 2026-11-20

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 99 个，细查前 20 个 · 比上次 = 和 2026-11-19 那次比 · 生成于 2026-11-20 06:50 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 3 个 · Show HN ✅ 25 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 3 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 3 个 · 🟡 在降温 10 个 · 🔵 已被发现 2 个 · 💤 不活跃 0 个 · 🔴 先核对 5 个
- **今天新出现 5 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [erkamyaman/rust-anything](https://github.com/erkamyaman/rust-anything) 平均每天 +1479，见 [爆发](#爆发)
- **复盘**：🚀 爆发 49/68 · 🔴 先核对 21/38 · 🟡 在降温 0/6 · 🔵 已被发现 1/3 · 💤 不活跃 0/1 · 🟢 窗口内 9/21（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) — Agent skill for hill-climbing local LLM serving speed (decod…（近 7 天 +1276，刚发布一周内）
  - [huggingface/pybot](https://github.com/huggingface/pybot) — PyBot: a chatbot written in pure Python by a swarm of agents…（近 7 天 +974，比前 7 天快 487.0 倍，在加速）
  - [lexifina/global-law](https://github.com/lexifina/global-law) — The world's law in git: any provision, any country, any date…（近 7 天 +146，比前 7 天快 1.1 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 22 个（star 合计 26814），代表：[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DIYgod/pinky](https://github.com/DIYgod/pinky)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：5 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: DeepSeek V3 in ~200 lines of pure Jax](https://github.com/Vaibhaav-Tiwari/deepseek-v3-jax) — 276 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [erkamyaman/rust-anything](https://github.com/erkamyaman/rust-anything) | 5589 | 1479 | +1789 | 3.8 | [1](https://news.ycombinator.com/item?id=50558549) | rust anything · erkamyaman rust anything · erkam rust anything | Rewrite your whole app in Rust, one piece at a time, checked… |
| [krisgfx9/Wireless-Device-Battery-Monitor](https://github.com/krisgfx9/Wireless-Device-Battery-Monitor) | 4772 | 1374 | +604 | 3.5 | [1](https://news.ycombinator.com/item?id=50543820) | wireless device battery monitor · krisgfx9 wireless device battery monitor · krisgfx wireless device battery monitor | Show the battery level of wireless mice, headsets, keyboards… |
| 🆕 [simplexai-labs/linger](https://github.com/simplexai-labs/linger) | 2108 | 208 | +1348 | 10.1 | — | linger · simplexai-labs linger · simplexai linger | Linger is An Open-Source Personal Agent That Runs Fully on Y… |
| 🆕 [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon) | 874 | 874 | — | 1 | — | blender ai mcp addon · bookwjitchieni1986 blender ai mcp addon | AI assistant and MCP server for Blender: visual chat, scene… |
| [gylive/google-ultra](https://github.com/gylive/google-ultra) | 2478 | 869 | — | 2.9 | — | google ultra · gylive google ultra |  |
| 🆕 [imxieyi/Kernarium](https://github.com/imxieyi/Kernarium) | 1399 | 110 | +784 | 12.7 | — | kernarium · imxieyi kernarium · yi kernarium | Run real Linux kernel natively on iOS |
| [huami1314/GestaltX](https://github.com/huami1314/GestaltX) | 8584 | 776 | +150 | 11.1 | — | gestaltx · huami1314 gestaltx | An MobileGestalt editor for iOS 27.x, featuring region-code… |
| 🆕 [sourmitocand1987/VividFrame-GPU](https://github.com/sourmitocand1987/VividFrame-GPU) | 1184 | 729 | — | 1.6 | — | vividframe gpu · sourmitocand1987 vividframe gpu | Any source. One real-time GPU enhancement pipeline. · video… |
| 🆕 [bothaggsigym1988/frameglide](https://github.com/bothaggsigym1988/frameglide) | 1137 | 697 | — | 1.6 | — | frameglide · bothaggsigym1988 frameglide | From a 30 fps console stream to 60–120 fps on your PC. · fra… |
| 🆕 [Bodila51/gtavi-claudecode](https://github.com/Bodila51/gtavi-claudecode) | 1019 | 662 | — | 1.5 | — | gtavi claudecode · bodila51 gtavi claudecode · codila gtavi claudecode | Claude Code plugin that turns GTA 6 streams into paid vertic… |
| [deepseek-ai/chat-demo](https://github.com/deepseek-ai/chat-demo) | 5064 | 637 | +156 | 7.9 | [2](https://news.ycombinator.com/item?id=50509966) | chat demo · deepseek-ai chat demo · deepseek chat demo | Chat Demo |
| 🆕 [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) | 596 | 596 | — | 1 | — | neonclipping · iamajmeena neonclipping | Paste a link, get captioned 9:16 clips in ~2 min. Free, loca… |
| [ersinkoc/phonebox](https://github.com/ersinkoc/phonebox) | 3943 | 313 | +595 | 12.6 | — | phonebox · ersinkoc phonebox · ersin phonebox | Turn an old Android phone into a customizable desk panel and… |
| 🆕 [0marContreras/gta6recomp](https://github.com/0marContreras/gta6recomp) | 700 | 442 | — | 1.6 | — | gta6recomp · 0marcontreras gta6recomp · omar gta6recomp | A GTA VI PC Port |
| 🆕 [MSNightmare/FastUnlock](https://github.com/MSNightmare/FastUnlock) | 427 | 427 | — | 1 | [8](https://news.ycombinator.com/item?id=50560543) | fastunlock · msnightmare fastunlock · birb fastunlock | FastUnlock : Windows Narrator LockScreen Bypass 0day Vulnera… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 85.8 | 🟢 窗口内 | [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) | Python | 1276 | +118 | +1276 | +0 | `·········▆█▃▂·` | 3 | [1](https://news.ycombinator.com/item?id=50542464) | — |
| 2 | 82.6 | 🟢 窗口内 | [huggingface/pybot](https://github.com/huggingface/pybot) | Python | 976 | +115 | +974 | +2 | `·····▁···▇█▃▃·` | 7 | [7](https://news.ycombinator.com/item?id=50517920) | — |
| 3 | 63 | 🟡 在降温 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki) | Swift | 1676 | +66 | +544 | +692 | `▄▄█▅▃▃▅▇▅▆▃▂▃·` | 14 | — | — |
| 4 | 61.4 | 🟡 在降温 | [DIYgod/pinky](https://github.com/DIYgod/pinky) | Go | 2558 | +67 | +461 | +2095 | `▃█▄▃▂▂▂▂▂▂▂▂▂·` | 13 | — | — |
| 5 | 60.4 | 🟡 在降温 | [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) | TypeScript | 1767 | +37 | +418 | +1349 | `····██▂▂▃▂▂▁▁·` | 11 | [5](https://news.ycombinator.com/item?id=49789538) | — |
| 6 | 59.9 | 🟢 窗口内 | [lexifina/global-law](https://github.com/lexifina/global-law) | HTML | 2123 | +18 | +146 | +138 | `▅▅▄▅▄▄▄▇█▅▅▃▄·` | 22 | [1](https://news.ycombinator.com/item?id=50418651) | — |
| 7 | 58.3 | 🟡 在降温 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode) | Python | 2789 | +58 | +341 | +1958 | `██▄▂▃▂▂▂▂▂▂▂▂·` | 16 | — | — |
| 8 | 57.6 | 🟡 在降温 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 2749 | +67 | +317 | +453 | `█▆█▆█▆▄▆▆▄▆▅▇·` | 25 | [2](https://news.ycombinator.com/item?id=50272846) | — |
| 9 | 56 | 🆕 🟡 在降温 | [alexeyw/lot-map](https://github.com/alexeyw/lot-map) | TypeScript | 1029 | +17 | +270 | +758 | `···▄█▅▄▃▂▂▂▂▁·` | 10 | — | — |
| 10 | 55.6 | 🟡 在降温 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 2687 | +29 | +260 | +352 | `█▆▇▆▄▃▅█▅▄▄▅▃·` | 25 | — | — |
| 11 | 54.2 | 🟡 在降温 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Rust | 2020 | +30 | +224 | +598 | `▆█▇▄▄▆▅▅▂▂▄▃▃·` | 18 | — | — |
| 12 | 51.9 | 🟡 在降温 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | TypeScript | 2666 | +28 | +179 | +494 | `▅▅▄▄█▃▂▂▂▂▃▃▂·` | 19 | — | — |
| 13 | 48.1 | 🟡 在降温 | [voyager-so/vork](https://github.com/voyager-so/vork) | Rust | 1649 | +16 | +122 | +1010 | `█▅▃▂▃▁▁▂▁▁▁▁▁·` | 14 | [8](https://news.ycombinator.com/item?id=50396650) | — |
| 14 | 45.3 | 🆕 🔴 先核对 | [simplexai-labs/linger](https://github.com/simplexai-labs/linger) | TypeScript | 2108 | +1348 | +1896 | +212 | `··▁▁▁▁▁▁▁▁▁▃█·` | 10 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 15 | 38.3 | 🆕 🔴 先核对 | [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) | Python | 595 | — | +595 | +0 | `············█·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 16 | 37.3 | 🔵 已被发现 | [Dodaios/ste80-humanizer](https://github.com/Dodaios/ste80-humanizer) | Python | 997 | +84 | +503 | +493 | `··█▇▄▃▂▆▄▃▂▇▄·` | 10 | [114](https://news.ycombinator.com/item?id=50429144) | — |
| 17 | 37.2 | 🆕 🔴 先核对 | [Lemxy/WinRust](https://github.com/Lemxy/WinRust) | Rust | 493 | — | +493 | +0 | `··········▃▃█·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 35.9 | 🔵 已被发现 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt) | TypeScript | 2650 | +185 | +1318 | +1332 | `····█▇▄▃▃▃▃▅▃·` | 9 | [307](https://news.ycombinator.com/item?id=50454625) | — |
| 19 | 20.3 | 🆕 🔴 先核对 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon) | — | 874 | — | +874 | +0 | `············█·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1% |
| 20 | 18.1 | 🔴 先核对 | [Illson/RustText](https://github.com/Illson/RustText) | C# | 414 | -225 | +414 | +0 | `··········█▄▂·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过；没有描述 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 1098 | 30 | 48011 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) |
| `mcp` | 241 | 30 | 31235 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[DIYgod/pinky](https://github.com/DIYgod/pinky)、[lexifina/global-law](https://github.com/lexifina/global-law) |
| `rust` | 196 | 30 | 27209 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker)、[morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust)、[s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) |
| `local-first` | 78 | 30 | 14090 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[yjid/kensaku](https://github.com/yjid/kensaku) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 22 | 26814 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DIYgod/pinky](https://github.com/DIYgod/pinky) |
| `ai-agents` | 20 | 18119 | [daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[yjid/kensaku](https://github.com/yjid/kensaku)、[agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) |
| `codex` | 16 | 18215 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[ZiChuanLan/agent-purge](https://github.com/ZiChuanLan/agent-purge) |
| `model-context-protocol` | 14 | 9872 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo)、[simpsoka/zigzag](https://github.com/simpsoka/zigzag) |
| `windows` | 13 | 11305 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[yjid/kensaku](https://github.com/yjid/kensaku)、[Renly1994/xiaotang-daozai](https://github.com/Renly1994/xiaotang-daozai) |
| `mcp-server` | 13 | 9777 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo)、[bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon) |
| `macos` | 11 | 8852 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[simpsoka/zigzag](https://github.com/simpsoka/zigzag) |
| `agent-skills` | 10 | 14045 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) |
| `developer-tools` | 9 | 3328 | [alexeyw/lot-map](https://github.com/alexeyw/lot-map)、[jazzenchen/agent-hud-open](https://github.com/jazzenchen/agent-hud-open)、[chutingyean/Agent-Cockpit](https://github.com/chutingyean/Agent-Cockpit) |
| `blender` | 8 | 4691 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[islandmed/SculptForge](https://github.com/islandmed/SculptForge)、[racdeufindurch198812/Blender-AI-MCP-Studio](https://github.com/racdeufindurch198812/Blender-AI-MCP-Studio) |
| `blender-addon` | 8 | 4691 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[islandmed/SculptForge](https://github.com/islandmed/SculptForge)、[racdeufindurch198812/Blender-AI-MCP-Studio](https://github.com/racdeufindurch198812/Blender-AI-MCP-Studio) |
| `python` | 8 | 3176 | [cutetailbud/ff-ruyijs](https://github.com/cutetailbud/ff-ruyijs)、[aa1143/NamiAgent](https://github.com/aa1143/NamiAgent)、[chaw1/datakeel](https://github.com/chaw1/datakeel) |

**语言分布**：Rust 28 · Python 21 · TypeScript 18 · JavaScript 7 · Go 5 · C++ 2 · Dart 2 · HTML 2

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) · 🟢 窗口内 · 85.8 分

> Agent skill for hill-climbing local LLM serving speed (decode, speculative decoding, prefill, KV, startup, TTFT) on any hardware and quantization

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1276 | +1276 | +0 | 114 | 6 | Python | MIT | 11-16（3 天前） | 3 天前 |

- **近 14 天每天新增**：`·········▆█▃▂·` 0 0 0 0 0 0 0 0 0 406 579 180 111 0
- **势头**：刚发布一周内
- **HN**：发过 1 次，最高 1 分（[讨论](https://news.ycombinator.com/item?id=50542464)）
- **topics**：`agent-skill` `benchmarking` `claude-code` `inference` `llm` `speculative-decoding`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [huggingface/pybot](https://github.com/huggingface/pybot) · 🟢 窗口内 · 82.6 分

> PyBot: a chatbot written in pure Python by a swarm of agents. No weights, no training, just rules.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 976 | +974 | +2 | 103 | 4 | Python | Apache-2.0 | 11-12（7 天前） | 3 天前 |

- **近 14 天每天新增**：`·····▁···▇█▃▃·` 0 0 0 0 0 2 0 0 0 325 408 134 107 0
- **势头**：比前 7 天快 487.0 倍，在加速
- **HN**：发过 2 次，最高 7 分（[讨论](https://news.ycombinator.com/item?id=50517920)）
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [JosssphZhou/poki](https://github.com/JosssphZhou/poki) · 🟡 在降温 · 63 分

> Poki uses your iPhone like you do. An open-source agent app that runs on your iPhone, reads the screen, and taps, types and swipes in real apps with your own model account.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1676 | +544 | +692 | 265 | 89 | Swift | AGPL-3.0 | 11-05（14 天前） | 今天 |

- **近 14 天每天新增**：`▄▄█▅▃▃▅▇▅▆▃▂▃·` 94 90 191 120 48 48 101 158 98 146 46 28 68 0
- **势头**：只有前 7 天的 79%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `ai-assistant` `automation` `claude-code` `computer-use` `gui-agent` `ios` `ios-app` `iphone` `llm` `mcp` `mobile-agent` `model-context-protocol` `open-source` `phone-agent` `swift` `voice-assistant`
- **主页**：<https://poki.bot>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 4. [DIYgod/pinky](https://github.com/DIYgod/pinky) · 🟡 在降温 · 61.4 分

> Let AI use your iPhone or Android phone, with you in the loop: any MCP agent from macOS, Windows or Linux, or Pinky itself, right on the phone.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2558 | +461 | +2095 | 267 | 17 | Go | Apache-2.0 | 11-06（13 天前） | 今天 |

- **近 14 天每天新增**：`▃█▄▃▂▂▂▂▂▂▂▂▂·` 218 901 419 219 142 129 67 71 78 73 92 82 65 0
- **势头**：只有前 7 天的 22%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `android` `claude-code` `ios` `iphone` `mcp` `mcp-server` `phone-automation`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 5. [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) · 🟡 在降温 · 60.4 分

> Open-source, self-hosted Slack alternative where your team and AI agents work together in channels and DMs. Agents run on Claude, ChatGPT/Codex, Gemini or Grok, with MCP tools, their own computer and browser, routines, memory and approvals. Web, desktop and phone apps. Docker Compose + Postgres. AGPL-3.0.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1767 | +418 | +1349 | 332 | 373 | TypeScript | AGPL-3.0 | 11-09（11 天前） | 今天 |

- **近 14 天每天新增**：`····██▂▂▃▂▂▁▁·` 0 0 0 0 606 635 108 67 148 83 46 34 40 0
- **势头**：只有前 7 天的 31%，在减速
- **HN**：发过 7 次，最高 5 分（[讨论](https://news.ycombinator.com/item?id=49789538)）
- **topics**：`agentic-ai` `ai-agents` `browser-automation` `chat` `claude` `claude-code` `codex` `collaboration` `computer-use` `docker-compose` `gemini` `grok` `human-in-the-loop` `llm` `mcp` `multi-agent` `openai` `self-hosted` `slack-alternative` `team-chat`
- **主页**：<https://agentes.chat>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 6. [lexifina/global-law](https://github.com/lexifina/global-law) · 🟢 窗口内 · 59.9 分

> The world's law in git: any provision, any country, any date, and the law that wrote each word.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2123 | +146 | +138 | 192 | 1 | HTML | — | 10-28（22 天前） | 今天 |

- **近 14 天每天新增**：`▅▅▄▅▄▄▄▇█▅▅▃▄·` 24 25 17 20 17 17 18 36 40 21 21 9 19 0
- **势头**：比前 7 天快 1.1 倍，在加速
- **HN**：发过 2 次，最高 1 分（[讨论](https://news.ycombinator.com/item?id=50418651)）
- **topics**：`git` `law` `legal-tech` `legislation` `mcp` `open-data`
- **主页**：<https://lexifina.com>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [sarpstar/cinecode](https://github.com/sarpstar/cinecode) · 🟡 在降温 · 58.3 分

> Films made with code. Short films, long YouTube videos, ads, explainers and music videos: an AI coding agent writes the script, builds every frame in code, designs the sound and hands you an MP4.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2789 | +341 | +1958 | 471 | 13 | Python | MIT | 11-03（16 天前） | 7 天前 |

- **近 14 天每天新增**：`██▄▂▃▂▂▂▂▂▂▂▂·` 584 615 265 119 172 117 86 72 57 47 63 50 52 0
- **势头**：只有前 7 天的 17%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://x.com/sarpstar>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) · 🟡 在降温 · 57.6 分

> UEFI pre-driver NVIDIA GPU unlocker for Windows Linux Hackintosh and all EFI-bootable system (Rust): SEC2 scrubber -> FWSEC/WPR2 -> signed Booter -> V67 four-write payload, read-back verified. Verified on most RTX 20 30 40 Series.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2749 | +317 | +453 | 254 | 19 | Rust | GPL-2.0 | 10-26（25 天前） | 今天 |

- **近 14 天每天新增**：`█▆█▆█▆▄▆▆▄▆▅▇·` 80 62 80 61 77 55 38 58 62 33 54 46 64 0
- **势头**：只有前 7 天的 70%，在减速
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50272846)）
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. 🆕 [alexeyw/lot-map](https://github.com/alexeyw/lot-map) · 🟡 在降温 · 56 分

> Lot Map for Claude Code: a live map beside the chat that shows what the agent is doing. Tool calls, model steps, hooks, skills and subagents light up as they happen. Local only, in 7 languages.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1029 | +270 | +758 | 115 | 3 | TypeScript | MIT | 11-09（10 天前） | 今天 |

- **近 14 天每天新增**：`···▄█▅▄▃▂▂▂▂▁·` 0 0 0 150 308 186 114 82 59 51 39 22 17 0
- **势头**：只有前 7 天的 36%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-observability` `ai-agents` `claude` `claude-code` `claude-code-plugin` `developer-tools` `svg-animation` `typescript` `visualization`
- **主页**：<https://alexeyw.github.io/lot-map/>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) · 🟡 在降温 · 55.6 分

> Evidence-first genealogy skill for AI agents (Codex, Claude Code): church books, civil, military, deportation and repression records across the former USSR. Replies in your language.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2687 | +260 | +352 | 277 | 0 | Python | MIT | 10-25（25 天前） | 今天 |

- **近 14 天每天新增**：`█▆▇▆▄▃▅█▅▄▄▅▃·` 78 59 66 52 31 23 43 73 45 32 33 50 27 0
- **势头**：只有前 7 天的 74%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `archives` `claude-code` `codex` `family-history` `familysearch` `genealogy` `ussr`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [simplexai-labs/linger](https://github.com/simplexai-labs/linger) — 一天进了一半以上的 star，但 HN 上没火过
- [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) — 一天进了一半以上的 star，但 HN 上没火过
- [Lemxy/WinRust](https://github.com/Lemxy/WinRust) — 一天进了一半以上的 star，但 HN 上没火过
- [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon) — 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1%
- [Illson/RustText](https://github.com/Illson/RustText) — 一天进了一半以上的 star，但 HN 上没火过；没有描述

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 276 | 30 | [Show HN: DeepSeek V3 in ~200 lines of pure Jax](https://github.com/Vaibhaav-Tiwari/deepseek-v3-jax) | [HN](https://news.ycombinator.com/item?id=50497589) |
| 256 | 76 | [Show HN: Isometric SF – A pixel-art map of the SF Bay Area](https://isometricsf.com/) | [HN](https://news.ycombinator.com/item?id=50487228) |
| 248 | 93 | [Show HN: ExitPath – Open-source ways out of Slack, Notion and Microsoft 365](https://exitpath-ruddy.vercel.app/) | [HN](https://news.ycombinator.com/item?id=50547980) |
| 234 | 57 | [Show HN: Take Voyager 1 apart, down to a single memory chip](https://rshekhar.com/voyager/) | [HN](https://news.ycombinator.com/item?id=50548161) |
| 220 | 27 | [Show HN: Live map of U.S. flights during tonight's FAA nationwide ground stop](https://grounds.top/) | [HN](https://news.ycombinator.com/item?id=50491545) |
| 212 | 97 | [Show HN: Cornhole News – A Hacker News inspired site for news across the Midwest](https://cornholenews.news) | [HN](https://news.ycombinator.com/item?id=50561515) |
| 210 | 38 | [Show HN: Alloy CSS, dialogs, menus and tabs that work with JavaScript off](https://alloyhtml.com/example.html) | [HN](https://news.ycombinator.com/item?id=50532385) |
| 173 | 44 | [Show HN: A terminal-native idle factory game, written in Rust with ratatui](https://gitlab.com/snipedbywifi/terminactory) | [HN](https://news.ycombinator.com/item?id=50497132) |
| 144 | 42 | [Show HN: Mastra Factory, the open-source software factory we use to build Mastra](https://news.ycombinator.com/item?id=50548660) | [HN](https://news.ycombinator.com/item?id=50548660) |
| 141 | 70 | [Show HN: Type Fighter 2](https://typefighter2.com/) | [HN](https://news.ycombinator.com/item?id=50544821) |
| 121 | 74 | [Show HN: Zigzag, a native Mac browser for people leaving Arc](https://github.com/ZigaoWang/zigzag) | [HN](https://news.ycombinator.com/item?id=50496787) |
| 120 | 13 | [Show HN: Open-source, real-time object tracking for live video feeds](https://github.com/aryamandarda/tamserve) | [HN](https://news.ycombinator.com/item?id=50523377) |
| 109 | 37 | [Show HN: Agweb – a browser for agents that stays out of your way](https://github.com/paul-nameless/agweb) | [HN](https://news.ycombinator.com/item?id=50497147) |
| 105 | 85 | [Show HN: Foolscap – a writing app that reads your book and never writes for you](https://foolscap.works/) | [HN](https://news.ycombinator.com/item?id=50559749) |
| 89 | 21 | [Show HN: The Last Complication, a Zachtronics-style watchmaking puzzle game](https://lastcomplication.com/) | [HN](https://news.ycombinator.com/item?id=50511718) |
| 88 | 3 | [Show HN: Carton Clock – A working pendulum clock made from empty drink cartons](https://www.niklasroy.com/carton-clock/) | [HN](https://news.ycombinator.com/item?id=50482279) |
| 86 | 39 | [Show HN: Fursoy – Out-of-order RV64IMAFDV core in SystemVerilog (Linux 6.6)](https://github.com/FURSOY/fursoy-cpu) | [HN](https://news.ycombinator.com/item?id=50497137) |
| 72 | 37 | [Show HN: Sutra-OS – A self-hosted ontology platform](https://github.com/0nelight/sutra-os) | [HN](https://news.ycombinator.com/item?id=50525052) |
| 67 | 64 | [Show HN: Gawain – Require type hints on all Python variables](https://github.com/matheuzgomes/gawain) | [HN](https://news.ycombinator.com/item?id=50504072) |
| 62 | 18 | [Show HN: Unref – A Python dead code finder built on Ruff's parser](https://github.com/Apakottur/unref) | [HN](https://news.ycombinator.com/item?id=50517410) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 10 | [PaperOrchestra: A Multi-Agent Framework for Automated AI Research Paper Writing](https://huggingface.co/papers/2604.05018) | PaperOrchestra is a multi-agent framework that converts unstructured research materials into complete LaTeX manuscripts with literature synt… | [google-research/paper-orchestra](https://github.com/google-research/paper-orchestra) 5145★ |
| 21 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 7793★ |
| 17 | [π^4: A Foundation Model for 4D Scene Geometry and Motion](https://huggingface.co/papers/2611.23144) | This unified foundation model enables the recovery of dense geometry, camera poses, and object tracking from diverse, uncalibrated observati… | 💡 [yyfz/Pi4](https://github.com/yyfz/Pi4) 337★ |
| 140 | [Gamer: A Generalist Vision-Language-Action Foundation Model for Long-Horizon Real-Time Game Agent](https://huggingface.co/papers/2611.18397) | Gamer is a generalist agent framework that integrates perception, memory, and multi-step reasoning, trained through continued pre-training,… | [RainBowLuoCS/Gamer](https://github.com/RainBowLuoCS/Gamer) 1004★ |
| 36 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 12081★ |
| 20 | [Bitnet.cpp: Efficient Edge Inference for Ternary LLMs](https://huggingface.co/papers/2502.11880) | Bitnet.cpp enhances edge inference for ternary LLMs using a novel mixed-precision matrix multiplication library, achieving significant speed… | [microsoft/BitNet](https://github.com/microsoft/BitNet) 42252★ |
| 169 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 123164★ |
| 70 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 24497★ |
| 78 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 87 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 93852★ |
| 185 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 84008★ |
| 39 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 36306★ |
| 73 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 36307★ |
| 79 | [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://huggingface.co/papers/2504.19413) | Mem0, a memory-centric architecture with graph-based memory, enhances long-term conversational coherence in LLMs by efficiently extracting,… | [mem0ai/mem0](https://github.com/mem0ai/mem0) 69262★ |
| 35 | [HuggingFace's Transformers: State-of-the-art Natural Language Processing](https://huggingface.co/papers/1910.03771) | Transformers library provides state-of-the-art Transformer architectures and pretrained models for natural language processing tasks with a… | [huggingface/transformers](https://github.com/huggingface/transformers) 169277★ |
| 121 | [Jeveration: System One Models Now Generate](https://huggingface.co/papers/2611.24738) | Jeveration repurposes a frozen vision-language model to generate coherent images and perform image-to-image and dense prediction tasks in a… | 💡 [Carol-lyh/Jeveration](https://github.com/Carol-lyh/Jeveration) 41★ |
| 158 | [ARIS: Autonomous Research via Adversarial Multi-Agent Collaboration](https://huggingface.co/papers/2605.03042) | ARIS is an open-source research harness that uses cross-model adversarial collaboration to ensure reliable long-term research outcomes throu… | [wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) 19487★ |
| 108 | [Learning Heterogeneous Tactile Representation for General Dexterous Manipulation](https://huggingface.co/papers/2611.12806) | LingBot-Touch is a tactile foundation model that learns a unified, extensible representation across heterogeneous tactile sensors, yielding… | 💡 [Robbyant/lingbot-touch](https://github.com/Robbyant/lingbot-touch) 775★ |
| 13 | [MovieRoll: A Systematic Framework for Rolling Out Long-Form Videos](https://huggingface.co/papers/2611.21339) | Streaming video generation must sustain quality beyond the training horizon while handling self-generated history and growing cache costs. | 💡 [Tencent-Hunyuan/MovieRoll](https://github.com/Tencent-Hunyuan/MovieRoll) 110★ |
| 12 | [MedJev: A System One Vision-Language Decision Model for Fast and Effective Medical Image Understandi…](https://huggingface.co/papers/2611.20992) | Medical image understanding with vision-language models (VLMs) typically relies on autoregressively generating reasoning and answer tokens. | 💡 [zfkarl/MedJev](https://github.com/zfkarl/MedJev) 89★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 33 | [clairic](https://huggingface.co/Cloudflare/clairic) | image-text-to-text | 84 | 1 |
| 46 | [olala v1.0 mini 7a1b](https://huggingface.co/OVHaiLLM/Olala-v1.0-mini-7A1B) | text-generation | 49 | 1 |
| 50 | [sava](https://huggingface.co/inworld/sava) | voice-activity-detection | 63 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 35 | 22 | [Design for Understandability](https://jschuster.org/blog/2026/11/19/design-for-understandability/) | `api` `plt` `practices` `slides` | [讨论](https://lobste.rs/s/qsrnot/design_for_understandability) |
| 64 | 3 | [PostgreSQL 19 Released](https://www.postgresql.org/about/news/postgresql-19-released-3449/) | `databases` `release` | [讨论](https://lobste.rs/s/pqyuhk/postgresql_19_released) |
| 152 | 55 | [We Need Smart People Who Give a Shit](https://violetpixel.com/blog/2026-11-17-we-need-smart-people-who-give-a-shit/) | `culture` | [讨论](https://lobste.rs/s/rzuasm/we_need_smart_people_who_give_shit) |
| 30 | 8 | [Mutex poisoning is not for everyone](https://bertptrs.nl/2026/11/16/mutex-poisoning-is-not-for-everyone.html) | `rust` | [讨论](https://lobste.rs/s/uzn2t6/mutex_poisoning_is_not_for_everyone) |
| 16 | 7 | [Hiring a Systems Programmer for Boxem](https://lobste.rs/s/pnfs5p) | `c` `job` | [讨论](https://lobste.rs/s/pnfs5p/hiring_systems_programmer_for_boxem) |
| 41 | 1 | [15 million web servers on one VM - smoltcp, DPDK, AF_XDP](https://kapteko.com/15-million-webservers/) | `networking` `rust` | [讨论](https://lobste.rs/s/elmy67/15_million_web_servers_on_one_vm_smoltcp) |
| 25 | 6 | [Ruby2Shell (GHSA-34m4-m9fh-gqp5)](https://verialabs.com/ruby2shell/) | `ruby` `security` | [讨论](https://lobste.rs/s/usdf7t/ruby2shell_ghsa_34m4_m9fh_gqp5) |
| 3 | 2 | [Garage Door Spam](https://blog.harrison.page/garage-door-spam/) | `hardware` | [讨论](https://lobste.rs/s/tr5ghf/garage_door_spam) |
| 223 | 73 | [Codeberg's domain suddenly disappeared from their account, site is unreachable](https://social.anoxinon.de/@Codeberg/117636454915265360) | `vcs` | [讨论](https://lobste.rs/s/spmgsd/codeberg_s_domain_suddenly_disappeared) |
| 27 | 3 | [Distributed, high-performance blob storage on SQLite](https://zerodha.tech/blog/high-performance-distributed-blob-storage/) | `distributed` `rust` | [讨论](https://lobste.rs/s/bk5nfs/distributed_high_performance_blob) |
| 9 | 1 | [Supporting FOSS projects to transition to memory safe tech](https://tweedegolf.nl/en/blog/243/supporting-foss-projects-to-transition-to-memory-safe-tech/) | `programming` `rust` | [讨论](https://lobste.rs/s/naiy6x/supporting_foss_projects_transition) |
| 4 | 0 | [Farcall, a terminal-ready Rust PC+DOS emulator](https://www.dialup.net/farcall/) | `retrocomputing` `virtualization` | [讨论](https://lobste.rs/s/lq9xuw/farcall_terminal_ready_rust_pc_dos) |
| 3 | 0 | [Jujutsu Primer](https://ethanlowman.com/posts/jj-primer/) | `vcs` | [讨论](https://lobste.rs/s/i6dn7g/jujutsu_primer) |
| 4 | 0 | [Visualizing a Ledger with pgledger-ui](https://www.pgrs.net/2026/11/19/visualizing-a-ledger-with-pgledger-ui/) | `databases` `visualization` | [讨论](https://lobste.rs/s/gftix3/visualizing_ledger_with_pgledger_ui) |
| 4 | 0 | [Rebuilding my local voice assistant pipeline](https://blog.platypush.tech/article/Rewriting-my-voice-assistant-pipeline) | `ai` `python` | [讨论](https://lobste.rs/s/gn5qb1/rebuilding_my_local_voice_assistant) |
| 4 | 2 | [Mercurius — A Zero-Trust Network‑Native Window System](https://mercurius.tebibyte.org/) | `distributed` `networking` | [讨论](https://lobste.rs/s/bkvpzd/mercurius_zero_trust_network_native) |
| 17 | 4 | [PHP 8.6 Release Announcement](https://www.php.net/releases/8.6/en.php) | `php` `release` | [讨论](https://lobste.rs/s/xn50o0/php_8_6_release_announcement) |
| 85 | 16 | [nginx2root](https://xint.io/blog/nginx2root-remote-code-execution) | `security` | [讨论](https://lobste.rs/s/wj2svg/nginx2root) |
| 1 | 0 | [Persistent incrementality in Rust](https://rust-glancer.github.io/blog/persistent-incrementality-in-rust/) | `rust` | [讨论](https://lobste.rs/s/9bvpac/persistent_incrementality_rust) |
| 43 | 15 | [Java4Shell is a reason to use Java](https://mccue.dev/pages/11-18-26-java4shell) | `java` `security` | [讨论](https://lobste.rs/s/a1uff5/java4shell_is_reason_use_java) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 92 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 68 | 49 | 72% | — |
| 🔴 先核对 | 38 | 21 | 55% | — |
| 🟡 在降温 | 6 | 0 | 0% | — |
| 🔵 已被发现 | 3 | 1 | 33% | — |
| 💤 不活跃 | 1 | 0 | 0% | — |
| 🟢 窗口内 | 21 | 9 | 42% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [JuneYaooo/rea-video](https://github.com/JuneYaooo/rea-video) | 2026-11-06 | 🚀 爆发 | 2273 | 11162 | 4 | ✅ 起来了 |
| [andrew-babo/muse4ai](https://github.com/andrew-babo/muse4ai) | 2026-11-06 | 🟢 窗口内 | 856 | 283 | 0 | 没起来 |
| [zortos293/Lichii](https://github.com/zortos293/Lichii) | 2026-11-06 | 🚀 爆发 | 2623 | 9852 | 2 | ✅ 起来了 |

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
