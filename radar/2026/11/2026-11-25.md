# early-radar 选题雷达 · 2026-11-25

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 106 个，细查前 20 个 · 比上次 = 和 2026-11-24 那次比 · 生成于 2026-11-25 08:01 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 2 个 · Show HN ✅ 15 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ❌ 1 个没查到，下次再查

## 今日速览

- **有数据源没拿到**：复盘。下面对应的部分是空的或变薄了，不代表今天没有
- **细查 20 个仓库**：🟢 窗口内 11 个 · 🟡 在降温 4 个 · 🔵 已被发现 0 个 · 💤 不活跃 0 个 · 🔴 先核对 5 个
- **今天新出现 5 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [Marvisak/VIctory](https://github.com/Marvisak/VIctory) 平均每天 +8250，见 [爆发](#爆发)
- **复盘**：🚀 爆发 55/77 · 🔴 先核对 25/43 · 🟡 在降温 0/6 · 🔵 已被发现 2/4 · 💤 不活跃 0/1 · 🟢 窗口内 11/25（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) — Paste a link, get captioned 9:16 clips in ~2 min. Free, loca…（近 7 天 +2532，刚发布一周内）
  - [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) — 20 AI testers on 20 different phones, in parallel, on GitHub…（近 7 天 +1929，比前 7 天快 45.9 倍，在加速）
  - [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) — Agent skill for hill-climbing local LLM serving speed (decod…（近 7 天 +1463，比前 7 天快 1.3 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 29 个（star 合计 28719），代表：[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DIYgod/pinky](https://github.com/DIYgod/pinky)、[sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：4 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: I built a game where you are an LLM's subagent](https://github.com/gulivan/worker755) — 360 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [Marvisak/VIctory](https://github.com/Marvisak/VIctory) | 11769 | 8250 | +4886 | 1.4 | [1](https://news.ycombinator.com/item?id=50622253) | victory · marvisak victory · marvis victory | An attempt at running GTA VI on PC |
| 🆕 [fxceless/victory-fork](https://github.com/fxceless/victory-fork) | 2407 | 2407 | — | 1 | — | victory fork · fxceless victory fork · hyphen victory fork | Work-in-progress fork of VIctory: getting an Xbox Series tit… |
| 🆕 [xcl-dev/xcl](https://github.com/xcl-dev/xcl) | 8027 | 1784 | — | 4.5 | [49](https://news.ycombinator.com/item?id=44859763) | xcl · xcl-dev xcl · xcl xcl | Xbox Series compatibility layer for Windows - runs console g… |
| [4lwayz/portwatch-vi](https://github.com/4lwayz/portwatch-vi) | 3139 | 933 | +1725 | 3.4 | — | portwatch vi · 4lwayz portwatch vi | Does GTA VI run on PC yet? A live tracker of community recom… |
| [ubiquitarianism/leonida](https://github.com/ubiquitarianism/leonida) | 2035 | 1521 | +1206 | 1.3 | — | leonida · ubiquitarianism leonida | A continuation of Leonida, the Xbox > PC port interface for… |
| [erkamyaman/rust-anything](https://github.com/erkamyaman/rust-anything) | 9356 | 1060 | +415 | 8.8 | [1](https://news.ycombinator.com/item?id=50558549) | rust anything · erkamyaman rust anything · erkam rust anything | Rewrite your whole app in Rust, one piece at a time, checked… |
| [EL4CTEO/fast-anything](https://github.com/EL4CTEO/fast-anything) | 3734 | 1003 | +372 | 3.7 | [213](https://news.ycombinator.com/item?id=50596155) | fast anything · el4cteo fast anything | Don't rewrite it in Rust. Rewrite the 5% that's slow: profil… |
| 🆕 [Zettrox/ztrx](https://github.com/Zettrox/ztrx) | 982 | 982 | — | 1 | — | ztrx · zettrox ztrx | Run the Xbox Series build of the game natively on Windows PC… |
| [AFK-surf/xnulinux](https://github.com/AFK-surf/xnulinux) | 3596 | 733 | +910 | 4.9 | [623](https://news.ycombinator.com/item?id=50607261) | xnulinux · afk-surf xnulinux · afk xnulinux | XNU as a loadable kernel module inside Linux (macOS personal… |
| 🆕 [Indigo-0167/universal-game-mod-manager](https://github.com/Indigo-0167/universal-game-mod-manager) | 1075 | 747 | — | 1.4 | — | universal game mod manager · indigo-0167 universal game mod manager | Free Windows game mod manager to discover, install, update a… |
| 🆕 [zero5122/offline-file-converter-windows](https://github.com/zero5122/offline-file-converter-windows) | 1059 | 739 | — | 1.4 | — | offline file converter windows · zero5122 offline file converter windows | Free offline file converter for Windows – convert PDF, docum… |
| 🆕 [Umbra9179/clipboard-history-manager-windows](https://github.com/Umbra9179/clipboard-history-manager-windows) | 1050 | 734 | — | 1.4 | — | clipboard history manager windows · umbra9179 clipboard history manager windows | Free open-source Windows clipboard manager with searchable h… |
| 🆕 [solv4626/steam-achievement-manager-windows](https://github.com/solv4626/steam-achievement-manager-windows) | 1048 | 729 | — | 1.4 | — | steam achievement manager windows · solv4626 steam achievement manager windows | Free open-source Steam Achievement Manager for Windows to ma… |
| 🆕 [kai415-debug/ffmpeg-video-audio-converter](https://github.com/kai415-debug/ffmpeg-video-audio-converter) | 1024 | 713 | — | 1.4 | — | ffmpeg video audio converter · kai415-debug ffmpeg video audio converter | Free Windows FFmpeg GUI for video and audio conversion, batc… |
| [Hut-hzf/ung220z-tool](https://github.com/Hut-hzf/ung220z-tool) | 4635 | 470 | +674 | 9.9 | — | ung220z tool · hut-hzf ung220z tool | ung220z-tool 是一个针对 UNG220Z，另含中兴/烽火/华为/九联多厂商适配、固件指纹识别与分家族排障建议… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 94 | 🟢 窗口内 | [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) | Python | 2532 | +173 | +2532 | +0 | `·······▇█▅▄▃▃·` | 5 | — | — |
| 2 | 90.8 | 🟢 窗口内 | [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) | Python | 1971 | +357 | +1929 | +42 | `····▁▁▁▁▁▁█▆▄·` | 8 | — | — |
| 3 | 87.5 | 🟢 窗口内 | [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) | Python | 2619 | +259 | +1463 | +1156 | `····▆█▃▂▂▆▄▅▄·` | 8 | — | — |
| 4 | 86.5 | 🟢 窗口内 | [Lemxy/WinRust](https://github.com/Lemxy/WinRust) | Rust | 1500 | +79 | +1348 | +152 | `·····▃▂█▇▅▇▄▃·` | 7 | — | — |
| 5 | 86.4 | 🟢 窗口内 | [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) | TypeScript | 1340 | +495 | +1334 | +6 | `······▁▁▃▂▆▄█▁` | 6 | — | — |
| 6 | 80.7 | 🆕 🟢 窗口内 | [danielwh2/sprite-stacking](https://github.com/danielwh2/sprite-stacking) | HTML | 834 | +118 | +834 | +0 | `········██▆▇▅·` | 4 | — | — |
| 7 | 80.1 | 🟢 窗口内 | [qianyiai/kurocat](https://github.com/qianyiai/kurocat) | TypeScript | 791 | +288 | +791 | +0 | `·········▁▅▆█▁` | 3 | — | — |
| 8 | 79.6 | 🟢 窗口内 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Rust | 2743 | +44 | +758 | +344 | `▃▂▂▁▁▂▂▂█▄▃▂▂·` | 23 | — | — |
| 9 | 76.2 | 🟢 窗口内 | [w01fb0ss/PiBot](https://github.com/w01fb0ss/PiBot) | TypeScript | 571 | +42 | +571 | +0 | `·········█▇▃▂·` | 4 | — | — |
| 10 | 72.5 | 🆕 🟢 窗口内 | [tweak-for-me/impulse](https://github.com/tweak-for-me/impulse) | Rust | 418 | — | +418 | +0 | `········▆█▆▆▅·` | 4 | — | — |
| 11 | 66.5 | 🟢 窗口内 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | TypeScript | 2890 | +20 | +254 | +222 | `▅▃▂▃▃▄▄▃▃▂██▃·` | 24 | — | — |
| 12 | 57.2 | 🟡 在降温 | [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) | TypeScript | 2029 | +27 | +304 | +1120 | `█▂▂▃▂▂▁▁▂▂▂▁▁·` | 16 | [5](https://news.ycombinator.com/item?id=49789538) | — |
| 13 | 56.7 | 🟡 在降温 | [DIYgod/pinky](https://github.com/DIYgod/pinky) | Go | 2773 | +36 | +288 | +589 | `█▅▅▅▅▆▅▅▄▃▃▃▃·` | 18 | — | — |
| 14 | 53.5 | 🟡 在降温 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode) | Python | 2943 | +15 | +210 | +489 | `█▆▅▄▄▅▄▄▃▂▄▃▂·` | 21 | — | — |
| 15 | 51.5 | 🟡 在降温 | [boringmarketer/boring-marketing-skills](https://github.com/boringmarketer/boring-marketing-skills) | Python | 849 | +26 | +172 | +677 | `····██▃▂▂▂▁▁▂·` | 8 | — | — |
| 16 | 41.3 | 🆕 🔴 先核对 | [Avaneesh-Inamdar/Stream-Tube-Desktop](https://github.com/Avaneesh-Inamdar/Stream-Tube-Desktop) | Rust | 973 | — | +973 | +0 | `··········▂▄█·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 39.3 | 🔴 先核对 | [Ahmet-Dedeler/awesome-gta6-reverse-engineering](https://github.com/Ahmet-Dedeler/awesome-gta6-reverse-engineering) | HTML | 703 | +75 | +703 | +0 | `·········▁▅█▃·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 38.9 | 🔴 先核对 | [erkamyaman/safe-anything](https://github.com/erkamyaman/safe-anything) | Rust | 651 | +104 | +651 | +0 | `··········▄█▃·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 38.2 | 🆕 🔴 先核对 | [Developing-Gamer/agent-sim](https://github.com/Developing-Gamer/agent-sim) | Rust | 577 | — | +577 | +0 | `···········▇█·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 20.9 | 🆕 🔴 先核对 | [Indigo-0167/universal-game-mod-manager](https://github.com/Indigo-0167/universal-game-mod-manager) | Rust | 1074 | — | +1074 | +0 | `············█▁` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1% |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 1046 | 30 | 41505 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DIYgod/pinky](https://github.com/DIYgod/pinky) |
| `rust` | 202 | 30 | 27884 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker)、[s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[Renly1994/xiaotang-daozai](https://github.com/Renly1994/xiaotang-daozai) |
| `mcp` | 202 | 30 | 27063 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[lexifina/global-law](https://github.com/lexifina/global-law)、[andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) |
| `local-first` | 64 | 30 | 12531 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping)、[DuskBotAI/duskbot](https://github.com/DuskBotAI/duskbot) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 29 | 28719 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DIYgod/pinky](https://github.com/DIYgod/pinky)、[sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) |
| `codex` | 22 | 17749 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat)、[kubai087/kubai-icons](https://github.com/kubai087/kubai-icons) |
| `ai-agents` | 21 | 17623 | [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat)、[pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers)、[JosssphZhou/poki](https://github.com/JosssphZhou/poki) |
| `windows` | 19 | 12604 | [Renly1994/xiaotang-daozai](https://github.com/Renly1994/xiaotang-daozai)、[simpsoka/zigzag](https://github.com/simpsoka/zigzag)、[Indigo-0167/universal-game-mod-manager](https://github.com/Indigo-0167/universal-game-mod-manager) |
| `mcp-server` | 16 | 10777 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[INK-Q/agy-fast](https://github.com/INK-Q/agy-fast)、[21stware/bowel](https://github.com/21stware/bowel) |
| `model-context-protocol` | 13 | 9245 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki)、[INK-Q/agy-fast](https://github.com/INK-Q/agy-fast)、[simpsoka/zigzag](https://github.com/simpsoka/zigzag) |
| `llm` | 12 | 13605 | [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill)、[agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat)、[pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) |
| `agent-skills` | 12 | 11896 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[kubai087/kubai-icons](https://github.com/kubai087/kubai-icons)、[Dodaios/ste80-humanizer](https://github.com/Dodaios/ste80-humanizer) |
| `macos` | 12 | 6290 | [simpsoka/zigzag](https://github.com/simpsoka/zigzag)、[qianyiai/kurocat](https://github.com/qianyiai/kurocat)、[21stware/bowel](https://github.com/21stware/bowel) |
| `developer-tools` | 11 | 5232 | [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast)、[alexeyw/lot-map](https://github.com/alexeyw/lot-map)、[devvmhq/devvm](https://github.com/devvmhq/devvm) |
| `desktop-app` | 9 | 5415 | [Avaneesh-Inamdar/Stream-Tube-Desktop](https://github.com/Avaneesh-Inamdar/Stream-Tube-Desktop)、[harshsinghsv/swiftdl](https://github.com/harshsinghsv/swiftdl)、[DuskBotAI/duskbot](https://github.com/DuskBotAI/duskbot) |
| `ai-agent` | 8 | 6758 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[INK-Q/agy-fast](https://github.com/INK-Q/agy-fast)、[aa1143/NamiAgent](https://github.com/aa1143/NamiAgent) |

**语言分布**：Rust 28 · TypeScript 28 · Python 20 · JavaScript 7 · Go 6 · HTML 3 · C# 1 · C++ 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) · 🟢 窗口内 · 94 分

> Paste a link, get captioned 9:16 clips in ~2 min. Free, local, open-source clipping engine (audio-first, YouTube captions, local LLM).

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2532 | +2532 | +0 | 159 | 35 | Python | AGPL-3.0 | 11-19（5 天前） | 今天 |

- **近 14 天每天新增**：`·······▇█▅▄▃▃·` 0 0 0 0 0 0 0 656 727 458 331 167 193 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-video-clipper` `clipping` `faster-whisper` `ffmpeg` `gameplay-clipper` `local-llm` `ollama` `open-source-video-editor` `opusclip-alternative` `shorts` `twitch-clips` `vertical-video` `video` `whisper` `youtube-shorts-generator` `yt-dlp`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) · 🟢 窗口内 · 90.8 分

> 20 AI testers on 20 different phones, in parallel, on GitHub's free runners: Claude Code agents on iOS Simulators and Android emulators that find broken flows, translation, layout and accessibility bugs

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1971 | +1929 | +42 | 196 | 1 | Python | MIT | 11-16（8 天前） | 今天 |

- **近 14 天每天新增**：`····▁▁▁▁▁▁█▆▄·` 0 0 0 0 17 14 11 4 3 8 865 658 391 0
- **势头**：比前 7 天快 45.9 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`accessibility-testing` `ai-agents` `ai-testing` `android` `android-emulator` `claude` `claude-code` `e2e-testing` `exploratory-testing` `expo` `flutter` `github-actions` `ios` `ios-simulator` `llm` `mobile-testing` `qa` `react-native` `test-automation` `ui-testing`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) · 🟢 窗口内 · 87.5 分

> Agent skill for hill-climbing local LLM serving speed (decode, speculative decoding, prefill, KV, startup, TTFT) on any hardware and quantization

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2619 | +1463 | +1156 | 238 | 25 | Python | MIT | 11-16（8 天前） | 8 天前 |

- **近 14 天每天新增**：`····▆█▃▂▂▆▄▅▄·` 0 0 0 0 401 576 179 113 107 407 221 332 283 0
- **势头**：比前 7 天快 1.3 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `benchmarking` `claude-code` `inference` `llm` `speculative-decoding`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [Lemxy/WinRust](https://github.com/Lemxy/WinRust) · 🟢 窗口内 · 86.5 分

> Windows shell replacement in Rust: taskbar, file manager, NTFS search, task manager, disk cleaner. One installer exe.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1500 | +1348 | +152 | 99 | 56 | Rust | Apache-2.0 | 11-17（7 天前） | 今天 |

- **近 14 天每天新增**：`·····▃▂█▇▅▇▄▃·` 0 0 0 0 0 80 72 347 298 183 300 126 94 0
- **势头**：比前 7 天快 8.9 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) · 🟢 窗口内 · 86.4 分

> Non-invasive MCP accelerator plugin for Google Antigravity (CLI/Desktop/IDE): cuts LLM turns (-34%), token quota (-31%), and upload traffic (-40%) without affecting native UI or diffs.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1340 | +1334 | +6 | 79 | 32 | TypeScript | MIT | 11-19（6 天前） | 今天 |

- **近 14 天每天新增**：`······▁▁▃▂▆▄█▁` 0 0 0 0 0 0 6 34 168 53 373 198 507 1
- **势头**：比前 7 天快 222.3 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `ai-coding` `antigravity` `antigravity-cli` `antigravity-ide` `antigravity-plugins` `coding-agent` `context-optimization` `developer-productivity` `developer-tools` `gemini` `google-antigravity` `latency-optimization` `mcp` `mcp-plugin` `mcp-server` `model-context-protocol` `performance` `plugin` `token-optimization`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. 🆕 [danielwh2/sprite-stacking](https://github.com/danielwh2/sprite-stacking) · 🟢 窗口内 · 80.7 分

> Agent skill: turn four pixel art views into fake-3D sprites you can spin. Works with Claude Code, Codex, Cursor, OpenCode, Gemini CLI, Pi.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 834 | +834 | +0 | 67 | 1 | HTML | MIT | 11-20（4 天前） | 今天 |

- **近 14 天每天新增**：`········██▆▇▅·` 0 0 0 0 0 0 0 0 200 201 138 166 129 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `claude-code` `codex` `cursor` `fake-3d` `gamedev` `pixel-art` `sprite-stacking` `voxel`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [qianyiai/kurocat](https://github.com/qianyiai/kurocat) · 🟢 窗口内 · 80.1 分

> KuroCat — Free open-source desktop typing cat pet & OBS overlay (Bongo Cat alternative, Tauri v2 + Rust + MCP)｜轻量级透明置顶桌面打字小黑猫伴侣（6款猫咪+鲸鱼娘大肥鱼 / 输密码防偷窥 / OBS透明源 / AI捏猫 / Win·Mac·Linux·Android）

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 791 | +791 | +0 | 126 | 40 | TypeScript | MIT | 11-21（3 天前） | 今天 |

- **近 14 天每天新增**：`·········▁▅▆█▁` 0 0 0 0 0 0 0 0 0 18 205 236 331 1
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`android` `bongo-cat` `bongocat` `cross-platform` `desktop-pet` `keyboard-visualizer` `kurocat` `linux` `macos` `mcp` `obs-studio` `open-source` `rust` `tauri` `typing-cat` `windows`
- **主页**：<https://qianyi.one/kurocat/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) · 🟢 窗口内 · 79.6 分

> Blazing-fast native notes app and rich-text editor for macOS, Windows, and Linux. Built with Rust + GPUI. Local-first and beautifully designed.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2743 | +758 | +344 | 238 | 40 | Rust | MIT | 11-01（23 天前） | 今天 |

- **近 14 天每天新增**：`▃▂▂▁▁▂▂▂█▄▃▂▂·` 87 64 66 21 26 46 34 29 368 182 88 44 47 0
- **势头**：比前 7 天快 2.2 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://quiet.md>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 9. [w01fb0ss/PiBot](https://github.com/w01fb0ss/PiBot) · 🟢 窗口内 · 76.2 分

> Open-source, local-first AI agent team for your desktop: multi-agent group chats, computer use, browser, MCP, routines and approvals. macOS, Windows, Linux + Android. Built on pi.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 571 | +571 | +0 | 86 | 8 | TypeScript | Apache-2.0 | 11-21（4 天前） | 今天 |

- **近 14 天每天新增**：`·········█▇▃▂·` 0 0 0 0 0 0 0 0 0 248 196 78 49 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent` `ai-agent` `ai-agents` `ai-assistant` `android` `automation` `chatgpt` `coding-agent` `computer-use` `desktop-app` `electron` `llm` `local-first` `mcp` `multi-agent` `ollama` `openai` `privacy` `self-hosted` `typescript`
- **主页**：<https://pibot.space>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 10. 🆕 [tweak-for-me/impulse](https://github.com/tweak-for-me/impulse) · 🟢 窗口内 · 72.5 分

> Lightweight alternative Windows client for game trainers: hotkeys, overlay and phone control.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 418 | +418 | +0 | 177 | 9 | Rust | GPL-3.0 | 11-20（4 天前） | 今天 |

- **近 14 天每天新增**：`········▆█▆▆▅·` 0 0 0 0 0 0 0 0 83 113 82 74 66 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`game-trainer` `gpui` `hotkeys` `overlay` `rust` `windows`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [Avaneesh-Inamdar/Stream-Tube-Desktop](https://github.com/Avaneesh-Inamdar/Stream-Tube-Desktop) — 一天进了一半以上的 star，但 HN 上没火过
- [Ahmet-Dedeler/awesome-gta6-reverse-engineering](https://github.com/Ahmet-Dedeler/awesome-gta6-reverse-engineering) — 一天进了一半以上的 star，但 HN 上没火过
- [erkamyaman/safe-anything](https://github.com/erkamyaman/safe-anything) — 一天进了一半以上的 star，但 HN 上没火过
- [Developing-Gamer/agent-sim](https://github.com/Developing-Gamer/agent-sim) — 一天进了一半以上的 star，但 HN 上没火过
- [Indigo-0167/universal-game-mod-manager](https://github.com/Indigo-0167/universal-game-mod-manager) — 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1%

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 360 | 89 | [Show HN: I built a game where you are an LLM's subagent](https://github.com/gulivan/worker755) | [HN](https://news.ycombinator.com/item?id=50599762) |
| 252 | 94 | [Show HN: ExitPath – Open-source ways out of Slack, Notion and Microsoft 365](https://exitpath-ruddy.vercel.app/) | [HN](https://news.ycombinator.com/item?id=50547980) |
| 241 | 60 | [Show HN: Take Voyager 1 apart, down to a single memory chip](https://rshekhar.com/voyager/) | [HN](https://news.ycombinator.com/item?id=50548161) |
| 238 | 122 | [Show HN: Cornhole News – A Hacker News inspired site for news across the Midwest](https://cornholenews.news) | [HN](https://news.ycombinator.com/item?id=50561515) |
| 180 | 137 | [Show HN: Zero C# – C# without a runtime or GC](https://onurgumus.github.io/zero-csharp/index.html) | [HN](https://news.ycombinator.com/item?id=50590279) |
| 159 | 45 | [Show HN: Mastra Factory, the open-source software factory we use to build Mastra](https://news.ycombinator.com/item?id=50548660) | [HN](https://news.ycombinator.com/item?id=50548660) |
| 152 | 76 | [Show HN: Type Fighter 2](https://typefighter2.com/) | [HN](https://news.ycombinator.com/item?id=50544821) |
| 142 | 52 | [Show HN: Fast deterministic natural language search for OpenStreetMap data](https://hippomaps.ch/?q=cafes+by+the+Limmat+100+m+from+the+lake+in+zurich#map=15.02/47.36708/8.54935) | [HN](https://news.ycombinator.com/item?id=50561199) |
| 133 | 96 | [Show HN: Foolscap – a writing app that reads your book and never writes for you](https://foolscap.works/) | [HN](https://news.ycombinator.com/item?id=50559749) |
| 130 | 95 | [Show HN: Drive around my village in 3D](https://cherwellvalleymotorclub.app) | [HN](https://news.ycombinator.com/item?id=50574412) |
| 129 | 36 | [Show HN: OpenComputer – an open source alternative to Devin](https://github.com/diggerhq/opencomputer) | [HN](https://news.ycombinator.com/item?id=50581403) |
| 94 | 18 | [Show HN: Mason – A lightweight Postgres read-replica, built on columnar storage](https://masondata.ai/) | [HN](https://news.ycombinator.com/item?id=50630294) |
| 89 | 60 | [Show HN: The Riemann Proof Handbook](https://github.com/tamnd/riemann-handbook) | [HN](https://news.ycombinator.com/item?id=50596664) |
| 72 | 14 | [Show HN: Old Nvidia and ATI tech demos, running again in the browser](https://gpu-demo-gallery.pages.dev/) | [HN](https://news.ycombinator.com/item?id=50638503) |
| 51 | 38 | [Show HN: I made a PS1 style racing game](https://outpostracer.com) | [HN](https://news.ycombinator.com/item?id=50589184) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 17 | [PaperOrchestra: A Multi-Agent Framework for Automated AI Research Paper Writing](https://huggingface.co/papers/2604.05018) | PaperOrchestra is a multi-agent framework that converts unstructured research materials into complete LaTeX manuscripts with literature synt… | [google-research/paper-orchestra](https://github.com/google-research/paper-orchestra) 6282★ |
| 111 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 32689★ |
| 39 | [Depth Pro 2: Sharp and Temporally Consistent Metric Monocular Depth](https://huggingface.co/papers/2611.26603) | A single scalable network estimates dense metric depth for images and video at native resolution, jointly improving metric accuracy, boundar… | 💡 [apple-aiml-research/ml-depth-pro-2](https://github.com/apple-aiml-research/ml-depth-pro-2) 723★ |
| 71 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 25118★ |
| 163 | [Gamer: A Generalist Vision-Language-Action Foundation Model for Long-Horizon Real-Time Game Agent](https://huggingface.co/papers/2611.18397) | Gamer is a generalist agent framework that integrates perception, memory, and multi-step reasoning, trained through continued pre-training,… | [RainBowLuoCS/Gamer](https://github.com/RainBowLuoCS/Gamer) 1487★ |
| 169 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 123698★ |
| 98 | [Embo-Harness: Towards Understanding Frontier-Model-as-Policy Harness](https://huggingface.co/papers/2611.31201) | A systematic framework shows that frontier multimodal models can serve as robot policies when harnessed with interfaces favoring native visu… | 💡 [DravenALG/Embo-Harness](https://github.com/DravenALG/Embo-Harness) 59★ |
| 21 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 8072★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 86 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 94256★ |
| 157 | [ARIS: Autonomous Research via Adversarial Multi-Agent Collaboration](https://huggingface.co/papers/2605.03042) | ARIS is an open-source research harness that uses cross-model adversarial collaboration to ensure reliable long-term research outcomes throu… | [wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) 19817★ |
| 72 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 36657★ |
| 38 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 36652★ |
| 110 | [FreeToken: Efficient Edge-Native MoE Serving with Bandwidth-Adaptive Execution](https://huggingface.co/papers/2608.16157) | FreeToken is an edge-native Mixture-of-Experts serving system that dynamically maps computation and model state onto heterogeneous local har… | [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken) 17755★ |
| 36 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 12300★ |
| 21 | [π^4: A Foundation Model for 4D Scene Geometry and Motion](https://huggingface.co/papers/2611.23144) | This unified foundation model enables the recovery of dense geometry, camera poses, and object tracking from diverse, uncalibrated observati… | 💡 [yyfz/Pi4](https://github.com/yyfz/Pi4) 495★ |
| 184 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 84296★ |
| 3 | [LittleBit: Ultra Low-Bit Quantization via Latent Factorization](https://huggingface.co/papers/2506.13771) | LittleBit is a novel method for extreme compression of large language models using low-rank factorization and multi-scale compensation, achi… | 💡 [SamsungLabs/LittleBit](https://github.com/SamsungLabs/LittleBit) 881★ |
| 22 | [Bitnet.cpp: Efficient Edge Inference for Ternary LLMs](https://huggingface.co/papers/2502.11880) | Bitnet.cpp enhances edge inference for ternary LLMs using a novel mixed-precision matrix multiplication library, achieving significant speed… | [microsoft/BitNet](https://github.com/microsoft/BitNet) 42463★ |
| 40 | [Geometric Context Transformer for Streaming 3D Reconstruction](https://huggingface.co/papers/2604.14141) | LingBot-Map is a feed-forward 3D foundation model that reconstructs scenes from video streams using a geometric context transformer architec… | [robbyant/lingbot-map](https://github.com/robbyant/lingbot-map) 19073★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 10 | [ternary bonsai 2.5](https://huggingface.co/prism-ml/Ternary-Bonsai-2.5-27B-GGUF) | text-generation | 171 | 1 |
| 50 | [raon 1 mini](https://huggingface.co/KRAFTON/Raon-1-mini) | text-generation | 62 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 32 | 1 | [Pokemon Childhood Version: A romhack where Mew is under the truck](https://wheybags.com/blog/pokemon_childhood_version.html) | `assembly` `games` | [讨论](https://lobste.rs/s/em9zdb/pokemon_childhood_version_romhack_where) |
| 102 | 6 | [2035 came early](https://fzakaria.com/2026/11/23/2035-came-early) | `nix` `wasm` | [讨论](https://lobste.rs/s/rkk6o8/2035_came_early) |
| 57 | 6 | [Security incident on Hex.pm](https://hex.pm/blog/security-incident-on-hexpm) | `elixir` `erlang` `gleam` | [讨论](https://lobste.rs/s/rfcgkx/security_incident_on_hex_pm) |
| 32 | 2 | [Why there are still no non-WebKit browsers on iOS](https://blog.mozilla.org/en/mozilla/internet-policy/apple-ios-browser-engine-rules/) | `browsers` `ios` | [讨论](https://lobste.rs/s/sv2flr/why_there_are_still_no_non_webkit_browsers) |
| 67 | 5 | [I checked Clojure's core with Lean and found 17 unreported bugs](https://s.conao3.com/blog/2026/e4f733) | `clojure` | [讨论](https://lobste.rs/s/yyktrz/i_checked_clojure_s_core_with_lean_found_17) |
| 13 | 1 | [Marginalia Search, Money, C++, Rust, AI, stuff](https://www.marginalia.nu/log/a_141_marginalia_update/) | `c++` `java` `performance` | [讨论](https://lobste.rs/s/srb0dp/marginalia_search_money_c_rust_ai_stuff) |
| 30 | 10 | [Per Vognsen on the effect of AVX-512 on lexing and parsing](https://mastodon.social/@pervognsen/117668394962974183) | `compilers` `performance` | [讨论](https://lobste.rs/s/m7gqr6/per_vognsen_on_effect_avx_512_on_lexing) |
| 11 | 1 | [Abolish Lock Poisoning](https://lucumr.pocoo.org/2026/11/25/poisoning/) | `rust` | [讨论](https://lobste.rs/s/sj2pkv/abolish_lock_poisoning) |
| 12 | 3 | [9/UX: a Macintosh-inspired desktop for 9front](https://progrium.github.io/9ux/) | `ai` `osdev` | [讨论](https://lobste.rs/s/vciex6/9_ux_macintosh_inspired_desktop_for) |
| 7 | 4 | [A faster algorithm for extracting hexadecimal digits of π](https://www.stylewarning.com/posts/faster-digit-extraction/) | `compsci` | [讨论](https://lobste.rs/s/qavfgc/faster_algorithm_for_extracting) |
| 16 | 2 | [Beyond Linux: A Journey Through the Open Source Ecosystem](https://it-notes.dragas.net/2026/11/17/beyond-linux-a-journey-through-the-open-source-ecosystem/) | `freebsd` `netbsd` `openbsd` | [讨论](https://lobste.rs/s/y56k2b/beyond_linux_journey_through_open_source) |
| 2 | 3 | [Matrix Multiplication is Θ(n^2.25)](https://raw.githubusercontent.com/openai/math/main/preprints/The-matrix-multiplication-exponent-is-nine-fourths-November-24-2026/paper.pdf) | `ai` `math` `pdf` | [讨论](https://lobste.rs/s/kn0pmh/matrix_multiplication_is_n_2_25) |
| 118 | 65 | [Ladybird is now in alpha](https://ladybird.org/posts/alpha/) | `browsers` | [讨论](https://lobste.rs/s/h6webg/ladybird_is_now_alpha) |
| 41 | 8 | [What VP != VNP Means (In 3 Minutes)](https://www.friedgil.com/vpvnp/) | `math` | [讨论](https://lobste.rs/s/2k95fs/what_vp_vnp_means_3_minutes) |
| 3 | 0 | [Flat/non-higher-order construction of ANF via mutable holes](https://blueberrywren.dev/blog/anf-mutable/) | `ml` `plt` | [讨论](https://lobste.rs/s/n0itvf/flat_non_higher_order_construction_anf) |
| 15 | 4 | [Bypassing iOS Safari 60 FPS Limit](https://rida.dev/blog/bypassing-ios-safari-60-fps-limit) | `browsers` `graphics` `mobile` | [讨论](https://lobste.rs/s/pxvmxo/bypassing_ios_safari_60_fps_limit) |
| 5 | 1 | [Dutch data protection authority advises against purchasing AI camera glasses](https://autoriteitpersoonsgegevens.nl/en/current/ap-advises-against-purchasing-ai-camera-glasses-serious-risks-for-users-and-bystanders) | `privacy` | [讨论](https://lobste.rs/s/l7fel2/dutch_data_protection_authority_advises) |
| 6 | 0 | [From formal verification to bug-finding in CHERIoT](https://cheriot.org/verification/2026/11/24/griotte-verification-effort.html) | `formalmethods` `security` | [讨论](https://lobste.rs/s/khb1yv/from_formal_verification_bug_finding) |
| 40 | 12 | [Lua for data representation](https://citrons.xyz/journal/2025-07-23) | `lua` | [讨论](https://lobste.rs/s/ezml41/lua_for_data_representation) |
| 2 | 0 | [Needles, Haystacks, and Numbers Between 0 and 1](https://rustfoundation.org/media/needles-haystacks-and-numbers-between-0-and-1/) | `rust` | [讨论](https://lobste.rs/s/5gefep/needles_haystacks_numbers_between_0_1) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 106 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 77 | 55 | 71% | — |
| 🔴 先核对 | 43 | 25 | 58% | 0 天 |
| 🟡 在降温 | 6 | 0 | 0% | — |
| 🔵 已被发现 | 4 | 2 | 50% | — |
| 💤 不活跃 | 1 | 0 | 0% | — |
| 🟢 窗口内 | 25 | 11 | 44% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [Kianuni/Erosion-CN](https://github.com/Kianuni/Erosion-CN) | 2026-11-11 | 🚀 爆发 | 1238 | 2826 | 0 | ✅ 起来了 |
| [Lee-xeo/Claude-Cage](https://github.com/Lee-xeo/Claude-Cage) | 2026-11-11 | 🚀 爆发 | 1487 | 8438 | 0 | ✅ 起来了 |
| [SK-Dev666/rust-external-trainer-tool](https://github.com/SK-Dev666/rust-external-trainer-tool) | 2026-11-11 | 🔴 先核对 | 773 | 0 | 0 | 仓库没了 |
| [expo/exact](https://github.com/expo/exact) | 2026-11-11 | 🔵 已被发现 | 2346 | 5071 | 137 | ✅ 起来了 |
| [reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA) | 2026-11-11 | 🟢 窗口内 | 2494 | 3493 | 0 | 没起来 |

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
