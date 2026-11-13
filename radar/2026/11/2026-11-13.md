# early-radar 选题雷达 · 2026-11-13

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 98 个，细查前 20 个 · 比上次 = 和 2026-11-12 那次比 · 生成于 2026-11-13 06:10 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 1 个 · Show HN ✅ 24 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 3 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 7 个 · 🟡 在降温 8 个 · 🔵 已被发现 1 个 · 💤 不活跃 0 个 · 🔴 先核对 4 个
- **今天新出现 2 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [storytold/craft-anything](https://github.com/storytold/craft-anything) 平均每天 +2401，见 [爆发](#爆发)
- **复盘**：🚀 爆发 36/52 · 🔴 先核对 15/28 · 🟡 在降温 0/5 · 🔵 已被发现 1/3 · 💤 不活跃 0/1 · 🟢 窗口内 8/17（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [DIYgod/pinky](https://github.com/DIYgod/pinky) — Let AI agents use your phone, with you in the loop.（近 7 天 +2029，刚发布一周内）
  - [sarpstar/cinecode](https://github.com/sarpstar/cinecode) — Films made with code. Short films, long YouTube videos, ads,…（近 7 天 +1873，比前 7 天快 3.8 倍，在加速）
  - [reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA) — Curated tools, case studies and papers for reverse engineeri…（近 7 天 +1534，比前 7 天快 3.3 倍，在加速）
- **趋势信号**：带 `ai-agents` topic 的新仓库这批里有 22 个（star 合计 23338），代表：[reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：4 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Every satellite that passed over any place this week, and its photos](https://www.watched.earth) — 485 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| ✅ [storytold/craft-anything](https://github.com/storytold/craft-anything) | 30350 | 2401 | +1481 | 12.6 | [6](https://news.ycombinator.com/item?id=50377361) | craft anything · storytold craft anything · artcraft craft anything | Craft Anything: understand how any software works, and craft… |
| [deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) | 22821 | 1775 | +236 | 12.9 | [11](https://news.ycombinator.com/item?id=50316116) | dsh superagent prototype · deepseek-ai dsh superagent prototype · deepseek dsh superagent prototype | Towards a More Autonomous Agent System |
| [huamidev/GestaltX](https://github.com/huamidev/GestaltX) | 7037 | 1743 | +488 | 4 | — | gestaltx · huamidev gestaltx | An MobileGestalt editor for iOS 27.x, featuring region-code… |
| [janestreet/agent_skills](https://github.com/janestreet/agent_skills) | 7904 | 827 | +1664 | 9.6 | [662](https://news.ycombinator.com/item?id=50438261) | agent skills · janestreet agent skills · jane agent skills | Agent skills |
| [NotRexed/Hookshot](https://github.com/NotRexed/Hookshot) | 8954 | 1156 | +889 | 7.7 | [2](https://news.ycombinator.com/item?id=50410236) | hookshot · notrexed hookshot | A Native Recompilation Of The Legend Of Zelda: Ocarina Of Ti… |
| [Lee-xeo/Claude-Cage](https://github.com/Lee-xeo/Claude-Cage) | 4984 | 395 | +1073 | 12.6 | — | claude cage · lee-xeo claude cage · shihao claude cage | Cage：为 Claude 特化的轻量化虚拟机，彻底杜绝网络泄露。多平台适配，支持多账号管理、远程部署、移动端操控。 |
| [Minireel/HGhub](https://github.com/Minireel/HGhub) | 8711 | 901 | +378 | 9.7 | — | hghub · minireel hghub | YellowFruit third-party client |
| [zortos293/Lichii](https://github.com/zortos293/Lichii) | 8825 | 697 | +213 | 12.7 | [2](https://news.ycombinator.com/item?id=50435881) | lichii · zortos293 lichii · zortos lichii | VERY experimental Nintendo Switch 2 emulator |
| [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) | 1236 | 293 | +692 | 4.2 | — | agentes chat · agentes-chat agentes chat | Open-source, self-hosted Slack alternative where your team a… |
| 🆕 [shanselman/gputaskman](https://github.com/shanselman/gputaskman) | 2802 | 274 | +641 | 10.2 | — | gputaskman · shanselman gputaskman · scott gputaskman | A GPU task manager for Windows, Linux, and WSL: per-process… |
| [tangerineturtle1/NX2navi](https://github.com/tangerineturtle1/NX2navi) | 3635 | 622 | +308 | 5.8 | — | nx2navi · tangerineturtle1 nx2navi |  |
| [jhaizhou-ops/S2Arm](https://github.com/jhaizhou-ops/S2Arm) | 2797 | 558 | +141 | 5 | — | s2arm · jhaizhou-ops s2arm | Run your own Switch games natively on iPhone, iPad and Mac:… |
| [Kianuni/Erosion-CN](https://github.com/Kianuni/Erosion-CN) | 1750 | 556 | +116 | 3.1 | — | erosion cn · kianuni erosion cn | iOS / iPadOS 系统配置与 MobileGestalt 研究工具箱（简体中文防白苹果安全加固版） |
| 🆕 [apex-compute/ANR](https://github.com/apex-compute/ANR) | 1082 | 522 | — | 2.1 | [2](https://news.ycombinator.com/item?id=50463533) | anr · apex-compute anr · apex anr | Apex Neural Rendering (ANR) by Apex Compute |
| [patch-gg/pixelfx](https://github.com/patch-gg/pixelfx) | 7228 | 517 | +182 | 14 | — | pixelfx · patch-gg pixelfx · patch pixelfx | 244 pixel art effects, every one a small piece of code. Plus… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 91.4 | 🟢 窗口内 | [DIYgod/pinky](https://github.com/DIYgod/pinky) | Go | 2029 | +121 | +2029 | +0 | `·······▃█▄▃▂▂·` | 6 | — | — |
| 2 | 90.4 | 🟢 窗口内 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode) | Python | 2363 | +118 | +1873 | +490 | `····▅▂▂██▄▂▃▂·` | 9 | — | — |
| 3 | 88 | 🟢 窗口内 | [reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA) | Python | 2687 | +79 | +1534 | +467 | `▁▂▂▂▂▂▂█▅▃▂▂▂·` | 28 | — | — |
| 4 | 82.7 | 🟢 窗口内 | [voyager-so/vork](https://github.com/voyager-so/vork) | Rust | 1499 | +32 | +984 | +515 | `······█▇▄▃▂▂▁·` | 7 | [8](https://news.ycombinator.com/item?id=50396650) | — |
| 5 | 76.6 | 🟢 窗口内 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki) | Swift | 1033 | +44 | +592 | +441 | `·····█▄▃▃▅▄▂▂·` | 7 | — | — |
| 6 | 67.4 | 🟢 窗口内 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2869 | +19 | +273 | +248 | `▆▇▄▃▃▆▇▆███▅▃·` | 22 | [3](https://news.ycombinator.com/item?id=50207695) | — |
| 7 | 67.2 | 🟢 窗口内 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | Rust | 2308 | +179 | +269 | +250 | `▂▃▃▃▂▂▂▂▂▂▂▁█·` | 24 | [4](https://news.ycombinator.com/item?id=50340534) | — |
| 8 | 62.8 | 🟡 在降温 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Rust | 1735 | +85 | +534 | +1201 | `···▁█▃▂▂▂▂▁▂▂·` | 11 | — | — |
| 9 | 61.5 | 🟡 在降温 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | TypeScript | 2460 | +41 | +466 | +1994 | `·█▇▄▂▂▂▂▂▂▂▂▁·` | 12 | — | — |
| 10 | 60.3 | 🟡 在降温 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 2403 | +56 | +415 | +1693 | `██▆▄▃▃▃▂▂▂▂▂▂·` | 17 | [2](https://news.ycombinator.com/item?id=50272846) | — |
| 11 | 57.3 | 🟡 在降温 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 2387 | +22 | +308 | +731 | `▂▂▃█▄▃▃▃▂▃▂▂▂·` | 18 | — | — |
| 12 | 54 | 🟡 在降温 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 2676 | +20 | +220 | +539 | `▂▅██▅▃▃▃▃▃▃▃▂·` | 25 | — | — |
| 13 | 49.6 | 🟡 在降温 | [daveebbelaar/bama](https://github.com/daveebbelaar/bama) | Swift | 1789 | +16 | +141 | +676 | `▆█▄▃▃▂▂▂▂▂▂▂▁·` | 19 | — | — |
| 14 | 48 | 🟡 在降温 | [lexifina/global-law](https://github.com/lexifina/global-law) | HTML | 1962 | +17 | +121 | +717 | `█▅▃▂▂▁▁▂▂▁▁▁▁·` | 15 | [1](https://news.ycombinator.com/item?id=50418651) | — |
| 15 | 47.1 | 🟡 在降温 | [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | TypeScript | 1957 | +12 | +110 | +287 | `▄█▆▃▃▅▂▂▃▂▃▃▂·` | 18 | — | — |
| 16 | 46.1 | 🆕 🔴 先核对 | [vercel-labs/ui](https://github.com/vercel-labs/ui) | TypeScript | 2182 | — | +2182 | +1 | `······▁···▁·█·` | 17 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 42.7 | 🔴 先核对 | [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) | TypeScript | 1236 | +692 | +1236 | +0 | `···········██·` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 42 | 🔴 先核对 | [SK-Dev666/rust-external-trainer-tool](https://github.com/SK-Dev666/rust-external-trainer-tool) | TypeScript | 1103 | -97 | +1103 | +0 | `·······▃▂▃▄█··` | 6 | — | fork 不到 star 的 1% |
| 19 | 41.6 | 🔵 已被发现 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt) | TypeScript | 1022 | +474 | +1022 | +0 | `··········▁█▆·` | 2 | [288](https://news.ycombinator.com/item?id=50454625) | — |
| 20 | 21 | 🆕 🔴 先核对 | [Marcian15350/mt5-tradeprotocol](https://github.com/Marcian15350/mt5-tradeprotocol) | TypeScript | 1103 | — | +1103 | +0 | `·······▃▂▃▄█··` | 6 | — | fork 不到 star 的 1%；没有描述 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 654 | 30 | 47544 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) |
| `mcp` | 275 | 30 | 33654 | [reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA)、[vercel-labs/ui](https://github.com/vercel-labs/ui)、[cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) |
| `rust` | 238 | 30 | 38556 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[longbridge/nsh](https://github.com/longbridge/nsh)、[physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) |
| `local-first` | 85 | 30 | 12205 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[yjid/kensaku](https://github.com/yjid/kensaku)、[Ebony-Vinyl/EAC-design-world](https://github.com/Ebony-Vinyl/EAC-design-world) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `ai-agents` | 22 | 23338 | [reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama) |
| `claude-code` | 21 | 26163 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) |
| `codex` | 14 | 18810 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) |
| `windows` | 14 | 14272 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[yjid/kensaku](https://github.com/yjid/kensaku) |
| `agent-skills` | 12 | 19746 | [reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) |
| `macos` | 11 | 12252 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama) |
| `mcp-server` | 8 | 6647 | [reason-machines/reason-network](https://github.com/reason-machines/reason-network)、[Ebony-Vinyl/EAC-design-world](https://github.com/Ebony-Vinyl/EAC-design-world)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) |
| `tauri` | 8 | 6582 | [yjid/kensaku](https://github.com/yjid/kensaku)、[oinkvm/oink](https://github.com/oinkvm/oink)、[torrentplayer/torrentplayer](https://github.com/torrentplayer/torrentplayer) |
| `privacy` | 8 | 5071 | [yjid/kensaku](https://github.com/yjid/kensaku)、[FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[sahenjp/RustXNG](https://github.com/sahenjp/RustXNG) |
| `linux` | 7 | 8030 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt) |
| `open-source` | 7 | 6338 | [yjid/kensaku](https://github.com/yjid/kensaku)、[SK-Dev666/rust-external-trainer-tool](https://github.com/SK-Dev666/rust-external-trainer-tool)、[FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt) |
| `developer-tools` | 7 | 5425 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze)、[SK-Dev666/rust-external-trainer-tool](https://github.com/SK-Dev666/rust-external-trainer-tool)、[kitlangton/scrawl](https://github.com/kitlangton/scrawl) |

**语言分布**：Rust 33 · Python 21 · TypeScript 21 · JavaScript 9 · Go 5 · C++ 2 · HTML 2 · Swift 2

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [DIYgod/pinky](https://github.com/DIYgod/pinky) · 🟢 窗口内 · 91.4 分

> Let AI agents use your phone, with you in the loop.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2029 | +2029 | +0 | 217 | 22 | Go | Apache-2.0 | 11-06（6 天前） | 今天 |

- **近 14 天每天新增**：`·······▃█▄▃▂▂·` 0 0 0 0 0 0 0 219 906 420 222 145 117 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [sarpstar/cinecode](https://github.com/sarpstar/cinecode) · 🟢 窗口内 · 90.4 分

> Films made with code. Short films, long YouTube videos, ads, explainers and music videos: an AI coding agent writes the script, builds every frame in code, designs the sound and hands you an MP4.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2363 | +1873 | +490 | 407 | 11 | Python | MIT | 11-03（9 天前） | 今天 |

- **近 14 天每天新增**：`····▅▂▂██▄▂▃▂·` 0 0 0 0 315 100 75 585 616 265 121 173 113 0
- **势头**：比前 7 天快 3.8 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://x.com/sarpstar>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA) · 🟢 窗口内 · 88 分

> Curated tools, case studies and papers for reverse engineering websites, games, apps, binaries, firmware and protocols. Source-reviewed, English and Chinese.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2687 | +1534 | +467 | 473 | 1849 | Python | MIT | 10-16（28 天前） | 今天 |

- **近 14 天每天新增**：`▁▂▂▂▂▂▂█▅▃▂▂▂·` 45 63 57 74 58 53 117 656 366 198 134 105 75 0
- **势头**：比前 7 天快 3.3 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-agents` `android-reverse-engineering` `awesome` `awesome-list` `awesome-resources` `binary-analysis` `decompilation` `firmware-analysis` `game-reversing` `ghidra` `ios-reverse-engineering` `javascript-deobfuscation` `mcp` `protocol-analysis` `rea` `research-papers` `reverse-engineering` `static-analysis` `web-reverse-engineering`
- **主页**：<https://awesomerea.org>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [voyager-so/vork](https://github.com/voyager-so/vork) · 🟢 窗口内 · 82.7 分

> Headless 3D and VFX engine for agents. Research preview.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1499 | +984 | +515 | 125 | 11 | Rust | — | 11-05（7 天前） | 1 天前 |

- **近 14 天每天新增**：`······█▇▄▃▂▂▁·` 0 0 0 0 0 0 515 446 230 125 50 104 29 0
- **势头**：比前 7 天快 1.9 倍，在加速
- **HN**：发过 2 次，最高 8 分（[讨论](https://news.ycombinator.com/item?id=50396650)）
- **topics**：`3d` `ai-agents` `gpu` `metal` `ray-tracing` `rendering` `rust` `slang` `vfx` `vulkan`
- **主页**：<https://voyager.so/vork>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [JosssphZhou/poki](https://github.com/JosssphZhou/poki) · 🟢 窗口内 · 76.6 分

> Let AI agents operate a real iPhone. Local MCP server and agent, no jailbreak, no extra hardware.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1033 | +592 | +441 | 186 | 91 | Swift | AGPL-3.0 | 11-05（7 天前） | 今天 |

- **近 14 天每天新增**：`·····█▄▃▃▅▄▂▂·` 0 0 0 0 0 310 131 95 90 192 122 48 45 0
- **势头**：比前 7 天快 1.3 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `automation` `ios` `iphone` `mcp` `model-context-protocol`
- **主页**：<https://poki.bot>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [xevrion/hatchzip](https://github.com/xevrion/hatchzip) · 🟢 窗口内 · 67.4 分

> HatchZip is a free, open-source archive extractor for Windows, macOS and Linux that extracts ZIP, 7z, RAR, tar and split archives in place, so it needs free space for the extracted files only. Desktop app and CLI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2869 | +273 | +248 | 99 | 10 | Rust | Apache-2.0 | 10-21（22 天前） | 今天 |

- **近 14 天每天新增**：`▆▇▄▃▃▆▇▆███▅▃·` 39 48 24 21 17 45 54 46 57 59 56 35 20 0
- **势头**：比前 7 天快 1.1 倍，在加速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=50207695)）
- **topics**：`7z` `7zip` `archive` `archive-extractor` `cli` `crash-safe` `disk-space` `extract` `extractor` `gui` `in-place` `linux` `macos` `rar` `rust` `tar` `unrar` `unzip` `windows` `zip`
- **主页**：<https://hatchzip.dev>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [indexable-inc/blaze](https://github.com/indexable-inc/blaze) · 🟢 窗口内 · 67.2 分

> Incremental rust builds up to 92x faster than cargo/rustc

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2308 | +269 | +250 | 86 | 437 | Rust | Apache-2.0 | 10-19（24 天前） | 今天 |

- **近 14 天每天新增**：`▂▃▃▃▂▂▂▂▂▂▂▁█·` 29 55 46 42 24 32 22 15 22 28 19 5 180 0
- **势头**：比前 7 天快 1.1 倍，在加速
- **HN**：发过 1 次，最高 4 分（[讨论](https://news.ycombinator.com/item?id=50340534)）
- **topics**：`cargo` `compiler` `cranelift` `developer-tools` `hot-reload` `incremental-compilation` `jit` `live-coding` `rust` `rust-analyzer`
- **主页**：<https://ix.dev/blaze>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) · 🟡 在降温 · 62.8 分

> Blazing-fast native notes app and rich-text editor for macOS, Windows, and Linux. Built with Rust + GPUI. Local-first and beautifully designed.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1735 | +534 | +1201 | 157 | 71 | Rust | MIT | 11-01（11 天前） | 今天 |

- **近 14 天每天新增**：`···▁█▃▂▂▂▂▁▂▂·` 0 0 0 1 854 265 81 93 125 118 53 62 83 0
- **势头**：只有前 7 天的 44%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://quiet.md>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) · 🟡 在降温 · 61.5 分

> Agent skill: describe your stack in a sentence, get an architecture diagram with official logos

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2460 | +466 | +1994 | 131 | 2 | TypeScript | MIT | 11-01（12 天前） | 今天 |

- **近 14 天每天新增**：`·█▇▄▂▂▂▂▂▂▂▂▁·` 0 722 592 330 144 96 110 87 77 59 64 140 39 0
- **势头**：只有前 7 天的 23%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `architecture-diagram` `claude-code` `claude-skills` `codex` `diagram` `system-architecture` `tech-stack`
- **主页**：<stacks.caru.moe>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) · 🟡 在降温 · 60.3 分

> UEFI pre-driver NVIDIA GPU unlocker for Windows Linux Hackintosh and all EFI-bootable system (Rust): SEC2 scrubber -> FWSEC/WPR2 -> signed Booter -> V67 four-write payload, read-back verified. Verified on most RTX 20 30 40 Series.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2403 | +415 | +1693 | 218 | 20 | Rust | GPL-2.0 | 10-26（17 天前） | 今天 |

- **近 14 天每天新增**：`██▆▄▃▃▃▂▂▂▂▂▂·` 448 418 306 195 113 100 113 80 62 81 62 77 53 0
- **势头**：只有前 7 天的 25%，在减速
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50272846)）
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [vercel-labs/ui](https://github.com/vercel-labs/ui) — 一天进了一半以上的 star，但 HN 上没火过
- [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) — 一天进了一半以上的 star，但 HN 上没火过
- [SK-Dev666/rust-external-trainer-tool](https://github.com/SK-Dev666/rust-external-trainer-tool) — fork 不到 star 的 1%
- [Marcian15350/mt5-tradeprotocol](https://github.com/Marcian15350/mt5-tradeprotocol) — fork 不到 star 的 1%；没有描述

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 485 | 84 | [Show HN: Every satellite that passed over any place this week, and its photos](https://www.watched.earth) | [HN](https://news.ycombinator.com/item?id=50428907) |
| 439 | 167 | [Show HN: My $300 embroidery machine needed a subscription, so I built my own app](https://github.com/simpsoka/zigzag) | [HN](https://news.ycombinator.com/item?id=50470488) |
| 436 | 145 | [Show HN: Get your coding agent off ~2019 JavaScript, onto modern web primitives](https://github.com/GoogleChrome/modern-web-guidance) | [HN](https://news.ycombinator.com/item?id=50443812) |
| 289 | 70 | [Show HN: Coldframe, a honeypot that poses as a supermarket fridge controller](https://github.com/hedgerow-dev/coldframe) | [HN](https://news.ycombinator.com/item?id=50406292) |
| 288 | 111 | [Show HN: Yogurt – Free, private, open-source alternative to Granola](https://github.com/FrigadeHQ/yogurt) | [HN](https://news.ycombinator.com/item?id=50454625) |
| 251 | 62 | [Show HN: Valencia, Spain in Sim City/Isometric View](https://tinyvalencia.com/) | [HN](https://news.ycombinator.com/item?id=50441518) |
| 239 | 94 | [Show HN: I recreated Papers Please but you're deciding which YC startups to fund](https://termsheetplease.com/) | [HN](https://news.ycombinator.com/item?id=50457230) |
| 168 | 137 | [Show HN: A 15 MB self-hosted Netflix and Spotify for your media server](https://github.com/HolyArrs/HolyArrs) | [HN](https://news.ycombinator.com/item?id=50439000) |
| 149 | 66 | [Show HN: Black Ops II statically recompiled to native ARM64 macOS](https://github.com/adrbn/bo2-mac) | [HN](https://news.ycombinator.com/item?id=50449891) |
| 124 | 49 | [Show HN: DBDelve – Open-Source DB Client Made with Rust and GPUI](https://news.ycombinator.com/item?id=50427934) | [HN](https://news.ycombinator.com/item?id=50427934) |
| 124 | 30 | [Show HN: Flide: Make Jev-like decision models up to 9.5x faster](https://github.com/OmniJev/Flide) | [HN](https://news.ycombinator.com/item?id=50421155) |
| 120 | 45 | [Show HN: MeowDisplay Is iPhone Mirroring, but in Reverse](https://meowdisplay.app/) | [HN](https://news.ycombinator.com/item?id=50429636) |
| 115 | 46 | [Show HN: Someone Was Here – Find out who used your Mac while you were away](https://someonewashere.app/) | [HN](https://news.ycombinator.com/item?id=50429812) |
| 115 | 22 | [Show HN: Ghanaian street games you can play in the browser](https://www.ghanastreetgames.com/) | [HN](https://news.ycombinator.com/item?id=50414117) |
| 112 | 43 | [Show HN: STE80 Humanizer – de-AI text by writing 80% of the way to ASD-STE100](https://github.com/Dodaios/ste80-humanizer) | [HN](https://news.ycombinator.com/item?id=50429144) |
| 104 | 20 | [Show HN: Godbolt-in-a-floating-window for Neovim (C, C++, Rust)](https://github.com/0xdeadf1sh/AssemblyForNeovim) | [HN](https://news.ycombinator.com/item?id=50453229) |
| 90 | 41 | [Show HN: Aircad – Professional drafting and 3D modeling in the browser](https://aircad.com) | [HN](https://news.ycombinator.com/item?id=50441350) |
| 90 | 25 | [Show HN: AgentRun – open-source, Self-improving Managed Agents](https://github.com/Parcha-ai/agentrun/blob/main/README.md) | [HN](https://news.ycombinator.com/item?id=50471650) |
| 84 | 14 | [Show HN: We compressed a 31B video+audio diffusion model to 14B, 6 steps, INT8](https://github.com/Video-Rebirth/hyperflow-h3-flash) | [HN](https://news.ycombinator.com/item?id=50405263) |
| 83 | 32 | [Show HN: Klad, a paint app your coding agent can drive (source-available)](https://github.com/klad-app/klad) | [HN](https://news.ycombinator.com/item?id=50454951) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 30 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 10434★ |
| 164 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 122268★ |
| 16 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 5947★ |
| 30 | [MACaQ: Fast, Model Agnostic Calibrated Quantization for Low-Precision Weights and Activations](https://huggingface.co/papers/2611.10649) | MACaQ is an MXFP4 W4A4 post-training quantization method that quantizes each linear layer independently using online activation transforms a… | 💡 [huawei-csl/MACaQ](https://github.com/huawei-csl/MACaQ) 203★ |
| 102 | [Learning Heterogeneous Tactile Representation for General Dexterous Manipulation](https://huggingface.co/papers/2611.12806) | LingBot-Touch is a tactile foundation model that learns a unified, extensible representation across heterogeneous tactile sensors, yielding… | 💡 [Robbyant/lingbot-touch](https://github.com/Robbyant/lingbot-touch) 367★ |
| 186 | [VibeVoice Technical Report](https://huggingface.co/papers/2508.19205) | VibeVoice synthesizes long-form multi-speaker speech using next-token diffusion and a highly efficient continuous speech tokenizer, achievin… | [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice) 57116★ |
| 68 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 23576★ |
| 65 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 47698★ |
| 11 | [e-means: outperforming k-means (in one-tenth the epochs)](https://huggingface.co/papers/2611.09501) | Lloyd's k-means algorithm is a long-running standard for clustering, with applications in data analysis, retrieval, quantization and data cu… | [facebookresearch/faiss](https://github.com/facebookresearch/faiss) 41525★ |
| 86 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 93341★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 35 | [Flide: Accelerating Decision Inference with Exact State Forking](https://huggingface.co/papers/2610.42148) | Flide is an exact inference engine that accelerates decision-model LLM agents by decoupling logical request trees from physical execution an… | 💡 [OmniJev/Flide](https://github.com/OmniJev/Flide) 481★ |
| 111 | [FreeToken: Efficient Edge-Native MoE Serving with Bandwidth-Adaptive Execution](https://huggingface.co/papers/2608.16157) | FreeToken is an edge-native Mixture-of-Experts serving system that dynamically maps computation and model state onto heterogeneous local har… | [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken) 17111★ |
| 39 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 35876★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 35877★ |
| 69 | [SplatAnything: Gaussian Spacing Normalization for Feed-forward 3DGS across Arbitrary Scenes](https://huggingface.co/papers/2611.08264) | SplatAnything applies Gaussian Spacing Normalization to canonicalize scene-level Gaussian spacing, yielding more consistent supervision and… | 💡 [zju3dv/SplatAnything](https://github.com/zju3dv/SplatAnything) 205★ |
| 105 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 31159★ |
| 34 | [HuggingFace's Transformers: State-of-the-art Natural Language Processing](https://huggingface.co/papers/1910.03771) | Transformers library provides state-of-the-art Transformer architectures and pretrained models for natural language processing tasks with a… | [huggingface/transformers](https://github.com/huggingface/transformers) 168909★ |
| 54 | [OmniEdu: Open Foundation Models for Learning and Teaching](https://huggingface.co/papers/2609.23088) | OmniEdu is a family of instruction-tuned educational foundation models that improve K-12 problem solving, curriculum understanding, and tuto… | [haolpku/Omni-Edu](https://github.com/haolpku/Omni-Edu) 1050★ |
| 75 | [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://huggingface.co/papers/2504.19413) | Mem0, a memory-centric architecture with graph-based memory, enhances long-term conversational coherence in LLMs by efficiently extracting,… | [mem0ai/mem0](https://github.com/mem0ai/mem0) 68896★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 43 | [inkling 2 small](https://huggingface.co/thinkingmachines/Inkling-2-Small) | image-text-to-text | 133 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 90 | 4 | [Announcing Rust 1.100.0](https://blog.rust-lang.org/2026/11/12/Rust-1.100.0/) | `release` `rust` | [讨论](https://lobste.rs/s/81hnjw/announcing_rust_1_100_0) |
| 52 | 21 | [The entirety of "Let Over Lambda" is now freely available online](https://letoverlambda.com/) | `book` `lisp` | [讨论](https://lobste.rs/s/ooshl8/entirety_let_over_lambda_is_now_freely) |
| 237 | 28 | [How I accidentally became a millionaire](https://lyra.horse/blog/2026/11/disinformation-machine/) | `security` | [讨论](https://lobste.rs/s/lnau2d/how_i_accidentally_became_millionaire) |
| 29 | 17 | [The anti-marketing aspect of the Gemini network](https://ploum.net/2026-11-12-anti-marketing-gemini.html) | `web` | [讨论](https://lobste.rs/s/pty8pn/anti_marketing_aspect_gemini_network) |
| 56 | 7 | [Hello Baochip](https://ratfactor.com/cards/hello-baochip) | `hardware` | [讨论](https://lobste.rs/s/3gw2f4/hello_baochip) |
| 12 | 6 | [libreagi - save OS models](https://libreagi.com/) | `ai` `privacy` | [讨论](https://lobste.rs/s/7c4iar/libreagi_save_os_models) |
| 21 | 2 | [Adapting CPython for yk](https://tratt.net/laurie/blog/2026/adapting_cpython_for_yk.html) | `compilers` `python` | [讨论](https://lobste.rs/s/gejy85/adapting_cpython_for_yk) |
| 19 | 0 | [Paths in pieces](https://stoppels.ch/2026/11/12/paths-in-pieces.html) | `unix` | [讨论](https://lobste.rs/s/yrpo2q/paths_pieces) |
| 30 | 4 | [The Secret of Monkey Island: all 13 versions side by side](https://monkeyisland.pages.dev/) | `games` `graphics` | [讨论](https://lobste.rs/s/ubbxhd/secret_monkey_island_all_13_versions_side) |
| 41 | 3 | [Hijacking Samsung TV Smart Hub Ads](https://dvratil.cz/2026/11/hijacking-samsung-tv-smart-hub-ads/) | `networking` `reversing` | [讨论](https://lobste.rs/s/2drgwh/hijacking_samsung_tv_smart_hub_ads) |
| 7 | 0 | [Contra "Glue work considered harmful"](https://sunshowers.io/posts/glue-work/) | `practices` | [讨论](https://lobste.rs/s/f6u0cg/contra_glue_work_considered_harmful) |
| 13 | 0 | [FreeBSD Status Report Third Quarter 2026](https://www.freebsd.org/status/report-2026-07-2026-09/) | `freebsd` | [讨论](https://lobste.rs/s/wbkayq/freebsd_status_report_third_quarter_2026) |
| 10 | 0 | [Let’s Write a PostScript Interpreter](https://beyondloom.com/blog/postscript.html) | `concatenative` | [讨论](https://lobste.rs/s/8kdcdd/let_s_write_postscript_interpreter) |
| 5 | 1 | [JIT bitmap text rendering for microcontrollers](https://linebender.org/blog/jit-bitmap-text/) | `graphics` `performance` | [讨论](https://lobste.rs/s/a3elxr/jit_bitmap_text_rendering_for) |
| 84 | 17 | [How a false smoke alarm almost drowned Jane Street's only NYC datacenter](https://michael.bacarella.com/2026/11/10/false-smoke-alarm-jane-street-datacenter/) | `devops` `ml` | [讨论](https://lobste.rs/s/ii1gzp/how_false_smoke_alarm_almost_drowned_jane) |
| 38 | 10 | [For the first time, a C++ standard failed to pass the national bodies](https://herecomesthemoon.net/2026/11/cpp26-failed-the-national-bodies/) | `c++` | [讨论](https://lobste.rs/s/lrpb0m/for_first_time_c_standard_failed_pass) |
| 127 | 72 | [How do you actually self-host securely?](https://lobste.rs/s/m43bas) | `ask` `devops` | [讨论](https://lobste.rs/s/m43bas/how_do_you_actually_self_host_securely) |
| 6 | 2 | [Dyalog Version 21.0](https://dyalog.com/dyalog/dyalog-versions/210.htm) | `apl` `release` | [讨论](https://lobste.rs/s/pbc1ke/dyalog_version_21_0) |
| 4 | 0 | [Futhark-J Bridge](https://chen.cat/j/futhark/) | `apl` | [讨论](https://lobste.rs/s/slkmnx/futhark_j_bridge) |
| 98 | 47 | [What are some "No AI" apps/companies/resources you know of?](https://lobste.rs/s/nld6x3) | `ask` | [讨论](https://lobste.rs/s/nld6x3/what_are_some_no_ai_apps_companies) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 62 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 52 | 36 | 69% | — |
| 🔴 先核对 | 28 | 15 | 53% | — |
| 🟡 在降温 | 5 | 0 | 0% | — |
| 🔵 已被发现 | 3 | 1 | 33% | — |
| 💤 不活跃 | 1 | 0 | 0% | — |
| 🟢 窗口内 | 17 | 8 | 47% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [SoMarkAI/OXR](https://github.com/SoMarkAI/OXR) | 2026-10-30 | 🟢 窗口内 | 2548 | 3802 | 4 | 没起来 |
| [qybaihe/bla](https://github.com/qybaihe/bla) | 2026-10-30 | 🔴 先核对 | 953 | 5483 | 1 | ✅ 起来了 |
| [valentderah/totk-pc-recomp](https://github.com/valentderah/totk-pc-recomp) | 2026-10-30 | 🚀 爆发 | 696 | 6973 | 0 | ✅ 起来了 |

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
