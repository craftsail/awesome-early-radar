# early-radar 选题雷达 · 2026-10-23

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 105 个，细查前 20 个 · 比上次 = 和 2026-10-22 那次比 · 生成于 2026-10-23 04:22 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 0 个 · Show HN ✅ 23 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 0 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 10 个 · 🟡 在降温 6 个 · 🔵 已被发现 2 个 · 💤 不活跃 0 个 · 🔴 先核对 2 个
- **今天新出现 2 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) 平均每天 +4245，见 [爆发](#爆发)
- **最值得今天试的**：
  - [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) — Ears for coding agents: let AI hear, review and make sound.…（近 7 天 +1812，比前 7 天快 4.3 倍，在加速）
  - [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) — 让你的agent一键直出商业级产品宣传片：会作曲，能指着画面改。Commercial-grade launch film…（近 7 天 +1459，刚发布一周内）
  - [aicodeking/leanrea](https://github.com/aicodeking/leanrea) — One 8 KB skill that replaces REA (Reverse Engineer Anything)…（近 7 天 +1348，比前 7 天快 51.8 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 24 个（star 合计 24989），代表：[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：6 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: SimCity, but with Permits](https://permit.petercai.com/) — 930 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) | 24789 | 4245 | +4683 | 5.8 | [6](https://news.ycombinator.com/item?id=50164485) | cleanyourtv · gathin23 cleanyourtv · gathin cleanyourtv | Debloat any Android or Google TV over Wi-Fi and get an Apple… |
| [deepseek-ai/DeepInfer](https://github.com/deepseek-ai/DeepInfer) | 20134 | 2936 | +1729 | 6.9 | [2333](https://news.ycombinator.com/item?id=50163277) | deepinfer · deepseek-ai deepinfer · deepseek deepinfer | DeepInfer: High-performance, large-scale inference framework… |
| [pengchujin/aerial-tv](https://github.com/pengchujin/aerial-tv) | 3304 | 1181 | +941 | 2.8 | — | aerial tv · pengchujin aerial tv | 给国产电视的一块干净桌面：参照 tvOS 设计的开源 Android TV 桌面，没有广告，开机自动接管。A tvOS-… |
| [simbasjungles/free-my-tv](https://github.com/simbasjungles/free-my-tv) | 3528 | 1047 | +708 | 3.4 | — | free my tv · simbasjungles free my tv · simba free my tv | A fast, ad-free home screen for Google TV. Open source, buil… |
| [ly05010419/MacNativeGames](https://github.com/ly05010419/MacNativeGames) | 4568 | 853 | +561 | 5.4 | — | macnativegames · ly05010419 macnativegames · yong macnativegames |  |
| [ikow/php2shell-poc](https://github.com/ikow/php2shell-poc) | 1567 | 846 | +463 | 1.9 | — | php2shell poc · ikow php2shell poc · qi php2shell poc | CVE-2026-109618/109619 — 5 RCE chains + detection rules (Sur… |
| 🆕 [seedds/nxnative](https://github.com/seedds/nxnative) | 1904 | 191 | +746 | 10 | — | nxnative · seedds nxnative | Switch games running natively on iPhone, iPad and Mac: an NS… |
| 🆕 [oosexgang/hackios-xnu-kernel](https://github.com/oosexgang/hackios-xnu-kernel) | 606 | 606 | — | 1 | [355](https://news.ycombinator.com/item?id=50196718) | hackios xnu kernel · oosexgang hackios xnu kernel |  |
| [9bie/php2shell-bypass-aslr-exp](https://github.com/9bie/php2shell-bypass-aslr-exp) | 982 | 572 | +367 | 1.7 | — | php2shell bypass aslr exp · 9bie php2shell bypass aslr exp | A php2shell exploit that requires no modifications to the of… |
| 🆕 [mmparko/dsh-purge](https://github.com/mmparko/dsh-purge) | 1774 | 178 | +556 | 10 | — | dsh purge · mmparko dsh purge | DeepSeek Harness 破甲 (mirror of YuJunZhiXue/dsh-purge) — 上游即将… |
| 🆕 [Acelogic/Snapintosh](https://github.com/Acelogic/Snapintosh) | 588 | 528 | — | 1.1 | — | snapintosh · acelogic snapintosh · miguel snapintosh | EL2 hypervisor and toolchain that boots macOS on the ASUS A1… |
| [eness/php2shell-CVE-2026-109618-CVE-2026-109619-PoC](https://github.com/eness/php2shell-CVE-2026-109618-CVE-2026-109619-PoC) | 901 | 493 | +244 | 1.8 | — | php2shell cve 2026 109618 cve 2026 109619 poc · eness php2shell cve 2026 109618 cve 2026 109619 poc · enes php2shell cve 2026 109618 cve 2026 109619 poc | Proof-of-Concept (PoC) exploit for php2shell (CVE-2026-10961… |
| 🆕 [tek-sys-hub/Rubix-lang](https://github.com/tek-sys-hub/Rubix-lang) | 1904 | 482 | — | 3.9 | — | rubix lang · tek-sys-hub rubix lang · tek rubix lang | The 100% Pure x86-64 Assembly Systems Language |
| [xiaoyang111222/cn-math-taxonomy](https://github.com/xiaoyang111222/cn-math-taxonomy) | 2289 | 476 | +253 | 4.8 | — | cn math taxonomy · xiaoyang111222 cn math taxonomy · aifeng cn math taxonomy | 数学（小学到高中）、英语（三年级到高中）、初中物理的知识图谱：1644 个知识点、2403 条先修边、6723 道题，对… |
| [JoasASantos/REA-Prompts](https://github.com/JoasASantos/REA-Prompts) | 1498 | 461 | +130 | 3.3 | — | rea prompts · joasasantos rea prompts · joas rea prompts | REAP - Prompts for you to use REA (Reverse Engineer Anything… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 90 | 🟢 窗口内 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) | Python | 2233 | +172 | +1812 | +421 | `·····▂▄▄▄█▅▂▃·` | 7 | — | — |
| 2 | 87.4 | 🟢 窗口内 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 1459 | +156 | +1459 | +0 | `········█▆▃▃▃·` | 4 | — | — |
| 3 | 86.5 | 🟢 窗口内 | [aicodeking/leanrea](https://github.com/aicodeking/leanrea) | Python | 1374 | +67 | +1348 | +26 | `······▁█▄▆▃▃▂·` | 6 | — | — |
| 4 | 82.6 | 🟢 窗口内 | [reason-machines/reason-network](https://github.com/reason-machines/reason-network) | Rust | 1081 | +138 | +972 | +108 | `······▄▆▅▃█▆▄·` | 6 | — | — |
| 5 | 81.5 | 🟢 窗口内 | [ELY-Open-Source/ElyOffice](https://github.com/ELY-Open-Source/ElyOffice) | Rust | 886 | +156 | +886 | +0 | `·········▇█▃▄·` | 3 | — | — |
| 6 | 80.7 | 🟢 窗口内 | [feder-cr/git-ai](https://github.com/feder-cr/git-ai) | Go | 966 | +44 | +831 | +135 | `·····▃▂▃█▄▄▂▂·` | 7 | — | — |
| 7 | 80.2 | 🟢 窗口内 | [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) | Python | 874 | +84 | +801 | +73 | `·····▂▃▅█▇▆▆▄·` | 7 | — | — |
| 8 | 79.7 | 🟢 窗口内 | [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) | Python | 848 | +48 | +767 | +81 | `······▃▅█▆▅▃▂·` | 6 | [1](https://news.ycombinator.com/item?id=50177079) | — |
| 9 | 73.2 | 🟢 窗口内 | [kanaworksai-hue/audio-studio-mcp](https://github.com/kanaworksai-hue/audio-studio-mcp) | Python | 444 | +15 | +444 | +0 | `········█▇▅▄▂·` | 4 | — | — |
| 10 | 68.6 | 🟢 窗口内 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) | Python | 2410 | +26 | +303 | +297 | `▂▃▄▃▂▂█▇▄▅▅▃▂·` | 22 | — | — |
| 11 | 64.7 | 🟡 在降温 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 1705 | +81 | +644 | +1061 | `··█▃▂▂▁▁▁▁▅▂▂·` | 10 | — | — |
| 12 | 62.5 | 🟡 在降温 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) | Go | 1721 | +127 | +517 | +1201 | `▁▁█▆▁▁▁▁▁▂▂▂▂·` | 14 | — | — |
| 13 | 61.4 | 🟡 在降温 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 1858 | +45 | +465 | +1393 | `·▁▆█▄▃▃▃▂▂▂▂▂·` | 12 | — | — |
| 14 | 59.5 | 🟡 在降温 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | Python | 2032 | +30 | +383 | +1601 | `▁█▆▃▂▄▃▂▂▂▂▂▁·` | 17 | [10](https://news.ycombinator.com/item?id=50037852) | — |
| 15 | 49.1 | 🟡 在降温 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) | TypeScript | 1654 | +7 | +134 | +879 | `█▄▃▂▂▁▁▂▁▁▁▁▁·` | 15 | — | — |
| 16 | 48.4 | 🟡 在降温 | [marclou/mailcheap](https://github.com/marclou/mailcheap) | JavaScript | 1307 | +12 | +126 | +1181 | `█▄▂▂▁▃▂▁▁▁▁▁▁·` | 12 | [2](https://news.ycombinator.com/item?id=50033695) | — |
| 17 | 44 | 🆕 🔵 已被发现 | [openfilm/openfilm](https://github.com/openfilm/openfilm) | TypeScript | 2171 | +301 | +1535 | +636 | `▃▃▂▂▂▂▅▆▅█▆▆▆·` | 18 | [244](https://news.ycombinator.com/item?id=44428438) | — |
| 18 | 37 | 🔴 先核对 | [realskyrin/ns-game-apple-arm-port](https://github.com/realskyrin/ns-game-apple-arm-port) | — | 477 | +48 | +477 | +0 | `·······▁▃▃▃█▂·` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 35.4 | 🆕 🔴 先核对 | [torrentplayer/torrentplayer](https://github.com/torrentplayer/torrentplayer) | Rust | 364 | — | +364 | +0 | `···········██·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 23.5 | 🔵 已被发现 | [rociiu/talorys](https://github.com/rociiu/talorys) | TypeScript | 1372 | +6 | +109 | +1263 | `█▅▃▂▂▄▂▂▁▁▁▁▁·` | 12 | [331](https://news.ycombinator.com/item?id=50031614) | — |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 514 | 30 | 43697 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) |
| `mcp` | 204 | 30 | 28907 | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) |
| `rust` | 162 | 30 | 19981 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx)、[oxc-project/tsrs](https://github.com/oxc-project/tsrs)、[opengeos/RustGIS](https://github.com/opengeos/RustGIS) |
| `local-first` | 52 | 30 | 10494 | [glanderness/BeefTV](https://github.com/glanderness/BeefTV)、[HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 24 | 24989 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) |
| `ai-agents` | 18 | 13030 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `codex` | 15 | 16375 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[openfilm/openfilm](https://github.com/openfilm/openfilm) |
| `llm` | 15 | 12129 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) |
| `agent-skills` | 14 | 16815 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) |
| `mcp-server` | 13 | 8965 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist) |
| `ai-agent` | 12 | 9963 | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `developer-tools` | 9 | 8075 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) |
| `coding-agents` | 7 | 8367 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[openfilm/openfilm](https://github.com/openfilm/openfilm)、[reason-machines/reason-network](https://github.com/reason-machines/reason-network) |
| `typescript` | 7 | 7310 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `self-hosted` | 7 | 4963 | [rociiu/talorys](https://github.com/rociiu/talorys)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) |
| `macos` | 7 | 2969 | [kitlangton/scrawl](https://github.com/kitlangton/scrawl)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch)、[strands-agents/box](https://github.com/strands-agents/box) |

**语言分布**：Python 31 · Rust 29 · TypeScript 19 · JavaScript 12 · Go 3 · Swift 3 · Astro 1 · C++ 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) · 🟢 窗口内 · 90 分

> Ears for coding agents: let AI hear, review and make sound. CPU-only, open source.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2233 | +1812 | +421 | 133 | 5 | Python | MIT | 10-15（7 天前） | 今天 |

- **近 14 天每天新增**：`·····▂▄▄▄█▅▂▃·` 0 0 0 0 0 112 309 285 263 679 344 73 168 0
- **势头**：比前 7 天快 4.3 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `audio` `claude-code` `mcp` `sound-design`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) · 🟢 窗口内 · 87.4 分

> 让你的agent一键直出商业级产品宣传片：会作曲，能指着画面改。Commercial-grade launch films by your coding agent — point at the frame to change it.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1459 | +1459 | +0 | 141 | 2 | JavaScript | MIT | 10-18（4 天前） | 今天 |

- **近 14 天每天新增**：`········█▆▃▃▃·` 0 0 0 0 0 0 0 0 580 440 170 135 134 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `animation` `claude-code` `codex` `gsap` `launch-video` `motion-graphics` `skills`
- **主页**：<https://github.com/alchaincyf/huashu-motion>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [aicodeking/leanrea](https://github.com/aicodeking/leanrea) · 🟢 窗口内 · 86.5 分

> One 8 KB skill that replaces REA (Reverse Engineer Anything): plain CLI tools, no MCP. Benchmarked: 38% faster, 35% cheaper.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1374 | +1348 | +26 | 207 | 6 | Python | MIT | 10-17（6 天前） | 3 天前 |

- **近 14 天每天新增**：`······▁█▄▆▃▃▂·` 0 0 0 0 0 0 26 466 219 322 165 116 60 0
- **势头**：比前 7 天快 51.8 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [reason-machines/reason-network](https://github.com/reason-machines/reason-network) · 🟢 窗口内 · 82.6 分

> Reason Network: your team's coding agents, talking to each other. The engine behind `reason network`.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1081 | +972 | +108 | 87 | 8 | Rust | Apache-2.0 | 10-16（6 天前） | 今天 |

- **近 14 天每天新增**：`······▄▆▅▃█▆▄·` 0 0 0 0 0 0 108 179 157 65 268 184 119 0
- **势头**：比前 7 天快 9.0 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`coding-agents` `iroh` `mcp` `peer-to-peer` `reason`
- **主页**：<https://reasonmachines.com>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [ELY-Open-Source/ElyOffice](https://github.com/ELY-Open-Source/ElyOffice) · 🟢 窗口内 · 81.5 分

> Ely Office: offline-first desktop apps in Rust and GPUI

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 886 | +886 | +0 | 56 | 17 | Rust | MIT | 10-19（3 天前） | 今天 |

- **近 14 天每天新增**：`·········▇█▃▄·` 0 0 0 0 0 0 0 0 0 294 360 100 132 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://office.elygpui.com>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [feder-cr/git-ai](https://github.com/feder-cr/git-ai) · 🟢 窗口内 · 80.7 分

> Git designed for AI agents.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 966 | +831 | +135 | 93 | 1 | Go | — | 10-15（7 天前） | 今天 |

- **近 14 天每天新增**：`·····▃▂▃█▄▄▂▂·` 0 0 0 0 0 75 60 77 350 161 160 42 41 0
- **势头**：比前 7 天快 6.2 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `coding-agents` `git` `golang` `scion` `version-control`
- **主页**：<https://www.anthropic.com/engineering/redesigning-source-control>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) · 🟢 窗口内 · 80.2 分

> 麦当劳 MCP 聚会/团餐组织助手 — 基于 Model Context Protocol 的派对预订与团餐规划 CLI/Skill

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 874 | +801 | +73 | 52 | 2 | Python | MIT | 10-15（7 天前） | 2 天前 |

- **近 14 天每天新增**：`·····▂▃▅█▇▆▆▄·` 0 0 0 0 0 16 57 103 188 154 145 130 81 0
- **势头**：比前 7 天快 11.0 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) · 🟢 窗口内 · 79.7 分

> Co-op Anything: point your AI agent at any single-player game and play it with friends (online and/or splitscreen!). MCP server and playbook to let you reverse engineer, fix, test, ship and share what it learns.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 848 | +767 | +81 | 116 | 88 | Python | MIT | 10-16（6 天前） | 今天 |

- **近 14 天每天新增**：`······▃▅█▆▅▃▂·` 0 0 0 0 0 0 81 131 234 156 125 77 44 0
- **势头**：比前 7 天快 9.5 倍，在加速
- **HN**：发过 1 次，最高 1 分（[讨论](https://news.ycombinator.com/item?id=50177079)）
- **主页**：<https://coopanything.app>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 9. [kanaworksai-hue/audio-studio-mcp](https://github.com/kanaworksai-hue/audio-studio-mcp) · 🟢 窗口内 · 73.2 分

> Local AI BGM and sound effects for Claude Code and any MCP client. Stable Audio 3 on Apple Silicon (MLX) and Windows NVIDIA GPUs (PyTorch). No cloud, no API key.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 444 | +444 | +0 | 33 | 1 | Python | MIT | 10-18（4 天前） | 今天 |

- **近 14 天每天新增**：`········█▇▅▄▂·` 0 0 0 0 0 0 0 0 154 127 93 58 12 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`apple-silicon` `audio-generation` `claude-code` `cuda` `game-audio` `mcp` `mcp-server` `mlx` `music-generation` `pytorch` `sound-effects` `stable-audio` `windows`
- **主页**：<https://kanaworksai-hue.github.io/audio-studio-mcp/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 10. [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) · 🟢 窗口内 · 68.6 分

> AI生成の日本語を自然な日本語へ推敲するAgent Skill / Agent Skill for Refining AI-Generated Japanese into Natural Japanese

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2410 | +303 | +297 | 63 | 1 | Python | MIT | 09-30（22 天前） | 今天 |

- **近 14 天每天新增**：`▂▃▄▃▂▂█▇▄▅▅▃▂·` 23 37 49 33 18 22 115 91 44 61 60 28 19 0
- **势头**：和前 7 天差不多
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-writing` `antigravity` `claude-code` `codex` `cursor` `gemini` `japanese` `linter` `llm` `nlp` `writing` `writing-assistant` `writing-tool`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [realskyrin/ns-game-apple-arm-port](https://github.com/realskyrin/ns-game-apple-arm-port) — 一天进了一半以上的 star，但 HN 上没火过
- [torrentplayer/torrentplayer](https://github.com/torrentplayer/torrentplayer) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 930 | 420 | [Show HN: SimCity, but with Permits](https://permit.petercai.com/) | [HN](https://news.ycombinator.com/item?id=50170593) |
| 329 | 86 | [Show HN: Llmspeed – feel how fast a local LLM runs before you buy the hardware](https://llmspeed.dev/) | [HN](https://news.ycombinator.com/item?id=50127979) |
| 254 | 111 | [Show HN: Gemini 4 Argon plays StarCraft](https://starskirmish.com/bench/v0-2/) | [HN](https://news.ycombinator.com/item?id=50118688) |
| 252 | 89 | [Show HN: Sphinx – A hook that quizzes you on your AI's code before shipping](https://sphinx-six-theta.vercel.app/) | [HN](https://news.ycombinator.com/item?id=50137950) |
| 226 | 129 | [Show HN: The Zelda timeline to catch up before the Ocarina of Time remake](https://legendofhyrule.com/) | [HN](https://news.ycombinator.com/item?id=50140769) |
| 209 | 48 | [Show HN: Esp32sim – Run ESP32 firmware in the browser](https://github.com/mikroverk/esp32sim) | [HN](https://news.ycombinator.com/item?id=50131189) |
| 188 | 13 | [Show HN: VoidAccess – open-source dark web OSINT, from query to a graph](https://github.com/KatrielMoses/voidaccess) | [HN](https://news.ycombinator.com/item?id=50167286) |
| 179 | 48 | [Show HN: High-quality duck audio synthesizer](https://celphase.github.io/duck-pond/) | [HN](https://news.ycombinator.com/item?id=50131006) |
| 158 | 113 | [Show HN: Qwen3-4B with the AI writing tics trained out](https://100toolkit.com/blog/deslop-model/) | [HN](https://news.ycombinator.com/item?id=50151928) |
| 157 | 85 | [Show HN: WhatsApp MCP running free on Cloudflare](https://github.com/finereli/whatsapp-mcp) | [HN](https://news.ycombinator.com/item?id=50145715) |
| 110 | 34 | [Show HN: Omnara – Open-source alternative to Claude Managed Agents](https://github.com/omnara-ai/omnara) | [HN](https://news.ycombinator.com/item?id=50183892) |
| 108 | 66 | [Show HN: Death Plan Switch, a self-hosted dead man's switch for solo devs](https://deathplanswitch.com/) | [HN](https://news.ycombinator.com/item?id=50161408) |
| 96 | 27 | [Show HN: Sumi.css – CSS Framework](https://github.com/vladocar/Sumi.css) | [HN](https://news.ycombinator.com/item?id=50180039) |
| 94 | 23 | [Show HN: Uberblok – an interactive museum of ZFS internals](https://uberblok.storagebits.workers.dev/) | [HN](https://news.ycombinator.com/item?id=50180257) |
| 76 | 19 | [Show HN: Parin – A 2D game engine between raylib and Godot, written in Dlang](https://github.com/Kapendev/parin) | [HN](https://news.ycombinator.com/item?id=50118098) |
| 75 | 32 | [Show HN: 500 clocks in one 6.3 MB HTML file by Opus 5.5](https://tkgally.github.io/500-clocks/) | [HN](https://news.ycombinator.com/item?id=50137820) |
| 74 | 42 | [Show HN: UI micro interactions prompts for AI](https://www.typeui.sh/micro-interactions) | [HN](https://news.ycombinator.com/item?id=50199290) |
| 71 | 53 | [Show HN: Jev Cards, Can you beat a vision model at a picture quiz?](https://jevcards.com) | [HN](https://news.ycombinator.com/item?id=50167617) |
| 69 | 42 | [Show HN: KiviDB, a faster Redis-compatible memory database and vector cache](https://github.com/kividbio/kividb) | [HN](https://news.ycombinator.com/item?id=50152541) |
| 66 | 9 | [Show HN: Penmentor – Claude marks up your handwritten math like a teacher](https://github.com/AbdullahAlhariri/penmentor) | [HN](https://news.ycombinator.com/item?id=50167604) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 117 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 18000★ |
| 62 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 43217★ |
| 154 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 113091★ |
| 94 | [MOSS-Image Technical Report](https://huggingface.co/papers/2610.23374) | MOSS-Image is an open diffusion transformer that combines high-fidelity synthesis with intent-aware prompt enhancement to generate text-rich… | [OpenMOSS/MOSS-Image](https://github.com/OpenMOSS/MOSS-Image) 1481★ |
| 118 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 2302★ |
| 29 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 6438★ |
| 15 | [Next-Concept Modeling: Fast, Parallel Coarse-to-Fine Text Generation](https://huggingface.co/papers/2610.14162) | Next-Concept Modeling uses hierarchical discrete codes and parallel level-wise generation to accelerate diffusion language models while impr… | 💡 [HazyResearch/ncm](https://github.com/HazyResearch/ncm) 827★ |
| 53 | [Scaling in Games: Continued Pre-Training For Embodied Agents In Diverse Virtual Worlds](https://huggingface.co/papers/2610.28698) | Continued pre-training across data scale, diversity, and model size improves embodied learning in virtual worlds but reveals limits in dista… | 💡 [THUSI-Lab/GameScaling](https://github.com/THUSI-Lab/GameScaling) 231★ |
| 97 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 28227★ |
| 66 | [StartLux-Decision: AutoThink Decision Models with Reinforcement Learning for Calibrated Deliberative…](https://huggingface.co/papers/2610.17309) | StartLux-Decision introduces efficient and adaptive decision models using single-pass prediction and confidence-guided reasoning, trained vi… | [StartLuxLabs/StartLux-Decision](https://github.com/StartLuxLabs/StartLux-Decision) 1210★ |
| 139 | [Looking Ahead: Modeling Future Evolution in Autoregressive Video Generation](https://huggingface.co/papers/2610.29989) | Future Chunk Prediction improves autoregressive video diffusion by enforcing future-chunk supervision, yielding more physically plausible vi… | 💡 [TencentARC/Looking-Ahead](https://github.com/TencentARC/Looking-Ahead) 63★ |
| 31 | [Internal Safety Collapse in Frontier Large Language Models](https://huggingface.co/papers/2603.23509) | Frontier large language models exhibit Internal Safety Collapse, where they generate harmful content under specific task conditions, reveali… | [wuyoscar/ISC-Bench](https://github.com/wuyoscar/ISC-Bench) 2128★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 91582★ |
| 170 | [MemT-1.0: Towards Memory-Native Evolution](https://huggingface.co/papers/2610.26825) | MemT-1.0 introduces a memory-native architecture that embeds continuous memory into foundation model computation, improving long-context eff… | 💡 [MemTensor/MemT-1.0](https://github.com/MemTensor/MemT-1.0) 334★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 205 | [YuE2: Unifying Symbolic and Audio Music Generation at Frontier Quality](https://huggingface.co/papers/2609.33757) | YuE2 unifies symbolic and audio music generation via symbolic planning, producing readable scores and full-song audio with state-of-the-art… | [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE) 12538★ |
| 52 | [SolarRenderer: Few-Step Generative Reference Rendering](https://huggingface.co/papers/2610.28630) | SolarRenderer adapts a frozen video backbone with lightweight LoRAs to render realistic videos from diverse structural inputs in four steps… | 💡 [Enderfga/SolarRenderer](https://github.com/Enderfga/SolarRenderer) 249★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 82307★ |
| 179 | [SmolDocling: An ultra-compact vision-language model for end-to-end multi-modal document conversion](https://huggingface.co/papers/2503.11576) | SmolDocling is a compact vision-language model that performs end-to-end document conversion with robust performance across various document… | [docling-project/docling](https://github.com/docling-project/docling) 69374★ |
| 50 | [PrismaCoder: Pushing the Boundaries of Open Multimodal Code Intelligence through Decomposed Rubric S…](https://huggingface.co/papers/2610.20538) | PrismaForge uses a rubric-based pipeline to synthesize and filter high-quality multimodal code data, enabling open models that rival proprie… | 💡 [QiushiSun/PrismaCoder](https://github.com/QiushiSun/PrismaCoder) 36★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

_这次没有（新上榜 0 个）。_

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 37 | 9 | [Docker is weird](https://codeandcake.dev/posts/2026-10-22-docker-is-weird) | `programming` | [讨论](https://lobste.rs/s/xsz9sc/docker_is_weird) |
| 16 | 8 | [a hacky fucked up way to portably access errno from outside of c](https://sebsite.pw/w/20260925-errno.html) | `c` | [讨论](https://lobste.rs/s/jgull9/hacky_fucked_up_way_portably_access_errno) |
| 56 | 21 | [examining the macOS gcc binary](https://zoey-on-github.github.io/blog/macgcc.html) | `mac` `reversing` | [讨论](https://lobste.rs/s/hplfis/examining_macos_gcc_binary) |
| 38 | 0 | [Quad9 DNS Resolver to exit France](https://quad9.net/news/blog/au-revoir-france/) | `law` `networking` | [讨论](https://lobste.rs/s/s0aktw/quad9_dns_resolver_exit_france) |
| 6 | 1 | [UUIDv7 doesn't have the properties you think it does](https://alexsci.com/blog/uuidv7-is-weird/) | `distributed` `python` | [讨论](https://lobste.rs/s/kcyzco/uuidv7_doesn_t_have_properties_you_think) |
| 36 | 6 | [jailbreaking the switch 2](https://pepsipu.com/blog/2026-10-switch2-jailbreak-ns2jb/) | `ai-tooling` `hardware` `reversing` `security` | [讨论](https://lobste.rs/s/me75ey/jailbreaking_switch_2) |
| 14 | 0 | [Please don't mess with links](https://maurycyz.com/misc/real_links/) | `web` | [讨论](https://lobste.rs/s/mucay8/please_don_t_mess_with_links) |
| 10 | 4 | [We have Traits at Home](https://www.axelmagn.com/blog/202610-zig-traits/) | `zig` | [讨论](https://lobste.rs/s/05xrj8/we_have_traits_at_home) |
| 19 | 3 | [Objects, attributes, maps, oh my](https://bernsteinbear.com/blog/object-shapes/) | `compilers` | [讨论](https://lobste.rs/s/8rkyrl/objects_attributes_maps_oh_my) |
| 19 | 3 | [Expose only share links of a private service with caddy](https://dataswamp.org/~solene/2026-10-21-caddy-forward-auth-public-share-links.html) | `devops` `security` | [讨论](https://lobste.rs/s/tu5ynp/expose_only_share_links_private_service) |
| 18 | 8 | [Tell your network to explain itself and then some](https://unixdigest.com/tutorials/tell-your-network-to-explain-itself-and-then-some.html) | `networking` | [讨论](https://lobste.rs/s/m6l6ld/tell_your_network_explain_itself_then) |
| 15 | 7 | [I built a garbage collector for Rust (2023)](https://claytonwramsey.com/blog/dumpster/) | `rust` | [讨论](https://lobste.rs/s/ju4q1u/i_built_garbage_collector_for_rust_2023) |
| 141 | 24 | [Firefox Local Mode](https://firefox-source-docs.mozilla.org/devtools-user/local_mode/index.html) | `browsers` | [讨论](https://lobste.rs/s/w9sxxq/firefox_local_mode) |
| 17 | 2 | [Script dependencies with Nix](https://entropicthoughts.com/python-dependencies-with-nix) | `nix` | [讨论](https://lobste.rs/s/oeehgs/script_dependencies_with_nix) |
| 32 | 5 | [Using a lookup-table to correct an approximation](https://www.corsix.org/content/using-a-lookup-table-to-correct-an-approximation) | `performance` | [讨论](https://lobste.rs/s/os7brs/using_lookup_table_correct) |
| 49 | 17 | [Google's Rust Style Guide](https://google.github.io/styleguide/rustguide.html) | `rust` | [讨论](https://lobste.rs/s/9jgl3x/google_s_rust_style_guide) |
| 27 | 0 | [Announcing DuckDB 2.0.0 LTS “Cinnamon Teal”](https://duckdb.org/2026/10/21/announcing-duckdb-200.html) | `databases` `release` | [讨论](https://lobste.rs/s/dcvs3u/announcing_duckdb_2_0_0_lts_cinnamon_teal) |
| 76 | 26 | [Eight Bits of Trust; eMudhra's CA keys cracked in milliseconds](https://scotthelme.co.uk/eight-bits-of-trust-emudhras-ca-keys-cracked-in-milliseconds/) | `cryptography` `security` | [讨论](https://lobste.rs/s/ebsqsp/eight_bits_trust_emudhra_s_ca_keys_cracked) |
| 8 | 0 | [Header Accordions: QPACK amplification attacks against HTTP/3 servers](https://foxio.io/blog/header-accordions-qpack-amplification-attacks-against-http-3-servers) | `security` | [讨论](https://lobste.rs/s/l2l50n/header_accordions_qpack_amplification) |
| 11 | 24 | [What is your opinion on submission quality since the `vibecoding` tag was removed?](https://lobste.rs/s/nmurnh) | `meta` | [讨论](https://lobste.rs/s/nmurnh/what_is_your_opinion_on_submission) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

_还没有到 14 天的，78 个在等。_

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
