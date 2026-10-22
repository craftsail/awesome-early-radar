# early-radar 选题雷达 · 2026-10-22

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 106 个，细查前 20 个 · 比上次 = 和 2026-10-21 那次比 · 生成于 2026-10-22 04:18 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 4 个 · Show HN ✅ 23 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 0 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 10 个 · 🟡 在降温 7 个 · 🔵 已被发现 1 个 · 💤 不活跃 0 个 · 🔴 先核对 2 个
- **今天新出现 2 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) 平均每天 +4156，见 [爆发](#爆发)
- **最值得今天试的**：
  - [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) — Ears for coding agents: let AI hear, review and make sound.…（近 7 天 +1949，比前 7 天快 17.4 倍，在加速）
  - [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) — 让你的agent一键直出商业级产品宣传片：会作曲，能指着画面改。Commercial-grade launch film…（近 7 天 +1303，刚发布一周内）
  - [aicodeking/leanrea](https://github.com/aicodeking/leanrea) — One 8 KB skill that replaces REA (Reverse Engineer Anything)…（近 7 天 +1307，刚发布一周内）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 22 个（star 合计 23974），代表：[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：6 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: SimCity, but with Permits](https://permit.petercai.com/) — 909 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) | 20106 | 4156 | +7073 | 4.8 | [6](https://news.ycombinator.com/item?id=50164485) | cleanyourtv · gathin23 cleanyourtv · gathin cleanyourtv | Debloat any Android or Google TV over Wi-Fi and get an Apple… |
| [deepseek-ai/DeepInfer](https://github.com/deepseek-ai/DeepInfer) | 18405 | 3144 | +4118 | 5.9 | [2304](https://news.ycombinator.com/item?id=50163277) | deepinfer · deepseek-ai deepinfer · deepseek deepinfer | DeepInfer: High-performance, large-scale inference framework… |
| [pengchujin/aerial-tv](https://github.com/pengchujin/aerial-tv) | 2363 | 1316 | +1385 | 1.8 | — | aerial tv · pengchujin aerial tv | 给国产电视的一块干净桌面：参照 tvOS 设计的开源 Android TV 桌面，没有广告，开机自动接管。A tvOS-… |
| [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) | 18652 | 1356 | +925 | 13.8 | — | anatomy · wheresryan22 anatomy · ryan anatomy | An agent skill for creating detailed, interactive isometric… |
| [simbasjungles/free-my-tv](https://github.com/simbasjungles/free-my-tv) | 2820 | 1191 | +877 | 2.4 | — | free my tv · simbasjungles free my tv · simba free my tv | A fast, ad-free home screen for Google TV. Open source, buil… |
| 🆕 [ikow/php2shell-poc](https://github.com/ikow/php2shell-poc) | 1104 | 1104 | — | 1 | — | php2shell poc · ikow php2shell poc · qi php2shell poc | CVE-2026-109618/109619 — 5 RCE chains + detection rules (Sur… |
| [ly05010419/MacNativeGames](https://github.com/ly05010419/MacNativeGames) | 4007 | 921 | +1024 | 4.4 | — | macnativegames · ly05010419 macnativegames · yong macnativegames |  |
| 🆕 [eness/php2shell-CVE-2026-109618-CVE-2026-109619-PoC](https://github.com/eness/php2shell-CVE-2026-109618-CVE-2026-109619-PoC) | 657 | 657 | — | 1 | — | php2shell cve 2026 109618 cve 2026 109619 poc · eness php2shell cve 2026 109618 cve 2026 109619 poc · enes php2shell cve 2026 109618 cve 2026 109619 poc | Proof-of-Concept (PoC) exploit for php2shell (CVE-2026-10961… |
| 🆕 [9bie/php2shell-bypass-aslr-exp](https://github.com/9bie/php2shell-bypass-aslr-exp) | 615 | 615 | — | 1 | — | php2shell bypass aslr exp · 9bie php2shell bypass aslr exp |  |
| [JoasASantos/REA-Prompts](https://github.com/JoasASantos/REA-Prompts) | 1368 | 608 | +302 | 2.2 | — | rea prompts · joasasantos rea prompts · joas rea prompts | REAP - Prompts for you to use REA (Reverse Engineer Anything… |
| [xiaoyang111222/cn-math-taxonomy](https://github.com/xiaoyang111222/cn-math-taxonomy) | 2036 | 536 | +363 | 3.8 | — | cn math taxonomy · xiaoyang111222 cn math taxonomy | 中小学知识图谱 + 前置诊断：数学（一–九年级、高中必修与选择性必修）+ 英语（小学、初中、高中），课标对齐、人教版，1… |
| 🆕 [ctresb/leis](https://github.com/ctresb/leis) | 1047 | 147 | +516 | 7.1 | — | leis · ctresb leis | Todas as leis do Brasil |
| 🆕 [eagle-hq/EAGLE-4](https://github.com/eagle-hq/EAGLE-4) | 747 | 469 | — | 1.6 | [2](https://news.ycombinator.com/item?id=50184118) | eagle 4 · eagle-hq eagle 4 · eagle eagle 4 | Official Inference Code of EAGLE-4 |
| [jhaizhou-ops/d2r-mobile](https://github.com/jhaizhou-ops/d2r-mobile) | 4334 | 441 | +131 | 9.8 | — | d2r mobile · jhaizhou-ops d2r mobile | Open-source iOS / macOS compatibility layer for Diablo II: R… |
| 🆕 [openai/php2shell-checker](https://github.com/openai/php2shell-checker) | 499 | 431 | — | 1.2 | [2](https://news.ycombinator.com/item?id=50184078) | php2shell checker · openai php2shell checker |  |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 90.9 | 🟢 窗口内 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) | Python | 2061 | +78 | +1949 | +112 | `······▂▄▄▄█▅▂·` | 6 | — | — |
| 2 | 86.1 | 🟢 窗口内 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 1303 | +125 | +1303 | +0 | `·········█▆▃▂·` | 3 | — | — |
| 3 | 86.1 | 🟢 窗口内 | [aicodeking/leanrea](https://github.com/aicodeking/leanrea) | Python | 1307 | +117 | +1307 | +0 | `·······▁█▄▆▃▃·` | 5 | — | — |
| 4 | 82.6 | 🟢 窗口内 | [LiCinCan/blender-ai-mcp-addon](https://github.com/LiCinCan/blender-ai-mcp-addon) | Python | 976 | +36 | +976 | +0 | `·······▆█▅▄▂▂·` | 6 | — | — |
| 5 | 82.2 | 🟢 窗口内 | [reason-machines/reason-network](https://github.com/reason-machines/reason-network) | Rust | 943 | +201 | +943 | +0 | `·······▄▆▅▃█▅·` | 5 | — | — |
| 6 | 80.9 | 🟢 窗口内 | [feder-cr/git-ai](https://github.com/feder-cr/git-ai) | Go | 922 | -367 | +847 | +75 | `······▃▂▃█▄▄▂·` | 6 | — | — |
| 7 | 80.2 | 🟢 窗口内 | [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) | Python | 800 | +79 | +800 | +0 | `·······▃▅█▆▅▃·` | 5 | [1](https://news.ycombinator.com/item?id=50177079) | — |
| 8 | 79.8 | 🟢 窗口内 | [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) | Python | 790 | +139 | +774 | +16 | `······▂▃▅█▇▆▆·` | 6 | — | — |
| 9 | 79.1 | 🟢 窗口内 | [ELY-Open-Source/ElyOffice](https://github.com/ELY-Open-Source/ElyOffice) | Rust | 730 | +92 | +730 | +0 | `··········▇█▂·` | 2 | — | — |
| 10 | 72.8 | 🆕 🟢 窗口内 | [kanaworksai-hue/audio-studio-mcp](https://github.com/kanaworksai-hue/audio-studio-mcp) | Python | 429 | +65 | +429 | +0 | `·········█▇▅▄·` | 3 | — | — |
| 11 | 63.9 | 🟡 在降温 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 1624 | +119 | +594 | +1030 | `···█▃▂▂▁▁▁▁▅▂·` | 9 | — | — |
| 12 | 63.5 | 🟡 在降温 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 1813 | +62 | +569 | +1244 | `··▁▆█▄▃▃▃▂▂▂▂·` | 11 | — | — |
| 13 | 62.4 | 🟡 在降温 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | Python | 2002 | +43 | +512 | +1453 | `▁▁█▆▃▂▄▃▂▂▂▂▁·` | 16 | [10](https://news.ycombinator.com/item?id=50037852) | — |
| 14 | 59.9 | 🟡 在降温 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) | Go | 1594 | +110 | +400 | +1192 | `▁▁▁█▆▁▁▁▁▁▂▂▂·` | 13 | — | — |
| 15 | 58.6 | 🟡 在降温 | [jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) | Python | 1165 | +10 | +350 | +815 | `··█▄▇▂▁▁▄▃▂▂▁·` | 10 | — | — |
| 16 | 54 | 🟡 在降温 | [marclou/mailcheap](https://github.com/marclou/mailcheap) | JavaScript | 1295 | +19 | +220 | +1075 | `·█▄▂▂▁▃▂▁▁▁▁▁·` | 11 | [2](https://news.ycombinator.com/item?id=50033695) | — |
| 17 | 50.5 | 🟡 在降温 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry) | TypeScript | 1647 | +12 | +155 | +1355 | `█▇▄▂▂▂▁▁▂▁▁▁▁·` | 14 | — | — |
| 18 | 36.4 | 🆕 🔴 先核对 | [realskyrin/ns-game-apple-arm-port](https://github.com/realskyrin/ns-game-apple-arm-port) | — | 429 | — | +429 | +0 | `········▁▃▃▃█·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 25.5 | 🔵 已被发现 | [rociiu/talorys](https://github.com/rociiu/talorys) | TypeScript | 1366 | +6 | +164 | +1202 | `·█▅▃▂▂▄▂▂▁▁▁▁·` | 11 | [331](https://news.ycombinator.com/item?id=50031614) | — |
| 20 | 23.4 | 🔴 先核对 | [outcrawlai/scout](https://github.com/outcrawlai/scout) | TypeScript | 959 | +1 | +107 | +852 | `·····█▂▁▁▁▁▁▁·` | 8 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 545 | 30 | 44581 | [feitangyuan/onetake](https://github.com/feitangyuan/onetake)、[dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) |
| `mcp` | 220 | 30 | 29298 | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[amontlabs/lcu](https://github.com/amontlabs/lcu) |
| `rust` | 170 | 30 | 19556 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx)、[opengeos/RustGIS](https://github.com/opengeos/RustGIS)、[oxc-project/tsrs](https://github.com/oxc-project/tsrs) |
| `local-first` | 58 | 30 | 10622 | [glanderness/BeefTV](https://github.com/glanderness/BeefTV)、[HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 22 | 23974 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) |
| `llm` | 16 | 12762 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) |
| `ai-agents` | 16 | 11568 | [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `codex` | 13 | 14402 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui) |
| `mcp-server` | 13 | 9423 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[LiCinCan/blender-ai-mcp-addon](https://github.com/LiCinCan/blender-ai-mcp-addon) |
| `agent-skills` | 12 | 16320 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[amontlabs/lcu](https://github.com/amontlabs/lcu) |
| `ai-agent` | 12 | 9596 | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `developer-tools` | 9 | 7968 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[mikehasa/golive-skill](https://github.com/mikehasa/golive-skill)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) |
| `macos` | 8 | 4927 | [amontlabs/lcu](https://github.com/amontlabs/lcu)、[kitlangton/scrawl](https://github.com/kitlangton/scrawl)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch) |
| `coding-agents` | 7 | 7829 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[openfilm/openfilm](https://github.com/openfilm/openfilm)、[reason-machines/reason-network](https://github.com/reason-machines/reason-network) |
| `typescript` | 7 | 7317 | [dzhng/jevgrep](https://github.com/dzhng/jevgrep)、[pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `python` | 7 | 5326 | [jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai)、[Harvil1/codeAgent](https://github.com/Harvil1/codeAgent)、[LiCinCan/blender-ai-mcp-addon](https://github.com/LiCinCan/blender-ai-mcp-addon) |

**语言分布**：Python 34 · Rust 29 · TypeScript 20 · JavaScript 10 · Go 3 · Swift 3 · Astro 1 · C++ 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) · 🟢 窗口内 · 90.9 分

> Ears for coding agents: let AI hear, review and make sound. CPU-only, open source.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2061 | +1949 | +112 | 117 | 4 | Python | MIT | 10-15（6 天前） | 3 天前 |

- **近 14 天每天新增**：`······▂▄▄▄█▅▂·` 0 0 0 0 0 0 112 309 285 263 680 344 68 0
- **势头**：比前 7 天快 17.4 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `audio` `claude-code` `mcp` `sound-design`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) · 🟢 窗口内 · 86.1 分

> 让你的agent一键直出商业级产品宣传片：会作曲，能指着画面改。Commercial-grade launch films by your coding agent — point at the frame to change it.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1303 | +1303 | +0 | 127 | 2 | JavaScript | MIT | 10-18（3 天前） | 2 天前 |

- **近 14 天每天新增**：`·········█▆▃▂·` 0 0 0 0 0 0 0 0 0 581 440 170 112 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `animation` `claude-code` `codex` `gsap` `launch-video` `motion-graphics` `skills`
- **主页**：<https://github.com/alchaincyf/huashu-motion>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [aicodeking/leanrea](https://github.com/aicodeking/leanrea) · 🟢 窗口内 · 86.1 分

> One 8 KB skill that replaces REA (Reverse Engineer Anything): plain CLI tools, no MCP. Benchmarked: 38% faster, 35% cheaper.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1307 | +1307 | +0 | 196 | 6 | Python | MIT | 10-17（5 天前） | 2 天前 |

- **近 14 天每天新增**：`·······▁█▄▆▃▃·` 0 0 0 0 0 0 0 26 466 219 322 166 108 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [LiCinCan/blender-ai-mcp-addon](https://github.com/LiCinCan/blender-ai-mcp-addon) · 🟢 窗口内 · 82.6 分

> AI assistant and MCP server for Blender: visual chat, scene tools, multi-agent workflows. Works with OpenAI, ChatGPT, Claude, Gemini, Ollama, OpenCode. Blender AI addon and plugin, copilot for 3D, bpy Python scripting, MCP integration.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 976 | +976 | +0 | 390 | 31 | Python | MIT | 10-15（6 天前） | 今天 |

- **近 14 天每天新增**：`·······▆█▅▄▂▂·` 0 0 0 0 0 0 0 255 336 197 135 26 27 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-assistant` `blender` `blender-addon` `blender-ai` `blender-automation` `blender-extension` `blender-mcp` `blender-plugin` `blender-python` `blender-scripting` `bpy` `chatgpt` `gpt` `llm` `mcp` `mcp-for-blender` `mcp-server` `model-context-protocol` `opencode` `python`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [reason-machines/reason-network](https://github.com/reason-machines/reason-network) · 🟢 窗口内 · 82.2 分

> Reason Network: your team's coding agents, talking to each other. The engine behind `reason network`.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 943 | +943 | +0 | 76 | 1 | Rust | Apache-2.0 | 10-16（5 天前） | 今天 |

- **近 14 天每天新增**：`·······▄▆▅▃█▅·` 0 0 0 0 0 0 0 108 180 157 65 269 164 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`coding-agents` `iroh` `mcp` `peer-to-peer` `reason`
- **主页**：<https://reasonmachines.com>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [feder-cr/git-ai](https://github.com/feder-cr/git-ai) · 🟢 窗口内 · 80.9 分

> Git designed for AI agents.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 922 | +847 | +75 | 85 | 1 | Go | — | 10-15（6 天前） | 今天 |

- **近 14 天每天新增**：`······▃▂▃█▄▄▂·` 0 0 0 0 0 0 75 60 77 350 161 160 39 0
- **势头**：比前 7 天快 11.3 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `coding-agents` `git` `golang` `scion` `version-control`
- **主页**：<https://www.anthropic.com/engineering/redesigning-source-control>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) · 🟢 窗口内 · 80.2 分

> Co-op Anything: point your AI agent at any single-player game and play it with friends (online and/or splitscreen!). MCP server and playbook to let you reverse engineer, fix, test, ship and share what it learns.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 800 | +800 | +0 | 101 | 72 | Python | MIT | 10-16（5 天前） | 今天 |

- **近 14 天每天新增**：`·······▃▅█▆▅▃·` 0 0 0 0 0 0 0 81 131 234 156 125 73 0
- **势头**：刚发布一周内
- **HN**：发过 1 次，最高 1 分（[讨论](https://news.ycombinator.com/item?id=50177079)）
- **主页**：<https://coopanything.app>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) · 🟢 窗口内 · 79.8 分

> 麦当劳 MCP 聚会/团餐组织助手 — 基于 Model Context Protocol 的派对预订与团餐规划 CLI/Skill

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 790 | +774 | +16 | 45 | 2 | Python | MIT | 10-15（6 天前） | 1 天前 |

- **近 14 天每天新增**：`······▂▃▅█▇▆▆·` 0 0 0 0 0 0 16 57 103 188 154 145 127 0
- **势头**：比前 7 天快 48.4 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 9. [ELY-Open-Source/ElyOffice](https://github.com/ELY-Open-Source/ElyOffice) · 🟢 窗口内 · 79.1 分

> Ely Office: offline-first desktop apps in Rust and GPUI

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 730 | +730 | +0 | 48 | 7 | Rust | MIT | 10-19（2 天前） | 今天 |

- **近 14 天每天新增**：`··········▇█▂·` 0 0 0 0 0 0 0 0 0 0 294 360 76 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://office.elygpui.com>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 10. 🆕 [kanaworksai-hue/audio-studio-mcp](https://github.com/kanaworksai-hue/audio-studio-mcp) · 🟢 窗口内 · 72.8 分

> Local AI BGM and sound effects for Claude Code and any MCP client. Stable Audio 3 on Apple Silicon (MLX) and Windows NVIDIA GPUs (PyTorch). No cloud, no API key.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 429 | +429 | +0 | 31 | 1 | Python | MIT | 10-18（3 天前） | 2 天前 |

- **近 14 天每天新增**：`·········█▇▅▄·` 0 0 0 0 0 0 0 0 0 154 127 93 55 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`apple-silicon` `audio-generation` `claude-code` `cuda` `game-audio` `mcp` `mcp-server` `mlx` `music-generation` `pytorch` `sound-effects` `stable-audio` `windows`
- **主页**：<https://kanaworksai-hue.github.io/audio-studio-mcp/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [realskyrin/ns-game-apple-arm-port](https://github.com/realskyrin/ns-game-apple-arm-port) — 一天进了一半以上的 star，但 HN 上没火过
- [outcrawlai/scout](https://github.com/outcrawlai/scout) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 909 | 410 | [Show HN: SimCity, but with Permits](https://permit.petercai.com/) | [HN](https://news.ycombinator.com/item?id=50170593) |
| 329 | 86 | [Show HN: Llmspeed – feel how fast a local LLM runs before you buy the hardware](https://llmspeed.dev/) | [HN](https://news.ycombinator.com/item?id=50127979) |
| 319 | 201 | [Show HN: Unfenced – Land for sale that borders public land](https://unfenced.land/) | [HN](https://news.ycombinator.com/item?id=50102247) |
| 254 | 111 | [Show HN: Gemini 4 Argon plays StarCraft](https://starskirmish.com/bench/v0-2/) | [HN](https://news.ycombinator.com/item?id=50118688) |
| 252 | 89 | [Show HN: Sphinx – A hook that quizzes you on your AI's code before shipping](https://sphinx-six-theta.vercel.app/) | [HN](https://news.ycombinator.com/item?id=50137950) |
| 225 | 129 | [Show HN: The Zelda timeline to catch up before the Ocarina of Time remake](https://legendofhyrule.com/) | [HN](https://news.ycombinator.com/item?id=50140769) |
| 207 | 48 | [Show HN: Esp32sim – Run ESP32 firmware in the browser](https://github.com/mikroverk/esp32sim) | [HN](https://news.ycombinator.com/item?id=50131189) |
| 188 | 13 | [Show HN: VoidAccess – open-source dark web OSINT, from query to a graph](https://github.com/KatrielMoses/voidaccess) | [HN](https://news.ycombinator.com/item?id=50167286) |
| 178 | 47 | [Show HN: High-quality duck audio synthesizer](https://celphase.github.io/duck-pond/) | [HN](https://news.ycombinator.com/item?id=50131006) |
| 158 | 113 | [Show HN: Qwen3-4B with the AI writing tics trained out](https://100toolkit.com/blog/deslop-model/) | [HN](https://news.ycombinator.com/item?id=50151928) |
| 157 | 84 | [Show HN: WhatsApp MCP running free on Cloudflare](https://github.com/finereli/whatsapp-mcp) | [HN](https://news.ycombinator.com/item?id=50145715) |
| 148 | 73 | [Show HN: Flipflop – Iroh-powered persistent tunnels for filesharing](https://github.com/andunieee/flipflop) | [HN](https://news.ycombinator.com/item?id=50099136) |
| 107 | 36 | [Show HN: Proa – A Rust web framework with fast SSR and multi-target rendering](https://proa.so/) | [HN](https://news.ycombinator.com/item?id=50105467) |
| 104 | 65 | [Show HN: Death Plan Switch, a self-hosted dead man's switch for solo devs](https://deathplanswitch.com/) | [HN](https://news.ycombinator.com/item?id=50161408) |
| 78 | 19 | [Show HN: Sumi.css – CSS Framework](https://github.com/vladocar/Sumi.css) | [HN](https://news.ycombinator.com/item?id=50180039) |
| 75 | 32 | [Show HN: 500 clocks in one 6.3 MB HTML file by Opus 5.5](https://tkgally.github.io/500-clocks/) | [HN](https://news.ycombinator.com/item?id=50137820) |
| 75 | 19 | [Show HN: Parin – A 2D game engine between raylib and Godot, written in Dlang](https://github.com/Kapendev/parin) | [HN](https://news.ycombinator.com/item?id=50118098) |
| 71 | 51 | [Show HN: Jev Cards, Can you beat a vision model at a picture quiz?](https://jevcards.com) | [HN](https://news.ycombinator.com/item?id=50167617) |
| 69 | 42 | [Show HN: KiviDB, a faster Redis-compatible memory database and vector cache](https://github.com/kividbio/kividb) | [HN](https://news.ycombinator.com/item?id=50152541) |
| 64 | 7 | [Show HN: Penmentor – Claude marks up your handwritten math like a teacher](https://github.com/AbdullahAlhariri/penmentor) | [HN](https://news.ycombinator.com/item?id=50167604) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 117 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 17240★ |
| 62 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 42816★ |
| 90 | [MOSS-Image Technical Report](https://huggingface.co/papers/2610.23374) | MOSS-Image is an open diffusion transformer that combines high-fidelity synthesis with intent-aware prompt enhancement to generate text-rich… | [OpenMOSS/MOSS-Image](https://github.com/OpenMOSS/MOSS-Image) 1311★ |
| 154 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 112614★ |
| 118 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 2148★ |
| 29 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 6201★ |
| 12 | [Next-Concept Modeling: Fast, Parallel Coarse-to-Fine Text Generation](https://huggingface.co/papers/2610.14162) | Next-Concept Modeling uses hierarchical discrete codes and parallel level-wise generation to accelerate diffusion language models while impr… | 💡 [HazyResearch/ncm](https://github.com/HazyResearch/ncm) 702★ |
| 24 | [StartLux-Decision: AutoThink Decision Models with Reinforcement Learning for Calibrated Deliberative…](https://huggingface.co/papers/2610.17309) | StartLux-Decision introduces efficient and adaptive decision models using single-pass prediction and confidence-guided reasoning, trained vi… | [StartLuxLabs/StartLux-Decision](https://github.com/StartLuxLabs/StartLux-Decision) 1110★ |
| 48 | [SolarRenderer: Few-Step Generative Reference Rendering](https://huggingface.co/papers/2610.28630) | SolarRenderer adapts a frozen video backbone with lightweight LoRAs to render realistic videos from diverse structural inputs in four steps… | 💡 [Enderfga/SolarRenderer](https://github.com/Enderfga/SolarRenderer) 215★ |
| 31 | [Internal Safety Collapse in Frontier Large Language Models](https://huggingface.co/papers/2603.23509) | Frontier large language models exhibit Internal Safety Collapse, where they generate harmful content under specific task conditions, reveali… | [wuyoscar/ISC-Bench](https://github.com/wuyoscar/ISC-Bench) 2052★ |
| 97 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 28086★ |
| 224 | [YuE2: Unifying Symbolic and Audio Music Generation at Frontier Quality](https://huggingface.co/papers/2609.33757) | YuE2 unifies symbolic and audio music generation via symbolic planning, producing readable scores and full-song audio with state-of-the-art… | [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE) 12482★ |
| 160 | [MemT-1.0: Towards Memory-Native Evolution](https://huggingface.co/papers/2610.26825) | MemT-1.0 introduces a memory-native architecture that embeds continuous memory into foundation model computation, improving long-context eff… | 💡 [MemTensor/MemT-1.0](https://github.com/MemTensor/MemT-1.0) 272★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 91484★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 460 | [Has GPT-6-Astra Achieved Embodied Intelligence?](https://huggingface.co/papers/2610.22471) | GPT-6-Astra achieves high performance across diverse robotic tasks via in-context learning, yet real-world deployment reveals gaps in demons… | 💡 [OpenSenseNova/SenseNova-RoboRSI](https://github.com/OpenSenseNova/SenseNova-RoboRSI) 224★ |
| 331 | [OpenGCUA: Toward a Fully Open Stack for Generalist Computer Use](https://huggingface.co/papers/2610.22200) | OpenGCUA introduces an open generalist computer-use agent that integrates visual and programmatic interfaces, harness-to-model decision tran… | 💡 [Tongyi-MAI/OpenGCUA](https://github.com/Tongyi-MAI/OpenGCUA) 396★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 82216★ |
| 103 | [OpenVLHarness: Real World Visual Agentic Tool-Use with Multimodal Memory](https://huggingface.co/papers/2610.26860) | OpenVLHarness improves multimodal reasoning by integrating persistent memory, heterogeneous tool interfaces, and iterative evidence composit… | 💡 [uclanlp/OpenVLHarness](https://github.com/uclanlp/OpenVLHarness) 167★ |
| 179 | [SmolDocling: An ultra-compact vision-language model for end-to-end multi-modal document conversion](https://huggingface.co/papers/2503.11576) | SmolDocling is a compact vision-language model that performs end-to-end document conversion with robust performance across various document… | [docling-project/docling](https://github.com/docling-project/docling) 69279★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 15 | [flint](https://huggingface.co/RecursiveSI/flint) | text-generation | 286 | 1 |
| 28 | [spark x2.6](https://huggingface.co/XHToken/Spark-X2.6-4B) | text-generation | 190 | 1 |
| 29 | [sage a1.5](https://huggingface.co/InternScience/Sage-A1.5) | text-generation | 167 | 1 |
| 40 | [fibo 2.0](https://huggingface.co/Comfy-Org/Fibo-2.0) | — | 124 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 80 | 16 | [Firefox Local Mode](https://firefox-source-docs.mozilla.org/devtools-user/local_mode/index.html) | `browsers` | [讨论](https://lobste.rs/s/w9sxxq/firefox_local_mode) |
| 183 | 119 | [Upcoming Critical PHP Security Release](https://www.php.net/archive/2026.php#2026-10-20-1) | `php` `security` | [讨论](https://lobste.rs/s/ekxoyt/upcoming_critical_php_security_release) |
| 56 | 2 | [zls 0.17.0](https://zigtools.org/zls/releases/0.17.0/) | `release` `zig` | [讨论](https://lobste.rs/s/hty1qk/zls_0_17_0) |
| 44 | 10 | [Eight Bits of Trust; eMudhra's CA keys cracked in milliseconds](https://scotthelme.co.uk/eight-bits-of-trust-emudhras-ca-keys-cracked-in-milliseconds/) | `cryptography` `security` | [讨论](https://lobste.rs/s/ebsqsp/eight_bits_trust_emudhra_s_ca_keys_cracked) |
| 23 | 7 | [Google's Rust Style Guide](https://google.github.io/styleguide/rustguide.html) | `rust` | [讨论](https://lobste.rs/s/9jgl3x/google_s_rust_style_guide) |
| 27 | 5 | [CVE-2026-107891: musl libc: multiple integer overflow in regcomp, possibly leading to incorrect allo…](https://www.openwall.com/lists/oss-security/2026/10/21/18) | `c` `security` | [讨论](https://lobste.rs/s/dldfel/cve_2026_107891_musl_libc_multiple) |
| 16 | 21 | [Passkeys Attestation Trap](https://mjtsai.com/blog/2026/10/15/passkeys-attestation-trap/) | `security` `web` | [讨论](https://lobste.rs/s/cdnepk/passkeys_attestation_trap) |
| 58 | 7 | [Unikernels in OCaml](https://uniker.nl/) | `ml` `osdev` | [讨论](https://lobste.rs/s/mfserj/unikernels_ocaml) |
| 58 | 6 | [The Future of CSS](https://www.joshwcomeau.com/css/interop-2027/) | `css` | [讨论](https://lobste.rs/s/vidyh0/future_css) |
| 11 | 2 | [Railway Security Disclosure: Wednesday October 21st](https://blog.railway.com/p/security-disclosure-wednesday-october-21st) | `devops` `security` | [讨论](https://lobste.rs/s/wi4nnl/railway_security_disclosure_wednesday) |
| 16 | 2 | [Flow Typing, A New Lens on Linearity](https://jaredforsyth.com/posts/papers-we-love-lens-on-linearity/) | `plt` | [讨论](https://lobste.rs/s/cquwex/flow_typing_new_lens_on_linearity) |
| 19 | 0 | [Don't throw it all away: Caching an immediate-mode UI](https://blickeditor.com/blog/caching-an-immediate-mode-ui) | `graphics` `performance` | [讨论](https://lobste.rs/s/cq7wn7/don_t_throw_it_all_away_caching_immediate) |
| 168 | 69 | [Protecting Firefox users following the compromise of eMudhra intermediate certificates](https://blog.mozilla.org/security/2026/10/20/protecting-firefox-users-following-the-compromise-of-emudhra-intermediate-certificates/) | `security` | [讨论](https://lobste.rs/s/gqyvn5/protecting_firefox_users_following) |
| 10 | 2 | [GitLab Critical Patch Release](https://docs.gitlab.com/releases/patches/patch-release-gitlab-19-5-1-released/) | `security` `vcs` | [讨论](https://lobste.rs/s/pnpcso/gitlab_critical_patch_release) |
| 36 | 2 | [Vector Graphics in Lil](https://beyondloom.com/blog/vectorgraphics.html) | `apl` `graphics` | [讨论](https://lobste.rs/s/tsfina/vector_graphics_lil) |
| 6 | 0 | [Understanding Nix flakes](https://lwn.net/SubscriberLink/1094226/7bb13383b169d475/) | `nix` | [讨论](https://lobste.rs/s/wno4h3/understanding_nix_flakes) |
| 14 | 1 | [Node.js — Wednesday, October 21, 2026 Security Releases](https://nodejs.org/en/blog/vulnerability/october-2026-security-releases) | `javascript` `nodejs` `security` | [讨论](https://lobste.rs/s/gu7bow/node_js_wednesday_october_21_2026) |
| 4 | 0 | [Embedding EYG in Erlang programs](https://eyg.run/guides/embedding-eyg-in-erlang-programs) | `erlang` | [讨论](https://lobste.rs/s/deqmg0/embedding_eyg_erlang_programs) |
| 39 | 12 | [Lobsters NYC Meetup on the 28th of October](https://lobste.rs/s/73ozwc) | `event` | [讨论](https://lobste.rs/s/73ozwc/lobsters_nyc_meetup_on_28th_october) |
| 5 | 0 | [Compromised LiteLLM 1.107.0 on PyPI Installs a Credential Stealer and Backdoor](https://safedep.io/litellm-pypi-compromise-credential-stealer-backdoor) | `ai-tooling` `security` | [讨论](https://lobste.rs/s/2czsv4/compromised_litellm_1_107_0_on_pypi) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

_还没有到 14 天的，71 个在等。_

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
