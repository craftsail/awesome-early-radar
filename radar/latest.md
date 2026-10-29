# early-radar 选题雷达 · 2026-10-29

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 106 个，细查前 20 个 · 比上次 = 和 2026-10-28 那次比 · 生成于 2026-10-29 05:23 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 3 个 · Show HN ✅ 18 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 5 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 5 个 · 🟡 在降温 8 个 · 🔵 已被发现 0 个 · 💤 不活跃 1 个 · 🔴 先核对 6 个
- **今天新出现 3 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) 平均每天 +3715，见 [爆发](#爆发)
- **复盘**：🚀 爆发 5/7 · 🔴 先核对 5/8 · 🟡 在降温 0/5 · 🔵 已被发现 0/2 · 🟢 窗口内 4/7（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [xevrion/hatchzip](https://github.com/xevrion/hatchzip) — HatchZip is a free, open-source archive extractor for Window…（近 7 天 +2253，比前 7 天快 93.9 倍，在加速）
  - [indexable-inc/blaze](https://github.com/indexable-inc/blaze) — Incremental rust builds up to 92x faster than cargo/rustc（近 7 天 +1513，比前 7 天快 8.1 倍，在加速）
  - [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) — Agent Skills that teach coding agents to write, review, and…（近 7 天 +1373，刚发布一周内）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 21 个（star 合计 24458），代表：[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：4 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Steal My Bitcoin](https://stealmybitcoin.com/) — 623 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) | 44141 | 3715 | +1905 | 11.9 | [6](https://news.ycombinator.com/item?id=50164485) | cleanyourtv · gathin23 cleanyourtv · gathin cleanyourtv | Debloat any Android or Google TV over Wi-Fi and get an Apple… |
| [deepseek-ai/DeepInfer](https://github.com/deepseek-ai/DeepInfer) | 24010 | 1861 | +534 | 12.9 | [2353](https://news.ycombinator.com/item?id=50163277) | deepinfer · deepseek-ai deepinfer · deepseek deepinfer | DeepInfer: High-performance, large-scale inference framework… |
| 🆕 [interplains/Zero-Breach-Toolkit](https://github.com/interplains/Zero-Breach-Toolkit) | 2923 | 809 | +1803 | 3.6 | — | zero breach toolkit · interplains zero breach toolkit · archivegenocide zero breach toolkit | Free, open-source, offline checks for traces of known mercen… |
| [anhao/ai-pose-gallery-zh](https://github.com/anhao/ai-pose-gallery-zh) | 2165 | 1268 | +1362 | 1.7 | — | ai pose gallery zh · anhao ai pose gallery zh | 中文版 AI 姿势参考图库 · 1439 组 / 2878 张图片 / 完整汉化 · 零依赖静态画廊 |
| [unclebob/ub-mode](https://github.com/unclebob/ub-mode) | 3953 | 1112 | +1312 | 3.6 | — | ub mode · unclebob ub mode · robert ub mode |  |
| [Zagitta/gpu-unlock](https://github.com/Zagitta/gpu-unlock) | 12519 | 1121 | +942 | 11.2 | [349](https://news.ycombinator.com/item?id=50219700) | gpu unlock · zagitta gpu unlock · simon gpu unlock | Your GeForce runs AI at half speed. This fixes it for 20/30/… |
| [rddmwmddr/android-ad-cleaner](https://github.com/rddmwmddr/android-ad-cleaner) | 4436 | 889 | +778 | 5 | — | android ad cleaner · rddmwmddr android ad cleaner | 关掉国产安卓手机系统里的广告、热搜、资讯推荐和营销推送。不 root，可还原，支持 AI 智能体一键执行。 |
| [pengchujin/aerial-tv](https://github.com/pengchujin/aerial-tv) | 7495 | 848 | +484 | 8.8 | — | aerial tv · pengchujin aerial tv | 给国产电视的一块干净桌面：参照 tvOS 设计的开源 Android TV 桌面，没有广告，开机自动接管。A tvOS-… |
| [JustAResearcher/gpu-unlock-ada](https://github.com/JustAResearcher/gpu-unlock-ada) | 4443 | 831 | +124 | 5.3 | [3](https://news.ycombinator.com/item?id=50223787) | gpu unlock ada · justaresearcher gpu unlock ada · tim gpu unlock ada | GPU tensor unlock source for RTX 4090 and experimental RTX 4… |
| [designfuchen/word-atlas](https://github.com/designfuchen/word-atlas) | 3106 | 802 | +384 | 3.9 | — | word atlas · designfuchen word atlas · boxin word atlas | 词光 · Word Atlas — Illustrated IELTS vocabulary with 7,298 wo… |
| 🆕 [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) | 1380 | 186 | +740 | 7.4 | — | openduet · copilotkit openduet | An Open Source template for a proactive AI agent that gets y… |
| 🆕 [smithjohn78390/tongjiang-lab](https://github.com/smithjohn78390/tongjiang-lab) | 628 | 605 | — | 1 | — | tongjiang lab · smithjohn78390 tongjiang lab | Free interactive 3D science lessons for high school · 铜匠实验室… |
| 🆕 [LNPANDY/NX2Apple](https://github.com/LNPANDY/NX2Apple) | 1664 | 197 | +586 | 8.5 | — | nx2apple · lnpandy nx2apple · lnp nx2apple | Play your own Switch games on iPhone/iPad — one-click macOS… |
| [simbasjungles/free-my-tv](https://github.com/simbasjungles/free-my-tv) | 5267 | 560 | +184 | 9.4 | [1](https://news.ycombinator.com/item?id=50220596) | free my tv · simbasjungles free my tv · simba free my tv | A fast, ad-free home screen for Google TV, LG webOS and Sams… |
| [ly05010419/MacNativeGames](https://github.com/ly05010419/MacNativeGames) | 6320 | 555 | +232 | 11.4 | — | macnativegames · ly05010419 macnativegames · yong macnativegames | Play your own Tears of the Kingdom and Breath of the Wild na… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 92.6 | 🟢 窗口内 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2277 | +78 | +2253 | +24 | `·····▁▁█▅▂▂▂▁·` | 7 | [3](https://news.ycombinator.com/item?id=50207695) | — |
| 2 | 87.9 | 🟢 窗口内 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | Rust | 1700 | +137 | +1513 | +187 | `···▁▃▁▁▁▂▃▆█▂·` | 9 | — | — |
| 3 | 86.7 | 🟢 窗口内 | [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) | Python | 1373 | +45 | +1373 | +0 | `········▅█▅▂▁·` | 6 | — | — |
| 4 | 83.2 | 🆕 🟢 窗口内 | [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) | Kotlin | 1029 | +108 | +1028 | +1 | `······▁▄█▇▄▅▄·` | 7 | — | — |
| 5 | 80.7 | 🟢 窗口内 | [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) | Python | 1600 | +0 | +833 | +752 | `▂▃▅▃▄▃▃▇█▅▂▁··` | 13 | — | — |
| 6 | 65.6 | 🟡 在降温 | [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) | Python | 1552 | +53 | +702 | +850 | `▃▅█▆▅▃▂█▅▆▃▃▂·` | 12 | [1](https://news.ycombinator.com/item?id=50177079) | — |
| 7 | 60.2 | 🟡 在降温 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) | Go | 2148 | +54 | +411 | +543 | `▂▂▃▆███▆▄▄▅▆▃·` | 20 | — | — |
| 8 | 59.7 | 🟡 在降温 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 1867 | +48 | +389 | +1478 | `··█▆▃▃▃▂▂▂▂▂▁·` | 10 | — | — |
| 9 | 56.2 | 🟡 在降温 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 2133 | +41 | +274 | +618 | `█▆▆▅▄▄▃▃▃▄▄▃▃·` | 18 | — | — |
| 10 | 55.3 | 🟡 在降温 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | Python | 2287 | +61 | +251 | +548 | `█▅▅▄▄▃▂▃▂▃▂▄▃·` | 23 | [10](https://news.ycombinator.com/item?id=50037852) | — |
| 11 | 53.7 | 🟡 在降温 | [reason-machines/reason-network](https://github.com/reason-machines/reason-network) | Rust | 1308 | +16 | +213 | +1094 | `▄▆▅▃█▆▅▃▂▂▂▂▁·` | 12 | — | — |
| 12 | 53.5 | 🟡 在降温 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 1926 | +40 | +209 | +692 | `▂▁▁▁█▃▂▂▁▁▂▂▂·` | 16 | — | — |
| 13 | 53.2 | 🟡 在降温 | [ELY-Open-Source/ElyOffice](https://github.com/ELY-Open-Source/ElyOffice) | Rust | 1089 | +19 | +203 | +886 | `···▇█▃▄▂▂▂▂▂▁·` | 9 | — | — |
| 14 | 46.4 | 🔴 先核对 | [t3dotgg/tstack](https://github.com/t3dotgg/tstack) | Python | 2289 | +241 | +2289 | +0 | `·······▁▁▁█▃▂·` | 5 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 15 | 43.4 | 🆕 🔴 先核对 | [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) | TypeScript | 1380 | +740 | +1379 | +1 | `·····▁·····██·` | 7 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 16 | 43.2 | 🔴 先核对 | [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | TypeScript | 1342 | +193 | +1342 | +0 | `·········▂█▄▃·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 42.5 | 🔴 先核对 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 1186 | +117 | +1186 | +0 | `·········█▄▄▂·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 41.7 | 💤 不活跃 | [yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) | Python | 1832 | -106 | +1042 | +516 | `▂▂▁▂▂▂▃▃█▇·▁··` | 16 | — | — |
| 19 | 39.8 | 🔴 先核对 | [mizorewww/gdirect](https://github.com/mizorewww/gdirect) | Rust | 758 | +6 | +758 | +0 | `········▁█▂▁▁·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 39.6 | 🆕 🔴 先核对 | [l0ng-ai/openidea](https://github.com/l0ng-ai/openidea) | TypeScript | 774 | — | +739 | +35 | `······▂▁▂▂▁▄█·` | 7 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 551 | 30 | 47170 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[t3dotgg/tstack](https://github.com/t3dotgg/tstack) |
| `mcp` | 289 | 30 | 32638 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) |
| `rust` | 189 | 30 | 28136 | [oxc-project/tsrs](https://github.com/oxc-project/tsrs)、[academa-labs/manimgx](https://github.com/academa-labs/manimgx)、[xevrion/hatchzip](https://github.com/xevrion/hatchzip) |
| `local-first` | 63 | 30 | 9375 | [chenxiachan/textfold](https://github.com/chenxiachan/textfold)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch)、[aboard-io/tinylittleoffice](https://github.com/aboard-io/tinylittleoffice) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 21 | 24458 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill) |
| `ai-agents` | 19 | 15161 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering) |
| `agent-skills` | 15 | 20190 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `codex` | 15 | 16302 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) |
| `llm` | 15 | 12126 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[Harvil1/codeAgent](https://github.com/Harvil1/codeAgent) |
| `mcp-server` | 12 | 10415 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `ai-agent` | 9 | 7367 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `claude-skills` | 8 | 11658 | [oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `developer-tools` | 8 | 6712 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai)、[hanzohanzhe/Grandet](https://github.com/hanzohanzhe/Grandet) |
| `macos` | 8 | 5704 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[kitlangton/scrawl](https://github.com/kitlangton/scrawl)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch) |
| `self-hosted` | 7 | 5731 | [marclou/mailcheap](https://github.com/marclou/mailcheap)、[rociiu/talorys](https://github.com/rociiu/talorys)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) |
| `coding-agents` | 7 | 5121 | [reason-machines/reason-network](https://github.com/reason-machines/reason-network)、[openqodex/openqodex](https://github.com/openqodex/openqodex)、[feder-cr/git-ai](https://github.com/feder-cr/git-ai) |

**语言分布**：Python 30 · Rust 30 · TypeScript 18 · JavaScript 12 · Go 3 · HTML 3 · Swift 2 · Astro 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [xevrion/hatchzip](https://github.com/xevrion/hatchzip) · 🟢 窗口内 · 92.6 分

> HatchZip is a free, open-source archive extractor for Windows, macOS and Linux that extracts ZIP, 7z, RAR, tar and split archives in place, so it needs free space for the extracted files only. Desktop app and CLI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2277 | +2253 | +24 | 71 | 9 | Rust | Apache-2.0 | 10-21（7 天前） | 今天 |

- **近 14 天每天新增**：`·····▁▁█▅▂▂▂▁·` 0 0 0 0 0 1 23 1138 604 199 101 144 67 0
- **势头**：比前 7 天快 93.9 倍，在加速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=50207695)）
- **topics**：`7z` `7zip` `archive` `archive-extractor` `cli` `crash-safe` `disk-space` `extract` `extractor` `gui` `in-place` `linux` `macos` `rar` `rust` `tar` `unrar` `unzip` `windows` `zip`
- **主页**：<https://hatchzip.dev>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [indexable-inc/blaze](https://github.com/indexable-inc/blaze) · 🟢 窗口内 · 87.9 分

> Incremental rust builds up to 92x faster than cargo/rustc

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1700 | +1513 | +187 | 58 | 462 | Rust | Apache-2.0 | 10-19（9 天前） | 今天 |

- **近 14 天每天新增**：`···▁▃▁▁▁▂▃▆█▂·` 0 0 0 17 151 14 5 4 104 156 456 675 118 0
- **势头**：比前 7 天快 8.1 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`cargo` `compiler` `cranelift` `developer-tools` `hot-reload` `incremental-compilation` `jit` `live-coding` `rust` `rust-analyzer`
- **主页**：<https://ix.dev/blaze>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) · 🟢 窗口内 · 86.7 分

> Agent Skills that teach coding agents to write, review, and port idiomatic Rust, plus a tested clippy config. Works with Claude Code, Codex, Copilot, Cursor, and Gemini CLI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1373 | +1373 | +0 | 63 | 4 | Python | MIT | 10-23（6 天前） | 今天 |

- **近 14 天每天新增**：`········▅█▅▂▁·` 0 0 0 0 0 0 0 0 303 583 357 90 40 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `claude-code` `claude-plugin` `claude-skills` `clippy` `code-review` `coding-agent` `cursor` `rust` `style-guide`
- **主页**：<https://www.beautifulrust.dev>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. 🆕 [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) · 🟢 窗口内 · 83.2 分

> A community-built phone app for Clean Your TV: clean up an Android TV from your phone. No laptop, no coding agent, nothing uninstalled.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1029 | +1028 | +1 | 96 | 1761 | Kotlin | MIT | 10-21（7 天前） | 今天 |

- **近 14 天每天新增**：`······▁▄█▇▄▅▄·` 0 0 0 0 0 0 1 104 288 246 133 151 106 0
- **势头**：比前 7 天快 1028.0 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adb` `android-tv` `debloat` `fire-tv` `google-tv` `launcher`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) · 🟢 窗口内 · 80.7 分

> 麦当劳 MCP 聚会/团餐组织助手 — 基于 Model Context Protocol 的派对预订与团餐规划 CLI/Skill

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1600 | +833 | +752 | 58 | 2 | Python | MIT | 10-15（13 天前） | 1 天前 |

- **近 14 天每天新增**：`▂▃▅▃▄▃▃▇█▅▂▁··` 53 96 166 115 133 114 75 256 325 176 59 17 0 0
- **势头**：比前 7 天快 1.1 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) · 🟡 在降温 · 65.6 分

> Co-op Anything: point your AI agent at any single-player game and play it with friends (online and/or splitscreen!). MCP server and playbook to let you reverse engineer, fix, test, ship and share what it learns.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1552 | +702 | +850 | 207 | 144 | Python | MIT | 10-16（12 天前） | 今天 |

- **近 14 天每天新增**：`▃▅█▆▅▃▂█▅▆▃▃▂·` 81 131 234 156 124 77 47 227 149 161 67 56 42 0
- **势头**：只有前 7 天的 83%，在减速
- **HN**：发过 1 次，最高 1 分（[讨论](https://news.ycombinator.com/item?id=50177079)）
- **主页**：<https://coopanything.app>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 7. [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) · 🟡 在降温 · 60.2 分

> ARTEX · AI autonomous penetration testing system (multi-agent LLM, Go + Next.js) · AI 自主渗透测试系统 · 百度 agent+ 攻防挑战赛冠军

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2148 | +411 | +543 | 1016 | 3 | Go | AGPL-3.0 | 10-08（20 天前） | 9 天前 |

- **近 14 天每天新增**：`▂▂▃▆███▆▄▄▅▆▃·` 10 19 45 92 127 122 128 90 56 46 80 95 44 0
- **势头**：只有前 7 天的 76%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `ai-security` `artex` `autonomous-agents` `cybersecurity` `go` `hacking` `llm` `llm-agent` `mcp` `nextjs` `offensive-security` `penetration-testing` `pentest` `red-team` `security` `security-tools` `vulnerability` `vulnerability-scanners` `web-security`
- **主页**：<https://artex-demo.vercel.app/>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) · 🟡 在降温 · 59.7 分

> 让你的agent一键直出商业级产品宣传片：会作曲，能指着画面改。Commercial-grade launch films by your coding agent — point at the frame to change it.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1867 | +389 | +1478 | 178 | 3 | JavaScript | MIT | 10-18（10 天前） | 6 天前 |

- **近 14 天每天新增**：`··█▆▃▃▃▂▂▂▂▂▁·` 0 0 580 437 170 135 156 78 50 83 68 73 37 0
- **势头**：只有前 7 天的 26%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `animation` `claude-code` `codex` `gsap` `launch-video` `motion-graphics` `skills`
- **主页**：<https://github.com/alchaincyf/huashu-motion>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [opengeos/RustGIS](https://github.com/opengeos/RustGIS) · 🟡 在降温 · 56.2 分

> A fast, free and open-source GIS in pure Rust.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2133 | +274 | +618 | 306 | 85 | Rust | Apache-2.0 | 10-10（18 天前） | 今天 |

- **近 14 天每天新增**：`█▆▆▅▄▄▃▃▃▄▄▃▃·` 149 116 102 77 69 63 42 34 32 67 54 50 37 0
- **势头**：只有前 7 天的 44%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`geospatial` `gis` `remote-sensing` `rust` `rust-lang`
- **主页**：<https://rustgis.app>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [academa-labs/manimgx](https://github.com/academa-labs/manimgx) · 🟡 在降温 · 55.3 分

> The animation engine for agents: blazingly fast math and 3D videos with Manim's Python API, on a Rust GPU core.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2287 | +251 | +548 | 163 | 30 | Python | MIT | 10-05（23 天前） | 2 天前 |

- **近 14 天每天新增**：`█▅▅▄▄▃▂▃▂▃▂▄▃·` 159 84 98 68 65 43 31 36 25 35 27 79 49 0
- **势头**：只有前 7 天的 46%，在减速
- **HN**：发过 1 次，最高 10 分（[讨论](https://news.ycombinator.com/item?id=50037852)）
- **主页**：<https://manimgx.academa.ai>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [t3dotgg/tstack](https://github.com/t3dotgg/tstack) — 一天进了一半以上的 star，但 HN 上没火过
- [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) — 一天进了一半以上的 star，但 HN 上没火过
- [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) — 一天进了一半以上的 star，但 HN 上没火过
- [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) — 一天进了一半以上的 star，但 HN 上没火过
- [mizorewww/gdirect](https://github.com/mizorewww/gdirect) — 一天进了一半以上的 star，但 HN 上没火过
- [l0ng-ai/openidea](https://github.com/l0ng-ai/openidea) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 623 | 450 | [Show HN: Steal My Bitcoin](https://stealmybitcoin.com/) | [HN](https://news.ycombinator.com/item?id=50224916) |
| 404 | 82 | [Show HN: TitleArt – Make text like it's 1997](https://titleart.dvy.io/) | [HN](https://news.ycombinator.com/item?id=50238708) |
| 315 | 115 | [Show HN: A Truly Modular Keyboard](https://github.com/notaroomba/keybytes) | [HN](https://news.ycombinator.com/item?id=50228115) |
| 236 | 94 | [Show HN: OnKey – I'm a bad singer, so I built an app to show where I'm off-key](https://github.com/dsmurrell/onkey) | [HN](https://news.ycombinator.com/item?id=50195488) |
| 177 | 49 | [Show HN: I put employees inside S&P 500 market-cap bubbles](https://bigwhalehunting.com/workforce/) | [HN](https://news.ycombinator.com/item?id=50232312) |
| 172 | 42 | [Show HN: Hob - Open-source, on device alternative to Claude Cowork and ChatGPT](https://github.com/FrigadeHQ/hob) | [HN](https://news.ycombinator.com/item?id=50246238) |
| 149 | 64 | [Show HN: Encarta 95 Web](https://benwinding.github.io/encarta_95_web/#/article/Art) | [HN](https://news.ycombinator.com/item?id=50218975) |
| 141 | 47 | [Show HN: Corgi, a helpful {agent, terminal} multiplexer](https://corgi.computer/) | [HN](https://news.ycombinator.com/item?id=50214373) |
| 112 | 81 | [Show HN: Making a smart TV dumb and then smart](https://github.com/anubhavmalhotra/r2d2-tv) | [HN](https://news.ycombinator.com/item?id=50202865) |
| 82 | 22 | [Show HN: Impossible Machines: declaratively program the physical world](https://www.impossiblemachines.xyz) | [HN](https://news.ycombinator.com/item?id=50202746) |
| 80 | 46 | [Show HN: UI micro interactions prompts for AI](https://www.typeui.sh/micro-interactions) | [HN](https://news.ycombinator.com/item?id=50199290) |
| 77 | 38 | [Show HN: Swurf – Swipe through the real web](https://swurf.org/) | [HN](https://news.ycombinator.com/item?id=50205320) |
| 70 | 57 | [Show HN: We had AI write a wiki from 45k Enron emails, every fact cited](https://www.thisandthat.chat/enron/) | [HN](https://news.ycombinator.com/item?id=50207620) |
| 68 | 26 | [Show HN: SlideBySide – Present slides without sharing your screen](https://slidebyside.com/) | [HN](https://news.ycombinator.com/item?id=50276883) |
| 68 | 26 | [Show HN: Hurston-1 open source TTS that speak Southern American and Afro-English](https://huggingface.co/destined/hurston-1) | [HN](https://news.ycombinator.com/item?id=50227330) |
| 66 | 58 | [Show HN: ADRs for AI – Deliberation records for human–AI work, versioned in Git](https://adrs.systems) | [HN](https://news.ycombinator.com/item?id=50227041) |
| 60 | 43 | [Show HN: Farol – A risk map of a pull request for the person who approves it](https://github.com/winnin/farol) | [HN](https://news.ycombinator.com/item?id=50231349) |
| 59 | 19 | [Show HN: Autonomous root for Tcl Android TV via CVE-2022-22706](https://gitlab.com/c4psu13/mali-pagecache-root) | [HN](https://news.ycombinator.com/item?id=50220042) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 157 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 117967★ |
| 125 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 21029★ |
| 104 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 29536★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 34627★ |
| 48 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 34683★ |
| 62 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 44019★ |
| 108 | [Hy-Nomas: Towards Free-form Interactive World Generation](https://huggingface.co/papers/2610.36729) | Hy-Nomas is a video world model that uses causal attention and structured conditioning to generate interactive, multi-turn video segments wi… | 💡 [Tencent-Hunyuan/Hy-Nomas](https://github.com/Tencent-Hunyuan/Hy-Nomas) 355★ |
| 107 | [MOSS-Image Technical Report](https://huggingface.co/papers/2610.23374) | MOSS-Image is an open diffusion transformer that combines high-fidelity synthesis with intent-aware prompt enhancement to generate text-rich… | [OpenMOSS/MOSS-Image](https://github.com/OpenMOSS/MOSS-Image) 2177★ |
| 31 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 7496★ |
| 23 | [Prism: Dynamic Sparse Attention for Native 2K Joint Video-Audio Generation Model Training](https://huggingface.co/papers/2610.05416) | Prism accelerates native joint video-audio generation at 2K by using dynamic sparse attention guided by local visual variance and audio-visu… | [Tencent-Hunyuan/Prism](https://github.com/Tencent-Hunyuan/Prism) 1440★ |
| 121 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 2798★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 92108★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 205 | [DynaFlow: Learning Free-Form Multi-Agent Orchestration](https://huggingface.co/papers/2610.34467) | DynaFlow enables adaptive multi-agent collaboration by letting a main agent synthesize executable workflows that coordinate sub-agents throu… | 💡 [amiya-special/Dynaflow](https://github.com/amiya-special/Dynaflow) 142★ |
| 18 | [Next-Concept Modeling: Fast, Parallel Coarse-to-Fine Text Generation](https://huggingface.co/papers/2610.14162) | Next-Concept Modeling uses hierarchical discrete codes and parallel level-wise generation to accelerate diffusion language models while impr… | [HazyResearch/ncm](https://github.com/HazyResearch/ncm) 1230★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 82693★ |
| 118 | [Work Agents: Systems, Capabilities, and Optimization](https://huggingface.co/papers/2610.35845) | The paper proposes a unified framework for work agents that integrates foundation models with runtime harnesses to execute complex digital t… | 💡 [EnjunDu/awesome-working-agent](https://github.com/EnjunDu/awesome-working-agent) 65★ |
| 180 | [SmolDocling: An ultra-compact vision-language model for end-to-end multi-modal document conversion](https://huggingface.co/papers/2503.11576) | SmolDocling is a compact vision-language model that performs end-to-end document conversion with robust performance across various document… | [docling-project/docling](https://github.com/docling-project/docling) 69752★ |
| 27 | [Build, Don't Play: Self-Improving LLM Research Agents Develop a Hearthstone Battlegrounds AI That Ri…](https://huggingface.co/papers/2610.33845) | AutoTavern demonstrates that self-improving LLM research agents can autonomously build a faithful game simulator and train a reinforcement l… | 💡 [MCG-NJU/AutoTavern](https://github.com/MCG-NJU/AutoTavern) 143★ |
| 75 | [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://huggingface.co/papers/2504.19413) | Mem0, a memory-centric architecture with graph-based memory, enhances long-term conversational coherence in LLMs by efficiently extracting,… | [mem0ai/mem0](https://github.com/mem0ai/mem0) 68013★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 17 | [nvidia nemotron 3.5 transcribe](https://huggingface.co/nvidia/NVIDIA-Nemotron-3.5-Transcribe-30B-A4B) | automatic-speech-recognition | 231 | 1 |
| 46 | [lfm3](https://huggingface.co/AtomicChat/LFM3-1.7B-Uncensored-GGUF) | text-generation | 113 | 1 |
| 49 | [clover](https://huggingface.co/Diffuspace/Clover-35B-A3B-Preview) | text-generation | 108 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 95 | 19 | [Apple's git still trusts the compromised eMudhra certificates](https://emudhra.we-have-a-problem.com/apple.html) | `cryptography` `mac` | [讨论](https://lobste.rs/s/xybmsj/apple_s_git_still_trusts_compromised) |
| 65 | 17 | [AlpineBSD](https://wiki.alpinebsd.org/) | `netbsd` | [讨论](https://lobste.rs/s/yxuvie/alpinebsd) |
| 15 | 2 | [GitLab security incident: attempted exploitation of CVE-2026-97229](https://alpinelinux.org/posts/GitLab-security-incident-CVE-2026-97229.html) | `linux` `security` | [讨论](https://lobste.rs/s/2zsjwt/gitlab_security_incident_attempted) |
| 127 | 32 | [This is not sustainable](https://www.netmeister.org/blog/defense-ddos.html) | `security` | [讨论](https://lobste.rs/s/cpaibp/this_is_not_sustainable) |
| 31 | 11 | [GOTO Considered Totally Sick (for error handling in C)](https://thestateofinahaze.net/blog/c-goto-considered-totally-sick/) | `c` | [讨论](https://lobste.rs/s/exwlmn/goto_considered_totally_sick_for_error) |
| 20 | 1 | [EMACS turns 50](https://www.technologyreview.com/2026/10/20/1145399/emacs-turns-50/) | `emacs` `historical` | [讨论](https://lobste.rs/s/uimyck/emacs_turns_50) |
| 33 | 0 | [Why Is This Fingerprinting Script Creating Bioweapons?](https://nullpt.rs/fingerprinting-bioweapons) | `ai` `reversing` | [讨论](https://lobste.rs/s/gvy5gz/why_is_this_fingerprinting_script) |
| 32 | 2 | [Hoot 0.10.0 released](https://spritely.institute/news/hoot-0-10-0-released.html) | `lisp` `release` | [讨论](https://lobste.rs/s/m3gsln/hoot_0_10_0_released) |
| 11 | 0 | [The case of the 9 bit AES key](https://v12.sh/blog/the-case-of-the-9bit-aes-key) | `cryptography` `reversing` | [讨论](https://lobste.rs/s/dqexzg/case_9_bit_aes_key) |
| 28 | 13 | [Code-execution flaw in UEFI firmware affects most servers on planet Earth](https://arstechnica.com/security/2026/10/code-execution-flaw-in-uefi-firmware-threatens-most-servers-on-planet-earth/) | `security` | [讨论](https://lobste.rs/s/0gomue/code_execution_flaw_uefi_firmware) |
| 84 | 15 | [A fast and secure tar parser for the Rust ecosystem](https://astral.sh/blog/tar-codec) | `python` `rust` | [讨论](https://lobste.rs/s/q7arzy/fast_secure_tar_parser_for_rust_ecosystem) |
| 35 | 1 | [Start Doing Graph Theory](https://vertex.degree/) | `book` `math` | [讨论](https://lobste.rs/s/46sc07/start_doing_graph_theory) |
| 6 | 0 | [Redox Ring Buffers Project Summary](https://www.redox-os.org/news/nlnet-rb-summary/) | `osdev` | [讨论](https://lobste.rs/s/brdwr2/redox_ring_buffers_project_summary) |
| 22 | 2 | [Forging a Microsoft Edge Full Chain with Logic Bugs Only](https://blog.orange.tw/posts/2026-10-the-last-proof-of-human-craft-browser-full-chain/) | `security` | [讨论](https://lobste.rs/s/ansfvi/forging_microsoft_edge_full_chain_with) |
| 23 | 7 | [Billion-query-per-second lookup tables in C++](https://lemire.me/blog/2026/10/26/billion-query-per-second-lookup-tables-in-c/) | `c++` `programming` | [讨论](https://lobste.rs/s/d3ubhd/billion_query_per_second_lookup_tables_c) |
| 83 | 15 | [Ghostty 1.4.0](https://ghostty.org/docs/install/release-notes/1-4-0) | `release` | [讨论](https://lobste.rs/s/o6vpqb/ghostty_1_4_0) |
| 69 | 23 | [Four Months of Zig](https://gracefulliberty.com/articles/four-months-of-zig/) | `zig` | [讨论](https://lobste.rs/s/qr59sa/four_months_zig) |
| 23 | 2 | [Pair-coding Lobste.rs feat](https://lobste.rs/s/mgy3tr) | `ask` `meta` `ruby` | [讨论](https://lobste.rs/s/mgy3tr/pair_coding_lobste_rs_feat) |
| 13 | 1 | [Raspberry Pi Zero 3 W and Pi 4 Model A on the Way?](https://bret.dk/raspberry-pi-zero-3-w-pi-4-model-a/) | `hardware` `linux` | [讨论](https://lobste.rs/s/hqcvyj/raspberry_pi_zero_3_w_pi_4_model_on_way) |
| 4 | 0 | [Introducing the Accessible Components Library](https://tetralogical.com/blog/2026/10/14/accessible-components-library/) | `a11y` `web` | [讨论](https://lobste.rs/s/ssp7ug/introducing_accessible_components) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 79 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 7 | 5 | 71% | — |
| 🔴 先核对 | 8 | 5 | 62% | — |
| 🟡 在降温 | 5 | 0 | 0% | — |
| 🔵 已被发现 | 2 | 0 | 0% | — |
| 🟢 窗口内 | 7 | 4 | 57% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [HeyPuter/everything](https://github.com/HeyPuter/everything) | 2026-10-15 | 🚀 爆发 | 794 | 5010 | 59 | ✅ 起来了 |
| [Oldcircle/geo-sleuth](https://github.com/Oldcircle/geo-sleuth) | 2026-10-15 | 🟢 窗口内 | 2821 | 4445 | 0 | 没起来 |
| [T-Auto/dsh-ops](https://github.com/T-Auto/dsh-ops) | 2026-10-15 | 🚀 爆发 | 1764 | 4710 | 0 | ✅ 起来了 |
| [marclou/mailcheap](https://github.com/marclou/mailcheap) | 2026-10-15 | 🔴 先核对 | 933 | 1539 | 2 | 没起来 |
| [spideymooon/McOracle](https://github.com/spideymooon/McOracle) | 2026-10-15 | 🔴 先核对 | 287 | 617 | 0 | 没起来 |

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
