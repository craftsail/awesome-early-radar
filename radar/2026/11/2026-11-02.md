# early-radar 选题雷达 · 2026-11-02

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 102 个，细查前 20 个 · 比上次 = 和 2026-11-01 那次比 · 生成于 2026-11-02 05:35 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 3 个 · Show HN ✅ 19 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 8 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 6 个 · 🟡 在降温 9 个 · 🔵 已被发现 0 个 · 💤 不活跃 0 个 · 🔴 先核对 5 个
- **今天新出现 2 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) 平均每天 +5064，见 [爆发](#爆发)
- **复盘**：🚀 爆发 13/19 · 🔴 先核对 8/15 · 🟡 在降温 0/5 · 🔵 已被发现 0/2 · 🟢 窗口内 5/9（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [qybaihe/bla](https://github.com/qybaihe/bla) — 🛡️ BLA (Blind LLM Agents) — Adversarial defense shield that…（近 7 天 +1842，比前 7 天快 63.5 倍，在加速）
  - [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) — An Open Source template for a proactive AI agent that gets y…（近 7 天 +1805，比前 7 天快 1805.0 倍，在加速）
  - [SoMarkAI/OXR](https://github.com/SoMarkAI/OXR) — An open-source document parsing model with SOTA accuracy and…（近 7 天 +1632，比前 7 天快 1.3 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 21 个（star 合计 25995），代表：[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：4 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: HackerBooks – HackerTube, but for books mentioned on HN](https://hackerbooks.org) — 1136 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) | 9295 | 5064 | +5605 | 1.8 | [11](https://news.ycombinator.com/item?id=50316116) | dsh superagent prototype · deepseek-ai dsh superagent prototype · deepseek dsh superagent prototype | Towards a More Autonomous Agent System |
| [l0ng-ai/openidea](https://github.com/l0ng-ai/openidea) | 3965 | 338 | +2071 | 11.7 | [38](https://news.ycombinator.com/item?id=50323848) | openidea · l0ng-ai openidea | The IDE you know, rebuilt in Rust. IntelliJ IDEA–style keyma… |
| [heydamir/unslop](https://github.com/heydamir/unslop) | 5086 | 1421 | +1344 | 3.6 | — | unslop · heydamir unslop · damir unslop | A Claude skill that turns vibecoded, AI-looking UI into a de… |
| [wangzan101/Mika](https://github.com/wangzan101/Mika) | 4297 | 1185 | +1324 | 3.6 | — | mika · wangzan101 mika · wangzan mika | An on-device AI agent for Android that operates apps and the… |
| [patch-gg/pixelfx](https://github.com/patch-gg/pixelfx) | 2867 | 971 | +1208 | 3 | — | pixelfx · patch-gg pixelfx · patch pixelfx | 244 pixel art effects, every one a small piece of code. Plus… |
| [ccch1mneyyy/dsh-Go](https://github.com/ccch1mneyyy/dsh-Go) | 5002 | 634 | +1194 | 7.9 | — | dsh go · ccch1mneyyy dsh go · chimney dsh go | dsh-go — DeepSeek Harness 装进口袋：手机本机运行，也能遥控你的电脑。 |
| ✅ [storytold/craft-anything](https://github.com/storytold/craft-anything) | 1570 | 972 | — | 1.6 | — | craft anything · storytold craft anything · artcraft craft anything | Craft Anything: understand how any software works, and craft… |
| 🆕 [haydenschmitty/floorplan](https://github.com/haydenschmitty/floorplan) | 1887 | 329 | +926 | 5.7 | — | floorplan · haydenschmitty floorplan · hayden floorplan | See how your app actually fits together. An interactive, pla… |
| [anhao/ai-pose-gallery-zh](https://github.com/anhao/ai-pose-gallery-zh) | 5247 | 918 | +434 | 5.7 | — | ai pose gallery zh · anhao ai pose gallery zh | 中文版 AI 姿势参考图库 · 1439 组 / 2878 张图片 / 完整汉化 · 零依赖静态画廊 |
| [valentderah/totk-pc-recomp](https://github.com/valentderah/totk-pc-recomp) | 3336 | 899 | +608 | 3.7 | — | totk pc recomp · valentderah totk pc recomp · valiantsin totk pc recomp | Static recompilation of The Legend of Zelda: Tears of the Ki… |
| [unclebob/ub-mode](https://github.com/unclebob/ub-mode) | 6329 | 837 | +434 | 7.6 | — | ub mode · unclebob ub mode · robert ub mode |  |
| [Djihads80/Eglantine](https://github.com/Djihads80/Eglantine) | 2094 | 497 | +687 | 4.2 | — | eglantine · djihads80 eglantine · djihad eglantine | VERY experimental Nintendo Switch 2 emulator |
| [pengchujin/aerial-tv](https://github.com/pengchujin/aerial-tv) | 8766 | 682 | +370 | 12.8 | — | aerial tv · pengchujin aerial tv | 给国产电视的一块干净桌面：参照 tvOS 设计的开源 Android TV 桌面，没有广告，开机自动接管。A tvOS-… |
| [rddmwmddr/android-ad-cleaner](https://github.com/rddmwmddr/android-ad-cleaner) | 5723 | 636 | +290 | 9 | — | android ad cleaner · rddmwmddr android ad cleaner | 关掉国产安卓手机系统里的广告、热搜、资讯推荐和营销推送。不 root，可还原，支持 AI 智能体一键执行。 |
| 🆕 [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | 627 | 627 | — | 1 | — | stack diagram · caru-ini stack diagram | Agent skill: describe your stack in a sentence, get an archi… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 90.2 | 🟢 窗口内 | [qybaihe/bla](https://github.com/qybaihe/bla) | JavaScript | 1871 | +129 | +1842 | +29 | `·····▁▁▂▁█▅▃▂·` | 8 | — | — |
| 2 | 90 | 🟢 窗口内 | [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) | TypeScript | 1806 | +65 | +1805 | +1 | `·▁·····██▃▂▂▂·` | 11 | — | — |
| 3 | 88.8 | 🟢 窗口内 | [SoMarkAI/OXR](https://github.com/SoMarkAI/OXR) | Python | 2867 | +84 | +1632 | +1235 | `▁▂▂▂▃▃▅█▄▄▂▂▂·` | 28 | [3](https://news.ycombinator.com/item?id=50183506) | — |
| 4 | 85.3 | 🟢 窗口内 | [daveebbelaar/bama](https://github.com/daveebbelaar/bama) | Swift | 1344 | +220 | +1223 | +121 | `······▄██▆▅▅▇·` | 8 | — | — |
| 5 | 84.2 | 🟢 窗口内 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 1129 | +407 | +1117 | +12 | `·····▁▁▂▁▂▄█▇·` | 6 | [2](https://news.ycombinator.com/item?id=50272846) | — |
| 6 | 82.5 | 🟢 窗口内 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | Rust | 1876 | +52 | +970 | +889 | `▃▁▁▁▂▃▆█▂▁▂▁▂·` | 13 | — | — |
| 7 | 66.9 | 🟡 在降温 | [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | TypeScript | 1672 | +72 | +806 | +866 | `·····▂█▄▃▂▁▁▂·` | 7 | — | — |
| 8 | 64.6 | 🟡 在降温 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 1460 | +53 | +638 | +822 | `·····█▄▄▂▂▂▂▂·` | 7 | — | — |
| 9 | 64.2 | 🟡 在降温 | [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) | Kotlin | 1384 | +93 | +615 | +769 | `··▁▄█▇▄▅▄▃▃▃▃·` | 11 | — | — |
| 10 | 60.3 | 🟡 在降温 | [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) | Python | 1654 | +26 | +415 | +1239 | `····▅█▅▂▁▂▂▂▁·` | 10 | — | — |
| 11 | 59.4 | 🟡 在降温 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2440 | +46 | +378 | +2062 | `·▁▁█▅▂▂▂▁▁▁▁▁·` | 11 | [3](https://news.ycombinator.com/item?id=50207695) | — |
| 12 | 58.2 | 🟡 在降温 | [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) | Python | 1790 | +58 | +336 | +852 | `▅▃▂█▆▆▃▃▂▂▃▃▃·` | 16 | [1](https://news.ycombinator.com/item?id=50177079) | — |
| 13 | 56 | 🟡 在降温 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 2025 | +75 | +270 | +740 | `█▇▇▄▃▄▄▄▃▂▂▂▄·` | 14 | — | — |
| 14 | 53.3 | 🟡 在降温 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 2248 | +32 | +205 | +360 | `█▇▅▅▄█▇▆▅▅▄▃▄·` | 22 | — | — |
| 15 | 52.8 | 🟡 在降温 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 2026 | +22 | +195 | +702 | `█▃▂▂▁▁▂▂▂▂▁▁▁·` | 20 | — | — |
| 16 | 39.7 | 🆕 🔴 先核对 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) | TypeScript | 747 | — | +747 | +0 | `···········▁█·` | 5 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 37.6 | 🆕 🔴 先核对 | [Centiplatrap/pc-game-fps-doctor](https://github.com/Centiplatrap/pc-game-fps-doctor) | JavaScript | 528 | — | +528 | +0 | `···········▃█·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 35.6 | 🔴 先核对 | [Balanov/svoi](https://github.com/Balanov/svoi) | JavaScript | 377 | +0 | +377 | +0 | `···········█··` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 34.1 | 🔴 先核对 | [t3dotgg/tstack](https://github.com/t3dotgg/tstack) | Python | 2595 | +50 | +910 | +1685 | `···▁▁▁█▃▂▂▁▁▁·` | 9 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 19.9 | 🔴 先核对 | [mizorewww/gdirect](https://github.com/mizorewww/gdirect) | Rust | 780 | +2 | +52 | +728 | `····▁█▂▁▁▁▁▁▁·` | 7 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 573 | 30 | 48716 | [SoMarkAI/OXR](https://github.com/SoMarkAI/OXR)、[t3dotgg/tstack](https://github.com/t3dotgg/tstack)、[jiwoochris/artex-global](https://github.com/jiwoochris/artex-global) |
| `mcp` | 307 | 30 | 34229 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[qybaihe/bla](https://github.com/qybaihe/bla)、[yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) |
| `rust` | 230 | 30 | 30753 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[academa-labs/manimgx](https://github.com/academa-labs/manimgx)、[opengeos/RustGIS](https://github.com/opengeos/RustGIS) |
| `local-first` | 81 | 30 | 11796 | [thtbee/nectarlink](https://github.com/thtbee/nectarlink)、[chenxiachan/textfold](https://github.com/chenxiachan/textfold)、[modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 21 | 25995 | [Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) |
| `ai-agents` | 21 | 19393 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering) |
| `codex` | 16 | 16429 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[shinshin86/mesh-avatar-studio](https://github.com/shinshin86/mesh-avatar-studio)、[UnderleveledBuilder/awesome-short-drama-skills](https://github.com/UnderleveledBuilder/awesome-short-drama-skills) |
| `agent-skills` | 14 | 18162 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) |
| `llm` | 13 | 10628 | [jiwoochris/artex-global](https://github.com/jiwoochris/artex-global)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[hanzohanzhe/Grandet](https://github.com/hanzohanzhe/Grandet) |
| `mcp-server` | 12 | 13521 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[qybaihe/bla](https://github.com/qybaihe/bla)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `ai-agent` | 9 | 8602 | [jiwoochris/artex-global](https://github.com/jiwoochris/artex-global)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `windows` | 9 | 6707 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[thtbee/nectarlink](https://github.com/thtbee/nectarlink)、[LingCore/WinShun](https://github.com/LingCore/WinShun) |
| `self-hosted` | 7 | 6403 | [marclou/mailcheap](https://github.com/marclou/mailcheap)、[rociiu/talorys](https://github.com/rociiu/talorys)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) |
| `developer-tools` | 7 | 6390 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai)、[hanzohanzhe/Grandet](https://github.com/hanzohanzhe/Grandet) |
| `open-source` | 7 | 4668 | [alexgaoth/awesome-reverse-engineered](https://github.com/alexgaoth/awesome-reverse-engineered)、[chenxiachan/textfold](https://github.com/chenxiachan/textfold)、[FortoGraphy/prism-download-manager](https://github.com/FortoGraphy/prism-download-manager) |
| `typescript` | 7 | 4446 | [pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust)、[rociiu/talorys](https://github.com/rociiu/talorys)、[SouravBeraAkaSpeed/xiryn](https://github.com/SouravBeraAkaSpeed/xiryn) |

**语言分布**：Rust 30 · Python 24 · TypeScript 16 · JavaScript 15 · Go 5 · HTML 3 · Swift 2 · Astro 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [qybaihe/bla](https://github.com/qybaihe/bla) · 🟢 窗口内 · 90.2 分

> 🛡️ BLA (Blind LLM Agents) — Adversarial defense shield that protects binaries, Electron apps, JS bundles, Python, and WebAssembly against AI reverse-engineering agents like REA. Poison -> Exhaust -> Hallucinate.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1871 | +1842 | +29 | 260 | 7 | JavaScript | MIT | 10-25（8 天前） | 今天 |

- **近 14 天每天新增**：`·····▁▁▂▁█▅▃▂·` 0 0 0 0 0 2 27 143 31 818 488 238 124 0
- **势头**：比前 7 天快 63.5 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adversarial-ai` `claude-code` `cursor` `electron-security` `llm-security` `mcp` `mcp-server` `obfuscation` `reverse-engineering` `webassembly`
- **主页**：<https://bla.tools>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) · 🟢 窗口内 · 90 分

> An Open Source template for a proactive AI agent that gets your work done and keeps you in the loop.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1806 | +1805 | +1 | 228 | 11 | TypeScript | MIT | 10-21（11 天前） | 1 天前 |

- **近 14 天每天新增**：`·▁·····██▃▂▂▂·` 0 1 0 0 0 0 0 702 690 172 105 71 65 0
- **势头**：比前 7 天快 1805.0 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<copilotkit.ai/openduet>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [SoMarkAI/OXR](https://github.com/SoMarkAI/OXR) · 🟢 窗口内 · 88.8 分

> An open-source document parsing model with SOTA accuracy and speed, using an RSI loop during post-training.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2867 | +1632 | +1235 | 215 | 22 | Python | — | 10-05（28 天前） | 8 天前 |

- **近 14 天每天新增**：`▁▂▂▂▃▃▅█▄▄▂▂▂·` 24 101 129 131 218 181 451 731 308 290 134 87 82 0
- **势头**：比前 7 天快 1.3 倍，在加速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=50183506)）
- **topics**：`agent` `llm-tools` `ocr` `oxr` `rsi` `vlm` `vlm-ocr`
- **主页**：<https://somark.ai/oxr>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [daveebbelaar/bama](https://github.com/daveebbelaar/bama) · 🟢 窗口内 · 85.3 分

> BAMA: Build Any Mac App. Agent skills to research, clone, design, build, optimize, and test native macOS apps with Swift and SwiftUI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1344 | +1223 | +121 | 173 | 5 | Swift | MIT | 10-24（8 天前） | 今天 |

- **近 14 天每天新增**：`······▄██▆▅▅▇·` 0 0 0 0 0 0 121 265 251 183 152 154 218 0
- **势头**：比前 7 天快 10.1 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-agents` `app-clone` `claude-code` `claude-code-plugin` `codex` `computer-use` `liquid-glass` `macos` `macos-app` `native-apps` `skills` `swift` `swiftdata` `swiftui`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) · 🟢 窗口内 · 84.2 分

> UEFI pre-driver NVIDIA GPU unlocker for Windows Linux Hackintosh and all EFI-bootable system (Rust): SEC2 scrubber -> FWSEC/WPR2 -> signed Booter -> V67 four-write payload, read-back verified. Verified on most RTX 20 30 40 Series.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1129 | +1117 | +12 | 101 | 28 | Rust | GPL-2.0 | 10-26（6 天前） | 今天 |

- **近 14 天每天新增**：`·····▁▁▂▁▂▄█▇·` 0 0 0 0 0 5 7 51 30 34 169 449 384 0
- **势头**：比前 7 天快 93.1 倍，在加速
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50272846)）
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [indexable-inc/blaze](https://github.com/indexable-inc/blaze) · 🟢 窗口内 · 82.5 分

> Incremental rust builds up to 92x faster than cargo/rustc

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1876 | +970 | +889 | 65 | 456 | Rust | Apache-2.0 | 10-19（13 天前） | 今天 |

- **近 14 天每天新增**：`▃▁▁▁▂▃▆█▂▁▂▁▂·` 151 14 5 4 104 156 455 672 126 37 54 29 52 0
- **势头**：比前 7 天快 1.1 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`cargo` `compiler` `cranelift` `developer-tools` `hot-reload` `incremental-compilation` `jit` `live-coding` `rust` `rust-analyzer`
- **主页**：<https://ix.dev/blaze>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) · 🟡 在降温 · 66.9 分

> AI digital-human talking-head videos from one photo: Renoise MCP generation + 5 editing styles + 48 creator-grade packaging components. Agent skill for Claude Code / Codex / OpenClaw / WorkBuddy …

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1672 | +806 | +866 | 381 | 4 | TypeScript | MIT | 10-26（7 天前） | 1 天前 |

- **近 14 天每天新增**：`·····▂█▄▃▂▁▁▂·` 0 0 0 0 0 88 778 299 190 154 53 36 74 0
- **势头**：只有前 7 天的 93%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) · 🟡 在降温 · 64.6 分

> Evidence-first genealogy skill for AI agents (Codex, Claude Code): church books, civil, military, deportation and repression records across the former USSR. Replies in your language.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1460 | +638 | +822 | 154 | 8 | Python | MIT | 10-25（7 天前） | 今天 |

- **近 14 天每天新增**：`·····█▄▄▂▂▂▂▂·` 0 0 0 0 0 593 229 255 113 88 72 61 49 0
- **势头**：只有前 7 天的 78%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `archives` `claude-code` `codex` `family-history` `familysearch` `genealogy` `ussr`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) · 🟡 在降温 · 64.2 分

> A community-built phone app for Clean Your TV: clean up an Android TV from your phone. No laptop, no coding agent, nothing uninstalled.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1384 | +615 | +769 | 118 | 3825 | Kotlin | MIT | 10-21（11 天前） | 1 天前 |

- **近 14 天每天新增**：`··▁▄█▇▄▅▄▃▃▃▃·` 0 0 1 103 288 244 133 150 114 89 79 97 86 0
- **势头**：只有前 7 天的 80%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adb` `android-tv` `debloat` `fire-tv` `google-tv` `launcher`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) · 🟡 在降温 · 60.3 分

> Agent Skills that teach coding agents to write, review, and port idiomatic Rust, plus a tested clippy config. Works with Claude Code, Codex, Copilot, Cursor, and Gemini CLI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1654 | +415 | +1239 | 86 | 4 | Python | MIT | 10-23（10 天前） | 2 天前 |

- **近 14 天每天新增**：`····▅█▅▂▁▂▂▂▁·` 0 0 0 0 302 581 356 89 41 60 118 78 29 0
- **势头**：只有前 7 天的 33%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `claude-code` `claude-plugin` `claude-skills` `clippy` `code-review` `coding-agent` `cursor` `rust` `style-guide`
- **主页**：<https://www.beautifulrust.dev>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) — 一天进了一半以上的 star，但 HN 上没火过
- [Centiplatrap/pc-game-fps-doctor](https://github.com/Centiplatrap/pc-game-fps-doctor) — 一天进了一半以上的 star，但 HN 上没火过
- [Balanov/svoi](https://github.com/Balanov/svoi) — 一天进了一半以上的 star，但 HN 上没火过
- [t3dotgg/tstack](https://github.com/t3dotgg/tstack) — 一天进了一半以上的 star，但 HN 上没火过
- [mizorewww/gdirect](https://github.com/mizorewww/gdirect) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 1136 | 207 | [Show HN: HackerBooks – HackerTube, but for books mentioned on HN](https://hackerbooks.org) | [HN](https://news.ycombinator.com/item?id=50326821) |
| 292 | 150 | [Show HN: A working Nintendo in ~1GB of Qwen weights](https://github.com/dbreunig/nesformer) | [HN](https://news.ycombinator.com/item?id=50306442) |
| 243 | 77 | [Show HN: To Honor Sir Patrick Stewart, Enjoy the TNG Episode Guessing Game](https://tng.episodle.com/) | [HN](https://news.ycombinator.com/item?id=50311686) |
| 196 | 46 | [Show HN: OmniDiff – Opensource, super fast, content aware Git difftool, in Rust](https://github.com/ivankovic/omnidiff) | [HN](https://news.ycombinator.com/item?id=50325253) |
| 194 | 51 | [Show HN: Marelleo, an open-source story box I built for my kids using ESP32](https://zebra.rodeo/en/blog/marelleo/) | [HN](https://news.ycombinator.com/item?id=50260753) |
| 178 | 41 | [Show HN: Point your camera at a landscape to learn about its geology](https://outcrop.rocks/) | [HN](https://news.ycombinator.com/item?id=50290533) |
| 177 | 43 | [Show HN: Hob - Open-source, on device alternative to Claude Cowork and ChatGPT](https://github.com/FrigadeHQ/hob) | [HN](https://news.ycombinator.com/item?id=50246238) |
| 154 | 132 | [Show HN: Auto Dismiss Mac OS "Allow <app> to find devices on local networks?"](https://github.com/johncassil/dontallow) | [HN](https://news.ycombinator.com/item?id=50294506) |
| 131 | 36 | [Show HN: I Turned DOOM into a Transformer](https://github.com/mottopanikeiku/doomformer) | [HN](https://news.ycombinator.com/item?id=50297697) |
| 98 | 6 | [Show HN: A language model that lives in a boot sector](https://github.com/kerlenton/bootgpt) | [HN](https://news.ycombinator.com/item?id=50315782) |
| 89 | 81 | [Show HN: NES Contra (1987) port (ASM –> C and then C –> WebAssembly)](https://epoyraz.github.io/nes-contra-us/) | [HN](https://news.ycombinator.com/item?id=50319169) |
| 85 | 43 | [Show HN: I built a multiplayer game where you're an aerial fighter cat](https://catcopter.com) | [HN](https://news.ycombinator.com/item?id=50305320) |
| 82 | 36 | [Show HN: SlideBySide – Present slides without sharing your screen](https://slidebyside.com/) | [HN](https://news.ycombinator.com/item?id=50276883) |
| 82 | 13 | [Show HN: I rebuilt my old canvas 3D library as a small WebGL 2 library – phoria2](https://kevs3d.co.uk/phoria2/) | [HN](https://news.ycombinator.com/item?id=50314508) |
| 82 | 13 | [Show HN: A proof-of-concept formalization of the IRS federal tax forms](https://github.com/emmilco/us-tax-model) | [HN](https://news.ycombinator.com/item?id=50278678) |
| 65 | 40 | [Show HN: Ghostman – A fast, keyboard-driven TUI API client and webhook inspector](https://github.com/4yk5/Ghostman) | [HN](https://news.ycombinator.com/item?id=50300902) |
| 60 | 42 | [Show HN: A USB-C LTE modem that gives my computer a phone line](https://github.com/Koppar-AI/koppar-lte-modem) | [HN](https://news.ycombinator.com/item?id=50317331) |
| 60 | 0 | [Show HN: Arsaze – Cursor for video editing (Tab-complete and agent edits)](https://www.arsaze.com) | [HN](https://news.ycombinator.com/item?id=50300618) |
| 53 | 21 | [Show HN: I rebuilt Kubernetes for ESP32 microcontrollers](https://github.com/arterialist/kube32) | [HN](https://news.ycombinator.com/item?id=50291812) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 8 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 3932★ |
| 162 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 119609★ |
| 63 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 45363★ |
| 85 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 21895★ |
| 103 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 30297★ |
| 32 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 8935★ |
| 110 | [FreeToken: Efficient Edge-Native MoE Serving with Bandwidth-Adaptive Execution](https://huggingface.co/papers/2608.16157) | FreeToken is an edge-native Mixture-of-Experts serving system that dynamically maps computation and model state onto heterogeneous local har… | [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken) 15490★ |
| 26 | [HairDeck: Animation-Ready Stylized Hair Cards from a Single Image](https://huggingface.co/papers/2610.40599) | HairDeck generates stylized hair cards and spring-bone animations as unordered token sets using a diffusion transformer, improving accuracy… | 💡 [hyz317/HairDeck](https://github.com/hyz317/HairDeck) 646★ |
| 39 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 35121★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 35122★ |
| 12 | [Xiaomi-OCR-0 Technical Report](https://huggingface.co/papers/2609.36136) | Xiaomi-OCR-0 is a compact vision-language model that unifies document parsing and OCR understanding through automated data synthesis, progre… | 💡 [SeerRay-Lab/Xiaomi-OCR-0](https://github.com/SeerRay-Lab/Xiaomi-OCR-0) 567★ |
| 13 | [Investor's Last Exam: Can AI Agents Do Equity Investment Without Seeing the Future?](https://huggingface.co/papers/2610.38342) | Investor's Last Exam evaluates financial agents on end-to-end equity research using frozen evidence, expert criteria, and dependency graphs,… | 💡 [Prophetlab/Investor-Last-Exam](https://github.com/Prophetlab/Investor-Last-Exam) 128★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 1 | [Differentiable Data Augmentation with Kornia](https://huggingface.co/papers/2011.09832) | This paper reviews the Kornia differentiable data augmentation module for both 2D and 3D tensors, integrating with PyTorch's autograd and op… | [arraiyopensource/kornia](https://github.com/arraiyopensource/kornia) 11763★ |
| 86 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 92429★ |
| 100 | [MOSS-Image Technical Report](https://huggingface.co/papers/2610.23374) | MOSS-Image is an open diffusion transformer that combines high-fidelity synthesis with intent-aware prompt enhancement to generate text-rich… | [OpenMOSS/MOSS-Image](https://github.com/OpenMOSS/MOSS-Image) 2436★ |
| 20 | [Intrinsic Distribution Matching](https://huggingface.co/papers/2610.39633) | Intrinsic Distribution Matching improves few-step text-to-image generation by adding explicit moment constraints to distribution matching di… | 💡 [inclusionAI/IDM](https://github.com/inclusionAI/IDM) 134★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 82942★ |
| 75 | [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://huggingface.co/papers/2504.19413) | Mem0, a memory-centric architecture with graph-based memory, enhances long-term conversational coherence in LLMs by efficiently extracting,… | [mem0ai/mem0](https://github.com/mem0ai/mem0) 68249★ |
| 103 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 2980★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 18 | [numbat](https://huggingface.co/burner22/numbat) | — | 225 | 1 |
| 27 | [deepseek v4.1 flash 1017 obliterated](https://huggingface.co/OBLITERATUS/DeepSeek-V4.1-Flash-1017-obliterated) | text-generation | 176 | 1 |
| 49 | [sulphur 3](https://huggingface.co/FusionCow/Sulphur-3) | — | 115 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 70 | 9 | [An outsider's perspective on Scion and Mononoke](https://typesanitizer.com/blog/scion.html) | `vcs` | [讨论](https://lobste.rs/s/s2qeww/outsider_s_perspective_on_scion_mononoke) |
| 26 | 10 | [Pratt parsing is a black box](https://vinipsmaker.github.io/blog/article/pratt-parsing-is-a-black-box/) | `compilers` `plt` | [讨论](https://lobste.rs/s/bzazar/pratt_parsing_is_black_box) |
| 106 | 32 | [Introducing Kwi, a new KDE terminal emulator](https://blogs.kde.org/2026/11/01/introducing-kwi/) | `linux` | [讨论](https://lobste.rs/s/lt44rt/introducing_kwi_new_kde_terminal) |
| 29 | 1 | [Work on GEFS (the Good Enough File System) for OpenBSD progresses](https://www.undeadly.org/cgi?action=article;sid=20261101115637) | `openbsd` | [讨论](https://lobste.rs/s/zjjvbo/work_on_gefs_good_enough_file_system_for) |
| 24 | 4 | [London Meetup - Nov 2026](https://lobste.rs/s/cqzwwg) | `event` | [讨论](https://lobste.rs/s/cqzwwg/london_meetup_nov_2026) |
| 146 | 39 | [Jepsen: ParticleDB 1.1.4](https://jepsen.io/analyses/particledb-1.1.4) | `databases` `testing` | [讨论](https://lobste.rs/s/drwd4j/jepsen_particledb_1_1_4) |
| 34 | 2 | [XKCD and Fourier](https://leancrew.com/all-this/2026/10/xkcd-and-fourier/) | `math` | [讨论](https://lobste.rs/s/mni8ri/xkcd_fourier) |
| 13 | 2 | [Introduction to Programming in ATS](https://ats-lang.sourceforge.net/DOCUMENT/INT2PROGINATS/HTML/book1.html) | `book` `plt` | [讨论](https://lobste.rs/s/oqj2zo/introduction_programming_ats) |
| 71 | 28 | [Mystery of 60-Second Fluctuations in Power Grids Solved](https://www.fz-juelich.de/en/news/archive/press-release/2026/mystery-of-60-second-fluctuations-in-power-grids-solved) | `science` | [讨论](https://lobste.rs/s/qwou15/mystery_60_second_fluctuations_power) |
| 3 | 1 | [Postgres 19 is late, and it's AI's fault](http://rhaas.blogspot.com/2026/10/postgres-19-is-late-and-its-ais-fault.html) | `databases` `practices` | [讨论](https://lobste.rs/s/0yxkvs/postgres_19_is_late_it_s_ai_s_fault) |
| 13 | 0 | [Zig: From Beginner to Slightly Less Beginner](https://www.youtube.com/watch?v=jWCQXBVIyrY) | `video` `zig` | [讨论](https://lobste.rs/s/uhlnqx/zig_from_beginner_slightly_less_beginner) |
| 90 | 20 | [Avoid Public Functions Calling Other Public Functions](https://matklad.github.io/2026/10/29/pub-calls-pub.html) | `api` `programming` | [讨论](https://lobste.rs/s/k508we/avoid_public_functions_calling_other) |
| 11 | 3 | [A Specialised Haskell Processor on FPGA](https://bathtub-01.github.io/technical/ouros-demo/) | `hardware` `haskell` | [讨论](https://lobste.rs/s/8o9wus/specialised_haskell_processor_on_fpga) |
| 54 | 34 | [The Kluever Maneuver](https://jordi.inversethought.com/blog/the-kluever-maneuver/) | `testing` | [讨论](https://lobste.rs/s/rpiu3w/kluever_maneuver) |
| 3 | 1 | [A400000 Winners](https://oeis.org/wiki/A400K_Winners) | `math` | [讨论](https://lobste.rs/s/reerrq/a400000_winners) |
| 15 | 0 | [groff/troff macros: ms, mm, me or mom](https://www.stephenlindholm.com/groff_macros.html) | `unix` | [讨论](https://lobste.rs/s/dbwbvr/groff_troff_macros_ms_mm_me_mom) |
| 7 | 1 | [Spooky C++](https://www.nablag.com/spooky_cpp) | `c++` | [讨论](https://lobste.rs/s/4yxx6f/spooky_c) |
| 9 | 5 | [Beating the compiler at signed 32-bit division](https://lemire.me/blog/2026/10/31/beating-the-compiler-at-signed-32-bit-division/) | `compilers` `performance` | [讨论](https://lobste.rs/s/ep5vsq/beating_compiler_at_signed_32_bit) |
| 4 | 0 | [Understanding Org's LaTeX previews](https://karthinks.com/software/understanding-org-latex-preview/) | `emacs` | [讨论](https://lobste.rs/s/yihs7m/understanding_org_s_latex_previews) |
| 2 | 0 | [The Beginning of BSD Unix](https://fosscomics.com/posts/13.%20BSD%20Unix%20Part%203%20-%20The%20Beginning%20of%20BSD%20Unix/) | `unix` | [讨论](https://lobste.rs/s/3nasb5/beginning_bsd_unix) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 74 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 19 | 13 | 68% | — |
| 🔴 先核对 | 15 | 8 | 53% | — |
| 🟡 在降温 | 5 | 0 | 0% | — |
| 🔵 已被发现 | 2 | 0 | 0% | — |
| 🟢 窗口内 | 9 | 5 | 55% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [Gathin23/tv-vibehack](https://github.com/Gathin23/tv-vibehack) | 2026-10-19 | 🚀 爆发 | 2325 | 49419 | 0 | ✅ 起来了 |
| [LiCinCan/blender-ai-mcp-addon](https://github.com/LiCinCan/blender-ai-mcp-addon) | 2026-10-19 | 🟢 窗口内 | 788 | 0 | 0 | 仓库没了 |
| [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | 2026-10-19 | 🚀 爆发 | 490 | 2025 | 0 | ✅ 起来了 |
| [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) | 2026-10-19 | 🔴 先核对 | 429 | 1790 | 1 | ✅ 起来了 |
| [ly05010419/MacNativeGames](https://github.com/ly05010419/MacNativeGames) | 2026-10-19 | 🚀 爆发 | 997 | 6802 | 0 | ✅ 起来了 |
| [obsidianmd/pele](https://github.com/obsidianmd/pele) | 2026-10-19 | 🚀 爆发 | 1972 | 4027 | 0 | ✅ 起来了 |
| [reason-machines/reason-network](https://github.com/reason-machines/reason-network) | 2026-10-19 | 🟢 窗口内 | 438 | 1442 | 0 | ✅ 起来了 |
| [xiaoyang111222/cn-math-taxonomy](https://github.com/xiaoyang111222/cn-math-taxonomy) | 2026-10-19 | 🚀 爆发 | 510 | 5983 | 0 | ✅ 起来了 |

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
