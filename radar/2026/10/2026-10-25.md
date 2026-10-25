# early-radar 选题雷达 · 2026-10-25

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 106 个，细查前 20 个 · 比上次 = 和 2026-10-24 那次比 · 生成于 2026-10-25 04:15 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 1 个 · Show HN ✅ 23 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 0 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 10 个 · 🟡 在降温 7 个 · 🔵 已被发现 1 个 · 💤 不活跃 0 个 · 🔴 先核对 2 个
- **今天新出现 3 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) 平均每天 +4111，见 [爆发](#爆发)
- **最值得今天试的**：
  - [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) — Ears for coding agents: let AI hear, review and make sound.…（近 7 天 +1677，比前 7 天快 1.7 倍，在加速）
  - [aicodeking/leanrea](https://github.com/aicodeking/leanrea) — One 8 KB skill that replaces REA (Reverse Engineer Anything)…（近 7 天 +1516，比前 7 天快 2.1 倍，在加速）
  - [yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) — 麦麦碳账本 · 基于麦当劳 MCP 的个人餐饮碳足迹估算与减排模拟器 / Personal dining carbon…（近 7 天 +1149，比前 7 天快 2.7 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 24 个（star 合计 26597），代表：[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[openfilm/openfilm](https://github.com/openfilm/openfilm)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：4 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: SimCity, but with Permits](https://permit.petercai.com/) — 937 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) | 32215 | 4111 | +3830 | 7.8 | [6](https://news.ycombinator.com/item?id=50164485) | cleanyourtv · gathin23 cleanyourtv · gathin cleanyourtv | Debloat any Android or Google TV over Wi-Fi and get an Apple… |
| 🆕 [Zagitta/gpu-unlock](https://github.com/Zagitta/gpu-unlock) | 3367 | 473 | +2718 | 7.1 | [205](https://news.ycombinator.com/item?id=50219700) | gpu unlock · zagitta gpu unlock · simon gpu unlock | Unlock FP/BF16 instruction issue rate on Nvidia 3000's cards… |
| [deepseek-ai/DeepInfer](https://github.com/deepseek-ai/DeepInfer) | 21934 | 2478 | +690 | 8.9 | [2346](https://news.ycombinator.com/item?id=50163277) | deepinfer · deepseek-ai deepinfer · deepseek deepinfer | DeepInfer: High-performance, large-scale inference framework… |
| [pengchujin/aerial-tv](https://github.com/pengchujin/aerial-tv) | 4450 | 928 | +521 | 4.8 | — | aerial tv · pengchujin aerial tv | 给国产电视的一块干净桌面：参照 tvOS 设计的开源 Android TV 桌面，没有广告，开机自动接管。A tvOS-… |
| [simbasjungles/free-my-tv](https://github.com/simbasjungles/free-my-tv) | 4332 | 807 | +336 | 5.4 | [1](https://news.ycombinator.com/item?id=50220596) | free my tv · simbasjungles free my tv · simba free my tv | A fast, ad-free home screen for Google TV, LG webOS and Sams… |
| 🆕 [JustAResearcher/gpu-unlock-ada](https://github.com/JustAResearcher/gpu-unlock-ada) | 1005 | 772 | — | 1.3 | [3](https://news.ycombinator.com/item?id=50223787) | gpu unlock ada · justaresearcher gpu unlock ada · tim gpu unlock ada | GPU tensor unlock source for RTX 4090 and experimental RTX 4… |
| [ly05010419/MacNativeGames](https://github.com/ly05010419/MacNativeGames) | 5251 | 714 | +270 | 7.3 | — | macnativegames · ly05010419 macnativegames · yong macnativegames |  |
| [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | 1741 | 505 | +654 | 3.4 | [3](https://news.ycombinator.com/item?id=50207695) | hatchzip · xevrion hatchzip · yash hatchzip | Extract huge archives in place: the archive shrinks as your… |
| 🆕 [yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) | 1567 | 123 | +582 | 12.8 | — | mccarbon · yeqv111 mccarbon | 麦麦碳账本 · 基于麦当劳 MCP 的个人餐饮碳足迹估算与减排模拟器 / Personal dining carbon… |
| [wesbos/3d-model-anything](https://github.com/wesbos/3d-model-anything) | 1712 | 510 | +539 | 3.4 | — | 3d model anything · wesbos 3d model anything · wes 3d model anything | Capture iPhone LiDAR and photos, reconstruct editable Three.… |
| [seedds/nxnative](https://github.com/seedds/nxnative) | 3144 | 263 | +507 | 12 | — | nxnative · seedds nxnative | Switch games running natively on iPhone, iPad and Mac: an NS… |
| [xiaoyang111222/cn-math-taxonomy](https://github.com/xiaoyang111222/cn-math-taxonomy) | 3324 | 489 | +442 | 6.8 | — | cn math taxonomy · xiaoyang111222 cn math taxonomy · aifeng cn math taxonomy | 数学（小学到高中）、英语（三年级到高中）、初中物理的知识图谱：1644 个知识点、2403 条先修边、6723 道题，对… |
| [ikow/php2shell-poc](https://github.com/ikow/php2shell-poc) | 1758 | 457 | +57 | 3.8 | — | php2shell poc · ikow php2shell poc · qi php2shell poc | CVE-2026-109618/109619 — 5 RCE chains + detection rules (Sur… |
| [oosexgang/hackios-xnu-kernel](https://github.com/oosexgang/hackios-xnu-kernel) | 1311 | 450 | +177 | 2.9 | [530](https://news.ycombinator.com/item?id=50196718) | hackios xnu kernel · oosexgang hackios xnu kernel |  |
| [JoasASantos/REA-Prompts](https://github.com/JoasASantos/REA-Prompts) | 2161 | 412 | +388 | 5.2 | — | rea prompts · joasasantos rea prompts · joas rea prompts | REAP - Prompts for you to use REA (Reverse Engineer Anything… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 89.1 | 🟢 窗口内 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) | Python | 2646 | +153 | +1677 | +969 | `···▂▄▄▄█▅▂▃▄▂·` | 9 | — | — |
| 2 | 87.9 | 🟢 窗口内 | [aicodeking/leanrea](https://github.com/aicodeking/leanrea) | Python | 2226 | +364 | +1516 | +709 | `····▁█▄▆▃▃▂█▆·` | 8 | — | — |
| 3 | 84.6 | 🆕 🟢 窗口内 | [yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) | Python | 1567 | +582 | +1149 | +418 | `▃·▁▂▂▂▁▂▂▂▃▃█·` | 12 | — | — |
| 4 | 84.2 | 🟢 窗口内 | [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) | Python | 1458 | +314 | +1118 | +340 | `···▁▂▃▅▄▄▃▃▇█·` | 9 | — | — |
| 5 | 83.2 | 🟢 窗口内 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 1604 | +58 | +1024 | +580 | `······█▆▃▃▃▂▂·` | 6 | — | — |
| 6 | 82.6 | 🟢 窗口内 | [ELY-Open-Source/ElyOffice](https://github.com/ELY-Open-Source/ElyOffice) | Rust | 973 | +38 | +973 | +0 | `·······▇█▃▄▂▂·` | 5 | — | — |
| 7 | 80.4 | 🆕 🟢 窗口内 | [Sam-Hui-dot/mcd-budget-meal](https://github.com/Sam-Hui-dot/mcd-budget-meal) | HTML | 1339 | +154 | +810 | +451 | `▃▂·▃▃▃▅▄▄▃▄█▆·` | 13 | — | — |
| 8 | 79.5 | 🟢 窗口内 | [reason-machines/reason-network](https://github.com/reason-machines/reason-network) | Rust | 1197 | +42 | +753 | +443 | `····▄▆▅▃█▆▅▃▂·` | 8 | — | — |
| 9 | 79.4 | 🟢 窗口内 | [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) | Python | 1191 | +124 | +745 | +446 | `····▃▅█▆▅▃▂█▄·` | 8 | [1](https://news.ycombinator.com/item?id=50177079) | — |
| 10 | 75.4 | 🟢 窗口内 | [torrentplayer/torrentplayer](https://github.com/torrentplayer/torrentplayer) | Rust | 536 | +94 | +536 | +0 | `·········██▄▄·` | 4 | — | — |
| 11 | 65.1 | 🟡 在降温 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 1775 | +18 | +670 | +1105 | `█▃▂▂▁▁▁▁▅▂▂▁▁·` | 12 | — | — |
| 12 | 64.1 | 🟡 在降温 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) | Go | 1876 | +54 | +608 | +1259 | `█▆▁▁▁▁▁▂▂▂▂▂▂·` | 16 | — | — |
| 13 | 60.6 | 🟡 在降温 | [feder-cr/git-ai](https://github.com/feder-cr/git-ai) | Go | 990 | +10 | +428 | +562 | `···▃▂▃█▄▄▂▂▁▁·` | 9 | — | — |
| 14 | 57.6 | 🟡 在降温 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 1924 | +32 | +315 | +1608 | `▆█▄▃▃▃▂▂▂▂▂▁▁·` | 14 | — | — |
| 15 | 55.6 | 🟡 在降温 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | Python | 2091 | +20 | +260 | +1175 | `█▃▃▅▄▃▃▂▂▂▂▂▁·` | 19 | [10](https://news.ycombinator.com/item?id=50037852) | — |
| 16 | 55.6 | 🟡 在降温 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) | Python | 2501 | +59 | +259 | +372 | `▄▃▂▂█▇▄▅▅▃▃▃▄·` | 24 | — | — |
| 17 | 51.5 | 🟡 在降温 | [marclou/mailcheap](https://github.com/marclou/mailcheap) | JavaScript | 1406 | +61 | +172 | +450 | `▃▄▂█▆▂▂▂▂▂▂▃▃·` | 14 | [2](https://news.ycombinator.com/item?id=50033695) | — |
| 18 | 44.8 | 🔴 先核对 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 1741 | +654 | +1741 | +0 | `·········▁▁█▅·` | 3 | [3](https://news.ycombinator.com/item?id=50207695) | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 44.2 | 🔵 已被发现 | [openfilm/openfilm](https://github.com/openfilm/openfilm) | TypeScript | 2628 | +262 | +1575 | +884 | `▂▂▂▂▅▆▅█▆▆▇▅▆·` | 20 | [244](https://news.ycombinator.com/item?id=44428438) | — |
| 20 | 42.1 | 🆕 🔴 先核对 | [amosblomqvist/learnharness](https://github.com/amosblomqvist/learnharness) | TypeScript | 1117 | — | +1108 | +9 | `····▁▁▁▁▁▁▁▄█·` | 8 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 525 | 30 | 43709 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[openfilm/openfilm](https://github.com/openfilm/openfilm) |
| `mcp` | 248 | 30 | 31655 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[aicodeking/leanrea](https://github.com/aicodeking/leanrea)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) |
| `rust` | 172 | 30 | 22527 | [oxc-project/tsrs](https://github.com/oxc-project/tsrs)、[academa-labs/manimgx](https://github.com/academa-labs/manimgx)、[opengeos/RustGIS](https://github.com/opengeos/RustGIS) |
| `local-first` | 50 | 30 | 9333 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[chenxiachan/textfold](https://github.com/chenxiachan/textfold)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 24 | 26597 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[openfilm/openfilm](https://github.com/openfilm/openfilm) |
| `ai-agents` | 19 | 14038 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering) |
| `codex` | 15 | 17111 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[openfilm/openfilm](https://github.com/openfilm/openfilm)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) |
| `llm` | 14 | 10503 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[Harvil1/codeAgent](https://github.com/Harvil1/codeAgent) |
| `agent-skills` | 13 | 14757 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `mcp-server` | 13 | 9658 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist) |
| `ai-agent` | 11 | 8209 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `macos` | 9 | 4134 | [Zfinix/eleven](https://github.com/Zfinix/eleven)、[kitlangton/scrawl](https://github.com/kitlangton/scrawl)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch) |
| `developer-tools` | 8 | 6984 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai)、[hanzohanzhe/Grandet](https://github.com/hanzohanzhe/Grandet) |
| `coding-agents` | 7 | 9059 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[openfilm/openfilm](https://github.com/openfilm/openfilm)、[reason-machines/reason-network](https://github.com/reason-machines/reason-network) |
| `claude-skills` | 7 | 8127 | [oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill) |
| `typescript` | 7 | 7578 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust)、[rociiu/talorys](https://github.com/rociiu/talorys) |

**语言分布**：Rust 29 · Python 28 · TypeScript 20 · JavaScript 13 · Go 3 · HTML 2 · Swift 2 · Astro 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) · 🟢 窗口内 · 89.1 分

> Ears for coding agents: let AI hear, review and make sound. CPU-only, open source.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2646 | +1677 | +969 | 162 | 8 | Python | MIT | 10-15（9 天前） | 2 天前 |

- **近 14 天每天新增**：`···▂▄▄▄█▅▂▃▄▂·` 0 0 0 112 309 285 263 679 343 73 203 245 134 0
- **势头**：比前 7 天快 1.7 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `audio` `claude-code` `mcp` `sound-design`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [aicodeking/leanrea](https://github.com/aicodeking/leanrea) · 🟢 窗口内 · 87.9 分

> One 8 KB skill that replaces REA (Reverse Engineer Anything): plain CLI tools, no MCP. Benchmarked: 38% faster, 35% cheaper.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2226 | +1516 | +709 | 340 | 7 | Python | MIT | 10-17（8 天前） | 5 天前 |

- **近 14 天每天新增**：`····▁█▄▆▃▃▂█▆·` 0 0 0 0 26 464 219 322 164 116 96 473 345 0
- **势头**：比前 7 天快 2.1 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. 🆕 [yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) · 🟢 窗口内 · 84.6 分

> 麦麦碳账本 · 基于麦当劳 MCP 的个人餐饮碳足迹估算与减排模拟器 | Personal dining carbon footprint estimator powered by McDonald's MCP

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1567 | +1149 | +418 | 37 | 0 | Python | MIT | 10-12（12 天前） | 11 天前 |

- **近 14 天每天新增**：`▃·▁▂▂▂▁▂▂▂▃▃█·` 205 0 4 67 63 46 33 101 86 107 131 149 575 0
- **势头**：比前 7 天快 2.7 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) · 🟢 窗口内 · 84.2 分

> 麦当劳 MCP 聚会/团餐组织助手 — 基于 Model Context Protocol 的派对预订与团餐规划 CLI/Skill

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1458 | +1118 | +340 | 70 | 2 | Python | MIT | 10-15（9 天前） | 今天 |

- **近 14 天每天新增**：`···▁▂▃▅▄▄▃▃▇█·` 0 0 0 15 53 97 175 151 142 123 80 276 346 0
- **势头**：比前 7 天快 3.3 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) · 🟢 窗口内 · 83.2 分

> 让你的agent一键直出商业级产品宣传片：会作曲，能指着画面改。Commercial-grade launch films by your coding agent — point at the frame to change it.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1604 | +1024 | +580 | 158 | 3 | JavaScript | MIT | 10-18（6 天前） | 2 天前 |

- **近 14 天每天新增**：`······█▆▃▃▃▂▂·` 0 0 0 0 0 0 580 439 170 135 157 78 45 0
- **势头**：比前 7 天快 1.8 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `animation` `claude-code` `codex` `gsap` `launch-video` `motion-graphics` `skills`
- **主页**：<https://github.com/alchaincyf/huashu-motion>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [ELY-Open-Source/ElyOffice](https://github.com/ELY-Open-Source/ElyOffice) · 🟢 窗口内 · 82.6 分

> Ely Office: offline-first desktop apps in Rust and GPUI

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 973 | +973 | +0 | 62 | 13 | Rust | MIT | 10-19（5 天前） | 1 天前 |

- **近 14 天每天新增**：`·······▇█▃▄▂▂·` 0 0 0 0 0 0 0 292 358 100 142 50 31 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://office.elygpui.com>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. 🆕 [Sam-Hui-dot/mcd-budget-meal](https://github.com/Sam-Hui-dot/mcd-budget-meal) · 🟢 窗口内 · 80.4 分

> 麦麦预算餐：基于麦当劳 MCP 的真实核价、预算比较与餐品替换 Skill

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1339 | +810 | +451 | 44 | 0 | HTML | — | 10-11（13 天前） | 今天 |

- **近 14 天每天新增**：`▃▂·▃▃▃▅▄▄▃▄█▆·` 64 33 0 78 56 88 132 112 96 73 98 257 174 0
- **势头**：比前 7 天快 1.8 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`mcdonalds` `mcp` `python` `skill` `workbuddy`
- **主页**：<https://sam-hui-dot.github.io/mcd-budget-meal/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [reason-machines/reason-network](https://github.com/reason-machines/reason-network) · 🟢 窗口内 · 79.5 分

> Reason Network: your team's coding agents, talking to each other. The engine behind `reason network`.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1197 | +753 | +443 | 101 | 9 | Rust | Apache-2.0 | 10-16（8 天前） | 今天 |

- **近 14 天每天新增**：`····▄▆▅▃█▆▅▃▂·` 0 0 0 0 108 179 156 65 268 184 137 60 39 0
- **势头**：比前 7 天快 1.7 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`coding-agents` `iroh` `mcp` `peer-to-peer` `reason`
- **主页**：<https://reasonmachines.com>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 9. [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) · 🟢 窗口内 · 79.4 分

> Co-op Anything: point your AI agent at any single-player game and play it with friends (online and/or splitscreen!). MCP server and playbook to let you reverse engineer, fix, test, ship and share what it learns.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1191 | +745 | +446 | 157 | 133 | Python | MIT | 10-16（8 天前） | 2 天前 |

- **近 14 天每天新增**：`····▃▅█▆▅▃▂█▄·` 0 0 0 0 81 131 234 156 124 77 47 227 114 0
- **势头**：比前 7 天快 1.7 倍，在加速
- **HN**：发过 1 次，最高 1 分（[讨论](https://news.ycombinator.com/item?id=50177079)）
- **主页**：<https://coopanything.app>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 10. [torrentplayer/torrentplayer](https://github.com/torrentplayer/torrentplayer) · 🟢 窗口内 · 75.4 分

> Stream any torrent, video or audio, and skip to any moment in about a second. Free, open-source desktop app for Windows, macOS and Linux. No servers, no accounts, no telemetry.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 536 | +536 | +0 | 8 | 6 | Rust | Apache-2.0 | 10-20（4 天前） | 今天 |

- **近 14 天每天新增**：`·········██▄▄·` 0 0 0 0 0 0 0 0 0 183 189 78 86 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`audio-player` `bittorrent` `cross-platform` `desktop-app` `media-player` `p2p` `rust` `streaming` `svelte` `tauri` `torrent` `video-player`
- **主页**：<https://torrentstream.io>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [xevrion/hatchzip](https://github.com/xevrion/hatchzip) — 一天进了一半以上的 star，但 HN 上没火过
- [amosblomqvist/learnharness](https://github.com/amosblomqvist/learnharness) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 937 | 425 | [Show HN: SimCity, but with Permits](https://permit.petercai.com/) | [HN](https://news.ycombinator.com/item?id=50170593) |
| 435 | 263 | [Show HN: Steal My Bitcoin](https://stealmybitcoin.com/) | [HN](https://news.ycombinator.com/item?id=50224916) |
| 253 | 89 | [Show HN: Sphinx – A hook that quizzes you on your AI's code before shipping](https://sphinx-six-theta.vercel.app/) | [HN](https://news.ycombinator.com/item?id=50137950) |
| 229 | 129 | [Show HN: The Zelda timeline to catch up before the Ocarina of Time remake](https://legendofhyrule.com/) | [HN](https://news.ycombinator.com/item?id=50140769) |
| 229 | 91 | [Show HN: OnKey – I'm a bad singer, so I built an app to show where I'm off-key](https://github.com/dsmurrell/onkey) | [HN](https://news.ycombinator.com/item?id=50195488) |
| 188 | 13 | [Show HN: VoidAccess – open-source dark web OSINT, from query to a graph](https://github.com/KatrielMoses/voidaccess) | [HN](https://news.ycombinator.com/item?id=50167286) |
| 158 | 113 | [Show HN: Qwen3-4B with the AI writing tics trained out](https://100toolkit.com/blog/deslop-model/) | [HN](https://news.ycombinator.com/item?id=50151928) |
| 157 | 85 | [Show HN: WhatsApp MCP running free on Cloudflare](https://github.com/finereli/whatsapp-mcp) | [HN](https://news.ycombinator.com/item?id=50145715) |
| 126 | 42 | [Show HN: Corgi, a helpful {agent, terminal} multiplexer](https://corgi.computer/) | [HN](https://news.ycombinator.com/item?id=50214373) |
| 122 | 34 | [Show HN: Uberblok – an interactive museum of ZFS internals](https://uberblok.storagebits.workers.dev/) | [HN](https://news.ycombinator.com/item?id=50180257) |
| 112 | 34 | [Show HN: Omnara – Open-source alternative to Claude Managed Agents](https://github.com/omnara-ai/omnara) | [HN](https://news.ycombinator.com/item?id=50183892) |
| 110 | 66 | [Show HN: Death Plan Switch, a self-hosted dead man's switch for solo devs](https://deathplanswitch.com/) | [HN](https://news.ycombinator.com/item?id=50161408) |
| 107 | 77 | [Show HN: Making a smart TV dumb and then smart](https://github.com/anubhavmalhotra/r2d2-tv) | [HN](https://news.ycombinator.com/item?id=50202865) |
| 102 | 28 | [Show HN: Sumi.css – CSS Framework](https://github.com/vladocar/Sumi.css) | [HN](https://news.ycombinator.com/item?id=50180039) |
| 80 | 45 | [Show HN: UI micro interactions prompts for AI](https://www.typeui.sh/micro-interactions) | [HN](https://news.ycombinator.com/item?id=50199290) |
| 80 | 18 | [Show HN: Impossible Machines: declaratively program the physical world](https://www.impossiblemachines.xyz) | [HN](https://news.ycombinator.com/item?id=50202746) |
| 73 | 36 | [Show HN: Swurf – Swipe through the real web](https://swurf.org/) | [HN](https://news.ycombinator.com/item?id=50205320) |
| 72 | 54 | [Show HN: Jev Cards, Can you beat a vision model at a picture quiz?](https://jevcards.com) | [HN](https://news.ycombinator.com/item?id=50167617) |
| 69 | 44 | [Show HN: KiviDB, a faster Redis-compatible memory database and vector cache](https://github.com/kividbio/kividb) | [HN](https://news.ycombinator.com/item?id=50152541) |
| 66 | 9 | [Show HN: Penmentor – Claude marks up your handwritten math like a teacher](https://github.com/AbdullahAlhariri/penmentor) | [HN](https://news.ycombinator.com/item?id=50167604) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 122 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 19127★ |
| 154 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 113735★ |
| 62 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 43575★ |
| 30 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 6954★ |
| 98 | [MOSS-Image Technical Report](https://huggingface.co/papers/2610.23374) | MOSS-Image is an open diffusion transformer that combines high-fidelity synthesis with intent-aware prompt enhancement to generate text-rich… | [OpenMOSS/MOSS-Image](https://github.com/OpenMOSS/MOSS-Image) 1760★ |
| 120 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 2517★ |
| 81 | [StartLux-Decision: AutoThink Decision Models with Reinforcement Learning for Calibrated Deliberative…](https://huggingface.co/papers/2610.17309) | StartLux-Decision introduces efficient and adaptive decision models using single-pass prediction and confidence-guided reasoning, trained vi… | [StartLuxLabs/StartLux-Decision](https://github.com/StartLuxLabs/StartLux-Decision) 1489★ |
| 16 | [Next-Concept Modeling: Fast, Parallel Coarse-to-Fine Text Generation](https://huggingface.co/papers/2610.14162) | Next-Concept Modeling uses hierarchical discrete codes and parallel level-wise generation to accelerate diffusion language models while impr… | 💡 [HazyResearch/ncm](https://github.com/HazyResearch/ncm) 969★ |
| 31 | [Internal Safety Collapse in Frontier Large Language Models](https://huggingface.co/papers/2603.23509) | Frontier large language models exhibit Internal Safety Collapse, where they generate harmful content under specific task conditions, reveali… | [wuyoscar/ISC-Bench](https://github.com/wuyoscar/ISC-Bench) 2313★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 91738★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 75 | [Scaling in Games: Continued Pre-Training For Embodied Agents In Diverse Virtual Worlds](https://huggingface.co/papers/2610.28698) | Continued pre-training across data scale, diversity, and model size improves embodied learning in virtual worlds but reveals limits in dista… | 💡 [THUSI-Lab/GameScaling](https://github.com/THUSI-Lab/GameScaling) 359★ |
| 23 | [Prism: Dynamic Sparse Attention for Native 2K Joint Video-Audio Generation Model Training](https://huggingface.co/papers/2610.05416) | Prism accelerates native joint video-audio generation at 2K by using dynamic sparse attention guided by local visual variance and audio-visu… | 💡 [Tencent-Hunyuan/Prism](https://github.com/Tencent-Hunyuan/Prism) 980★ |
| 97 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 28339★ |
| 205 | [YuE2: Unifying Symbolic and Audio Music Generation at Frontier Quality](https://huggingface.co/papers/2609.33757) | YuE2 unifies symbolic and audio music generation via symbolic planning, producing readable scores and full-song audio with state-of-the-art… | [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE) 12659★ |
| 180 | [SmolDocling: An ultra-compact vision-language model for end-to-end multi-modal document conversion](https://huggingface.co/papers/2503.11576) | SmolDocling is a compact vision-language model that performs end-to-end document conversion with robust performance across various document… | [docling-project/docling](https://github.com/docling-project/docling) 69508★ |
| 48 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 33827★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 33828★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 82419★ |
| 11 | [UniAVC: Unified Audio-Video Creation via Progressive Training and Asymmetric Scheduling](https://huggingface.co/papers/2610.24791) | UniAVC trains separate audio and video branches on abundant unimodal data before aligning them with scarce paired data, using independent no… | 💡 [HKUST-LongGroup/UniAVC](https://github.com/HKUST-LongGroup/UniAVC) 241★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 33 | [deepseek v4.1 flash 1017](https://huggingface.co/orcarouter/DeepSeek-V4.1-Flash-1017-abliterated-GGUF) | text-generation | 150 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 100 | 30 | [I want my Wednesday back](https://blog.luitjes.it/posts/i-want-my-wednesday-back/) | `php` `security` | [讨论](https://lobste.rs/s/xgih2x/i_want_my_wednesday_back) |
| 27 | 12 | [Balloting has completed for C++26. Unfortunately it was Disapproved](https://www.linkedin.com/posts/robertseacord_balloting-has-completed-for-c26-unfortunately-activity-7519795140887035918-5PWL) | `c++` | [讨论](https://lobste.rs/s/rlrfew/balloting_has_completed_for_c_26) |
| 34 | 0 | [Bringing uv and ty together](https://astral.sh/blog/uv-ty-integration) | `python` | [讨论](https://lobste.rs/s/dfieqa/bringing_uv_ty_together) |
| 31 | 7 | [Wild version 0.11.0 released](https://github.com/wild-linker/wild/releases/tag/0.11.0) | `mac` `release` `rust` | [讨论](https://lobste.rs/s/vulvk7/wild_version_0_11_0_released) |
| 60 | 13 | [Indian government sites are serving revoked eMudhra certificates](https://captnemo.in/blog/2026/10/23/emsign-revoked-gov-in/) | `security` | [讨论](https://lobste.rs/s/zug8xv/indian_government_sites_are_serving) |
| 30 | 1 | [Be Aware of What's in Your Logs](https://fireborn.mataroa.blog/blog/be-aware-of-whats-in-your-logs/) | `debugging` | [讨论](https://lobste.rs/s/rl0dz5/be_aware_what_s_your_logs) |
| 68 | 58 | [Attention people who think UB is fine](https://blog.habets.se/2026/10/Attention-people-who-think-UB-is-fine.html) | `c` `c++` | [讨论](https://lobste.rs/s/5xzuff/attention_people_who_think_ub_is_fine) |
| 7 | 0 | [We should be more ambitious with the software we build](https://danluu.com/ambitious/) | `practices` | [讨论](https://lobste.rs/s/8h9sey/we_should_be_more_ambitious_with_software) |
| 9 | 14 | [How to run a city builder on 16 MHz](https://larstofus.com/2025/11/16/how-to-run-a-city-builder-on-12-5-mhz/) | `programming` | [讨论](https://lobste.rs/s/qzfohf/how_run_city_builder_on_16_mhz) |
| 25 | 2 | [Emacs finally folds to my liking](https://jointhefreeworld.org/blog/articles/emacs/emacs-folding-kirigami/) | `emacs` | [讨论](https://lobste.rs/s/yczems/emacs_finally_folds_my_liking) |
| 2 | 0 | [MacOS Extensions pack for the Apple Network Server v1.0](http://oldvcr.blogspot.com/2026/10/macos-extensions-pack-for-apple-network.html) | `retrocomputing` `reversing` | [讨论](https://lobste.rs/s/7byfjv/macos_extensions_pack_for_apple_network) |
| 26 | 22 | [What's wrong with AI?](https://homepage.farm/ai.html) | `culture` | [讨论](https://lobste.rs/s/vh8l3t/what_s_wrong_with_ai) |
| 8 | 10 | [This week's "node2shell" Brotli vulnerability (CVE-2026-111497) is exploitable in Python, other cons…](https://www.aikido.dev/blog/python-packages-vulnerable-node2shell-brotli-cve-2026-111497) | `security` `web` | [讨论](https://lobste.rs/s/al3yyf/this_week_s_node2shell_brotli) |
| 61 | 8 | [The glorious @xkcdRandom Zig builtin](https://ochagavia.nl/blog/the-glorious-@xkcdrandom-zig-builtin/) | `compilers` `satire` `zig` | [讨论](https://lobste.rs/s/5hoqzj/glorious_xkcdrandom_zig_builtin) |
| 15 | 1 | [Twelve years of distributed SQLite](https://philipotoole.com/twelve-years-of-distributed-sqlite/) | `databases` | [讨论](https://lobste.rs/s/rqefcw/twelve_years_distributed_sqlite) |
| 2 | 0 | [SIMD and Go](https://internals-for-interns.com/posts/go-simd/) | `go` | [讨论](https://lobste.rs/s/whgofc/simd_go) |
| 51 | 69 | [Software is slow because of bad design, not slow languages](https://www.seangoedecke.com/software-is-slow-because-of-bad-design-not-slow-languages/) | `performance` | [讨论](https://lobste.rs/s/hd72yt/software_is_slow_because_bad_design_not) |
| 3 | 1 | [The Polyglot's Dilemma: Conformance Testing a Dozen Specs in as Many Languages](https://emptysqua.re/blog/polyglots-dilemma/) | `practices` | [讨论](https://lobste.rs/s/gzpdsk/polyglot_s_dilemma_conformance_testing) |
| 4 | 0 | [2026 Ruby on Rails Community Survey Results](https://railsdeveloper.com/survey/2026) | `ruby` | [讨论](https://lobste.rs/s/ysah7i/2026_ruby_on_rails_community_survey) |
| 49 | 19 | [How close can pure FP get to C?](https://rtfeldman.com/fp-vs-c) | `performance` `programming` | [讨论](https://lobste.rs/s/7me8wm/how_close_can_pure_fp_get_c) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

_还没有到 14 天的，87 个在等。_

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
