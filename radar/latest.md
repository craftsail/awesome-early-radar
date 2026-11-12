# early-radar 选题雷达 · 2026-11-12

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 99 个，细查前 20 个 · 比上次 = 和 2026-11-11 那次比 · 生成于 2026-11-12 06:51 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 0 个 · Show HN ✅ 23 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 6 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 6 个 · 🟡 在降温 10 个 · 🔵 已被发现 1 个 · 💤 不活跃 0 个 · 🔴 先核对 3 个
- **今天新出现 2 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [storytold/craft-anything](https://github.com/storytold/craft-anything) 平均每天 +2474，见 [爆发](#爆发)
- **复盘**：🚀 爆发 35/51 · 🔴 先核对 14/27 · 🟡 在降温 0/5 · 🔵 已被发现 1/3 · 💤 不活跃 0/1 · 🟢 窗口内 8/16（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [DIYgod/pinky](https://github.com/DIYgod/pinky) — Let AI agents use your phone, with you in the loop.（近 7 天 +1908，刚发布一周内）
  - [sarpstar/cinecode](https://github.com/sarpstar/cinecode) — Films made with code. Short films, long YouTube videos, ads,…（近 7 天 +1829，比前 7 天快 4.4 倍，在加速）
  - [reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA) — Curated tools, case studies and papers for reverse engineeri…（近 7 天 +1572，比前 7 天快 3.8 倍，在加速）
- **趋势信号**：带 `ai-agents` topic 的新仓库这批里有 25 个（star 合计 24910），代表：[reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：5 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Every satellite that passed over any place this week, and its photos](https://www.watched.earth) — 480 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| ✅ [storytold/craft-anything](https://github.com/storytold/craft-anything) | 28869 | 2474 | +1973 | 11.7 | [6](https://news.ycombinator.com/item?id=50377361) | craft anything · storytold craft anything · artcraft craft anything | Craft Anything: understand how any software works, and craft… |
| [Lee-xeo/Claude-Cage](https://github.com/Lee-xeo/Claude-Cage) | 3911 | 336 | +2424 | 11.7 | — | claude cage · lee-xeo claude cage · shihao claude cage | Cage：为 Claude 特化的轻量化虚拟机，彻底杜绝网络泄露。多平台适配，支持多账号管理、远程部署、移动端操控。 |
| [janestreet/agent_skills](https://github.com/janestreet/agent_skills) | 6240 | 727 | +2165 | 8.6 | [10](https://news.ycombinator.com/item?id=50438261) | agent skills · janestreet agent skills · jane agent skills | Agent skills |
| [huamidev/GestaltX](https://github.com/huamidev/GestaltX) | 6549 | 2136 | +1211 | 3.1 | — | gestaltx · huamidev gestaltx | An MobileGestalt editor for iOS 27.x, featuring region-code… |
| [deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) | 22585 | 1900 | +315 | 11.9 | [11](https://news.ycombinator.com/item?id=50316116) | dsh superagent prototype · deepseek-ai dsh superagent prototype · deepseek dsh superagent prototype | Towards a More Autonomous Agent System |
| [anefzaoui/misterdownloadmanager](https://github.com/anefzaoui/misterdownloadmanager) | 7115 | 500 | +1280 | 14.2 | — | misterdownloadmanager · anefzaoui misterdownloadmanager · ahmed misterdownloadmanager | misterdownloadmanager: The ultimate open-source, clean-room… |
| [NotRexed/Hookshot](https://github.com/NotRexed/Hookshot) | 8065 | 1191 | +1258 | 6.8 | [2](https://news.ycombinator.com/item?id=50410236) | hookshot · notrexed hookshot | A Native Recompilation Of The Legend Of Zelda: Ocarina Of Ti… |
| [heydamir/unslop](https://github.com/heydamir/unslop) | 14709 | 1079 | +764 | 13.6 | — | unslop · heydamir unslop · damir unslop | A Claude skill that turns vibecoded, AI-looking UI into a de… |
| [Minireel/HGhub](https://github.com/Minireel/HGhub) | 8333 | 958 | +147 | 8.7 | — | hghub · minireel hghub | YellowFruit third-party client |
| [Kianuni/Erosion-CN](https://github.com/Kianuni/Erosion-CN) | 1634 | 751 | +396 | 2.2 | — | erosion cn · kianuni erosion cn | iOS / iPadOS 系统配置与 MobileGestalt 研究工具箱（简体中文防白苹果安全加固版） |
| [zortos293/Lichii](https://github.com/zortos293/Lichii) | 8612 | 737 | +353 | 11.7 | [2](https://news.ycombinator.com/item?id=50435881) | lichii · zortos293 lichii · zortos lichii | VERY experimental Nintendo Switch 2 emulator |
| [expo/exact](https://github.com/expo/exact) | 3035 | 297 | +689 | 10.2 | [134](https://news.ycombinator.com/item?id=50433541) | exact · expo exact | Write an app once. It runs natively on the web, macOS, iOS,… |
| [tangerineturtle1/NX2navi](https://github.com/tangerineturtle1/NX2navi) | 3327 | 683 | +380 | 4.9 | — | nx2navi · tangerineturtle1 nx2navi |  |
| [jhaizhou-ops/S2Arm](https://github.com/jhaizhou-ops/S2Arm) | 2656 | 657 | +200 | 4 | — | s2arm · jhaizhou-ops s2arm | Run your own Switch games natively on iPhone, iPad and Mac:… |
| [JuneYaooo/rea-video](https://github.com/JuneYaooo/rea-video) | 7201 | 529 | +623 | 13.6 | [4](https://news.ycombinator.com/item?id=50368605) | rea video · juneyaooo rea video | Reverse-engineer any video, shot by shot: filmed, AI-generat… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 90.7 | 🟢 窗口内 | [DIYgod/pinky](https://github.com/DIYgod/pinky) | Go | 1908 | +162 | +1908 | +0 | `········▃█▄▃▂·` | 5 | — | — |
| 2 | 90.1 | 🟢 窗口内 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode) | Python | 2245 | +171 | +1829 | +416 | `·····▅▂▂██▄▂▃·` | 8 | — | — |
| 3 | 88.3 | 🟢 窗口内 | [reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA) | Python | 2608 | +114 | +1572 | +411 | `▂▁▂▂▂▂▂▂█▅▃▂▂·` | 27 | — | — |
| 4 | 87.5 | 🟢 窗口内 | [voyager-so/vork](https://github.com/voyager-so/vork) | Rust | 1467 | +102 | +1467 | +0 | `·······█▇▄▃▂▂·` | 6 | [8](https://news.ycombinator.com/item?id=50396650) | — |
| 5 | 78.3 | 🟢 窗口内 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki) | Swift | 989 | +52 | +679 | +310 | `······█▄▃▃▅▄▂·` | 6 | — | — |
| 6 | 68.8 | 🟢 窗口内 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2850 | +39 | +307 | +225 | `▅▆▇▄▃▃▆▇▆███▅·` | 21 | [3](https://news.ycombinator.com/item?id=50207695) | — |
| 7 | 62.8 | 🟡 在降温 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | TypeScript | 2419 | +156 | +534 | +1885 | `··█▇▄▂▂▂▂▂▂▂▂·` | 11 | — | — |
| 8 | 61.6 | 🟡 在降温 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 2347 | +73 | +471 | +1749 | `▄██▆▄▃▃▃▂▂▂▂▂·` | 17 | [2](https://news.ycombinator.com/item?id=50272846) | — |
| 9 | 59.1 | 🟡 在降温 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 2365 | +34 | +367 | +721 | `▃▂▂▃█▄▃▃▃▂▃▂▂·` | 17 | — | — |
| 10 | 57.6 | 🟡 在降温 | [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) | Kotlin | 2010 | +68 | +316 | +581 | `▆█▇█▆▆▆▅▄▅▅▄▆·` | 21 | — | — |
| 11 | 54.8 | 🟡 在降温 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 2656 | +39 | +238 | +526 | `▂▂▅██▅▃▃▃▃▃▃▃·` | 24 | — | — |
| 12 | 50.8 | 🟡 在降温 | [daveebbelaar/bama](https://github.com/daveebbelaar/bama) | Swift | 1773 | +20 | +159 | +794 | `▆▆█▄▃▃▂▂▂▂▂▂▂·` | 18 | — | — |
| 13 | 47.8 | 🟡 在降温 | [lexifina/global-law](https://github.com/lexifina/global-law) | HTML | 1945 | +18 | +118 | +1643 | `█▃▂▂▁▁▁▁▁▁▁▁▁·` | 14 | [1](https://news.ycombinator.com/item?id=50418651) | — |
| 14 | 47.4 | 🟡 在降温 | [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | TypeScript | 1945 | +27 | +113 | +325 | `▅▄█▆▃▃▅▂▂▃▂▃▃·` | 17 | — | — |
| 15 | 47.2 | 🟡 在降温 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | Rust | 2129 | +6 | +111 | +281 | `█▅█▇▆▄▅▄▃▄▅▃▂·` | 23 | [4](https://news.ycombinator.com/item?id=50340534) | — |
| 16 | 44.1 | 🟡 在降温 | [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) | TypeScript | 2043 | +13 | +81 | +405 | `█▆▆▅▄▃▃▂▂▂▂▂▂·` | 21 | — | — |
| 17 | 42.5 | 🔴 先核对 | [SK-Dev666/rust-external-trainer-tool](https://github.com/SK-Dev666/rust-external-trainer-tool) | TypeScript | 1200 | +427 | +1200 | +0 | `········▅▂▃▄█·` | 5 | — | fork 不到 star 的 1% |
| 18 | 37.8 | 🆕 🔵 已被发现 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt) | TypeScript | 548 | — | +548 | +0 | `···········▁█·` | 1 | [221](https://news.ycombinator.com/item?id=50454625) | — |
| 19 | 37.8 | 🆕 🔴 先核对 | [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) | TypeScript | 544 | — | +544 | +0 | `············█·` | 3 | [5](https://news.ycombinator.com/item?id=49789538) | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 31.4 | 🔴 先核对 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Rust | 1650 | +68 | +530 | +1120 | `····▁█▃▂▂▂▂▁▁·` | 10 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 653 | 30 | 46589 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) |
| `mcp` | 270 | 30 | 29830 | [reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA)、[cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything)、[lexifina/global-law](https://github.com/lexifina/global-law) |
| `rust` | 233 | 30 | 37589 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[longbridge/nsh](https://github.com/longbridge/nsh)、[physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) |
| `local-first` | 80 | 30 | 11755 | [yjid/kensaku](https://github.com/yjid/kensaku)、[s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[Ebony-Vinyl/EAC-design-world](https://github.com/Ebony-Vinyl/EAC-design-world) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `ai-agents` | 25 | 24910 | [reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama) |
| `claude-code` | 22 | 26953 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) |
| `codex` | 16 | 20752 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) |
| `windows` | 15 | 13424 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[yjid/kensaku](https://github.com/yjid/kensaku) |
| `agent-skills` | 12 | 21469 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) |
| `macos` | 12 | 12431 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama) |
| `privacy` | 9 | 4642 | [yjid/kensaku](https://github.com/yjid/kensaku)、[sahenjp/RustXNG](https://github.com/sahenjp/RustXNG)、[FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt) |
| `mcp-server` | 8 | 6558 | [reason-machines/reason-network](https://github.com/reason-machines/reason-network)、[Ebony-Vinyl/EAC-design-world](https://github.com/Ebony-Vinyl/EAC-design-world)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) |
| `tauri` | 8 | 6297 | [yjid/kensaku](https://github.com/yjid/kensaku)、[oinkvm/oink](https://github.com/oinkvm/oink)、[torrentplayer/torrentplayer](https://github.com/torrentplayer/torrentplayer) |
| `linux` | 7 | 7378 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt) |
| `open-source` | 7 | 5831 | [yjid/kensaku](https://github.com/yjid/kensaku)、[SK-Dev666/rust-external-trainer-tool](https://github.com/SK-Dev666/rust-external-trainer-tool)、[FortoGraphy/prism-download-manager](https://github.com/FortoGraphy/prism-download-manager) |
| `developer-tools` | 7 | 5323 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze)、[SK-Dev666/rust-external-trainer-tool](https://github.com/SK-Dev666/rust-external-trainer-tool)、[kitlangton/scrawl](https://github.com/kitlangton/scrawl) |

**语言分布**：Rust 33 · TypeScript 21 · Python 20 · JavaScript 10 · Go 5 · HTML 3 · C++ 2 · Swift 2

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [DIYgod/pinky](https://github.com/DIYgod/pinky) · 🟢 窗口内 · 90.7 分

> Let AI agents use your phone, with you in the loop.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1908 | +1908 | +0 | 198 | 23 | Go | Apache-2.0 | 11-06（5 天前） | 今天 |

- **近 14 天每天新增**：`········▃█▄▃▂·` 0 0 0 0 0 0 0 0 219 908 420 222 139 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [sarpstar/cinecode](https://github.com/sarpstar/cinecode) · 🟢 窗口内 · 90.1 分

> Films made with code. Short films, long YouTube videos, ads, explainers and music videos: an AI coding agent writes the script, builds every frame in code, designs the sound and hands you an MP4.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2245 | +1829 | +416 | 391 | 11 | Python | MIT | 11-03（8 天前） | 8 天前 |

- **近 14 天每天新增**：`·····▅▂▂██▄▂▃·` 0 0 0 0 0 316 100 75 586 616 265 121 166 0
- **势头**：比前 7 天快 4.4 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA) · 🟢 窗口内 · 88.3 分

> Curated tools, case studies and papers for reverse engineering websites, games, apps, binaries, firmware and protocols. Source-reviewed, English and Chinese.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2608 | +1572 | +411 | 464 | 1848 | Python | MIT | 10-16（27 天前） | 今天 |

- **近 14 天每天新增**：`▂▁▂▂▂▂▂▂█▅▃▂▂·` 61 45 63 57 74 58 53 117 656 367 198 134 100 0
- **势头**：比前 7 天快 3.8 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-agents` `android-reverse-engineering` `awesome` `awesome-list` `awesome-resources` `binary-analysis` `decompilation` `firmware-analysis` `game-reversing` `ghidra` `ios-reverse-engineering` `javascript-deobfuscation` `mcp` `protocol-analysis` `rea` `research-papers` `reverse-engineering` `static-analysis` `web-reverse-engineering`
- **主页**：<https://awesomerea.org>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [voyager-so/vork](https://github.com/voyager-so/vork) · 🟢 窗口内 · 87.5 分

> Headless 3D and VFX engine for agents. Research preview.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1467 | +1467 | +0 | 121 | 7 | Rust | — | 11-05（6 天前） | 今天 |

- **近 14 天每天新增**：`·······█▇▄▃▂▂·` 0 0 0 0 0 0 0 515 446 230 125 50 101 0
- **势头**：刚发布一周内
- **HN**：发过 2 次，最高 8 分（[讨论](https://news.ycombinator.com/item?id=50396650)）
- **topics**：`3d` `ai-agents` `gpu` `metal` `ray-tracing` `rendering` `rust` `slang` `vfx` `vulkan`
- **主页**：<https://voyager.so/vork>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [JosssphZhou/poki](https://github.com/JosssphZhou/poki) · 🟢 窗口内 · 78.3 分

> Let AI agents operate a real iPhone. Local MCP server and agent, no jailbreak, no extra hardware.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 989 | +679 | +310 | 182 | 64 | Swift | AGPL-3.0 | 11-05（6 天前） | 今天 |

- **近 14 天每天新增**：`······█▄▃▃▅▄▂·` 0 0 0 0 0 0 310 131 95 90 192 123 48 0
- **势头**：比前 7 天快 2.2 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `automation` `ios` `iphone` `mcp` `model-context-protocol`
- **主页**：<https://poki.bot>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [xevrion/hatchzip](https://github.com/xevrion/hatchzip) · 🟢 窗口内 · 68.8 分

> HatchZip is a free, open-source archive extractor for Windows, macOS and Linux that extracts ZIP, 7z, RAR, tar and split archives in place, so it needs free space for the extracted files only. Desktop app and CLI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2850 | +307 | +225 | 98 | 20 | Rust | Apache-2.0 | 10-21（21 天前） | 今天 |

- **近 14 天每天新增**：`▅▆▇▄▃▃▆▇▆███▅·` 31 39 48 24 21 17 45 54 46 57 59 56 35 0
- **势头**：比前 7 天快 1.4 倍，在加速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=50207695)）
- **topics**：`7z` `7zip` `archive` `archive-extractor` `cli` `crash-safe` `disk-space` `extract` `extractor` `gui` `in-place` `linux` `macos` `rar` `rust` `tar` `unrar` `unzip` `windows` `zip`
- **主页**：<https://hatchzip.dev>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) · 🟡 在降温 · 62.8 分

> Agent skill: describe your stack in a sentence, get an architecture diagram with official logos

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2419 | +534 | +1885 | 127 | 1 | TypeScript | MIT | 11-01（11 天前） | 今天 |

- **近 14 天每天新增**：`··█▇▄▂▂▂▂▂▂▂▂·` 0 0 722 593 330 144 96 110 87 77 59 64 137 0
- **势头**：只有前 7 天的 28%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `architecture-diagram` `claude-code` `claude-skills` `codex` `diagram` `system-architecture` `tech-stack`
- **主页**：<stacks.caru.moe>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) · 🟡 在降温 · 61.6 分

> UEFI pre-driver NVIDIA GPU unlocker for Windows Linux Hackintosh and all EFI-bootable system (Rust): SEC2 scrubber -> FWSEC/WPR2 -> signed Booter -> V67 four-write payload, read-back verified. Verified on most RTX 20 30 40 Series.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2347 | +471 | +1749 | 210 | 20 | Rust | GPL-2.0 | 10-26（17 天前） | 今天 |

- **近 14 天每天新增**：`▄██▆▄▃▃▃▂▂▂▂▂·` 168 448 418 307 195 113 100 113 80 62 81 62 73 0
- **势头**：只有前 7 天的 27%，在减速
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50272846)）
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) · 🟡 在降温 · 59.1 分

> Evidence-first genealogy skill for AI agents (Codex, Claude Code): church books, civil, military, deportation and repression records across the former USSR. Replies in your language.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2365 | +367 | +721 | 234 | 7 | Python | MIT | 10-25（17 天前） | 今天 |

- **近 14 天每天新增**：`▃▂▂▃█▄▃▃▃▂▃▂▂·` 71 61 54 64 285 104 82 81 79 59 66 52 30 0
- **势头**：只有前 7 天的 51%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `archives` `claude-code` `codex` `family-history` `familysearch` `genealogy` `ussr`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) · 🟡 在降温 · 57.6 分

> A community-built phone app for Clean Your TV: clean up an Android TV from your phone. No laptop, no coding agent, nothing uninstalled.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2010 | +316 | +581 | 190 | 8334 | Kotlin | MIT | 10-21（21 天前） | 8 天前 |

- **近 14 天每天新增**：`▆█▇█▆▆▆▅▄▅▅▄▆·` 79 95 92 101 75 66 73 60 42 54 51 42 67 0
- **势头**：只有前 7 天的 54%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adb` `android-tv` `debloat` `fire-tv` `google-tv` `launcher`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [SK-Dev666/rust-external-trainer-tool](https://github.com/SK-Dev666/rust-external-trainer-tool) — fork 不到 star 的 1%
- [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) — 一天进了一半以上的 star，但 HN 上没火过
- [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 480 | 82 | [Show HN: Every satellite that passed over any place this week, and its photos](https://www.watched.earth) | [HN](https://news.ycombinator.com/item?id=50428907) |
| 429 | 142 | [Show HN: Get your coding agent off ~2019 JavaScript, onto modern web primitives](https://github.com/GoogleChrome/modern-web-guidance) | [HN](https://news.ycombinator.com/item?id=50443812) |
| 289 | 70 | [Show HN: Coldframe, a honeypot that poses as a supermarket fridge controller](https://github.com/hedgerow-dev/coldframe) | [HN](https://news.ycombinator.com/item?id=50406292) |
| 247 | 61 | [Show HN: Valencia, Spain in Sim City/Isometric View](https://tinyvalencia.com/) | [HN](https://news.ycombinator.com/item?id=50441518) |
| 221 | 92 | [Show HN: Yogurt – Free, private, open-source alternative to Granola](https://github.com/FrigadeHQ/yogurt) | [HN](https://news.ycombinator.com/item?id=50454625) |
| 209 | 82 | [Show HN: I recreated Papers Please but you're deciding which YC startups to fund](https://termsheetplease.com/) | [HN](https://news.ycombinator.com/item?id=50457230) |
| 176 | 30 | [Show HN: Firenook – Firebase emulators in Rust: 40× faster writes, 10× less RAM](https://firenook.dev/) | [HN](https://news.ycombinator.com/item?id=50378643) |
| 167 | 137 | [Show HN: A 15 MB self-hosted Netflix and Spotify for your media server](https://github.com/HolyArrs/HolyArrs) | [HN](https://news.ycombinator.com/item?id=50439000) |
| 143 | 62 | [Show HN: Black Ops II statically recompiled to native ARM64 macOS](https://github.com/adrbn/bo2-mac) | [HN](https://news.ycombinator.com/item?id=50449891) |
| 124 | 30 | [Show HN: Flide: Make Jev-like decision models up to 9.5x faster](https://github.com/OmniJev/Flide) | [HN](https://news.ycombinator.com/item?id=50421155) |
| 122 | 48 | [Show HN: DBDelve – Open-Source DB Client Made with Rust and GPUI](https://news.ycombinator.com/item?id=50427934) | [HN](https://news.ycombinator.com/item?id=50427934) |
| 120 | 45 | [Show HN: MeowDisplay Is iPhone Mirroring, but in Reverse](https://meowdisplay.app/) | [HN](https://news.ycombinator.com/item?id=50429636) |
| 115 | 45 | [Show HN: Someone Was Here – Find out who used your Mac while you were away](https://someonewashere.app/) | [HN](https://news.ycombinator.com/item?id=50429812) |
| 114 | 22 | [Show HN: Ghanaian street games you can play in the browser](https://www.ghanastreetgames.com/) | [HN](https://news.ycombinator.com/item?id=50414117) |
| 111 | 43 | [Show HN: STE80 Humanizer – de-AI text by writing 80% of the way to ASD-STE100](https://github.com/Dodaios/ste80-humanizer) | [HN](https://news.ycombinator.com/item?id=50429144) |
| 101 | 18 | [Show HN: Godbolt-in-a-floating-window for Neovim (C, C++, Rust)](https://github.com/0xdeadf1sh/AssemblyForNeovim) | [HN](https://news.ycombinator.com/item?id=50453229) |
| 96 | 34 | [Show HN: Stroq – a local audit of what your coding agent did and why](https://github.com/AGGIB/Stroq) | [HN](https://news.ycombinator.com/item?id=50380704) |
| 88 | 48 | [Show HN: Waymark – A workflow engine that compiles jobs instead of replaying](https://github.com/piercefreeman/waymark) | [HN](https://news.ycombinator.com/item?id=50379221) |
| 83 | 14 | [Show HN: We compressed a 31B video+audio diffusion model to 14B, 6 steps, INT8](https://github.com/Video-Rebirth/hyperflow-h3-flash) | [HN](https://news.ycombinator.com/item?id=50405263) |
| 78 | 31 | [Show HN: Klad, a paint app your coding agent can drive (source-available)](https://github.com/klad-app/klad) | [HN](https://news.ycombinator.com/item?id=50454951) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 164 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 122158★ |
| 29 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 10052★ |
| 22 | [MACaQ: Fast, Model Agnostic Calibrated Quantization for Low-Precision Weights and Activations](https://huggingface.co/papers/2611.10649) | MACaQ is an MXFP4 W4A4 post-training quantization method that quantizes each linear layer independently using online activation transforms a… | 💡 [huawei-csl/MACaQ](https://github.com/huawei-csl/MACaQ) 89★ |
| 15 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 5745★ |
| 186 | [VibeVoice Technical Report](https://huggingface.co/papers/2508.19205) | VibeVoice synthesizes long-form multi-speaker speech using next-token diffusion and a highly efficient continuous speech tokenizer, achievin… | [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice) 57055★ |
| 65 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 47639★ |
| 99 | [Learning Heterogeneous Tactile Representation for General Dexterous Manipulation](https://huggingface.co/papers/2611.12806) | LingBot-Touch is a tactile foundation model that learns a unified, extensible representation across heterogeneous tactile sensors, yielding… | 💡 [Robbyant/lingbot-touch](https://github.com/Robbyant/lingbot-touch) 210★ |
| 68 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 23482★ |
| 9 | [e-means: outperforming k-means (in one-tenth the epochs)](https://huggingface.co/papers/2611.09501) | Lloyd's k-means algorithm is a long-running standard for clustering, with applications in data analysis, retrieval, quantization and data cu… | [facebookresearch/faiss](https://github.com/facebookresearch/faiss) 41448★ |
| 35 | [Flide: Accelerating Decision Inference with Exact State Forking](https://huggingface.co/papers/2610.42148) | Flide is an exact inference engine that accelerates decision-model LLM agents by decoupling logical request trees from physical execution an… | 💡 [OmniJev/Flide](https://github.com/OmniJev/Flide) 453★ |
| 86 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 93247★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 70 | [SplatAnything: Gaussian Spacing Normalization for Feed-forward 3DGS across Arbitrary Scenes](https://huggingface.co/papers/2611.08264) | SplatAnything applies Gaussian Spacing Normalization to canonicalize scene-level Gaussian spacing, yielding more consistent supervision and… | 💡 [zju3dv/SplatAnything](https://github.com/zju3dv/SplatAnything) 173★ |
| 111 | [FreeToken: Efficient Edge-Native MoE Serving with Bandwidth-Adaptive Execution](https://huggingface.co/papers/2608.16157) | FreeToken is an edge-native Mixture-of-Experts serving system that dynamically maps computation and model state onto heterogeneous local har… | [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken) 17045★ |
| 105 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 31112★ |
| 39 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 35809★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 35809★ |
| 34 | [HuggingFace's Transformers: State-of-the-art Natural Language Processing](https://huggingface.co/papers/1910.03771) | Transformers library provides state-of-the-art Transformer architectures and pretrained models for natural language processing tasks with a… | [huggingface/transformers](https://github.com/huggingface/transformers) 168887★ |
| 54 | [OmniEdu: Open Foundation Models for Learning and Teaching](https://huggingface.co/papers/2609.23088) | OmniEdu is a family of instruction-tuned educational foundation models that improve K-12 problem solving, curriculum understanding, and tuto… | 💡 [haolpku/Omni-Edu](https://github.com/haolpku/Omni-Edu) 996★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 83523★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

_这次没有（新上榜 0 个）。_

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 73 | 8 | [How I accidentally became a millionaire](https://lyra.horse/blog/2026/11/disinformation-machine/) | `security` | [讨论](https://lobste.rs/s/lnau2d/how_i_accidentally_became_millionaire) |
| 103 | 57 | [How do you actually self-host securely?](https://lobste.rs/s/m43bas) | `ask` `devops` | [讨论](https://lobste.rs/s/m43bas/how_do_you_actually_self_host_securely) |
| 74 | 29 | [What are some "No AI" apps/companies/resources you know of?](https://lobste.rs/s/nld6x3) | `ask` | [讨论](https://lobste.rs/s/nld6x3/what_are_some_no_ai_apps_companies) |
| 52 | 6 | [How a false smoke alarm almost drowned Jane Street's only NYC datacenter](https://michael.bacarella.com/2026/11/10/false-smoke-alarm-jane-street-datacenter/) | `devops` `ml` | [讨论](https://lobste.rs/s/ii1gzp/how_false_smoke_alarm_almost_drowned_jane) |
| 79 | 1 | [In Memoriam: Tim Peters 1952–2026](https://discuss.python.org/t/in-memoriam-tim-peters-1952-2026/110028) | `person` `python` | [讨论](https://lobste.rs/s/romf5e/memoriam_tim_peters_1952_2026) |
| 16 | 1 | [For the first time, a C++ standard failed to pass the national bodies](https://herecomesthemoon.net/2026/11/cpp26-failed-the-national-bodies/) | `c++` | [讨论](https://lobste.rs/s/lrpb0m/for_first_time_c_standard_failed_pass) |
| 42 | 8 | [Using voltage glitching to unleash the A100 in my mining card](https://blog.kate.land/posts/using-voltage-glitching-to-unlock-the-a100/) | `hardware` | [讨论](https://lobste.rs/s/zy4p7f/using_voltage_glitching_unleash_a100_my) |
| 17 | 6 | [About the downtime and security incident](https://danbooru.donmai.us/forum_topics/38685.html) | `security` | [讨论](https://lobste.rs/s/wfr0b4/about_downtime_security_incident) |
| 18 | 5 | [Lock your GitHub Actions](https://hugovk.dev/blog/2026/lock-github-actions/) | `devops` | [讨论](https://lobste.rs/s/v3uidx/lock_your_github_actions) |
| 185 | 27 | [.name grandfathered](https://neil.fraser.name/news/2026/11/10/) | `networking` | [讨论](https://lobste.rs/s/vkkbwo/name_grandfathered) |
| 11 | 2 | [Andrew Kensler's permute(), a function for stateless, constant-time pseudorandom-order array iterati…](https://andrew-helmer.github.io/permute/) | `compsci` | [讨论](https://lobste.rs/s/pdzud6/andrew_kensler_s_permute_function_for) |
| 61 | 20 | [I deleted all my SSH keys](https://blog.infected.systems/posts/2026-11-03-i-deleted-all-my-ssh-keys/) | `hardware` `security` | [讨论](https://lobste.rs/s/sdtcvv/i_deleted_all_my_ssh_keys) |
| 16 | 4 | [London meetup - update](https://lobste.rs/s/miyll7) | `event` | [讨论](https://lobste.rs/s/miyll7/london_meetup_update) |
| 15 | 0 | [Google Summer of Code 2026 results](https://blog.rust-lang.org/2026/11/11/gsoc-2026-results/) | `rust` | [讨论](https://lobste.rs/s/uz2j2h/google_summer_code_2026_results) |
| 10 | 0 | [The Myth of Neutral Code](https://foss.life/notes/2026/the-myth-of-neutral-code/) | `culture` | [讨论](https://lobste.rs/s/sc7qkv/myth_neutral_code) |
| 8 | 0 | [eMudhra Statement on Recent Certificate Security Incident](https://emudhra.com/en/post/certificate-security-incident) | `cryptography` `security` | [讨论](https://lobste.rs/s/pfscsm/emudhra_statement_on_recent_certificate) |
| 44 | 9 | [Go Turns 17](https://go.dev/blog/17years) | `go` | [讨论](https://lobste.rs/s/idktfu/go_turns_17) |
| 10 | 4 | [Monads in Lean](https://eli.thegreenplace.net/2026/monads-in-lean/) | `programming` | [讨论](https://lobste.rs/s/quicny/monads_lean) |
| 4 | 1 | [No Effect Before Its Cause: From Einstein to Lamport](https://www.itworkslocally.dev/posts/no-effect-before-its-cause) | `distributed` | [讨论](https://lobste.rs/s/3rydtk/no_effect_before_its_cause_from_einstein) |
| 82 | 5 | [The hardest tarball](https://stoppels.ch/2026/11/07/the-hardest-tarball.html) | `unix` | [讨论](https://lobste.rs/s/t7qkjb/hardest_tarball) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 61 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 51 | 35 | 68% | — |
| 🔴 先核对 | 27 | 14 | 51% | — |
| 🟡 在降温 | 5 | 0 | 0% | — |
| 🔵 已被发现 | 3 | 1 | 33% | — |
| 💤 不活跃 | 1 | 0 | 0% | — |
| 🟢 窗口内 | 16 | 8 | 50% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) | 2026-10-29 | 🔴 先核对 | 1380 | 2043 | 0 | 没起来 |
| [LNPANDY/NX2Apple](https://github.com/LNPANDY/NX2Apple) | 2026-10-29 | 🚀 爆发 | 1664 | 6236 | 0 | ✅ 起来了 |
| [interplains/Zero-Breach-Toolkit](https://github.com/interplains/Zero-Breach-Toolkit) | 2026-10-29 | 🚀 爆发 | 2923 | 4685 | 0 | 没起来 |
| [l0ng-ai/openidea](https://github.com/l0ng-ai/openidea) | 2026-10-29 | 🔴 先核对 | 774 | 8642 | 41 | ✅ 起来了 |
| [smithjohn78390/tongjiang-lab](https://github.com/smithjohn78390/tongjiang-lab) | 2026-10-29 | 🚀 爆发 | 628 | 0 | 0 | 仓库没了 |
| [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) | 2026-10-29 | 🟢 窗口内 | 1029 | 2010 | 0 | 没起来 |

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
