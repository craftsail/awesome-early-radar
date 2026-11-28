# early-radar 选题雷达 · 2026-11-28

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 104 个，细查前 20 个 · 比上次 = 和 2026-11-27 那次比 · 生成于 2026-11-28 07:22 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 1 个 · Show HN ✅ 21 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 3 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 10 个 · 🟡 在降温 4 个 · 🔵 已被发现 1 个 · 💤 不活跃 0 个 · 🔴 先核对 5 个
- **今天新出现 2 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [Marvisak/VIctory](https://github.com/Marvisak/VIctory) 平均每天 +3157，见 [爆发](#爆发)
- **复盘**：🚀 爆发 59/82 · 🔴 先核对 27/45 · 🟡 在降温 0/6 · 🔵 已被发现 3/5 · 💤 不活跃 0/1 · 🟢 窗口内 12/26（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) — 20 AI testers on 20 different phones, in parallel, on GitHub…（近 7 天 +2585，比前 7 天快 45.4 倍，在加速）
  - [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) — Non-invasive MCP accelerator plugin for Google Antigravity (…（近 7 天 +1839，比前 7 天快 7.2 倍，在加速）
  - [qianyiai/KuroCat](https://github.com/qianyiai/KuroCat) — KuroCat — Free open-source 3D/2D desktop typing cat & AI com…（近 7 天 +1801，比前 7 天快 100.1 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 28 个（star 合计 34031），代表：[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill)、[DIYgod/pinky](https://github.com/DIYgod/pinky)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：5 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: bouncemarket – a live prediction market game for a bouncing ball](https://bouncemarket.minhanhday.com/) — 363 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [Marvisak/VIctory](https://github.com/Marvisak/VIctory) | 13887 | 3157 | +366 | 4.4 | [1](https://news.ycombinator.com/item?id=50622253) | victory · marvisak victory · marvis victory | An attempt at running GTA VI on PC |
| 🆕 [trustno1-coder/VIctory-NVIDIA](https://github.com/trustno1-coder/VIctory-NVIDIA) | 4338 | 1866 | — | 2.3 | — | victory nvidia · trustno1-coder victory nvidia | VIctory (Xbox Series compatibility layer) tuned for NVIDIA R… |
| [xcl-dev/xcl](https://github.com/xcl-dev/xcl) | 8763 | 1173 | +118 | 7.5 | [49](https://news.ycombinator.com/item?id=44859763) | xcl · xcl-dev xcl · xcl xcl | Xbox Series compatibility layer for Windows - runs console g… |
| [4lwayz/portwatch-vi](https://github.com/4lwayz/portwatch-vi) | 6886 | 1087 | +786 | 6.3 | — | portwatch vi · 4lwayz portwatch vi | Does GTA VI run on PC yet? A live tracker of community recom… |
| [Pixel679-cmyk/windows-titlebar-blur-customizer](https://github.com/Pixel679-cmyk/windows-titlebar-blur-customizer) | 1506 | 1065 | +823 | 1.4 | — | windows titlebar blur customizer · pixel679-cmyk windows titlebar blur customizer | Customize Windows 10 and 11 title bar effects with Aero, Acr… |
| [nexu-io/opengame](https://github.com/nexu-io/opengame) | 2480 | 865 | +974 | 2.9 | — | opengame · nexu-io opengame · opendesign opengame | The Super Game Agent — the Unity & Unreal for AI agents, wit… |
| [fxceless/victory-fork](https://github.com/fxceless/victory-fork) | 3366 | 947 | +64 | 3.6 | — | victory fork · fxceless victory fork · hyphen victory fork | Work-in-progress fork of VIctory: getting an Xbox Series tit… |
| [erkamyaman/rust-anything](https://github.com/erkamyaman/rust-anything) | 10894 | 923 | +470 | 11.8 | [1](https://news.ycombinator.com/item?id=50558549) | rust anything · erkamyaman rust anything · erkam rust anything | Rewrite your app in Rust, piece by piece, checked against th… |
| 🆕 [riveran0226/windows-explorer-blur-mica](https://github.com/riveran0226/windows-explorer-blur-mica) | 915 | 915 | — | 1 | — | windows explorer blur mica · riveran0226 windows explorer blur mica | Free Windows 10 & 11 Explorer customization tool for Acrylic… |
| 🆕 [flint63-code/gitdesk-windows](https://github.com/flint63-code/gitdesk-windows) | 908 | 908 | — | 1 | — | gitdesk windows · flint63-code gitdesk windows | Free open-source Git GUI client for Windows with visual comm… |
| 🆕 [mist-8659/windows-mouse-keyboard-sharing-kvm](https://github.com/mist-8659/windows-mouse-keyboard-sharing-kvm) | 907 | 907 | — | 1 | — | windows mouse keyboard sharing kvm · mist-8659 windows mouse keyboard sharing kvm | Free open-source KVM software to share one keyboard and mous… |
| 🆕 [nocta1554/windows-video-downloader-gui](https://github.com/nocta1554/windows-video-downloader-gui) | 904 | 904 | — | 1 | — | windows video downloader gui · nocta1554 windows video downloader gui | Free open-source Windows video downloader GUI for YouTube an… |
| 🆕 [Red2076-arch/waifu2x-image-upscaler-windows](https://github.com/Red2076-arch/waifu2x-image-upscaler-windows) | 900 | 900 | — | 1 | — | waifu2x image upscaler windows · red2076-arch waifu2x image upscaler windows | Free AI image upscaler and photo denoiser for Windows powere… |
| 🆕 [leaf7684/windows-modern-media-player](https://github.com/leaf7684/windows-modern-media-player) | 898 | 898 | — | 1 | — | windows modern media player · leaf7684 windows modern media player | Free open-source Windows media player with VLC playback, vid… |
| 🆕 [hollow-445/windows-keyboard-manager](https://github.com/hollow-445/windows-keyboard-manager) | 897 | 897 | — | 1 | — | windows keyboard manager · hollow-445 windows keyboard manager | Free open-source keyboard remapping software for Windows wit… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 94.3 | 🟢 窗口内 | [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) | Python | 2642 | +97 | +2585 | +57 | `·▁▁▁▁▁▁█▆▄▄▂▂·` | 11 | [1](https://news.ycombinator.com/item?id=50655803) | — |
| 2 | 90.2 | 🟢 窗口内 | [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) | TypeScript | 2096 | +297 | +1839 | +257 | `···▁▁▃▂▆▄█▄▄▅·` | 9 | — | — |
| 3 | 90 | 🟢 窗口内 | [qianyiai/KuroCat](https://github.com/qianyiai/KuroCat) | TypeScript | 1819 | +230 | +1801 | +18 | `······▁▄▅▇▇█▅·` | 6 | — | — |
| 4 | 89.2 | 🟢 窗口内 | [Avaneesh-Inamdar/Stream-Tube-Desktop](https://github.com/Avaneesh-Inamdar/Stream-Tube-Desktop) | Rust | 1691 | +129 | +1691 | +0 | `·······▂▄█▅▄▂·` | 5 | — | — |
| 5 | 86.8 | 🟢 窗口内 | [ZigZagBoi1/ScarlettPort](https://github.com/ZigZagBoi1/ScarlettPort) | Rust | 1388 | +617 | +1388 | +0 | `·········▄▂▆█·` | 3 | — | — |
| 6 | 81.9 | 🟢 窗口内 | [xikhar/papercraft](https://github.com/xikhar/papercraft) | JavaScript | 1031 | +171 | +919 | +112 | `·····▂▄▆█▅▄▅▆·` | 7 | — | — |
| 7 | 80.8 | 🟢 窗口内 | [erkamyaman/safe-anything](https://github.com/erkamyaman/safe-anything) | Rust | 840 | +39 | +840 | +0 | `·······▄█▃▃▂▂·` | 5 | — | — |
| 8 | 80.6 | 🟢 窗口内 | [Ahmet-Dedeler/awesome-gta6-reverse-engineering](https://github.com/Ahmet-Dedeler/awesome-gta6-reverse-engineering) | HTML | 850 | +45 | +826 | +24 | `······▁▅█▃▂▂▂·` | 6 | — | — |
| 9 | 79.9 | 🟢 窗口内 | [chanke17/KuroCat](https://github.com/chanke17/KuroCat) | C++ | 780 | +61 | +780 | +0 | `·······▆█▇▇▅▃·` | 5 | — | — |
| 10 | 78.7 | 🟢 窗口内 | [danielwh2/sprite-stacking](https://github.com/danielwh2/sprite-stacking) | HTML | 1106 | +55 | +706 | +400 | `·····██▆▇▅▅▄▃·` | 7 | — | — |
| 11 | 70.1 | 🟡 在降温 | [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) | Python | 2952 | +155 | +1112 | +1840 | `····▇█▅▄▃▃▂▂▃·` | 8 | — | — |
| 12 | 70.1 | 🟡 在降温 | [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) | Python | 2891 | +51 | +1109 | +1782 | `·▆█▃▂▂▆▄▅▄▂▂▂·` | 11 | — | — |
| 13 | 66 | 🟡 在降温 | [Lemxy/WinRust](https://github.com/Lemxy/WinRust) | Rust | 1711 | +53 | +736 | +975 | `··▃▂█▇▅▇▄▃▃▃▂·` | 10 | — | — |
| 14 | 53.1 | 🟡 在降温 | [DIYgod/pinky](https://github.com/DIYgod/pinky) | Go | 2844 | +18 | +201 | +484 | `▇▆█▇▆▅▄▄▄▄▂▄▂·` | 21 | — | — |
| 15 | 46.9 | 🔴 先核对 | [nexu-io/opengame](https://github.com/nexu-io/opengame) | TypeScript | 2479 | +973 | +2480 | +0 | `··········▁█▅·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 16 | 41.1 | 🔴 先核对 | [zortos293/XSEmu](https://github.com/zortos293/XSEmu) | Rust | 939 | +179 | +939 | +0 | `···········█▃·` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 40.7 | 🆕 🔵 已被发现 | [gary23w/f-ck_data_brokers](https://github.com/gary23w/f-ck_data_brokers) | Python | 886 | +419 | +886 | +0 | `···········█▇·` | 1 | [245](https://news.ycombinator.com/item?id=50658191) | — |
| 18 | 38 | 🔴 先核对 | [ProjectLeonidaL/leonida](https://github.com/ProjectLeonidaL/leonida) | Rust | 558 | +37 | +558 | +0 | `········▂█▂▂▂·` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 37.5 | 🆕 🔴 先核对 | [stellarr-studio/kelvaroq](https://github.com/stellarr-studio/kelvaroq) | Python | 520 | +159 | +520 | +0 | `··········▂█▅·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 21.7 | 🔴 先核对 | [Indigo-0167/universal-game-mod-manager](https://github.com/Indigo-0167/universal-game-mod-manager) | Rust | 1372 | +71 | +1372 | +0 | `·········█▃▁▁·` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1% |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 1040 | 30 | 41727 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill)、[DIYgod/pinky](https://github.com/DIYgod/pinky) |
| `rust` | 234 | 30 | 30949 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[Renly1994/xiaotang-daozai](https://github.com/Renly1994/xiaotang-daozai)、[qianyiai/KuroCat](https://github.com/qianyiai/KuroCat) |
| `mcp` | 197 | 30 | 28871 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[nexu-io/opengame](https://github.com/nexu-io/opengame)、[JosssphZhou/poki](https://github.com/JosssphZhou/poki) |
| `local-first` | 68 | 30 | 15848 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping)、[nexu-io/opengame](https://github.com/nexu-io/opengame) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 28 | 34031 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill)、[DIYgod/pinky](https://github.com/DIYgod/pinky) |
| `codex` | 22 | 22018 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[nexu-io/opengame](https://github.com/nexu-io/opengame)、[agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) |
| `windows` | 22 | 19259 | [Renly1994/xiaotang-daozai](https://github.com/Renly1994/xiaotang-daozai)、[qianyiai/KuroCat](https://github.com/qianyiai/KuroCat)、[Avaneesh-Inamdar/Stream-Tube-Desktop](https://github.com/Avaneesh-Inamdar/Stream-Tube-Desktop) |
| `ai-agents` | 20 | 21267 | [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers)、[nexu-io/opengame](https://github.com/nexu-io/opengame)、[JosssphZhou/poki](https://github.com/JosssphZhou/poki) |
| `mcp-server` | 17 | 13259 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[INK-Q/agy-fast](https://github.com/INK-Q/agy-fast)、[gary23w/f-ck_data_brokers](https://github.com/gary23w/f-ck_data_brokers) |
| `model-context-protocol` | 13 | 10607 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki)、[INK-Q/agy-fast](https://github.com/INK-Q/agy-fast)、[simpsoka/zigzag](https://github.com/simpsoka/zigzag) |
| `llm` | 12 | 14913 | [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill)、[pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers)、[JosssphZhou/poki](https://github.com/JosssphZhou/poki) |
| `agent-skills` | 12 | 14669 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[nexu-io/opengame](https://github.com/nexu-io/opengame)、[kubai087/kubai-icons](https://github.com/kubai087/kubai-icons) |
| `macos` | 12 | 8101 | [qianyiai/KuroCat](https://github.com/qianyiai/KuroCat)、[simpsoka/zigzag](https://github.com/simpsoka/zigzag)、[21stware/bowel](https://github.com/21stware/bowel) |
| `3d-modeling` | 10 | 4721 | [credoksopho1984/blender-ai-copilot-studio](https://github.com/credoksopho1984/blender-ai-copilot-studio)、[tiobeharxi1987/blender-ai-copilot-flow](https://github.com/tiobeharxi1987/blender-ai-copilot-flow)、[Doug-218/blender-ai-copilot-forge](https://github.com/Doug-218/blender-ai-copilot-forge) |
| `developer-tools` | 9 | 5423 | [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast)、[alexeyw/lot-map](https://github.com/alexeyw/lot-map)、[devvmhq/devvm](https://github.com/devvmhq/devvm) |
| `3d-automation` | 9 | 4565 | [credoksopho1984/blender-ai-copilot-studio](https://github.com/credoksopho1984/blender-ai-copilot-studio)、[tiobeharxi1987/blender-ai-copilot-flow](https://github.com/tiobeharxi1987/blender-ai-copilot-flow)、[Doug-218/blender-ai-copilot-forge](https://github.com/Doug-218/blender-ai-copilot-forge) |

**语言分布**：Rust 29 · TypeScript 24 · Python 21 · JavaScript 6 · Go 5 · HTML 3 · C# 1 · C++ 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) · 🟢 窗口内 · 94.3 分

> 20 AI testers on 20 different phones, in parallel, on GitHub's free runners: Claude Code agents on iOS Simulators and Android emulators that find broken flows, translation, layout and accessibility bugs

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2642 | +2585 | +57 | 271 | 8 | Python | MIT | 11-16（11 天前） | 今天 |

- **近 14 天每天新增**：`·▁▁▁▁▁▁█▆▄▄▂▂·` 0 17 14 11 4 3 8 865 658 391 419 155 97 0
- **势头**：比前 7 天快 45.4 倍，在加速
- **HN**：发过 1 次，最高 1 分（[讨论](https://news.ycombinator.com/item?id=50655803)）
- **topics**：`accessibility-testing` `ai-agents` `ai-testing` `android` `android-emulator` `claude` `claude-code` `e2e-testing` `exploratory-testing` `expo` `flutter` `github-actions` `ios` `ios-simulator` `llm` `mobile-testing` `qa` `react-native` `test-automation` `ui-testing`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) · 🟢 窗口内 · 90.2 分

> Non-invasive MCP accelerator plugin for Google Antigravity (CLI/Desktop/IDE): cuts LLM turns (-34%), token quota (-31%), and upload traffic (-40%) without affecting native UI or diffs.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2096 | +1839 | +257 | 117 | 27 | TypeScript | MIT | 11-19（9 天前） | 今天 |

- **近 14 天每天新增**：`···▁▁▃▂▆▄█▄▄▅·` 0 0 0 5 34 166 52 372 195 503 250 220 299 0
- **势头**：比前 7 天快 7.2 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `ai-coding` `antigravity` `antigravity-cli` `antigravity-ide` `antigravity-plugins` `coding-agent` `context-optimization` `developer-productivity` `developer-tools` `gemini` `google-antigravity` `latency-optimization` `mcp` `mcp-plugin` `mcp-server` `model-context-protocol` `performance` `plugin` `token-optimization`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [qianyiai/KuroCat](https://github.com/qianyiai/KuroCat) · 🟢 窗口内 · 90 分

> KuroCat — Free open-source 3D/2D desktop typing cat & AI companion (Bongo Cat alternative · MCP · Win/Mac/Linux/Android) 开源3D桌面打字小黑猫

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1819 | +1801 | +18 | 258 | 75 | TypeScript | MIT | 11-21（6 天前） | 今天 |

- **近 14 天每天新增**：`······▁▄▅▇▇█▅·` 0 0 0 0 0 0 18 205 234 330 384 420 228 0
- **势头**：比前 7 天快 100.1 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`3d` `ai-companion` `android` `bongo-cat` `bongocat` `claude-code` `codex` `cross-platform` `desktop-pet` `keyboard-visualizer` `kurocat` `linux` `macos` `mcp` `obs-studio` `open-source` `rust` `tauri` `typing-cat` `windows`
- **主页**：<https://kurocat.org>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [Avaneesh-Inamdar/Stream-Tube-Desktop](https://github.com/Avaneesh-Inamdar/Stream-Tube-Desktop) · 🟢 窗口内 · 89.2 分

> Native YouTube client for Windows in Rust, with SponsorBlock, DeArrow and Return YouTube Dislike built in

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1691 | +1691 | +0 | 155 | 39 | Rust | MIT | 11-22（5 天前） | 今天 |

- **近 14 天每天新增**：`·······▂▄█▅▄▂·` 0 0 0 0 0 0 0 46 288 632 336 254 135 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`dearrow` `desktop-app` `gpui` `mpv` `rust` `sponsorblock` `windows` `youtube` `youtube-client`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [ZigZagBoi1/ScarlettPort](https://github.com/ZigZagBoi1/ScarlettPort) · 🟢 窗口内 · 86.8 分

> Native PC port layer for an Xbox Series X|S title: the game's x64 code runs on your CPU and its RDNA2 GPU code is recompiled for your graphics card. Bring your own files.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1388 | +1388 | +0 | 199 | 21 | Rust | — | 11-24（3 天前） | 今天 |

- **近 14 天每天新增**：`·········▄▂▆█·` 0 0 0 0 0 0 0 0 0 281 79 406 622 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`amd` `compatibility-layer` `d3d12` `directx12` `dxil` `game-port` `native-port` `nvidia` `pc-port` `rust` `shader-recompiler` `shader-translation` `victory` `windows` `xbox` `xbox-series-s` `xbox-series-x`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [xikhar/papercraft](https://github.com/xikhar/papercraft) · 🟢 窗口内 · 81.9 分

> Agent skill to build games, interactive scenes, web pages and animations in a handcrafted pop-up papercraft style

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1031 | +919 | +112 | 109 | 2 | JavaScript | MIT | 11-21（7 天前） | 今天 |

- **近 14 天每天新增**：`·····▂▄▆█▅▄▅▆·` 0 0 0 0 0 28 84 172 221 137 93 123 173 0
- **势头**：比前 7 天快 8.2 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [erkamyaman/safe-anything](https://github.com/erkamyaman/safe-anything) · 🟢 窗口内 · 80.8 分

> Find the holes before someone else does. A fast, 100% Rust vulnerability scanner: XSS, SQL injection, leaked secrets, dependency CVEs and AI agent setups.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 840 | +840 | +0 | 96 | 16 | Rust | MIT | 11-22（5 天前） | 今天 |

- **近 14 天每天新增**：`·······▄█▃▃▂▂·` 0 0 0 0 0 0 0 165 370 114 89 63 39 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `claude-code` `claude-code-plugin` `cli` `codex` `cursor` `devsecops` `mcp` `osv` `owasp` `rust` `sast` `secret-scanning` `secrets` `security` `security-scanner` `sql-injection` `vulnerability` `vulnerability-scanner` `xss`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [Ahmet-Dedeler/awesome-gta6-reverse-engineering](https://github.com/Ahmet-Dedeler/awesome-gta6-reverse-engineering) · 🟢 窗口内 · 80.6 分

> Curated list of open-source GTA VI (GTA 6) reverse engineering tools, RAGE 9 / RPF9 archive explorers, TTPF texture & ADAT/AWC audio decoders, format docs, and Xbox Series / PS5 translation layers.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 850 | +826 | +24 | 53 | 1 | HTML | — | 11-21（6 天前） | 今天 |

- **近 14 天每天新增**：`······▁▅█▃▂▂▂·` 0 0 0 0 0 0 24 221 365 83 53 53 51 0
- **势头**：比前 7 天快 34.4 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`awesome` `awesome-list` `game-preservation` `grand-theft-auto-vi` `gta-6` `gta-vi` `gta6` `gtavi` `modding` `rage9` `rdna2` `recompilation` `reverse-engineering` `rpf9` `rust` `scarlett` `ttpf` `xbox-series`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 9. [chanke17/KuroCat](https://github.com/chanke17/KuroCat) · 🟢 窗口内 · 79.9 分

> KuroCat — Free open-source native desktop cat pet & OBS overlay (Bongo Cat alternative, Swift/C++, 802 KB)｜开源免费原生桌面萌猫（全平台 macOS·Win·Linux·UOS / 2.5D转头捕猎 / 数位板 / OBS透明绿幕 / 在线皮肤工坊 / 零按键上传）

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 780 | +780 | +0 | 86 | 22 | C++ | MIT | 11-23（5 天前） | 今天 |

- **近 14 天每天新增**：`·······▆█▇▇▅▃·` 0 0 0 0 0 0 0 115 178 159 158 108 62 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`bongo-cat` `bongo-cat-alternative` `cpp` `desktop-companion` `desktop-pet` `drawing-tablet` `kurocat` `linux` `macos` `mcp` `mcp-server` `native-app` `obs` `obs-overlay` `open-source` `streamer-tools` `swift` `uos` `vtuber` `windows`
- **主页**：<https://kurocat.cc/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 10. [danielwh2/sprite-stacking](https://github.com/danielwh2/sprite-stacking) · 🟢 窗口内 · 78.7 分

> Agent skill: turn four pixel art views into fake-3D sprites you can spin. Works with Claude Code, Codex, Cursor, OpenCode, Gemini CLI, Pi.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1106 | +706 | +400 | 89 | 1 | HTML | MIT | 11-20（7 天前） | 3 天前 |

- **近 14 天每天新增**：`·····██▆▇▅▅▄▃·` 0 0 0 0 0 199 201 138 166 129 129 89 55 0
- **势头**：比前 7 天快 1.8 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `claude-code` `codex` `cursor` `fake-3d` `gamedev` `pixel-art` `sprite-stacking` `voxel`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [nexu-io/opengame](https://github.com/nexu-io/opengame) — 一天进了一半以上的 star，但 HN 上没火过
- [zortos293/XSEmu](https://github.com/zortos293/XSEmu) — 一天进了一半以上的 star，但 HN 上没火过
- [ProjectLeonidaL/leonida](https://github.com/ProjectLeonidaL/leonida) — 一天进了一半以上的 star，但 HN 上没火过
- [stellarr-studio/kelvaroq](https://github.com/stellarr-studio/kelvaroq) — 一天进了一半以上的 star，但 HN 上没火过
- [Indigo-0167/universal-game-mod-manager](https://github.com/Indigo-0167/universal-game-mod-manager) — 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1%

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 363 | 121 | [Show HN: bouncemarket – a live prediction market game for a bouncing ball](https://bouncemarket.minhanhday.com/) | [HN](https://news.ycombinator.com/item?id=50667726) |
| 362 | 90 | [Show HN: I built a game where you are an LLM's subagent](https://github.com/gulivan/worker755) | [HN](https://news.ycombinator.com/item?id=50599762) |
| 356 | 80 | [Show HN: Old Nvidia and ATI tech demos, running again in the browser](https://gpu-demo-gallery.pages.dev/) | [HN](https://news.ycombinator.com/item?id=50638503) |
| 305 | 108 | [Show HN: I wrote an entire Vim manual over 4 years](http://themouseless.dev/vim/) | [HN](https://news.ycombinator.com/item?id=50655868) |
| 245 | 55 | [Show HN: Fuck_data_brokers.py](https://github.com/gary23w/f-ck_data_brokers) | [HN](https://news.ycombinator.com/item?id=50658191) |
| 182 | 138 | [Show HN: Zero C# – C# without a runtime or GC](https://onurgumus.github.io/zero-csharp/index.html) | [HN](https://news.ycombinator.com/item?id=50590279) |
| 153 | 34 | [Show HN: Three Linux VMs in a browser tab, each running a different browser](https://michidk.github.io/sidebyside/) | [HN](https://news.ycombinator.com/item?id=50656036) |
| 148 | 30 | [Show HN: Synth Patch Hero](https://swarkentin.github.io/synth-patch-hero/) | [HN](https://news.ycombinator.com/item?id=50623232) |
| 136 | 13 | [Show HN: An agent skill that optimizes code with falsifiable hypotheses](https://chszlab.github.io/AgenticAlgorithmEngineering/) | [HN](https://news.ycombinator.com/item?id=50611593) |
| 126 | 37 | [Show HN: DragDropMath – Learn math by feel](https://dragdropmath.com/) | [HN](https://news.ycombinator.com/item?id=50669673) |
| 124 | 69 | [Show HN: Olumino, a Markdown notes and spaced repetition app](https://olumino.app) | [HN](https://news.ycombinator.com/item?id=50651099) |
| 110 | 21 | [Show HN: Mason – A lightweight Postgres read-replica, built on columnar storage](https://masondata.ai/) | [HN](https://news.ycombinator.com/item?id=50630294) |
| 89 | 60 | [Show HN: The Riemann Proof Handbook](https://github.com/tamnd/riemann-handbook) | [HN](https://news.ycombinator.com/item?id=50596664) |
| 84 | 69 | [Show HN: Analysis of Hacker News predictions since 2008](https://hnpredictions.com/) | [HN](https://news.ycombinator.com/item?id=50633531) |
| 77 | 27 | [Show HN: I restored Palm's last device, and brought its OS to other platforms](https://www.webosarchive.org/pivot/2026/11/27/the-story-so-far/) | [HN](https://news.ycombinator.com/item?id=50667452) |
| 62 | 16 | [Show HN: SimDrop – Running iOS simulators in the macOS Finder sidebar](https://github.com/rxliuli/sim-drop) | [HN](https://news.ycombinator.com/item?id=50657070) |
| 58 | 8 | [Show HN: Turned a $5 AliExpress clock into a desk Clawd pet(+usage)](https://github.com/click6067-ship-it/token-tv) | [HN](https://news.ycombinator.com/item?id=50642300) |
| 56 | 26 | [Show HN: Rchive – Every drive I've owned since the 90s, searchable in one window](https://www.rchive.computer/) | [HN](https://news.ycombinator.com/item?id=50624684) |
| 52 | 40 | [Show HN: I made a PS1 style racing game](https://outpostracer.com) | [HN](https://news.ycombinator.com/item?id=50589184) |
| 52 | 22 | [Show HN: Type-C – variants, options, generics and pattern matching for C](https://github.com/stass/type-c) | [HN](https://news.ycombinator.com/item?id=50602561) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 20 | [PaperOrchestra: A Multi-Agent Framework for Automated AI Research Paper Writing](https://huggingface.co/papers/2604.05018) | PaperOrchestra is a multi-agent framework that converts unstructured research materials into complete LaTeX manuscripts with literature synt… | [google-research/paper-orchestra](https://github.com/google-research/paper-orchestra) 6621★ |
| 112 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 32894★ |
| 73 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 25463★ |
| 105 | [OS-Omni: Benchmarking Generalist Computer-Using Agents on Long-Horizon Workflows Across Platforms](https://huggingface.co/papers/2611.34232) | A live cross-platform benchmark evaluates computer-using agents on long-horizon workflows across Windows, Ubuntu, macOS, iOS, Android, and W… | 💡 [OS-Copilot/OS-Omni](https://github.com/OS-Copilot/OS-Omni) 106★ |
| 170 | [InCoder-32B: Code Foundation Model for Industrial Scenarios](https://huggingface.co/papers/2603.16790) | InCoder-32B is a 32-billion-parameter code model trained on industrial datasets with extended context length and execution verification to i… | 💡 [CSJianYang/Industrial-Coder](https://github.com/CSJianYang/Industrial-Coder) 822★ |
| 168 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 123937★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 41 | [Depth Pro 2: Sharp and Temporally Consistent Metric Monocular Depth](https://huggingface.co/papers/2611.26603) | A single scalable network estimates dense metric depth for images and video at native resolution, jointly improving metric accuracy, boundar… | 💡 [apple-aiml-research/ml-depth-pro-2](https://github.com/apple-aiml-research/ml-depth-pro-2) 796★ |
| 170 | [Gamer: A Generalist Vision-Language-Action Foundation Model for Long-Horizon Real-Time Game Agent](https://huggingface.co/papers/2611.18397) | Gamer is a generalist agent framework that integrates perception, memory, and multi-step reasoning, trained through continued pre-training,… | [RainBowLuoCS/Gamer](https://github.com/RainBowLuoCS/Gamer) 1620★ |
| 87 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 94473★ |
| 158 | [ARIS: Autonomous Research via Adversarial Multi-Agent Collaboration](https://huggingface.co/papers/2605.03042) | ARIS is an open-source research harness that uses cross-model adversarial collaboration to ensure reliable long-term research outcomes throu… | [wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) 20007★ |
| 28 | [PaddleOCR-VL-1.6: Expanding the Frontier of Document Parsing with Under-Optimized Region Refinement…](https://huggingface.co/papers/2606.03264) | PaddleOCR-VL-1.6 enhances document parsing performance through targeted data optimization and progressive post-training techniques, achievin… | [PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) 93400★ |
| 38 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 36827★ |
| 72 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 36828★ |
| 21 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 8167★ |
| 24 | [Instruction-Following Evaluation for Large Language Models](https://huggingface.co/papers/2311.07911) | Instruction-Following Eval (IFEval) provides a standardized benchmark for evaluating Large Language Models' ability to follow natural langua… | [google-research/google-research](https://github.com/google-research/google-research) 39567★ |
| 184 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 84437★ |
| 178 | [SmolDocling: An ultra-compact vision-language model for end-to-end multi-modal document conversion](https://huggingface.co/papers/2503.11576) | SmolDocling is a compact vision-language model that performs end-to-end document conversion with robust performance across various document… | [docling-project/docling](https://github.com/docling-project/docling) 71151★ |
| 75 | [Mixture-of-Loops Transformer](https://huggingface.co/papers/2611.34923) | A Mixture-of-Loops Transformer reuses key-value memory across loops and depths, and its U-shaped variant improves pretraining efficiency and… | 💡 [hustvl/MoLT](https://github.com/hustvl/MoLT) 97★ |
| 107 | [Embo-Harness: Towards Understanding Frontier-Model-as-Policy Harness](https://huggingface.co/papers/2611.31201) | A systematic framework shows that frontier multimodal models can serve as robot policies when harnessed with interfaces favoring native visu… | 💡 [DravenALG/Embo-Harness](https://github.com/DravenALG/Embo-Harness) 75★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 41 | [te pk minimax h3](https://huggingface.co/Alissonerdx/TE-PK-Minimax-H3) | — | 83 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 44 | 18 | [Hard Drive pricing has gotten bad](https://blog.ktz.me/black-friday-hard-drive-prices-are-messed-up/) | `hardware` | [讨论](https://lobste.rs/s/96gu7o/hard_drive_pricing_has_gotten_bad) |
| 38 | 10 | [Objections to .php application being published on ICANN site](https://pub.roddie.digital/3n3aavxi6hc2g) | `web` | [讨论](https://lobste.rs/s/d0phlt/objections_php_application_being) |
| 48 | 8 | [Tiny Hat: a new Linux distro dedicated to retro gamedev](https://roboticoverlords.org/tinyhat) | `games` `linux` `retrocomputing` | [讨论](https://lobste.rs/s/mbm7xw/tiny_hat_new_linux_distro_dedicated_retro) |
| 46 | 0 | [The State of Allocators in 2026 - Finally Stabilised](https://cetra3.github.io/blog/state-of-allocators-2026-finally-stabilised/) | `rust` | [讨论](https://lobste.rs/s/u746hs/state_allocators_2026_finally) |
| 21 | 8 | [Why optimistic updates are corrosive](https://datastar-instant-intent.ndyg.cross.stream/corrosive/) | `web` | [讨论](https://lobste.rs/s/amjski/why_optimistic_updates_are_corrosive) |
| 18 | 4 | [Build your own Paint](https://www.buildyourownpaint.com/en) | `rust` | [讨论](https://lobste.rs/s/c2zrmq/build_your_own_paint) |
| 16 | 36 | [What are you doing this weekend?](https://lobste.rs/s/locqp9) | `ask` `programming` | [讨论](https://lobste.rs/s/locqp9/what_are_you_doing_this_weekend) |
| 15 | 4 | [Pop!_OS 26.04 LTS Has Landed](https://system76.com/blog/post/pop_os-26-04-lts-has-landed) | `linux` `release` | [讨论](https://lobste.rs/s/hizg2w/pop_os_26_04_lts_has_landed) |
| 86 | 45 | [Taking Email Back](http://www.linux-magazine.com/Online/Features/Taking-Email-Back) | `email` | [讨论](https://lobste.rs/s/afxeri/taking_email_back) |
| 9 | 1 | [x86 is an octal machine](https://gist.github.com/seanjensengrey/f971c20d05d4d0efc0781f2f3c0353da) | `compsci` `retrocomputing` | [讨论](https://lobste.rs/s/kikmfz/x86_is_octal_machine) |
| 2 | 3 | [FastLanes: Next-gen File Format](https://research.vu.nl/files/447013431/afroozehphdthesis%20-%2069280d90f0bfd.pdf) | `pdf` `performance` | [讨论](https://lobste.rs/s/ulfg29/fastlanes_next_gen_file_format) |
| 7 | 2 | [Exception Best Practices](https://www.well-typed.com/blog/2026/11/exception-best-practices/) | `haskell` | [讨论](https://lobste.rs/s/tgihkm/exception_best_practices) |
| 9 | 10 | [Pimalaya goes stable](https://blog.pimalaya.org/pimalaya-goes-stable/) | `email` `release` `rust` | [讨论](https://lobste.rs/s/kaj037/pimalaya_goes_stable) |
| 8 | 6 | [Curb impacts of AI on programming to maintain EU sovereignty](https://www.draketo.de/software/curb-ai-impact) | `ai` | [讨论](https://lobste.rs/s/lmxpfo/curb_impacts_ai_on_programming_maintain) |
| 14 | 12 | [AI made self-hosting fun again](https://janlukas.blog/posts/ai-self-hosting) | `devops` | [讨论](https://lobste.rs/s/xsjwvi/ai_made_self_hosting_fun_again) |
| 3 | 0 | [Proof automation in a language](https://www.imperialviolet.org/2026/11/15/proofauto2.html) | `formalmethods` `plt` | [讨论](https://lobste.rs/s/ohmjfv/proof_automation_language) |
| 25 | 26 | [The need for a formally verifiable mainstream programming language](https://blainehansen.me/post/mainstream-verifiable-language/) | `ai` `building-ai-tooling` `formalmethods` `plt` | [讨论](https://lobste.rs/s/byfdgn/need_for_formally_verifiable_mainstream) |
| 46 | 13 | [Company Culture = Slack Emoji ÷ sqrt(Headcount)](https://lia.mg/posts/measuring-company-culture-with-slack-emoji/) | `culture` `satire` | [讨论](https://lobste.rs/s/fin7at/company_culture_slack_emoji_sqrt) |
| 1 | 0 | [A Best-in-Class iOS App: The Book Series](https://www.bestinclassiosapp.com/) | `book` `ios` `pdf` | [讨论](https://lobste.rs/s/wkljma/best_class_ios_app_book_series) |
| 62 | 4 | [Garage v2.6.0 released with web admin, v1.x EoL & other news](https://garagehq.deuxfleurs.fr/blog/2026-11-webadmin-release/) | `distributed` `release` `web` | [讨论](https://lobste.rs/s/2gfpu3/garage_v2_6_0_released_with_web_admin_v1_x) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 124 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 82 | 59 | 71% | — |
| 🔴 先核对 | 45 | 27 | 60% | 0 天 |
| 🟡 在降温 | 6 | 0 | 0% | — |
| 🔵 已被发现 | 5 | 3 | 60% | — |
| 💤 不活跃 | 1 | 0 | 0% | — |
| 🟢 窗口内 | 26 | 12 | 46% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [deepseek-ai/chat-demo](https://github.com/deepseek-ai/chat-demo) | 2026-11-14 | 🚀 爆发 | 1095 | 5529 | 2 | ✅ 起来了 |
| [libracoder/kiri](https://github.com/libracoder/kiri) | 2026-11-14 | 🚀 爆发 | 2398 | 14080 | 0 | ✅ 起来了 |
| [shinyobjectz/raea](https://github.com/shinyobjectz/raea) | 2026-11-14 | 🟢 窗口内 | 2389 | 5385 | 1 | ✅ 起来了 |

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
