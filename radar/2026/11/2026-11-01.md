# early-radar 选题雷达 · 2026-11-01

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 107 个，细查前 20 个 · 比上次 = 和 2026-10-31 那次比 · 生成于 2026-11-01 05:38 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 1 个 · Show HN ✅ 18 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 6 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 9 个 · 🟡 在降温 6 个 · 🔵 已被发现 0 个 · 💤 不活跃 0 个 · 🔴 先核对 5 个
- **今天新出现 3 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) 平均每天 +3690，见 [爆发](#爆发)
- **复盘**：🚀 爆发 8/14 · 🔴 先核对 7/14 · 🟡 在降温 0/5 · 🔵 已被发现 0/2 · 🟢 窗口内 4/8（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [SoMarkAI/OXR](https://github.com/SoMarkAI/OXR) — An open-source document parsing model with SOTA accuracy and…（近 7 天 +1999，比前 7 天快 2.5 倍，在加速）
  - [l0ng-ai/openidea](https://github.com/l0ng-ai/openidea) — The IDE you know, rebuilt in Rust. IntelliJ IDEA–style keyma…（近 7 天 +1755，比前 7 天快 12.6 倍，在加速）
  - [qybaihe/bla](https://github.com/qybaihe/bla) — 🛡️ BLA (Blind LLM Agents) — Adversarial defense shield that…（近 7 天 +1740，比前 7 天快 870.0 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 22 个（star 合计 25736），代表：[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：5 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: TitleArt – Make text like it's 1997](https://titleart.dvy.io/) — 409 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| 🆕 [deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) | 3690 | 3690 | — | 1 | [8](https://news.ycombinator.com/item?id=50316116) | dsh superagent prototype · deepseek-ai dsh superagent prototype · deepseek dsh superagent prototype | Towards a More Autonomous Agent System |
| [heydamir/unslop](https://github.com/heydamir/unslop) | 3742 | 1450 | +2234 | 2.6 | — | unslop · heydamir unslop · damir unslop | A Claude skill that turns vibecoded, AI-looking UI into a de… |
| [wangzan101/Mika](https://github.com/wangzan101/Mika) | 2973 | 1131 | +1285 | 2.6 | — | mika · wangzan101 mika · wangzan mika | An on-device AI agent for Android that operates apps and the… |
| 🆕 [patch-gg/pixelfx](https://github.com/patch-gg/pixelfx) | 1659 | 849 | +1247 | 2 | — | pixelfx · patch-gg pixelfx · patch pixelfx | 244 pixel art effects, every one a small piece of code. Plus… |
| 🆕 [ccch1mneyyy/dsh-Go](https://github.com/ccch1mneyyy/dsh-Go) | 3808 | 552 | +1027 | 6.9 | — | dsh go · ccch1mneyyy dsh go · chimney dsh go | dsh-go — DeepSeek Harness 装进口袋：手机本机运行，也能遥控你的电脑。 |
| [anhao/ai-pose-gallery-zh](https://github.com/anhao/ai-pose-gallery-zh) | 4813 | 1020 | +707 | 4.7 | — | ai pose gallery zh · anhao ai pose gallery zh | 中文版 AI 姿势参考图库 · 1439 组 / 2878 张图片 / 完整汉化 · 零依赖静态画廊 |
| [valentderah/totk-pc-recomp](https://github.com/valentderah/totk-pc-recomp) | 2728 | 1006 | +947 | 2.7 | — | totk pc recomp · valentderah totk pc recomp · valiantsin totk pc recomp | Static recompilation of The Legend of Zelda: Tears of the Ki… |
| [Zagitta/gpu-unlock](https://github.com/Zagitta/gpu-unlock) | 13909 | 981 | +377 | 14.2 | [351](https://news.ycombinator.com/item?id=50219700) | gpu unlock · zagitta gpu unlock · simon gpu unlock | Your GeForce runs AI at half speed. This fixes it for 20/30/… |
| [unclebob/ub-mode](https://github.com/unclebob/ub-mode) | 5895 | 898 | +448 | 6.6 | — | ub mode · unclebob ub mode · robert ub mode |  |
| 🆕 [Djihads80/Eglantine](https://github.com/Djihads80/Eglantine) | 1407 | 437 | +821 | 3.2 | — | eglantine · djihads80 eglantine · djihad eglantine | VERY experimental Nintendo Switch 2 emulator |
| [pengchujin/aerial-tv](https://github.com/pengchujin/aerial-tv) | 8396 | 708 | +279 | 11.9 | — | aerial tv · pengchujin aerial tv | 给国产电视的一块干净桌面：参照 tvOS 设计的开源 Android TV 桌面，没有广告，开机自动接管。A tvOS-… |
| [rddmwmddr/android-ad-cleaner](https://github.com/rddmwmddr/android-ad-cleaner) | 5433 | 679 | +290 | 8 | — | android ad cleaner · rddmwmddr android ad cleaner | 关掉国产安卓手机系统里的广告、热搜、资讯推荐和营销推送。不 root，可还原，支持 AI 智能体一键执行。 |
| [kevinraymond/florilegium](https://github.com/kevinraymond/florilegium) | 1172 | 614 | +449 | 1.9 | [374](https://news.ycombinator.com/item?id=50305637) | florilegium · kevinraymond florilegium · kevin florilegium | Procedurally generated Delft-blue floral page margins for Lu… |
| [interplains/Zero-Breach-Toolkit](https://github.com/interplains/Zero-Breach-Toolkit) | 4020 | 607 | +125 | 6.6 | — | zero breach toolkit · interplains zero breach toolkit · archivegenocide zero breach toolkit | Free, open-source, offline checks for traces of known mercen… |
| [paipiange/nvzhuang](https://github.com/paipiange/nvzhuang) | 1777 | 596 | +440 | 3 | — | nvzhuang · paipiange nvzhuang | 1407 张 AI 女装参考图集与虚拟试穿网站，支持中英检索、OpenAI Images / Gemini / 豆包及自… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 91.2 | 🟢 窗口内 | [SoMarkAI/OXR](https://github.com/SoMarkAI/OXR) | Python | 2783 | +92 | +1999 | +784 | `·▁▂▂▂▃▃▅█▄▄▂▂·` | 27 | [3](https://news.ycombinator.com/item?id=50183506) | — |
| 2 | 89.6 | 🟢 窗口内 | [l0ng-ai/openidea](https://github.com/l0ng-ai/openidea) | TypeScript | 1894 | +193 | +1755 | +139 | `···▁▁▂▁▁▄██▆▄·` | 10 | — | — |
| 3 | 89.5 | 🟢 窗口内 | [qybaihe/bla](https://github.com/qybaihe/bla) | JavaScript | 1742 | +259 | +1740 | +2 | `······▁▁▂▁█▅▃·` | 7 | — | — |
| 4 | 89.5 | 🟢 窗口内 | [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) | TypeScript | 1741 | +75 | +1740 | +1 | `··▁·····██▃▂▂·` | 10 | — | — |
| 5 | 87.9 | 🟢 窗口内 | [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | TypeScript | 1600 | +40 | +1512 | +88 | `······▂█▄▃▂▁▁·` | 6 | — | — |
| 6 | 86.7 | 🟢 窗口内 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | Rust | 1824 | +31 | +1373 | +451 | `▁▃▁▁▁▂▃▆█▂▁▂▁·` | 12 | — | — |
| 7 | 84.3 | 🆕 🟢 窗口内 | [daveebbelaar/bama](https://github.com/daveebbelaar/bama) | Swift | 1124 | +167 | +1124 | +0 | `·······▄██▆▅▅·` | 7 | — | — |
| 8 | 80.4 | 🟢 窗口内 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 1407 | +58 | +814 | +593 | `······█▄▄▂▂▂▂·` | 6 | — | — |
| 9 | 77.8 | 🟢 窗口内 | [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) | Kotlin | 1291 | +98 | +655 | +636 | `···▁▄█▇▄▅▄▃▃▃·` | 10 | — | — |
| 10 | 66.1 | 🟡 在降温 | [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) | Python | 1628 | +88 | +743 | +885 | `·····▅█▅▂▁▂▂▂·` | 9 | — | — |
| 11 | 60.7 | 🟡 在降温 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2394 | +38 | +432 | +1962 | `··▁▁█▅▂▂▂▁▁▁▁·` | 10 | [3](https://news.ycombinator.com/item?id=50207695) | — |
| 12 | 58.5 | 🟡 在降温 | [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) | Python | 1732 | +73 | +345 | +941 | `▆▅▃▂█▆▆▃▃▂▂▃▃·` | 15 | [1](https://news.ycombinator.com/item?id=50177079) | — |
| 13 | 55.8 | 🟡 在降温 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 1950 | +25 | +263 | +1108 | `█▄▃▄▂▂▂▂▂▂▂▁▁·` | 13 | — | — |
| 14 | 54.3 | 🟡 在降温 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 2216 | +23 | +227 | +383 | `█▇▇▅▄▄▇▆▆▅▄▄▃·` | 21 | — | — |
| 15 | 53.7 | 🟡 在降温 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 2004 | +21 | +214 | +687 | `▁█▃▂▂▁▁▂▂▂▂▁▁·` | 19 | — | — |
| 16 | 48 | 🔴 先核对 | [wangzan101/Mika](https://github.com/wangzan101/Mika) | Kotlin | 2973 | +1285 | +2973 | +0 | `··········▂█▆·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 46.8 | 🔴 先核对 | [t3dotgg/tstack](https://github.com/t3dotgg/tstack) | Python | 2545 | +66 | +2444 | +101 | `····▁▁▁█▃▂▂▁▁·` | 8 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 39.5 | 🆕 🔴 先核对 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 722 | — | +717 | +5 | `······▁▁▂▁▂▄█·` | 5 | [2](https://news.ycombinator.com/item?id=50272846) | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 35.6 | 🆕 🔴 先核对 | [Balanov/svoi](https://github.com/Balanov/svoi) | JavaScript | 377 | — | +377 | +0 | `············█·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 25 | 🔴 先核对 | [mizorewww/gdirect](https://github.com/mizorewww/gdirect) | Rust | 778 | +4 | +147 | +631 | `·····▁█▂▁▁▁▁▁·` | 6 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 589 | 30 | 50463 | [wangzan101/Mika](https://github.com/wangzan101/Mika)、[SoMarkAI/OXR](https://github.com/SoMarkAI/OXR)、[t3dotgg/tstack](https://github.com/t3dotgg/tstack) |
| `mcp` | 307 | 30 | 33692 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[yeqv111/mccarbon](https://github.com/yeqv111/mccarbon)、[qybaihe/bla](https://github.com/qybaihe/bla) |
| `rust` | 221 | 30 | 30515 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx)、[xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[opengeos/RustGIS](https://github.com/opengeos/RustGIS) |
| `local-first` | 79 | 30 | 10199 | [chenxiachan/textfold](https://github.com/chenxiachan/textfold)、[thtbee/nectarlink](https://github.com/thtbee/nectarlink)、[aboard-io/tinylittleoffice](https://github.com/aboard-io/tinylittleoffice) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 22 | 25736 | [Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) |
| `ai-agents` | 22 | 19337 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering) |
| `codex` | 16 | 15474 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[shinshin86/mesh-avatar-studio](https://github.com/shinshin86/mesh-avatar-studio)、[UnderleveledBuilder/awesome-short-drama-skills](https://github.com/UnderleveledBuilder/awesome-short-drama-skills) |
| `agent-skills` | 15 | 18386 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) |
| `llm` | 15 | 14189 | [wangzan101/Mika](https://github.com/wangzan101/Mika)、[jiwoochris/artex-global](https://github.com/jiwoochris/artex-global)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX) |
| `mcp-server` | 12 | 12759 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[qybaihe/bla](https://github.com/qybaihe/bla)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `ai-agent` | 11 | 11923 | [wangzan101/Mika](https://github.com/wangzan101/Mika)、[jiwoochris/artex-global](https://github.com/jiwoochris/artex-global)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist) |
| `windows` | 9 | 6077 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[LingCore/WinShun](https://github.com/LingCore/WinShun)、[thtbee/nectarlink](https://github.com/thtbee/nectarlink) |
| `developer-tools` | 8 | 8183 | [l0ng-ai/openidea](https://github.com/l0ng-ai/openidea)、[indexable-inc/blaze](https://github.com/indexable-inc/blaze)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) |
| `typescript` | 8 | 4834 | [pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust)、[rociiu/talorys](https://github.com/rociiu/talorys)、[stencil-hq/dquickts](https://github.com/stencil-hq/dquickts) |
| `claude-skills` | 7 | 10219 | [Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) |
| `macos` | 7 | 6137 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[kitlangton/scrawl](https://github.com/kitlangton/scrawl) |

**语言分布**：Rust 30 · Python 25 · TypeScript 17 · JavaScript 16 · Go 5 · HTML 3 · C 2 · Kotlin 2

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [SoMarkAI/OXR](https://github.com/SoMarkAI/OXR) · 🟢 窗口内 · 91.2 分

> An open-source document parsing model with SOTA accuracy and speed, using an RSI loop during post-training.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2783 | +1999 | +784 | 209 | 21 | Python | — | 10-05（27 天前） | 7 天前 |

- **近 14 天每天新增**：`·▁▂▂▂▃▃▅█▄▄▂▂·` 0 24 101 129 131 218 181 452 731 308 290 134 84 0
- **势头**：比前 7 天快 2.5 倍，在加速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=50183506)）
- **topics**：`agent` `llm-tools` `ocr` `oxr` `rsi` `vlm` `vlm-ocr`
- **主页**：<https://somark.ai/oxr>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [l0ng-ai/openidea](https://github.com/l0ng-ai/openidea) · 🟢 窗口内 · 89.6 分

> The IDE you know, rebuilt in Rust. IntelliJ IDEA–style keymap, tool windows and search-everywhere in a fast native app: editor, code insight, debugger, Git, terminal, database and HTTP clients for 60+ languages.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1894 | +1755 | +139 | 189 | 97 | TypeScript | Apache-2.0 | 10-21（10 天前） | 今天 |

- **近 14 天每天新增**：`···▁▁▂▁▁▄██▆▄·` 0 0 0 35 23 46 35 21 191 488 504 368 183 0
- **势头**：比前 7 天快 12.6 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`code-editor` `cross-platform` `dap` `database-client` `debugger` `desktop-app` `developer-tools` `git` `http-client` `ide` `intellij` `lsp` `rust` `tauri` `terminal`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [qybaihe/bla](https://github.com/qybaihe/bla) · 🟢 窗口内 · 89.5 分

> 🛡️ BLA (Blind LLM Agents) — Adversarial defense shield that protects binaries, Electron apps, JS bundles, Python, and WebAssembly against AI reverse-engineering agents like REA. Poison -> Exhaust -> Hallucinate.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1742 | +1740 | +2 | 235 | 10 | JavaScript | MIT | 10-25（7 天前） | 今天 |

- **近 14 天每天新增**：`······▁▁▂▁█▅▃·` 0 0 0 0 0 0 2 27 143 31 818 489 232 0
- **势头**：比前 7 天快 870.0 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adversarial-ai` `claude-code` `cursor` `electron-security` `llm-security` `mcp` `mcp-server` `obfuscation` `reverse-engineering` `webassembly`
- **主页**：<https://bla.tools>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) · 🟢 窗口内 · 89.5 分

> An Open Source template for a proactive AI agent that gets your work done and keeps you in the loop.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1741 | +1740 | +1 | 223 | 11 | TypeScript | MIT | 10-21（10 天前） | 今天 |

- **近 14 天每天新增**：`··▁·····██▃▂▂·` 0 0 1 0 0 0 0 0 703 690 172 105 70 0
- **势头**：比前 7 天快 1740.0 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<copilotkit.ai/openduet>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) · 🟢 窗口内 · 87.9 分

> AI digital-human talking-head videos from one photo: Renoise MCP generation + 5 editing styles + 48 creator-grade packaging components. Agent skill for Claude Code / Codex / OpenClaw / WorkBuddy …

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1600 | +1512 | +88 | 366 | 4 | TypeScript | MIT | 10-26（6 天前） | 今天 |

- **近 14 天每天新增**：`······▂█▄▃▂▁▁·` 0 0 0 0 0 0 88 778 301 190 154 53 36 0
- **势头**：比前 7 天快 17.2 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [indexable-inc/blaze](https://github.com/indexable-inc/blaze) · 🟢 窗口内 · 86.7 分

> Incremental rust builds up to 92x faster than cargo/rustc

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1824 | +1373 | +451 | 65 | 455 | Rust | Apache-2.0 | 10-19（12 天前） | 今天 |

- **近 14 天每天新增**：`▁▃▁▁▁▂▃▆█▂▁▂▁·` 17 151 14 5 4 104 156 455 673 126 37 54 28 0
- **势头**：比前 7 天快 3.0 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`cargo` `compiler` `cranelift` `developer-tools` `hot-reload` `incremental-compilation` `jit` `live-coding` `rust` `rust-analyzer`
- **主页**：<https://ix.dev/blaze>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. 🆕 [daveebbelaar/bama](https://github.com/daveebbelaar/bama) · 🟢 窗口内 · 84.3 分

> BAMA: Build Any Mac App. Agent skills to research, clone, design, build, optimize, and test native macOS apps with Swift and SwiftUI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1124 | +1124 | +0 | 154 | 1 | Swift | MIT | 10-24（7 天前） | 2 天前 |

- **近 14 天每天新增**：`·······▄██▆▅▅·` 0 0 0 0 0 0 0 121 265 251 184 152 151 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-agents` `app-clone` `claude-code` `claude-code-plugin` `codex` `computer-use` `liquid-glass` `macos` `macos-app` `native-apps` `skills` `swift` `swiftdata` `swiftui`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) · 🟢 窗口内 · 80.4 分

> Evidence-first genealogy skill for AI agents (Codex, Claude Code): church books, civil, military, deportation and repression records across the former USSR. Replies in your language.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1407 | +814 | +593 | 150 | 2 | Python | MIT | 10-25（6 天前） | 今天 |

- **近 14 天每天新增**：`······█▄▄▂▂▂▂·` 0 0 0 0 0 0 593 229 255 113 88 72 57 0
- **势头**：比前 7 天快 1.4 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `archives` `claude-code` `codex` `family-history` `familysearch` `genealogy` `ussr`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 9. [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) · 🟢 窗口内 · 77.8 分

> A community-built phone app for Clean Your TV: clean up an Android TV from your phone. No laptop, no coding agent, nothing uninstalled.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1291 | +655 | +636 | 112 | 3359 | Kotlin | MIT | 10-21（10 天前） | 今天 |

- **近 14 天每天新增**：`···▁▄█▇▄▅▄▃▃▃·` 0 0 0 1 103 288 244 133 150 114 89 79 90 0
- **势头**：和前 7 天差不多
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adb` `android-tv` `debloat` `fire-tv` `google-tv` `launcher`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 10. [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) · 🟡 在降温 · 66.1 分

> Agent Skills that teach coding agents to write, review, and port idiomatic Rust, plus a tested clippy config. Works with Claude Code, Codex, Copilot, Cursor, and Gemini CLI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1628 | +743 | +885 | 83 | 3 | Python | MIT | 10-23（9 天前） | 1 天前 |

- **近 14 天每天新增**：`·····▅█▅▂▁▂▂▂·` 0 0 0 0 0 302 583 357 89 41 60 119 77 0
- **势头**：只有前 7 天的 84%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `claude-code` `claude-plugin` `claude-skills` `clippy` `code-review` `coding-agent` `cursor` `rust` `style-guide`
- **主页**：<https://www.beautifulrust.dev>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [wangzan101/Mika](https://github.com/wangzan101/Mika) — 一天进了一半以上的 star，但 HN 上没火过
- [t3dotgg/tstack](https://github.com/t3dotgg/tstack) — 一天进了一半以上的 star，但 HN 上没火过
- [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) — 一天进了一半以上的 star，但 HN 上没火过
- [Balanov/svoi](https://github.com/Balanov/svoi) — 一天进了一半以上的 star，但 HN 上没火过
- [mizorewww/gdirect](https://github.com/mizorewww/gdirect) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 409 | 82 | [Show HN: TitleArt – Make text like it's 1997](https://titleart.dvy.io/) | [HN](https://news.ycombinator.com/item?id=50238708) |
| 284 | 144 | [Show HN: A working Nintendo in ~1GB of Qwen weights](https://github.com/dbreunig/nesformer) | [HN](https://news.ycombinator.com/item?id=50306442) |
| 236 | 74 | [Show HN: To Honor Sir Patrick Stewart, Enjoy the TNG Episode Guessing Game](https://tng.episodle.com/) | [HN](https://news.ycombinator.com/item?id=50311686) |
| 184 | 49 | [Show HN: Marelleo, an open-source story box I built for my kids using ESP32](https://zebra.rodeo/en/blog/marelleo/) | [HN](https://news.ycombinator.com/item?id=50260753) |
| 178 | 49 | [Show HN: I put employees inside S&P 500 market-cap bubbles](https://bigwhalehunting.com/workforce/) | [HN](https://news.ycombinator.com/item?id=50232312) |
| 177 | 43 | [Show HN: Hob - Open-source, on device alternative to Claude Cowork and ChatGPT](https://github.com/FrigadeHQ/hob) | [HN](https://news.ycombinator.com/item?id=50246238) |
| 154 | 130 | [Show HN: Auto Dismiss Mac OS "Allow <app> to find devices on local networks?"](https://github.com/johncassil/dontallow) | [HN](https://news.ycombinator.com/item?id=50294506) |
| 129 | 35 | [Show HN: I Turned DOOM into a Transformer](https://github.com/mottopanikeiku/doomformer) | [HN](https://news.ycombinator.com/item?id=50297697) |
| 84 | 42 | [Show HN: I built a multiplayer game where you're an aerial fighter cat](https://catcopter.com) | [HN](https://news.ycombinator.com/item?id=50305320) |
| 82 | 36 | [Show HN: SlideBySide – Present slides without sharing your screen](https://slidebyside.com/) | [HN](https://news.ycombinator.com/item?id=50276883) |
| 81 | 13 | [Show HN: A proof-of-concept formalization of the IRS federal tax forms](https://github.com/emmilco/us-tax-model) | [HN](https://news.ycombinator.com/item?id=50278678) |
| 77 | 46 | [Show HN: NES Contra (1987) port (ASM –> C and then C –> WebAssembly)](https://epoyraz.github.io/nes-contra-us/) | [HN](https://news.ycombinator.com/item?id=50319169) |
| 71 | 3 | [Show HN: A language model that lives in a boot sector](https://github.com/kerlenton/bootgpt) | [HN](https://news.ycombinator.com/item?id=50315782) |
| 60 | 43 | [Show HN: Farol – A risk map of a pull request for the person who approves it](https://github.com/winnin/farol) | [HN](https://news.ycombinator.com/item?id=50231349) |
| 60 | 0 | [Show HN: Arsaze – Cursor for video editing (Tab-complete and agent edits)](https://www.arsaze.com) | [HN](https://news.ycombinator.com/item?id=50300618) |
| 53 | 36 | [Show HN: Ghostman – A fast, keyboard-driven TUI API client and webhook inspector](https://github.com/4yk5/Ghostman) | [HN](https://news.ycombinator.com/item?id=50300902) |
| 52 | 36 | [Show HN: A USB-C LTE modem that gives my computer a phone line](https://github.com/Koppar-AI/koppar-lte-modem) | [HN](https://news.ycombinator.com/item?id=50317331) |
| 52 | 16 | [Show HN: I rebuilt Kubernetes for ESP32 microcontrollers](https://github.com/arterialist/kube32) | [HN](https://news.ycombinator.com/item?id=50291812) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 7 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 3078★ |
| 160 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 119103★ |
| 85 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 21678★ |
| 31 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 8862★ |
| 62 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 44675★ |
| 105 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 30126★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 35027★ |
| 48 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 35054★ |
| 11 | [Investor's Last Exam: Can AI Agents Do Equity Investment Without Seeing the Future?](https://huggingface.co/papers/2610.38342) | Investor's Last Exam evaluates financial agents on end-to-end equity research using frozen evidence, expert criteria, and dependency graphs,… | 💡 [Prophetlab/Investor-Last-Exam](https://github.com/Prophetlab/Investor-Last-Exam) 127★ |
| 20 | [HairDeck: Animation-Ready Stylized Hair Cards from a Single Image](https://huggingface.co/papers/2610.40599) | HairDeck generates stylized hair cards and spring-bone animations as unordered token sets using a diffusion transformer, improving accuracy… | 💡 [hyz317/HairDeck](https://github.com/hyz317/HairDeck) 379★ |
| 90 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 92355★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 104 | [MOSS-Image Technical Report](https://huggingface.co/papers/2610.23374) | MOSS-Image is an open diffusion transformer that combines high-fidelity synthesis with intent-aware prompt enhancement to generate text-rich… | [OpenMOSS/MOSS-Image](https://github.com/OpenMOSS/MOSS-Image) 2362★ |
| 20 | [Intrinsic Distribution Matching](https://huggingface.co/papers/2610.39633) | Intrinsic Distribution Matching improves few-step text-to-image generation by adding explicit moment constraints to distribution matching di… | 💡 [inclusionAI/IDM](https://github.com/inclusionAI/IDM) 85★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 82885★ |
| 107 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 2941★ |
| 9 | [Xiaomi-OCR-0 Technical Report](https://huggingface.co/papers/2609.36136) | Xiaomi-OCR-0 is a compact vision-language model that unifies document parsing and OCR understanding through automated data synthesis, progre… | 💡 [SeerRay-Lab/Xiaomi-OCR-0](https://github.com/SeerRay-Lab/Xiaomi-OCR-0) 369★ |
| 113 | [FreeToken: Efficient Edge-Native MoE Serving with Bandwidth-Adaptive Execution](https://huggingface.co/papers/2608.16157) | FreeToken is an edge-native Mixture-of-Experts serving system that dynamically maps computation and model state onto heterogeneous local har… | [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken) 15012★ |
| 123 | [Hy-Nomas: Towards Free-form Interactive World Generation](https://huggingface.co/papers/2610.36729) | Hy-Nomas is a video world model that uses causal attention and structured conditioning to generate interactive, multi-turn video segments wi… | 💡 [Tencent-Hunyuan/Hy-Nomas](https://github.com/Tencent-Hunyuan/Hy-Nomas) 431★ |
| 180 | [SmolDocling: An ultra-compact vision-language model for end-to-end multi-modal document conversion](https://huggingface.co/papers/2503.11576) | SmolDocling is a compact vision-language model that performs end-to-end document conversion with robust performance across various document… | [docling-project/docling](https://github.com/docling-project/docling) 69924★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 50 | [deepseek v4.1 flash 1017 gsq rco](https://huggingface.co/AtomicChat/DeepSeek-V4.1-Flash-1017-Uncensored-GSQ-RCO-GGUF) | text-generation | 102 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 83 | 18 | [Jepsen: ParticleDB 1.1.4](https://jepsen.io/analyses/particledb-1.1.4) | `databases` `testing` | [讨论](https://lobste.rs/s/drwd4j/jepsen_particledb_1_1_4) |
| 37 | 18 | [The Kluever Maneuver](https://jordi.inversethought.com/blog/the-kluever-maneuver/) | `testing` | [讨论](https://lobste.rs/s/rpiu3w/kluever_maneuver) |
| 50 | 8 | [Avoid Public Functions Calling Other Public Functions](https://matklad.github.io/2026/10/29/pub-calls-pub.html) | `api` `programming` | [讨论](https://lobste.rs/s/k508we/avoid_public_functions_calling_other) |
| 24 | 9 | [Mystery of 60-Second Fluctuations in Power Grids Solved](https://www.fz-juelich.de/en/news/archive/press-release/2026/mystery-of-60-second-fluctuations-in-power-grids-solved) | `science` | [讨论](https://lobste.rs/s/qwou15/mystery_60_second_fluctuations_power) |
| 9 | 2 | [Introducing Kwi, a new KDE terminal emulator](https://blogs.kde.org/2026/11/01/introducing-kwi/) | `linux` | [讨论](https://lobste.rs/s/lt44rt/introducing_kwi_new_kde_terminal) |
| 9 | 2 | [An LC-3 Disassembler in Haskell](https://abhinavsarkar.net/posts/lc3-disassembler/) | `assembly` `haskell` `reversing` | [讨论](https://lobste.rs/s/qoznnh/lc_3_disassembler_haskell) |
| 64 | 9 | [The support case of a customer who said that all they could see was a black screen](https://devblogs.microsoft.com/oldnewthing/20261029-00/?p=112808/) | `historical` `windows` | [讨论](https://lobste.rs/s/soosuu/support_case_customer_who_said_all_they) |
| 10 | 1 | [Novellas with groff](https://movq.de/blog/postings/2026-10-31/0/POSTING-en.html) | `unix` | [讨论](https://lobste.rs/s/54xwm8/novellas_with_groff) |
| 13 | 1 | [Enlightenment 0.28.0 Release](https://www.enlightenment.org/news/2026-10-31-enlightenment-0.28.0) | `linux` `release` | [讨论](https://lobste.rs/s/fmawla/enlightenment_0_28_0_release) |
| 44 | 11 | [How hard is it to check for whitespace?](https://serce.me/posts/2026-10-30-how-hard-is-it-to-check-for-whitespace) | `java` `performance` | [讨论](https://lobste.rs/s/1pmuy7/how_hard_is_it_check_for_whitespace) |
| 167 | 38 | [Backdoors in Claude Code for VS, Cursor official extensions](https://cyberplace.social/@GossiTheDog/117528831681803563) | `security` | [讨论](https://lobste.rs/s/ttp7aq/backdoors_claude_code_for_vs_cursor) |
| 10 | 10 | [Digital minimalism](https://vitalik.eth.limo/general/2026/10/31/digital_minimalism.html) | `privacy` | [讨论](https://lobste.rs/s/y81ppi/digital_minimalism) |
| 20 | 6 | [Tangled, hire a front-end accessibility expert](https://dbushell.com/2026/11/01/tangled-accessibility/) | `a11y` `rant` `vcs` | [讨论](https://lobste.rs/s/ymqjuj/tangled_hire_front_end_accessibility) |
| 25 | 2 | [Clojure/Conj 2026](http://www.youtube.com/playlist?list=PLAkHRk3lgU_Q) | `clojure` `video` | [讨论](https://lobste.rs/s/wd4ye5/clojure_conj_2026) |
| 10 | 1 | [Let’s Build a Brain](https://aatishb.com/myriad/lets-build-a-brain/) | `ai` `programming` | [讨论](https://lobste.rs/s/bmmj1e/let_s_build_brain) |
| 41 | 22 | [No, npm, “estee” is not a typo of “testem”](https://smoores.dev/post/no_npm_estee_is_not_a_typo/) | `javascript` | [讨论](https://lobste.rs/s/xudbqx/no_npm_estee_is_not_typo_testem) |
| 6 | 2 | [Speeding up GPU copies by permuting iteration spaces, or, optimising the identity function](https://futhark-lang.org/blog/2026-10-31-faster-copying.html) | `compilers` | [讨论](https://lobste.rs/s/1abkzu/speeding_up_gpu_copies_by_permuting) |
| 94 | 34 | [Do At-Proto Users Know This Is Public?](https://melaniekat.com/blog/public-on-pds/) | `privacy` | [讨论](https://lobste.rs/s/htgcuc/do_at_proto_users_know_this_is_public) |
| 43 | 30 | [The federated code forge](https://tangled.org/blog/forge/) | `distributed` `vcs` | [讨论](https://lobste.rs/s/ukj8mm/federated_code_forge) |
| 1 | 0 | [A brief history of just-in-time (2003)](https://dl.acm.org/doi/10.1145/857076.857077) | `compilers` `historical` `pdf` | [讨论](https://lobste.rs/s/h6dt6e/brief_history_just_time_2003) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 78 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 14 | 8 | 57% | — |
| 🔴 先核对 | 14 | 7 | 50% | — |
| 🟡 在降温 | 5 | 0 | 0% | — |
| 🔵 已被发现 | 2 | 0 | 0% | — |
| 🟢 窗口内 | 8 | 4 | 50% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [aicodeking/leanrea](https://github.com/aicodeking/leanrea) | 2026-10-18 | 🔴 先核对 | 462 | 3807 | 0 | ✅ 起来了 |
| [anujasid/blender-ai-mcp-addon](https://github.com/anujasid/blender-ai-mcp-addon) | 2026-10-18 | 🔴 先核对 | 642 | 0 | 0 | 仓库没了 |
| [google-research/harness2](https://github.com/google-research/harness2) | 2026-10-18 | 🚀 爆发 | 1688 | 21722 | 81 | ✅ 起来了 |
| [jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) | 2026-10-18 | 🟢 窗口内 | 938 | 1212 | 0 | 没起来 |
| [tangency-labs/solidcraft](https://github.com/tangency-labs/solidcraft) | 2026-10-18 | 🚀 爆发 | 4409 | 12669 | 0 | ✅ 起来了 |
| [xscreensaver-official/xscreensaver](https://github.com/xscreensaver-official/xscreensaver) | 2026-10-18 | 🚀 爆发 | 737 | 1209 | 92 | 没起来 |

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
