# early-radar 选题雷达 · 2026-10-28

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 107 个，细查前 20 个 · 比上次 = 和 2026-10-27 那次比 · 生成于 2026-10-28 05:12 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 3 个 · Show HN ✅ 20 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 5 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 6 个 · 🟡 在降温 8 个 · 🔵 已被发现 0 个 · 💤 不活跃 1 个 · 🔴 先核对 5 个
- **今天新出现 1 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) 平均每天 +3884，见 [爆发](#爆发)
- **复盘**：🚀 爆发 3/5 · 🔴 先核对 5/6 · 🟡 在降温 0/5 · 🔵 已被发现 0/2 · 🟢 窗口内 4/6（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [indexable-inc/blaze](https://github.com/indexable-inc/blaze) — Incremental rust builds up to 92x faster than cargo/rustc（近 7 天 +1381，比前 7 天快 7.6 倍，在加速）
  - [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) — Agent Skills that teach coding agents to write, review, and…（近 7 天 +1328，刚发布一周内）
  - [yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) — 麦麦碳账本 · 基于麦当劳 MCP 的个人餐饮碳足迹估算与减排模拟器 / Personal dining carbon…（近 7 天 +1264，比前 7 天快 2.7 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 24 个（star 合计 24841），代表：[nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：5 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Steal My Bitcoin](https://stealmybitcoin.com/) — 619 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) | 42236 | 3884 | +2544 | 10.9 | [6](https://news.ycombinator.com/item?id=50164485) | cleanyourtv · gathin23 cleanyourtv · gathin cleanyourtv | Debloat any Android or Google TV over Wi-Fi and get an Apple… |
| [deepseek-ai/DeepInfer](https://github.com/deepseek-ai/DeepInfer) | 23476 | 1974 | +359 | 11.9 | [2353](https://news.ycombinator.com/item?id=50163277) | deepinfer · deepseek-ai deepinfer · deepseek deepinfer | DeepInfer: High-performance, large-scale inference framework… |
| 🆕 [unclebob/ub-mode](https://github.com/unclebob/ub-mode) | 2641 | 1037 | +1938 | 2.5 | — | ub mode · unclebob ub mode · robert ub mode |  |
| 🆕 [DLSS-5-Swaper-New/.github](https://github.com/DLSS-5-Swaper-New/.github) | 1541 | 1541 | — | 1 | — | github · dlss-5-swaper-new github · dlss github | DLSS 5 Swapper is a specialized Windows utility for PC gamin… |
| [Zagitta/gpu-unlock](https://github.com/Zagitta/gpu-unlock) | 11577 | 1140 | +1528 | 10.2 | [349](https://news.ycombinator.com/item?id=50219700) | gpu unlock · zagitta gpu unlock · simon gpu unlock | Your GeForce runs AI at half speed. This fixes it for 20/30/… |
| [rddmwmddr/android-ad-cleaner](https://github.com/rddmwmddr/android-ad-cleaner) | 3658 | 918 | +1471 | 4 | — | android ad cleaner · rddmwmddr android ad cleaner | 关掉国产安卓手机系统里的广告、热搜、资讯推荐和营销推送。不 root，可还原，支持 AI 智能体一键执行。 |
| [JustAResearcher/gpu-unlock-ada](https://github.com/JustAResearcher/gpu-unlock-ada) | 4319 | 995 | +388 | 4.3 | [3](https://news.ycombinator.com/item?id=50223787) | gpu unlock ada · justaresearcher gpu unlock ada · tim gpu unlock ada | GPU tensor unlock source for RTX 4090 and experimental RTX 4… |
| [designfuchen/word-atlas](https://github.com/designfuchen/word-atlas) | 2722 | 950 | +853 | 2.9 | — | word atlas · designfuchen word atlas · boxin word atlas | 词光 · Word Atlas — Illustrated IELTS vocabulary with 7,298 wo… |
| [pengchujin/aerial-tv](https://github.com/pengchujin/aerial-tv) | 7011 | 895 | +750 | 7.8 | — | aerial tv · pengchujin aerial tv | 给国产电视的一块干净桌面：参照 tvOS 设计的开源 Android TV 桌面，没有广告，开机自动接管。A tvOS-… |
| [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | 1563 | 190 | +807 | 8.2 | — | blaze · indexable-inc blaze | Incremental rust builds up to 92x faster than cargo/rustc |
| 🆕 [anhao/ai-pose-gallery-zh](https://github.com/anhao/ai-pose-gallery-zh) | 803 | 803 | — | 1 | — | ai pose gallery zh · anhao ai pose gallery zh | 中文版 AI 姿势参考图库 · 1439 组 / 2878 张图片 / 完整汉化 · 零依赖静态画廊 |
| [amosblomqvist/learnharness](https://github.com/amosblomqvist/learnharness) | 3207 | 281 | +749 | 11.4 | [12](https://news.ycombinator.com/item?id=50243281) | learnharness · amosblomqvist learnharness · eero learnharness | Agent harness for learning difficult things. |
| [simbasjungles/free-my-tv](https://github.com/simbasjungles/free-my-tv) | 5083 | 605 | +195 | 8.4 | [1](https://news.ycombinator.com/item?id=50220596) | free my tv · simbasjungles free my tv · simba free my tv | A fast, ad-free home screen for Google TV, LG webOS and Sams… |
| [ly05010419/MacNativeGames](https://github.com/ly05010419/MacNativeGames) | 6088 | 586 | +258 | 10.4 | — | macnativegames · ly05010419 macnativegames · yong macnativegames | Play your own Tears of the Kingdom and Breath of the Wild na… |
| [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | 1149 | 567 | +328 | 2 | — | digital human koubo · andyhuo520 digital human koubo | AI digital-human talking-head videos from one photo: Renoise… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 86.8 | 🟢 窗口内 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | Rust | 1563 | +807 | +1381 | +182 | `····▁▃▁▁▁▂▃▆█·` | 8 | — | — |
| 2 | 86.3 | 🟢 窗口内 | [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) | Python | 1328 | +93 | +1328 | +0 | `·········▅█▅▂·` | 5 | — | — |
| 3 | 85.7 | 🟢 窗口内 | [yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) | Python | 1938 | +6 | +1264 | +467 | `▂▂▂▁▂▂▂▂▃█▆·▁·` | 15 | — | — |
| 4 | 81.7 | 🟢 窗口内 | [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) | Python | 1600 | -53 | +908 | +692 | `▁▂▃▅▃▄▃▃▇█▅▂▁·` | 12 | — | — |
| 5 | 74.8 | 🟢 窗口内 | [torrentplayer/torrentplayer](https://github.com/torrentplayer/torrentplayer) | Rust | 690 | +16 | +507 | +183 | `······██▄▄▄▃▂·` | 7 | — | — |
| 6 | 74.2 | 🟢 窗口内 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) | Go | 2094 | +93 | +484 | +421 | `▁▂▂▃▆███▆▄▄▅▆·` | 19 | — | — |
| 7 | 65.5 | 🟡 在降温 | [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) | Python | 1499 | +49 | +696 | +803 | `·▃▅█▆▅▃▂█▅▆▃▂·` | 11 | [1](https://news.ycombinator.com/item?id=50177079) | — |
| 8 | 62.1 | 🟡 在降温 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 1819 | +74 | +497 | +1322 | `···█▆▃▃▃▂▂▂▂▂·` | 9 | — | — |
| 9 | 58.1 | 🟡 在降温 | [reason-machines/reason-network](https://github.com/reason-machines/reason-network) | Rust | 1292 | +24 | +333 | +958 | `·▄▆▅▃█▆▅▃▂▂▂▂·` | 11 | — | — |
| 10 | 57.8 | 🟡 在降温 | [ELY-Open-Source/ElyOffice](https://github.com/ELY-Open-Source/ElyOffice) | Rust | 1070 | +25 | +324 | +746 | `····▇█▃▄▂▂▂▂▁·` | 8 | — | — |
| 11 | 56.2 | 🟡 在降温 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 2092 | +48 | +275 | +719 | `██▆▆▅▄▄▃▃▃▄▄▃·` | 17 | — | — |
| 12 | 55.5 | 🟡 在降温 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 1886 | +60 | +255 | +661 | `▂▂▁▁▁█▃▂▂▁▁▂▂·` | 15 | — | — |
| 13 | 54.2 | 🟡 在降温 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) | Python | 2613 | +30 | +224 | +420 | `▂█▆▄▅▅▃▃▃▅▄▃▃·` | 27 | — | — |
| 14 | 54 | 🟡 在降温 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx) | Python | 2226 | +68 | +221 | +752 | `█▆▄▄▃▃▂▂▂▂▂▂▃·` | 22 | [10](https://news.ycombinator.com/item?id=50037852) | — |
| 15 | 46.2 | 🔴 先核对 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2199 | +131 | +2198 | +1 | `······▁▁█▅▂▂▂·` | 6 | [3](https://news.ycombinator.com/item?id=50207695) | 一天进了一半以上的 star，但 HN 上没火过 |
| 16 | 45.8 | 🔴 先核对 | [t3dotgg/tstack](https://github.com/t3dotgg/tstack) | Python | 2048 | +401 | +2048 | +0 | `········▁▁▁█▃·` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 42.3 | 🔴 先核对 | [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | TypeScript | 1149 | +328 | +1149 | +0 | `··········▂█▄·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 41.9 | 🔴 先核对 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 1069 | +262 | +1069 | +0 | `··········█▄▄·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 39.7 | 🔴 先核对 | [mizorewww/gdirect](https://github.com/mizorewww/gdirect) | Rust | 752 | +37 | +752 | +0 | `·········▁█▂▁·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 39.4 | 🆕 💤 不活跃 | [Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill) | Python | 2039 | +161 | +711 | +621 | `▆▄▃▅▅▇▆▇▆▆▆▆█·` | 21 | — | — |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 549 | 30 | 44722 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[academa-labs/manimgx](https://github.com/academa-labs/manimgx) |
| `mcp` | 286 | 30 | 32119 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[yeqv111/mccarbon](https://github.com/yeqv111/mccarbon)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `rust` | 190 | 30 | 26799 | [oxc-project/tsrs](https://github.com/oxc-project/tsrs)、[academa-labs/manimgx](https://github.com/academa-labs/manimgx)、[xevrion/hatchzip](https://github.com/xevrion/hatchzip) |
| `local-first` | 61 | 30 | 9158 | [chenxiachan/textfold](https://github.com/chenxiachan/textfold)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch)、[aboard-io/tinylittleoffice](https://github.com/aboard-io/tinylittleoffice) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 24 | 24841 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill) |
| `ai-agents` | 21 | 15946 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering) |
| `llm` | 18 | 13680 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[Harvil1/codeAgent](https://github.com/Harvil1/codeAgent) |
| `agent-skills` | 17 | 20541 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `codex` | 16 | 16432 | [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu)、[oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) |
| `mcp-server` | 11 | 9436 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `ai-agent` | 11 | 8310 | [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `claude-skills` | 10 | 12380 | [oil-oil/oil-ui](https://github.com/oil-oil/oil-ui)、[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `developer-tools` | 9 | 6834 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai)、[hanzohanzhe/Grandet](https://github.com/hanzohanzhe/Grandet) |
| `macos` | 9 | 5989 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[kitlangton/scrawl](https://github.com/kitlangton/scrawl)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch) |
| `self-hosted` | 7 | 5640 | [marclou/mailcheap](https://github.com/marclou/mailcheap)、[rociiu/talorys](https://github.com/rociiu/talorys)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) |
| `typescript` | 7 | 5091 | [pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust)、[rociiu/talorys](https://github.com/rociiu/talorys)、[outcrawlai/scout](https://github.com/outcrawlai/scout) |

**语言分布**：Python 32 · Rust 30 · TypeScript 18 · JavaScript 12 · Go 3 · HTML 3 · Swift 2 · Astro 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [indexable-inc/blaze](https://github.com/indexable-inc/blaze) · 🟢 窗口内 · 86.8 分

> Incremental rust builds up to 92x faster than cargo/rustc

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1563 | +1381 | +182 | 50 | 96 | Rust | Apache-2.0 | 10-19（8 天前） | 今天 |

- **近 14 天每天新增**：`····▁▃▁▁▁▂▃▆█·` 0 0 0 0 17 151 14 5 4 104 157 456 655 0
- **势头**：比前 7 天快 7.6 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`cargo` `compiler` `cranelift` `developer-tools` `hot-reload` `incremental-compilation` `jit` `live-coding` `rust` `rust-analyzer`
- **主页**：<https://ix.dev/blaze>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) · 🟢 窗口内 · 86.3 分

> Agent Skills that teach coding agents to write, review, and port idiomatic Rust, plus a tested clippy config. Works with Claude Code, Codex, Copilot, Cursor, and Gemini CLI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1328 | +1328 | +0 | 59 | 3 | Python | MIT | 10-23（5 天前） | 今天 |

- **近 14 天每天新增**：`·········▅█▅▂·` 0 0 0 0 0 0 0 0 0 303 583 357 85 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `claude-code` `claude-plugin` `claude-skills` `clippy` `code-review` `coding-agent` `cursor` `rust` `style-guide`
- **主页**：<https://www.beautifulrust.dev>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) · 🟢 窗口内 · 85.7 分

> 麦麦碳账本 · 基于麦当劳 MCP 的个人餐饮碳足迹估算与减排模拟器 | Personal dining carbon footprint estimator powered by McDonald's MCP

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1938 | +1264 | +467 | 43 | 0 | Python | MIT | 10-12（15 天前） | 14 天前 |

- **近 14 天每天新增**：`▂▂▂▁▂▂▂▂▃█▆·▁·` 67 63 46 33 89 78 91 116 128 572 442 0 6 0
- **势头**：比前 7 天快 2.7 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) · 🟢 窗口内 · 81.7 分

> 麦当劳 MCP 聚会/团餐组织助手 — 基于 Model Context Protocol 的派对预订与团餐规划 CLI/Skill

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1600 | +908 | +692 | 58 | 2 | Python | MIT | 10-15（12 天前） | 今天 |

- **近 14 天每天新增**：`▁▂▃▅▃▄▃▃▇█▅▂▁·` 15 53 96 166 115 133 114 75 256 325 176 59 17 0
- **势头**：比前 7 天快 1.3 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [torrentplayer/torrentplayer](https://github.com/torrentplayer/torrentplayer) · 🟢 窗口内 · 74.8 分

> Stream any torrent, video or audio, and skip to any moment in about a second. Free, open-source desktop app for Windows, macOS and Linux. No servers, no accounts, no telemetry.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 690 | +507 | +183 | 18 | 5 | Rust | Apache-2.0 | 10-20（7 天前） | 今天 |

- **近 14 天每天新增**：`······██▄▄▄▃▂·` 0 0 0 0 0 0 183 189 78 91 69 66 14 0
- **势头**：比前 7 天快 2.8 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`audio-player` `bittorrent` `cross-platform` `desktop-app` `media-player` `p2p` `rust` `streaming` `svelte` `tauri` `torrent` `video-player`
- **主页**：<https://torrentplayer.io>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) · 🟢 窗口内 · 74.2 分

> ARTEX · AI autonomous penetration testing system (multi-agent LLM, Go + Next.js) · AI 自主渗透测试系统 · 百度 agent+ 攻防挑战赛冠军

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2094 | +484 | +421 | 997 | 3 | Go | AGPL-3.0 | 10-08（19 天前） | 8 天前 |

- **近 14 天每天新增**：`▁▂▂▃▆███▆▄▄▅▆·` 5 10 19 45 92 128 122 128 90 56 46 80 84 0
- **势头**：比前 7 天快 1.1 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `ai-security` `artex` `autonomous-agents` `cybersecurity` `go` `hacking` `llm` `llm-agent` `mcp` `nextjs` `offensive-security` `penetration-testing` `pentest` `red-team` `security` `security-tools` `vulnerability` `vulnerability-scanners` `web-security`
- **主页**：<https://artex-demo.vercel.app/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) · 🟡 在降温 · 65.5 分

> Co-op Anything: point your AI agent at any single-player game and play it with friends (online and/or splitscreen!). MCP server and playbook to let you reverse engineer, fix, test, ship and share what it learns.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1499 | +696 | +803 | 195 | 143 | Python | MIT | 10-16（11 天前） | 今天 |

- **近 14 天每天新增**：`·▃▅█▆▅▃▂█▅▆▃▂·` 0 81 131 234 156 124 77 47 227 149 161 67 45 0
- **势头**：只有前 7 天的 87%，在减速
- **HN**：发过 1 次，最高 1 分（[讨论](https://news.ycombinator.com/item?id=50177079)）
- **主页**：<https://coopanything.app>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) · 🟡 在降温 · 62.1 分

> 让你的agent一键直出商业级产品宣传片：会作曲，能指着画面改。Commercial-grade launch films by your coding agent — point at the frame to change it.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1819 | +497 | +1322 | 175 | 3 | JavaScript | MIT | 10-18（9 天前） | 5 天前 |

- **近 14 天每天新增**：`···█▆▃▃▃▂▂▂▂▂·` 0 0 0 580 437 170 135 157 78 50 83 68 61 0
- **势头**：只有前 7 天的 38%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `animation` `claude-code` `codex` `gsap` `launch-video` `motion-graphics` `skills`
- **主页**：<https://github.com/alchaincyf/huashu-motion>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [reason-machines/reason-network](https://github.com/reason-machines/reason-network) · 🟡 在降温 · 58.1 分

> Reason Network: your team's coding agents, talking to each other. The engine behind `reason network`.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1292 | +333 | +958 | 110 | 21 | Rust | Apache-2.0 | 10-16（11 天前） | 今天 |

- **近 14 天每天新增**：`·▄▆▅▃█▆▅▃▂▂▂▂·` 0 108 179 155 65 267 184 137 60 45 45 23 23 0
- **势头**：只有前 7 天的 35%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`coding-agents` `iroh` `mcp` `peer-to-peer` `reason`
- **主页**：<https://reasonmachines.com>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [ELY-Open-Source/ElyOffice](https://github.com/ELY-Open-Source/ElyOffice) · 🟡 在降温 · 57.8 分

> Ely Office: offline-first desktop apps in Rust and GPUI

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1070 | +324 | +746 | 69 | 10 | Rust | MIT | 10-19（8 天前） | 2 天前 |

- **近 14 天每天新增**：`····▇█▃▄▂▂▂▂▁·` 0 0 0 0 291 356 99 142 49 33 34 42 24 0
- **势头**：只有前 7 天的 43%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://office.elygpui.com>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [xevrion/hatchzip](https://github.com/xevrion/hatchzip) — 一天进了一半以上的 star，但 HN 上没火过
- [t3dotgg/tstack](https://github.com/t3dotgg/tstack) — 一天进了一半以上的 star，但 HN 上没火过
- [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) — 一天进了一半以上的 star，但 HN 上没火过
- [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) — 一天进了一半以上的 star，但 HN 上没火过
- [mizorewww/gdirect](https://github.com/mizorewww/gdirect) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 619 | 450 | [Show HN: Steal My Bitcoin](https://stealmybitcoin.com/) | [HN](https://news.ycombinator.com/item?id=50224916) |
| 400 | 82 | [Show HN: TitleArt – Make text like it's 1997](https://titleart.dvy.io/) | [HN](https://news.ycombinator.com/item?id=50238708) |
| 307 | 111 | [Show HN: A Truly Modular Keyboard](https://github.com/notaroomba/keybytes) | [HN](https://news.ycombinator.com/item?id=50228115) |
| 235 | 94 | [Show HN: OnKey – I'm a bad singer, so I built an app to show where I'm off-key](https://github.com/dsmurrell/onkey) | [HN](https://news.ycombinator.com/item?id=50195488) |
| 177 | 49 | [Show HN: I put employees inside S&P 500 market-cap bubbles](https://bigwhalehunting.com/workforce/) | [HN](https://news.ycombinator.com/item?id=50232312) |
| 167 | 42 | [Show HN: Hob - Open-source, on device alternative to Claude Cowork and ChatGPT](https://github.com/FrigadeHQ/hob) | [HN](https://news.ycombinator.com/item?id=50246238) |
| 140 | 47 | [Show HN: Corgi, a helpful {agent, terminal} multiplexer](https://corgi.computer/) | [HN](https://news.ycombinator.com/item?id=50214373) |
| 126 | 38 | [Show HN: Uberblok – an interactive museum of ZFS internals](https://uberblok.storagebits.workers.dev/) | [HN](https://news.ycombinator.com/item?id=50180257) |
| 118 | 59 | [Show HN: Encarta 95 Web](https://benwinding.github.io/encarta_95_web/#/article/Art) | [HN](https://news.ycombinator.com/item?id=50218975) |
| 114 | 34 | [Show HN: Omnara – Open-source alternative to Claude Managed Agents](https://github.com/omnara-ai/omnara) | [HN](https://news.ycombinator.com/item?id=50183892) |
| 110 | 81 | [Show HN: Making a smart TV dumb and then smart](https://github.com/anubhavmalhotra/r2d2-tv) | [HN](https://news.ycombinator.com/item?id=50202865) |
| 105 | 31 | [Show HN: Sumi.css – CSS Framework](https://github.com/vladocar/Sumi.css) | [HN](https://news.ycombinator.com/item?id=50180039) |
| 82 | 22 | [Show HN: Impossible Machines: declaratively program the physical world](https://www.impossiblemachines.xyz) | [HN](https://news.ycombinator.com/item?id=50202746) |
| 80 | 46 | [Show HN: UI micro interactions prompts for AI](https://www.typeui.sh/micro-interactions) | [HN](https://news.ycombinator.com/item?id=50199290) |
| 77 | 38 | [Show HN: Swurf – Swipe through the real web](https://swurf.org/) | [HN](https://news.ycombinator.com/item?id=50205320) |
| 70 | 57 | [Show HN: We had AI write a wiki from 45k Enron emails, every fact cited](https://www.thisandthat.chat/enron/) | [HN](https://news.ycombinator.com/item?id=50207620) |
| 67 | 25 | [Show HN: Hurston-1 open source TTS that speak Southern American and Afro-English](https://huggingface.co/destined/hurston-1) | [HN](https://news.ycombinator.com/item?id=50227330) |
| 66 | 56 | [Show HN: ADRs for AI – Deliberation records for human–AI work, versioned in Git](https://adrs.systems) | [HN](https://news.ycombinator.com/item?id=50227041) |
| 60 | 43 | [Show HN: Farol – A risk map of a pull request for the person who approves it](https://github.com/winnin/farol) | [HN](https://news.ycombinator.com/item?id=50231349) |
| 59 | 19 | [Show HN: Autonomous root for Tcl Android TV via CVE-2022-22706](https://gitlab.com/c4psu13/mali-pagecache-root) | [HN](https://news.ycombinator.com/item?id=50220042) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 155 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 117422★ |
| 124 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 20552★ |
| 102 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 29208★ |
| 31 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 7728★ |
| 62 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 43956★ |
| 48 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 34430★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 34435★ |
| 105 | [MOSS-Image Technical Report](https://huggingface.co/papers/2610.23374) | MOSS-Image is an open diffusion transformer that combines high-fidelity synthesis with intent-aware prompt enhancement to generate text-rich… | [OpenMOSS/MOSS-Image](https://github.com/OpenMOSS/MOSS-Image) 2107★ |
| 23 | [Prism: Dynamic Sparse Attention for Native 2K Joint Video-Audio Generation Model Training](https://huggingface.co/papers/2610.05416) | Prism accelerates native joint video-audio generation at 2K by using dynamic sparse attention guided by local visual variance and audio-visu… | [Tencent-Hunyuan/Prism](https://github.com/Tencent-Hunyuan/Prism) 1412★ |
| 193 | [DynaFlow: Learning Free-Form Multi-Agent Orchestration](https://huggingface.co/papers/2610.34467) | DynaFlow enables adaptive multi-agent collaboration by letting a main agent synthesize executable workflows that coordinate sub-agents throu… | 💡 [amiya-special/Dynaflow](https://github.com/amiya-special/Dynaflow) 107★ |
| 121 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 2723★ |
| 108 | [Work Agents: Systems, Capabilities, and Optimization](https://huggingface.co/papers/2610.35845) | The paper proposes a unified framework for work agents that integrates foundation models with runtime harnesses to execute complex digital t… | 💡 [EnjunDu/awesome-working-agent](https://github.com/EnjunDu/awesome-working-agent) 58★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 92010★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 17 | [Next-Concept Modeling: Fast, Parallel Coarse-to-Fine Text Generation](https://huggingface.co/papers/2610.14162) | Next-Concept Modeling uses hierarchical discrete codes and parallel level-wise generation to accelerate diffusion language models while impr… | [HazyResearch/ncm](https://github.com/HazyResearch/ncm) 1168★ |
| 15 | [Build, Don't Play: Self-Improving LLM Research Agents Develop a Hearthstone Battlegrounds AI That Ri…](https://huggingface.co/papers/2610.33845) | AutoTavern demonstrates that self-improving LLM research agents can autonomously build a faithful game simulator and train a reinforcement l… | 💡 [MCG-NJU/AutoTavern](https://github.com/MCG-NJU/AutoTavern) 68★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 82622★ |
| 31 | [Internal Safety Collapse in Frontier Large Language Models](https://huggingface.co/papers/2603.23509) | Frontier large language models exhibit Internal Safety Collapse, where they generate harmful content under specific task conditions, reveali… | [wuyoscar/ISC-Bench](https://github.com/wuyoscar/ISC-Bench) 2438★ |
| 13 | [Zero-Mem: Zero-Token Memory Operations for LLM Agents](https://huggingface.co/papers/2607.29377) | Zero-Mem enables structured agent memory without intermediate LLM generation by organizing interaction traces into complementary graph and t… | 💡 [Zero-Mem/Zero-mem](https://github.com/Zero-Mem/Zero-mem) 299★ |
| 256 | [WeVisOne-VL: Unified Visual Perception from Objects to Pixels](https://huggingface.co/papers/2610.31329) | WeVisOne-VL unifies object-level and pixel-level visual perception via structured token prediction, supporting detection, localization, coun… | 💡 [Tencent/WeVisOne-VL](https://github.com/Tencent/WeVisOne-VL) 310★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 14 | [unlimited ocr 2](https://huggingface.co/baidu/Unlimited-OCR-2) | image-text-to-text | 265 | 1 |
| 17 | [lfm3](https://huggingface.co/LiquidAI/LFM3-1.7B) | text-generation | 216 | 1 |
| 24 | [hy simulmt](https://huggingface.co/tencent/Hy-SimulMT-30B-A3B-FP8) | translation | 183 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 50 | 10 | [A fast and secure tar parser for the Rust ecosystem](https://astral.sh/blog/tar-codec) | `python` `rust` | [讨论](https://lobste.rs/s/q7arzy/fast_secure_tar_parser_for_rust_ecosystem) |
| 43 | 9 | [Four Months of Zig](https://gracefulliberty.com/articles/four-months-of-zig/) | `zig` | [讨论](https://lobste.rs/s/qr59sa/four_months_zig) |
| 87 | 19 | [Python's experimental JIT to be removed](https://lwn.net/SubscriberLink/1102102/0c00e4d550f25f8c/) | `python` | [讨论](https://lobste.rs/s/cajuq6/python_s_experimental_jit_be_removed) |
| 30 | 1 | [Ghostty 1.4.0](https://ghostty.org/docs/install/release-notes/1-4-0) | `release` | [讨论](https://lobste.rs/s/o6vpqb/ghostty_1_4_0) |
| 31 | 2 | [1,447 emoji? We'll do it live](https://planetpeanut.studio/post/2026/10/27/pidgin-emoji-twitch) | `design` | [讨论](https://lobste.rs/s/qd0hc9/1_447_emoji_we_ll_do_it_live) |
| 75 | 32 | [Shitty Screenshare](http://shittyscreenshare.com) | `browsers` `web` | [讨论](https://lobste.rs/s/cxxcik/shitty_screenshare) |
| 24 | 9 | [Compile-Time Dependent Types](https://thenumb.at/Syl-Intro/) | `ml` `plt` | [讨论](https://lobste.rs/s/d09iy3/compile_time_dependent_types) |
| 23 | 2 | [A stackless floodfill automation (2023)](https://t3x.org/files/floodfill.pdf) | `compsci` `pdf` | [讨论](https://lobste.rs/s/tp0zlk/stackless_floodfill_automation_2023) |
| 11 | 3 | [Fuzzers vs. AI: Comparing Fuzzilli and BigSleep on JavaScript Engines](https://projectzero.google/2026/10/fuzzing-v-AI.html) | `ai` `security` | [讨论](https://lobste.rs/s/rswyzt/fuzzers_vs_ai_comparing_fuzzilli) |
| 3 | 1 | [This is not sustainable](https://www.netmeister.org/blog/defense-ddos.html) | `security` | [讨论](https://lobste.rs/s/cpaibp/this_is_not_sustainable) |
| 18 | 1 | [Filian, Fil-C binaries on Debian](https://cr.yp.to/2025/fil-c.html) | `c` `linux` | [讨论](https://lobste.rs/s/rs6ce2/filian_fil_c_binaries_on_debian) |
| 50 | 28 | [The Exponential Time Hypothesis Is False [pdf]](https://files.mathhelm.org/files/733/The-Exponential-Time-Hypothesis-is-False-October-25-2026.pdf) | `math` `pdf` | [讨论](https://lobste.rs/s/pq6ju6/exponential_time_hypothesis_is_false_pdf) |
| 5 | 0 | [Reminder: Lobsters NYC Meetup Tomorrow 5:30 at Walker's](https://lobste.rs/s/87iesc) | `event` | [讨论](https://lobste.rs/s/87iesc/reminder_lobsters_nyc_meetup_tomorrow_5) |
| 13 | 0 | [Finding panics with Call Graph Analyzer](https://tweedegolf.nl/en/blog/242/finding-panics-with-call-graph-analyzer/) | `compilers` `rust` | [讨论](https://lobste.rs/s/opqtiv/finding_panics_with_call_graph_analyzer) |
| 111 | 2 | [CSS-Tricks has a new owner](https://css-tricks.com/css-tricks-has-a-new-owner/) | `web` | [讨论](https://lobste.rs/s/6ntoqr/css_tricks_has_new_owner) |
| 72 | 11 | [Oldest GUI application that still runs on Windows 11](https://blog.enlyth.com/posts/oldest-windows-gui-app-win-11/) | `historical` `windows` | [讨论](https://lobste.rs/s/rwubks/oldest_gui_application_still_runs_on) |
| 46 | 7 | [A faster way to compute signed 64-bit floor division by constants](https://www.benjoffe.com/fast-floordiv) | `c++` `performance` | [讨论](https://lobste.rs/s/o5to4p/faster_way_compute_signed_64_bit_floor) |
| 12 | 1 | [Full Haskell-like Type Class resolution in Java](https://garciat.com/posts/java-type-classes/) | `haskell` `java` `plt` | [讨论](https://lobste.rs/s/beiiil/full_haskell_like_type_class_resolution) |
| 6 | 0 | [An Evening with Berferd: In Which a Cracker is Lured, Endured, and Studied (1992)](https://www.cheswick.com/ches/papers/berferd.pdf) | `pdf` `security` `unix` | [讨论](https://lobste.rs/s/7bbzjf/evening_with_berferd_which_cracker_is) |
| 85 | 23 | [Websites Should Be Printable](https://brennenputh.me/blog/printable-websites/) | `css` `web` | [讨论](https://lobste.rs/s/olnqh2/websites_should_be_printable) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 78 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 5 | 3 | 60% | — |
| 🔴 先核对 | 6 | 5 | 83% | — |
| 🟡 在降温 | 5 | 0 | 0% | — |
| 🔵 已被发现 | 2 | 0 | 0% | — |
| 🟢 窗口内 | 6 | 4 | 66% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [tobi/disktree](https://github.com/tobi/disktree) | 2026-10-13 | 🟡 在降温 | 2876 | 3728 | 3 | 没起来 |
| [trhhubsd/ARTEXX](https://github.com/trhhubsd/ARTEXX) | 2026-10-13 | 🔴 先核对 | 845 | 2094 | 0 | ✅ 起来了 |
| [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) | 2026-10-13 | 🚀 爆发 | 7146 | 21545 | 1 | ✅ 起来了 |
| [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | 2026-10-13 | 🔴 先核对 | 758 | 1886 | 0 | ✅ 起来了 |
| [Arekejoker/qwen21-nsfw-pose-skill](https://github.com/Arekejoker/qwen21-nsfw-pose-skill) | 2026-10-14 | 🚀 爆发 | 950 | 3773 | 0 | ✅ 起来了 |

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
