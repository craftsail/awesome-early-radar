# early-radar 选题雷达 · 2026-11-17

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 96 个，细查前 20 个 · 比上次 = 和 2026-11-16 那次比 · 生成于 2026-11-17 07:34 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 0 个 · Show HN ✅ 27 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 4 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 5 个 · 🟡 在降温 11 个 · 🔵 已被发现 1 个 · 💤 不活跃 0 个 · 🔴 先核对 3 个
- **今天新出现 0 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [huamidev/GestaltX](https://github.com/huamidev/GestaltX) 平均每天 +982，见 [爆发](#爆发)
- **复盘**：🚀 爆发 47/63 · 🔴 先核对 19/34 · 🟡 在降温 0/5 · 🔵 已被发现 1/3 · 💤 不活跃 0/1 · 🟢 窗口内 8/19（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) — Open-source, self-hosted Slack alternative where your team a…（近 7 天 +1651，前 7 天没有新增，这周才开始涨）
  - [makepad/relax](https://github.com/makepad/relax) — Relax Rust JIT（近 7 天 +584，刚发布一周内）
  - [credoksopho1984/blender-ai-copilot-studio](https://github.com/credoksopho1984/blender-ai-copilot-studio) — An AI copilot and MCP server for Blender that turns plain-la…（近 7 天 +516，刚发布一周内）
- **趋势信号**：带 `ai-agents` topic 的新仓库这批里有 22 个（star 合计 23119），代表：[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[hitkeeen/blender-ai-mcp-addon](https://github.com/hitkeeen/blender-ai-mcp-addon)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：3 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: My $300 embroidery machine needed a subscription, so I built my own app](https://github.com/simpsoka/zigzag) — 741 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [huamidev/GestaltX](https://github.com/huamidev/GestaltX) | 7950 | 982 | +175 | 8.1 | — | gestaltx · huamidev gestaltx | An MobileGestalt editor for iOS 27.x, featuring region-code… |
| [deepseek-ai/chat-demo](https://github.com/deepseek-ai/chat-demo) | 4279 | 860 | +838 | 5 | [2](https://news.ycombinator.com/item?id=50509966) | chat demo · deepseek-ai chat demo · deepseek chat demo | Chat Demo |
| [janestreet/agent_skills](https://github.com/janestreet/agent_skills) | 9683 | 711 | +543 | 13.6 | [719](https://news.ycombinator.com/item?id=50438261) | agent skills · janestreet agent skills · jane agent skills | Agent skills |
| [Minireel/HGhub](https://github.com/Minireel/HGhub) | 9631 | 702 | +491 | 13.7 | — | hghub · minireel hghub | Plug-in media player |
| 🆕 [ersinkoc/phonebox](https://github.com/ersinkoc/phonebox) | 2086 | 217 | +685 | 9.6 | — | phonebox · ersinkoc phonebox · ersin phonebox | Turn an old Android phone into a customizable desk panel and… |
| 🆕 [Noniv/abyssal-garden](https://github.com/Noniv/abyssal-garden) | 1872 | 395 | +661 | 4.7 | [44](https://news.ycombinator.com/item?id=50506767) | abyssal garden · noniv abyssal garden · maksymilian abyssal garden | A dreamy underwater world you can swim through in your brows… |
| [hitkeeen/blender-ai-mcp-addon](https://github.com/hitkeeen/blender-ai-mcp-addon) | 2310 | 490 | +595 | 4.7 | — | blender ai mcp addon · hitkeeen blender ai mcp addon · hitkeen blender ai mcp addon | AI assistant and MCP server for Blender: visual chat, scene… |
| 🆕 [krisgfx9/Wireless-Device-Battery-Monitor](https://github.com/krisgfx9/Wireless-Device-Battery-Monitor) | 506 | 506 | — | 1 | — | wireless device battery monitor · krisgfx9 wireless device battery monitor · krisgfx wireless device battery monitor | Show the battery level of wireless mice, headsets, keyboards… |
| [duwqijlk/muse-protocol](https://github.com/duwqijlk/muse-protocol) | 1513 | 465 | +348 | 3.3 | — | muse protocol · duwqijlk muse protocol · xcrun muse protocol | muse.ai 注册与邀请码兑换协议研究（纯 HTTP Python 实现） |
| [tangerineturtle1/NX2navi](https://github.com/tangerineturtle1/NX2navi) | 4288 | 433 | +41 | 9.9 | — | nx2navi · tangerineturtle1 nx2navi |  |
| [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop) | 5728 | 410 | +171 | 14 | — | agent autoloop · kkkkhazix agent autoloop · khazix agent autoloop | 让你的命令行 Agent 在后台自己接活、自己跟进到底；平时不烦你，遇到拿不准的事才发卡片找你拍板。 |
| [apex-compute/ANR](https://github.com/apex-compute/ANR) | 2506 | 409 | +232 | 6.1 | [2](https://news.ycombinator.com/item?id=50463533) | anr · apex-compute anr · apex anr | Apex Neural Rendering (ANR) by Apex Compute |
| [jhaizhou-ops/S2Arm](https://github.com/jhaizhou-ops/S2Arm) | 3405 | 375 | +154 | 9.1 | — | s2arm · jhaizhou-ops s2arm | Run your own Switch games natively on iPhone, iPad and Mac:… |
| 🆕 [ZiChuanLan/freebie-radar](https://github.com/ZiChuanLan/freebie-radar) | 1255 | 254 | +364 | 4.9 | — | freebie radar · zichuanlan freebie radar · lan freebie radar | 白嫖与资讯资源聚合雷达：100+个源定时采集 + AI 二审过滤假福利 + 获取方式分级隔离抽奖/试用/推广 + Tel… |
| 🆕 [joshpuckett/allo](https://github.com/joshpuckett/allo) | 506 | 320 | — | 1.6 | — | allo · joshpuckett allo · josh allo | Allo is your friendly neighborhood typeface, free and open s… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 88.9 | 🟢 窗口内 | [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) | TypeScript | 1651 | +101 | +1651 | +0 | `·······██▂▂▃▂·` | 8 | [5](https://news.ycombinator.com/item?id=49789538) | — |
| 2 | 76.5 | 🟢 窗口内 | [makepad/relax](https://github.com/makepad/relax) | Rust | 584 | +19 | +584 | +0 | `·······▆▇█▂▂▁·` | 5 | — | — |
| 3 | 75 | 🟢 窗口内 | [credoksopho1984/blender-ai-copilot-studio](https://github.com/credoksopho1984/blender-ai-copilot-studio) | — | 516 | +3 | +516 | +0 | `········▄▆█▄▁·` | 4 | — | — |
| 4 | 74.9 | 🟢 窗口内 | [racdeufindurch198812/Blender-AI-MCP-Studio](https://github.com/racdeufindurch198812/Blender-AI-MCP-Studio) | — | 514 | +3 | +514 | +0 | `········▄▅█▄▁·` | 4 | — | — |
| 5 | 74.9 | 🟢 窗口内 | [tiobeharxi1987/blender-ai-copilot-flow](https://github.com/tiobeharxi1987/blender-ai-copilot-flow) | — | 514 | +4 | +514 | +0 | `········▄▅█▄▁·` | 4 | — | — |
| 6 | 64 | 🟡 在降温 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki) | Swift | 1537 | +165 | +601 | +936 | `·█▄▃▃▅▄▂▂▃▅▃▄·` | 11 | — | — |
| 7 | 63.3 | 🟡 在降温 | [DIYgod/pinky](https://github.com/DIYgod/pinky) | Go | 2322 | +86 | +560 | +1762 | `···▃█▄▃▂▂▂▂▂▂·` | 10 | — | — |
| 8 | 63.1 | 🟡 在降温 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode) | Python | 2621 | +51 | +547 | +2074 | `▅▂▂██▄▂▃▂▂▂▂▁·` | 13 | — | — |
| 9 | 58 | 🟡 在降温 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Rust | 1916 | +27 | +329 | +1586 | `█▃▂▂▂▂▁▂▂▂▂▁▁·` | 15 | — | — |
| 10 | 57.8 | 🟡 在降温 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 2592 | +39 | +323 | +611 | `█▇█▆▅▆▅▆▄▃▅▅▃·` | 22 | [2](https://news.ycombinator.com/item?id=50272846) | — |
| 11 | 56.3 | 🟡 在降温 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | TypeScript | 2555 | +32 | +277 | +636 | `█▆▆▅▅▄▄█▃▂▂▂▂·` | 16 | — | — |
| 12 | 55.1 | 🟡 在降温 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 2577 | +32 | +246 | +521 | `█▇▆▆▅▅▅▃▃▄▆▄▃·` | 22 | — | — |
| 13 | 54.9 | 🟡 在降温 | [voyager-so/vork](https://github.com/voyager-so/vork) | Rust | 1607 | +10 | +241 | +1366 | `··█▇▄▃▂▂▁▁▂▁▁·` | 11 | [8](https://news.ycombinator.com/item?id=50396650) | — |
| 14 | 52.6 | 🟡 在降温 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 2808 | +56 | +192 | +328 | `█▄▄▄▄▅▄▄▃▂▃▄▅·` | 29 | — | — |
| 15 | 50 | 🟡 在降温 | [lexifina/global-law](https://github.com/lexifina/global-law) | HTML | 2075 | +23 | +148 | +157 | `▇▅▃▅▅▄▅▄▄▄▇█▅·` | 19 | [1](https://news.ycombinator.com/item?id=50418651) | — |
| 16 | 49.3 | 🟡 在降温 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2950 | +21 | +137 | +333 | `▃▆▇▆███▅▃▃▃▃▃·` | 26 | [3](https://news.ycombinator.com/item?id=50207695) | — |
| 17 | 46.5 | 🔴 先核对 | [hitkeeen/blender-ai-mcp-addon](https://github.com/hitkeeen/blender-ai-mcp-addon) | — | 2310 | +595 | +2310 | +0 | `········▁▂▂█▃·` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 45.4 | 🔵 已被发现 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt) | TypeScript | 1916 | +222 | +1916 | +0 | `·······█▇▄▃▃▃·` | 6 | [305](https://news.ycombinator.com/item?id=50454625) | — |
| 19 | 30.9 | 🔴 先核对 | [SK-Dev666/rust-external-trainer-tool](https://github.com/SK-Dev666/rust-external-trainer-tool) | TypeScript | 1103 | +0 | +482 | +621 | `···▃▂▃▄█······` | 10 | — | fork 不到 star 的 1% |
| 20 | 15.5 | 🔴 先核对 | [Marcian15350/mt5-tradeprotocol](https://github.com/Marcian15350/mt5-tradeprotocol) | TypeScript | 1106 | +1 | +485 | +621 | `···▃▂▃▄█·▁▁·▁·` | 10 | — | fork 不到 star 的 1%；没有描述 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 1119 | 30 | 48875 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[sarpstar/cinecode](https://github.com/sarpstar/cinecode)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) |
| `mcp` | 258 | 30 | 33147 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[hitkeeen/blender-ai-mcp-addon](https://github.com/hitkeeen/blender-ai-mcp-addon)、[lexifina/global-law](https://github.com/lexifina/global-law) |
| `rust` | 215 | 30 | 38258 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) |
| `local-first` | 89 | 30 | 13343 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[yjid/kensaku](https://github.com/yjid/kensaku) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `ai-agents` | 22 | 23119 | [shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[hitkeeen/blender-ai-mcp-addon](https://github.com/hitkeeen/blender-ai-mcp-addon)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama) |
| `claude-code` | 20 | 27686 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) |
| `codex` | 16 | 20390 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) |
| `windows` | 15 | 17833 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[oinkvm/oink](https://github.com/oinkvm/oink) |
| `agent-skills` | 12 | 18223 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) |
| `macos` | 11 | 14282 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[oinkvm/oink](https://github.com/oinkvm/oink) |
| `mcp-server` | 11 | 10095 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[hitkeeen/blender-ai-mcp-addon](https://github.com/hitkeeen/blender-ai-mcp-addon)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) |
| `model-context-protocol` | 9 | 8472 | [hitkeeen/blender-ai-mcp-addon](https://github.com/hitkeeen/blender-ai-mcp-addon)、[JosssphZhou/poki](https://github.com/JosssphZhou/poki)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) |
| `llm` | 8 | 7902 | [hitkeeen/blender-ai-mcp-addon](https://github.com/hitkeeen/blender-ai-mcp-addon)、[agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat)、[mdiri-ai/SoduWork](https://github.com/mdiri-ai/SoduWork) |
| `developer-tools` | 8 | 5034 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze)、[SK-Dev666/rust-external-trainer-tool](https://github.com/SK-Dev666/rust-external-trainer-tool)、[jazzenchen/agent-hud-open](https://github.com/jazzenchen/agent-hud-open) |
| `linux` | 7 | 9609 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt) |
| `tauri` | 7 | 6940 | [oinkvm/oink](https://github.com/oinkvm/oink)、[yjid/kensaku](https://github.com/yjid/kensaku)、[torrentplayer/torrentplayer](https://github.com/torrentplayer/torrentplayer) |

**语言分布**：Rust 29 · TypeScript 22 · Python 16 · JavaScript 10 · Go 5 · C++ 2 · HTML 2 · Swift 2

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) · 🟢 窗口内 · 88.9 分

> Open-source, self-hosted Slack alternative where your team and AI agents work together in channels and DMs. Agents run on Claude, ChatGPT/Codex, Gemini or Grok, with MCP tools, their own computer and browser, routines, memory and approvals. Web, desktop and phone apps. Docker Compose + Postgres. AGPL-3.0.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1651 | +1651 | +0 | 295 | 237 | TypeScript | AGPL-3.0 | 11-09（8 天前） | 今天 |

- **近 14 天每天新增**：`·······██▂▂▃▂·` 0 0 0 0 0 0 0 607 638 108 68 148 82 0
- **势头**：前 7 天没有新增，这周才开始涨
- **HN**：发过 7 次，最高 5 分（[讨论](https://news.ycombinator.com/item?id=49789538)）
- **topics**：`agentic-ai` `ai-agents` `browser-automation` `chat` `claude` `claude-code` `codex` `collaboration` `computer-use` `docker-compose` `gemini` `grok` `human-in-the-loop` `llm` `mcp` `multi-agent` `openai` `self-hosted` `slack-alternative` `team-chat`
- **主页**：<https://agentes.chat>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [makepad/relax](https://github.com/makepad/relax) · 🟢 窗口内 · 76.5 分

> Relax Rust JIT

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 584 | +584 | +0 | 31 | 17 | Rust | MIT | 11-11（5 天前） | 今天 |

- **近 14 天每天新增**：`·······▆▇█▂▂▁·` 0 0 0 0 0 0 0 153 161 202 34 20 14 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [credoksopho1984/blender-ai-copilot-studio](https://github.com/credoksopho1984/blender-ai-copilot-studio) · 🟢 窗口内 · 75 分

> An AI copilot and MCP server for Blender that turns plain-language briefs into scene operations—inside a visual chat studio with multi-agent teams, your choice of AI models, and 27 built-in scene tools. · blender-ai-copilot-studio · blender ai · ai for blender · blender copilot · blender ai copilot · blender ai assistant · blender mcp server

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 516 | +516 | +0 | 14 | 48 | — | MIT | 11-12（4 天前） | 1 天前 |

- **近 14 天每天新增**：`········▄▆█▄▁·` 0 0 0 0 0 0 0 0 78 136 205 94 3 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`3d-automation` `3d-modeling` `blender` `blender-addon` `blender-agents` `blender-ai` `blender-assistant` `blender-automation` `blender-chatgpt` `blender-copilot` `blender-extension` `blender-llm` `blender-mcp` `blender-plugin` `blender-scripting` `blender3d` `bpy` `mcp` `mcp-server` `model-context-protocol`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [racdeufindurch198812/Blender-AI-MCP-Studio](https://github.com/racdeufindurch198812/Blender-AI-MCP-Studio) · 🟢 窗口内 · 74.9 分

> Blender AI MCP Studio is an AI assistant and built-in Model Context Protocol MCP server for Blender that turns plain-language briefs into inspected, approved and reversible 3D scene operations — with a visual chat workspace, multi-agent teams and your choice of AI models. · blender ai mcp studio · mcp-for-blender · mcp for blender pro

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 514 | +514 | +0 | 13 | 45 | — | MIT | 11-12（4 天前） | 1 天前 |

- **近 14 天每天新增**：`········▄▅█▄▁·` 0 0 0 0 0 0 0 0 80 126 215 90 3 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`3d-automation` `3d-modeling` `blender` `blender-addon` `blender-agents` `blender-ai` `blender-assistant` `blender-automation` `blender-chatgpt` `blender-copilot` `blender-extension` `blender-llm` `blender-mcp` `blender-plugin` `blender-scripting` `blender3d` `bpy` `mcp` `mcp-server` `model-context-protocol`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [tiobeharxi1987/blender-ai-copilot-flow](https://github.com/tiobeharxi1987/blender-ai-copilot-flow) · 🟢 窗口内 · 74.9 分

> A controlled AI workflow for Blender: every copilot edit is a supervised tool call—proposed, approved, executed in sequence, cancellable after the current step and undoable by name—inside a visual studio with a built-in MCP server. · blender-ai-copilot-flow · blender · blender 3d · blender addon · blender plugin · blender extension

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 514 | +514 | +0 | 12 | 48 | — | MIT | 11-12（4 天前） | 今天 |

- **近 14 天每天新增**：`········▄▅█▄▁·` 0 0 0 0 0 0 0 0 79 134 210 87 4 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`3d-automation` `3d-modeling` `blender` `blender-addon` `blender-agents` `blender-ai` `blender-assistant` `blender-automation` `blender-chatgpt` `blender-copilot` `blender-extension` `blender-llm` `blender-mcp` `blender-plugin` `blender-scripting` `blender3d` `bpy` `mcp` `mcp-server` `model-context-protocol`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [JosssphZhou/poki](https://github.com/JosssphZhou/poki) · 🟡 在降温 · 64 分

> Poki uses your iPhone like you do. An open-source agent that sees your screen and taps, types, and swipes across any app on your real device. Runs locally, plugs right into Claude Code and any MCP agent.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1537 | +601 | +936 | 240 | 72 | Swift | AGPL-3.0 | 11-05（11 天前） | 今天 |

- **近 14 天每天新增**：`·█▄▃▃▅▄▂▂▃▅▃▄·` 0 309 131 94 90 191 121 48 48 102 158 99 146 0
- **势头**：只有前 7 天的 64%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `automation` `ios` `iphone` `mcp` `model-context-protocol`
- **主页**：<https://poki.bot>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 7. [DIYgod/pinky](https://github.com/DIYgod/pinky) · 🟡 在降温 · 63.3 分

> Let AI use your iPhone or Android phone, with you in the loop: any MCP agent from macOS, Windows or Linux, or Pinky itself, right on the phone.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2322 | +560 | +1762 | 248 | 21 | Go | Apache-2.0 | 11-06（10 天前） | 今天 |

- **近 14 天每天新增**：`···▃█▄▃▂▂▂▂▂▂·` 0 0 0 219 904 420 219 142 130 67 71 78 72 0
- **势头**：只有前 7 天的 32%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `android` `claude-code` `ios` `iphone` `mcp` `mcp-server` `phone-automation`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [sarpstar/cinecode](https://github.com/sarpstar/cinecode) · 🟡 在降温 · 63.1 分

> Films made with code. Short films, long YouTube videos, ads, explainers and music videos: an AI coding agent writes the script, builds every frame in code, designs the sound and hands you an MP4.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2621 | +547 | +2074 | 451 | 12 | Python | MIT | 11-03（13 天前） | 4 天前 |

- **近 14 天每天新增**：`▅▂▂██▄▂▃▂▂▂▂▁·` 315 100 75 584 615 265 120 172 117 86 72 58 42 0
- **势头**：只有前 7 天的 26%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://x.com/sarpstar>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) · 🟡 在降温 · 58 分

> Blazing-fast native notes app and rich-text editor for macOS, Windows, and Linux. Built with Rust + GPUI. Local-first and beautifully designed.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1916 | +329 | +1586 | 167 | 72 | Rust | MIT | 11-01（15 天前） | 今天 |

- **近 14 天每天新增**：`█▃▂▂▂▂▁▂▂▂▂▁▁·` 853 265 81 93 125 116 53 62 87 64 69 22 25 0
- **势头**：只有前 7 天的 21%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://quiet.md>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) · 🟡 在降温 · 57.8 分

> UEFI pre-driver NVIDIA GPU unlocker for Windows Linux Hackintosh and all EFI-bootable system (Rust): SEC2 scrubber -> FWSEC/WPR2 -> signed Booter -> V67 four-write payload, read-back verified. Verified on most RTX 20 30 40 Series.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2592 | +323 | +611 | 238 | 25 | Rust | GPL-2.0 | 10-26（22 天前） | 今天 |

- **近 14 天每天新增**：`█▇█▆▅▆▅▆▄▃▅▅▃·` 113 100 113 80 62 81 62 77 55 39 58 62 32 0
- **势头**：只有前 7 天的 53%，在减速
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50272846)）
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [hitkeeen/blender-ai-mcp-addon](https://github.com/hitkeeen/blender-ai-mcp-addon) — 一天进了一半以上的 star，但 HN 上没火过
- [SK-Dev666/rust-external-trainer-tool](https://github.com/SK-Dev666/rust-external-trainer-tool) — fork 不到 star 的 1%
- [Marcian15350/mt5-tradeprotocol](https://github.com/Marcian15350/mt5-tradeprotocol) — fork 不到 star 的 1%；没有描述

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 741 | 258 | [Show HN: My $300 embroidery machine needed a subscription, so I built my own app](https://github.com/simpsoka/zigzag) | [HN](https://news.ycombinator.com/item?id=50470488) |
| 448 | 146 | [Show HN: Get your coding agent off ~2019 JavaScript, onto modern web primitives](https://github.com/GoogleChrome/modern-web-guidance) | [HN](https://news.ycombinator.com/item?id=50443812) |
| 305 | 117 | [Show HN: Yogurt – Free, private, open-source alternative to Granola](https://github.com/FrigadeHQ/yogurt) | [HN](https://news.ycombinator.com/item?id=50454625) |
| 276 | 30 | [Show HN: DeepSeek V3 in ~200 lines of pure Jax](https://github.com/Vaibhaav-Tiwari/deepseek-v3-jax) | [HN](https://news.ycombinator.com/item?id=50497589) |
| 261 | 63 | [Show HN: Valencia, Spain in Sim City/Isometric View](https://tinyvalencia.com/) | [HN](https://news.ycombinator.com/item?id=50441518) |
| 255 | 76 | [Show HN: Isometric SF – A pixel-art map of the SF Bay Area](https://isometricsf.com/) | [HN](https://news.ycombinator.com/item?id=50487228) |
| 248 | 97 | [Show HN: I recreated Papers Please but you're deciding which YC startups to fund](https://termsheetplease.com/) | [HN](https://news.ycombinator.com/item?id=50457230) |
| 219 | 27 | [Show HN: Live map of U.S. flights during tonight's FAA nationwide ground stop](https://grounds.top/) | [HN](https://news.ycombinator.com/item?id=50491545) |
| 171 | 44 | [Show HN: A terminal-native idle factory game, written in Rust with ratatui](https://gitlab.com/snipedbywifi/terminactory) | [HN](https://news.ycombinator.com/item?id=50497132) |
| 170 | 138 | [Show HN: A 15 MB self-hosted Netflix and Spotify for your media server](https://github.com/HolyArrs/HolyArrs) | [HN](https://news.ycombinator.com/item?id=50439000) |
| 153 | 67 | [Show HN: Black Ops II statically recompiled to native ARM64 macOS](https://github.com/adrbn/bo2-mac) | [HN](https://news.ycombinator.com/item?id=50449891) |
| 138 | 41 | [Show HN: AgentRun – open-source, Self-improving Managed Agents](https://github.com/Parcha-ai/agentrun/blob/main/README.md) | [HN](https://news.ycombinator.com/item?id=50471650) |
| 117 | 62 | [Show HN: I have trained 15 blood glucose forecasting models on my own data](https://github.com/0xdeadf1sh/T1DMAI) | [HN](https://news.ycombinator.com/item?id=50444761) |
| 109 | 37 | [Show HN: Agweb – a browser for agents that stays out of your way](https://github.com/paul-nameless/agweb) | [HN](https://news.ycombinator.com/item?id=50497147) |
| 106 | 20 | [Show HN: Godbolt-in-a-floating-window for Neovim (C, C++, Rust)](https://github.com/0xdeadf1sh/AssemblyForNeovim) | [HN](https://news.ycombinator.com/item?id=50453229) |
| 95 | 47 | [Show HN: Aircad – Professional drafting and 3D modeling in the browser](https://aircad.com) | [HN](https://news.ycombinator.com/item?id=50441350) |
| 87 | 2 | [Show HN: Carton Clock – A working pendulum clock made from empty drink cartons](https://www.niklasroy.com/carton-clock/) | [HN](https://news.ycombinator.com/item?id=50482279) |
| 86 | 39 | [Show HN: Fursoy – Out-of-order RV64IMAFDV core in SystemVerilog (Linux 6.6)](https://github.com/FURSOY/fursoy-cpu) | [HN](https://news.ycombinator.com/item?id=50497137) |
| 85 | 17 | [Show HN: The Last Complication, a Zachtronics-style watchmaking puzzle game](https://lastcomplication.com/) | [HN](https://news.ycombinator.com/item?id=50511718) |
| 84 | 34 | [Show HN: Klad, a paint app your coding agent can drive (source-available)](https://github.com/klad-app/klad) | [HN](https://news.ycombinator.com/item?id=50454951) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 4 | [PaperOrchestra: A Multi-Agent Framework for Automated AI Research Paper Writing](https://huggingface.co/papers/2604.05018) | PaperOrchestra is a multi-agent framework that converts unstructured research materials into complete LaTeX manuscripts with literature synt… | [google-research/paper-orchestra](https://github.com/google-research/paper-orchestra) 1732★ |
| 17 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 7261★ |
| 33 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 11961★ |
| 169 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 122889★ |
| 71 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 24151★ |
| 100 | [Gamer: A Generalist Vision-Language-Action Foundation Model for Long-Horizon Real-Time Game Agent](https://huggingface.co/papers/2611.18397) | Gamer is a generalist agent framework that integrates perception, memory, and multi-step reasoning, trained through continued pre-training,… | 💡 [RainBowLuoCS/Gamer](https://github.com/RainBowLuoCS/Gamer) 243★ |
| 105 | [Learning Heterogeneous Tactile Representation for General Dexterous Manipulation](https://huggingface.co/papers/2611.12806) | LingBot-Touch is a tactile foundation model that learns a unified, extensible representation across heterogeneous tactile sensors, yielding… | 💡 [Robbyant/lingbot-touch](https://github.com/Robbyant/lingbot-touch) 692★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 86 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 93606★ |
| 32 | [MACaQ: Fast, Model Agnostic Calibrated Quantization for Low-Precision Weights and Activations](https://huggingface.co/papers/2611.10649) | MACaQ is an MXFP4 W4A4 post-training quantization method that quantizes each linear layer independently using online activation transforms a… | 💡 [huawei-csl/MACaQ](https://github.com/huawei-csl/MACaQ) 339★ |
| 66 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 47905★ |
| 17 | [e-means: outperforming k-means (in one-tenth the epochs)](https://huggingface.co/papers/2611.09501) | Lloyd's k-means algorithm is a long-running standard for clustering, with applications in data analysis, retrieval, quantization and data cu… | [facebookresearch/faiss](https://github.com/facebookresearch/faiss) 41743★ |
| 39 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 36093★ |
| 157 | [ARIS: Autonomous Research via Adversarial Multi-Agent Collaboration](https://huggingface.co/papers/2605.03042) | ARIS is an open-source research harness that uses cross-model adversarial collaboration to ensure reliable long-term research outcomes throu… | [wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) 19320★ |
| 72 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 36093★ |
| 34 | [HuggingFace's Transformers: State-of-the-art Natural Language Processing](https://huggingface.co/papers/1910.03771) | Transformers library provides state-of-the-art Transformer architectures and pretrained models for natural language processing tasks with a… | [huggingface/transformers](https://github.com/huggingface/transformers) 169106★ |
| 76 | [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://huggingface.co/papers/2504.19413) | Mem0, a memory-centric architecture with graph-based memory, enhances long-term conversational coherence in LLMs by efficiently extracting,… | [mem0ai/mem0](https://github.com/mem0ai/mem0) 69088★ |
| 187 | [VibeVoice Technical Report](https://huggingface.co/papers/2508.19205) | VibeVoice synthesizes long-form multi-speaker speech using next-token diffusion and a highly efficient continuous speech tokenizer, achievin… | [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice) 57213★ |
| 182 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 83751★ |
| 55 | [OmniEdu: Open Foundation Models for Learning and Teaching](https://huggingface.co/papers/2609.23088) | OmniEdu is a family of instruction-tuned educational foundation models that improve K-12 problem solving, curriculum understanding, and tuto… | [haolpku/Omni-Edu](https://github.com/haolpku/Omni-Edu) 1223★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

_这次没有（新上榜 0 个）。_

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 23 | 10 | [How Rust Changed Me As A Developer](https://blog.startifact.com/posts/how-rust-changed-me/) | `performance` `rust` | [讨论](https://lobste.rs/s/s7mejx/how_rust_changed_me_as_developer) |
| 57 | 11 | [What is w2rt6byl5nf1opmc-a[.]com?](https://jack.cab/blog/siterate.html) | `web` | [讨论](https://lobste.rs/s/dgvb5g/what_is_w2rt6byl5nf1opmc_com) |
| 68 | 25 | [Migrating from GitHub to Codeberg](https://yorickpeterse.com/articles/migrating-from-github-to-codeberg/) | `programming` `vcs` | [讨论](https://lobste.rs/s/rhoopo/migrating_from_github_codeberg) |
| 28 | 11 | [Janet Reno was talking about my friend Coolio (computer criminal)](https://michael.bacarella.com/2026/11/16/janet-reno-vs-my-friend-coolio/) | `culture` `security` | [讨论](https://lobste.rs/s/urcrqe/janet_reno_was_talking_about_my_friend) |
| 12 | 9 | [On Leaving Swift for Rust](https://www.prux.org/posts/goodbye-swift-hello-rust/) | `mobile` `rust` `swift` | [讨论](https://lobste.rs/s/6t3oi4/on_leaving_swift_for_rust) |
| 23 | 0 | [Improving the Wii U's Wii Mode](https://garyodernichts.blogspot.com/2026/11/improving-wii-us-wii-mode.html) | `graphics` `hardware` `reversing` | [讨论](https://lobste.rs/s/sz6o8w/improving_wii_u_s_wii_mode) |
| 44 | 5 | [Squircles](https://linebender.org/wiki/curves/squircle/) | `graphics` | [讨论](https://lobste.rs/s/iihw5u/squircles) |
| 141 | 34 | [A datetime library for Rust](https://burntsushi.net/jiff/) | `rust` | [讨论](https://lobste.rs/s/dxxvek/datetime_library_for_rust) |
| 17 | 6 | [Quality IMAP, Part 1: Your Mailbox Is A Database](https://aerogramme.deuxfleurs.fr/blog/2026-quality-imap-part-1/) | `email` `testing` | [讨论](https://lobste.rs/s/gm4vao/quality_imap_part_1_your_mailbox_is) |
| 26 | 0 | [Enabling the parallel frontend on nightly](https://blog.rust-lang.org/2026/11/16/enabling-parallel-frontend-on-nightly/) | `rust` | [讨论](https://lobste.rs/s/8eivbk/enabling_parallel_frontend_on_nightly) |
| 72 | 6 | [Paint in the memory of other programs](https://citrons.xyz/journal/2026-04-13) | `programming` `visualization` | [讨论](https://lobste.rs/s/thiekk/paint_memory_other_programs) |
| 17 | 5 | ["Proof of use" as a requirement for open source contributions?](https://lobste.rs/s/ki1l5r) | `ai` `ask` `culture` | [讨论](https://lobste.rs/s/ki1l5r/proof_use_as_requirement_for_open_source) |
| 70 | 11 | [you won't win at copyright](https://ingrids.space/posts/you-wont-win-at-copyright/) | `culture` `law` `philosophy` | [讨论](https://lobste.rs/s/emdfap/you_won_t_win_at_copyright) |
| 13 | 24 | [What are you doing this week?](https://lobste.rs/s/isejqv) | `ask` `programming` | [讨论](https://lobste.rs/s/isejqv/what_are_you_doing_this_week) |
| 43 | 0 | [Universal XSS in uBlock Origin from website-driven element picker](https://iter.ca/post/ubo-uxss/) | `browsers` `security` `web` | [讨论](https://lobste.rs/s/x0ykkw/universal_xss_ublock_origin_from_website) |
| 17 | 1 | [NoisyTCP](https://www.openwall.com/lists/oss-security/2026/11/15/2) | `linux` `security` | [讨论](https://lobste.rs/s/uegnml/noisytcp) |
| 42 | 1 | [Announcing Hegel-clj](https://aphyr.com/posts/428-announcing-hegel-clj) | `clojure` `release` `testing` | [讨论](https://lobste.rs/s/ydzo2o/announcing_hegel_clj) |
| 4 | 0 | [Where did the ACK go?](https://yashgarg.dev/posts/where-did-the-ack-go/) | `networking` `reversing` | [讨论](https://lobste.rs/s/n5jtzr/where_did_ack_go) |
| 9 | 2 | [Software is breaking down at a systemic level](https://www.breck-mckye.com/blog/2026/11/software-is-breaking-down-at-a-systemic-level/) | `culture` | [讨论](https://lobste.rs/s/wifhdc/software_is_breaking_down_at_systemic) |
| 26 | 6 | [beer.drv.drv.drv](https://fzakaria.com/2026/11/14/beer-drv-drv-drv) | `nix` | [讨论](https://lobste.rs/s/md0vco/beer_drv_drv_drv) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 75 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 63 | 47 | 74% | — |
| 🔴 先核对 | 34 | 19 | 55% | — |
| 🟡 在降温 | 5 | 0 | 0% | — |
| 🔵 已被发现 | 3 | 1 | 33% | — |
| 💤 不活跃 | 1 | 0 | 0% | — |
| 🟢 窗口内 | 19 | 8 | 42% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [Balanov/shim](https://github.com/Balanov/shim) | 2026-11-03 | 🔴 先核对 | 358 | 193 | 29 | 没起来 |
| [BryceYuuu/RUN](https://github.com/BryceYuuu/RUN) | 2026-11-03 | 🚀 爆发 | 1985 | 4915 | 0 | ✅ 起来了 |
| [Verlintas/NOIR](https://github.com/Verlintas/NOIR) | 2026-11-03 | 🚀 爆发 | 1487 | 3609 | 0 | ✅ 起来了 |
| [emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) | 2026-11-03 | 🟢 窗口内 | 909 | 1222 | 0 | 没起来 |

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
