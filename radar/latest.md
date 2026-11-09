# early-radar 选题雷达 · 2026-11-09

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 101 个，细查前 20 个 · 比上次 = 和 2026-11-08 那次比 · 生成于 2026-11-09 05:49 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 2 个 · Show HN ✅ 23 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 6 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 4 个 · 🟡 在降温 12 个 · 🔵 已被发现 0 个 · 💤 不活跃 1 个 · 🔴 先核对 3 个
- **今天新出现 3 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [storytold/craft-anything](https://github.com/storytold/craft-anything) 平均每天 +2685，见 [爆发](#爆发)
- **复盘**：🚀 爆发 32/45 · 🔴 先核对 11/23 · 🟡 在降温 0/5 · 🔵 已被发现 1/3 · 🟢 窗口内 6/13（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [sarpstar/cinecode](https://github.com/sarpstar/cinecode) — Films made with code. Short films, long YouTube videos, ads,…（近 7 天 +1662，刚发布一周内）
  - [benjitaylor/skills](https://github.com/benjitaylor/skills) — Skills for AI coding agents.（近 7 天 +1660，比前 7 天快 1.6 倍，在加速）
  - [voyager-so/vork](https://github.com/voyager-so/vork) — Headless 3D and VFX engine for agents. Research preview.（近 7 天 +1174，刚发布一周内）
- **趋势信号**：带 `ai-agents` topic 的新仓库这批里有 26 个（star 合计 24518），代表：[reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[reason-machines/reason-network](https://github.com/reason-machines/reason-network)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：4 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Subvocal – Talk to your computer without making noise](https://news.ycombinator.com/item?id=50340088) — 844 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| ✅ [storytold/craft-anything](https://github.com/storytold/craft-anything) | 23155 | 2685 | +2035 | 8.6 | [6](https://news.ycombinator.com/item?id=50377361) | craft anything · storytold craft anything · artcraft craft anything | Craft Anything: understand how any software works, and craft… |
| [deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) | 21359 | 2415 | +444 | 8.8 | [11](https://news.ycombinator.com/item?id=50316116) | dsh superagent prototype · deepseek-ai dsh superagent prototype · deepseek dsh superagent prototype | Towards a More Autonomous Agent System |
| 🆕 [anefzaoui/misterdownloadmanager](https://github.com/anefzaoui/misterdownloadmanager) | 2161 | 193 | +1737 | 11.2 | — | misterdownloadmanager · anefzaoui misterdownloadmanager · ahmed misterdownloadmanager | misterdownloadmanager: The ultimate open-source, clean-room… |
| [Minireel/HGhub](https://github.com/Minireel/HGhub) | 3888 | 687 | +1422 | 5.7 | — | hghub · minireel hghub | YellowFruit third-party client |
| [NotRexed/Hookshot](https://github.com/NotRexed/Hookshot) | 3358 | 900 | +1300 | 3.7 | [2](https://news.ycombinator.com/item?id=50410236) | hookshot · notrexed hookshot | A Native Recompilation Of The Legend Of Zelda: Ocarina Of Ti… |
| [heydamir/unslop](https://github.com/heydamir/unslop) | 12149 | 1147 | +688 | 10.6 | — | unslop · heydamir unslop · damir unslop | A Claude skill that turns vibecoded, AI-looking UI into a de… |
| [zortos293/Lichii](https://github.com/zortos293/Lichii) | 7016 | 811 | +1089 | 8.6 | — | lichii · zortos293 lichii · zortos lichii | VERY experimental Nintendo Switch 2 emulator |
| [JuneYaooo/rea-video](https://github.com/JuneYaooo/rea-video) | 4766 | 451 | +998 | 10.6 | [4](https://news.ycombinator.com/item?id=50368605) | rea video · juneyaooo rea video | Reverse-engineer any video, shot by shot: filmed, AI-generat… |
| 🆕 [tangerineturtle1/NX2navi](https://github.com/tangerineturtle1/NX2navi) | 1511 | 828 | — | 1.8 | — | nx2navi · tangerineturtle1 nx2navi |  |
| 🆕 [jhaizhou-ops/S2Arm](https://github.com/jhaizhou-ops/S2Arm) | 827 | 827 | — | 1 | — | s2arm · jhaizhou-ops s2arm | Run your own Switch games natively on iPhone, iPad and Mac:… |
| [wangzan101/Mika](https://github.com/wangzan101/Mika) | 7788 | 732 | +145 | 10.6 | — | mika · wangzan101 mika · wangzan mika | An on-device AI agent for Android that operates apps and the… |
| [worldonlyu/Google_AI_Pro_2Year_ZeroCost_Auto](https://github.com/worldonlyu/Google_AI_Pro_2Year_ZeroCost_Auto) | 3287 | 711 | +193 | 4.6 | — | google ai pro 2year zerocost auto · worldonlyu google ai pro 2year zerocost auto | Google_AI_Pro_2Year_ZeroCost_Auto |
| [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop) | 4164 | 705 | +171 | 5.9 | — | agent autoloop · kkkkhazix agent autoloop · khazix agent autoloop | 让你的命令行 Agent 在后台自己接活、自己跟进到底；平时不烦你，遇到拿不准的事才发卡片找你拍板。 |
| [sarpstar/cinecode](https://github.com/sarpstar/cinecode) | 1662 | 286 | +666 | 5.8 | — | cinecode · sarpstar cinecode | Films made with code. Short films, long YouTube videos, ads,… |
| [JenkinWoo/sheeridVerify](https://github.com/JenkinWoo/sheeridVerify) | 1884 | 661 | +137 | 2.8 | — | sheeridverify · jenkinwoo sheeridverify |  |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 89 | 🟢 窗口内 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode) | Python | 1662 | +666 | +1662 | +0 | `········▅▂▂██·` | 5 | — | — |
| 2 | 89 | 🟢 窗口内 | [benjitaylor/skills](https://github.com/benjitaylor/skills) | TypeScript | 2722 | +197 | +1660 | +1063 | `····▃▇▇█▆▃▂▅▃·` | 13 | — | — |
| 3 | 84.8 | 🟢 窗口内 | [voyager-so/vork](https://github.com/voyager-so/vork) | Rust | 1174 | +239 | +1174 | +0 | `··········█▇▄·` | 3 | [8](https://news.ycombinator.com/item?id=50396650) | — |
| 4 | 77.2 | 🆕 🟢 窗口内 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki) | JavaScript | 622 | +91 | +622 | +0 | `·········█▄▃▃·` | 3 | — | — |
| 5 | 68.2 | 🟡 在降温 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) | Python | 2741 | +6 | +916 | +1825 | `····▁▇█▅▄▁▁▁▁·` | 12 | — | — |
| 6 | 67.3 | 🟡 在降温 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | TypeScript | 2154 | +75 | +837 | +1317 | `·····█▇▄▂▂▂▂▂·` | 8 | — | — |
| 7 | 65.3 | 🟡 在降温 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 2212 | +62 | +685 | +706 | `▇▄▃▃▂▂▃█▄▃▃▃▂·` | 14 | — | — |
| 8 | 64.9 | 🟡 在降温 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 2127 | +58 | +659 | +1456 | `▂▁▂▄██▆▄▃▃▃▂▂·` | 13 | [2](https://news.ycombinator.com/item?id=50272846) | — |
| 9 | 61.3 | 🟡 在降温 | [ZiChuanLan/agent-purge](https://github.com/ZiChuanLan/agent-purge) | JavaScript | 1487 | +55 | +460 | +558 | `█▆▃▂▂▂▃▇▃▂▃▄▂·` | 14 | — | — |
| 10 | 54.9 | 🟡 在降温 | [daveebbelaar/bama](https://github.com/daveebbelaar/bama) | Swift | 1705 | +29 | +241 | +1343 | `██▆▅▅▇▄▃▂▂▂▂▂·` | 15 | — | — |
| 11 | 54.6 | 🟡 在降温 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2698 | +59 | +235 | +405 | `█▄▃▃▃▃▂▂▂▃▄▃▄·` | 18 | [3](https://news.ycombinator.com/item?id=50207695) | — |
| 12 | 51.5 | 🟡 在降温 | [lexifina/global-law](https://github.com/lexifina/global-law) | HTML | 1889 | +30 | +172 | +1717 | `··▂█▃▂▂▁▁▁▁▁▁·` | 11 | [1](https://news.ycombinator.com/item?id=50418651) | — |
| 13 | 50.4 | 🟡 在降温 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | Rust | 2075 | +22 | +154 | +1016 | `█▂▁▂▁▂▁▁▁▁▁▁▁·` | 20 | [4](https://news.ycombinator.com/item?id=50340534) | — |
| 14 | 49.6 | 🟡 在降温 | [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | TypeScript | 1886 | +23 | +142 | +879 | `█▅▅▂▂▃▂▁▁▂▁▁▁·` | 14 | — | — |
| 15 | 49.2 | 🟡 在降温 | [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) | TypeScript | 1999 | +11 | +136 | +1862 | `██▃▂▂▂▂▁▁▁▁▁▁·` | 18 | — | — |
| 16 | 46.1 | 🆕 🔴 先核对 | [anefzaoui/misterdownloadmanager](https://github.com/anefzaoui/misterdownloadmanager) | Rust | 2161 | +1737 | +2157 | +4 | `···▁··▁▁▂▁▁▁█·` | 11 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 44.5 | 🟡 在降温 | [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) | Python | 1767 | +10 | +85 | +444 | `▆▃▅█▆▃▂▂▂▂▂▂▁·` | 17 | — | — |
| 18 | 43.5 | 🔴 先核对 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Rust | 1403 | +116 | +1403 | +0 | `·······▁█▃▂▂▂·` | 7 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 41.7 | 🆕 🔴 先核对 | [DIYgod/pinky](https://github.com/DIYgod/pinky) | Go | 1045 | — | +1045 | +0 | `···········▃█·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 29.7 | 💤 不活跃 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 2534 | +45 | +376 | +409 | `▅▃▃▂▂▅██▅▃▃▃▃·` | 21 | — | — |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 622 | 30 | 45577 | [benjitaylor/skills](https://github.com/benjitaylor/skills)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) |
| `mcp` | 279 | 30 | 34088 | [reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) |
| `rust` | 237 | 30 | 35768 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[opengeos/RustGIS](https://github.com/opengeos/RustGIS)、[anefzaoui/misterdownloadmanager](https://github.com/anefzaoui/misterdownloadmanager) |
| `local-first` | 79 | 30 | 14217 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot)、[yjid/kensaku](https://github.com/yjid/kensaku)、[s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `ai-agents` | 26 | 24518 | [reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[reason-machines/reason-network](https://github.com/reason-machines/reason-network) |
| `claude-code` | 20 | 26384 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) |
| `agent-skills` | 14 | 22278 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA) |
| `codex` | 14 | 18924 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) |
| `windows` | 12 | 9486 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[yjid/kensaku](https://github.com/yjid/kensaku)、[yzlin286-wq/Deepscient](https://github.com/yzlin286-wq/Deepscient) |
| `mcp-server` | 9 | 10904 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[reason-machines/reason-network](https://github.com/reason-machines/reason-network)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `macos` | 8 | 8433 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[Zfinix/eleven](https://github.com/Zfinix/eleven) |
| `claude-skills` | 7 | 12671 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `self-hosted` | 7 | 6797 | [marclou/mailcheap](https://github.com/marclou/mailcheap)、[rociiu/talorys](https://github.com/rociiu/talorys)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) |
| `tauri` | 7 | 4906 | [yjid/kensaku](https://github.com/yjid/kensaku)、[oinkvm/oink](https://github.com/oinkvm/oink)、[torrentplayer/torrentplayer](https://github.com/torrentplayer/torrentplayer) |
| `typescript` | 7 | 3657 | [rociiu/talorys](https://github.com/rociiu/talorys)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[SouravBeraAkaSpeed/xiryn](https://github.com/SouravBeraAkaSpeed/xiryn) |
| `llm` | 6 | 5864 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot)、[heqiangdiao-wq/AI-Cross-Border-Ecommerce-Agent-Toolkit](https://github.com/heqiangdiao-wq/AI-Cross-Border-Ecommerce-Agent-Toolkit)、[sahenjp/RustXNG](https://github.com/sahenjp/RustXNG) |

**语言分布**：Rust 32 · Python 24 · TypeScript 18 · JavaScript 10 · Go 5 · HTML 5 · C++ 2 · Astro 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [sarpstar/cinecode](https://github.com/sarpstar/cinecode) · 🟢 窗口内 · 89 分

> Films made with code. Short films, long YouTube videos, ads, explainers and music videos: an AI coding agent writes the script, builds every frame in code, designs the sound and hands you an MP4.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1662 | +1662 | +0 | 298 | 7 | Python | MIT | 11-03（5 天前） | 5 天前 |

- **近 14 天每天新增**：`········▅▂▂██·` 0 0 0 0 0 0 0 0 316 101 76 588 581 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [benjitaylor/skills](https://github.com/benjitaylor/skills) · 🟢 窗口内 · 89 分

> Skills for AI coding agents.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2722 | +1660 | +1063 | 188 | 0 | TypeScript | — | 10-26（13 天前） | 4 天前 |

- **近 14 天每天新增**：`····▃▇▇█▆▃▂▅▃·` 0 0 0 0 139 448 476 556 366 165 106 286 181 0
- **势头**：比前 7 天快 1.6 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [voyager-so/vork](https://github.com/voyager-so/vork) · 🟢 窗口内 · 84.8 分

> Headless 3D and VFX engine for agents. Research preview.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1174 | +1174 | +0 | 89 | 6 | Rust | — | 11-05（3 天前） | 今天 |

- **近 14 天每天新增**：`··········█▇▄·` 0 0 0 0 0 0 0 0 0 0 516 449 209 0
- **势头**：刚发布一周内
- **HN**：发过 1 次，最高 8 分（[讨论](https://news.ycombinator.com/item?id=50396650)）
- **topics**：`3d` `ai-agents` `gpu` `metal` `ray-tracing` `rendering` `rust` `slang` `vfx` `vulkan`
- **主页**：<https://voyager.so/vork>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. 🆕 [JosssphZhou/poki](https://github.com/JosssphZhou/poki) · 🟢 窗口内 · 77.2 分

> Let AI agents operate a real iPhone. Local MCP server and agent, no jailbreak, no extra hardware.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 622 | +622 | +0 | 128 | 24 | JavaScript | AGPL-3.0 | 11-05（3 天前） | 今天 |

- **近 14 天每天新增**：`·········█▄▃▃·` 0 0 0 0 0 0 0 0 0 311 132 96 83 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `automation` `ios` `iphone` `mcp` `model-context-protocol`
- **主页**：<https://poki.bot>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) · 🟡 在降温 · 68.2 分

> 🤖 Open-source, local-first alternative to Grok Bot, OpenAI dots and Claude Duet. Your own AI bots on any model: GPT, Claude, Gemini, Grok, DeepSeek, Kimi, GLM and 70+ more through one Modelflare key. Reach them in the app, WeChat or Feishu; they remember you, work in the background, run commands and use your computer. Pay per use.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2741 | +916 | +1825 | 45 | 1 | Python | MIT | 10-27（12 天前） | 今天 |

- **近 14 天每天新增**：`····▁▇█▅▄▁▁▁▁·` 0 0 0 0 1 863 961 510 355 20 16 11 4 0
- **势头**：只有前 7 天的 50%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `ai-assistant` `chatbot` `claude` `computer-use` `deepseek` `desktop-app` `dsh` `electron` `feishu` `gemini` `gpt` `grok` `llm` `local-first` `modelflare` `multi-model` `openai-compatible` `personal-ai-agent` `wechat`
- **主页**：<https://anymodel.bot/>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 6. [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) · 🟡 在降温 · 67.3 分

> Agent skill: describe your stack in a sentence, get an architecture diagram with official logos

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2154 | +837 | +1317 | 108 | 2 | TypeScript | MIT | 11-01（8 天前） | 6 天前 |

- **近 14 天每天新增**：`·····█▇▄▂▂▂▂▂·` 0 0 0 0 0 723 594 330 145 96 110 87 69 0
- **势头**：只有前 7 天的 64%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `architecture-diagram` `claude-code` `claude-skills` `codex` `diagram` `system-architecture` `tech-stack`
- **主页**：<stacks.caru.moe>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 7. [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) · 🟡 在降温 · 65.3 分

> Evidence-first genealogy skill for AI agents (Codex, Claude Code): church books, civil, military, deportation and repression records across the former USSR. Replies in your language.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2212 | +685 | +706 | 224 | 8 | Python | MIT | 10-25（14 天前） | 1 天前 |

- **近 14 天每天新增**：`▇▄▃▃▂▂▃█▄▃▃▃▂·` 255 113 88 71 61 54 64 285 105 82 81 79 53 0
- **势头**：和前 7 天差不多
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `archives` `claude-code` `codex` `family-history` `familysearch` `genealogy` `ussr`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) · 🟡 在降温 · 64.9 分

> UEFI pre-driver NVIDIA GPU unlocker for Windows Linux Hackintosh and all EFI-bootable system (Rust): SEC2 scrubber -> FWSEC/WPR2 -> signed Booter -> V67 four-write payload, read-back verified. Verified on most RTX 20 30 40 Series.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2127 | +659 | +1456 | 191 | 24 | Rust | GPL-2.0 | 10-26（13 天前） | 今天 |

- **近 14 天每天新增**：`▂▁▂▄██▆▄▃▃▃▂▂·` 51 30 34 168 448 418 307 195 114 101 114 80 55 0
- **势头**：只有前 7 天的 45%，在减速
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50272846)）
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [ZiChuanLan/agent-purge](https://github.com/ZiChuanLan/agent-purge) · 🟡 在降温 · 61.3 分

> One persona, many coding agents. Replace or inject system prompts across codex, claude, opencode, grok, omp, hermes, pi, zcode - with a local web console.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1487 | +460 | +558 | 922 | 1 | JavaScript | MIT | 10-25（14 天前） | 今天 |

- **近 14 天每天新增**：`█▆▃▂▂▂▃▇▃▂▃▄▂·` 208 146 50 36 18 39 61 187 58 41 49 82 43 0
- **势头**：只有前 7 天的 82%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`claude-code` `codex` `coding-agent` `deepseek-harness` `harness` `magpie-plugin` `omp` `opencode` `pi` `system-prompt`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [daveebbelaar/bama](https://github.com/daveebbelaar/bama) · 🟡 在降温 · 54.9 分

> BAMA: Build Any Mac App. Agent skills to research, clone, design, build, optimize, and test native macOS apps with Swift and SwiftUI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1705 | +241 | +1343 | 208 | 1 | Swift | MIT | 10-24（15 天前） | 3 天前 |

- **近 14 天每天新增**：`██▆▅▅▇▄▃▂▂▂▂▂·` 265 251 183 152 154 227 111 64 51 36 34 27 29 0
- **势头**：只有前 7 天的 18%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-agents` `app-clone` `claude-code` `claude-code-plugin` `codex` `computer-use` `liquid-glass` `macos` `macos-app` `native-apps` `skills` `swift` `swiftdata` `swiftui`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [anefzaoui/misterdownloadmanager](https://github.com/anefzaoui/misterdownloadmanager) — 一天进了一半以上的 star，但 HN 上没火过
- [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) — 一天进了一半以上的 star，但 HN 上没火过
- [DIYgod/pinky](https://github.com/DIYgod/pinky) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 844 | 395 | [Show HN: Subvocal – Talk to your computer without making noise](https://news.ycombinator.com/item?id=50340088) | [HN](https://news.ycombinator.com/item?id=50340088) |
| 488 | 83 | [Show HN: HackerTV – HN's most-recommended Youtube videos as 24/7 TV channels](https://hackertv.org) | [HN](https://news.ycombinator.com/item?id=50346755) |
| 475 | 148 | [Show HN: Hacker Times, a New York Times-inspired version of Hacker News](https://hackertimes.ca/) | [HN](https://news.ycombinator.com/item?id=50346981) |
| 325 | 55 | [Show HN: Warsaw in voxels – An interactive 3D map of the city centre](https://p.migdal.pl/warsaw-vibe-voxel/) | [HN](https://news.ycombinator.com/item?id=50339221) |
| 284 | 29 | [Show HN: A decent text-to-image model trained for ~$20K (Apache 2.0 Weights)](https://www.linum.ai/field-notes/pjit-21k) | [HN](https://news.ycombinator.com/item?id=50368208) |
| 280 | 64 | [Show HN: Coldframe, a honeypot that poses as a supermarket fridge controller](https://github.com/hedgerow-dev/coldframe) | [HN](https://news.ycombinator.com/item?id=50406292) |
| 255 | 40 | [Show HN: After a decade of reversing, I got co-op working in DOS Wing Commander](https://fireflyk64.github.io/wcmulti/) | [HN](https://news.ycombinator.com/item?id=50369895) |
| 238 | 58 | [Show HN: I've updated my Linux System Call website and API](https://syscall.sh/) | [HN](https://news.ycombinator.com/item?id=50334704) |
| 185 | 39 | [Show HN: Vegetable Gardening for Engineers](https://jrcpl.us/contrib/2020/gardening-for-engineers/) | [HN](https://news.ycombinator.com/item?id=50362963) |
| 185 | 25 | [Show HN: HackerHack – HackerBooks but for Posts Posted on HN](https://news.ycombinator.com/) | [HN](https://news.ycombinator.com/item?id=50333877) |
| 171 | 30 | [Show HN: Firenook – Firebase emulators in Rust: 40× faster writes, 10× less RAM](https://firenook.dev/) | [HN](https://news.ycombinator.com/item?id=50378643) |
| 127 | 69 | [Show HN: Uncracked City, detective game where you question LLM suspects that lie](https://uncracked.city) | [HN](https://news.ycombinator.com/item?id=50358352) |
| 120 | 85 | [Show HN: I built a tool that prices a pre-built PC part by part](https://pcdealcheck.com/) | [HN](https://news.ycombinator.com/item?id=50366929) |
| 106 | 36 | [Show HN: Kairos – Open-source risk and fraud decisioning platform](https://github.com/finic-ai/kairos) | [HN](https://news.ycombinator.com/item?id=50358314) |
| 93 | 34 | [Show HN: Stroq – a local audit of what your coding agent did and why](https://github.com/AGGIB/Stroq) | [HN](https://news.ycombinator.com/item?id=50380704) |
| 85 | 46 | [Show HN: Waymark – A workflow engine that compiles jobs instead of replaying](https://github.com/piercefreeman/waymark) | [HN](https://news.ycombinator.com/item?id=50379221) |
| 79 | 14 | [Show HN: We compressed a 31B video+audio diffusion model to 14B, 6 steps, INT8](https://github.com/Video-Rebirth/hyperflow-h3-flash) | [HN](https://news.ycombinator.com/item?id=50405263) |
| 72 | 57 | [Show HN: I built a little browser game to practice Vim commands](https://hjkl.duy.run) | [HN](https://news.ycombinator.com/item?id=50347552) |
| 71 | 26 | [Show HN: HackerChurn – which SaaS tools HN wants to cancel](https://hissingkitty.com/hacker-churn) | [HN](https://news.ycombinator.com/item?id=50353386) |
| 62 | 37 | [Show HN: Tmux-restore saves tmux windows and agent sessions across reboots](https://github.com/andrewboldi/tmux-restore) | [HN](https://news.ycombinator.com/item?id=50355009) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 163 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 121414★ |
| 184 | [VibeVoice Technical Report](https://huggingface.co/papers/2508.19205) | VibeVoice synthesizes long-form multi-speaker speech using next-token diffusion and a highly efficient continuous speech tokenizer, achievin… | [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice) 56806★ |
| 14 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 5298★ |
| 64 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 47355★ |
| 67 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 23151★ |
| 111 | [FreeToken: Efficient Edge-Native MoE Serving with Bandwidth-Adaptive Execution](https://huggingface.co/papers/2608.16157) | FreeToken is an edge-native Mixture-of-Experts serving system that dynamically maps computation and model state onto heterogeneous local har… | [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken) 16858★ |
| 8 | [Persistent Recursive Worlds Enable Autonomous Software Evolution](https://huggingface.co/papers/2608.10450) | Genesis organizes long-horizon software development around a persistent project rather than persistent agents, enabling multi-day compiler c… | 💡 [EMI-Group/genesis](https://github.com/EMI-Group/genesis) 663★ |
| 103 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 30949★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 86 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 92969★ |
| 39 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 35614★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 35615★ |
| 33 | [HairDeck: Animation-Ready Stylized Hair Cards from a Single Image](https://huggingface.co/papers/2610.40599) | HairDeck generates stylized hair cards and spring-bone animations as unordered token sets using a diffusion transformer, improving accuracy… | 💡 [hyz317/HairDeck](https://github.com/hyz317/HairDeck) 951★ |
| 75 | [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://huggingface.co/papers/2504.19413) | Mem0, a memory-centric architecture with graph-based memory, enhances long-term conversational coherence in LLMs by efficiently extracting,… | [mem0ai/mem0](https://github.com/mem0ai/mem0) 68656★ |
| 48 | [Democratizing Robot-Use Agents: A Unified Harness with Open Models](https://huggingface.co/papers/2611.01560) | Uni-robot-agent enables open-weight robot-use agents to surpass proprietary models in zero-shot manipulation and suggests joint development… | 💡 [Open-RUA/uni-robot-agent](https://github.com/Open-RUA/uni-robot-agent) 290★ |
| 22 | [VisSearch-Bench: Evaluating Long Horizon Visual Search in Multimodal Agents](https://huggingface.co/papers/2611.04894) | VisSearch-Bench evaluates multimodal agents on visually intensive search tasks that require integrating visual context with external informa… | 💡 [antins-labs/VisSearch-Bench-v1](https://github.com/antins-labs/VisSearch-Bench-v1) 61★ |
| 156 | [ARIS: Autonomous Research via Adversarial Multi-Agent Collaboration](https://huggingface.co/papers/2605.03042) | ARIS is an open-source research harness that uses cross-model adversarial collaboration to ensure reliable long-term research outcomes throu… | [wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) 18882★ |
| 46 | [WeVisOne-VL: Unified Visual Perception from Objects to Pixels](https://huggingface.co/papers/2610.31329) | WeVisOne-VL unifies object-level and pixel-level visual perception via structured token prediction, supporting detection, localization, coun… | [Tencent/WeVisOne-VL](https://github.com/Tencent/WeVisOne-VL) 1077★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 83316★ |
| 29 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 9170★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 40 | [autotrust jev v1.1](https://huggingface.co/autotrust/AutoTrust-JEV-27B-v1.1) | text-classification | 1366 | 1 |
| 48 | [qwen3.8 dspine b16](https://huggingface.co/tencent/Qwen3.8-27B-DSpine-b16) | text-generation | 105 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 37 | 18 | [systemd loves Rust](https://amutable.com/blog/systemd-loves-rust) | `rust` `systemd` | [讨论](https://lobste.rs/s/62loik/systemd_loves_rust) |
| 40 | 7 | [A bit about email](https://maurycyz.com/misc/email/) | `email` | [讨论](https://lobste.rs/s/jnz4v5/bit_about_email) |
| 10 | 10 | [Unattended reboots with encrypted disks](https://jmmv.dev/2026/11/zkeys-intro.html) | `freebsd` `security` | [讨论](https://lobste.rs/s/urg4yu/unattended_reboots_with_encrypted_disks) |
| 16 | 5 | [Herb Sutter: When a language’s creator and its owners strongly disagree: C++26 post-DIS, historical…](https://isocpp.org/files/papers/P4454R0.pdf) | `c++` `pdf` | [讨论](https://lobste.rs/s/vlagyq/herb_sutter_when_language_s_creator_its) |
| 14 | 5 | [What can I realistically do with local AI on a Mac mini M5 Pro (48GB)?](https://lobste.rs/s/umsitb) | `ai` `ask` `mac` | [讨论](https://lobste.rs/s/umsitb/what_can_i_realistically_do_with_local_ai) |
| 10 | 0 | [Virtualized Redox: from Virtio-FS to Cloud Hypervisor, and beyond](https://www.redox-os.org/news/virtualized-redox/) | `osdev` | [讨论](https://lobste.rs/s/zozcwa/virtualized_redox_from_virtio_fs_cloud) |
| 5 | 0 | [Sem86: a full-system x86 emulator without hardcoded semantics](https://liblisa.nl/sem86/) | `virtualization` | [讨论](https://lobste.rs/s/a7byol/sem86_full_system_x86_emulator_without) |
| 21 | 1 | [NetBSD 11 desktop on a Raspberry Pi 4](https://neongd.com/articles/netbsd11-rpi4.gmi) | `netbsd` | [讨论](https://lobste.rs/s/rv1icj/netbsd_11_desktop_on_raspberry_pi_4) |
| 3 | 0 | [unlocking any car from X brand in most of the world](https://shubs.io/unlocking-any-car-from-x-brand-in-most-of-the-world/) | `reversing` `security` | [讨论](https://lobste.rs/s/kbrpx3/unlocking_any_car_from_x_brand_most_world) |
| 3 | 5 | [I Dislike Pull Requests (2020)](https://medium.com/@pia.fak.sunnanbo/i-hate-pull-requests-17836dd3cc38) | `practices` | [讨论](https://lobste.rs/s/za1r6h/i_dislike_pull_requests_2020) |
| 15 | 5 | [Nspawn 3.0: A Docker-compatible Engine API for systemd-nspawn containers](https://blog.nspawn.org/posts/nspawn-3-0-a-docker-compatible-engine-api-for-systemd-nspawn-containers/) | `release` | [讨论](https://lobste.rs/s/lh0qbr/nspawn_3_0_docker_compatible_engine_api) |
| 40 | 15 | [I’m not a fan of Deno’s security model (2024)](https://goldstein.lol/posts/deno-security/) | `security` | [讨论](https://lobste.rs/s/sh62d1/i_m_not_fan_deno_s_security_model_2024) |
| 22 | 31 | [Who wants to crowdsource LLM scans of articles submitted to Lobste.rs?](https://lobste.rs/s/jbdtim) | `meta` | [讨论](https://lobste.rs/s/jbdtim/who_wants_crowdsource_llm_scans_articles) |
| 3 | 0 | [Optimizing reference deletions in Git](https://nayak.im/posts/optimizing-reference-deletion/) | `c` `performance` `rust` `vcs` | [讨论](https://lobste.rs/s/ic1ora/optimizing_reference_deletions_git) |
| 8 | 3 | [Introducing Project Steadfast](https://noteflakes.com/articles/2026-11-07-introducing-project-steadfast) | `ruby` | [讨论](https://lobste.rs/s/5cavvx/introducing_project_steadfast) |
| 8 | 0 | [Playing with the STM32MP2](https://serd.es///2026/11/08/playing-with-stm32mp2.html) | `hardware` | [讨论](https://lobste.rs/s/cwmxea/playing_with_stm32mp2) |
| 94 | 89 | [How are you dealing with all the negative side effects of AI on the web?](https://lobste.rs/s/ipplhe) | `ask` `web` | [讨论](https://lobste.rs/s/ipplhe/how_are_you_dealing_with_all_negative_side) |
| 33 | 3 | [Dear Open Source Developers: It's OK not to embargo](https://opensourcesecurity.io/2026/10-embargo/) | `security` | [讨论](https://lobste.rs/s/lhovnm/dear_open_source_developers_it_s_ok_not) |
| 12 | 2 | [Hacking the T-Mobile Sidekick, 20 Years Too Late](https://x86.cx/blog/redanger) | `retrocomputing` `reversing` | [讨论](https://lobste.rs/s/f1nsnm/hacking_t_mobile_sidekick_20_years_too) |
| 5 | 1 | [Following breadcrumbs in code - What accidentally committed Ad-Hoc logs reveal about developer compr…](https://link.springer.com/article/10.1007/s10664-026-10988-z) | `pdf` `practices` | [讨论](https://lobste.rs/s/b6ebju/following_breadcrumbs_code_what) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 66 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 45 | 32 | 71% | — |
| 🔴 先核对 | 23 | 11 | 47% | — |
| 🟡 在降温 | 5 | 0 | 0% | — |
| 🔵 已被发现 | 3 | 1 | 33% | — |
| 🟢 窗口内 | 13 | 6 | 46% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | 2026-10-26 | 🚀 爆发 | 548 | 2212 | 0 | ✅ 起来了 |
| [Jakeschincariol/day-trader-skill](https://github.com/Jakeschincariol/day-trader-skill) | 2026-10-26 | 🚀 爆发 | 1699 | 6226 | 0 | ✅ 起来了 |
| [designfuchen/word-atlas](https://github.com/designfuchen/word-atlas) | 2026-10-26 | 🚀 爆发 | 816 | 4503 | 0 | ✅ 起来了 |
| [mizorewww/gdirect](https://github.com/mizorewww/gdirect) | 2026-10-26 | 🔴 先核对 | 601 | 797 | 0 | 没起来 |
| [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) | 2026-10-26 | 🔴 先核对 | 824 | 1768 | 0 | ✅ 起来了 |
| [rddmwmddr/android-ad-cleaner](https://github.com/rddmwmddr/android-ad-cleaner) | 2026-10-26 | 🚀 爆发 | 1019 | 7155 | 0 | ✅ 起来了 |

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
