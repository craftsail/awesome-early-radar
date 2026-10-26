# early-radar 选题雷达 · 2026-10-26

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 106 个，细查前 20 个 · 比上次 = 和 2026-10-25 那次比 · 生成于 2026-10-26 04:19 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 1 个 · Show HN ✅ 23 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 0 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 10 个 · 🟡 在降温 6 个 · 🔵 已被发现 1 个 · 💤 不活跃 0 个 · 🔴 先核对 3 个
- **今天新出现 2 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) 平均每天 +4058，见 [爆发](#爆发)
- **最值得今天试的**：
  - [amosblomqvist/learnharness](https://github.com/amosblomqvist/learnharness) — Agent harness for learning difficult things.（近 7 天 +1735，比前 7 天快 115.7 倍，在加速）
  - [aicodeking/leanrea](https://github.com/aicodeking/leanrea) — One 8 KB skill that replaces REA (Reverse Engineer Anything)…（近 7 天 +1592，比前 7 天快 1.5 倍，在加速）
  - [yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) — 麦麦碳账本 · 基于麦当劳 MCP 的个人餐饮碳足迹估算与减排模拟器 / Personal dining carbon…（近 7 天 +1435，比前 7 天快 4.7 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 27 个（star 合计 30172），代表：[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[openfilm/openfilm](https://github.com/openfilm/openfilm)、[Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：2 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: SimCity, but with Permits](https://permit.petercai.com/) — 938 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) | 35867 | 4058 | +3652 | 8.8 | [6](https://news.ycombinator.com/item?id=50164485) | cleanyourtv · gathin23 cleanyourtv · gathin cleanyourtv | Debloat any Android or Google TV over Wi-Fi and get an Apple… |
| [Zagitta/gpu-unlock](https://github.com/Zagitta/gpu-unlock) | 7279 | 897 | +3912 | 8.1 | [338](https://news.ycombinator.com/item?id=50219700) | gpu unlock · zagitta gpu unlock · simon gpu unlock | Unlock FP/BF16 instruction issue rate on Nvidia 3000's cards… |
| [deepseek-ai/DeepInfer](https://github.com/deepseek-ai/DeepInfer) | 22556 | 2289 | +622 | 9.9 | [2351](https://news.ycombinator.com/item?id=50163277) | deepinfer · deepseek-ai deepinfer · deepseek deepinfer | DeepInfer: High-performance, large-scale inference framework… |
| [JustAResearcher/gpu-unlock-ada](https://github.com/JustAResearcher/gpu-unlock-ada) | 2940 | 1276 | +1935 | 2.3 | [3](https://news.ycombinator.com/item?id=50223787) | gpu unlock ada · justaresearcher gpu unlock ada · tim gpu unlock ada | GPU tensor unlock source for RTX 4090 and experimental RTX 4… |
| [seedds/nxnative](https://github.com/seedds/nxnative) | 4489 | 346 | +1345 | 13 | — | nxnative · seedds nxnative | Switch games running natively on iPhone, iPad and Mac: an NS… |
| [pengchujin/aerial-tv](https://github.com/pengchujin/aerial-tv) | 5233 | 903 | +783 | 5.8 | — | aerial tv · pengchujin aerial tv | 给国产电视的一块干净桌面：参照 tvOS 设计的开源 Android TV 桌面，没有广告，开机自动接管。A tvOS-… |
| 🆕 [designfuchen/word-atlas](https://github.com/designfuchen/word-atlas) | 816 | 816 | — | 1 | — | word atlas · designfuchen word atlas · boxin word atlas | 词光 · 一词一画，点亮雅思 — 7,298 IELTS words, each with an original il… |
| [simbasjungles/free-my-tv](https://github.com/simbasjungles/free-my-tv) | 4647 | 730 | +315 | 6.4 | [1](https://news.ycombinator.com/item?id=50220596) | free my tv · simbasjungles free my tv · simba free my tv | A fast, ad-free home screen for Google TV, LG webOS and Sams… |
| [ly05010419/MacNativeGames](https://github.com/ly05010419/MacNativeGames) | 5527 | 662 | +276 | 8.4 | — | macnativegames · ly05010419 macnativegames · yong macnativegames | Play your own Tears of the Kingdom and Breath of the Wild na… |
| [amosblomqvist/learnharness](https://github.com/amosblomqvist/learnharness) | 1750 | 187 | +633 | 9.4 | — | learnharness · amosblomqvist learnharness · eero learnharness | Agent harness for learning difficult things. |
| 🆕 [mizorewww/gdirect](https://github.com/mizorewww/gdirect) | 601 | 601 | — | 1 | — | gdirect · mizorewww gdirect | Rust Google Drive direct downloader using pinned libaria2 |
| 🆕 [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | 548 | 548 | — | 1 | — | ex ussr kinship research · denissergeevitch ex ussr kinship research · denis ex ussr kinship research | Evidence-first genealogy skill for AI agents (Codex, Claude… |
| 🆕 [Jakeschincariol/day-trader-skill](https://github.com/Jakeschincariol/day-trader-skill) | 1699 | 304 | +545 | 5.6 | — | day trader skill · jakeschincariol day trader skill · jake day trader skill | 11 Claude skills for day trading: scan thousands of charts,… |
| 🆕 [rddmwmddr/android-ad-cleaner](https://github.com/rddmwmddr/android-ad-cleaner) | 1019 | 523 | — | 1.9 | — | android ad cleaner · rddmwmddr android ad cleaner | 关掉国产安卓手机系统里的广告、热搜、资讯推荐和营销推送。不 root，可还原，支持 AI 智能体一键执行。 |
| [xiaoyang111222/cn-math-taxonomy](https://github.com/xiaoyang111222/cn-math-taxonomy) | 3819 | 489 | +495 | 7.8 | — | cn math taxonomy · xiaoyang111222 cn math taxonomy · aifeng cn math taxonomy | 数学（小学到高中）、英语（三年级到高中）、初中物理的知识图谱：1644 个知识点、2403 条先修边、6723 道题，对… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 89.5 | 🟢 窗口内 | [amosblomqvist/learnharness](https://github.com/amosblomqvist/learnharness) | TypeScript | 1750 | +633 | +1735 | +15 | `···▁▁▁▁▁▁▁▃█▆·` | 9 | — | — |
| 2 | 88.5 | 🟢 窗口内 | [aicodeking/leanrea](https://github.com/aicodeking/leanrea) | Python | 2621 | +395 | +1592 | +1029 | `···▁█▄▆▃▃▂█▇▆·` | 9 | — | — |
| 3 | 87.2 | 🟢 窗口内 | [yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) | Python | 1942 | +375 | +1435 | +303 | `·▁▂▂▂▁▂▂▂▂▃█▆·` | 13 | — | — |
| 4 | 84.5 | 🟢 窗口内 | [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) | Python | 1599 | +141 | +1146 | +453 | `··▁▂▃▄▃▃▃▂▆█▄·` | 10 | — | — |
| 5 | 80.6 | 🟢 窗口内 | [Sam-Hui-dot/mcd-budget-meal](https://github.com/Sam-Hui-dot/mcd-budget-meal) | HTML | 1441 | +102 | +826 | +473 | `▂·▃▃▃▅▄▃▃▃█▆▅·` | 14 | — | — |
| 6 | 80 | 🟢 窗口内 | [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) | Python | 1384 | +193 | +782 | +602 | `···▃▅█▆▅▃▂█▅▆·` | 9 | [1](https://news.ycombinator.com/item?id=50177079) | — |
| 7 | 79.2 | 🟢 窗口内 | [reason-machines/reason-network](https://github.com/reason-machines/reason-network) | Rust | 1242 | +45 | +734 | +507 | `···▄▆▅▃█▆▅▃▂▂·` | 9 | — | — |
| 8 | 78.8 | 🟢 窗口内 | [ELY-Open-Source/ElyOffice](https://github.com/ELY-Open-Source/ElyOffice) | Rust | 1002 | +29 | +710 | +292 | `······▇█▃▄▂▂▂·` | 6 | — | — |
| 9 | 78 | 🟢 窗口内 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 1794 | +19 | +663 | +424 | `▄▃▂▂▁▁▁█▃▂▂▁▁·` | 13 | — | — |
| 10 | 76.8 | 🟢 窗口内 | [torrentplayer/torrentplayer](https://github.com/torrentplayer/torrentplayer) | Rust | 603 | +67 | +603 | +0 | `········██▄▄▃·` | 5 | — | — |
| 11 | 70.6 | 🟡 在降温 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) | Python | 2810 | +164 | +1162 | +1648 | `··▂▄▄▄█▅▂▃▄▂▃·` | 10 | — | — |
| 12 | 65 | 🟡 在降温 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 1684 | +80 | +665 | +1019 | `·····█▆▃▃▃▂▂▂·` | 7 | — | — |
| 13 | 63.4 | 🟡 在降温 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) | Go | 1925 | +49 | +565 | +683 | `█▁▁▁▁▂▂▃▃▃▂▂▂·` | 17 | — | — |
| 14 | 57.2 | 🟡 在降温 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 1991 | +67 | +305 | +1313 | `█▄▃▃▃▂▂▂▂▂▁▁▂·` | 15 | — | — |
| 15 | 55.1 | 🟡 在降温 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) | Python | 2550 | +49 | +247 | +384 | `▃▂▂█▇▄▅▅▃▃▃▅▃·` | 25 | — | — |
| 16 | 54.5 | 🟡 在降温 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | Python | 2131 | +40 | +232 | +875 | `▅▄█▆▄▄▃▃▂▂▂▂▂·` | 20 | [10](https://news.ycombinator.com/item?id=50037852) | — |
| 17 | 45.5 | 🔴 先核对 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 1956 | +215 | +1956 | +0 | `········▁▁█▅▂·` | 4 | [3](https://news.ycombinator.com/item?id=50207695) | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 43.7 | 🔵 已被发现 | [openfilm/openfilm](https://github.com/openfilm/openfilm) | TypeScript | 2857 | +229 | +1465 | +1152 | `▂▂▂▅▆▅█▆▆▇▅▆▅·` | 21 | [244](https://news.ycombinator.com/item?id=44428438) | — |
| 19 | 40.3 | 🆕 🔴 先核对 | [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) | Python | 824 | — | +824 | +0 | `···········▅█·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 38.4 | 🆕 🔴 先核对 | [mizorewww/gdirect](https://github.com/mizorewww/gdirect) | Rust | 601 | — | +601 | +0 | `···········▁█·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 528 | 30 | 46191 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[openfilm/openfilm](https://github.com/openfilm/openfilm)、[Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) |
| `mcp` | 264 | 30 | 33518 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[aicodeking/leanrea](https://github.com/aicodeking/leanrea)、[yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) |
| `rust` | 175 | 30 | 25290 | [oxc-project/tsrs](https://github.com/oxc-project/tsrs)、[ludovic111/horizon](https://github.com/ludovic111/horizon)、[academa-labs/manimgx](https://github.com/academa-labs/manimgx) |
| `local-first` | 56 | 30 | 9784 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[chenxiachan/textfold](https://github.com/chenxiachan/textfold)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 27 | 30172 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[openfilm/openfilm](https://github.com/openfilm/openfilm)、[Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) |
| `ai-agents` | 20 | 14601 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering) |
| `codex` | 18 | 19914 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[openfilm/openfilm](https://github.com/openfilm/openfilm)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) |
| `llm` | 16 | 11770 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[Harvil1/codeAgent](https://github.com/Harvil1/codeAgent) |
| `agent-skills` | 15 | 16839 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `mcp-server` | 13 | 9990 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `ai-agent` | 11 | 8429 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `claude-skills` | 10 | 10883 | [oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill) |
| `developer-tools` | 10 | 8073 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai)、[hanzohanzhe/Grandet](https://github.com/hanzohanzhe/Grandet) |
| `macos` | 9 | 5451 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[kitlangton/scrawl](https://github.com/kitlangton/scrawl)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch) |
| `coding-agents` | 7 | 9372 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[openfilm/openfilm](https://github.com/openfilm/openfilm)、[reason-machines/reason-network](https://github.com/reason-machines/reason-network) |
| `typescript` | 7 | 7686 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust)、[rociiu/talorys](https://github.com/rociiu/talorys) |

**语言分布**：Python 31 · Rust 29 · TypeScript 19 · JavaScript 11 · Go 3 · HTML 3 · Swift 2 · Astro 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [amosblomqvist/learnharness](https://github.com/amosblomqvist/learnharness) · 🟢 窗口内 · 89.5 分

> Agent harness for learning difficult things.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1750 | +1735 | +15 | 306 | 127 | TypeScript | AGPL-3.0 | 10-16（9 天前） | 今天 |

- **近 14 天每天新增**：`···▁▁▁▁▁▁▁▃█▆·` 0 0 0 1 4 4 6 3 2 7 289 852 582 0
- **势头**：比前 7 天快 115.7 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<learnharness.ai>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [aicodeking/leanrea](https://github.com/aicodeking/leanrea) · 🟢 窗口内 · 88.5 分

> One 8 KB skill that replaces REA (Reverse Engineer Anything): plain CLI tools, no MCP. Benchmarked: 38% faster, 35% cheaper.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2621 | +1592 | +1029 | 398 | 7 | Python | MIT | 10-17（9 天前） | 6 天前 |

- **近 14 天每天新增**：`···▁█▄▆▃▃▂█▇▆·` 0 0 0 26 463 219 321 164 115 96 469 394 354 0
- **势头**：比前 7 天快 1.5 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) · 🟢 窗口内 · 87.2 分

> 麦麦碳账本 · 基于麦当劳 MCP 的个人餐饮碳足迹估算与减排模拟器 | Personal dining carbon footprint estimator powered by McDonald's MCP

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1942 | +1435 | +303 | 43 | 0 | Python | MIT | 10-12（13 天前） | 12 天前 |

- **近 14 天每天新增**：`·▁▂▂▂▁▂▂▂▂▃█▆·` 0 4 67 63 46 33 90 78 94 119 130 572 442 0
- **势头**：比前 7 天快 4.7 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) · 🟢 窗口内 · 84.5 分

> 麦当劳 MCP 聚会/团餐组织助手 — 基于 Model Context Protocol 的派对预订与团餐规划 CLI/Skill

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1599 | +1146 | +453 | 64 | 2 | Python | MIT | 10-15（10 天前） | 1 天前 |

- **近 14 天每天新增**：`··▁▂▃▄▃▃▃▂▆█▄·` 0 0 15 53 96 169 120 134 116 76 259 381 180 0
- **势头**：比前 7 天快 2.5 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [Sam-Hui-dot/mcd-budget-meal](https://github.com/Sam-Hui-dot/mcd-budget-meal) · 🟢 窗口内 · 80.6 分

> 麦麦预算餐：基于麦当劳 MCP 的真实核价、预算比较与餐品替换 Skill

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1441 | +826 | +473 | 44 | 0 | HTML | — | 10-11（14 天前） | 1 天前 |

- **近 14 天每天新增**：`▂·▃▃▃▅▄▃▃▃█▆▅·` 33 0 78 56 88 125 93 86 67 88 248 192 145 0
- **势头**：比前 7 天快 1.7 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`mcdonalds` `mcp` `python` `skill` `workbuddy`
- **主页**：<https://sam-hui-dot.github.io/mcd-budget-meal/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) · 🟢 窗口内 · 80 分

> Co-op Anything: point your AI agent at any single-player game and play it with friends (online and/or splitscreen!). MCP server and playbook to let you reverse engineer, fix, test, ship and share what it learns.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1384 | +782 | +602 | 176 | 141 | Python | MIT | 10-16（9 天前） | 今天 |

- **近 14 天每天新增**：`···▃▅█▆▅▃▂█▅▆·` 0 0 0 81 131 234 156 124 77 47 227 150 157 0
- **势头**：比前 7 天快 1.3 倍，在加速
- **HN**：发过 1 次，最高 1 分（[讨论](https://news.ycombinator.com/item?id=50177079)）
- **主页**：<https://coopanything.app>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [reason-machines/reason-network](https://github.com/reason-machines/reason-network) · 🟢 窗口内 · 79.2 分

> Reason Network: your team's coding agents, talking to each other. The engine behind `reason network`.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1242 | +734 | +507 | 106 | 10 | Rust | Apache-2.0 | 10-16（9 天前） | 今天 |

- **近 14 天每天新增**：`···▄▆▅▃█▆▅▃▂▂·` 0 0 0 108 179 155 65 268 184 137 60 45 40 0
- **势头**：比前 7 天快 1.4 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`coding-agents` `iroh` `mcp` `peer-to-peer` `reason`
- **主页**：<https://reasonmachines.com>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [ELY-Open-Source/ElyOffice](https://github.com/ELY-Open-Source/ElyOffice) · 🟢 窗口内 · 78.8 分

> Ely Office: offline-first desktop apps in Rust and GPUI

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1002 | +710 | +292 | 65 | 13 | Rust | MIT | 10-19（6 天前） | 今天 |

- **近 14 天每天新增**：`······▇█▃▄▂▂▂·` 0 0 0 0 0 0 292 357 99 142 50 33 29 0
- **势头**：比前 7 天快 2.4 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://office.elygpui.com>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 9. [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) · 🟢 窗口内 · 78 分

> Daily radar for new AI terms: names of new models, products and repos, caught on X, Hugging Face, GitHub and sitemaps before keyword tools list them.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1794 | +663 | +424 | 550 | 2 | Python | MIT | 10-12（13 天前） | 今天 |

- **近 14 天每天新增**：`▄▃▂▂▁▁▁█▃▂▂▁▁·` 174 91 55 31 21 26 26 409 93 86 36 20 19 0
- **势头**：比前 7 天快 1.6 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai` `aisa` `claude-code` `claude-skills` `google-trends` `keyword-research` `mcp` `mcp-server` `seo` `trends`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 10. [torrentplayer/torrentplayer](https://github.com/torrentplayer/torrentplayer) · 🟢 窗口内 · 76.8 分

> Stream any torrent, video or audio, and skip to any moment in about a second. Free, open-source desktop app for Windows, macOS and Linux. No servers, no accounts, no telemetry.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 603 | +603 | +0 | 9 | 6 | Rust | Apache-2.0 | 10-20（5 天前） | 1 天前 |

- **近 14 天每天新增**：`········██▄▄▃·` 0 0 0 0 0 0 0 0 183 189 78 91 62 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`audio-player` `bittorrent` `cross-platform` `desktop-app` `media-player` `p2p` `rust` `streaming` `svelte` `tauri` `torrent` `video-player`
- **主页**：<https://torrentstream.io>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [xevrion/hatchzip](https://github.com/xevrion/hatchzip) — 一天进了一半以上的 star，但 HN 上没火过
- [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) — 一天进了一半以上的 star，但 HN 上没火过
- [mizorewww/gdirect](https://github.com/mizorewww/gdirect) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 938 | 425 | [Show HN: SimCity, but with Permits](https://permit.petercai.com/) | [HN](https://news.ycombinator.com/item?id=50170593) |
| 595 | 440 | [Show HN: Steal My Bitcoin](https://stealmybitcoin.com/) | [HN](https://news.ycombinator.com/item?id=50224916) |
| 234 | 91 | [Show HN: OnKey – I'm a bad singer, so I built an app to show where I'm off-key](https://github.com/dsmurrell/onkey) | [HN](https://news.ycombinator.com/item?id=50195488) |
| 188 | 13 | [Show HN: VoidAccess – open-source dark web OSINT, from query to a graph](https://github.com/KatrielMoses/voidaccess) | [HN](https://news.ycombinator.com/item?id=50167286) |
| 171 | 47 | [Show HN: I put employees inside S&P 500 market-cap bubbles](https://bigwhalehunting.com/workforce/) | [HN](https://news.ycombinator.com/item?id=50232312) |
| 158 | 113 | [Show HN: Qwen3-4B with the AI writing tics trained out](https://100toolkit.com/blog/deslop-model/) | [HN](https://news.ycombinator.com/item?id=50151928) |
| 138 | 46 | [Show HN: Corgi, a helpful {agent, terminal} multiplexer](https://corgi.computer/) | [HN](https://news.ycombinator.com/item?id=50214373) |
| 126 | 36 | [Show HN: Uberblok – an interactive museum of ZFS internals](https://uberblok.storagebits.workers.dev/) | [HN](https://news.ycombinator.com/item?id=50180257) |
| 114 | 34 | [Show HN: Omnara – Open-source alternative to Claude Managed Agents](https://github.com/omnara-ai/omnara) | [HN](https://news.ycombinator.com/item?id=50183892) |
| 110 | 66 | [Show HN: Death Plan Switch, a self-hosted dead man's switch for solo devs](https://deathplanswitch.com/) | [HN](https://news.ycombinator.com/item?id=50161408) |
| 109 | 79 | [Show HN: Making a smart TV dumb and then smart](https://github.com/anubhavmalhotra/r2d2-tv) | [HN](https://news.ycombinator.com/item?id=50202865) |
| 104 | 31 | [Show HN: Sumi.css – CSS Framework](https://github.com/vladocar/Sumi.css) | [HN](https://news.ycombinator.com/item?id=50180039) |
| 81 | 20 | [Show HN: Impossible Machines: declaratively program the physical world](https://www.impossiblemachines.xyz) | [HN](https://news.ycombinator.com/item?id=50202746) |
| 80 | 46 | [Show HN: UI micro interactions prompts for AI](https://www.typeui.sh/micro-interactions) | [HN](https://news.ycombinator.com/item?id=50199290) |
| 76 | 35 | [Show HN: Swurf – Swipe through the real web](https://swurf.org/) | [HN](https://news.ycombinator.com/item?id=50205320) |
| 72 | 54 | [Show HN: Jev Cards, Can you beat a vision model at a picture quiz?](https://jevcards.com) | [HN](https://news.ycombinator.com/item?id=50167617) |
| 70 | 56 | [Show HN: We had AI write a wiki from 45k Enron emails, every fact cited](https://www.thisandthat.chat/enron/) | [HN](https://news.ycombinator.com/item?id=50207620) |
| 69 | 44 | [Show HN: KiviDB, a faster Redis-compatible memory database and vector cache](https://github.com/kividbio/kividb) | [HN](https://news.ycombinator.com/item?id=50152541) |
| 66 | 9 | [Show HN: Penmentor – Claude marks up your handwritten math like a teacher](https://github.com/AbdullahAlhariri/penmentor) | [HN](https://news.ycombinator.com/item?id=50167604) |
| 61 | 55 | [Show HN: I built a task system to handle the drudgery so I could focus on tasks](https://3anddoneapp.com/try) | [HN](https://news.ycombinator.com/item?id=50151980) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 123 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 19629★ |
| 154 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 114817★ |
| 62 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 43751★ |
| 30 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 7208★ |
| 103 | [MOSS-Image Technical Report](https://huggingface.co/papers/2610.23374) | MOSS-Image is an open diffusion transformer that combines high-fidelity synthesis with intent-aware prompt enhancement to generate text-rich… | [OpenMOSS/MOSS-Image](https://github.com/OpenMOSS/MOSS-Image) 1855★ |
| 120 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 2582★ |
| 81 | [StartLux-Decision: AutoThink Decision Models with Reinforcement Learning for Calibrated Deliberative…](https://huggingface.co/papers/2610.17309) | StartLux-Decision introduces efficient and adaptive decision models using single-pass prediction and confidence-guided reasoning, trained vi… | [StartLuxLabs/StartLux-Decision](https://github.com/StartLuxLabs/StartLux-Decision) 1554★ |
| 23 | [Prism: Dynamic Sparse Attention for Native 2K Joint Video-Audio Generation Model Training](https://huggingface.co/papers/2610.05416) | Prism accelerates native joint video-audio generation at 2K by using dynamic sparse attention guided by local visual variance and audio-visu… | [Tencent-Hunyuan/Prism](https://github.com/Tencent-Hunyuan/Prism) 1123★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 33972★ |
| 48 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 33966★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 16 | [Next-Concept Modeling: Fast, Parallel Coarse-to-Fine Text Generation](https://huggingface.co/papers/2610.14162) | Next-Concept Modeling uses hierarchical discrete codes and parallel level-wise generation to accelerate diffusion language models while impr… | [HazyResearch/ncm](https://github.com/HazyResearch/ncm) 1026★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 91813★ |
| 97 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 28392★ |
| 31 | [Internal Safety Collapse in Frontier Large Language Models](https://huggingface.co/papers/2603.23509) | Frontier large language models exhibit Internal Safety Collapse, where they generate harmful content under specific task conditions, reveali… | [wuyoscar/ISC-Bench](https://github.com/wuyoscar/ISC-Bench) 2334★ |
| 78 | [Scaling in Games: Continued Pre-Training For Embodied Agents In Diverse Virtual Worlds](https://huggingface.co/papers/2610.28698) | Continued pre-training across data scale, diversity, and model size improves embodied learning in virtual worlds but reveals limits in dista… | 💡 [THUSI-Lab/GameScaling](https://github.com/THUSI-Lab/GameScaling) 388★ |
| 244 | [WeVisOne-VL: Unified Visual Perception from Objects to Pixels](https://huggingface.co/papers/2610.31329) | WeVisOne-VL unifies object-level and pixel-level visual perception via structured token prediction, supporting detection, localization, coun… | 💡 [Tencent/WeVisOne-VL](https://github.com/Tencent/WeVisOne-VL) 193★ |
| 180 | [SmolDocling: An ultra-compact vision-language model for end-to-end multi-modal document conversion](https://huggingface.co/papers/2503.11576) | SmolDocling is a compact vision-language model that performs end-to-end document conversion with robust performance across various document… | [docling-project/docling](https://github.com/docling-project/docling) 69571★ |
| 206 | [YuE2: Unifying Symbolic and Audio Music Generation at Frontier Quality](https://huggingface.co/papers/2609.33757) | YuE2 unifies symbolic and audio music generation via symbolic planning, producing readable scores and full-song audio with state-of-the-art… | [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE) 12708★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 82467★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 6 | [nanbeige4.3](https://huggingface.co/Nanbeige/Nanbeige4.3-33B) | text-generation | 409 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 52 | 14 | [POSIX wordexp(3) is dangerous](https://yossarian.net/til/post/posix-wordexp-3-is-dangerous/) | `c` `security` | [讨论](https://lobste.rs/s/tbbiqb/posix_wordexp_3_is_dangerous) |
| 91 | 26 | [The Slurptop: A home-built luggable that runs on power tool batteries](https://slurpburgers.com/slurpbuilds/the-slurptop/) | `art` `hardware` | [讨论](https://lobste.rs/s/zfoiw1/slurptop_home_built_luggable_runs_on) |
| 52 | 27 | [Vim Classic](https://vim-classic.org/) | `editors` `vim` | [讨论](https://lobste.rs/s/cxwpil/vim_classic) |
| 12 | 2 | [Simple NetBSD webserver](https://bsandro.tech/posts/simple-netbsd-webserver/) | `netbsd` | [讨论](https://lobste.rs/s/hzrmwz/simple_netbsd_webserver) |
| 35 | 13 | [Partial Order Precedence](https://ziglang.org/devlog/2026/#2026-10-24) | `zig` | [讨论](https://lobste.rs/s/kiivg2/partial_order_precedence) |
| 6 | 3 | [The Goose Programming Language](https://aardappel.github.io/goose/) | `plt` | [讨论](https://lobste.rs/s/dkoryq/goose_programming_language) |
| 5 | 1 | [writing about pratt parsing so I remember it](https://www.unix.dog/~yosh/blog/2026-10-25_pratt-parsing.html) | `c` `plt` | [讨论](https://lobste.rs/s/mu3xcd/writing_about_pratt_parsing_so_i_remember) |
| 8 | 2 | [Building Java ME Apps with Modern Tooling](https://voxelmanip.se/2026/10/24/building-java-me-apps-with-modern-tooling/) | `java` `retrocomputing` | [讨论](https://lobste.rs/s/ekwolo/building_java_me_apps_with_modern_tooling) |
| 12 | 1 | [A vision for a next-generation timeline](https://media.ccc.de/v/matrix-conference-2026-99070-a-vision-for-a-next-generation-timeline) | `distributed` `video` | [讨论](https://lobste.rs/s/jdczl6/vision_for_next_generation_timeline) |
| 115 | 31 | [I want my Wednesday back](https://blog.luitjes.it/posts/i-want-my-wednesday-back/) | `php` `security` | [讨论](https://lobste.rs/s/xgih2x/i_want_my_wednesday_back) |
| 15 | 2 | [When a glibc update accidentally breaks Chromium's audio (2021)](https://refi64.dev/posts/chromium-audio-break.html) | `c` `debugging` `programming` | [讨论](https://lobste.rs/s/5ullyu/when_glibc_update_accidentally_breaks) |
| 5 | 1 | [“AI Skills” are worthless in 2026](https://fishbowl.pastiche.org/2026/10/26/ai-skills) | `ai-tooling` `practices` | [讨论](https://lobste.rs/s/x1s5oq/ai_skills_are_worthless_2026) |
| 51 | 26 | [Balloting has completed for C++26. Unfortunately it was Disapproved](https://www.linkedin.com/posts/robertseacord_balloting-has-completed-for-c26-unfortunately-activity-7519795140887035918-5PWL) | `c++` | [讨论](https://lobste.rs/s/rlrfew/balloting_has_completed_for_c_26) |
| 10 | 0 | [SIMD-accelerated computer vision on a $2 microcontroller](https://shraiwi.com/blog/simd-fast-esp32s3/) | `assembly` | [讨论](https://lobste.rs/s/qsmmke/simd_accelerated_computer_vision_on_2) |
| 2 | 1 | [Two musings on the design of compiler warnings (2020)](https://quuxplusone.github.io/blog/2020/09/02/wparentheses/) | `compilers` | [讨论](https://lobste.rs/s/kfaimp/two_musings_on_design_compiler_warnings) |
| 4 | 0 | [Reverse-Engineering Instruction Encodings (2001)](https://www.usenix.org/legacy/events/usenix01/full_papers/hsieh/hsieh_html/) | `assembly` `reversing` | [讨论](https://lobste.rs/s/1q1rc1/reverse_engineering_instruction) |
| 14 | 0 | [MacOS Extensions pack for the Apple Network Server v1.0](http://oldvcr.blogspot.com/2026/10/macos-extensions-pack-for-apple-network.html) | `retrocomputing` `reversing` | [讨论](https://lobste.rs/s/7byfjv/macos_extensions_pack_for_apple_network) |
| 53 | 0 | [Bringing uv and ty together](https://astral.sh/blog/uv-ty-integration) | `python` | [讨论](https://lobste.rs/s/dfieqa/bringing_uv_ty_together) |
| 23 | 15 | [How to run a city builder on 16 MHz](https://larstofus.com/2025/11/16/how-to-run-a-city-builder-on-12-5-mhz/) | `programming` | [讨论](https://lobste.rs/s/qzfohf/how_run_city_builder_on_16_mhz) |
| 37 | 8 | [Wild version 0.11.0 released](https://github.com/wild-linker/wild/releases/tag/0.11.0) | `mac` `release` `rust` | [讨论](https://lobste.rs/s/vulvk7/wild_version_0_11_0_released) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

_还没有到 14 天的，93 个在等。_

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
