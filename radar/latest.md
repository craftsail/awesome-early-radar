# early-radar 选题雷达 · 2026-11-27

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 105 个，细查前 20 个 · 比上次 = 和 2026-11-26 那次比 · 生成于 2026-11-27 07:53 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 5 个 · Show HN ✅ 17 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 5 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 14 个 · 🟡 在降温 1 个 · 🔵 已被发现 0 个 · 💤 不活跃 0 个 · 🔴 先核对 5 个
- **今天新出现 5 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [Marvisak/VIctory](https://github.com/Marvisak/VIctory) 平均每天 +3952，见 [爆发](#爆发)
- **复盘**：🚀 爆发 57/80 · 🔴 先核对 27/45 · 🟡 在降温 0/6 · 🔵 已被发现 3/5 · 💤 不活跃 0/1 · 🟢 窗口内 11/25（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) — 20 AI testers on 20 different phones, in parallel, on GitHub…（近 7 天 +2496，比前 7 天快 50.9 倍，在加速）
  - [qianyiai/KuroCat](https://github.com/qianyiai/KuroCat) — KuroCat — Free open-source 3D/2D desktop typing cat & AI cod…（近 7 天 +1589，刚发布一周内）
  - [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) — Non-invasive MCP accelerator plugin for Google Antigravity (…（近 7 天 +1592，比前 7 天快 7.7 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 28 个（star 合计 32505），代表：[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill)、[DIYgod/pinky](https://github.com/DIYgod/pinky)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：5 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: I built a game where you are an LLM's subagent](https://github.com/gulivan/worker755) — 362 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [Marvisak/VIctory](https://github.com/Marvisak/VIctory) | 13521 | 3952 | +717 | 3.4 | [1](https://news.ycombinator.com/item?id=50622253) | victory · marvisak victory · marvis victory | An attempt at running GTA VI on PC |
| [Belobug/VIctory-Belobug-AMD](https://github.com/Belobug/VIctory-Belobug-AMD) | 3548 | 1843 | +1856 | 1.9 | — | victory belobug amd · belobug victory belobug amd |  |
| [4lwayz/portwatch-vi](https://github.com/4lwayz/portwatch-vi) | 6100 | 1138 | +1525 | 5.4 | — | portwatch vi · 4lwayz portwatch vi | Does GTA VI run on PC yet? A live tracker of community recom… |
| [avatarmanz/VIctory-7900XTX](https://github.com/avatarmanz/VIctory-7900XTX) | 1881 | 1344 | +616 | 1.4 | — | victory 7900xtx · avatarmanz victory 7900xtx | Goal: an Xbox Series title (your own dump) on PC as the Seri… |
| [xcl-dev/xcl](https://github.com/xcl-dev/xcl) | 8645 | 1331 | +255 | 6.5 | [49](https://news.ycombinator.com/item?id=44859763) | xcl · xcl-dev xcl · xcl xcl | Xbox Series compatibility layer for Windows - runs console g… |
| [fxceless/victory-fork](https://github.com/fxceless/victory-fork) | 3302 | 1281 | +143 | 2.6 | — | victory fork · fxceless victory fork · hyphen victory fork | Work-in-progress fork of VIctory: getting an Xbox Series tit… |
| [RMvdesi/obsidian-prism](https://github.com/RMvdesi/obsidian-prism) | 2520 | 247 | +1079 | 10.2 | — | obsidian prism · rmvdesi obsidian prism | Optical UI, damped-spring choreography, 512K shallow-water v… |
| [alesha-pro/llm.asm](https://github.com/alesha-pro/llm.asm) | 1738 | 862 | +1047 | 2 | [230](https://news.ycombinator.com/item?id=50648365) | llm asm · alesha-pro llm asm · alexey llm asm | Qwen3-0.6B inference (12 KB), bare-metal bootable OS (22 KB)… |
| [erkamyaman/rust-anything](https://github.com/erkamyaman/rust-anything) | 10424 | 963 | +674 | 10.8 | [1](https://news.ycombinator.com/item?id=50558549) | rust anything · erkamyaman rust anything · erkam rust anything | Rewrite your app in Rust, piece by piece, checked against th… |
| 🆕 [nexu-io/opengame](https://github.com/nexu-io/opengame) | 1506 | 798 | — | 1.9 | — | opengame · nexu-io opengame · opendesign opengame | The Super Game Agent — the Unity & Unreal for AI agents, wit… |
| [ubiquitarianism/leonida](https://github.com/ubiquitarianism/leonida) | 2559 | 768 | +169 | 3.3 | — | leonida · ubiquitarianism leonida | A continuation of Leonida, the Xbox > PC port interface for… |
| [EL4CTEO/fast-anything](https://github.com/EL4CTEO/fast-anything) | 4326 | 757 | +266 | 5.7 | [215](https://news.ycombinator.com/item?id=50596155) | fast anything · el4cteo fast anything | Don't rewrite it in Rust. Rewrite the 5% that's slow: profil… |
| 🆕 [DoubleGhosty/cool_fox](https://github.com/DoubleGhosty/cool_fox) | 752 | 752 | — | 1 | — | cool fox · doubleghosty cool fox · ghosty cool fox | cool_fox: Leading CGBJ runtime continuation for GTA VI PC -… |
| 🆕 [opensetlabs/openset-llm](https://github.com/opensetlabs/openset-llm) | 1887 | 137 | +724 | 13.8 | — | openset llm · opensetlabs openset llm · open openset llm | Fast local LLM inference on plain CPUs. No GPU, 8 GB of RAM.… |
| 🆕 [Pixel679-cmyk/windows-titlebar-blur-customizer](https://github.com/Pixel679-cmyk/windows-titlebar-blur-customizer) | 683 | 683 | — | 1 | — | windows titlebar blur customizer · pixel679-cmyk windows titlebar blur customizer | Customize Windows 10 and 11 title bar effects with Aero, Acr… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 93.9 | 🟢 窗口内 | [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) | Python | 2545 | +155 | +2496 | +49 | `··▁▁▁▁▁▁█▆▄▄▂·` | 10 | [1](https://news.ycombinator.com/item?id=50655803) | — |
| 2 | 88.5 | 🆕 🟢 窗口内 | [qianyiai/KuroCat](https://github.com/qianyiai/KuroCat) | TypeScript | 1589 | — | +1589 | +0 | `·······▁▄▅▇▇█·` | 5 | — | — |
| 3 | 88.5 | 🟢 窗口内 | [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) | TypeScript | 1799 | +214 | +1592 | +207 | `····▁▁▃▂▆▄█▅▄·` | 8 | — | — |
| 4 | 88.3 | 🟢 窗口内 | [Avaneesh-Inamdar/Stream-Tube-Desktop](https://github.com/Avaneesh-Inamdar/Stream-Tube-Desktop) | Rust | 1562 | +253 | +1562 | +0 | `········▂▄█▅▄·` | 4 | — | — |
| 5 | 87.5 | 🟢 窗口内 | [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) | Python | 2840 | +109 | +1464 | +1376 | `··▆█▃▂▂▆▄▅▄▂▂·` | 10 | — | — |
| 6 | 87.1 | 🟢 窗口内 | [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) | Python | 2797 | +152 | +1414 | +1383 | `·····▇█▅▄▃▃▂▂·` | 7 | — | — |
| 7 | 81.1 | 🟢 窗口内 | [Lemxy/WinRust](https://github.com/Lemxy/WinRust) | Rust | 1658 | +76 | +863 | +795 | `···▃▂█▇▅▇▄▃▃▃·` | 9 | — | — |
| 8 | 81 | 🟢 窗口内 | [danielwh2/sprite-stacking](https://github.com/danielwh2/sprite-stacking) | HTML | 1051 | +88 | +852 | +199 | `······██▆▇▅▅▄·` | 6 | — | — |
| 9 | 80.7 | 🟢 窗口内 | [xikhar/papercraft](https://github.com/xikhar/papercraft) | JavaScript | 860 | +122 | +832 | +28 | `······▂▄▆█▅▄▅·` | 6 | — | — |
| 10 | 80.3 | 🟢 窗口内 | [Ahmet-Dedeler/awesome-gta6-reverse-engineering](https://github.com/Ahmet-Dedeler/awesome-gta6-reverse-engineering) | HTML | 805 | +50 | +805 | +0 | `·······▁▅█▃▂▂·` | 5 | — | — |
| 11 | 80.2 | 🟢 窗口内 | [erkamyaman/safe-anything](https://github.com/erkamyaman/safe-anything) | Rust | 801 | +63 | +801 | +0 | `········▄█▃▃▂·` | 4 | — | — |
| 12 | 79 | 🟢 窗口内 | [chanke17/KuroCat](https://github.com/chanke17/KuroCat) | C++ | 719 | +107 | +719 | +0 | `········▆█▇▇▅·` | 4 | — | — |
| 13 | 77.1 | 🟢 窗口内 | [Developing-Gamer/agent-sim](https://github.com/Developing-Gamer/agent-sim) | Rust | 617 | +12 | +617 | +0 | `·········▇█▂▁·` | 5 | — | — |
| 14 | 73.8 | 🟢 窗口内 | [SulphurS16/Regaliant](https://github.com/SulphurS16/Regaliant) | Rust | 468 | +35 | +468 | +0 | `·········█▇▄▂·` | 3 | — | — |
| 15 | 54.1 | 🟡 在降温 | [DIYgod/pinky](https://github.com/DIYgod/pinky) | Go | 2826 | +36 | +223 | +514 | `▆▇▆█▇▆▅▄▄▄▄▂▄·` | 20 | — | — |
| 16 | 43.9 | 🆕 🔴 先核对 | [nexu-io/opengame](https://github.com/nexu-io/opengame) | TypeScript | 1506 | — | +1506 | +0 | `···········▁█·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 39.9 | 🆕 🔴 先核对 | [ZigZagBoi1/ScarlettPort](https://github.com/ZigZagBoi1/ScarlettPort) | Rust | 771 | +406 | +771 | +0 | `··········▆▂█·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 39.8 | 🆕 🔴 先核对 | [zortos293/XSEmu](https://github.com/zortos293/XSEmu) | Rust | 760 | — | +760 | +0 | `············█·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 37.5 | 🆕 🔴 先核对 | [ProjectLeonidaL/leonida](https://github.com/ProjectLeonidaL/leonida) | Rust | 521 | +56 | +521 | +0 | `·········▃█▂▂·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 21.5 | 🔴 先核对 | [Indigo-0167/universal-game-mod-manager](https://github.com/Indigo-0167/universal-game-mod-manager) | Rust | 1301 | +2 | +1301 | +0 | `··········█▂▁·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1% |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 1037 | 30 | 40164 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill)、[DIYgod/pinky](https://github.com/DIYgod/pinky) |
| `rust` | 221 | 30 | 28839 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[Renly1994/xiaotang-daozai](https://github.com/Renly1994/xiaotang-daozai)、[voyager-so/vork](https://github.com/voyager-so/vork) |
| `mcp` | 201 | 30 | 28453 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[lexifina/global-law](https://github.com/lexifina/global-law)、[JosssphZhou/poki](https://github.com/JosssphZhou/poki) |
| `local-first` | 66 | 30 | 14910 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping)、[nexu-io/opengame](https://github.com/nexu-io/opengame) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 28 | 32505 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill)、[DIYgod/pinky](https://github.com/DIYgod/pinky) |
| `windows` | 24 | 18446 | [Renly1994/xiaotang-daozai](https://github.com/Renly1994/xiaotang-daozai)、[qianyiai/KuroCat](https://github.com/qianyiai/KuroCat)、[Avaneesh-Inamdar/Stream-Tube-Desktop](https://github.com/Avaneesh-Inamdar/Stream-Tube-Desktop) |
| `codex` | 21 | 20495 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat)、[qianyiai/KuroCat](https://github.com/qianyiai/KuroCat) |
| `ai-agents` | 20 | 20119 | [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers)、[JosssphZhou/poki](https://github.com/JosssphZhou/poki)、[agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) |
| `mcp-server` | 16 | 11966 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[INK-Q/agy-fast](https://github.com/INK-Q/agy-fast)、[21stware/bowel](https://github.com/21stware/bowel) |
| `model-context-protocol` | 13 | 10253 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki)、[INK-Q/agy-fast](https://github.com/INK-Q/agy-fast)、[simpsoka/zigzag](https://github.com/simpsoka/zigzag) |
| `macos` | 13 | 8201 | [qianyiai/KuroCat](https://github.com/qianyiai/KuroCat)、[simpsoka/zigzag](https://github.com/simpsoka/zigzag)、[21stware/bowel](https://github.com/21stware/bowel) |
| `llm` | 12 | 14982 | [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill)、[pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers)、[JosssphZhou/poki](https://github.com/JosssphZhou/poki) |
| `agent-skills` | 12 | 13422 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[nexu-io/opengame](https://github.com/nexu-io/opengame)、[kubai087/kubai-icons](https://github.com/kubai087/kubai-icons) |
| `desktop-app` | 10 | 6840 | [Avaneesh-Inamdar/Stream-Tube-Desktop](https://github.com/Avaneesh-Inamdar/Stream-Tube-Desktop)、[harshsinghsv/swiftdl](https://github.com/harshsinghsv/swiftdl)、[Ciao1019/ArcMD](https://github.com/Ciao1019/ArcMD) |
| `3d-modeling` | 10 | 4718 | [credoksopho1984/blender-ai-copilot-studio](https://github.com/credoksopho1984/blender-ai-copilot-studio)、[tiobeharxi1987/blender-ai-copilot-flow](https://github.com/tiobeharxi1987/blender-ai-copilot-flow)、[Doug-218/blender-ai-copilot-forge](https://github.com/Doug-218/blender-ai-copilot-forge) |
| `developer-tools` | 9 | 5110 | [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast)、[alexeyw/lot-map](https://github.com/alexeyw/lot-map)、[devvmhq/devvm](https://github.com/devvmhq/devvm) |

**语言分布**：Rust 28 · TypeScript 25 · Python 18 · JavaScript 8 · Go 5 · HTML 4 · C++ 2 · C# 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) · 🟢 窗口内 · 93.9 分

> 20 AI testers on 20 different phones, in parallel, on GitHub's free runners: Claude Code agents on iOS Simulators and Android emulators that find broken flows, translation, layout and accessibility bugs

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2545 | +2496 | +49 | 259 | 7 | Python | MIT | 11-16（10 天前） | 今天 |

- **近 14 天每天新增**：`··▁▁▁▁▁▁█▆▄▄▂·` 0 0 17 14 11 4 3 8 865 658 391 419 155 0
- **势头**：比前 7 天快 50.9 倍，在加速
- **HN**：发过 1 次，最高 1 分（[讨论](https://news.ycombinator.com/item?id=50655803)）
- **topics**：`accessibility-testing` `ai-agents` `ai-testing` `android` `android-emulator` `claude` `claude-code` `e2e-testing` `exploratory-testing` `expo` `flutter` `github-actions` `ios` `ios-simulator` `llm` `mobile-testing` `qa` `react-native` `test-automation` `ui-testing`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. 🆕 [qianyiai/KuroCat](https://github.com/qianyiai/KuroCat) · 🟢 窗口内 · 88.5 分

> KuroCat — Free open-source 3D/2D desktop typing cat & AI coding companion (Bongo Cat alternative · Tauri v2 + Rust + MCP · Claude/Codex/DeepSeek/OBS · Win/Mac/Linux/Android)｜开源3D桌面打字小黑猫与AI伴侣

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1589 | +1589 | +0 | 222 | 58 | TypeScript | MIT | 11-21（5 天前） | 今天 |

- **近 14 天每天新增**：`·······▁▄▅▇▇█·` 0 0 0 0 0 0 0 18 205 234 330 384 418 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`3d` `ai-companion` `android` `bongo-cat` `bongocat` `claude-code` `codex` `cross-platform` `desktop-pet` `keyboard-visualizer` `kurocat` `linux` `macos` `mcp` `obs-studio` `open-source` `rust` `tauri` `typing-cat` `windows`
- **主页**：<https://kurocat.org>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) · 🟢 窗口内 · 88.5 分

> Non-invasive MCP accelerator plugin for Google Antigravity (CLI/Desktop/IDE): cuts LLM turns (-34%), token quota (-31%), and upload traffic (-40%) without affecting native UI or diffs.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1799 | +1592 | +207 | 102 | 23 | TypeScript | MIT | 11-19（8 天前） | 今天 |

- **近 14 天每天新增**：`····▁▁▃▂▆▄█▅▄·` 0 0 0 0 5 34 168 52 372 195 504 252 217 0
- **势头**：比前 7 天快 7.7 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `ai-coding` `antigravity` `antigravity-cli` `antigravity-ide` `antigravity-plugins` `coding-agent` `context-optimization` `developer-productivity` `developer-tools` `gemini` `google-antigravity` `latency-optimization` `mcp` `mcp-plugin` `mcp-server` `model-context-protocol` `performance` `plugin` `token-optimization`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [Avaneesh-Inamdar/Stream-Tube-Desktop](https://github.com/Avaneesh-Inamdar/Stream-Tube-Desktop) · 🟢 窗口内 · 88.3 分

> Native YouTube client for Windows in Rust, with SponsorBlock, DeArrow and Return YouTube Dislike built in

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1562 | +1562 | +0 | 135 | 35 | Rust | MIT | 11-22（4 天前） | 今天 |

- **近 14 天每天新增**：`········▂▄█▅▄·` 0 0 0 0 0 0 0 0 48 289 634 337 254 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`dearrow` `desktop-app` `gpui` `mpv` `rust` `sponsorblock` `windows` `youtube` `youtube-client`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) · 🟢 窗口内 · 87.5 分

> Agent skill for hill-climbing local LLM serving speed (decode, speculative decoding, prefill, KV, startup, TTFT) on any hardware and quantization

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2840 | +1464 | +1376 | 260 | 27 | Python | MIT | 11-16（10 天前） | 10 天前 |

- **近 14 天每天新增**：`··▆█▃▂▂▆▄▅▄▂▂·` 0 0 401 576 179 113 107 406 221 332 283 113 109 0
- **势头**：比前 7 天快 1.1 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `benchmarking` `claude-code` `inference` `llm` `speculative-decoding`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) · 🟢 窗口内 · 87.1 分

> Paste a link, get captioned 9:16 clips in ~2 min. Free, local, open-source clipping engine (audio-first, YouTube captions, local LLM).

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2797 | +1414 | +1383 | 176 | 52 | Python | AGPL-3.0 | 11-19（7 天前） | 2 天前 |

- **近 14 天每天新增**：`·····▇█▅▄▃▃▂▂·` 0 0 0 0 0 656 727 458 331 167 191 115 152 0
- **势头**：和前 7 天差不多
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-video-clipper` `clipping` `faster-whisper` `ffmpeg` `gameplay-clipper` `local-llm` `ollama` `open-source-video-editor` `opusclip-alternative` `shorts` `twitch-clips` `vertical-video` `video` `whisper` `youtube-shorts-generator` `yt-dlp`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [Lemxy/WinRust](https://github.com/Lemxy/WinRust) · 🟢 窗口内 · 81.1 分

> Windows shell replacement in Rust: taskbar, file manager, NTFS search, task manager, disk cleaner. One installer exe.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1658 | +863 | +795 | 114 | 66 | Rust | Apache-2.0 | 11-17（9 天前） | 1 天前 |

- **近 14 天每天新增**：`···▃▂█▇▅▇▄▃▃▃·` 0 0 0 80 72 347 296 181 300 126 94 83 79 0
- **势头**：比前 7 天快 1.1 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [danielwh2/sprite-stacking](https://github.com/danielwh2/sprite-stacking) · 🟢 窗口内 · 81 分

> Agent skill: turn four pixel art views into fake-3D sprites you can spin. Works with Claude Code, Codex, Cursor, OpenCode, Gemini CLI, Pi.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1051 | +852 | +199 | 87 | 1 | HTML | MIT | 11-20（6 天前） | 2 天前 |

- **近 14 天每天新增**：`······██▆▇▅▅▄·` 0 0 0 0 0 0 199 201 138 166 129 129 89 0
- **势头**：比前 7 天快 4.3 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `claude-code` `codex` `cursor` `fake-3d` `gamedev` `pixel-art` `sprite-stacking` `voxel`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 9. [xikhar/papercraft](https://github.com/xikhar/papercraft) · 🟢 窗口内 · 80.7 分

> Agent skill to build games, interactive scenes, web pages and animations in a handcrafted pop-up papercraft style

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 860 | +832 | +28 | 93 | 2 | JavaScript | MIT | 11-21（6 天前） | 5 天前 |

- **近 14 天每天新增**：`······▂▄▆█▅▄▅·` 0 0 0 0 0 0 28 84 172 223 137 94 122 0
- **势头**：比前 7 天快 29.7 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 10. [Ahmet-Dedeler/awesome-gta6-reverse-engineering](https://github.com/Ahmet-Dedeler/awesome-gta6-reverse-engineering) · 🟢 窗口内 · 80.3 分

> Curated list of open-source GTA VI (GTA 6) reverse engineering tools, RAGE 9 / RPF9 archive explorers, TTPF texture & ADAT/AWC audio decoders, format docs, and Xbox Series / PS5 translation layers.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 805 | +805 | +0 | 48 | 2 | HTML | — | 11-21（5 天前） | 今天 |

- **近 14 天每天新增**：`·······▁▅█▃▂▂·` 0 0 0 0 0 0 0 24 223 368 84 53 53 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`awesome` `awesome-list` `game-preservation` `grand-theft-auto-vi` `gta-6` `gta-vi` `gta6` `gtavi` `modding` `rage9` `rdna2` `recompilation` `reverse-engineering` `rpf9` `rust` `scarlett` `ttpf` `xbox-series`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [nexu-io/opengame](https://github.com/nexu-io/opengame) — 一天进了一半以上的 star，但 HN 上没火过
- [ZigZagBoi1/ScarlettPort](https://github.com/ZigZagBoi1/ScarlettPort) — 一天进了一半以上的 star，但 HN 上没火过
- [zortos293/XSEmu](https://github.com/zortos293/XSEmu) — 一天进了一半以上的 star，但 HN 上没火过
- [ProjectLeonidaL/leonida](https://github.com/ProjectLeonidaL/leonida) — 一天进了一半以上的 star，但 HN 上没火过
- [Indigo-0167/universal-game-mod-manager](https://github.com/Indigo-0167/universal-game-mod-manager) — 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1%

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 362 | 90 | [Show HN: I built a game where you are an LLM's subagent](https://github.com/gulivan/worker755) | [HN](https://news.ycombinator.com/item?id=50599762) |
| 355 | 80 | [Show HN: Old Nvidia and ATI tech demos, running again in the browser](https://gpu-demo-gallery.pages.dev/) | [HN](https://news.ycombinator.com/item?id=50638503) |
| 231 | 49 | [Show HN: Fuck_data_brokers.py](https://github.com/gary23w/f-ck_data_brokers) | [HN](https://news.ycombinator.com/item?id=50658191) |
| 181 | 137 | [Show HN: Zero C# – C# without a runtime or GC](https://onurgumus.github.io/zero-csharp/index.html) | [HN](https://news.ycombinator.com/item?id=50590279) |
| 139 | 44 | [Show HN: I wrote an entire Vim manual over 4 years](http://themouseless.dev/vim/) | [HN](https://news.ycombinator.com/item?id=50655868) |
| 137 | 28 | [Show HN: Synth Patch Hero](https://swarkentin.github.io/synth-patch-hero/) | [HN](https://news.ycombinator.com/item?id=50623232) |
| 136 | 30 | [Show HN: Three Linux VMs in a browser tab, each running a different browser](https://michidk.github.io/sidebyside/) | [HN](https://news.ycombinator.com/item?id=50656036) |
| 132 | 97 | [Show HN: Drive around my village in 3D](https://cherwellvalleymotorclub.app) | [HN](https://news.ycombinator.com/item?id=50574412) |
| 131 | 36 | [Show HN: OpenComputer – an open source alternative to Devin](https://github.com/diggerhq/opencomputer) | [HN](https://news.ycombinator.com/item?id=50581403) |
| 131 | 13 | [Show HN: An agent skill that optimizes code with falsifiable hypotheses](https://chszlab.github.io/AgenticAlgorithmEngineering/) | [HN](https://news.ycombinator.com/item?id=50611593) |
| 109 | 21 | [Show HN: Mason – A lightweight Postgres read-replica, built on columnar storage](https://masondata.ai/) | [HN](https://news.ycombinator.com/item?id=50630294) |
| 100 | 44 | [Show HN: Olumino, a Markdown notes and spaced repetition app](https://olumino.app) | [HN](https://news.ycombinator.com/item?id=50651099) |
| 89 | 60 | [Show HN: The Riemann Proof Handbook](https://github.com/tamnd/riemann-handbook) | [HN](https://news.ycombinator.com/item?id=50596664) |
| 57 | 7 | [Show HN: Turned a $5 AliExpress clock into a desk Clawd pet(+usage)](https://github.com/click6067-ship-it/token-tv) | [HN](https://news.ycombinator.com/item?id=50642300) |
| 53 | 26 | [Show HN: Rchive – Every drive I've owned since the 90s, searchable in one window](https://www.rchive.computer/) | [HN](https://news.ycombinator.com/item?id=50624684) |
| 52 | 38 | [Show HN: I made a PS1 style racing game](https://outpostracer.com) | [HN](https://news.ycombinator.com/item?id=50589184) |
| 52 | 22 | [Show HN: Type-C – variants, options, generics and pattern matching for C](https://github.com/stass/type-c) | [HN](https://news.ycombinator.com/item?id=50602561) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 19 | [PaperOrchestra: A Multi-Agent Framework for Automated AI Research Paper Writing](https://huggingface.co/papers/2604.05018) | PaperOrchestra is a multi-agent framework that converts unstructured research materials into complete LaTeX manuscripts with literature synt… | [google-research/paper-orchestra](https://github.com/google-research/paper-orchestra) 6502★ |
| 112 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 32845★ |
| 72 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 25320★ |
| 41 | [Depth Pro 2: Sharp and Temporally Consistent Metric Monocular Depth](https://huggingface.co/papers/2611.26603) | A single scalable network estimates dense metric depth for images and video at native resolution, jointly improving metric accuracy, boundar… | 💡 [apple-aiml-research/ml-depth-pro-2](https://github.com/apple-aiml-research/ml-depth-pro-2) 771★ |
| 168 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 123844★ |
| 169 | [InCoder-32B: Code Foundation Model for Industrial Scenarios](https://huggingface.co/papers/2603.16790) | InCoder-32B is a 32-billion-parameter code model trained on industrial datasets with extended context length and execution verification to i… | 💡 [CSJianYang/Industrial-Coder](https://github.com/CSJianYang/Industrial-Coder) 721★ |
| 76 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 167 | [Gamer: A Generalist Vision-Language-Action Foundation Model for Long-Horizon Real-Time Game Agent](https://huggingface.co/papers/2611.18397) | Gamer is a generalist agent framework that integrates perception, memory, and multi-step reasoning, trained through continued pre-training,… | [RainBowLuoCS/Gamer](https://github.com/RainBowLuoCS/Gamer) 1584★ |
| 87 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 94427★ |
| 158 | [ARIS: Autonomous Research via Adversarial Multi-Agent Collaboration](https://huggingface.co/papers/2605.03042) | ARIS is an open-source research harness that uses cross-model adversarial collaboration to ensure reliable long-term research outcomes throu… | [wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) 19984★ |
| 28 | [PaddleOCR-VL-1.6: Expanding the Frontier of Document Parsing with Under-Optimized Region Refinement…](https://huggingface.co/papers/2606.03264) | PaddleOCR-VL-1.6 enhances document parsing performance through targeted data optimization and progressive post-training techniques, achievin… | [PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) 93336★ |
| 21 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 8143★ |
| 72 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 36781★ |
| 38 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 36771★ |
| 24 | [Instruction-Following Evaluation for Large Language Models](https://huggingface.co/papers/2311.07911) | Instruction-Following Eval (IFEval) provides a standardized benchmark for evaluating Large Language Models' ability to follow natural langua… | [google-research/google-research](https://github.com/google-research/google-research) 39532★ |
| 106 | [Embo-Harness: Towards Understanding Frontier-Model-as-Policy Harness](https://huggingface.co/papers/2611.31201) | A systematic framework shows that frontier multimodal models can serve as robot policies when harnessed with interfaces favoring native visu… | 💡 [DravenALG/Embo-Harness](https://github.com/DravenALG/Embo-Harness) 70★ |
| 184 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 84390★ |
| 178 | [SmolDocling: An ultra-compact vision-language model for end-to-end multi-modal document conversion](https://huggingface.co/papers/2503.11576) | SmolDocling is a compact vision-language model that performs end-to-end document conversion with robust performance across various document… | [docling-project/docling](https://github.com/docling-project/docling) 71121★ |
| 69 | [Mixture-of-Loops Transformer](https://huggingface.co/papers/2611.34923) | A Mixture-of-Loops Transformer reuses key-value memory across loops and depths, and its U-shaped variant improves pretraining efficiency and… | 💡 [hustvl/MoLT](https://github.com/hustvl/MoLT) 69★ |
| 3 | [LittleBit: Ultra Low-Bit Quantization via Latent Factorization](https://huggingface.co/papers/2506.13771) | LittleBit is a novel method for extreme compression of large language models using low-rank factorization and multi-scale compensation, achi… | 💡 [SamsungLabs/LittleBit](https://github.com/SamsungLabs/LittleBit) 943★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 18 | [inkling 2 mini gsq rco](https://huggingface.co/ISTA-DASLab/Inkling-2-Mini-GSQ-RCO-GGUF) | text-generation | 158 | 1 |
| 32 | [ming image 0.2 design](https://huggingface.co/inclusionAI/Ming-Image-0.2-Design) | text-to-image | 115 | 1 |
| 40 | [ccore web coder](https://huggingface.co/ccore/CCORE-Web-Coder-4B) | text-generation | 100 | 1 |
| 42 | [gigachat4](https://huggingface.co/ai-sage/GigaChat4-708B-A41B) | text-generation | 58 | 1 |
| 45 | [minimax h3](https://huggingface.co/Comfy-Org/MiniMax-H3) | — | 2861 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 30 | 6 | [Taking Email Back](http://www.linux-magazine.com/Online/Features/Taking-Email-Back) | `email` | [讨论](https://lobste.rs/s/afxeri/taking_email_back) |
| 112 | 17 | [Slow Ubuntu security response times](https://www.openwall.com/lists/oss-security/2026/11/25/9) | `linux` `security` | [讨论](https://lobste.rs/s/wzlzlh/slow_ubuntu_security_response_times) |
| 43 | 3 | [Garage v2.6.0 released with web admin, v1.x EoL & other news](https://garagehq.deuxfleurs.fr/blog/2026-11-webadmin-release/) | `distributed` `release` `web` | [讨论](https://lobste.rs/s/2gfpu3/garage_v2_6_0_released_with_web_admin_v1_x) |
| 27 | 15 | [In defense of lock poisoning in Rust (2025)](https://sunshowers.io/posts/on-poisoning/) | `rust` | [讨论](https://lobste.rs/s/wpylec/defense_lock_poisoning_rust_2025) |
| 10 | 8 | [The need for a formally verifiable mainstream programming language](https://blainehansen.me/post/mainstream-verifiable-language/) | `ai` `building-ai-tooling` `formalmethods` `plt` | [讨论](https://lobste.rs/s/byfdgn/need_for_formally_verifiable_mainstream) |
| 7 | 2 | [AI made self-hosting fun again](https://janlukas.blog/posts/ai-self-hosting) | `ai` `devops` | [讨论](https://lobste.rs/s/xsjwvi/ai_made_self_hosting_fun_again) |
| 43 | 33 | [Entering the Geminispace](https://jmmv.dev/2026/11/entering-the-geminispace.html) | `web` | [讨论](https://lobste.rs/s/8rgqmw/entering_geminispace) |
| 18 | 8 | [How WinHelp files work](https://quin.fyi/posts/how-winhelp-files-work.html) | `programming` `reversing` `rust` `show` | [讨论](https://lobste.rs/s/w4kxiz/how_winhelp_files_work) |
| 53 | 25 | [Generalized Riemann Hypothesis proof in Lean 4, in 76k lines (down from 17M)](https://leanprover.zulipchat.com/#narrow/channel/658556-Riemann-Hypothesis/topic/Cleaning.20up.20the.20proof/near/643702366) | `math` | [讨论](https://lobste.rs/s/tlwot6/generalized_riemann_hypothesis_proof) |
| 56 | 53 | [Scott Aaronson on recent complexity theory AI achievements](https://scottaaronson.blog/?p=10379) | `compsci` `math` | [讨论](https://lobste.rs/s/ilit8q/scott_aaronson_on_recent_complexity) |
| 31 | 9 | [Typed indexes in Zig](https://lvignoli.eu/posts/2026-11-16-typed-indexes-in-zig/) | `programming` `zig` | [讨论](https://lobste.rs/s/l6g7j1/typed_indexes_zig) |
| 13 | 13 | [Ansible Fails waiting for privilege escalation on Ubuntu 26](https://www.jeffgeerling.com/blog/2026/ansible-fails-become-ubuntu2604/) | `devops` `linux` | [讨论](https://lobste.rs/s/3lkriu/ansible_fails_waiting_for_privilege) |
| 29 | 4 | [Browser tabs as a container runtime](https://fzakaria.com/2026/11/25/browser-tabs-as-a-container-runtime) | `browsers` | [讨论](https://lobste.rs/s/hge0sd/browser_tabs_as_container_runtime) |
| 10 | 0 | [London Meetup - 13th December 2026](https://lobste.rs/s/l8cjcz) | `event` | [讨论](https://lobste.rs/s/l8cjcz/london_meetup_13th_december_2026) |
| 25 | 5 | [Make the Plan a Value](https://jackkelly.name/blog/archives/2026/11/26/make_the_plan_a_value) | `haskell` | [讨论](https://lobste.rs/s/9imhob/make_plan_value) |
| 16 | 0 | [Understanding "You are not expected to understand this."](https://www.taniwha.com/~paul/not.html) | `assembly` `c` `unix` | [讨论](https://lobste.rs/s/nkmtqk/understanding_you_are_not_expected) |
| 1 | 0 | [Curb impacts of AI on programming to maintain EU sovereignty](https://www.draketo.de/software/curb-ai-impact) | `ai` | [讨论](https://lobste.rs/s/lmxpfo/curb_impacts_ai_on_programming_maintain) |
| 45 | 0 | [UI style guides](https://aresluna.org/ui-style-guides/) | `graphics` `historical` | [讨论](https://lobste.rs/s/pbfhis/ui_style_guides) |
| 2 | 0 | [Ambiguous Errors Are the Mind Killer](https://amit.prasad.me/blog/ambiguous-errors) | `api` | [讨论](https://lobste.rs/s/wfkkh4/ambiguous_errors_are_mind_killer) |
| 32 | 3 | [The beauty of CSS mixins](https://patrickbrosset.com/articles/2026-11-25-the-beauty-of-css-mixins/) | `css` | [讨论](https://lobste.rs/s/faqxns/beauty_css_mixins) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 117 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 80 | 57 | 71% | — |
| 🔴 先核对 | 45 | 27 | 60% | 0 天 |
| 🟡 在降温 | 6 | 0 | 0% | — |
| 🔵 已被发现 | 5 | 3 | 60% | — |
| 💤 不活跃 | 1 | 0 | 0% | — |
| 🟢 窗口内 | 25 | 11 | 44% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [huamidev/GestaltX](https://github.com/huamidev/GestaltX) | 2026-11-10 | 🚀 爆发 | 3049 | 9035 | 0 | ✅ 起来了 |
| [Marcian15350/mt5-tradeprotocol](https://github.com/Marcian15350/mt5-tradeprotocol) | 2026-11-13 | 🔴 先核对 | 1103 | 0 | 0 | 仓库没了 |
| [apex-compute/ANR](https://github.com/apex-compute/ANR) | 2026-11-13 | 🚀 爆发 | 1082 | 3123 | 2 | ✅ 起来了 |
| [shanselman/gputaskman](https://github.com/shanselman/gputaskman) | 2026-11-13 | 🚀 爆发 | 2802 | 3873 | 0 | 没起来 |
| [vercel-labs/ui](https://github.com/vercel-labs/ui) | 2026-11-13 | 🔴 先核对 | 2182 | 7709 | 0 | ✅ 起来了 |

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
