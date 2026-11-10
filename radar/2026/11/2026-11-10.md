# early-radar 选题雷达 · 2026-11-10

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 101 个，细查前 20 个 · 比上次 = 和 2026-11-09 那次比 · 生成于 2026-11-10 06:55 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 1 个 · Show HN ✅ 21 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 6 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 4 个 · 🟡 在降温 13 个 · 🔵 已被发现 0 个 · 💤 不活跃 0 个 · 🔴 先核对 3 个
- **今天新出现 2 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [Minireel/HGhub](https://github.com/Minireel/HGhub) 平均每天 +1053，见 [爆发](#爆发)
- **复盘**：🚀 爆发 32/47 · 🔴 先核对 13/25 · 🟡 在降温 0/5 · 🔵 已被发现 1/3 · 🟢 窗口内 8/15（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [sarpstar/cinecode](https://github.com/sarpstar/cinecode) — Films made with code. Short films, long YouTube videos, ads,…（近 7 天 +1952，刚发布一周内）
  - [voyager-so/vork](https://github.com/voyager-so/vork) — Headless 3D and VFX engine for agents. Research preview.（近 7 天 +1314，刚发布一周内）
  - [JosssphZhou/poki](https://github.com/JosssphZhou/poki) — Let AI agents operate a real iPhone. Local MCP server and ag…（近 7 天 +812，刚发布一周内）
- **趋势信号**：带 `ai-agents` topic 的新仓库这批里有 26 个（star 合计 24912），代表：[reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：3 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Every satellite that passed over any place this week, and its photos](https://www.watched.earth) — 300 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [Minireel/HGhub](https://github.com/Minireel/HGhub) | 7058 | 1053 | +3170 | 6.7 | — | hghub · minireel hghub | YellowFruit third-party client |
| 🆕 [huamidev/GestaltX](https://github.com/huamidev/GestaltX) | 3049 | 2852 | — | 1.1 | — | gestaltx · huamidev gestaltx | An MobileGestalt editor for iOS 27.x, featuring region-code… |
| ✅ [storytold/craft-anything](https://github.com/storytold/craft-anything) | 25059 | 2591 | +1904 | 9.7 | [6](https://news.ycombinator.com/item?id=50377361) | craft anything · storytold craft anything · artcraft craft anything | Craft Anything: understand how any software works, and craft… |
| [anefzaoui/misterdownloadmanager](https://github.com/anefzaoui/misterdownloadmanager) | 4535 | 371 | +2374 | 12.2 | — | misterdownloadmanager · anefzaoui misterdownloadmanager · ahmed misterdownloadmanager | misterdownloadmanager: The ultimate open-source, clean-room… |
| [deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) | 21915 | 2216 | +556 | 9.9 | [11](https://news.ycombinator.com/item?id=50316116) | dsh superagent prototype · deepseek-ai dsh superagent prototype · deepseek dsh superagent prototype | Towards a More Autonomous Agent System |
| [NotRexed/Hookshot](https://github.com/NotRexed/Hookshot) | 5453 | 1142 | +2095 | 4.8 | [2](https://news.ycombinator.com/item?id=50410236) | hookshot · notrexed hookshot | A Native Recompilation Of The Legend Of Zelda: Ocarina Of Ti… |
| 🆕 [janestreet/agent_skills](https://github.com/janestreet/agent_skills) | 2542 | 386 | +1916 | 6.6 | [4](https://news.ycombinator.com/item?id=50429183) | agent skills · janestreet agent skills · jane agent skills | Agent skills |
| [jhaizhou-ops/S2Arm](https://github.com/jhaizhou-ops/S2Arm) | 2107 | 1030 | +1280 | 2 | — | s2arm · jhaizhou-ops s2arm | Run your own Switch games natively on iPhone, iPad and Mac:… |
| [heydamir/unslop](https://github.com/heydamir/unslop) | 12934 | 1112 | +785 | 11.6 | — | unslop · heydamir unslop · damir unslop | A Claude skill that turns vibecoded, AI-looking UI into a de… |
| [tangerineturtle1/NX2navi](https://github.com/tangerineturtle1/NX2navi) | 2542 | 885 | +1031 | 2.9 | — | nx2navi · tangerineturtle1 nx2navi |  |
| [JuneYaooo/rea-video](https://github.com/JuneYaooo/rea-video) | 5792 | 499 | +1026 | 11.6 | [4](https://news.ycombinator.com/item?id=50368605) | rea video · juneyaooo rea video | Reverse-engineer any video, shot by shot: filmed, AI-generat… |
| [zortos293/Lichii](https://github.com/zortos293/Lichii) | 7791 | 804 | +775 | 9.7 | [2](https://news.ycombinator.com/item?id=50435881) | lichii · zortos293 lichii · zortos lichii | VERY experimental Nintendo Switch 2 emulator |
| [wangzan101/Mika](https://github.com/wangzan101/Mika) | 7958 | 681 | +170 | 11.7 | — | mika · wangzan101 mika · wangzan mika | An on-device AI agent for Android that operates apps and the… |
| 🆕 [IainKay/ram-altman](https://github.com/IainKay/ram-altman) | 1517 | 329 | +675 | 4.6 | [56](https://news.ycombinator.com/item?id=50424757) | ram altman · iainkay ram altman · iain ram altman | Monitors your RAM and reports any "quite terrible" unused ca… |
| [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop) | 4349 | 625 | +185 | 7 | — | agent autoloop · kkkkhazix agent autoloop · khazix agent autoloop | 让你的命令行 Agent 在后台自己接活、自己跟进到底；平时不烦你，遇到拿不准的事才发卡片找你拍板。 |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 90.9 | 🟢 窗口内 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode) | Python | 1952 | +290 | +1952 | +0 | `·······▅▂▂██▄·` | 6 | — | — |
| 2 | 86.2 | 🟢 窗口内 | [voyager-so/vork](https://github.com/voyager-so/vork) | Rust | 1314 | +140 | +1314 | +0 | `·········█▇▄▃·` | 4 | [8](https://news.ycombinator.com/item?id=50396650) | — |
| 3 | 80.4 | 🟢 窗口内 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki) | Swift | 812 | +190 | +812 | +0 | `········█▄▃▃▅·` | 4 | — | — |
| 4 | 77.7 | 🆕 🟢 窗口内 | [cutetailbud/ff-ruyijs](https://github.com/cutetailbud/ff-ruyijs) | C++ | 1201 | +113 | +650 | +551 | `▆▃▄▃▄▃▃▅▅▅▂█▅·` | 12 | — | — |
| 5 | 71.8 | 🟡 在降温 | [benjitaylor/skills](https://github.com/benjitaylor/skills) | TypeScript | 2929 | +207 | +1313 | +1616 | `···▃▇▇█▆▃▂▅▄▃·` | 15 | — | — |
| 6 | 63.5 | 🟡 在降温 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | TypeScript | 2217 | +62 | +572 | +1645 | `····█▇▄▂▂▂▂▂▂·` | 9 | — | — |
| 7 | 63 | 🟡 在降温 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 2209 | +82 | +546 | +1600 | `▁▂▄██▆▄▃▃▃▂▂▂·` | 15 | [2](https://news.ycombinator.com/item?id=50272846) | — |
| 8 | 62.5 | 🟡 在降温 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) | Python | 2847 | +106 | +517 | +2330 | `···▁▇█▅▄▁▁▁▁▂·` | 13 | — | — |
| 9 | 61.5 | 🟡 在降温 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 2282 | +70 | +470 | +736 | `▄▃▃▂▂▃█▄▃▃▃▂▃·` | 15 | — | — |
| 10 | 58.3 | 🟡 在降温 | [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) | Kotlin | 1898 | +48 | +341 | +644 | `█▆▆▇▇▇▆▅▅▅▄▄▄·` | 19 | — | — |
| 11 | 56.7 | 🟡 在降温 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 2578 | +44 | +289 | +467 | `▃▃▂▂▅██▅▃▃▃▃▃·` | 22 | — | — |
| 12 | 56.4 | 🟡 在降温 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2764 | +66 | +280 | +282 | `█▆▄▅▆▃▃▃▆▆▆▇▇·` | 19 | [3](https://news.ycombinator.com/item?id=50207695) | — |
| 13 | 53.1 | 🟡 在降温 | [daveebbelaar/bama](https://github.com/daveebbelaar/bama) | Swift | 1730 | +25 | +202 | +1142 | `█▆▅▅▇▄▃▂▂▂▂▂▂·` | 16 | — | — |
| 14 | 49.7 | 🟡 在降温 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | Rust | 2106 | +31 | +143 | +388 | `█▃▄▃▄▄▃▂▃▂▂▂▃·` | 21 | [4](https://news.ycombinator.com/item?id=50340534) | — |
| 15 | 49.3 | 🟡 在降温 | [lexifina/global-law](https://github.com/lexifina/global-law) | HTML | 1909 | +20 | +137 | +1772 | `·▂█▃▂▂▁▁▁▁▁▁▁·` | 12 | [1](https://news.ycombinator.com/item?id=50418651) | — |
| 16 | 49.3 | 🟡 在降温 | [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | TypeScript | 1901 | +15 | +138 | +599 | `█▇▃▂▄▃▂▂▃▂▂▂▁·` | 15 | — | — |
| 17 | 47 | 🆕 🔴 先核对 | [janestreet/agent_skills](https://github.com/janestreet/agent_skills) | — | 2541 | +1915 | +2541 | +0 | `········▁▁▁▄█·` | 6 | [4](https://news.ycombinator.com/item?id=50429183) | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 46.6 | 🟡 在降温 | [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) | TypeScript | 2016 | +17 | +105 | +1214 | `█▃▂▂▂▂▁▁▁▁▁▁▁·` | 19 | — | — |
| 19 | 44 | 🔴 先核对 | [DIYgod/pinky](https://github.com/DIYgod/pinky) | Go | 1535 | +490 | +1535 | +0 | `··········▃█▄·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 44 | 🔴 先核对 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Rust | 1531 | +128 | +1530 | +1 | `······▁█▃▂▂▂▂·` | 8 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 637 | 30 | 48570 | [benjitaylor/skills](https://github.com/benjitaylor/skills)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[janestreet/agent_skills](https://github.com/janestreet/agent_skills) |
| `mcp` | 277 | 30 | 33864 | [reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) |
| `rust` | 236 | 30 | 35236 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[longbridge/nsh](https://github.com/longbridge/nsh)、[physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) |
| `local-first` | 76 | 30 | 14367 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot)、[s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[yjid/kensaku](https://github.com/yjid/kensaku) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `ai-agents` | 26 | 24912 | [reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea) |
| `claude-code` | 21 | 28126 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) |
| `codex` | 15 | 19634 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) |
| `agent-skills` | 14 | 23923 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) |
| `windows` | 13 | 12104 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[yjid/kensaku](https://github.com/yjid/kensaku) |
| `macos` | 9 | 10253 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea) |
| `mcp-server` | 9 | 9611 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[reason-machines/reason-network](https://github.com/reason-machines/reason-network)、[alexgaoth/awesome-reverse-engineered](https://github.com/alexgaoth/awesome-reverse-engineered) |
| `open-source` | 8 | 5680 | [yjid/kensaku](https://github.com/yjid/kensaku)、[alexgaoth/awesome-reverse-engineered](https://github.com/alexgaoth/awesome-reverse-engineered)、[FortoGraphy/prism-download-manager](https://github.com/FortoGraphy/prism-download-manager) |
| `claude-skills` | 7 | 13008 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `tauri` | 7 | 5302 | [yjid/kensaku](https://github.com/yjid/kensaku)、[oinkvm/oink](https://github.com/oinkvm/oink)、[torrentplayer/torrentplayer](https://github.com/torrentplayer/torrentplayer) |
| `llm` | 6 | 6045 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot)、[heqiangdiao-wq/AI-Cross-Border-Ecommerce-Agent-Toolkit](https://github.com/heqiangdiao-wq/AI-Cross-Border-Ecommerce-Agent-Toolkit)、[sahenjp/RustXNG](https://github.com/sahenjp/RustXNG) |
| `desktop-app` | 6 | 5210 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot)、[torrentplayer/torrentplayer](https://github.com/torrentplayer/torrentplayer)、[FrigadeHQ/hob](https://github.com/FrigadeHQ/hob) |

**语言分布**：Rust 33 · Python 25 · TypeScript 17 · JavaScript 7 · Go 5 · HTML 5 · C++ 2 · Swift 2

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [sarpstar/cinecode](https://github.com/sarpstar/cinecode) · 🟢 窗口内 · 90.9 分

> Films made with code. Short films, long YouTube videos, ads, explainers and music videos: an AI coding agent writes the script, builds every frame in code, designs the sound and hands you an MP4.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1952 | +1952 | +0 | 345 | 7 | Python | MIT | 11-03（6 天前） | 6 天前 |

- **近 14 天每天新增**：`·······▅▂▂██▄·` 0 0 0 0 0 0 0 316 101 76 588 616 255 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [voyager-so/vork](https://github.com/voyager-so/vork) · 🟢 窗口内 · 86.2 分

> Headless 3D and VFX engine for agents. Research preview.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1314 | +1314 | +0 | 99 | 9 | Rust | — | 11-05（4 天前） | 今天 |

- **近 14 天每天新增**：`·········█▇▄▃·` 0 0 0 0 0 0 0 0 0 516 448 230 120 0
- **势头**：刚发布一周内
- **HN**：发过 2 次，最高 8 分（[讨论](https://news.ycombinator.com/item?id=50396650)）
- **topics**：`3d` `ai-agents` `gpu` `metal` `ray-tracing` `rendering` `rust` `slang` `vfx` `vulkan`
- **主页**：<https://voyager.so/vork>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [JosssphZhou/poki](https://github.com/JosssphZhou/poki) · 🟢 窗口内 · 80.4 分

> Let AI agents operate a real iPhone. Local MCP server and agent, no jailbreak, no extra hardware.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 812 | +812 | +0 | 170 | 38 | Swift | AGPL-3.0 | 11-05（4 天前） | 今天 |

- **近 14 天每天新增**：`········█▄▃▃▅·` 0 0 0 0 0 0 0 0 311 132 96 91 182 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `automation` `ios` `iphone` `mcp` `model-context-protocol`
- **主页**：<https://poki.bot>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. 🆕 [cutetailbud/ff-ruyijs](https://github.com/cutetailbud/ff-ruyijs) · 🟢 窗口内 · 77.7 分

> This is a lightweight, headless browser purpose-built for AI agents (such as Codex or Claude Code) to perform browser automation tasks; it is designed to navigate through various web protection systems, login processes, and reverse-engineering scenarios

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1201 | +650 | +551 | 335 | 4 | C++ | AGPL-3.0 | 10-28（12 天前） | 今天 |

- **近 14 天每天新增**：`▆▃▄▃▄▃▃▅▅▅▂█▅·` 131 55 85 69 95 63 53 103 100 108 30 195 114 0
- **势头**：比前 7 天快 1.2 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`anti-bot` `automation` `firefox` `headless-browser` `javascript` `python` `spidermonkey` `web-scraping`
- **主页**：<https://cutetailbud.github.io/ff-ruyijs/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [benjitaylor/skills](https://github.com/benjitaylor/skills) · 🟡 在降温 · 71.8 分

> Skills for AI coding agents.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2929 | +1313 | +1616 | 199 | 0 | TypeScript | — | 10-26（15 天前） | 5 天前 |

- **近 14 天每天新增**：`···▃▇▇█▆▃▂▅▄▃·` 0 0 0 139 447 475 555 366 165 106 287 200 189 0
- **势头**：只有前 7 天的 81%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 6. [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) · 🟡 在降温 · 63.5 分

> Agent skill: describe your stack in a sentence, get an architecture diagram with official logos

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2217 | +572 | +1645 | 110 | 1 | TypeScript | MIT | 11-01（9 天前） | 1 天前 |

- **近 14 天每天新增**：`····█▇▄▂▂▂▂▂▂·` 0 0 0 0 722 593 330 145 96 110 87 77 57 0
- **势头**：只有前 7 天的 35%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `architecture-diagram` `claude-code` `claude-skills` `codex` `diagram` `system-architecture` `tech-stack`
- **主页**：<stacks.caru.moe>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 7. [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) · 🟡 在降温 · 63 分

> UEFI pre-driver NVIDIA GPU unlocker for Windows Linux Hackintosh and all EFI-bootable system (Rust): SEC2 scrubber -> FWSEC/WPR2 -> signed Booter -> V67 four-write payload, read-back verified. Verified on most RTX 20 30 40 Series.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2209 | +546 | +1600 | 201 | 22 | Rust | GPL-2.0 | 10-26（15 天前） | 今天 |

- **近 14 天每天新增**：`▁▂▄██▆▄▃▃▃▂▂▂·` 30 34 168 448 418 307 195 113 101 114 80 62 76 0
- **势头**：只有前 7 天的 34%，在减速
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50272846)）
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) · 🟡 在降温 · 62.5 分

> 🤖 Open-source, local-first alternative to Grok Bot, OpenAI dots and Claude Duet. Your own AI bots on any model: GPT, Claude, Gemini, Grok, DeepSeek, Kimi, GLM and 70+ more through one Modelflare key. Reach them in the app, WeChat or Feishu; they remember you, work in the background, run commands and use your computer. Pay per use.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2847 | +517 | +2330 | 46 | 1 | Python | MIT | 10-27（13 天前） | 今天 |

- **近 14 天每天新增**：`···▁▇█▅▄▁▁▁▁▂·` 0 0 0 1 862 958 509 355 20 16 11 4 111 0
- **势头**：只有前 7 天的 22%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `ai-assistant` `chatbot` `claude` `computer-use` `deepseek` `desktop-app` `dsh` `electron` `feishu` `gemini` `gpt` `grok` `llm` `local-first` `modelflare` `multi-model` `openai-compatible` `personal-ai-agent` `wechat`
- **主页**：<https://anymodel.bot/>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) · 🟡 在降温 · 61.5 分

> Evidence-first genealogy skill for AI agents (Codex, Claude Code): church books, civil, military, deportation and repression records across the former USSR. Replies in your language.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2282 | +470 | +736 | 229 | 1 | Python | MIT | 10-25（15 天前） | 今天 |

- **近 14 天每天新增**：`▄▃▃▂▂▃█▄▃▃▃▂▃·` 113 88 71 61 54 64 285 105 82 81 79 59 64 0
- **势头**：只有前 7 天的 64%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `archives` `claude-code` `codex` `family-history` `familysearch` `genealogy` `ussr`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) · 🟡 在降温 · 58.3 分

> A community-built phone app for Clean Your TV: clean up an Android TV from your phone. No laptop, no coding agent, nothing uninstalled.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1898 | +341 | +644 | 172 | 7487 | Kotlin | MIT | 10-21（19 天前） | 6 天前 |

- **近 14 天每天新增**：`█▆▆▇▇▇▆▅▅▅▄▄▄·` 114 88 79 95 92 101 75 66 73 60 42 54 46 0
- **势头**：只有前 7 天的 53%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adb` `android-tv` `debloat` `fire-tv` `google-tv` `launcher`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [janestreet/agent_skills](https://github.com/janestreet/agent_skills) — 一天进了一半以上的 star，但 HN 上没火过
- [DIYgod/pinky](https://github.com/DIYgod/pinky) — 一天进了一半以上的 star，但 HN 上没火过
- [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 300 | 50 | [Show HN: Every satellite that passed over any place this week, and its photos](https://www.watched.earth) | [HN](https://news.ycombinator.com/item?id=50428907) |
| 287 | 69 | [Show HN: Coldframe, a honeypot that poses as a supermarket fridge controller](https://github.com/hedgerow-dev/coldframe) | [HN](https://news.ycombinator.com/item?id=50406292) |
| 286 | 30 | [Show HN: A decent text-to-image model trained for ~$20K (Apache 2.0 Weights)](https://www.linum.ai/field-notes/pjit-21k) | [HN](https://news.ycombinator.com/item?id=50368208) |
| 256 | 41 | [Show HN: After a decade of reversing, I got co-op working in DOS Wing Commander](https://fireflyk64.github.io/wcmulti/) | [HN](https://news.ycombinator.com/item?id=50369895) |
| 217 | 43 | [Show HN: Vegetable Gardening for Engineers](https://jrcpl.us/contrib/2020/gardening-for-engineers/) | [HN](https://news.ycombinator.com/item?id=50362963) |
| 173 | 30 | [Show HN: Firenook – Firebase emulators in Rust: 40× faster writes, 10× less RAM](https://firenook.dev/) | [HN](https://news.ycombinator.com/item?id=50378643) |
| 127 | 69 | [Show HN: Uncracked City, detective game where you question LLM suspects that lie](https://uncracked.city) | [HN](https://news.ycombinator.com/item?id=50358352) |
| 122 | 29 | [Show HN: Flide: Make Jev-like decision models up to 9.5x faster](https://github.com/OmniJev/Flide) | [HN](https://news.ycombinator.com/item?id=50421155) |
| 121 | 85 | [Show HN: I built a tool that prices a pre-built PC part by part](https://pcdealcheck.com/) | [HN](https://news.ycombinator.com/item?id=50366929) |
| 107 | 37 | [Show HN: Kairos – Open-source risk and fraud decisioning platform](https://github.com/finic-ai/kairos) | [HN](https://news.ycombinator.com/item?id=50358314) |
| 100 | 38 | [Show HN: DBDelve – Open-Source DB Client Made with Rust and GPUI](https://news.ycombinator.com/item?id=50427934) | [HN](https://news.ycombinator.com/item?id=50427934) |
| 95 | 34 | [Show HN: Stroq – a local audit of what your coding agent did and why](https://github.com/AGGIB/Stroq) | [HN](https://news.ycombinator.com/item?id=50380704) |
| 92 | 36 | [Show HN: MeowDisplay Is iPhone Mirroring, but in Reverse](https://meowdisplay.app/) | [HN](https://news.ycombinator.com/item?id=50429636) |
| 88 | 48 | [Show HN: Waymark – A workflow engine that compiles jobs instead of replaying](https://github.com/piercefreeman/waymark) | [HN](https://news.ycombinator.com/item?id=50379221) |
| 87 | 29 | [Show HN: Someone Was Here – Find out who used your Mac while you were away](https://someonewashere.app/) | [HN](https://news.ycombinator.com/item?id=50429812) |
| 83 | 24 | [Show HN: STE80 Humanizer – de-AI text by writing 80% of the way to ASD-STE100](https://github.com/Dodaios/ste80-humanizer) | [HN](https://news.ycombinator.com/item?id=50429144) |
| 83 | 14 | [Show HN: We compressed a 31B video+audio diffusion model to 14B, 6 steps, INT8](https://github.com/Video-Rebirth/hyperflow-h3-flash) | [HN](https://news.ycombinator.com/item?id=50405263) |
| 71 | 26 | [Show HN: HackerChurn – which SaaS tools HN wants to cancel](https://hissingkitty.com/hacker-churn) | [HN](https://news.ycombinator.com/item?id=50353386) |
| 64 | 10 | [Show HN: Spindle – a full-featured, type-safe web framework for OCaml 5](https://github.com/hyphatech/spindle) | [HN](https://news.ycombinator.com/item?id=50377613) |
| 62 | 37 | [Show HN: Tmux-restore saves tmux windows and agent sessions across reboots](https://github.com/andrewboldi/tmux-restore) | [HN](https://news.ycombinator.com/item?id=50355009) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 164 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 121707★ |
| 15 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 5542★ |
| 185 | [VibeVoice Technical Report](https://huggingface.co/papers/2508.19205) | VibeVoice synthesizes long-form multi-speaker speech using next-token diffusion and a highly efficient continuous speech tokenizer, achievin… | [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice) 56902★ |
| 64 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 47435★ |
| 67 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 23293★ |
| 64 | [SplatAnything: Gaussian Spacing Normalization for Feed-forward 3DGS across Arbitrary Scenes](https://huggingface.co/papers/2611.08264) | SplatAnything applies Gaussian Spacing Normalization to canonicalize scene-level Gaussian spacing, yielding more consistent supervision and… | 💡 [zju3dv/SplatAnything](https://github.com/zju3dv/SplatAnything) 88★ |
| 111 | [FreeToken: Efficient Edge-Native MoE Serving with Bandwidth-Adaptive Execution](https://huggingface.co/papers/2608.16157) | FreeToken is an edge-native Mixture-of-Experts serving system that dynamically maps computation and model state onto heterogeneous local har… | [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken) 16948★ |
| 103 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 31045★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 86 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 93051★ |
| 8 | [Persistent Recursive Worlds Enable Autonomous Software Evolution](https://huggingface.co/papers/2608.10450) | Genesis organizes long-horizon software development around a persistent project rather than persistent agents, enabling multi-day compiler c… | 💡 [EMI-Group/genesis](https://github.com/EMI-Group/genesis) 667★ |
| 39 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 35686★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 35687★ |
| 30 | [Next-Concept Modeling: Fast, Parallel Coarse-to-Fine Text Generation](https://huggingface.co/papers/2610.14162) | Next-Concept Modeling uses hierarchical discrete codes and parallel level-wise generation to accelerate diffusion language models while impr… | [HazyResearch/ncm](https://github.com/HazyResearch/ncm) 1741★ |
| 75 | [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://huggingface.co/papers/2504.19413) | Mem0, a memory-centric architecture with graph-based memory, enhances long-term conversational coherence in LLMs by efficiently extracting,… | [mem0ai/mem0](https://github.com/mem0ai/mem0) 68717★ |
| 34 | [HairDeck: Animation-Ready Stylized Hair Cards from a Single Image](https://huggingface.co/papers/2610.40599) | HairDeck generates stylized hair cards and spring-bone animations as unordered token sets using a diffusion transformer, improving accuracy… | [hyz317/HairDeck](https://github.com/hyz317/HairDeck) 1044★ |
| 156 | [ARIS: Autonomous Research via Adversarial Multi-Agent Collaboration](https://huggingface.co/papers/2605.03042) | ARIS is an open-source research harness that uses cross-model adversarial collaboration to ensure reliable long-term research outcomes throu… | [wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) 18936★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 83381★ |
| 54 | [OmniEdu: Open Foundation Models for Learning and Teaching](https://huggingface.co/papers/2609.23088) | OmniEdu is a family of instruction-tuned educational foundation models that improve K-12 problem solving, curriculum understanding, and tuto… | 💡 [haolpku/Omni-Edu](https://github.com/haolpku/Omni-Edu) 836★ |
| 46 | [WeVisOne-VL: Unified Visual Perception from Objects to Pixels](https://huggingface.co/papers/2610.31329) | WeVisOne-VL unifies object-level and pixel-level visual perception via structured token prediction, supporting detection, localization, coun… | [Tencent/WeVisOne-VL](https://github.com/Tencent/WeVisOne-VL) 1111★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 33 | [gemma 4 ara heretic](https://huggingface.co/mradermacher/gemma-4-31B-it-ARA-heretic-GGUF) | — | 135 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 83 | 9 | [Horrible public key tricks](https://maurycyz.com/projects/badcert/) | `cryptography` | [讨论](https://lobste.rs/s/txkq8s/horrible_public_key_tricks) |
| 90 | 16 | [How Much Energy Does Building Distro Packages Use](https://www.wezm.net/v2/posts/2026/distro-energy-use/) | `linux` | [讨论](https://lobste.rs/s/ezjewj/how_much_energy_does_building_distro) |
| 47 | 8 | [Microsoft are rejecting your mail](https://www.mythic-beasts.com/blog/2026/11/09/microsoft-are-rejecting-your-mail/) | `email` | [讨论](https://lobste.rs/s/ynik5s/microsoft_are_rejecting_your_mail) |
| 42 | 22 | [Let’s Talk About Why all This OT Stuff is Connected](https://tisiphone.net/2026/11/08/lets-talk-about-why-all-this-ot-stuff-is-connected/) | `security` | [讨论](https://lobste.rs/s/jxigk6/let_s_talk_about_why_all_this_ot_stuff_is) |
| 92 | 26 | [Terminal2Shell: Critical flaw grants instant shell access on every major OS](https://terminal2shell.com/) | `satire` `security` | [讨论](https://lobste.rs/s/vghqe8/terminal2shell_critical_flaw_grants) |
| 81 | 27 | [unlocking any car from X brand in most of the world](https://shubs.io/unlocking-any-car-from-x-brand-in-most-of-the-world/) | `reversing` `security` | [讨论](https://lobste.rs/s/kbrpx3/unlocking_any_car_from_x_brand_most_world) |
| 19 | 6 | [What's new in Node.js 27](https://nodejsdesignpatterns.com/blog/whats-new-in-nodejs-27/) | `javascript` `nodejs` | [讨论](https://lobste.rs/s/vtjjbc/what_s_new_node_js_27) |
| 18 | 2 | [A C++ Quicksort Faster Than std::sort](https://tiki.li/blog/about_blqsort) | `c` `c++` `performance` | [讨论](https://lobste.rs/s/qi2lni/c_quicksort_faster_than_std_sort) |
| 14 | 6 | [I was wrong about dark mode](https://dbushell.com/2026/11/09/dark-mode/) | `css` `design` `web` | [讨论](https://lobste.rs/s/iqhxz6/i_was_wrong_about_dark_mode) |
| 42 | 4 | [Sure mate, buy me a bloody coffee](https://peateasea.de/sure-mate-buy-me-a-bloody-coffee/) | `culture` | [讨论](https://lobste.rs/s/eeclwg/sure_mate_buy_me_bloody_coffee) |
| 8 | 2 | [Blunt Banhammer Blocks Basic Bots Ballistically](https://shkspr.mobi/blog/2026/11/blunt-banhammer-blocks-basic-bots-ballistically/) | `web` | [讨论](https://lobste.rs/s/bubqox/blunt_banhammer_blocks_basic_bots) |
| 5 | 0 | [The race to secure record-like information for domains](https://alexsci.com/blog/the-race-to-secure-record-like-information-for-domains/) | `networking` `security` | [讨论](https://lobste.rs/s/vqtg9b/race_secure_record_like_information_for) |
| 20 | 23 | [What are you doing this week?](https://lobste.rs/s/tt42jc) | `ask` `programming` | [讨论](https://lobste.rs/s/tt42jc/what_are_you_doing_this_week) |
| 3 | 2 | [Two apps one process](https://andersmurphy.com/2026/11/09/two-apps-one-process.html) | `web` | [讨论](https://lobste.rs/s/sifkms/two_apps_one_process) |
| 59 | 20 | [Herb Sutter: When a language’s creator and its owners strongly disagree: C++26 post-DIS, historical…](https://isocpp.org/files/papers/P4454R0.pdf) | `c++` `pdf` | [讨论](https://lobste.rs/s/vlagyq/herb_sutter_when_language_s_creator_its) |
| 24 | 2 | [Slightly better interpolating spline](https://gasiulis.name/new-spline/) | `graphics` | [讨论](https://lobste.rs/s/t5bmg5/slightly_better_interpolating_spline) |
| 6 | 5 | [Playing classical music on a classic PC with GentleOS](https://www.youtube.com/watch?v=Vp16LLOvegw) | `c` `osdev` `retrocomputing` `video` | [讨论](https://lobste.rs/s/xf23r4/playing_classical_music_on_classic_pc) |
| 4 | 0 | [You should try Gleam](https://nchagnet.eu/blog/you-should-try-gleam) | `gleam` | [讨论](https://lobste.rs/s/4yqgpu/you_should_try_gleam) |
| 17 | 2 | [What is malloc doing, anyway?](https://benmandrew.com/articles/what-is-malloc-doing-anyway) | `c` `unix` | [讨论](https://lobste.rs/s/l75lxf/what_is_malloc_doing_anyway) |
| 6 | 2 | [PyPI's redesigned project pages with clearer security signals are now live](https://blog.pypi.org/posts/2026-11-06-ui-updates-complete/) | `python` `security` | [讨论](https://lobste.rs/s/s1tppi/pypi_s_redesigned_project_pages_with) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 64 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 47 | 32 | 68% | — |
| 🔴 先核对 | 25 | 13 | 52% | — |
| 🟡 在降温 | 5 | 0 | 0% | — |
| 🔵 已被发现 | 3 | 1 | 33% | — |
| 🟢 窗口内 | 15 | 8 | 53% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [KillaBoi/StealMyBitcoin-PoC](https://github.com/KillaBoi/StealMyBitcoin-PoC) | 2026-10-27 | 🚀 爆发 | 865 | 1045 | 182 | 没起来 |
| [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | 2026-10-27 | 🔴 先核对 | 821 | 1901 | 0 | ✅ 起来了 |
| [enesozturk/dimensional-drawing](https://github.com/enesozturk/dimensional-drawing) | 2026-10-27 | 🚀 爆发 | 1043 | 2015 | 0 | 没起来 |
| [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | 2026-10-27 | 🟢 窗口内 | 756 | 2106 | 4 | ✅ 起来了 |
| [ludovic111/horizon](https://github.com/ludovic111/horizon) | 2026-10-27 | 🟢 窗口内 | 2534 | 8412 | 2 | ✅ 起来了 |
| [t3dotgg/tstack](https://github.com/t3dotgg/tstack) | 2026-10-27 | 🔴 先核对 | 1647 | 3401 | 0 | ✅ 起来了 |

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
