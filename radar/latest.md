# early-radar 选题雷达 · 2026-10-27

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 107 个，细查前 20 个 · 比上次 = 和 2026-10-26 那次比 · 生成于 2026-10-27 04:38 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 0 个 · Show HN ✅ 23 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 20 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 8 个 · 🟡 在降温 8 个 · 🔵 已被发现 0 个 · 💤 不活跃 0 个 · 🔴 先核对 4 个
- **今天新出现 4 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) 平均每天 +4029，见 [爆发](#爆发)
- **复盘**：🚀 爆发 1/3 · 🔴 先核对 3/4 · 🟡 在降温 0/4 · 🔵 已被发现 0/2 · 🟢 窗口内 4/6（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [amosblomqvist/learnharness](https://github.com/amosblomqvist/learnharness) — Agent harness for learning difficult things.（近 7 天 +2441，比前 7 天快 143.6 倍，在加速）
  - [ludovic111/horizon](https://github.com/ludovic111/horizon) — Minecraft: Java Edition 26.3 rewritten from scratch in Rust,…（近 7 天 +2329，比前 7 天快 11.6 倍，在加速）
  - [yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) — 麦麦碳账本 · 基于麦当劳 MCP 的个人餐饮碳足迹估算与减排模拟器 / Personal dining carbon…（近 7 天 +1349，比前 7 天快 3.5 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 25 个（star 合计 26748），代表：[Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：1 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: SimCity, but with Permits](https://permit.petercai.com/) — 938 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) | 39692 | 4029 | +3825 | 9.9 | [6](https://news.ycombinator.com/item?id=50164485) | cleanyourtv · gathin23 cleanyourtv · gathin cleanyourtv | Debloat any Android or Google TV over Wi-Fi and get an Apple… |
| [Zagitta/gpu-unlock](https://github.com/Zagitta/gpu-unlock) | 10049 | 1100 | +2770 | 9.1 | [348](https://news.ycombinator.com/item?id=50219700) | gpu unlock · zagitta gpu unlock · simon gpu unlock | Unlock FP/BF16 instruction issue rate on Nvidia 3000's cards… |
| [deepseek-ai/DeepInfer](https://github.com/deepseek-ai/DeepInfer) | 23117 | 2127 | +561 | 10.9 | [2351](https://news.ycombinator.com/item?id=50163277) | deepinfer · deepseek-ai deepinfer · deepseek deepinfer | DeepInfer: High-performance, large-scale inference framework… |
| [seedds/nxnative](https://github.com/seedds/nxnative) | 6454 | 462 | +1965 | 14 | [1](https://news.ycombinator.com/item?id=50242845) | nxnative · seedds nxnative | Switch games running natively on iPhone, iPad and Mac: an NS… |
| [JustAResearcher/gpu-unlock-ada](https://github.com/JustAResearcher/gpu-unlock-ada) | 3931 | 1185 | +991 | 3.3 | [3](https://news.ycombinator.com/item?id=50223787) | gpu unlock ada · justaresearcher gpu unlock ada · tim gpu unlock ada | GPU tensor unlock source for RTX 4090 and experimental RTX 4… |
| [rddmwmddr/android-ad-cleaner](https://github.com/rddmwmddr/android-ad-cleaner) | 2187 | 739 | +1168 | 3 | — | android ad cleaner · rddmwmddr android ad cleaner | 关掉国产安卓手机系统里的广告、热搜、资讯推荐和营销推送。不 root，可还原，支持 AI 智能体一键执行。 |
| [designfuchen/word-atlas](https://github.com/designfuchen/word-atlas) | 1869 | 1015 | +1053 | 1.8 | — | word atlas · designfuchen word atlas · boxin word atlas | 词光 · Word Atlas — Illustrated IELTS vocabulary with 7,298 wo… |
| [pengchujin/aerial-tv](https://github.com/pengchujin/aerial-tv) | 6261 | 919 | +1028 | 6.8 | — | aerial tv · pengchujin aerial tv | 给国产电视的一块干净桌面：参照 tvOS 设计的开源 Android TV 桌面，没有广告，开机自动接管。A tvOS-… |
| 🆕 [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | 821 | 818 | — | 1 | — | digital human koubo · andyhuo520 digital human koubo | AI digital-human talking-head videos from one photo: Renoise… |
| [amosblomqvist/learnharness](https://github.com/amosblomqvist/learnharness) | 2458 | 237 | +708 | 10.4 | [10](https://news.ycombinator.com/item?id=50243281) | learnharness · amosblomqvist learnharness · eero learnharness | Agent harness for learning difficult things. |
| 🆕 [KillaBoi/StealMyBitcoin-PoC](https://github.com/KillaBoi/StealMyBitcoin-PoC) | 865 | 673 | — | 1.3 | [163](https://news.ycombinator.com/item?id=50237379) | stealmybitcoin poc · killaboi stealmybitcoin poc · jaydip stealmybitcoin poc | A public release of the Steal My Bitcoin challenge |
| [simbasjungles/free-my-tv](https://github.com/simbasjungles/free-my-tv) | 4888 | 662 | +241 | 7.4 | [1](https://news.ycombinator.com/item?id=50220596) | free my tv · simbasjungles free my tv · simba free my tv | A fast, ad-free home screen for Google TV, LG webOS and Sams… |
| [ly05010419/MacNativeGames](https://github.com/ly05010419/MacNativeGames) | 5830 | 622 | +303 | 9.4 | — | macnativegames · ly05010419 macnativegames · yong macnativegames | Play your own Tears of the Kingdom and Breath of the Wild na… |
| 🆕 [t3dotgg/tstack](https://github.com/t3dotgg/tstack) | 1647 | 552 | — | 3 | — | tstack · t3dotgg tstack · theo tstack | The agent skills I use every day. Works with Claude Code and… |
| 🆕 [enesozturk/dimensional-drawing](https://github.com/enesozturk/dimensional-drawing) | 1043 | 283 | +507 | 3.7 | — | dimensional drawing · enesozturk dimensional drawing · enes dimensional drawing |  |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 93.6 | 🟢 窗口内 | [amosblomqvist/learnharness](https://github.com/amosblomqvist/learnharness) | TypeScript | 2458 | +708 | +2441 | +17 | `··▁▁▁▁▁▁▁▃█▆▆·` | 10 | [10](https://news.ycombinator.com/item?id=50243281) | — |
| 2 | 93 | 🆕 🟢 窗口内 | [ludovic111/horizon](https://github.com/ludovic111/horizon) | Rust | 2534 | +391 | +2329 | +201 | `▁▁▂▁▁▁▁▁▁▂█▇▃·` | 23 | [2](https://news.ycombinator.com/item?id=50239035) | — |
| 3 | 86.5 | 🟢 窗口内 | [yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) | Python | 1932 | -10 | +1349 | +380 | `▁▂▂▂▁▂▂▂▂▃█▆··` | 14 | — | — |
| 4 | 85.4 | 🟢 窗口内 | [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) | Python | 1235 | +411 | +1235 | +0 | `··········▅█▅·` | 4 | — | — |
| 5 | 83.8 | 🟢 窗口内 | [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) | Python | 1653 | +54 | +1075 | +578 | `·▁▂▃▄▃▃▃▂▆█▅▂·` | 11 | — | — |
| 6 | 78.2 | 🟢 窗口内 | [torrentplayer/torrentplayer](https://github.com/torrentplayer/torrentplayer) | Rust | 674 | +71 | +674 | +0 | `·······██▄▄▄▃·` | 6 | — | — |
| 7 | 76.5 | 🆕 🟢 窗口内 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | Rust | 756 | +324 | +588 | +168 | `·····▁▄▁▁▁▃▅█·` | 7 | — | — |
| 8 | 74.9 | 🟢 窗口内 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) | Go | 2001 | +76 | +513 | +301 | `▁▁▂▂▃▆███▆▄▄▅·` | 18 | — | — |
| 9 | 68.6 | 🟡 在降温 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) | Python | 2940 | +130 | +948 | +1992 | `·▂▄▄▄█▅▂▃▄▂▃▂·` | 11 | — | — |
| 10 | 65.9 | 🟡 在降温 | [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) | Python | 1450 | +66 | +724 | +726 | `··▃▅█▆▅▃▂█▅▆▃·` | 10 | [1](https://news.ycombinator.com/item?id=50177079) | — |
| 11 | 63.2 | 🟡 在降温 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 1745 | +61 | +557 | +1188 | `····█▆▃▃▃▂▂▂▂·` | 8 | — | — |
| 12 | 62 | 🟡 在降温 | [reason-machines/reason-network](https://github.com/reason-machines/reason-network) | Rust | 1268 | +26 | +492 | +775 | `··▄▆▅▃█▆▅▃▂▂▂·` | 10 | — | — |
| 13 | 59.9 | 🟡 在降温 | [ELY-Open-Source/ElyOffice](https://github.com/ELY-Open-Source/ElyOffice) | Rust | 1045 | +43 | +397 | +648 | `·····▇█▃▄▂▂▂▂·` | 7 | — | — |
| 14 | 56.7 | 🟡 在降温 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 1826 | +32 | +288 | +659 | `▃▂▂▁▁▁█▃▂▂▁▁▂·` | 14 | — | — |
| 15 | 56.7 | 🟡 在降温 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 2044 | +53 | +289 | +892 | `█▅▅▄▄▃▃▃▂▂▂▃▃·` | 16 | — | — |
| 16 | 52.8 | 🟡 在降温 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | Python | 2158 | +27 | +196 | +814 | `▄█▆▄▄▃▃▂▂▂▂▂▂·` | 21 | [10](https://news.ycombinator.com/item?id=50037852) | — |
| 17 | 45.8 | 🔴 先核对 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2068 | +112 | +2068 | +0 | `·······▁▁█▅▂▂·` | 5 | [3](https://news.ycombinator.com/item?id=50207695) | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 44.4 | 🆕 🔴 先核对 | [t3dotgg/tstack](https://github.com/t3dotgg/tstack) | Python | 1647 | — | +1647 | +0 | `·········▁▁▁█·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 40.3 | 🆕 🔴 先核对 | [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | TypeScript | 821 | — | +821 | +0 | `···········▂█·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 39.4 | 🔴 先核对 | [mizorewww/gdirect](https://github.com/mizorewww/gdirect) | Rust | 715 | +114 | +715 | +0 | `··········▁█▂·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 539 | 30 | 45629 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[amosblomqvist/learnharness](https://github.com/amosblomqvist/learnharness) |
| `mcp` | 272 | 30 | 33348 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) |
| `rust` | 190 | 30 | 27614 | [ludovic111/horizon](https://github.com/ludovic111/horizon)、[oxc-project/tsrs](https://github.com/oxc-project/tsrs)、[academa-labs/manimgx](https://github.com/academa-labs/manimgx) |
| `local-first` | 62 | 30 | 10327 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[chenxiachan/textfold](https://github.com/chenxiachan/textfold)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 25 | 26748 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) |
| `ai-agents` | 20 | 15405 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering) |
| `agent-skills` | 16 | 19282 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `codex` | 16 | 15011 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) |
| `llm` | 16 | 12712 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[Harvil1/codeAgent](https://github.com/Harvil1/codeAgent) |
| `claude-skills` | 11 | 12832 | [oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `mcp-server` | 11 | 9264 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `ai-agent` | 9 | 7957 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `macos` | 9 | 5777 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[kitlangton/scrawl](https://github.com/kitlangton/scrawl)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch) |
| `developer-tools` | 9 | 5765 | [jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai)、[hanzohanzhe/Grandet](https://github.com/hanzohanzhe/Grandet)、[kitlangton/scrawl](https://github.com/kitlangton/scrawl) |
| `python` | 6 | 7031 | [hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist)、[Sam-Hui-dot/mcd-budget-meal](https://github.com/Sam-Hui-dot/mcd-budget-meal)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) |
| `motion-graphics` | 6 | 4956 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[Tejashmakwana/motionmaxxing](https://github.com/Tejashmakwana/motionmaxxing)、[zhuyansen/awesome-claude-video-skills](https://github.com/zhuyansen/awesome-claude-video-skills) |

**语言分布**：Python 32 · Rust 30 · TypeScript 17 · JavaScript 12 · Go 4 · HTML 3 · Swift 2 · Astro 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [amosblomqvist/learnharness](https://github.com/amosblomqvist/learnharness) · 🟢 窗口内 · 93.6 分

> Agent harness for learning difficult things.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2458 | +2441 | +17 | 428 | 163 | TypeScript | AGPL-3.0 | 10-16（10 天前） | 1 天前 |

- **近 14 天每天新增**：`··▁▁▁▁▁▁▁▃█▆▆·` 0 0 1 3 4 6 3 2 7 289 853 647 643 0
- **势头**：比前 7 天快 143.6 倍，在加速
- **HN**：发过 1 次，最高 10 分（[讨论](https://news.ycombinator.com/item?id=50243281)）
- **主页**：<learnharness.ai>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. 🆕 [ludovic111/horizon](https://github.com/ludovic111/horizon) · 🟢 窗口内 · 93 分

> Minecraft: Java Edition 26.3 rewritten from scratch in Rust, checked against vanilla with 281 differential harnesses. Get it with the Horizon launcher.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2534 | +2329 | +201 | 173 | 438 | Rust | MIT | 10-03（23 天前） | 今天 |

- **近 14 天每天新增**：`▁▁▂▁▁▁▁▁▁▂█▇▃·` 3 47 78 29 16 17 11 36 38 79 969 874 333 0
- **势头**：比前 7 天快 11.6 倍，在加速
- **HN**：发过 2 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50239035)）
- **topics**：`differential-testing` `game-engine` `gamedev` `linux` `minecraft` `minecraft-java` `reimplementation` `rust` `voxel` `vulkan` `wgpu`
- **主页**：<https://playhorizon.dev>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) · 🟢 窗口内 · 86.5 分

> 麦麦碳账本 · 基于麦当劳 MCP 的个人餐饮碳足迹估算与减排模拟器 | Personal dining carbon footprint estimator powered by McDonald's MCP

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1932 | +1349 | +380 | 43 | 0 | Python | MIT | 10-12（14 天前） | 13 天前 |

- **近 14 天每天新增**：`▁▂▂▂▁▂▂▂▂▃█▆··` 4 67 63 46 33 89 78 91 116 128 572 442 0 0
- **势头**：比前 7 天快 3.5 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) · 🟢 窗口内 · 85.4 分

> Agent Skills that teach coding agents to write, review, and port idiomatic Rust, plus a tested clippy config. Works with Claude Code, Codex, Copilot, Cursor, and Gemini CLI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1235 | +1235 | +0 | 55 | 3 | Python | MIT | 10-23（4 天前） | 今天 |

- **近 14 天每天新增**：`··········▅█▅·` 0 0 0 0 0 0 0 0 0 0 304 583 348 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `claude-code` `claude-plugin` `claude-skills` `clippy` `code-review` `coding-agent` `cursor` `rust` `style-guide`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) · 🟢 窗口内 · 83.8 分

> 麦当劳 MCP 聚会/团餐组织助手 — 基于 Model Context Protocol 的派对预订与团餐规划 CLI/Skill

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1653 | +1075 | +578 | 58 | 2 | Python | MIT | 10-15（11 天前） | 2 天前 |

- **近 14 天每天新增**：`·▁▂▃▄▃▃▃▂▆█▅▂·` 0 15 53 96 166 115 133 114 75 256 380 199 51 0
- **势头**：比前 7 天快 1.9 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [torrentplayer/torrentplayer](https://github.com/torrentplayer/torrentplayer) · 🟢 窗口内 · 78.2 分

> Stream any torrent, video or audio, and skip to any moment in about a second. Free, open-source desktop app for Windows, macOS and Linux. No servers, no accounts, no telemetry.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 674 | +674 | +0 | 17 | 10 | Rust | Apache-2.0 | 10-20（6 天前） | 今天 |

- **近 14 天每天新增**：`·······██▄▄▄▃·` 0 0 0 0 0 0 0 183 189 78 91 69 64 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`audio-player` `bittorrent` `cross-platform` `desktop-app` `media-player` `p2p` `rust` `streaming` `svelte` `tauri` `torrent` `video-player`
- **主页**：<https://torrentstream.io>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. 🆕 [indexable-inc/blaze](https://github.com/indexable-inc/blaze) · 🟢 窗口内 · 76.5 分

> Incremental rust builds up to 92x faster than cargo/rustc

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 756 | +588 | +168 | 23 | 107 | Rust | Apache-2.0 | 10-19（7 天前） | 今天 |

- **近 14 天每天新增**：`·····▁▄▁▁▁▃▅█·` 0 0 0 0 0 17 151 14 5 4 104 157 304 0
- **势头**：比前 7 天快 3.5 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`cargo` `compiler` `cranelift` `developer-tools` `hot-reload` `incremental-compilation` `jit` `live-coding` `rust` `rust-analyzer`
- **主页**：<ix.dev/blaze>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) · 🟢 窗口内 · 74.9 分

> ARTEX · AI autonomous penetration testing system (multi-agent LLM, Go + Next.js) · AI 自主渗透测试系统 · 百度 agent+ 攻防挑战赛冠军

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2001 | +513 | +301 | 966 | 2 | Go | AGPL-3.0 | 10-08（18 天前） | 7 天前 |

- **近 14 天每天新增**：`▁▁▂▂▃▆███▆▄▄▅·` 2 5 10 19 45 92 128 122 128 90 56 47 70 0
- **势头**：比前 7 天快 1.7 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `ai-security` `artex` `autonomous-agents` `cybersecurity` `go` `hacking` `llm` `llm-agent` `mcp` `nextjs` `offensive-security` `penetration-testing` `pentest` `red-team` `security` `security-tools` `vulnerability` `vulnerability-scanners` `web-security`
- **主页**：<https://artex-demo.vercel.app/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 9. [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) · 🟡 在降温 · 68.6 分

> Ears for coding agents: let AI hear, review and make sound. CPU-only, open source.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2940 | +948 | +1992 | 180 | 14 | Python | MIT | 10-15（11 天前） | 4 天前 |

- **近 14 天每天新增**：`·▂▄▄▄█▅▂▃▄▂▃▂·` 0 112 309 285 263 680 343 73 202 245 145 164 119 0
- **势头**：只有前 7 天的 48%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `audio` `claude-code` `mcp` `sound-design`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) · 🟡 在降温 · 65.9 分

> Co-op Anything: point your AI agent at any single-player game and play it with friends (online and/or splitscreen!). MCP server and playbook to let you reverse engineer, fix, test, ship and share what it learns.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1450 | +724 | +726 | 187 | 145 | Python | MIT | 10-16（10 天前） | 今天 |

- **近 14 天每天新增**：`··▃▅█▆▅▃▂█▅▆▃·` 0 0 81 131 234 156 124 77 47 227 150 161 62 0
- **势头**：和前 7 天差不多
- **HN**：发过 1 次，最高 1 分（[讨论](https://news.ycombinator.com/item?id=50177079)）
- **主页**：<https://coopanything.app>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [xevrion/hatchzip](https://github.com/xevrion/hatchzip) — 一天进了一半以上的 star，但 HN 上没火过
- [t3dotgg/tstack](https://github.com/t3dotgg/tstack) — 一天进了一半以上的 star，但 HN 上没火过
- [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) — 一天进了一半以上的 star，但 HN 上没火过
- [mizorewww/gdirect](https://github.com/mizorewww/gdirect) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 938 | 425 | [Show HN: SimCity, but with Permits](https://permit.petercai.com/) | [HN](https://news.ycombinator.com/item?id=50170593) |
| 615 | 449 | [Show HN: Steal My Bitcoin](https://stealmybitcoin.com/) | [HN](https://news.ycombinator.com/item?id=50224916) |
| 389 | 75 | [Show HN: TitleArt – Make text like it's 1997](https://titleart.dvy.io/) | [HN](https://news.ycombinator.com/item?id=50238708) |
| 283 | 101 | [Show HN: A Truly Modular Keyboard](https://github.com/notaroomba/keybytes) | [HN](https://news.ycombinator.com/item?id=50228115) |
| 235 | 94 | [Show HN: OnKey – I'm a bad singer, so I built an app to show where I'm off-key](https://github.com/dsmurrell/onkey) | [HN](https://news.ycombinator.com/item?id=50195488) |
| 188 | 13 | [Show HN: VoidAccess – open-source dark web OSINT, from query to a graph](https://github.com/KatrielMoses/voidaccess) | [HN](https://news.ycombinator.com/item?id=50167286) |
| 177 | 48 | [Show HN: I put employees inside S&P 500 market-cap bubbles](https://bigwhalehunting.com/workforce/) | [HN](https://news.ycombinator.com/item?id=50232312) |
| 140 | 46 | [Show HN: Corgi, a helpful {agent, terminal} multiplexer](https://corgi.computer/) | [HN](https://news.ycombinator.com/item?id=50214373) |
| 132 | 31 | [Show HN: Hob - Open-source, on device alternative to Claude Cowork and ChatGPT](https://github.com/FrigadeHQ/hob) | [HN](https://news.ycombinator.com/item?id=50246238) |
| 126 | 37 | [Show HN: Uberblok – an interactive museum of ZFS internals](https://uberblok.storagebits.workers.dev/) | [HN](https://news.ycombinator.com/item?id=50180257) |
| 114 | 34 | [Show HN: Omnara – Open-source alternative to Claude Managed Agents](https://github.com/omnara-ai/omnara) | [HN](https://news.ycombinator.com/item?id=50183892) |
| 109 | 81 | [Show HN: Making a smart TV dumb and then smart](https://github.com/anubhavmalhotra/r2d2-tv) | [HN](https://news.ycombinator.com/item?id=50202865) |
| 105 | 31 | [Show HN: Sumi.css – CSS Framework](https://github.com/vladocar/Sumi.css) | [HN](https://news.ycombinator.com/item?id=50180039) |
| 81 | 22 | [Show HN: Impossible Machines: declaratively program the physical world](https://www.impossiblemachines.xyz) | [HN](https://news.ycombinator.com/item?id=50202746) |
| 80 | 46 | [Show HN: UI micro interactions prompts for AI](https://www.typeui.sh/micro-interactions) | [HN](https://news.ycombinator.com/item?id=50199290) |
| 77 | 37 | [Show HN: Swurf – Swipe through the real web](https://swurf.org/) | [HN](https://news.ycombinator.com/item?id=50205320) |
| 72 | 54 | [Show HN: Jev Cards, Can you beat a vision model at a picture quiz?](https://jevcards.com) | [HN](https://news.ycombinator.com/item?id=50167617) |
| 70 | 57 | [Show HN: We had AI write a wiki from 45k Enron emails, every fact cited](https://www.thisandthat.chat/enron/) | [HN](https://news.ycombinator.com/item?id=50207620) |
| 66 | 9 | [Show HN: Penmentor – Claude marks up your handwritten math like a teacher](https://github.com/AbdullahAlhariri/penmentor) | [HN](https://news.ycombinator.com/item?id=50167604) |
| 65 | 54 | [Show HN: ADRs for AI – Deliberation records for human–AI work, versioned in Git](https://adrs.systems) | [HN](https://news.ycombinator.com/item?id=50227041) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 123 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 20168★ |
| 154 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 116374★ |
| 30 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 7484★ |
| 62 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 43861★ |
| 104 | [MOSS-Image Technical Report](https://huggingface.co/papers/2610.23374) | MOSS-Image is an open diffusion transformer that combines high-fidelity synthesis with intent-aware prompt enhancement to generate text-rich… | [OpenMOSS/MOSS-Image](https://github.com/OpenMOSS/MOSS-Image) 2009★ |
| 48 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 34200★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 34200★ |
| 23 | [Prism: Dynamic Sparse Attention for Native 2K Joint Video-Audio Generation Model Training](https://huggingface.co/papers/2610.05416) | Prism accelerates native joint video-audio generation at 2K by using dynamic sparse attention guided by local visual variance and audio-visu… | [Tencent-Hunyuan/Prism](https://github.com/Tencent-Hunyuan/Prism) 1268★ |
| 121 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 2639★ |
| 100 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 28581★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 91914★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 17 | [Next-Concept Modeling: Fast, Parallel Coarse-to-Fine Text Generation](https://huggingface.co/papers/2610.14162) | Next-Concept Modeling uses hierarchical discrete codes and parallel level-wise generation to accelerate diffusion language models while impr… | [HazyResearch/ncm](https://github.com/HazyResearch/ncm) 1107★ |
| 81 | [StartLux-Decision: AutoThink Decision Models with Reinforcement Learning for Calibrated Deliberative…](https://huggingface.co/papers/2610.17309) | StartLux-Decision introduces efficient and adaptive decision models using single-pass prediction and confidence-guided reasoning, trained vi… | [StartLuxLabs/StartLux-Decision](https://github.com/StartLuxLabs/StartLux-Decision) 1582★ |
| 253 | [WeVisOne-VL: Unified Visual Perception from Objects to Pixels](https://huggingface.co/papers/2610.31329) | WeVisOne-VL unifies object-level and pixel-level visual perception via structured token prediction, supporting detection, localization, coun… | 💡 [Tencent/WeVisOne-VL](https://github.com/Tencent/WeVisOne-VL) 263★ |
| 180 | [SmolDocling: An ultra-compact vision-language model for end-to-end multi-modal document conversion](https://huggingface.co/papers/2503.11576) | SmolDocling is a compact vision-language model that performs end-to-end document conversion with robust performance across various document… | [docling-project/docling](https://github.com/docling-project/docling) 69627★ |
| 31 | [Internal Safety Collapse in Frontier Large Language Models](https://huggingface.co/papers/2603.23509) | Frontier large language models exhibit Internal Safety Collapse, where they generate harmful content under specific task conditions, reveali… | [wuyoscar/ISC-Bench](https://github.com/wuyoscar/ISC-Bench) 2367★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 82527★ |
| 206 | [YuE2: Unifying Symbolic and Audio Music Generation at Frontier Quality](https://huggingface.co/papers/2609.33757) | YuE2 unifies symbolic and audio music generation via symbolic planning, producing readable scores and full-song audio with state-of-the-art… | [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE) 12751★ |
| 75 | [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://huggingface.co/papers/2504.19413) | Mem0, a memory-centric architecture with graph-based memory, enhances long-term conversational coherence in LLMs by efficiently extracting,… | [mem0ai/mem0](https://github.com/mem0ai/mem0) 67863★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

_这次没有（新上榜 0 个）。_

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 11 | 6 | [Shitty Screenshare](http://shittyscreenshare.com) | `browsers` `web` | [讨论](https://lobste.rs/s/cxxcik/shitty_screenshare) |
| 66 | 17 | [Websites Should Be Printable](https://brennenputh.me/blog/printable-websites/) | `css` `web` | [讨论](https://lobste.rs/s/olnqh2/websites_should_be_printable) |
| 50 | 27 | [Why is it so expensive to send an email?](https://evancz.dev/why-is-it-so-expensive-to-send-an-email) | `email` | [讨论](https://lobste.rs/s/ryjnyi/why_is_it_so_expensive_send_email) |
| 53 | 2 | [CSS-Tricks has a new owner](https://css-tricks.com/css-tricks-has-a-new-owner/) | `web` | [讨论](https://lobste.rs/s/6ntoqr/css_tricks_has_new_owner) |
| 23 | 4 | [A faster way to compute signed 64-bit floor division by constants](https://www.benjoffe.com/fast-floordiv) | `c++` `performance` | [讨论](https://lobste.rs/s/o5to4p/faster_way_compute_signed_64_bit_floor) |
| 54 | 11 | [Gram 3.4.0 released](https://gram-editor.com/posts/release-3.4.0/) | `editors` `release` | [讨论](https://lobste.rs/s/p9obkt/gram_3_4_0_released) |
| 34 | 1 | [Oldest GUI application that still runs on Windows 11](https://blog.enlyth.com/posts/oldest-windows-gui-app-win-11/) | `historical` `windows` | [讨论](https://lobste.rs/s/rwubks/oldest_gui_application_still_runs_on) |
| 46 | 32 | [About the compromised eMudhra intermediate CAs](https://support.apple.com/en-us/149555) | `mac` `security` | [讨论](https://lobste.rs/s/xzp4m0/about_compromised_emudhra_intermediate) |
| 7 | 17 | [The passkey is worse](https://www.kcoleman.me/2026/10/22/hacked.html) | `security` `web` | [讨论](https://lobste.rs/s/ihmfsc/passkey_is_worse) |
| 25 | 6 | [Stalwart v1.0: The Fastest Mail Server on the Planet](https://stalw.art/blog/stalwart-1-0/) | `email` | [讨论](https://lobste.rs/s/c0yniy/stalwart_v1_0_fastest_mail_server_on) |
| 14 | 0 | [The Exponential Time Hypothesis Is False [pdf]](https://github.com/openai/math/blob/main/preprints/The-Exponential-Time-Hypothesis-is-False-October-25-2026/paper.pdf) | `math` `pdf` | [讨论](https://lobste.rs/s/pq6ju6/exponential_time_hypothesis_is_false_pdf) |
| 17 | 2 | [Pharo 14 Released](https://pharo.org/news/2026-10-26-Pharo14Release.html) | `release` | [讨论](https://lobste.rs/s/1h5kuj/pharo_14_released) |
| 53 | 8 | [Simple NetBSD webserver](https://bsandro.tech/posts/simple-netbsd-webserver/) | `netbsd` | [讨论](https://lobste.rs/s/hzrmwz/simple_netbsd_webserver) |
| 84 | 20 | [POSIX wordexp(3) is dangerous](https://yossarian.net/til/post/posix-wordexp-3-is-dangerous/) | `c` `security` | [讨论](https://lobste.rs/s/tbbiqb/posix_wordexp_3_is_dangerous) |
| 15 | 26 | [What are you doing this week?](https://lobste.rs/s/xxdda9) | `ask` `programming` | [讨论](https://lobste.rs/s/xxdda9/what_are_you_doing_this_week) |
| 7 | 0 | [Our Response To The eMudhra Key Disclosure Incident](https://go.dev/blog/emudhra-incident) | `go` | [讨论](https://lobste.rs/s/cxdpiu/our_response_emudhra_key_disclosure) |
| 3 | 0 | [(VCF Midwest 2026) Building a Living 90s Internet for Vintage Computers](https://www.youtube.com/watch?v=mZfJ-sulqQs) | `retrocomputing` `video` | [讨论](https://lobste.rs/s/uhfzlv/vcf_midwest_2026_building_living_90s) |
| 9 | 0 | [Heavenly delights of hashing numbers under EQUALP](https://turtleware.eu/posts/Heavenly-delights-of-hashing-numbers-under-EQUALP.html) | `lisp` `math` `performance` `programming` | [讨论](https://lobste.rs/s/0ta2mv/heavenly_delights_hashing_numbers_under) |
| 41 | 40 | [“AI Skills” are worthless in 2026](https://fishbowl.pastiche.org/2026/10/26/ai-skills) | `ai-tooling` `practices` | [讨论](https://lobste.rs/s/x1s5oq/ai_skills_are_worthless_2026) |
| 12 | 6 | [From impulse purchase to pocket studio: The M-Vave FM-1](https://arstechnica.com/gadgets/2026/10/from-impulse-purchase-to-pocket-studio-the-m-vave-fm-1/) | `hardware` | [讨论](https://lobste.rs/s/5u7gjd/from_impulse_purchase_pocket_studio_m) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 79 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 3 | 1 | 33% | — |
| 🔴 先核对 | 4 | 3 | 75% | — |
| 🟡 在降温 | 4 | 0 | 0% | — |
| 🔵 已被发现 | 2 | 0 | 0% | — |
| 🟢 窗口内 | 6 | 4 | 66% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [ARahim3/DigUp](https://github.com/ARahim3/DigUp) | 2026-10-13 | 🟢 窗口内 | 2071 | 5879 | 5 | ✅ 起来了 |
| [Ayzzz123/mcd-coupon-strategist](https://github.com/Ayzzz123/mcd-coupon-strategist) | 2026-10-13 | 🟢 窗口内 | 256 | 990 | 0 | ✅ 起来了 |
| [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) | 2026-10-13 | 🟢 窗口内 | 1362 | 1675 | 0 | 没起来 |
| [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | 2026-10-13 | 🔴 先核对 | 1057 | 2158 | 10 | ✅ 起来了 |
| [bherbruck/solidcraft](https://github.com/bherbruck/solidcraft) | 2026-10-13 | 🟢 窗口内 | 1330 | 10855 | 146 | ✅ 起来了，比 HN 早 0 天 |
| [dzhng/jevgrep](https://github.com/dzhng/jevgrep) | 2026-10-13 | 🟡 在降温 | 2651 | 2912 | 5 | 没起来 |
| [feder-cr/invisible_playwright_mcp](https://github.com/feder-cr/invisible_playwright_mcp) | 2026-10-13 | 🔴 先核对 | 2764 | 885 | 0 | 没起来 |
| [feitangyuan/onetake](https://github.com/feitangyuan/onetake) | 2026-10-13 | 🟡 在降温 | 2249 | 3331 | 0 | 没起来 |
| [jhaizhou-ops/d2r-mobile](https://github.com/jhaizhou-ops/d2r-mobile) | 2026-10-13 | 🚀 爆发 | 960 | 4716 | 0 | ✅ 起来了 |
| [liseami/CCBaga](https://github.com/liseami/CCBaga) | 2026-10-13 | 🚀 爆发 | 1894 | 3125 | 0 | 没起来 |
| [mhtsec/ARTEX](https://github.com/mhtsec/ARTEX) | 2026-10-13 | 🚀 爆发 | 3778 | 0 | 0 | 仓库没了 |
| [morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering) | 2026-10-13 | 🟢 窗口内 | 349 | 1289 | 0 | ✅ 起来了 |
| [mrsarac/ff-tracking](https://github.com/mrsarac/ff-tracking) | 2026-10-13 | 🟢 窗口内 | 351 | 525 | 0 | 没起来 |
| [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) | 2026-10-13 | 🟡 在降温 | 1929 | 2583 | 0 | 没起来 |
| [oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) | 2026-10-13 | 🟡 在降温 | 1420 | 2383 | 0 | 没起来 |
| [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) | 2026-10-13 | 🔴 先核对 | 1113 | 3961 | 3 | ✅ 起来了 |
| [openai/math](https://github.com/openai/math) | 2026-10-13 | 🚀 爆发 | 14551 | 15710 | 431 | 没起来 |
| [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | 2026-10-13 | 🔴 先核对 | 469 | 2044 | 0 | ✅ 起来了 |
| [pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust) | 2026-10-13 | 🔵 已被发现 | 1139 | 1532 | 119 | 没起来 |
| [rociiu/talorys](https://github.com/rociiu/talorys) | 2026-10-13 | 🔵 已被发现 | 920 | 1391 | 331 | 没起来 |

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
