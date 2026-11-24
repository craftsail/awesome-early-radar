# early-radar 选题雷达 · 2026-11-24

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 104 个，细查前 20 个 · 比上次 = 和 2026-11-23 那次比 · 生成于 2026-11-24 09:30 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 4 个 · Show HN ✅ 17 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ❌ 1 个没查到，下次再查

## 今日速览

- **有数据源没拿到**：复盘。下面对应的部分是空的或变薄了，不代表今天没有
- **细查 20 个仓库**：🟢 窗口内 7 个 · 🟡 在降温 10 个 · 🔵 已被发现 0 个 · 💤 不活跃 0 个 · 🔴 先核对 3 个
- **今天新出现 3 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [Marvisak/VIctory](https://github.com/Marvisak/VIctory) 平均每天 +6883，见 [爆发](#爆发)
- **复盘**：🚀 爆发 53/75 · 🔴 先核对 25/43 · 🟡 在降温 0/6 · 🔵 已被发现 1/3 · 💤 不活跃 0/1 · 🟢 窗口内 11/24（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) — Paste a link, get captioned 9:16 clips in ~2 min. Free, loca…（近 7 天 +2359，刚发布一周内）
  - [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) — Agent skill for hill-climbing local LLM serving speed (decod…（近 7 天 +1381，比前 7 天快 1.4 倍，在加速）
  - [Lemxy/WinRust](https://github.com/Lemxy/WinRust) — Windows shell replacement in Rust: taskbar, file manager, NT…（近 7 天 +1341，比前 7 天快 16.8 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 28 个（star 合计 31418），代表：[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[DIYgod/pinky](https://github.com/DIYgod/pinky)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：5 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: I built a game where you are an LLM's subagent](https://github.com/gulivan/worker755) — 358 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| 🆕 [Marvisak/VIctory](https://github.com/Marvisak/VIctory) | 6883 | 6883 | — | 1 | [1](https://news.ycombinator.com/item?id=50622253) | victory · marvisak victory · marvis victory | An attempt at running GTA VI on PC |
| 🆕 [ivall/xcl](https://github.com/ivall/xcl) | 5630 | 1581 | — | 3.6 | — | xcl · ivall xcl | Xbox Series compatibility layer for Windows - runs console g… |
| [Hut-hzf/ung220z-tool](https://github.com/Hut-hzf/ung220z-tool) | 3961 | 444 | +1533 | 8.9 | — | ung220z tool · hut-hzf ung220z tool | ung220z-tool 是一个针对 UNG220Z，另含中兴/烽火/华为/九联多厂商适配、固件指纹识别与分家族排障建议… |
| [EL4CTEO/fast-anything](https://github.com/EL4CTEO/fast-anything) | 3362 | 1207 | +1072 | 2.8 | [208](https://news.ycombinator.com/item?id=50596155) | fast anything · el4cteo fast anything | Don't rewrite it in Rust. Rewrite the 5% that's slow: profil… |
| [erkamyaman/rust-anything](https://github.com/erkamyaman/rust-anything) | 8941 | 1133 | +761 | 7.9 | [1](https://news.ycombinator.com/item?id=50558549) | rust anything · erkamyaman rust anything · erkam rust anything | Rewrite your whole app in Rust, one piece at a time, checked… |
| [os6/nospeaker](https://github.com/os6/nospeaker) | 1593 | 842 | +958 | 1.9 | [310](https://news.ycombinator.com/item?id=50610318) | nospeaker · os6 nospeaker · cody nospeaker | make your macbook's trackpad talk using its haptic motor |
| [XinaTian/MROffice](https://github.com/XinaTian/MROffice) | 3358 | 246 | +897 | 13.7 | [4](https://news.ycombinator.com/item?id=50546074) | mroffice · xinatian mroffice · xina mroffice | MR Office — the open-source editors of the AI office suite c… |
| 🆕 [ubiquitarianism/leonida](https://github.com/ubiquitarianism/leonida) | 829 | 829 | — | 1 | — | leonida · ubiquitarianism leonida | A continuation of Leonida, the Xbox > PC port of GTA VI |
| [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) | 1614 | 212 | +752 | 7.6 | — | mobile agent testers · pierridotite mobile agent testers · pierre mobile agent testers | 20 AI testers on 20 different phones, in parallel, on GitHub… |
| 🆕 [AFK-surf/xnulinux](https://github.com/AFK-surf/xnulinux) | 2686 | 677 | — | 4 | [610](https://news.ycombinator.com/item?id=50607261) | xnulinux · afk-surf xnulinux · afk xnulinux | XNU as a loadable kernel module inside Linux (macOS personal… |
| 🆕 [4lwayz/portwatch-vi](https://github.com/4lwayz/portwatch-vi) | 1414 | 583 | — | 2.4 | — | portwatch vi · 4lwayz portwatch vi | Does GTA VI run on PC yet? A live tracker of community recom… |
| [omonkeyz/xbox-emulator](https://github.com/omonkeyz/xbox-emulator) | 1730 | 566 | +329 | 3.1 | — | xbox emulator · omonkeyz xbox emulator | Progress notes for running Xbox Series X/S builds on PC (Tom… |
| 🆕 [RyanLebedev6104/robrun-cheat](https://github.com/RyanLebedev6104/robrun-cheat) | 535 | 535 | — | 1 | — | robrun cheat · ryanlebedev6104 robrun cheat | ROB RUN external-overlay & External runtime-mod — Spatial Bo… |
| [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) | 2359 | 474 | +193 | 5 | — | neonclipping · iamajmeena neonclipping | Paste a link, get captioned 9:16 clips in ~2 min. Free, loca… |
| [R0Y00/Xbox2Windows](https://github.com/R0Y00/Xbox2Windows) | 1726 | 472 | +370 | 3.7 | — | xbox2windows · r0y00 xbox2windows · royoo xbox2windows | Static recompilation research for Xbox Series X/S software o… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 93.2 | 🟢 窗口内 | [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) | Python | 2359 | +193 | +2359 | +0 | `········▇█▅▄▃▁` | 4 | — | — |
| 2 | 86.8 | 🟢 窗口内 | [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) | Python | 2360 | +360 | +1381 | +979 | `·····▆█▃▂▂▆▄▅▁` | 7 | — | — |
| 3 | 86.4 | 🟢 窗口内 | [Lemxy/WinRust](https://github.com/Lemxy/WinRust) | Rust | 1421 | +151 | +1341 | +80 | `······▃▂█▇▅▇▄▁` | 6 | — | — |
| 4 | 80.9 | 🟢 窗口内 | [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) | TypeScript | 845 | +219 | +845 | +0 | `·······▁▂▄▂█▅▁` | 5 | — | — |
| 5 | 79.4 | 🟢 窗口内 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Rust | 2699 | +49 | +748 | +371 | `▂▃▂▂▁▁▂▂▂█▄▃▂▁` | 22 | — | — |
| 6 | 75.3 | 🟢 窗口内 | [w01fb0ss/PiBot](https://github.com/w01fb0ss/PiBot) | TypeScript | 529 | +88 | +529 | +0 | `··········█▇▃▁` | 3 | — | — |
| 7 | 74.7 | 🆕 🟢 窗口内 | [qianyiai/kurocat](https://github.com/qianyiai/kurocat) | TypeScript | 503 | — | +503 | +0 | `··········▂▇█▂` | 2 | — | — |
| 8 | 60.5 | 🟡 在降温 | [huggingface/pybot](https://github.com/huggingface/pybot) | Python | 1156 | +30 | +422 | +734 | `·▁···▇█▃▃▂▂▂▁▁` | 11 | [7](https://news.ycombinator.com/item?id=50517920) | — |
| 9 | 58.1 | 🟡 在降温 | [DIYgod/pinky](https://github.com/DIYgod/pinky) | Go | 2737 | +45 | +332 | +650 | `█▇▄▅▅▅▆▅▄▄▃▃▃▁` | 17 | — | — |
| 10 | 57.8 | 🟡 在降温 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki) | Swift | 1900 | +41 | +322 | +644 | `▃▃▅█▅▇▃▂▄▂▄▅▂▁` | 18 | — | — |
| 11 | 57.4 | 🟡 在降温 | [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) | TypeScript | 2002 | +39 | +310 | +1692 | `██▂▂▃▂▂▁▁▂▂▂▁▁` | 15 | — | — |
| 12 | 56.3 | 🟡 在降温 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | TypeScript | 2870 | +99 | +277 | +319 | `█▃▂▂▂▂▃▃▂▂▂▅▅▁` | 23 | — | — |
| 13 | 55.8 | 🟡 在降温 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 2901 | +31 | +264 | +376 | `█▆▄▆▇▄▆▅▇▄▅▅▄▁` | 29 | [2](https://news.ycombinator.com/item?id=50272846) | — |
| 14 | 54.9 | 🟡 在降温 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode) | Python | 2928 | +38 | +242 | +613 | `█▆▅▄▃▃▄▃▃▂▂▃▂▁` | 20 | — | — |
| 15 | 54.7 | 🟡 在降温 | [boringmarketer/boring-marketing-skills](https://github.com/boringmarketer/boring-marketing-skills) | Python | 823 | +24 | +237 | +586 | `·····██▃▂▂▂▁▁▁` | 7 | — | — |
| 16 | 49.8 | 🟡 在降温 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 2753 | +15 | +144 | +279 | `▄▃▅█▅▄▄▆▄▂▃▂▃▁` | 29 | — | — |
| 17 | 44.5 | 🟡 在降温 | [voyager-so/vork](https://github.com/voyager-so/vork) | Rust | 1707 | +15 | +85 | +257 | `█▃▃▅▂▂▂▂▂▂▂▂▂▁` | 18 | [8](https://news.ycombinator.com/item?id=50396650) | — |
| 18 | 44.2 | 🔴 先核对 | [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) | Python | 1614 | +752 | +1583 | +31 | `·····▁▁▁▁▁▁█▆▁` | 7 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 38.7 | 🆕 🔴 先核对 | [Ahmet-Dedeler/awesome-gta6-reverse-engineering](https://github.com/Ahmet-Dedeler/awesome-gta6-reverse-engineering) | HTML | 628 | — | +628 | +0 | `··········▁▅█▁` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 37.8 | 🆕 🔴 先核对 | [erkamyaman/safe-anything](https://github.com/erkamyaman/safe-anything) | Rust | 547 | — | +547 | +0 | `···········▄█▁` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 1056 | 30 | 44184 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) |
| `mcp` | 199 | 30 | 26627 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[lexifina/global-law](https://github.com/lexifina/global-law)、[andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) |
| `rust` | 194 | 30 | 27276 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker)、[s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[Renly1994/xiaotang-daozai](https://github.com/Renly1994/xiaotang-daozai) |
| `local-first` | 67 | 30 | 13238 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 28 | 31418 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[DIYgod/pinky](https://github.com/DIYgod/pinky) |
| `codex` | 22 | 21726 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[ZiChuanLan/agent-purge](https://github.com/ZiChuanLan/agent-purge) |
| `ai-agents` | 18 | 16019 | [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat)、[JosssphZhou/poki](https://github.com/JosssphZhou/poki)、[voyager-so/vork](https://github.com/voyager-so/vork) |
| `mcp-server` | 18 | 12057 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo)、[INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) |
| `model-context-protocol` | 16 | 11033 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo)、[simpsoka/zigzag](https://github.com/simpsoka/zigzag) |
| `windows` | 15 | 9090 | [Renly1994/xiaotang-daozai](https://github.com/Renly1994/xiaotang-daozai)、[simpsoka/zigzag](https://github.com/simpsoka/zigzag)、[Koimsurai/Arke](https://github.com/Koimsurai/Arke) |
| `agent-skills` | 12 | 13548 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[kubai087/kubai-icons](https://github.com/kubai087/kubai-icons) |
| `llm` | 10 | 11874 | [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill)、[agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat)、[JosssphZhou/poki](https://github.com/JosssphZhou/poki) |
| `macos` | 10 | 5267 | [simpsoka/zigzag](https://github.com/simpsoka/zigzag)、[21stware/bowel](https://github.com/21stware/bowel)、[gelenmedya/rustyfiles](https://github.com/gelenmedya/rustyfiles) |
| `3d-modeling` | 10 | 4727 | [racdeufindurch198812/Blender-AI-MCP-Studio](https://github.com/racdeufindurch198812/Blender-AI-MCP-Studio)、[credoksopho1984/blender-ai-copilot-studio](https://github.com/credoksopho1984/blender-ai-copilot-studio)、[tiobeharxi1987/blender-ai-copilot-flow](https://github.com/tiobeharxi1987/blender-ai-copilot-flow) |
| `developer-tools` | 10 | 4513 | [alexeyw/lot-map](https://github.com/alexeyw/lot-map)、[INK-Q/agy-fast](https://github.com/INK-Q/agy-fast)、[devvmhq/devvm](https://github.com/devvmhq/devvm) |
| `3d-automation` | 9 | 4581 | [racdeufindurch198812/Blender-AI-MCP-Studio](https://github.com/racdeufindurch198812/Blender-AI-MCP-Studio)、[credoksopho1984/blender-ai-copilot-studio](https://github.com/credoksopho1984/blender-ai-copilot-studio)、[tiobeharxi1987/blender-ai-copilot-flow](https://github.com/tiobeharxi1987/blender-ai-copilot-flow) |

**语言分布**：Rust 28 · TypeScript 25 · Python 20 · JavaScript 8 · Go 5 · HTML 2 · C# 1 · C++ 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) · 🟢 窗口内 · 93.2 分

> Paste a link, get captioned 9:16 clips in ~2 min. Free, local, open-source clipping engine (audio-first, YouTube captions, local LLM).

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2359 | +2359 | +0 | 150 | 21 | Python | MIT | 11-19（4 天前） | 今天 |

- **近 14 天每天新增**：`········▇█▅▄▃▁` 0 0 0 0 0 0 0 0 657 728 458 331 169 16
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-video-clipper` `clipping` `faster-whisper` `ffmpeg` `gameplay-clipper` `local-llm` `ollama` `open-source-video-editor` `opusclip-alternative` `shorts` `twitch-clips` `vertical-video` `video` `whisper` `youtube-shorts-generator` `yt-dlp`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) · 🟢 窗口内 · 86.8 分

> Agent skill for hill-climbing local LLM serving speed (decode, speculative decoding, prefill, KV, startup, TTFT) on any hardware and quantization

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2360 | +1381 | +979 | 221 | 23 | Python | MIT | 11-16（7 天前） | 7 天前 |

- **近 14 天每天新增**：`·····▆█▃▂▂▆▄▅▁` 0 0 0 0 0 403 576 178 113 107 407 221 332 23
- **势头**：比前 7 天快 1.4 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `benchmarking` `claude-code` `inference` `llm` `speculative-decoding`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [Lemxy/WinRust](https://github.com/Lemxy/WinRust) · 🟢 窗口内 · 86.4 分

> Windows shell replacement in Rust: taskbar, file manager, NTFS search, task manager, disk cleaner. One installer exe.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1421 | +1341 | +80 | 88 | 32 | Rust | Apache-2.0 | 11-17（6 天前） | 今天 |

- **近 14 天每天新增**：`······▃▂█▇▅▇▄▁` 0 0 0 0 0 0 80 72 348 298 183 301 127 12
- **势头**：比前 7 天快 16.8 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) · 🟢 窗口内 · 80.9 分

> Non-invasive MCP accelerator plugin for Google Antigravity (CLI/Desktop/IDE): cuts LLM turns (-34%), token quota (-31%), and upload traffic (-40%) without affecting native UI or diffs.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 845 | +845 | +0 | 54 | 25 | TypeScript | MIT | 11-19（5 天前） | 今天 |

- **近 14 天每天新增**：`·······▁▂▄▂█▅▁` 0 0 0 0 0 0 0 7 34 168 53 375 198 10
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `ai-coding` `antigravity` `antigravity-cli` `antigravity-ide` `antigravity-plugins` `coding-agent` `context-optimization` `developer-productivity` `developer-tools` `gemini` `google-antigravity` `latency-optimization` `mcp` `mcp-plugin` `mcp-server` `model-context-protocol` `performance` `plugin` `token-optimization`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) · 🟢 窗口内 · 79.4 分

> Blazing-fast native notes app and rich-text editor for macOS, Windows, and Linux. Built with Rust + GPUI. Local-first and beautifully designed.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2699 | +748 | +371 | 234 | 40 | Rust | MIT | 11-01（22 天前） | 今天 |

- **近 14 天每天新增**：`▂▃▂▂▁▁▂▂▂█▄▃▂▁` 61 87 64 66 21 26 46 34 29 368 182 88 44 3
- **势头**：比前 7 天快 2.0 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://quiet.md>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [w01fb0ss/PiBot](https://github.com/w01fb0ss/PiBot) · 🟢 窗口内 · 75.3 分

> Open-source, local-first AI agent team for your desktop: multi-agent group chats, computer use, browser, MCP, routines and approvals. macOS, Windows, Linux + Android. Built on pi.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 529 | +529 | +0 | 74 | 6 | TypeScript | Apache-2.0 | 11-21（3 天前） | 今天 |

- **近 14 天每天新增**：`··········█▇▃▁` 0 0 0 0 0 0 0 0 0 0 249 197 78 5
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent` `ai-agent` `ai-agents` `ai-assistant` `android` `automation` `chatgpt` `coding-agent` `computer-use` `desktop-app` `electron` `llm` `local-first` `mcp` `multi-agent` `ollama` `openai` `privacy` `self-hosted` `typescript`
- **主页**：<https://pibot.space>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. 🆕 [qianyiai/kurocat](https://github.com/qianyiai/kurocat) · 🟢 窗口内 · 74.7 分

> KuroCat — Free open-source desktop typing cat pet & OBS overlay (Bongo Cat alternative, Tauri v2 + Rust + MCP)｜轻量级透明置顶桌面打字小黑猫伴侣（6款猫咪+鲸鱼娘大肥鱼 / 输密码防偷窥 / OBS透明源 / AI捏猫 / Win·Mac·Linux·Android）

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 503 | +503 | +0 | 76 | 18 | TypeScript | MIT | 11-21（2 天前） | 今天 |

- **近 14 天每天新增**：`··········▂▇█▂` 0 0 0 0 0 0 0 0 0 0 18 205 236 44
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`android` `bongo-cat` `bongocat` `cross-platform` `desktop-pet` `keyboard-visualizer` `kurocat` `linux` `macos` `mcp` `obs-studio` `open-source` `rust` `tauri` `typing-cat` `windows`
- **主页**：<https://qianyi.one/kurocat/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [huggingface/pybot](https://github.com/huggingface/pybot) · 🟡 在降温 · 60.5 分

> PyBot: a chatbot written in pure Python by a swarm of agents. No weights, no training, just rules.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1156 | +422 | +734 | 132 | 13 | Python | Apache-2.0 | 11-12（11 天前） | 7 天前 |

- **近 14 天每天新增**：`·▁···▇█▃▃▂▂▂▁▁` 0 2 0 0 0 325 407 132 114 71 39 37 26 3
- **势头**：只有前 7 天的 57%，在减速
- **HN**：发过 2 次，最高 7 分（[讨论](https://news.ycombinator.com/item?id=50517920)）
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [DIYgod/pinky](https://github.com/DIYgod/pinky) · 🟡 在降温 · 58.1 分

> Let AI use your iPhone or Android phone, with you in the loop: any MCP agent from macOS, Windows or Linux, or Pinky itself, right on the phone.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2737 | +332 | +650 | 286 | 22 | Go | Apache-2.0 | 11-06（17 天前） | 今天 |

- **近 14 天每天新增**：`█▇▄▅▅▅▆▅▄▄▃▃▃▁` 142 129 66 71 78 72 92 82 68 51 43 38 45 5
- **势头**：只有前 7 天的 51%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `android` `claude-code` `ios` `iphone` `mcp` `mcp-server` `phone-automation`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [JosssphZhou/poki](https://github.com/JosssphZhou/poki) · 🟡 在降温 · 57.8 分

> Poki uses your iPhone like you do. An open-source agent app that runs on your iPhone, reads the screen, and taps, types and swipes in real apps with your own model account.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1900 | +322 | +644 | 279 | 158 | Swift | AGPL-3.0 | 11-05（18 天前） | 今天 |

- **近 14 天每天新增**：`▃▃▅█▅▇▃▂▄▂▄▅▂▁` 48 48 101 158 98 145 46 28 71 28 64 96 33 2
- **势头**：只有前 7 天的 50%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `ai-assistant` `automation` `claude-code` `computer-use` `gui-agent` `ios` `ios-app` `iphone` `llm` `mcp` `mobile-agent` `model-context-protocol` `open-source` `phone-agent` `swift` `voice-assistant`
- **主页**：<https://poki.bot>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) — 一天进了一半以上的 star，但 HN 上没火过
- [Ahmet-Dedeler/awesome-gta6-reverse-engineering](https://github.com/Ahmet-Dedeler/awesome-gta6-reverse-engineering) — 一天进了一半以上的 star，但 HN 上没火过
- [erkamyaman/safe-anything](https://github.com/erkamyaman/safe-anything) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 358 | 90 | [Show HN: I built a game where you are an LLM's subagent](https://github.com/gulivan/worker755) | [HN](https://news.ycombinator.com/item?id=50599762) |
| 251 | 94 | [Show HN: ExitPath – Open-source ways out of Slack, Notion and Microsoft 365](https://exitpath-ruddy.vercel.app/) | [HN](https://news.ycombinator.com/item?id=50547980) |
| 240 | 60 | [Show HN: Take Voyager 1 apart, down to a single memory chip](https://rshekhar.com/voyager/) | [HN](https://news.ycombinator.com/item?id=50548161) |
| 237 | 122 | [Show HN: Cornhole News – A Hacker News inspired site for news across the Midwest](https://cornholenews.news) | [HN](https://news.ycombinator.com/item?id=50561515) |
| 235 | 141 | [Show HN: Tinnitus frequency finder and audio notch tool](https://trynotched.com/find) | [HN](https://news.ycombinator.com/item?id=50541568) |
| 211 | 40 | [Show HN: Alloy CSS, dialogs, menus and tabs that work with JavaScript off](https://alloyhtml.com/example.html) | [HN](https://news.ycombinator.com/item?id=50532385) |
| 179 | 136 | [Show HN: Zero C# – C# without a runtime or GC](https://onurgumus.github.io/zero-csharp/index.html) | [HN](https://news.ycombinator.com/item?id=50590279) |
| 159 | 45 | [Show HN: Mastra Factory, the open-source software factory we use to build Mastra](https://news.ycombinator.com/item?id=50548660) | [HN](https://news.ycombinator.com/item?id=50548660) |
| 151 | 76 | [Show HN: Type Fighter 2](https://typefighter2.com/) | [HN](https://news.ycombinator.com/item?id=50544821) |
| 142 | 52 | [Show HN: Fast deterministic natural language search for OpenStreetMap data](https://hippomaps.ch/?q=cafes+by+the+Limmat+100+m+from+the+lake+in+zurich#map=15.02/47.36708/8.54935) | [HN](https://news.ycombinator.com/item?id=50561199) |
| 132 | 96 | [Show HN: Foolscap – a writing app that reads your book and never writes for you](https://foolscap.works/) | [HN](https://news.ycombinator.com/item?id=50559749) |
| 129 | 36 | [Show HN: OpenComputer – an open source alternative to Devin](https://github.com/diggerhq/opencomputer) | [HN](https://news.ycombinator.com/item?id=50581403) |
| 117 | 82 | [Show HN: Drive around my village in 3D](https://cherwellvalleymotorclub.app) | [HN](https://news.ycombinator.com/item?id=50574412) |
| 89 | 60 | [Show HN: The Riemann Proof Handbook](https://github.com/tamnd/riemann-handbook) | [HN](https://news.ycombinator.com/item?id=50596664) |
| 82 | 11 | [Show HN: An API for word timestamps from speech, 75% within 20ms](https://quebec.yarn.so) | [HN](https://news.ycombinator.com/item?id=50532515) |
| 68 | 23 | [Show HN: An ASCII cell aquarium for your terminal](https://github.com/kborer/cells/) | [HN](https://news.ycombinator.com/item?id=50541047) |
| 54 | 8 | [Show HN: TrnRT – An open-source LLM inference engine for AWS Trainium](https://github.com/RunanywhereAI/trnrt) | [HN](https://news.ycombinator.com/item?id=50533270) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 16 | [PaperOrchestra: A Multi-Agent Framework for Automated AI Research Paper Writing](https://huggingface.co/papers/2604.05018) | PaperOrchestra is a multi-agent framework that converts unstructured research materials into complete LaTeX manuscripts with literature synt… | [google-research/paper-orchestra](https://github.com/google-research/paper-orchestra) 6197★ |
| 110 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 32591★ |
| 37 | [Depth Pro 2: Sharp and Temporally Consistent Metric Monocular Depth](https://huggingface.co/papers/2611.26603) | A single scalable network estimates dense metric depth for images and video at native resolution, jointly improving metric accuracy, boundar… | 💡 [apple-aiml-research/ml-depth-pro-2](https://github.com/apple-aiml-research/ml-depth-pro-2) 632★ |
| 157 | [Gamer: A Generalist Vision-Language-Action Foundation Model for Long-Horizon Real-Time Game Agent](https://huggingface.co/papers/2611.18397) | Gamer is a generalist agent framework that integrates perception, memory, and multi-step reasoning, trained through continued pre-training,… | [RainBowLuoCS/Gamer](https://github.com/RainBowLuoCS/Gamer) 1459★ |
| 71 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 24994★ |
| 169 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 123598★ |
| 21 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 8045★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 21 | [π^4: A Foundation Model for 4D Scene Geometry and Motion](https://huggingface.co/papers/2611.23144) | This unified foundation model enables the recovery of dense geometry, camera poses, and object tracking from diverse, uncalibrated observati… | 💡 [yyfz/Pi4](https://github.com/yyfz/Pi4) 475★ |
| 86 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 94169★ |
| 110 | [FreeToken: Efficient Edge-Native MoE Serving with Bandwidth-Adaptive Execution](https://huggingface.co/papers/2608.16157) | FreeToken is an edge-native Mixture-of-Experts serving system that dynamically maps computation and model state onto heterogeneous local har… | [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken) 17736★ |
| 22 | [Bitnet.cpp: Efficient Edge Inference for Ternary LLMs](https://huggingface.co/papers/2502.11880) | Bitnet.cpp enhances edge inference for ternary LLMs using a novel mixed-precision matrix multiplication library, achieving significant speed… | [microsoft/BitNet](https://github.com/microsoft/BitNet) 42448★ |
| 36 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 12275★ |
| 3 | [LittleBit: Ultra Low-Bit Quantization via Latent Factorization](https://huggingface.co/papers/2506.13771) | LittleBit is a novel method for extreme compression of large language models using low-rank factorization and multi-scale compensation, achi… | 💡 [SamsungLabs/LittleBit](https://github.com/SamsungLabs/LittleBit) 841★ |
| 38 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 36557★ |
| 72 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 36558★ |
| 184 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 84219★ |
| 40 | [Geometric Context Transformer for Streaming 3D Reconstruction](https://huggingface.co/papers/2604.14141) | LingBot-Map is a feed-forward 3D foundation model that reconstructs scenes from video streams using a geometric context transformer architec… | [robbyant/lingbot-map](https://github.com/robbyant/lingbot-map) 19033★ |
| 12 | [MovieRoll: A Systematic Framework for Rolling Out Long-Form Videos](https://huggingface.co/papers/2611.21339) | Streaming video generation must sustain quality beyond the training horizon while handling self-generated history and growing cache costs. | 💡 [Tencent-Hunyuan/MovieRoll](https://github.com/Tencent-Hunyuan/MovieRoll) 337★ |
| 12 | [MedJev: A System One Vision-Language Decision Model for Fast and Effective Medical Image Understandi…](https://huggingface.co/papers/2611.20992) | Medical image understanding with vision-language models (VLMs) typically relies on autoregressively generating reasoning and answer tokens. | 💡 [zfkarl/MedJev](https://github.com/zfkarl/MedJev) 254★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 15 | [ling 3.2 air](https://huggingface.co/inclusionAI/Ling-3.2-air) | — | 139 | 1 |
| 35 | [qwen3.8 nariq](https://huggingface.co/nari-labs/Qwen3.8-27B-NariQ-GGUF) | image-text-to-text | 75 | 1 |
| 38 | [ocria nano 1](https://huggingface.co/llamaindex/OCRia-nano-1) | image-to-text | 77 | 1 |
| 40 | [memt 1.0 pro](https://huggingface.co/MemTensor/MemT-1.0-Pro) | text-generation | 78 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 99 | 34 | [Ladybird is now in alpha](https://ladybird.org/posts/alpha/) | `browsers` | [讨论](https://lobste.rs/s/h6webg/ladybird_is_now_alpha) |
| 11 | 1 | [2035 came early](https://fzakaria.com/2026/11/23/2035-came-early) | `nix` `wasm` | [讨论](https://lobste.rs/s/rkk6o8/2035_came_early) |
| 109 | 46 | [Signal is Serious About Protecting Your Privacy](https://signal.org/blog/protecting-your-privacy/) | `mobile` `privacy` | [讨论](https://lobste.rs/s/vldbcn/signal_is_serious_about_protecting_your) |
| 25 | 0 | [What VP != VNP Means (In 3 Minutes)](https://www.friedgil.com/vpvnp/) | `math` | [讨论](https://lobste.rs/s/2k95fs/what_vp_vnp_means_3_minutes) |
| 17 | 2 | [Lua for data representation](https://citrons.xyz/journal/2025-07-23) | `lua` | [讨论](https://lobste.rs/s/ezml41/lua_for_data_representation) |
| 26 | 21 | [Sneakernet](https://sneakernet.eu/) | `distributed` `networking` | [讨论](https://lobste.rs/s/pdecff/sneakernet) |
| 17 | 12 | [Held together by spare time: Reviving wiki.alpinelinux.org during PHP2Shell](https://lambdacreate.com/posts/held-together-by-spare-time) | `devops` | [讨论](https://lobste.rs/s/gtc9rg/held_together_by_spare_time_reviving_wiki) |
| 82 | 31 | [GitHub Actions accepts invalid YAML](https://yossarian.net/til/post/github-actions-accepts-invalid-yaml/) | `programming` | [讨论](https://lobste.rs/s/leqwqu/github_actions_accepts_invalid_yaml) |
| 32 | 1 | [Quality IMAP, Part 2: Mailbox Concurrency](https://aerogramme.deuxfleurs.fr/blog/2026-quality-imap-part-2/) | `distributed` `email` `testing` | [讨论](https://lobste.rs/s/lnpwpu/quality_imap_part_2_mailbox_concurrency) |
| 21 | 0 | [UQ researchers send an unblockable message using gravity](https://news.uq.edu.au/2026-11-uq-researchers-send-unblockable-message-using-gravity) | `compsci` `science` | [讨论](https://lobste.rs/s/ht8v1g/uq_researchers_send_unblockable_message) |
| 12 | 0 | [the algebra of dependent types (2025)](https://dotat.at/@/2025-05-28-types.html) | `plt` | [讨论](https://lobste.rs/s/n2krd2/algebra_dependent_types_2025) |
| 29 | 0 | [Illiterate Programming](https://deadsimpletech.com/blog/illiterate-programming) | `culture` | [讨论](https://lobste.rs/s/xxgezw/illiterate_programming) |
| 7 | 1 | [cgo's pointer check is all over the place](https://theconsensus.dev/p/2026/11/15/cgos-pointer-check.html) | `go` | [讨论](https://lobste.rs/s/fgbvtt/cgo_s_pointer_check_is_all_over_place) |
| 12 | 0 | [Release: Roto v0.14.0](https://community.nlnetlabs.nl/t/release-roto-v0-14-0/3511) | `release` `rust` | [讨论](https://lobste.rs/s/fygpme/release_roto_v0_14_0) |
| 7 | 0 | [Swapping Jolt's sorted collections to a B+tree](https://yogthos.net/posts/2026-11-23-b+trees.html) | `clojure` | [讨论](https://lobste.rs/s/wv9nhw/swapping_jolt_s_sorted_collections_b_tree) |
| 12 | 25 | [What are you doing this week?](https://lobste.rs/s/t8c4vj) | `ask` `programming` | [讨论](https://lobste.rs/s/t8c4vj/what_are_you_doing_this_week) |
| 0 | 0 | [There's no reason for software to be slow anymore](https://danluu.com/no-slow/) | `ai` | [讨论](https://lobste.rs/s/uf8vxo/there_s_no_reason_for_software_be_slow) |
| 15 | 1 | [Let's Meet in the Middle](https://george.mand.is/2026/11/lets-meet-in-the-middle/) | `api` `culture` | [讨论](https://lobste.rs/s/7fscqs/let_s_meet_middle) |
| 65 | 5 | [Gliver completes the Guix desktop](https://dustycloud.org/blog/gliver-completes-the-guix-desktop/) | `linux` `lisp` | [讨论](https://lobste.rs/s/wc8fla/gliver_completes_guix_desktop) |
| 9 | 0 | [Reverse Engineering a Board Game](https://wuemeli.com/blog/reversing-hitster-game/) | `android` `reversing` `rust` | [讨论](https://lobste.rs/s/8g6qyx/reverse_engineering_board_game) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 99 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 75 | 53 | 70% | — |
| 🔴 先核对 | 43 | 25 | 58% | 0 天 |
| 🟡 在降温 | 6 | 0 | 0% | — |
| 🔵 已被发现 | 3 | 1 | 33% | — |
| 💤 不活跃 | 1 | 0 | 0% | — |
| 🟢 窗口内 | 24 | 11 | 45% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [IainKay/ram-altman](https://github.com/IainKay/ram-altman) | 2026-11-10 | 🚀 爆发 | 1517 | 2387 | 89 | 没起来 |
| [cutetailbud/ff-ruyijs](https://github.com/cutetailbud/ff-ruyijs) | 2026-11-10 | 🟢 窗口内 | 1201 | 977 | 0 | 没起来 |
| [janestreet/agent_skills](https://github.com/janestreet/agent_skills) | 2026-11-10 | 🔴 先核对 | 2541 | 11478 | 726 | ✅ 起来了，比 HN 早 0 天 |

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
