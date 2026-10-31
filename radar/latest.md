# early-radar 选题雷达 · 2026-10-31

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 107 个，细查前 20 个 · 比上次 = 和 2026-10-30 那次比 · 生成于 2026-10-31 05:07 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 2 个 · Show HN ✅ 18 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 4 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 8 个 · 🟡 在降温 7 个 · 🔵 已被发现 0 个 · 💤 不活跃 0 个 · 🔴 先核对 5 个
- **今天新出现 2 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) 平均每天 +3385，见 [爆发](#爆发)
- **复盘**：🚀 爆发 6/11 · 🔴 先核对 6/13 · 🟡 在降温 0/5 · 🔵 已被发现 0/2 · 🟢 窗口内 4/7（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [SoMarkAI/OXR](https://github.com/SoMarkAI/OXR) — An open-source document parsing model with SOTA accuracy and…（近 7 天 +2088，比前 7 天快 3.5 倍，在加速）
  - [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) — An Open Source template for a proactive AI agent that gets y…（近 7 天 +1665，比前 7 天快 1665.0 倍，在加速）
  - [l0ng-ai/openidea](https://github.com/l0ng-ai/openidea) — The IDE you know, rebuilt in Rust. IntelliJ IDEA–style keyma…（近 7 天 +1597，比前 7 天快 15.4 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 21 个（star 合计 23737），代表：[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：3 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: Steal My Bitcoin](https://stealmybitcoin.com/) — 625 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) | 46949 | 3385 | +1256 | 13.9 | [6](https://news.ycombinator.com/item?id=50164485) | cleanyourtv · gathin23 cleanyourtv · gathin cleanyourtv | Debloat any Android or Google TV over Wi-Fi and get an Apple… |
| [anhao/ai-pose-gallery-zh](https://github.com/anhao/ai-pose-gallery-zh) | 4106 | 1111 | +731 | 3.7 | — | ai pose gallery zh · anhao ai pose gallery zh | 中文版 AI 姿势参考图库 · 1439 组 / 2878 张图片 / 完整汉化 · 零依赖静态画廊 |
| [valentderah/totk-pc-recomp](https://github.com/valentderah/totk-pc-recomp) | 1781 | 1053 | +1085 | 1.7 | — | totk pc recomp · valentderah totk pc recomp · valiantsin totk pc recomp | Static recompilation of The Legend of Zelda: Tears of the Ki… |
| 🆕 [wangzan101/Mika](https://github.com/wangzan101/Mika) | 1688 | 1051 | — | 1.6 | — | mika · wangzan101 mika · wangzan mika | Mika — 你手机上的私人 AI 助理，替你操作 App、上网、把事办成。An on-device AI agent… |
| [Zagitta/gpu-unlock](https://github.com/Zagitta/gpu-unlock) | 13532 | 1029 | +351 | 13.2 | [351](https://news.ycombinator.com/item?id=50219700) | gpu unlock · zagitta gpu unlock · simon gpu unlock | Your GeForce runs AI at half speed. This fixes it for 20/30/… |
| [unclebob/ub-mode](https://github.com/unclebob/ub-mode) | 5447 | 983 | +578 | 5.5 | — | ub mode · unclebob ub mode · robert ub mode |  |
| 🆕 [heydamir/unslop](https://github.com/heydamir/unslop) | 1508 | 967 | — | 1.6 | — | unslop · heydamir unslop · damir unslop | A Claude skill that turns vibecoded, AI-looking UI into a de… |
| 🆕 [paipiange/nvzhuang](https://github.com/paipiange/nvzhuang) | 1337 | 683 | +936 | 2 | — | nvzhuang · paipiange nvzhuang | 1407 张 AI 女装参考图集与虚拟试穿网站，支持中英检索、OpenAI Images / Gemini / 豆包及自… |
| [pengchujin/aerial-tv](https://github.com/pengchujin/aerial-tv) | 8117 | 750 | +288 | 10.8 | — | aerial tv · pengchujin aerial tv | 给国产电视的一块干净桌面：参照 tvOS 设计的开源 Android TV 桌面，没有广告，开机自动接管。A tvOS-… |
| [rddmwmddr/android-ad-cleaner](https://github.com/rddmwmddr/android-ad-cleaner) | 5143 | 737 | +333 | 7 | — | android ad cleaner · rddmwmddr android ad cleaner | 关掉国产安卓手机系统里的广告、热搜、资讯推荐和营销推送。不 root，可还原，支持 AI 智能体一键执行。 |
| 🆕 [kevinraymond/florilegium](https://github.com/kevinraymond/florilegium) | 723 | 723 | — | 1 | [235](https://news.ycombinator.com/item?id=50305637) | florilegium · kevinraymond florilegium · kevin florilegium | Procedurally generated Delft-blue floral page margins for Lu… |
| [interplains/Zero-Breach-Toolkit](https://github.com/interplains/Zero-Breach-Toolkit) | 3895 | 695 | +232 | 5.6 | — | zero breach toolkit · interplains zero breach toolkit · archivegenocide zero breach toolkit | Free, open-source, offline checks for traces of known mercen… |
| [JustAResearcher/gpu-unlock-ada](https://github.com/JustAResearcher/gpu-unlock-ada) | 4592 | 626 | +57 | 7.3 | [3](https://news.ycombinator.com/item?id=50223787) | gpu unlock ada · justaresearcher gpu unlock ada · tim gpu unlock ada | GPU tensor unlock source for RTX 4090 and experimental RTX 4… |
| [designfuchen/word-atlas](https://github.com/designfuchen/word-atlas) | 3407 | 581 | +138 | 5.9 | — | word atlas · designfuchen word atlas · boxin word atlas | 词光 · Word Atlas — Illustrated IELTS vocabulary with 7,298 wo… |
| [qybaihe/bla](https://github.com/qybaihe/bla) | 1483 | 248 | +530 | 6 | — | bla · qybaihe bla · timo bla | 🛡️ BLA (Blind LLM Agents) — Adversarial defense shield that… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 91.7 | 🟢 窗口内 | [SoMarkAI/OXR](https://github.com/SoMarkAI/OXR) | Python | 2691 | +143 | +2088 | +603 | `··▁▂▂▂▃▃▅█▄▄▂·` | 26 | [3](https://news.ycombinator.com/item?id=50183506) | — |
| 2 | 89 | 🟢 窗口内 | [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) | TypeScript | 1666 | +100 | +1665 | +1 | `···▁·····██▃▂·` | 9 | — | — |
| 3 | 88.5 | 🟢 窗口内 | [l0ng-ai/openidea](https://github.com/l0ng-ai/openidea) | TypeScript | 1701 | +443 | +1597 | +104 | `····▁▁▂▁▁▄██▆·` | 9 | — | — |
| 4 | 88.2 | 🟢 窗口内 | [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | TypeScript | 1560 | +59 | +1560 | +0 | `·······▂█▄▃▂▁·` | 5 | — | — |
| 5 | 87.8 | 🟢 窗口内 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | Rust | 1793 | +50 | +1498 | +295 | `·▁▃▁▁▁▂▃▆█▂▁▂·` | 11 | — | — |
| 6 | 86.5 | 🟢 窗口内 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 1349 | +72 | +1349 | +0 | `·······█▄▄▂▂▂·` | 5 | — | — |
| 7 | 85.5 | 🟢 窗口内 | [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) | Python | 1540 | +113 | +1238 | +302 | `······▅█▅▂▁▂▂·` | 8 | — | — |
| 8 | 80.2 | 🟢 窗口内 | [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) | Kotlin | 1193 | +75 | +801 | +392 | `····▁▄█▇▄▅▄▃▃·` | 9 | — | — |
| 9 | 63.9 | 🟡 在降温 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2356 | +31 | +592 | +1764 | `···▁▁█▅▂▂▂▁▁▁·` | 9 | [3](https://news.ycombinator.com/item?id=50207695) | — |
| 10 | 60.7 | 🟡 在降温 | [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) | Python | 1659 | +63 | +432 | +1015 | `█▆▅▃▂█▅▆▃▃▂▂▃·` | 14 | [1](https://news.ycombinator.com/item?id=50177079) | — |
| 11 | 57.7 | 🟡 在降温 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 1925 | +30 | +320 | +1605 | `█▆▃▃▃▂▂▂▂▂▁▁▁·` | 12 | — | — |
| 12 | 56 | 🟡 在降温 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 2193 | +26 | +270 | +419 | `█▆▆▅▄▃▃▆▅▄▄▃▃·` | 20 | — | — |
| 13 | 55.3 | 🟡 在降温 | [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) | Python | 1598 | -3 | +252 | +1182 | `▅▃▄▃▃▆█▅▂▁·▁··` | 15 | — | — |
| 14 | 53.6 | 🟡 在降温 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 1983 | +12 | +212 | +694 | `▁▁█▃▂▂▁▁▂▂▂▂▁·` | 18 | — | — |
| 15 | 50.8 | 🟡 在降温 | [ELY-Open-Source/ElyOffice](https://github.com/ELY-Open-Source/ElyOffice) | Rust | 1127 | +20 | +159 | +968 | `·▇█▃▄▂▂▂▂▂▁▁▁·` | 11 | — | — |
| 16 | 46.8 | 🔴 先核对 | [t3dotgg/tstack](https://github.com/t3dotgg/tstack) | Python | 2479 | +65 | +2444 | +35 | `·····▁▁▁█▃▂▂▁·` | 7 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 45.7 | 🆕 🔴 先核对 | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) | Python | 2268 | — | +2046 | +224 | `▁▁▁▂▁▁▁▁▁▁▂▃█·` | 18 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 44.6 | 🆕 🔴 先核对 | [wangzan101/Mika](https://github.com/wangzan101/Mika) | Kotlin | 1688 | — | +1688 | +0 | `···········▂█·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 43.8 | 🔴 先核对 | [qybaihe/bla](https://github.com/qybaihe/bla) | TypeScript | 1483 | +530 | +1483 | +0 | `·······▁▁▂▁█▅·` | 5 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 39.8 | 🔴 先核对 | [mizorewww/gdirect](https://github.com/mizorewww/gdirect) | Rust | 774 | +9 | +755 | +19 | `······▁█▂▁▁▁▁·` | 5 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 574 | 30 | 49952 | [SoMarkAI/OXR](https://github.com/SoMarkAI/OXR)、[t3dotgg/tstack](https://github.com/t3dotgg/tstack)、[jiwoochris/artex-global](https://github.com/jiwoochris/artex-global) |
| `mcp` | 298 | 30 | 32927 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[yeqv111/mccarbon](https://github.com/yeqv111/mccarbon)、[cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) |
| `rust` | 197 | 30 | 31564 | [oxc-project/tsrs](https://github.com/oxc-project/tsrs)、[academa-labs/manimgx](https://github.com/academa-labs/manimgx)、[xevrion/hatchzip](https://github.com/xevrion/hatchzip) |
| `local-first` | 68 | 30 | 10090 | [chenxiachan/textfold](https://github.com/chenxiachan/textfold)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch)、[aboard-io/tinylittleoffice](https://github.com/aboard-io/tinylittleoffice) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 21 | 23737 | [Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) |
| `ai-agents` | 20 | 16673 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering) |
| `llm` | 16 | 12892 | [jiwoochris/artex-global](https://github.com/jiwoochris/artex-global)、[wangzan101/Mika](https://github.com/wangzan101/Mika)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) |
| `codex` | 14 | 13642 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[shinshin86/mesh-avatar-studio](https://github.com/shinshin86/mesh-avatar-studio)、[UnderleveledBuilder/awesome-short-drama-skills](https://github.com/UnderleveledBuilder/awesome-short-drama-skills) |
| `agent-skills` | 13 | 16255 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) |
| `mcp-server` | 13 | 12797 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist) |
| `ai-agent` | 11 | 10569 | [jiwoochris/artex-global](https://github.com/jiwoochris/artex-global)、[wangzan101/Mika](https://github.com/wangzan101/Mika)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist) |
| `developer-tools` | 8 | 7918 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze)、[l0ng-ai/openidea](https://github.com/l0ng-ai/openidea)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) |
| `macos` | 8 | 5882 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[kitlangton/scrawl](https://github.com/kitlangton/scrawl)、[aixisstudio/Snitch](https://github.com/aixisstudio/Snitch) |
| `claude-skills` | 7 | 9979 | [Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) |
| `self-hosted` | 7 | 5974 | [marclou/mailcheap](https://github.com/marclou/mailcheap)、[rociiu/talorys](https://github.com/rociiu/talorys)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) |
| `open-source` | 7 | 4147 | [alexgaoth/awesome-reverse-engineered](https://github.com/alexgaoth/awesome-reverse-engineered)、[chenxiachan/textfold](https://github.com/chenxiachan/textfold)、[FortoGraphy/prism-download-manager](https://github.com/FortoGraphy/prism-download-manager) |

**语言分布**：Rust 30 · Python 28 · TypeScript 18 · JavaScript 12 · Go 4 · HTML 3 · C 2 · Kotlin 2

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [SoMarkAI/OXR](https://github.com/SoMarkAI/OXR) · 🟢 窗口内 · 91.7 分

> An open-source document parsing model with SOTA accuracy and speed, using an RSI loop during post-training.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2691 | +2088 | +603 | 190 | 21 | Python | — | 10-05（26 天前） | 6 天前 |

- **近 14 天每天新增**：`··▁▂▂▂▃▃▅█▄▄▂·` 0 0 24 101 129 131 218 181 452 732 308 290 125 0
- **势头**：比前 7 天快 3.5 倍，在加速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=50183506)）
- **topics**：`agent` `llm-tools` `ocr` `oxr` `rsi` `vlm` `vlm-ocr`
- **主页**：<https://somark.ai/oxr>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) · 🟢 窗口内 · 89 分

> An Open Source template for a proactive AI agent that gets your work done and keeps you in the loop.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1666 | +1665 | +1 | 210 | 11 | TypeScript | MIT | 10-21（9 天前） | 2 天前 |

- **近 14 天每天新增**：`···▁·····██▃▂·` 0 0 0 1 0 0 0 0 0 704 691 172 98 0
- **势头**：比前 7 天快 1665.0 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<copilotkit.ai/openduet>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [l0ng-ai/openidea](https://github.com/l0ng-ai/openidea) · 🟢 窗口内 · 88.5 分

> The IDE you know, rebuilt in Rust. IntelliJ IDEA–style keymap, tool windows and search-everywhere in a fast native app: editor, code insight, debugger, Git, terminal, database and HTTP clients for 60+ languages.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1701 | +1597 | +104 | 157 | 89 | TypeScript | Apache-2.0 | 10-21（9 天前） | 今天 |

- **近 14 天每天新增**：`····▁▁▂▁▁▄██▆·` 0 0 0 0 35 23 46 35 21 191 488 504 358 0
- **势头**：比前 7 天快 15.4 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`code-editor` `cross-platform` `dap` `database-client` `debugger` `desktop-app` `developer-tools` `git` `http-client` `ide` `intellij` `lsp` `rust` `tauri` `terminal`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) · 🟢 窗口内 · 88.2 分

> AI digital-human talking-head videos from one photo: Renoise MCP generation + 5 editing styles + 48 creator-grade packaging components. Agent skill for Claude Code / Codex / OpenClaw / WorkBuddy …

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1560 | +1560 | +0 | 354 | 4 | TypeScript | MIT | 10-26（5 天前） | 今天 |

- **近 14 天每天新增**：`·······▂█▄▃▂▁·` 0 0 0 0 0 0 0 88 778 301 190 154 49 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [indexable-inc/blaze](https://github.com/indexable-inc/blaze) · 🟢 窗口内 · 87.8 分

> Incremental rust builds up to 92x faster than cargo/rustc

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1793 | +1498 | +295 | 64 | 452 | Rust | Apache-2.0 | 10-19（11 天前） | 今天 |

- **近 14 天每天新增**：`·▁▃▁▁▁▂▃▆█▂▁▂·` 0 17 151 14 5 4 104 156 455 674 126 37 50 0
- **势头**：比前 7 天快 5.1 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`cargo` `compiler` `cranelift` `developer-tools` `hot-reload` `incremental-compilation` `jit` `live-coding` `rust` `rust-analyzer`
- **主页**：<https://ix.dev/blaze>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) · 🟢 窗口内 · 86.5 分

> Evidence-first genealogy skill for AI agents (Codex, Claude Code): church books, civil, military, deportation and repression records across the former USSR. Replies in your language.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1349 | +1349 | +0 | 139 | 2 | Python | MIT | 10-25（5 天前） | 今天 |

- **近 14 天每天新增**：`·······█▄▄▂▂▂·` 0 0 0 0 0 0 0 593 229 255 113 88 71 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `archives` `claude-code` `codex` `family-history` `familysearch` `genealogy` `ussr`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) · 🟢 窗口内 · 85.5 分

> Agent Skills that teach coding agents to write, review, and port idiomatic Rust, plus a tested clippy config. Works with Claude Code, Codex, Copilot, Cursor, and Gemini CLI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1540 | +1238 | +302 | 79 | 3 | Python | MIT | 10-23（8 天前） | 今天 |

- **近 14 天每天新增**：`······▅█▅▂▁▂▂·` 0 0 0 0 0 0 302 583 357 89 41 60 108 0
- **势头**：比前 7 天快 4.1 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `claude-code` `claude-plugin` `claude-skills` `clippy` `code-review` `coding-agent` `cursor` `rust` `style-guide`
- **主页**：<https://www.beautifulrust.dev>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) · 🟢 窗口内 · 80.2 分

> A community-built phone app for Clean Your TV: clean up an Android TV from your phone. No laptop, no coding agent, nothing uninstalled.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1193 | +801 | +392 | 108 | 2746 | Kotlin | MIT | 10-21（9 天前） | 今天 |

- **近 14 天每天新增**：`····▁▄█▇▄▅▄▃▃·` 0 0 0 0 1 103 288 244 133 151 114 89 70 0
- **势头**：比前 7 天快 2.0 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adb` `android-tv` `debloat` `fire-tv` `google-tv` `launcher`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 9. [xevrion/hatchzip](https://github.com/xevrion/hatchzip) · 🟡 在降温 · 63.9 分

> HatchZip is a free, open-source archive extractor for Windows, macOS and Linux that extracts ZIP, 7z, RAR, tar and split archives in place, so it needs free space for the extracted files only. Desktop app and CLI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2356 | +592 | +1764 | 77 | 15 | Rust | Apache-2.0 | 10-21（9 天前） | 今天 |

- **近 14 天每天新增**：`···▁▁█▅▂▂▂▁▁▁·` 0 0 0 1 23 1138 602 198 101 144 71 49 29 0
- **势头**：只有前 7 天的 34%，在减速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=50207695)）
- **topics**：`7z` `7zip` `archive` `archive-extractor` `cli` `crash-safe` `disk-space` `extract` `extractor` `gui` `in-place` `linux` `macos` `rar` `rust` `tar` `unrar` `unzip` `windows` `zip`
- **主页**：<https://hatchzip.dev>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) · 🟡 在降温 · 60.7 分

> Co-op Anything: point your AI agent at any single-player game and play it with friends (online and/or splitscreen!). MCP server and playbook to let you reverse engineer, fix, test, ship and share what it learns.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1659 | +432 | +1015 | 231 | 154 | Python | MIT | 10-16（14 天前） | 今天 |

- **近 14 天每天新增**：`█▆▅▃▂█▅▆▃▃▂▂▃·` 234 156 125 77 47 227 149 161 67 56 45 44 59 0
- **势头**：只有前 7 天的 43%，在减速
- **HN**：发过 1 次，最高 1 分（[讨论](https://news.ycombinator.com/item?id=50177079)）
- **主页**：<https://coopanything.app>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [t3dotgg/tstack](https://github.com/t3dotgg/tstack) — 一天进了一半以上的 star，但 HN 上没火过
- [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) — 一天进了一半以上的 star，但 HN 上没火过
- [wangzan101/Mika](https://github.com/wangzan101/Mika) — 一天进了一半以上的 star，但 HN 上没火过
- [qybaihe/bla](https://github.com/qybaihe/bla) — 一天进了一半以上的 star，但 HN 上没火过
- [mizorewww/gdirect](https://github.com/mizorewww/gdirect) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 625 | 450 | [Show HN: Steal My Bitcoin](https://stealmybitcoin.com/) | [HN](https://news.ycombinator.com/item?id=50224916) |
| 408 | 82 | [Show HN: TitleArt – Make text like it's 1997](https://titleart.dvy.io/) | [HN](https://news.ycombinator.com/item?id=50238708) |
| 320 | 116 | [Show HN: A Truly Modular Keyboard](https://github.com/notaroomba/keybytes) | [HN](https://news.ycombinator.com/item?id=50228115) |
| 220 | 118 | [Show HN: A working Nintendo in ~1GB of Qwen weights](https://github.com/dbreunig/nesformer) | [HN](https://news.ycombinator.com/item?id=50306442) |
| 178 | 49 | [Show HN: I put employees inside S&P 500 market-cap bubbles](https://bigwhalehunting.com/workforce/) | [HN](https://news.ycombinator.com/item?id=50232312) |
| 175 | 43 | [Show HN: Hob - Open-source, on device alternative to Claude Cowork and ChatGPT](https://github.com/FrigadeHQ/hob) | [HN](https://news.ycombinator.com/item?id=50246238) |
| 151 | 65 | [Show HN: Encarta 95 Web](https://benwinding.github.io/encarta_95_web/#/article/Art) | [HN](https://news.ycombinator.com/item?id=50218975) |
| 149 | 126 | [Show HN: Auto Dismiss Mac OS "Allow <app> to find devices on local networks?"](https://github.com/johncassil/dontallow) | [HN](https://news.ycombinator.com/item?id=50294506) |
| 133 | 41 | [Show HN: To Honor Sir Patrick Stewart, Enjoy the TNG Episode Guessing Game](https://tng.episodle.com/) | [HN](https://news.ycombinator.com/item?id=50311686) |
| 125 | 36 | [Show HN: I Turned DOOM into a Transformer](https://github.com/mottopanikeiku/doomformer) | [HN](https://news.ycombinator.com/item?id=50297697) |
| 81 | 35 | [Show HN: SlideBySide – Present slides without sharing your screen](https://slidebyside.com/) | [HN](https://news.ycombinator.com/item?id=50276883) |
| 80 | 40 | [Show HN: I built a multiplayer game where you're an aerial fighter cat](https://catcopter.com) | [HN](https://news.ycombinator.com/item?id=50305320) |
| 80 | 12 | [Show HN: A proof-of-concept formalization of the IRS federal tax forms](https://github.com/emmilco/us-tax-model) | [HN](https://news.ycombinator.com/item?id=50278678) |
| 68 | 28 | [Show HN: Hurston-1 open source TTS that speak Southern American and Afro-English](https://huggingface.co/destined/hurston-1) | [HN](https://news.ycombinator.com/item?id=50227330) |
| 66 | 59 | [Show HN: ADRs for AI – Deliberation records for human–AI work, versioned in Git](https://adrs.systems) | [HN](https://news.ycombinator.com/item?id=50227041) |
| 60 | 43 | [Show HN: Farol – A risk map of a pull request for the person who approves it](https://github.com/winnin/farol) | [HN](https://news.ycombinator.com/item?id=50231349) |
| 60 | 0 | [Show HN: Arsaze – Cursor for video editing (Tab-complete and agent edits)](https://www.arsaze.com) | [HN](https://news.ycombinator.com/item?id=50300618) |
| 59 | 19 | [Show HN: Autonomous root for Tcl Android TV via CVE-2022-22706](https://gitlab.com/c4psu13/mali-pagecache-root) | [HN](https://news.ycombinator.com/item?id=50220042) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 159 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 118757★ |
| 126 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 21511★ |
| 6 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 2019★ |
| 31 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 8851★ |
| 105 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 29989★ |
| 48 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 34953★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 34955★ |
| 10 | [Investor's Last Exam: Can AI Agents Do Equity Investment Without Seeing the Future?](https://huggingface.co/papers/2610.38342) | Investor's Last Exam evaluates financial agents on end-to-end equity research using frozen evidence, expert criteria, and dependency graphs,… | 💡 [Prophetlab/Investor-Last-Exam](https://github.com/Prophetlab/Investor-Last-Exam) 86★ |
| 62 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 44161★ |
| 239 | [Intrinsic Distribution Matching](https://huggingface.co/papers/2610.39633) | Intrinsic Distribution Matching improves few-step text-to-image generation by adding explicit moment constraints to distribution matching di… | 💡 [inclusionAI/IDM](https://github.com/inclusionAI/IDM) 49★ |
| 107 | [MOSS-Image Technical Report](https://huggingface.co/papers/2610.23374) | MOSS-Image is an open diffusion transformer that combines high-fidelity synthesis with intent-aware prompt enhancement to generate text-rich… | [OpenMOSS/MOSS-Image](https://github.com/OpenMOSS/MOSS-Image) 2312★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 92273★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 126 | [Hy-Nomas: Towards Free-form Interactive World Generation](https://huggingface.co/papers/2610.36729) | Hy-Nomas is a video world model that uses causal attention and structured conditioning to generate interactive, multi-turn video segments wi… | 💡 [Tencent-Hunyuan/Hy-Nomas](https://github.com/Tencent-Hunyuan/Hy-Nomas) 412★ |
| 118 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 2899★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 82816★ |
| 180 | [SmolDocling: An ultra-compact vision-language model for end-to-end multi-modal document conversion](https://huggingface.co/papers/2503.11576) | SmolDocling is a compact vision-language model that performs end-to-end document conversion with robust performance across various document… | [docling-project/docling](https://github.com/docling-project/docling) 69878★ |
| 26 | [PaddleOCR-VL-1.6: Expanding the Frontier of Document Parsing with Under-Optimized Region Refinement…](https://huggingface.co/papers/2606.03264) | PaddleOCR-VL-1.6 enhances document parsing performance through targeted data optimization and progressive post-training techniques, achievin… | [PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) 91997★ |
| 23 | [Prism: Dynamic Sparse Attention for Native 2K Joint Video-Audio Generation Model Training](https://huggingface.co/papers/2610.05416) | Prism accelerates native joint video-audio generation at 2K by using dynamic sparse attention guided by local visual variance and audio-visu… | [Tencent-Hunyuan/Prism](https://github.com/Tencent-Hunyuan/Prism) 1518★ |
| 19 | [Next-Concept Modeling: Fast, Parallel Coarse-to-Fine Text Generation](https://huggingface.co/papers/2610.14162) | Next-Concept Modeling uses hierarchical discrete codes and parallel level-wise generation to accelerate diffusion language models while impr… | [HazyResearch/ncm](https://github.com/HazyResearch/ncm) 1326★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 25 | [idol](https://huggingface.co/speridlabs/idol) | image-to-3d | 162 | 1 |
| 38 | [audio8 tts realistic](https://huggingface.co/Edge0/Audio8-TTS-Realistic-0.6b) | text-to-speech | 125 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 148 | 38 | [Backdoors in Claude Code for VS, Cursor official extensions](https://cyberplace.social/@GossiTheDog/117528831681803563) | `security` | [讨论](https://lobste.rs/s/ttp7aq/backdoors_claude_code_for_vs_cursor) |
| 82 | 26 | [Do At-Proto Users Know This Is Public?](https://melaniekat.com/blog/public-on-pds/) | `privacy` | [讨论](https://lobste.rs/s/htgcuc/do_at_proto_users_know_this_is_public) |
| 29 | 19 | [No, npm, “estee” is not a typo of “testem”](https://smoores.dev/post/no_npm_estee_is_not_a_typo/) | `javascript` | [讨论](https://lobste.rs/s/xudbqx/no_npm_estee_is_not_typo_testem) |
| 25 | 14 | [The federated code forge](https://tangled.org/blog/forge/) | `distributed` `vcs` | [讨论](https://lobste.rs/s/ukj8mm/federated_code_forge) |
| 13 | 2 | [How hard is it to check for whitespace?](https://serce.me/posts/2026-10-30-how-hard-is-it-to-check-for-whitespace) | `java` `performance` | [讨论](https://lobste.rs/s/1pmuy7/how_hard_is_it_check_for_whitespace) |
| 31 | 5 | [Infinite Mac: BeOS](https://blog.persistent.info/2026/10/infinite-mac-beos.html) | `retrocomputing` | [讨论](https://lobste.rs/s/fskctn/infinite_mac_beos) |
| 72 | 7 | [How curl was accidentally Turing-complete for nine months](https://seriot.ch/computation/curl.html) | `compsci` | [讨论](https://lobste.rs/s/f4aqog/how_curl_was_accidentally_turing) |
| 13 | 1 | [The support case of a customer who said that all they could see was a black screen](https://devblogs.microsoft.com/oldnewthing/20261029-00/?p=112808/) | `historical` `windows` | [讨论](https://lobste.rs/s/soosuu/support_case_customer_who_said_all_they) |
| 77 | 21 | [If you love a website, back it up](http://blog.mistys-internet.website/post/2026/10/29/if-you-love-a-website-back-it-up/) | `web` | [讨论](https://lobste.rs/s/6ole9g/if_you_love_website_back_it_up) |
| 15 | 6 | [Shrinking NixOS Ram footprint and resource requirements to the bare minimum](https://lowendspirit.com/discussion/11543/shrinking-nixos-ram-footprint-and-resource-requirements-to-the-bare-minimum) | `nix` | [讨论](https://lobste.rs/s/o1z9mm/shrinking_nixos_ram_footprint_resource) |
| 20 | 36 | [What are you doing this weekend?](https://lobste.rs/s/u7dsbx) | `ask` `programming` | [讨论](https://lobste.rs/s/u7dsbx/what_are_you_doing_this_weekend) |
| 11 | 0 | [Switch lowering in GCC](https://xoranth.net/gcc-switch/) | `compilers` `performance` | [讨论](https://lobste.rs/s/ncclwy/switch_lowering_gcc) |
| 7 | 0 | [Protecting against CVE-2026-98432](https://groups.google.com/g/golang-announce/c/PCoQcdxoScw) | `go` `security` | [讨论](https://lobste.rs/s/mp8yqt/protecting_against_cve_2026_98432) |
| 61 | 46 | [London meetup](https://lobste.rs/s/dsrruj) | `event` | [讨论](https://lobste.rs/s/dsrruj/london_meetup) |
| 4 | 0 | [Tactical-Retreat: a freely available, multi-platform QuakeC-based Counter-Strike v1.5 port](https://www.frag-net.com/project_tacticalretreat.html) | `games` | [讨论](https://lobste.rs/s/95quqz/tactical_retreat_freely_available_multi) |
| 9 | 0 | [Getting Google Cast on my Soundbar](https://codon.org.uk/~mjg59/blog/p/getting-google-cast-on-my-soundbar/) | `reversing` | [讨论](https://lobste.rs/s/uyobll/getting_google_cast_on_my_soundbar) |
| 18 | 6 | [Pidgin 3.0 Alpha 4 2.98.0 has been released](https://discourse.imfreedom.org/t/pidgin-3-0-alpha-4-2-98-0-has-been-released/445) | `release` | [讨论](https://lobste.rs/s/qsvspv/pidgin_3_0_alpha_4_2_98_0_has_been_released) |
| 5 | 0 | [The top ten reasons embedded projects get into trouble (2002)](https://www.ganssle.com/articles/jackstoptenlist.htm) | `hardware` | [讨论](https://lobste.rs/s/mk87la/top_ten_reasons_embedded_projects_get) |
| 4 | 2 | [Defending the patch gap against automated attackers](https://blog.mozilla.org/en/firefox/privacy-security/defending-patch-gap/) | `browsers` `security` | [讨论](https://lobste.rs/s/dtvr7y/defending_patch_gap_against_automated) |
| 9 | 0 | [Go 1.28's HTTP/2 Parking: Measuring Memory Savings](https://abdolirad.me/articles/go-1-28-http2-parking-memory/) | `go` | [讨论](https://lobste.rs/s/mhmqky/go_1_28_s_http_2_parking_measuring_memory) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 77 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 11 | 6 | 54% | — |
| 🔴 先核对 | 13 | 6 | 46% | — |
| 🟡 在降温 | 5 | 0 | 0% | — |
| 🔵 已被发现 | 2 | 0 | 0% | — |
| 🟢 窗口内 | 7 | 4 | 57% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [Leonxlnx/earshot](https://github.com/Leonxlnx/earshot) | 2026-10-17 | 🔴 先核对 | 367 | 3329 | 0 | ✅ 起来了 |
| [anujasid/mcp-for-blender-pro](https://github.com/anujasid/mcp-for-blender-pro) | 2026-10-17 | 🔴 先核对 | 306 | 0 | 0 | 仓库没了 |
| [feder-cr/git-ai](https://github.com/feder-cr/git-ai) | 2026-10-17 | 🔴 先核对 | 1067 | 1029 | 0 | 没起来 |
| [trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) | 2026-10-17 | 🔴 先核对 | 1209 | 1216 | 0 | 没起来 |

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
