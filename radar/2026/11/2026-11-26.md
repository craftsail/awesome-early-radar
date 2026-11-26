# early-radar 选题雷达 · 2026-11-26

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 106 个，细查前 20 个 · 比上次 = 和 2026-11-25 那次比 · 生成于 2026-11-26 07:52 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 2 个 · Show HN ✅ 13 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ❌ 1 个没查到，下次再查

## 今日速览

- **有数据源没拿到**：复盘。下面对应的部分是空的或变薄了，不代表今天没有
- **细查 20 个仓库**：🟢 窗口内 14 个 · 🟡 在降温 3 个 · 🔵 已被发现 0 个 · 💤 不活跃 0 个 · 🔴 先核对 3 个
- **今天新出现 3 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [Marvisak/VIctory](https://github.com/Marvisak/VIctory) 平均每天 +5290，见 [爆发](#爆发)
- **复盘**：🚀 爆发 55/77 · 🔴 先核对 26/44 · 🟡 在降温 0/6 · 🔵 已被发现 3/5 · 💤 不活跃 0/1 · 🟢 窗口内 11/25（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) — 20 AI testers on 20 different phones, in parallel, on GitHub…（近 7 天 +2344，比前 7 天快 51.0 倍，在加速）
  - [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) — Paste a link, get captioned 9:16 clips in ~2 min. Free, loca…（近 7 天 +1989，比前 7 天快 3.0 倍，在加速）
  - [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) — Non-invasive MCP accelerator plugin for Google Antigravity (…（近 7 天 +1545，比前 7 天快 38.6 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 30 个（star 合计 31129），代表：[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DIYgod/pinky](https://github.com/DIYgod/pinky)、[sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：4 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: I built a game where you are an LLM's subagent](https://github.com/gulivan/worker755) — 360 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [Marvisak/VIctory](https://github.com/Marvisak/VIctory) | 12804 | 5290 | +1035 | 2.4 | [1](https://news.ycombinator.com/item?id=50622253) | victory · marvisak victory · marvis victory | An attempt at running GTA VI on PC |
| [fxceless/victory-fork](https://github.com/fxceless/victory-fork) | 3159 | 2004 | +752 | 1.6 | — | victory fork · fxceless victory fork · hyphen victory fork | Work-in-progress fork of VIctory: getting an Xbox Series tit… |
| 🆕 [Belobug/VIctory-Belobug-AMD](https://github.com/Belobug/VIctory-Belobug-AMD) | 1692 | 1692 | — | 1 | — | victory belobug amd · belobug victory belobug amd |  |
| [xcl-dev/xcl](https://github.com/xcl-dev/xcl) | 8390 | 1527 | +363 | 5.5 | [24](https://news.ycombinator.com/item?id=45104944) | xcl · xcl-dev xcl · xcl xcl | Xbox Series compatibility layer for Windows - runs console g… |
| [4lwayz/portwatch-vi](https://github.com/4lwayz/portwatch-vi) | 4575 | 1050 | +1436 | 4.4 | — | portwatch vi · 4lwayz portwatch vi | Does GTA VI run on PC yet? A live tracker of community recom… |
| 🆕 [avatarmanz/VIctory-7900XTX](https://github.com/avatarmanz/VIctory-7900XTX) | 1265 | 1265 | — | 1 | — | victory 7900xtx · avatarmanz victory 7900xtx | Goal: an Xbox Series title (your own dump) at a stable 30+ f… |
| [ubiquitarianism/leonida](https://github.com/ubiquitarianism/leonida) | 2390 | 1025 | +355 | 2.3 | — | leonida · ubiquitarianism leonida | A continuation of Leonida, the Xbox > PC port interface for… |
| [erkamyaman/rust-anything](https://github.com/erkamyaman/rust-anything) | 9750 | 993 | +394 | 9.8 | [1](https://news.ycombinator.com/item?id=50558549) | rust anything · erkamyaman rust anything · erkam rust anything | Rewrite your whole app in Rust, one piece at a time, checked… |
| 🆕 [RMvdesi/obsidian-prism](https://github.com/RMvdesi/obsidian-prism) | 1441 | 156 | +966 | 9.2 | — | obsidian prism · rmvdesi obsidian prism | Optical UI, damped-spring choreography, 512K shallow-water v… |
| [EL4CTEO/fast-anything](https://github.com/EL4CTEO/fast-anything) | 4060 | 861 | +326 | 4.7 | [215](https://news.ycombinator.com/item?id=50596155) | fast anything · el4cteo fast anything | Don't rewrite it in Rust. Rewrite the 5% that's slow: profil… |
| [AFK-surf/xnulinux](https://github.com/AFK-surf/xnulinux) | 4047 | 686 | +451 | 5.9 | [628](https://news.ycombinator.com/item?id=50607261) | xnulinux · afk-surf xnulinux · afk xnulinux | XNU as a loadable kernel module inside Linux (macOS personal… |
| 🆕 [alesha-pro/llm.asm](https://github.com/alesha-pro/llm.asm) | 691 | 680 | — | 1 | [134](https://news.ycombinator.com/item?id=50648365) | llm asm · alesha-pro llm asm · alexey llm asm | Qwen3-0.6B inference (12 KB), bare-metal bootable OS (22 KB)… |
| 🆕 [codec-d/cool_fox](https://github.com/codec-d/cool_fox) | 647 | 647 | — | 1 | — | cool fox · codec-d cool fox |  |
| 🆕 [lsernau/grh-lean](https://github.com/lsernau/grh-lean) | 575 | 575 | — | 1 | [425](https://news.ycombinator.com/item?id=50648050) | grh lean · lsernau grh lean | A short Lean 4 proof of the Generalized Riemann Hypothesis |
| 🆕 [crhywun/g1-acq](https://github.com/crhywun/g1-acq) | 1375 | 355 | +534 | 3.9 | — | g1 acq · crhywun g1 acq · chang g1 acq |  |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 93.1 | 🟢 窗口内 | [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) | Python | 2390 | +419 | +2344 | +46 | `···▁▁▁▁▁▁█▆▄▄·` | 9 | — | — |
| 2 | 91.2 | 🟢 窗口内 | [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) | Python | 2645 | +113 | +1989 | +656 | `······▇█▅▄▃▃▂·` | 6 | — | — |
| 3 | 88.1 | 🟢 窗口内 | [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) | TypeScript | 1585 | +244 | +1545 | +40 | `·····▁▁▃▂▆▄█▄·` | 7 | — | — |
| 4 | 87.5 | 🟢 窗口内 | [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) | Python | 2731 | +112 | +1462 | +1269 | `···▆█▃▂▂▆▄▅▄▂·` | 9 | — | — |
| 5 | 86.1 | 🟢 窗口内 | [Avaneesh-Inamdar/Stream-Tube-Desktop](https://github.com/Avaneesh-Inamdar/Stream-Tube-Desktop) | Rust | 1309 | +335 | +1309 | +0 | `·········▂▄█▅·` | 3 | — | — |
| 6 | 84.7 | 🟢 窗口内 | [qianyiai/kurocat](https://github.com/qianyiai/kurocat) | TypeScript | 1165 | +374 | +1165 | +0 | `········▁▅▅▇█·` | 4 | — | — |
| 7 | 83.9 | 🟢 窗口内 | [Lemxy/WinRust](https://github.com/Lemxy/WinRust) | Rust | 1582 | +82 | +1083 | +499 | `····▃▂█▇▅▇▄▃▃·` | 8 | — | — |
| 8 | 82.5 | 🟢 窗口内 | [danielwh2/sprite-stacking](https://github.com/danielwh2/sprite-stacking) | HTML | 962 | +128 | +963 | +0 | `·······██▆▇▅▅·` | 5 | — | — |
| 9 | 81.5 | 🟢 窗口内 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Rust | 2906 | +163 | +893 | +286 | `▂▂▁▁▂▂▂█▄▃▂▂▄·` | 24 | — | — |
| 10 | 79.5 | 🟢 窗口内 | [Ahmet-Dedeler/awesome-gta6-reverse-engineering](https://github.com/Ahmet-Dedeler/awesome-gta6-reverse-engineering) | HTML | 755 | +52 | +755 | +0 | `········▁▅█▃▂·` | 4 | — | — |
| 11 | 79.3 | 🆕 🟢 窗口内 | [xikhar/papercraft](https://github.com/xikhar/papercraft) | JavaScript | 738 | +94 | +738 | +0 | `·······▂▄▆█▅▄·` | 5 | — | — |
| 12 | 77.3 | 🟢 窗口内 | [w01fb0ss/PiBot](https://github.com/w01fb0ss/PiBot) | TypeScript | 628 | +57 | +628 | +0 | `········█▇▃▂▃·` | 5 | — | — |
| 13 | 77 | 🆕 🟢 窗口内 | [chanke17/KuroCat](https://github.com/chanke17/KuroCat) | C++ | 612 | +159 | +612 | +0 | `·········▆█▇▇·` | 3 | — | — |
| 14 | 72.9 | 🆕 🟢 窗口内 | [SulphurS16/Regaliant](https://github.com/SulphurS16/Regaliant) | Rust | 433 | — | +433 | +0 | `··········█▇▄·` | 2 | — | — |
| 15 | 56.7 | 🟡 在降温 | [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) | TypeScript | 2057 | +28 | +288 | +530 | `▆▄█▅▃▃▃▆▃▃▃▂▂·` | 17 | [5](https://news.ycombinator.com/item?id=49789538) | — |
| 16 | 54.7 | 🟡 在降温 | [DIYgod/pinky](https://github.com/DIYgod/pinky) | Go | 2790 | +17 | +237 | +529 | `▆▆▇▆█▇▆▅▄▄▄▄▂·` | 19 | — | — |
| 17 | 53.3 | 🟡 在降温 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode) | Python | 2991 | +48 | +206 | +425 | `█▇▆▅▆▅▅▄▃▅▄▃▅·` | 22 | — | — |
| 18 | 39.6 | 🔴 先核对 | [erkamyaman/safe-anything](https://github.com/erkamyaman/safe-anything) | Rust | 738 | +87 | +738 | +0 | `·········▄█▃▃·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 38.4 | 🔴 先核对 | [Developing-Gamer/agent-sim](https://github.com/Developing-Gamer/agent-sim) | Rust | 605 | +28 | +605 | +0 | `··········▇█▂·` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 21.5 | 🔴 先核对 | [Indigo-0167/universal-game-mod-manager](https://github.com/Indigo-0167/universal-game-mod-manager) | Rust | 1299 | +224 | +1299 | +0 | `···········█▃·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1% |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 1052 | 30 | 41067 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DIYgod/pinky](https://github.com/DIYgod/pinky) |
| `rust` | 204 | 30 | 26406 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[Renly1994/xiaotang-daozai](https://github.com/Renly1994/xiaotang-daozai)、[voyager-so/vork](https://github.com/voyager-so/vork) |
| `mcp` | 198 | 30 | 26898 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[lexifina/global-law](https://github.com/lexifina/global-law)、[JosssphZhou/poki](https://github.com/JosssphZhou/poki) |
| `local-first` | 63 | 30 | 13014 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping)、[w01fb0ss/PiBot](https://github.com/w01fb0ss/PiBot) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 30 | 31129 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DIYgod/pinky](https://github.com/DIYgod/pinky)、[sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) |
| `codex` | 23 | 19405 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat)、[kubai087/kubai-icons](https://github.com/kubai087/kubai-icons) |
| `ai-agents` | 22 | 19014 | [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers)、[JosssphZhou/poki](https://github.com/JosssphZhou/poki)、[agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) |
| `windows` | 22 | 15460 | [Renly1994/xiaotang-daozai](https://github.com/Renly1994/xiaotang-daozai)、[Avaneesh-Inamdar/Stream-Tube-Desktop](https://github.com/Avaneesh-Inamdar/Stream-Tube-Desktop)、[Indigo-0167/universal-game-mod-manager](https://github.com/Indigo-0167/universal-game-mod-manager) |
| `mcp-server` | 17 | 11683 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[INK-Q/agy-fast](https://github.com/INK-Q/agy-fast)、[21stware/bowel](https://github.com/21stware/bowel) |
| `model-context-protocol` | 14 | 10046 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki)、[INK-Q/agy-fast](https://github.com/INK-Q/agy-fast)、[simpsoka/zigzag](https://github.com/simpsoka/zigzag) |
| `macos` | 13 | 7508 | [qianyiai/kurocat](https://github.com/qianyiai/kurocat)、[simpsoka/zigzag](https://github.com/simpsoka/zigzag)、[21stware/bowel](https://github.com/21stware/bowel) |
| `llm` | 12 | 14517 | [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill)、[pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers)、[JosssphZhou/poki](https://github.com/JosssphZhou/poki) |
| `agent-skills` | 12 | 12357 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[kubai087/kubai-icons](https://github.com/kubai087/kubai-icons)、[Dodaios/ste80-humanizer](https://github.com/Dodaios/ste80-humanizer) |
| `desktop-app` | 10 | 6312 | [Avaneesh-Inamdar/Stream-Tube-Desktop](https://github.com/Avaneesh-Inamdar/Stream-Tube-Desktop)、[harshsinghsv/swiftdl](https://github.com/harshsinghsv/swiftdl)、[w01fb0ss/PiBot](https://github.com/w01fb0ss/PiBot) |
| `developer-tools` | 10 | 5014 | [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast)、[alexeyw/lot-map](https://github.com/alexeyw/lot-map)、[devvmhq/devvm](https://github.com/devvmhq/devvm) |
| `open-source` | 9 | 6542 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki)、[Indigo-0167/universal-game-mod-manager](https://github.com/Indigo-0167/universal-game-mod-manager)、[qianyiai/kurocat](https://github.com/qianyiai/kurocat) |

**语言分布**：Rust 28 · TypeScript 26 · Python 20 · JavaScript 7 · Go 6 · HTML 3 · C# 2 · C++ 2

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) · 🟢 窗口内 · 93.1 分

> 20 AI testers on 20 different phones, in parallel, on GitHub's free runners: Claude Code agents on iOS Simulators and Android emulators that find broken flows, translation, layout and accessibility bugs

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2390 | +2344 | +46 | 247 | 10 | Python | MIT | 11-16（9 天前） | 今天 |

- **近 14 天每天新增**：`···▁▁▁▁▁▁█▆▄▄·` 0 0 0 17 14 11 4 3 8 864 658 391 420 0
- **势头**：比前 7 天快 51.0 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`accessibility-testing` `ai-agents` `ai-testing` `android` `android-emulator` `claude` `claude-code` `e2e-testing` `exploratory-testing` `expo` `flutter` `github-actions` `ios` `ios-simulator` `llm` `mobile-testing` `qa` `react-native` `test-automation` `ui-testing`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) · 🟢 窗口内 · 91.2 分

> Paste a link, get captioned 9:16 clips in ~2 min. Free, local, open-source clipping engine (audio-first, YouTube captions, local LLM).

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2645 | +1989 | +656 | 167 | 45 | Python | AGPL-3.0 | 11-19（6 天前） | 1 天前 |

- **近 14 天每天新增**：`······▇█▅▄▃▃▂·` 0 0 0 0 0 0 656 727 458 331 167 191 115 0
- **势头**：比前 7 天快 3.0 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-video-clipper` `clipping` `faster-whisper` `ffmpeg` `gameplay-clipper` `local-llm` `ollama` `open-source-video-editor` `opusclip-alternative` `shorts` `twitch-clips` `vertical-video` `video` `whisper` `youtube-shorts-generator` `yt-dlp`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) · 🟢 窗口内 · 88.1 分

> Non-invasive MCP accelerator plugin for Google Antigravity (CLI/Desktop/IDE): cuts LLM turns (-34%), token quota (-31%), and upload traffic (-40%) without affecting native UI or diffs.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1585 | +1545 | +40 | 87 | 28 | TypeScript | MIT | 11-19（7 天前） | 今天 |

- **近 14 天每天新增**：`·····▁▁▃▂▆▄█▄·` 0 0 0 0 0 6 34 168 52 373 197 504 251 0
- **势头**：比前 7 天快 38.6 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `ai-coding` `antigravity` `antigravity-cli` `antigravity-ide` `antigravity-plugins` `coding-agent` `context-optimization` `developer-productivity` `developer-tools` `gemini` `google-antigravity` `latency-optimization` `mcp` `mcp-plugin` `mcp-server` `model-context-protocol` `performance` `plugin` `token-optimization`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) · 🟢 窗口内 · 87.5 分

> Agent skill for hill-climbing local LLM serving speed (decode, speculative decoding, prefill, KV, startup, TTFT) on any hardware and quantization

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2731 | +1462 | +1269 | 249 | 26 | Python | MIT | 11-16（9 天前） | 9 天前 |

- **近 14 天每天新增**：`···▆█▃▂▂▆▄▅▄▂·` 0 0 0 401 576 179 113 107 407 221 332 283 112 0
- **势头**：比前 7 天快 1.2 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `benchmarking` `claude-code` `inference` `llm` `speculative-decoding`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [Avaneesh-Inamdar/Stream-Tube-Desktop](https://github.com/Avaneesh-Inamdar/Stream-Tube-Desktop) · 🟢 窗口内 · 86.1 分

> Native YouTube client for Windows in Rust, with SponsorBlock, DeArrow and Return YouTube Dislike built in

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1309 | +1309 | +0 | 108 | 46 | Rust | MIT | 11-22（3 天前） | 今天 |

- **近 14 天每天新增**：`·········▂▄█▅·` 0 0 0 0 0 0 0 0 0 48 289 634 338 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`dearrow` `desktop-app` `gpui` `mpv` `rust` `sponsorblock` `windows` `youtube` `youtube-client`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [qianyiai/kurocat](https://github.com/qianyiai/kurocat) · 🟢 窗口内 · 84.7 分

> KuroCat — Free open-source 3D/2D desktop typing cat & AI coding companion (Bongo Cat alternative · Tauri v2 + Rust + MCP · Claude/Codex/DeepSeek/OBS · Win/Mac/Linux/Android)｜开源3D桌面打字小黑猫与AI伴侣

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1165 | +1165 | +0 | 172 | 46 | TypeScript | MIT | 11-21（4 天前） | 今天 |

- **近 14 天每天新增**：`········▁▅▅▇█·` 0 0 0 0 0 0 0 0 18 205 235 330 377 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`3d` `ai-companion` `android` `bongo-cat` `bongocat` `claude-code` `codex` `cross-platform` `desktop-pet` `keyboard-visualizer` `kurocat` `linux` `macos` `mcp` `obs-studio` `open-source` `rust` `tauri` `typing-cat` `windows`
- **主页**：<https://qianyi.one/kurocat/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [Lemxy/WinRust](https://github.com/Lemxy/WinRust) · 🟢 窗口内 · 83.9 分

> Windows shell replacement in Rust: taskbar, file manager, NTFS search, task manager, disk cleaner. One installer exe.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1582 | +1083 | +499 | 109 | 52 | Rust | Apache-2.0 | 11-17（8 天前） | 今天 |

- **近 14 天每天新增**：`····▃▂█▇▅▇▄▃▃·` 0 0 0 0 80 72 347 297 182 300 126 94 84 0
- **势头**：比前 7 天快 2.2 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [danielwh2/sprite-stacking](https://github.com/danielwh2/sprite-stacking) · 🟢 窗口内 · 82.5 分

> Agent skill: turn four pixel art views into fake-3D sprites you can spin. Works with Claude Code, Codex, Cursor, OpenCode, Gemini CLI, Pi.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 962 | +963 | +0 | 80 | 1 | HTML | MIT | 11-20（5 天前） | 1 天前 |

- **近 14 天每天新增**：`·······██▆▇▅▅·` 0 0 0 0 0 0 0 200 201 138 166 129 129 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `claude-code` `codex` `cursor` `fake-3d` `gamedev` `pixel-art` `sprite-stacking` `voxel`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 9. [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) · 🟢 窗口内 · 81.5 分

> Blazing-fast native notes app and rich-text editor for macOS, Windows, and Linux. Built with Rust + GPUI. Local-first and beautifully designed.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2906 | +893 | +286 | 244 | 70 | Rust | MIT | 11-01（24 天前） | 今天 |

- **近 14 天每天新增**：`▂▂▁▁▂▂▂█▄▃▂▂▄·` 64 66 21 26 46 34 29 368 182 88 44 47 164 0
- **势头**：比前 7 天快 3.1 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://quiet.md>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 10. [Ahmet-Dedeler/awesome-gta6-reverse-engineering](https://github.com/Ahmet-Dedeler/awesome-gta6-reverse-engineering) · 🟢 窗口内 · 79.5 分

> Curated list of open-source GTA VI (GTA 6) reverse engineering tools, RAGE 9 / RPF9 archive explorers, TTPF texture & ADAT/AWC audio decoders, format docs, and Xbox Series / PS5 translation layers.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 755 | +755 | +0 | 43 | 0 | HTML | — | 11-21（4 天前） | 今天 |

- **近 14 天每天新增**：`········▁▅█▃▂·` 0 0 0 0 0 0 0 0 24 224 370 84 53 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`awesome` `awesome-list` `game-preservation` `grand-theft-auto-vi` `gta-6` `gta-vi` `gta6` `gtavi` `modding` `rage9` `rdna2` `recompilation` `reverse-engineering` `rpf9` `rust` `scarlett` `ttpf` `xbox-series`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [erkamyaman/safe-anything](https://github.com/erkamyaman/safe-anything) — 一天进了一半以上的 star，但 HN 上没火过
- [Developing-Gamer/agent-sim](https://github.com/Developing-Gamer/agent-sim) — 一天进了一半以上的 star，但 HN 上没火过
- [Indigo-0167/universal-game-mod-manager](https://github.com/Indigo-0167/universal-game-mod-manager) — 一天进了一半以上的 star，但 HN 上没火过；fork 不到 star 的 1%

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 360 | 90 | [Show HN: I built a game where you are an LLM's subagent](https://github.com/gulivan/worker755) | [HN](https://news.ycombinator.com/item?id=50599762) |
| 345 | 79 | [Show HN: Old Nvidia and ATI tech demos, running again in the browser](https://gpu-demo-gallery.pages.dev/) | [HN](https://news.ycombinator.com/item?id=50638503) |
| 238 | 122 | [Show HN: Cornhole News – A Hacker News inspired site for news across the Midwest](https://cornholenews.news) | [HN](https://news.ycombinator.com/item?id=50561515) |
| 181 | 137 | [Show HN: Zero C# – C# without a runtime or GC](https://onurgumus.github.io/zero-csharp/index.html) | [HN](https://news.ycombinator.com/item?id=50590279) |
| 142 | 52 | [Show HN: Fast deterministic natural language search for OpenStreetMap data](https://hippomaps.ch/?q=cafes+by+the+Limmat+100+m+from+the+lake+in+zurich#map=15.02/47.36708/8.54935) | [HN](https://news.ycombinator.com/item?id=50561199) |
| 133 | 96 | [Show HN: Foolscap – a writing app that reads your book and never writes for you](https://foolscap.works/) | [HN](https://news.ycombinator.com/item?id=50559749) |
| 132 | 97 | [Show HN: Drive around my village in 3D](https://cherwellvalleymotorclub.app) | [HN](https://news.ycombinator.com/item?id=50574412) |
| 131 | 36 | [Show HN: OpenComputer – an open source alternative to Devin](https://github.com/diggerhq/opencomputer) | [HN](https://news.ycombinator.com/item?id=50581403) |
| 106 | 10 | [Show HN: An agent skill that optimizes code with falsifiable hypotheses](https://chszlab.github.io/AgenticAlgorithmEngineering/) | [HN](https://news.ycombinator.com/item?id=50611593) |
| 104 | 21 | [Show HN: Mason – A lightweight Postgres read-replica, built on columnar storage](https://masondata.ai/) | [HN](https://news.ycombinator.com/item?id=50630294) |
| 89 | 60 | [Show HN: The Riemann Proof Handbook](https://github.com/tamnd/riemann-handbook) | [HN](https://news.ycombinator.com/item?id=50596664) |
| 51 | 38 | [Show HN: I made a PS1 style racing game](https://outpostracer.com) | [HN](https://news.ycombinator.com/item?id=50589184) |
| 51 | 22 | [Show HN: Type-C – variants, options, generics and pattern matching for C](https://github.com/stass/type-c) | [HN](https://news.ycombinator.com/item?id=50602561) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 18 | [PaperOrchestra: A Multi-Agent Framework for Automated AI Research Paper Writing](https://huggingface.co/papers/2604.05018) | PaperOrchestra is a multi-agent framework that converts unstructured research materials into complete LaTeX manuscripts with literature synt… | [google-research/paper-orchestra](https://github.com/google-research/paper-orchestra) 6405★ |
| 112 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 32793★ |
| 72 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 25193★ |
| 40 | [Depth Pro 2: Sharp and Temporally Consistent Metric Monocular Depth](https://huggingface.co/papers/2611.26603) | A single scalable network estimates dense metric depth for images and video at native resolution, jointly improving metric accuracy, boundar… | 💡 [apple-aiml-research/ml-depth-pro-2](https://github.com/apple-aiml-research/ml-depth-pro-2) 760★ |
| 166 | [Gamer: A Generalist Vision-Language-Action Foundation Model for Long-Horizon Real-Time Game Agent](https://huggingface.co/papers/2611.18397) | Gamer is a generalist agent framework that integrates perception, memory, and multi-step reasoning, trained through continued pre-training,… | [RainBowLuoCS/Gamer](https://github.com/RainBowLuoCS/Gamer) 1541★ |
| 169 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 123762★ |
| 169 | [InCoder-32B: Code Foundation Model for Industrial Scenarios](https://huggingface.co/papers/2603.16790) | InCoder-32B is a 32-billion-parameter code model trained on industrial datasets with extended context length and execution verification to i… | 💡 [CSJianYang/Industrial-Coder](https://github.com/CSJianYang/Industrial-Coder) 619★ |
| 76 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 87 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 94346★ |
| 21 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 8109★ |
| 158 | [ARIS: Autonomous Research via Adversarial Multi-Agent Collaboration](https://huggingface.co/papers/2605.03042) | ARIS is an open-source research harness that uses cross-model adversarial collaboration to ensure reliable long-term research outcomes throu… | [wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) 19914★ |
| 105 | [Embo-Harness: Towards Understanding Frontier-Model-as-Policy Harness](https://huggingface.co/papers/2611.31201) | A systematic framework shows that frontier multimodal models can serve as robot policies when harnessed with interfaces favoring native visu… | 💡 [DravenALG/Embo-Harness](https://github.com/DravenALG/Embo-Harness) 68★ |
| 38 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 36713★ |
| 72 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 36715★ |
| 36 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 12334★ |
| 184 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 84343★ |
| 21 | [π^4: A Foundation Model for 4D Scene Geometry and Motion](https://huggingface.co/papers/2611.23144) | This unified foundation model enables the recovery of dense geometry, camera poses, and object tracking from diverse, uncalibrated observati… | 💡 [yyfz/Pi4](https://github.com/yyfz/Pi4) 502★ |
| 28 | [PaddleOCR-VL-1.6: Expanding the Frontier of Document Parsing with Under-Optimized Region Refinement…](https://huggingface.co/papers/2606.03264) | PaddleOCR-VL-1.6 enhances document parsing performance through targeted data optimization and progressive post-training techniques, achievin… | [PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) 93218★ |
| 110 | [FreeToken: Efficient Edge-Native MoE Serving with Bandwidth-Adaptive Execution](https://huggingface.co/papers/2608.16157) | FreeToken is an edge-native Mixture-of-Experts serving system that dynamically maps computation and model state onto heterogeneous local har… | [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken) 17778★ |
| 24 | [Instruction-Following Evaluation for Large Language Models](https://huggingface.co/papers/2311.07911) | Instruction-Following Eval (IFEval) provides a standardized benchmark for evaluating Large Language Models' ability to follow natural langua… | [google-research/google-research](https://github.com/google-research/google-research) 39448★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 11 | [nemotron labs image](https://huggingface.co/nvidia/Nemotron-Labs-Image-30B-A3B) | text-to-image | 200 | 1 |
| 32 | [magi 2](https://huggingface.co/sand-ai/MAGI-2-preview) | image-text-to-video | 231 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 61 | 2 | [Slow Ubuntu security response times](https://www.openwall.com/lists/oss-security/2026/11/25/9) | `linux` `security` | [讨论](https://lobste.rs/s/wzlzlh/slow_ubuntu_security_response_times) |
| 37 | 15 | [Scott Aaronson on recent complexity theory AI achievements](https://scottaaronson.blog/?p=10379) | `compsci` `math` | [讨论](https://lobste.rs/s/ilit8q/scott_aaronson_on_recent_complexity) |
| 18 | 10 | [Entering the Geminispace](https://jmmv.dev/2026/11/entering-the-geminispace.html) | `web` | [讨论](https://lobste.rs/s/8rgqmw/entering_geminispace) |
| 50 | 7 | [Optimizing Rustc's next trait solver](https://donsz.nl/blog/optimizing-rustcs-next-trait-solver) | `compilers` `performance` `rust` | [讨论](https://lobste.rs/s/lyyksp/optimizing_rustc_s_next_trait_solver) |
| 107 | 21 | [Marginalia Search, Money, C++, Rust, AI, stuff](https://www.marginalia.nu/log/a_141_marginalia_update/) | `c++` `java` `performance` | [讨论](https://lobste.rs/s/srb0dp/marginalia_search_money_c_rust_ai_stuff) |
| 17 | 0 | [Typed indexes in Zig](https://lvignoli.eu/posts/2026-11-16-typed-indexes-in-zig/) | `programming` `zig` | [讨论](https://lobste.rs/s/l6g7j1/typed_indexes_zig) |
| 39 | 3 | [Update on a security incident involving 1Password’s backend systems](https://1password.com/blog/update-on-nov-2026-security-incident) | `security` | [讨论](https://lobste.rs/s/aulbi2/update_on_security_incident_involving) |
| 14 | 3 | [Generalized Riemann Hypothesis proof in Lean 4, in 76k lines (down from 17M)](https://leanprover.zulipchat.com/#narrow/channel/658556-Riemann-Hypothesis/topic/Cleaning.20up.20the.20proof/near/643702366) | `math` | [讨论](https://lobste.rs/s/tlwot6/generalized_riemann_hypothesis_proof) |
| 47 | 0 | [October in Servo: video captions and inert content](https://servo.org/blog/2026/11/25/october-in-servo/) | `browsers` `release` `rust` `web` | [讨论](https://lobste.rs/s/tf9ldm/october_servo_video_captions_inert) |
| 8 | 0 | [Make the Plan a Value](https://jackkelly.name/blog/archives/2026/11/26/make_the_plan_a_value) | `haskell` | [讨论](https://lobste.rs/s/9imhob/make_plan_value) |
| 49 | 75 | [Abolish Lock Poisoning](https://lucumr.pocoo.org/2026/11/25/poisoning/) | `rust` | [讨论](https://lobste.rs/s/sj2pkv/abolish_lock_poisoning) |
| 76 | 5 | [Pokemon Childhood Version: A romhack where Mew is under the truck](https://wheybags.com/blog/pokemon_childhood_version.html) | `assembly` `games` | [讨论](https://lobste.rs/s/em9zdb/pokemon_childhood_version_romhack_where) |
| 83 | 21 | [Why there are still no non-WebKit browsers on iOS](https://blog.mozilla.org/en/mozilla/internet-policy/apple-ios-browser-engine-rules/) | `browsers` `ios` | [讨论](https://lobste.rs/s/sv2flr/why_there_are_still_no_non_webkit_browsers) |
| 2 | 0 | [How WinHelp files work](https://quin.fyi/posts/how-winhelp-files-work.html) | `programming` `reversing` `rust` `show` | [讨论](https://lobste.rs/s/w4kxiz/how_winhelp_files_work) |
| 5 | 0 | [Browser tabs as a container runtime](https://fzakaria.com/2026/11/25/browser-tabs-as-a-container-runtime) | `ai` `browsers` `linux` | [讨论](https://lobste.rs/s/hge0sd/browser_tabs_as_container_runtime) |
| 8 | 0 | [UI style guides](https://aresluna.org/ui-style-guides/) | `graphics` `historical` | [讨论](https://lobste.rs/s/pbfhis/ui_style_guides) |
| 6 | 1 | [The beauty of CSS mixins](https://patrickbrosset.com/articles/2026-11-25-the-beauty-of-css-mixins/) | `css` | [讨论](https://lobste.rs/s/faqxns/beauty_css_mixins) |
| 6 | 1 | [SSH is a GUI framework](https://zydra.sh/articles/ssh-is-a-gui-framework/) | `programming` | [讨论](https://lobste.rs/s/rtde6f/ssh_is_gui_framework) |
| 25 | 2 | [Taking over US Treasury subdomains for $3 each](https://www.intruder.io/research/taking-over-us-treasury-subdomains-for-3-each) | `networking` `security` | [讨论](https://lobste.rs/s/ogxwpi/taking_over_us_treasury_subdomains_for_3) |
| 15 | 2 | [Getting old Java phones online again](https://antcating.github.io/2026/11/23/getting-old-java-phones-online-again.html) | `retrocomputing` | [讨论](https://lobste.rs/s/7x2mrq/getting_old_java_phones_online_again) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 114 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 77 | 55 | 71% | — |
| 🔴 先核对 | 44 | 26 | 59% | 0 天 |
| 🟡 在降温 | 6 | 0 | 0% | — |
| 🔵 已被发现 | 5 | 3 | 60% | — |
| 💤 不活跃 | 1 | 0 | 0% | — |
| 🟢 窗口内 | 25 | 11 | 44% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt) | 2026-11-12 | 🔵 已被发现 | 548 | 3581 | 308 | ✅ 起来了 |
| [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) | 2026-11-12 | 🔴 先核对 | 544 | 2057 | 5 | ✅ 起来了 |

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
