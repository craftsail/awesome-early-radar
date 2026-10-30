# early-radar 选题雷达 · 2026-10-30

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 107 个，细查前 20 个 · 比上次 = 和 2026-10-29 那次比 · 生成于 2026-10-30 05:23 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 2 个 · Show HN ✅ 17 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 6 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 8 个 · 🟡 在降温 7 个 · 🔵 已被发现 0 个 · 💤 不活跃 1 个 · 🔴 先核对 4 个
- **今天新出现 2 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) 平均每天 +3547，见 [爆发](#爆发)
- **复盘**：🚀 爆发 6/11 · 🔴 先核对 5/10 · 🟡 在降温 0/5 · 🔵 已被发现 0/2 · 🟢 窗口内 4/7（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [SoMarkAI/OXR](https://github.com/SoMarkAI/OXR) — An open-source document parsing model with SOTA accuracy and…（近 7 天 +2163，比前 7 天快 5.6 倍，在加速）
  - [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) — An Open Source template for a proactive AI agent that gets y…（近 7 天 +1565，比前 7 天快 1565.0 倍，在加速）
  - [indexable-inc/blaze](https://github.com/indexable-inc/blaze) — Incremental rust builds up to 92x faster than cargo/rustc（近 7 天 +1552，比前 7 天快 8.1 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 22 个（star 合计 26419），代表：[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：4 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Steal My Bitcoin](https://stealmybitcoin.com/) — 623 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) | 45693 | 3547 | +1552 | 12.9 | [6](https://news.ycombinator.com/item?id=50164485) | cleanyourtv · gathin23 cleanyourtv · gathin cleanyourtv | Debloat any Android or Google TV over Wi-Fi and get an Apple… |
| [deepseek-ai/DeepInfer](https://github.com/deepseek-ai/DeepInfer) | 24312 | 1749 | +302 | 13.9 | [2353](https://news.ycombinator.com/item?id=50163277) | deepinfer · deepseek-ai deepinfer · deepseek deepinfer | DeepInfer: High-performance, large-scale inference framework… |
| [anhao/ai-pose-gallery-zh](https://github.com/anhao/ai-pose-gallery-zh) | 3375 | 1247 | +1210 | 2.7 | — | ai pose gallery zh · anhao ai pose gallery zh | 中文版 AI 姿势参考图库 · 1439 组 / 2878 张图片 / 完整汉化 · 零依赖静态画廊 |
| [Zagitta/gpu-unlock](https://github.com/Zagitta/gpu-unlock) | 13181 | 1084 | +662 | 12.2 | [350](https://news.ycombinator.com/item?id=50219700) | gpu unlock · zagitta gpu unlock · simon gpu unlock | Your GeForce runs AI at half speed. This fixes it for 20/30/… |
| [unclebob/ub-mode](https://github.com/unclebob/ub-mode) | 4869 | 1069 | +916 | 4.6 | — | ub mode · unclebob ub mode · robert ub mode |  |
| [rddmwmddr/android-ad-cleaner](https://github.com/rddmwmddr/android-ad-cleaner) | 4810 | 803 | +374 | 6 | — | android ad cleaner · rddmwmddr android ad cleaner | 关掉国产安卓手机系统里的广告、热搜、资讯推荐和营销推送。不 root，可还原，支持 AI 智能体一键执行。 |
| [pengchujin/aerial-tv](https://github.com/pengchujin/aerial-tv) | 7829 | 796 | +334 | 9.8 | — | aerial tv · pengchujin aerial tv | 给国产电视的一块干净桌面：参照 tvOS 设计的开源 Android TV 桌面，没有广告，开机自动接管。A tvOS-… |
| [interplains/Zero-Breach-Toolkit](https://github.com/interplains/Zero-Breach-Toolkit) | 3663 | 794 | +740 | 4.6 | — | zero breach toolkit · interplains zero breach toolkit · archivegenocide zero breach toolkit | Free, open-source, offline checks for traces of known mercen… |
| [JustAResearcher/gpu-unlock-ada](https://github.com/JustAResearcher/gpu-unlock-ada) | 4535 | 714 | +92 | 6.3 | [3](https://news.ycombinator.com/item?id=50223787) | gpu unlock ada · justaresearcher gpu unlock ada · tim gpu unlock ada | GPU tensor unlock source for RTX 4090 and experimental RTX 4… |
| 🆕 [valentderah/totk-pc-recomp](https://github.com/valentderah/totk-pc-recomp) | 696 | 696 | — | 1 | — | totk pc recomp · valentderah totk pc recomp · valiantsin totk pc recomp | Static recompilation of The Legend of Zelda: Tears of the Ki… |
| [designfuchen/word-atlas](https://github.com/designfuchen/word-atlas) | 3269 | 671 | +163 | 4.9 | — | word atlas · designfuchen word atlas · boxin word atlas | 词光 · Word Atlas — Illustrated IELTS vocabulary with 7,298 wo… |
| [Jakeschincariol/day-trader-skill](https://github.com/Jakeschincariol/day-trader-skill) | 3312 | 344 | +605 | 9.6 | — | day trader skill · jakeschincariol day trader skill · jake day trader skill | 11 Claude skills for day trading: scan thousands of charts,… |
| [ly05010419/MacNativeGames](https://github.com/ly05010419/MacNativeGames) | 6471 | 522 | +151 | 12.4 | — | macnativegames · ly05010419 macnativegames · yong macnativegames | Play your own Tears of the Kingdom and Breath of the Wild na… |
| [simbasjungles/free-my-tv](https://github.com/simbasjungles/free-my-tv) | 5408 | 519 | +141 | 10.4 | [1](https://news.ycombinator.com/item?id=50220596) | free my tv · simbasjungles free my tv · simba free my tv | A fast, ad-free home screen for Google TV, LG webOS and Sams… |
| [smithjohn78390/tongjiang-lab](https://github.com/smithjohn78390/tongjiang-lab) | 1013 | 497 | +385 | 2 | — | tongjiang lab · smithjohn78390 tongjiang lab | Free interactive 3D science lessons for high school · 铜匠实验室… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 92.2 | 🆕 🟢 窗口内 | [SoMarkAI/OXR](https://github.com/SoMarkAI/OXR) | Python | 2548 | +291 | +2163 | +385 | `···▁▂▂▂▃▃▅█▄▄·` | 25 | [3](https://news.ycombinator.com/item?id=50183506) | — |
| 2 | 88.3 | 🟢 窗口内 | [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) | TypeScript | 1566 | +186 | +1565 | +1 | `····▁·····██▃·` | 8 | — | — |
| 3 | 88.2 | 🟢 窗口内 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | Rust | 1743 | +43 | +1552 | +191 | `··▁▃▁▁▁▂▃▆█▂▁·` | 10 | — | — |
| 4 | 87.2 | 🟢 窗口内 | [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) | Python | 1427 | +54 | +1427 | +0 | `·······▅█▅▂▁▂·` | 7 | — | — |
| 5 | 85.8 | 🟢 窗口内 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 1277 | +91 | +1277 | +0 | `········█▄▄▂▂·` | 4 | — | — |
| 6 | 85.1 | 🟢 窗口内 | [l0ng-ai/openidea](https://github.com/l0ng-ai/openidea) | TypeScript | 1258 | +484 | +1200 | +58 | `·····▂▁▂▂▁▄█▇·` | 8 | — | — |
| 7 | 84.7 | 🟢 窗口内 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2325 | +48 | +1163 | +1162 | `····▁▁█▅▂▂▂▁▁·` | 8 | [3](https://news.ycombinator.com/item?id=50207695) | — |
| 8 | 83.1 | 🟢 窗口内 | [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) | Kotlin | 1118 | +89 | +1014 | +104 | `·····▁▄█▇▄▅▄▃·` | 8 | — | — |
| 9 | 63.6 | 🟡 在降温 | [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) | Python | 1601 | +1 | +578 | +955 | `▃▅▃▄▃▃▇█▅▂▁·▁·` | 14 | — | — |
| 10 | 62.5 | 🟡 在降温 | [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) | Python | 1596 | +44 | +519 | +996 | `▅█▆▅▃▂█▅▆▃▃▂▂·` | 13 | [1](https://news.ycombinator.com/item?id=50177079) | — |
| 11 | 60.3 | 🟡 在降温 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) | Go | 2239 | +91 | +414 | +621 | `▂▃▆███▆▄▄▅▆▄▆·` | 21 | — | — |
| 12 | 58.3 | 🟡 在降温 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 1895 | +28 | +340 | +1555 | `·█▆▃▃▃▂▂▂▂▂▁▁·` | 11 | — | — |
| 13 | 56.2 | 🟡 在降温 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 2167 | +34 | +276 | +502 | `█▇▆▅▅▄▃▃▅▄▄▃▃·` | 19 | — | — |
| 14 | 53.9 | 🟡 在降温 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 1971 | +45 | +218 | +697 | `▁▁▁█▃▂▂▁▁▂▂▂▂·` | 17 | — | — |
| 15 | 51.6 | 🟡 在降温 | [ELY-Open-Source/ElyOffice](https://github.com/ELY-Open-Source/ElyOffice) | Rust | 1107 | +18 | +173 | +934 | `··▇█▃▄▂▂▂▂▂▁▁·` | 10 | — | — |
| 16 | 46.7 | 🔴 先核对 | [t3dotgg/tstack](https://github.com/t3dotgg/tstack) | Python | 2414 | +125 | +2406 | +8 | `······▁▁▁█▃▂▂·` | 6 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 43.9 | 🔴 先核对 | [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | TypeScript | 1501 | +159 | +1501 | +0 | `········▂█▄▃▂·` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 41.2 | 🆕 🔴 先核对 | [qybaihe/bla](https://github.com/qybaihe/bla) | TypeScript | 953 | — | +953 | +0 | `········▁▁▂▁█·` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 40.9 | 💤 不活跃 | [yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) | Python | 1832 | +0 | +914 | +581 | `▂▁▂▂▂▃▃█▇·▁···` | 17 | — | — |
| 20 | 39.8 | 🔴 先核对 | [mizorewww/gdirect](https://github.com/mizorewww/gdirect) | Rust | 765 | +7 | +765 | +0 | `·······▁█▂▁▁▁·` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 564 | 30 | 49155 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[SoMarkAI/OXR](https://github.com/SoMarkAI/OXR)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) |
| `mcp` | 297 | 30 | 32951 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) |
| `rust` | 195 | 30 | 29450 | [oxc-project/tsrs](https://github.com/oxc-project/tsrs)、[academa-labs/manimgx](https://github.com/academa-labs/manimgx)、[xevrion/hatchzip](https://github.com/xevrion/hatchzip) |
| `local-first` | 66 | 30 | 9751 | [chenxiachan/textfold](https://github.com/chenxiachan/textfold)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch)、[aboard-io/tinylittleoffice](https://github.com/aboard-io/tinylittleoffice) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 22 | 26419 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill) |
| `ai-agents` | 20 | 15945 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering) |
| `agent-skills` | 15 | 20920 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `codex` | 15 | 17067 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) |
| `llm` | 15 | 12433 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[Harvil1/codeAgent](https://github.com/Harvil1/codeAgent) |
| `mcp-server` | 12 | 10801 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist) |
| `ai-agent` | 9 | 7482 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `claude-skills` | 8 | 12094 | [oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `developer-tools` | 8 | 7377 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze)、[l0ng-ai/openidea](https://github.com/l0ng-ai/openidea)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) |
| `macos` | 8 | 5797 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[kitlangton/scrawl](https://github.com/kitlangton/scrawl)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch) |
| `self-hosted` | 7 | 5895 | [marclou/mailcheap](https://github.com/marclou/mailcheap)、[rociiu/talorys](https://github.com/rociiu/talorys)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) |
| `coding-agents` | 7 | 5289 | [reason-machines/reason-network](https://github.com/reason-machines/reason-network)、[openqodex/openqodex](https://github.com/openqodex/openqodex)、[feder-cr/git-ai](https://github.com/feder-cr/git-ai) |

**语言分布**：Rust 31 · Python 29 · TypeScript 19 · JavaScript 12 · Go 3 · HTML 3 · Swift 2 · Astro 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. 🆕 [SoMarkAI/OXR](https://github.com/SoMarkAI/OXR) · 🟢 窗口内 · 92.2 分

> An open-source document parsing model with SOTA accuracy and speed, using an RSI loop during post-training.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2548 | +2163 | +385 | 174 | 22 | Python | — | 10-05（25 天前） | 5 天前 |

- **近 14 天每天新增**：`···▁▂▂▂▃▃▅█▄▄·` 0 0 0 24 101 129 131 218 181 452 732 308 272 0
- **势头**：比前 7 天快 5.6 倍，在加速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=50183506)）
- **topics**：`agent` `llm-tools` `ocr` `rsi` `vlm` `vlm-ocr`
- **主页**：<https://somark.ai/oxr>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) · 🟢 窗口内 · 88.3 分

> An Open Source template for a proactive AI agent that gets your work done and keeps you in the loop.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1566 | +1565 | +1 | 199 | 11 | TypeScript | MIT | 10-21（8 天前） | 1 天前 |

- **近 14 天每天新增**：`····▁·····██▃·` 0 0 0 0 1 0 0 0 0 0 704 693 168 0
- **势头**：比前 7 天快 1565.0 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<copilotkit.ai/openduet>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [indexable-inc/blaze](https://github.com/indexable-inc/blaze) · 🟢 窗口内 · 88.2 分

> Incremental rust builds up to 92x faster than cargo/rustc

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1743 | +1552 | +191 | 60 | 434 | Rust | Apache-2.0 | 10-19（10 天前） | 今天 |

- **近 14 天每天新增**：`··▁▃▁▁▁▂▃▆█▂▁·` 0 0 17 151 14 5 4 104 156 455 675 126 36 0
- **势头**：比前 7 天快 8.1 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`cargo` `compiler` `cranelift` `developer-tools` `hot-reload` `incremental-compilation` `jit` `live-coding` `rust` `rust-analyzer`
- **主页**：<https://ix.dev/blaze>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) · 🟢 窗口内 · 87.2 分

> Agent Skills that teach coding agents to write, review, and port idiomatic Rust, plus a tested clippy config. Works with Claude Code, Codex, Copilot, Cursor, and Gemini CLI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1427 | +1427 | +0 | 70 | 4 | Python | MIT | 10-23（7 天前） | 1 天前 |

- **近 14 天每天新增**：`·······▅█▅▂▁▂·` 0 0 0 0 0 0 0 303 582 357 89 41 55 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `claude-code` `claude-plugin` `claude-skills` `clippy` `code-review` `coding-agent` `cursor` `rust` `style-guide`
- **主页**：<https://www.beautifulrust.dev>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) · 🟢 窗口内 · 85.8 分

> Evidence-first genealogy skill for AI agents (Codex, Claude Code): church books, civil, military, deportation and repression records across the former USSR. Replies in your language.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1277 | +1277 | +0 | 133 | 4 | Python | MIT | 10-25（4 天前） | 今天 |

- **近 14 天每天新增**：`········█▄▄▂▂·` 0 0 0 0 0 0 0 0 594 229 255 113 86 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `archives` `claude-code` `codex` `family-history` `familysearch` `genealogy` `ussr`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [l0ng-ai/openidea](https://github.com/l0ng-ai/openidea) · 🟢 窗口内 · 85.1 分

> The IDE you know, rebuilt in Rust. IntelliJ IDEA–style keymap, tool windows and search-everywhere in a fast native app: editor, code insight, debugger, Git, terminal, database and HTTP clients for 60+ languages.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1258 | +1200 | +58 | 118 | 74 | TypeScript | Apache-2.0 | 10-21（8 天前） | 今天 |

- **近 14 天每天新增**：`·····▂▁▂▂▁▄█▇·` 0 0 0 0 0 35 23 46 35 21 191 489 418 0
- **势头**：比前 7 天快 20.7 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`code-editor` `cross-platform` `dap` `database-client` `debugger` `desktop-app` `developer-tools` `git` `http-client` `ide` `intellij` `lsp` `rust` `tauri` `terminal`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [xevrion/hatchzip](https://github.com/xevrion/hatchzip) · 🟢 窗口内 · 84.7 分

> HatchZip is a free, open-source archive extractor for Windows, macOS and Linux that extracts ZIP, 7z, RAR, tar and split archives in place, so it needs free space for the extracted files only. Desktop app and CLI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2325 | +1163 | +1162 | 75 | 9 | Rust | Apache-2.0 | 10-21（8 天前） | 今天 |

- **近 14 天每天新增**：`····▁▁█▅▂▂▂▁▁·` 0 0 0 0 1 23 1138 602 199 101 144 71 46 0
- **势头**：和前 7 天差不多
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=50207695)）
- **topics**：`7z` `7zip` `archive` `archive-extractor` `cli` `crash-safe` `disk-space` `extract` `extractor` `gui` `in-place` `linux` `macos` `rar` `rust` `tar` `unrar` `unzip` `windows` `zip`
- **主页**：<https://hatchzip.dev>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) · 🟢 窗口内 · 83.1 分

> A community-built phone app for Clean Your TV: clean up an Android TV from your phone. No laptop, no coding agent, nothing uninstalled.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1118 | +1014 | +104 | 102 | 2243 | Kotlin | MIT | 10-21（8 天前） | 今天 |

- **近 14 天每天新增**：`·····▁▄█▇▄▅▄▃·` 0 0 0 0 0 1 103 288 246 133 151 114 82 0
- **势头**：比前 7 天快 9.8 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adb` `android-tv` `debloat` `fire-tv` `google-tv` `launcher`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 9. [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) · 🟡 在降温 · 63.6 分

> 麦当劳 MCP 聚会/团餐组织助手 — 基于 Model Context Protocol 的派对预订与团餐规划 CLI/Skill

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1601 | +578 | +955 | 58 | 2 | Python | MIT | 10-15（14 天前） | 2 天前 |

- **近 14 天每天新增**：`▃▅▃▄▃▃▇█▅▂▁·▁·` 96 166 115 133 114 75 256 325 176 59 17 0 1 0
- **势头**：只有前 7 天的 61%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) · 🟡 在降温 · 62.5 分

> Co-op Anything: point your AI agent at any single-player game and play it with friends (online and/or splitscreen!). MCP server and playbook to let you reverse engineer, fix, test, ship and share what it learns.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1596 | +519 | +996 | 222 | 159 | Python | MIT | 10-16（13 天前） | 今天 |

- **近 14 天每天新增**：`▅█▆▅▃▂█▅▆▃▃▂▂·` 131 234 156 124 77 47 227 149 161 67 56 45 41 0
- **势头**：只有前 7 天的 52%，在减速
- **HN**：发过 1 次，最高 1 分（[讨论](https://news.ycombinator.com/item?id=50177079)）
- **主页**：<https://coopanything.app>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [t3dotgg/tstack](https://github.com/t3dotgg/tstack) — 一天进了一半以上的 star，但 HN 上没火过
- [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) — 一天进了一半以上的 star，但 HN 上没火过
- [qybaihe/bla](https://github.com/qybaihe/bla) — 一天进了一半以上的 star，但 HN 上没火过
- [mizorewww/gdirect](https://github.com/mizorewww/gdirect) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 623 | 450 | [Show HN: Steal My Bitcoin](https://stealmybitcoin.com/) | [HN](https://news.ycombinator.com/item?id=50224916) |
| 405 | 82 | [Show HN: TitleArt – Make text like it's 1997](https://titleart.dvy.io/) | [HN](https://news.ycombinator.com/item?id=50238708) |
| 318 | 116 | [Show HN: A Truly Modular Keyboard](https://github.com/notaroomba/keybytes) | [HN](https://news.ycombinator.com/item?id=50228115) |
| 177 | 49 | [Show HN: I put employees inside S&P 500 market-cap bubbles](https://bigwhalehunting.com/workforce/) | [HN](https://news.ycombinator.com/item?id=50232312) |
| 175 | 43 | [Show HN: Hob - Open-source, on device alternative to Claude Cowork and ChatGPT](https://github.com/FrigadeHQ/hob) | [HN](https://news.ycombinator.com/item?id=50246238) |
| 149 | 65 | [Show HN: Encarta 95 Web](https://benwinding.github.io/encarta_95_web/#/article/Art) | [HN](https://news.ycombinator.com/item?id=50218975) |
| 141 | 47 | [Show HN: Corgi, a helpful {agent, terminal} multiplexer](https://corgi.computer/) | [HN](https://news.ycombinator.com/item?id=50214373) |
| 118 | 90 | [Show HN: Auto Dismiss Mac OS "Allow <app> to find devices on local networks?"](https://github.com/johncassil/dontallow) | [HN](https://news.ycombinator.com/item?id=50294506) |
| 80 | 35 | [Show HN: SlideBySide – Present slides without sharing your screen](https://slidebyside.com/) | [HN](https://news.ycombinator.com/item?id=50276883) |
| 77 | 38 | [Show HN: Swurf – Swipe through the real web](https://swurf.org/) | [HN](https://news.ycombinator.com/item?id=50205320) |
| 70 | 57 | [Show HN: We had AI write a wiki from 45k Enron emails, every fact cited](https://www.thisandthat.chat/enron/) | [HN](https://news.ycombinator.com/item?id=50207620) |
| 68 | 27 | [Show HN: Hurston-1 open source TTS that speak Southern American and Afro-English](https://huggingface.co/destined/hurston-1) | [HN](https://news.ycombinator.com/item?id=50227330) |
| 68 | 12 | [Show HN: A proof-of-concept formalization of the IRS federal tax forms](https://github.com/emmilco/us-tax-model) | [HN](https://news.ycombinator.com/item?id=50278678) |
| 66 | 58 | [Show HN: ADRs for AI – Deliberation records for human–AI work, versioned in Git](https://adrs.systems) | [HN](https://news.ycombinator.com/item?id=50227041) |
| 61 | 14 | [Show HN: I Turned DOOM into a Transformer](https://github.com/mottopanikeiku/doomformer) | [HN](https://news.ycombinator.com/item?id=50297697) |
| 60 | 43 | [Show HN: Farol – A risk map of a pull request for the person who approves it](https://github.com/winnin/farol) | [HN](https://news.ycombinator.com/item?id=50231349) |
| 59 | 19 | [Show HN: Autonomous root for Tcl Android TV via CVE-2022-22706](https://gitlab.com/c4psu13/mali-pagecache-root) | [HN](https://news.ycombinator.com/item?id=50220042) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 158 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 118394★ |
| 125 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 21316★ |
| 31 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 8735★ |
| 105 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 29774★ |
| 48 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 34880★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 34798★ |
| 6 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | 💡 [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 710★ |
| 62 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 44071★ |
| 107 | [MOSS-Image Technical Report](https://huggingface.co/papers/2610.23374) | MOSS-Image is an open diffusion transformer that combines high-fidelity synthesis with intent-aware prompt enhancement to generate text-rich… | [OpenMOSS/MOSS-Image](https://github.com/OpenMOSS/MOSS-Image) 2239★ |
| 126 | [Hy-Nomas: Towards Free-form Interactive World Generation](https://huggingface.co/papers/2610.36729) | Hy-Nomas is a video world model that uses causal attention and structured conditioning to generate interactive, multi-turn video segments wi… | 💡 [Tencent-Hunyuan/Hy-Nomas](https://github.com/Tencent-Hunyuan/Hy-Nomas) 388★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 92204★ |
| 23 | [Prism: Dynamic Sparse Attention for Native 2K Joint Video-Audio Generation Model Training](https://huggingface.co/papers/2610.05416) | Prism accelerates native joint video-audio generation at 2K by using dynamic sparse attention guided by local visual variance and audio-visu… | [Tencent-Hunyuan/Prism](https://github.com/Tencent-Hunyuan/Prism) 1517★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 118 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 2852★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 82758★ |
| 26 | [PaddleOCR-VL-1.6: Expanding the Frontier of Document Parsing with Under-Optimized Region Refinement…](https://huggingface.co/papers/2606.03264) | PaddleOCR-VL-1.6 enhances document parsing performance through targeted data optimization and progressive post-training techniques, achievin… | [PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) 91948★ |
| 19 | [Next-Concept Modeling: Fast, Parallel Coarse-to-Fine Text Generation](https://huggingface.co/papers/2610.14162) | Next-Concept Modeling uses hierarchical discrete codes and parallel level-wise generation to accelerate diffusion language models while impr… | [HazyResearch/ncm](https://github.com/HazyResearch/ncm) 1279★ |
| 142 | [DynaFlow: Learning Free-Form Multi-Agent Orchestration](https://huggingface.co/papers/2610.34467) | DynaFlow enables adaptive multi-agent collaboration by letting a main agent synthesize executable workflows that coordinate sub-agents throu… | 💡 [amiya-special/Dynaflow](https://github.com/amiya-special/Dynaflow) 163★ |
| 180 | [SmolDocling: An ultra-compact vision-language model for end-to-end multi-modal document conversion](https://huggingface.co/papers/2503.11576) | SmolDocling is a compact vision-language model that performs end-to-end document conversion with robust performance across various document… | [docling-project/docling](https://github.com/docling-project/docling) 69817★ |
| 259 | [WeVisOne-VL: Unified Visual Perception from Objects to Pixels](https://huggingface.co/papers/2610.31329) | WeVisOne-VL unifies object-level and pixel-level visual perception via structured token prediction, supporting detection, localization, coun… | 💡 [Tencent/WeVisOne-VL](https://github.com/Tencent/WeVisOne-VL) 428★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 12 | [mistral large 4 1t](https://huggingface.co/mistralai/Mistral-Large-4-1T-A52B) | image-text-to-text | 1238 | 1 |
| 42 | [pika h3 flex](https://huggingface.co/Pika-Labs/Pika-H3-Flex) | image-to-video | 123 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 23 | 12 | [London meetup](https://lobste.rs/s/dsrruj) | `event` | [讨论](https://lobste.rs/s/dsrruj/london_meetup) |
| 45 | 25 | [NetBSD adds a new Emacs-like text editor called atto](https://mastodon.sdf.org/@netbsd/117518160563539748) | `editors` `netbsd` | [讨论](https://lobste.rs/s/m6fw0x/netbsd_adds_new_emacs_like_text_editor) |
| 59 | 12 | [What the fox say?](https://entropicthoughts.com/what-the-fox-say) | `games` | [讨论](https://lobste.rs/s/7qaac6/what_fox_say) |
| 29 | 38 | [Shared password manager for families?](https://lobste.rs/s/eccbci) | `ask` `security` | [讨论](https://lobste.rs/s/eccbci/shared_password_manager_for_families) |
| 13 | 1 | [C2PA's eMudhra Moment](https://www.da.vidbuchanan.co.uk/blog/c2pa-four.html) | `cryptography` `security` | [讨论](https://lobste.rs/s/2matgw/c2pa_s_emudhra_moment) |
| 34 | 1 | [My favourite PowerMac is a Nintendo Wii](https://virtuallyfun.com/2026/10/29/my-favourite-powermac-is-a-nintendo-wii/) | `retrocomputing` `reversing` | [讨论](https://lobste.rs/s/siebde/my_favourite_powermac_is_nintendo_wii) |
| 8 | 2 | [If you love a website, back it up](http://blog.mistys-internet.website/post/2026/10/29/if-you-love-a-website-back-it-up/) | `web` | [讨论](https://lobste.rs/s/6ole9g/if_you_love_website_back_it_up) |
| 42 | 5 | [Qwenputer: a fully functioning, deterministic RISC-V CPU inside Qwen3.5](https://divagr.com/blog/qwenputer) | `ai` | [讨论](https://lobste.rs/s/zftely/qwenputer_fully_functioning) |
| 17 | 6 | [Phorge](https://www.phorge.it/) | `php` `vcs` | [讨论](https://lobste.rs/s/tw3rsp/phorge) |
| 77 | 11 | [EMACS turns 50](https://www.technologyreview.com/2026/10/20/1145399/emacs-turns-50/) | `emacs` `historical` | [讨论](https://lobste.rs/s/uimyck/emacs_turns_50) |
| 121 | 26 | [Apple's git still trusts the compromised eMudhra certificates](https://emudhra.we-have-a-problem.com/apple.html) | `cryptography` `mac` | [讨论](https://lobste.rs/s/xybmsj/apple_s_git_still_trusts_compromised) |
| 7 | 0 | [Design the interface for functionality not familiarity](https://lapcatsoftware.com/articles/2026/10/10.html) | `mac` | [讨论](https://lobste.rs/s/qqelq1/design_interface_for_functionality_not) |
| 8 | 6 | [Building NixOS using Nixtamal](https://nixtamal.toast.al/cookbook/nixos-using-nixtamal/) | `nix` | [讨论](https://lobste.rs/s/4x3ten/building_nixos_using_nixtamal) |
| 43 | 6 | [GitLab security incident: attempted exploitation of CVE-2026-97229](https://alpinelinux.org/posts/GitLab-security-incident-CVE-2026-97229.html) | `linux` `security` | [讨论](https://lobste.rs/s/2zsjwt/gitlab_security_incident_attempted) |
| 113 | 11 | [Why Is This Fingerprinting Script Creating Bioweapons?](https://nullpt.rs/fingerprinting-bioweapons) | `reversing` | [讨论](https://lobste.rs/s/gvy5gz/why_is_this_fingerprinting_script) |
| 9 | 5 | [Extremely brief history of PDP computers](https://entropicthoughts.com/history-of-pdp-computers) | `hardware` `historical` | [讨论](https://lobste.rs/s/ldvd3n/extremely_brief_history_pdp_computers) |
| 8 | 9 | [The Web Can't Afford a JavaScript Runtime Monoculture](https://redmonk.com/kholterhoff/2026/10/27/js-runtime-monoculture/) | `javascript` | [讨论](https://lobste.rs/s/x6n380/web_can_t_afford_javascript_runtime) |
| 6 | 1 | [An open format for writing agent-native software requirements](https://slcr.dev/announcements#2026-10-29-slcr-launches) | `building-ai-tooling` `practices` `release` | [讨论](https://lobste.rs/s/nexvnc/open_format_for_writing_agent_native) |
| 5 | 0 | [XSS in yarr RSS reader](https://0x67673068.me/xss-in-yarr/) | `go` `security` `web` | [讨论](https://lobste.rs/s/1r7enm/xss_yarr_rss_reader) |
| 1 | 0 | [Pidgin 3.0 Alpha 4 2.98.0 has been released](https://discourse.imfreedom.org/t/pidgin-3-0-alpha-4-2-98-0-has-been-released/445) | `release` | [讨论](https://lobste.rs/s/qsvspv/pidgin_3_0_alpha_4_2_98_0_has_been_released) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 76 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 11 | 6 | 54% | — |
| 🔴 先核对 | 10 | 5 | 50% | — |
| 🟡 在降温 | 5 | 0 | 0% | — |
| 🔵 已被发现 | 2 | 0 | 0% | — |
| 🟢 窗口内 | 7 | 4 | 57% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [Graphicle-AI/graphicle](https://github.com/Graphicle-AI/graphicle) | 2026-10-16 | 🔴 先核对 | 176 | 470 | 48 | 没起来 |
| [Supermedo/uncharted_pc](https://github.com/Supermedo/uncharted_pc) | 2026-10-16 | 🚀 爆发 | 726 | 2085 | 0 | ✅ 起来了 |
| [ahwootech/BRUTAL](https://github.com/ahwootech/BRUTAL) | 2026-10-16 | 🚀 爆发 | 1229 | 2301 | 9 | 没起来 |
| [chenglou/handwired](https://github.com/chenglou/handwired) | 2026-10-16 | 🚀 爆发 | 1160 | 2067 | 3 | 没起来 |
| [feder-cr/open_scion](https://github.com/feder-cr/open_scion) | 2026-10-16 | 🚀 爆发 | 739 | 1018 | 0 | 没起来 |
| [outcrawlai/scout](https://github.com/outcrawlai/scout) | 2026-10-16 | 🔴 先核对 | 840 | 947 | 0 | 没起来 |

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
