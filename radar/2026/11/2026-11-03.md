# early-radar 选题雷达 · 2026-11-03

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 101 个，细查前 20 个 · 比上次 = 和 2026-11-02 那次比 · 生成于 2026-11-03 06:15 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 1 个 · Show HN ✅ 25 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 4 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 5 个 · 🟡 在降温 10 个 · 🔵 已被发现 0 个 · 💤 不活跃 0 个 · 🔴 先核对 5 个
- **今天新出现 2 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) 平均每天 +5012，见 [爆发](#爆发)
- **复盘**：🚀 爆发 15/21 · 🔴 先核对 8/16 · 🟡 在降温 0/5 · 🔵 已被发现 0/2 · 🟢 窗口内 6/10（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [qybaihe/bla](https://github.com/qybaihe/bla) — 🛡️ BLA (Blind LLM Agents) — Adversarial defense shield that…（近 7 天 +1835，比前 7 天快 10.7 倍，在加速）
  - [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) — UEFI pre-driver NVIDIA GPU unlocker for Windows Linux Hackin…（近 7 天 +1398，比前 7 天快 22.2 倍，在加速）
  - [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) — An Open Source template for a proactive AI agent that gets y…（近 7 天 +1167，比前 7 天快 1.7 倍，在加速）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 21 个（star 合计 27858），代表：[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：4 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: HackerBooks – HackerTube, but for books mentioned on HN](https://hackerbooks.org) — 1818 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) | 14349 | 5012 | +5054 | 2.9 | [11](https://news.ycombinator.com/item?id=50316116) | dsh superagent prototype · deepseek-ai dsh superagent prototype · deepseek dsh superagent prototype | Towards a More Autonomous Agent System |
| ✅ [storytold/craft-anything](https://github.com/storytold/craft-anything) | 5127 | 1940 | +3557 | 2.6 | — | craft anything · storytold craft anything · artcraft craft anything | Craft Anything: understand how any software works, and craft… |
| [heydamir/unslop](https://github.com/heydamir/unslop) | 6540 | 1420 | +1454 | 4.6 | — | unslop · heydamir unslop · damir unslop | A Claude skill that turns vibecoded, AI-looking UI into a de… |
| [wangzan101/Mika](https://github.com/wangzan101/Mika) | 5606 | 1205 | +1309 | 4.7 | — | mika · wangzan101 mika · wangzan mika | An on-device AI agent for Android that operates apps and the… |
| [l0ng-ai/openidea](https://github.com/l0ng-ai/openidea) | 5212 | 409 | +1247 | 12.7 | [41](https://news.ycombinator.com/item?id=50323848) | openidea · l0ng-ai openidea | The IDE you know, rebuilt in Rust. IntelliJ IDEA–style keyma… |
| [ccch1mneyyy/dsh-Go](https://github.com/ccch1mneyyy/dsh-Go) | 6239 | 699 | +1237 | 8.9 | — | dsh go · ccch1mneyyy dsh go · chimney dsh go | dsh-go — DeepSeek Harness 装进口袋：手机本机运行，也能遥控你的电脑。 |
| [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) | 1752 | 254 | +1005 | 6.9 | — | anymodelbot · modelflare-ai anymodelbot · modelflare anymodelbot | 🤖 Open-source, local-first alternative to Grok Bot, OpenAI d… |
| [patch-gg/pixelfx](https://github.com/patch-gg/pixelfx) | 3666 | 921 | +799 | 4 | — | pixelfx · patch-gg pixelfx · patch pixelfx | 244 pixel art effects, every one a small piece of code. Plus… |
| [valentderah/totk-pc-recomp](https://github.com/valentderah/totk-pc-recomp) | 4139 | 874 | +803 | 4.7 | — | totk pc recomp · valentderah totk pc recomp · valiantsin totk pc recomp | Static recompilation of The Legend of Zelda: Tears of the Ki… |
| [anhao/ai-pose-gallery-zh](https://github.com/anhao/ai-pose-gallery-zh) | 5583 | 828 | +336 | 6.7 | — | ai pose gallery zh · anhao ai pose gallery zh | 中文版 AI 姿势参考图库 · 1439 组 / 2878 张图片 / 完整汉化 · 零依赖静态画廊 |
| [unclebob/ub-mode](https://github.com/unclebob/ub-mode) | 6622 | 771 | +293 | 8.6 | — | ub mode · unclebob ub mode · robert ub mode |  |
| 🆕 [BryceYuuu/RUN](https://github.com/BryceYuuu/RUN) | 1985 | 415 | +671 | 4.8 | — | run · bryceyuuu run · bryce run | RUN · 润：海外移居手册（欧洲 36 国 · 110 条路线 · 主要移民地区） |
| [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | 1292 | 637 | +665 | 2 | — | stack diagram · caru-ini stack diagram | Agent skill: describe your stack in a sentence, get an archi… |
| [pengchujin/aerial-tv](https://github.com/pengchujin/aerial-tv) | 9118 | 657 | +352 | 13.9 | — | aerial tv · pengchujin aerial tv | 给国产电视的一块干净桌面：参照 tvOS 设计的开源 Android TV 桌面，没有广告，开机自动接管。A tvOS-… |
| 🆕 [Verlintas/NOIR](https://github.com/Verlintas/NOIR) | 1487 | 630 | — | 2.4 | — | noir · verlintas noir | 手机隐私审计：用 adb 扫出 Android 应用的权限、上报端点与数据流向，并给出可回滚的处置。Desktop An… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 90.2 | 🟢 窗口内 | [qybaihe/bla](https://github.com/qybaihe/bla) | TypeScript | 2007 | +136 | +1835 | +172 | `····▁▁▂▁█▅▃▂▂·` | 9 | — | — |
| 2 | 86.9 | 🟢 窗口内 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 1461 | +332 | +1398 | +63 | `····▁▁▂▁▂▄██▆·` | 7 | [2](https://news.ycombinator.com/item?id=50272846) | — |
| 3 | 84.8 | 🟢 窗口内 | [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) | TypeScript | 1869 | +63 | +1167 | +702 | `▁·····██▃▂▂▂▂·` | 12 | — | — |
| 4 | 83.7 | 🟢 窗口内 | [daveebbelaar/bama](https://github.com/daveebbelaar/bama) | Swift | 1459 | +115 | +1073 | +386 | `·····▄██▆▅▅▇▄·` | 9 | — | — |
| 5 | 80.4 | 🆕 🟢 窗口内 | [emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) | Rust | 909 | +251 | +810 | +99 | `·····▂▂▂▂▁▂█▄·` | 8 | — | — |
| 6 | 63.5 | 🟡 在降温 | [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | TypeScript | 1739 | +67 | +574 | +1165 | `····▂█▄▃▂▁▁▂▁·` | 8 | — | — |
| 7 | 63.4 | 🟡 在降温 | [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) | Kotlin | 1482 | +98 | +563 | +919 | `·▁▄█▇▄▅▄▃▃▃▃▃·` | 12 | — | — |
| 8 | 60.9 | 🟡 在降温 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 1520 | +60 | +442 | +1077 | `····█▄▄▂▂▂▂▂▂·` | 8 | — | — |
| 9 | 58.9 | 🟡 在降温 | [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) | Python | 1688 | +34 | +359 | +1329 | `···▅█▅▂▁▂▂▂▁▁·` | 11 | — | — |
| 10 | 58.5 | 🟡 在降温 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | Rust | 1923 | +47 | +345 | +1410 | `▁▁▁▂▃▆█▂▁▂▁▂▁·` | 14 | [3](https://news.ycombinator.com/item?id=50340534) | — |
| 11 | 58 | 🟡 在降温 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 2156 | +131 | +328 | +643 | `▇█▅▃▅▄▄▃▃▂▂▄▇·` | 15 | — | — |
| 12 | 57.7 | 🟡 在降温 | [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) | Python | 1829 | +39 | +319 | +783 | `▃▂█▆▆▃▃▂▂▃▃▃▂·` | 17 | [1](https://news.ycombinator.com/item?id=50177079) | — |
| 13 | 55.7 | 🟡 在降温 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2466 | +26 | +261 | +2205 | `▁▁█▅▂▂▂▁▁▁▁▁▁·` | 12 | [3](https://news.ycombinator.com/item?id=50207695) | — |
| 14 | 51.9 | 🟡 在降温 | [opengeos/RustGIS](https://github.com/opengeos/RustGIS) | Rust | 2271 | +23 | +178 | +342 | `█▅▅▄█▇▆▅▅▄▃▅▃·` | 23 | — | — |
| 15 | 51.1 | 🟡 在降温 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Python | 2052 | +26 | +165 | +350 | `█▇▄▂▃▄▅▄▄▂▃▃▃·` | 21 | — | — |
| 16 | 44.8 | 🔴 先核对 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) | TypeScript | 1752 | +1005 | +1752 | +0 | `··········▁██·` | 6 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 43 | 🔴 先核对 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | TypeScript | 1292 | +665 | +1292 | +0 | `···········█▆·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 38.5 | 🔴 先核对 | [Centiplatrap/pc-game-fps-doctor](https://github.com/Centiplatrap/pc-game-fps-doctor) | JavaScript | 608 | +80 | +608 | +0 | `··········▃█▂·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 35.3 | 🆕 🔴 先核对 | [Balanov/shim](https://github.com/Balanov/shim) | Go | 358 | — | +358 | +0 | `············█·` | 1 | [29](https://news.ycombinator.com/item?id=21744910) | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 31.7 | 🔴 先核对 | [t3dotgg/tstack](https://github.com/t3dotgg/tstack) | Python | 2645 | +50 | +563 | +2082 | `··▁▁▁█▃▂▂▁▁▁▁·` | 10 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 577 | 30 | 47019 | [t3dotgg/tstack](https://github.com/t3dotgg/tstack)、[academa-labs/manimgx](https://github.com/academa-labs/manimgx)、[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill) |
| `mcp` | 310 | 30 | 35518 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[qybaihe/bla](https://github.com/qybaihe/bla)、[cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) |
| `rust` | 235 | 30 | 33386 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx)、[xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[opengeos/RustGIS](https://github.com/opengeos/RustGIS) |
| `local-first` | 84 | 30 | 14302 | [thtbee/nectarlink](https://github.com/thtbee/nectarlink)、[modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 21 | 27858 | [Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `ai-agents` | 21 | 20479 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `codex` | 16 | 18205 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[shinshin86/mesh-avatar-studio](https://github.com/shinshin86/mesh-avatar-studio)、[UnderleveledBuilder/awesome-short-drama-skills](https://github.com/UnderleveledBuilder/awesome-short-drama-skills) |
| `agent-skills` | 15 | 20311 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) |
| `llm` | 12 | 9503 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot)、[trhhubsd/ARTEX](https://github.com/trhhubsd/ARTEX)、[hanzohanzhe/Grandet](https://github.com/hanzohanzhe/Grandet) |
| `mcp-server` | 11 | 13555 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[qybaihe/bla](https://github.com/qybaihe/bla)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `windows` | 8 | 7443 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[thtbee/nectarlink](https://github.com/thtbee/nectarlink)、[LingCore/WinShun](https://github.com/LingCore/WinShun) |
| `ai-agent` | 8 | 7150 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot)、[hujjun/mcd-saver-strategist](https://github.com/hujjun/mcd-saver-strategist)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `claude-skills` | 7 | 10831 | [Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) |
| `self-hosted` | 7 | 6932 | [marclou/mailcheap](https://github.com/marclou/mailcheap)、[rociiu/talorys](https://github.com/rociiu/talorys)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) |
| `developer-tools` | 7 | 6485 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai)、[hanzohanzhe/Grandet](https://github.com/hanzohanzhe/Grandet) |
| `open-source` | 7 | 4880 | [alexgaoth/awesome-reverse-engineered](https://github.com/alexgaoth/awesome-reverse-engineered)、[chenxiachan/textfold](https://github.com/chenxiachan/textfold)、[FortoGraphy/prism-download-manager](https://github.com/FortoGraphy/prism-download-manager) |

**语言分布**：Rust 32 · Python 21 · TypeScript 17 · JavaScript 14 · Go 6 · HTML 3 · Swift 2 · Astro 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [qybaihe/bla](https://github.com/qybaihe/bla) · 🟢 窗口内 · 90.2 分

> 🛡️ BLA (Blind LLM Agents) — Adversarial defense shield that protects binaries, Electron apps, JS bundles, Python, and WebAssembly against AI reverse-engineering agents like REA. Poison -> Exhaust -> Hallucinate.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2007 | +1835 | +172 | 273 | 19 | TypeScript | MIT | 10-25（9 天前） | 今天 |

- **近 14 天每天新增**：`····▁▁▂▁█▅▃▂▂·` 0 0 0 0 2 27 143 31 817 488 238 145 116 0
- **势头**：比前 7 天快 10.7 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adversarial-ai` `claude-code` `cursor` `electron-security` `llm-security` `mcp` `mcp-server` `obfuscation` `reverse-engineering` `webassembly`
- **主页**：<https://bla.tools>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) · 🟢 窗口内 · 86.9 分

> UEFI pre-driver NVIDIA GPU unlocker for Windows Linux Hackintosh and all EFI-bootable system (Rust): SEC2 scrubber -> FWSEC/WPR2 -> signed Booter -> V67 four-write payload, read-back verified. Verified on most RTX 20 30 40 Series.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1461 | +1398 | +63 | 126 | 38 | Rust | GPL-2.0 | 10-26（7 天前） | 今天 |

- **近 14 天每天新增**：`····▁▁▂▁▂▄██▆·` 0 0 0 0 5 7 51 30 34 169 449 421 295 0
- **势头**：比前 7 天快 22.2 倍，在加速
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50272846)）
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) · 🟢 窗口内 · 84.8 分

> An Open Source template for a proactive AI agent that gets your work done and keeps you in the loop.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1869 | +1167 | +702 | 235 | 12 | TypeScript | MIT | 10-21（12 天前） | 今天 |

- **近 14 天每天新增**：`▁·····██▃▂▂▂▂·` 1 0 0 0 0 0 701 690 172 105 71 73 56 0
- **势头**：比前 7 天快 1.7 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<copilotkit.ai/openduet>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [daveebbelaar/bama](https://github.com/daveebbelaar/bama) · 🟢 窗口内 · 83.7 分

> BAMA: Build Any Mac App. Agent skills to research, clone, design, build, optimize, and test native macOS apps with Swift and SwiftUI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1459 | +1073 | +386 | 182 | 5 | Swift | MIT | 10-24（9 天前） | 1 天前 |

- **近 14 天每天新增**：`·····▄██▆▅▅▇▄·` 0 0 0 0 0 121 265 251 183 152 154 228 105 0
- **势头**：比前 7 天快 2.8 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-agents` `app-clone` `claude-code` `claude-code-plugin` `codex` `computer-use` `liquid-glass` `macos` `macos-app` `native-apps` `skills` `swift` `swiftdata` `swiftui`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. 🆕 [emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) · 🟢 窗口内 · 80.4 分

> Self-hosted, sharable kanban for humans and agents. One 4.5 MB binary, 4.5 MB of RAM, 10 to 60 tokens per agent reply, starts in 2 ms, zero setup.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 909 | +810 | +99 | 57 | 1 | Rust | AGPL-3.0 | 10-25（8 天前） | 今天 |

- **近 14 天每天新增**：`·····▂▂▂▂▁▂█▄·` 0 0 0 0 0 38 61 34 54 11 48 443 220 0
- **势头**：比前 7 天快 8.2 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `claude-code` `cli` `codex` `coding-agents` `kanban` `local-first` `mcp` `mcp-server` `model-context-protocol` `productivity` `project-management` `raspberry-pi` `rust` `self-hosted` `sqlite` `task-manager`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) · 🟡 在降温 · 63.5 分

> AI digital-human talking-head videos from one photo: Renoise MCP generation + 5 editing styles + 48 creator-grade packaging components. Agent skill for Claude Code / Codex / OpenClaw / WorkBuddy …

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1739 | +574 | +1165 | 398 | 4 | TypeScript | MIT | 10-26（8 天前） | 2 天前 |

- **近 14 天每天新增**：`····▂█▄▃▂▁▁▂▁·` 0 0 0 0 88 778 299 190 154 53 36 86 55 0
- **势头**：只有前 7 天的 49%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 7. [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) · 🟡 在降温 · 63.4 分

> A community-built phone app for Clean Your TV: clean up an Android TV from your phone. No laptop, no coding agent, nothing uninstalled.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1482 | +563 | +919 | 129 | 4360 | Kotlin | MIT | 10-21（12 天前） | 2 天前 |

- **近 14 天每天新增**：`·▁▄█▇▄▅▄▃▃▃▃▃·` 0 1 103 288 244 133 150 114 89 79 96 92 93 0
- **势头**：只有前 7 天的 61%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adb` `android-tv` `debloat` `fire-tv` `google-tv` `launcher`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) · 🟡 在降温 · 60.9 分

> Evidence-first genealogy skill for AI agents (Codex, Claude Code): church books, civil, military, deportation and repression records across the former USSR. Replies in your language.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1520 | +442 | +1077 | 163 | 1 | Python | MIT | 10-25（8 天前） | 今天 |

- **近 14 天每天新增**：`····█▄▄▂▂▂▂▂▂·` 0 0 0 0 593 229 255 113 88 71 61 54 55 0
- **势头**：只有前 7 天的 41%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `archives` `claude-code` `codex` `family-history` `familysearch` `genealogy` `ussr`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) · 🟡 在降温 · 58.9 分

> Agent Skills that teach coding agents to write, review, and port idiomatic Rust, plus a tested clippy config. Works with Claude Code, Codex, Copilot, Cursor, and Gemini CLI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1688 | +359 | +1329 | 87 | 4 | Python | MIT | 10-23（11 天前） | 今天 |

- **近 14 天每天新增**：`···▅█▅▂▁▂▂▂▁▁·` 0 0 0 303 581 356 89 41 60 118 78 41 21 0
- **势头**：只有前 7 天的 27%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `claude-code` `claude-plugin` `claude-skills` `clippy` `code-review` `coding-agent` `cursor` `rust` `style-guide`
- **主页**：<https://www.beautifulrust.dev>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [indexable-inc/blaze](https://github.com/indexable-inc/blaze) · 🟡 在降温 · 58.5 分

> Incremental rust builds up to 92x faster than cargo/rustc

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1923 | +345 | +1410 | 69 | 481 | Rust | Apache-2.0 | 10-19（14 天前） | 今天 |

- **近 14 天每天新增**：`▁▁▁▂▃▆█▂▁▂▁▂▁·` 14 5 4 104 156 455 672 126 37 53 29 55 45 0
- **势头**：只有前 7 天的 24%，在减速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=50340534)）
- **topics**：`cargo` `compiler` `cranelift` `developer-tools` `hot-reload` `incremental-compilation` `jit` `live-coding` `rust` `rust-analyzer`
- **主页**：<https://ix.dev/blaze>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) — 一天进了一半以上的 star，但 HN 上没火过
- [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) — 一天进了一半以上的 star，但 HN 上没火过
- [Centiplatrap/pc-game-fps-doctor](https://github.com/Centiplatrap/pc-game-fps-doctor) — 一天进了一半以上的 star，但 HN 上没火过
- [Balanov/shim](https://github.com/Balanov/shim) — 一天进了一半以上的 star，但 HN 上没火过
- [t3dotgg/tstack](https://github.com/t3dotgg/tstack) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 1818 | 300 | [Show HN: HackerBooks – HackerTube, but for books mentioned on HN](https://hackerbooks.org) | [HN](https://news.ycombinator.com/item?id=50326821) |
| 629 | 324 | [Show HN: Subvocal – Talk to your computer without making noise](https://news.ycombinator.com/item?id=50340088) | [HN](https://news.ycombinator.com/item?id=50340088) |
| 334 | 103 | [Show HN: Wikihack – HackerTube, but for Wikipedia articles mentioned on HN](https://wikihack.netlify.app) | [HN](https://news.ycombinator.com/item?id=50333339) |
| 313 | 94 | [Show HN: OmniDiff – Opensource, super fast, content aware Git difftool, in Rust](https://github.com/ivankovic/omnidiff) | [HN](https://news.ycombinator.com/item?id=50325253) |
| 295 | 153 | [Show HN: A working Nintendo in ~1GB of Qwen weights](https://github.com/dbreunig/nesformer) | [HN](https://news.ycombinator.com/item?id=50306442) |
| 257 | 54 | [Show HN: Point your camera at a landscape to learn about its geology](https://outcrop.rocks/) | [HN](https://news.ycombinator.com/item?id=50290533) |
| 244 | 80 | [Show HN: To Honor Sir Patrick Stewart, Enjoy the TNG Episode Guessing Game](https://tng.episodle.com/) | [HN](https://news.ycombinator.com/item?id=50311686) |
| 237 | 38 | [Show HN: Warsaw in voxels – An interactive 3D map of the city centre](https://p.migdal.pl/warsaw-vibe-voxel/) | [HN](https://news.ycombinator.com/item?id=50339221) |
| 217 | 52 | [Show HN: I've updated my Linux System Call website and API](https://syscall.sh/) | [HN](https://news.ycombinator.com/item?id=50334704) |
| 194 | 52 | [Show HN: Marelleo, an open-source story box I built for my kids using ESP32](https://zebra.rodeo/en/blog/marelleo/) | [HN](https://news.ycombinator.com/item?id=50260753) |
| 182 | 25 | [Show HN: HackerHack – HackerBooks but for Posts Posted on HN](https://news.ycombinator.com/) | [HN](https://news.ycombinator.com/item?id=50333877) |
| 154 | 133 | [Show HN: Auto Dismiss Mac OS "Allow <app> to find devices on local networks?"](https://github.com/johncassil/dontallow) | [HN](https://news.ycombinator.com/item?id=50294506) |
| 154 | 50 | [Show HN: Hacker Times, a New York Times-inspired version of Hacker News](https://hackertimes.ca/) | [HN](https://news.ycombinator.com/item?id=50346981) |
| 132 | 36 | [Show HN: I Turned DOOM into a Transformer](https://github.com/mottopanikeiku/doomformer) | [HN](https://news.ycombinator.com/item?id=50297697) |
| 105 | 6 | [Show HN: A language model that lives in a boot sector](https://github.com/kerlenton/bootgpt) | [HN](https://news.ycombinator.com/item?id=50315782) |
| 101 | 29 | [Show HN: I rebuilt my old canvas 3D library as a small WebGL 2 library – phoria2](https://kevs3d.co.uk/phoria2/) | [HN](https://news.ycombinator.com/item?id=50314508) |
| 90 | 80 | [Show HN: NES Contra (1987) port (ASM –> C and then C –> WebAssembly)](https://epoyraz.github.io/nes-contra-us/) | [HN](https://news.ycombinator.com/item?id=50319169) |
| 85 | 43 | [Show HN: I built a multiplayer game where you're an aerial fighter cat](https://catcopter.com) | [HN](https://news.ycombinator.com/item?id=50305320) |
| 84 | 13 | [Show HN: A proof-of-concept formalization of the IRS federal tax forms](https://github.com/emmilco/us-tax-model) | [HN](https://news.ycombinator.com/item?id=50278678) |
| 83 | 36 | [Show HN: SlideBySide – Present slides without sharing your screen](https://slidebyside.com/) | [HN](https://news.ycombinator.com/item?id=50276883) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 9 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 4490★ |
| 162 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 120025★ |
| 63 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 46020★ |
| 111 | [FreeToken: Efficient Edge-Native MoE Serving with Bandwidth-Adaptive Execution](https://huggingface.co/papers/2608.16157) | FreeToken is an edge-native Mixture-of-Experts serving system that dynamically maps computation and model state onto heterogeneous local har… | [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken) 16154★ |
| 86 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 22110★ |
| 103 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 30408★ |
| 1 | [Differentiable Data Augmentation with Kornia](https://huggingface.co/papers/2011.09832) | This paper reviews the Kornia differentiable data augmentation module for both 2D and 3D tensors, integrating with PyTorch's autograd and op… | [arraiyopensource/kornia](https://github.com/arraiyopensource/kornia) 12116★ |
| 33 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 8955★ |
| 41 | [HairDeck: Animation-Ready Stylized Hair Cards from a Single Image](https://huggingface.co/papers/2610.40599) | HairDeck generates stylized hair cards and spring-bone animations as unordered token sets using a diffusion transformer, improving accuracy… | 💡 [hyz317/HairDeck](https://github.com/hyz317/HairDeck) 750★ |
| 13 | [Xiaomi-OCR-0 Technical Report](https://huggingface.co/papers/2609.36136) | Xiaomi-OCR-0 is a compact vision-language model that unifies document parsing and OCR understanding through automated data synthesis, progre… | 💡 [SeerRay-Lab/Xiaomi-OCR-0](https://github.com/SeerRay-Lab/Xiaomi-OCR-0) 766★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 35223★ |
| 39 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 35258★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 86 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 92511★ |
| 100 | [MOSS-Image Technical Report](https://huggingface.co/papers/2610.23374) | MOSS-Image is an open diffusion transformer that combines high-fidelity synthesis with intent-aware prompt enhancement to generate text-rich… | [OpenMOSS/MOSS-Image](https://github.com/OpenMOSS/MOSS-Image) 2512★ |
| 37 | [Intrinsic Distribution Matching](https://huggingface.co/papers/2610.39633) | Intrinsic Distribution Matching improves few-step text-to-image generation by adding explicit moment constraints to distribution matching di… | 💡 [inclusionAI/IDM](https://github.com/inclusionAI/IDM) 211★ |
| 107 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 3056★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 83011★ |
| 14 | [Investor's Last Exam: Can AI Agents Do Equity Investment Without Seeing the Future?](https://huggingface.co/papers/2610.38342) | Investor's Last Exam evaluates financial agents on end-to-end equity research using frozen evidence, expert criteria, and dependency graphs,… | 💡 [Prophetlab/Investor-Last-Exam](https://github.com/Prophetlab/Investor-Last-Exam) 136★ |
| 75 | [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://huggingface.co/papers/2504.19413) | Mem0, a memory-centric architecture with graph-based memory, enhances long-term conversational coherence in LLMs by efficiently extracting,… | [mem0ai/mem0](https://github.com/mem0ai/mem0) 68296★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 16 | [audio8 tts realistic air](https://huggingface.co/Edge0/Audio8-TTS-Realistic-Air) | text-to-speech | 251 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 90 | 4 | [Jailbreaking my car's navigation system just so I can change the time](https://blog.nns.ee/2026/11/02/renault-hack/) | `linux` `reversing` `security` | [讨论](https://lobste.rs/s/qvdatp/jailbreaking_my_car_s_navigation_system) |
| 35 | 3 | [A Decade of Kill Bugs](https://alangrow.com/blog/a-decade-of-kill-bugs) | `historical` `linux` `unix` | [讨论](https://lobste.rs/s/wgoato/decade_kill_bugs) |
| 35 | 3 | [Stop Hardcoding Your Timeouts](https://alfy.blog/2026/04/23/stop-hardcoding-your-timeouts.html) | `a11y` `practices` | [讨论](https://lobste.rs/s/qa0owz/stop_hardcoding_your_timeouts) |
| 24 | 4 | [This background sound leaks your exact location](https://youtu.be/UytYrhYLOKI) | `math` `security` `video` | [讨论](https://lobste.rs/s/s1btqo/this_background_sound_leaks_your_exact) |
| 22 | 6 | [My favourite laptop](https://blog.jsbarretto.com/post/laptop) | `hardware` | [讨论](https://lobste.rs/s/ezg5mx/my_favourite_laptop) |
| 5 | 5 | [Why did you choose the nix you nix?](https://lobste.rs/s/7fcuxz) | `ask` `nix` | [讨论](https://lobste.rs/s/7fcuxz/why_did_you_choose_nix_you_nix) |
| 143 | 20 | [An outsider's perspective on Scion and Mononoke](https://typesanitizer.com/blog/scion.html) | `vcs` | [讨论](https://lobste.rs/s/s2qeww/outsider_s_perspective_on_scion_mononoke) |
| 25 | 6 | [Polyend releases the Tracker firmware source code](https://backstage.polyend.com/t/tracker-the-biggest-update-yet/25120) | `art` `release` | [讨论](https://lobste.rs/s/gu6yyl/polyend_releases_tracker_firmware) |
| 17 | 41 | [What are you doing this week?](https://lobste.rs/s/maqsgl) | `ask` `programming` | [讨论](https://lobste.rs/s/maqsgl/what_are_you_doing_this_week) |
| 23 | 10 | [My reflex of assuming our servers need ever-growing amounts of RAM](https://utcc.utoronto.ca/~cks/space/blog/sysadmin/ServerRAMGrowthReflex) | `devops` `hardware` | [讨论](https://lobste.rs/s/saskzi/my_reflex_assuming_our_servers_need_ever) |
| 13 | 1 | [Sparks of Weight-Space Programming: LLMs can natively read & write neural network weights](https://rikiyat.github.io/blog/weight-space-programming/) | `ai` | [讨论](https://lobste.rs/s/u7wdqj/sparks_weight_space_programming_llms_can) |
| 47 | 19 | [Postgres 19 is late, and it's AI's fault](http://rhaas.blogspot.com/2026/10/postgres-19-is-late-and-its-ais-fault.html) | `databases` `practices` | [讨论](https://lobste.rs/s/0yxkvs/postgres_19_is_late_it_s_ai_s_fault) |
| 11 | 0 | [An Introduction to Bε-trees and Write-Optimization](https://www.usenix.org/publications/login/oct15/bender) | `databases` | [讨论](https://lobste.rs/s/0ec9yk/introduction_b_trees_write_optimization) |
| 28 | 5 | [the lost malloc()](https://napcakes.nekoweb.org/posts/malloc/) | `c` `historical` `unix` | [讨论](https://lobste.rs/s/ihqhia/lost_malloc) |
| 91 | 11 | [Work on GEFS (the Good Enough File System) for OpenBSD progresses](https://www.undeadly.org/cgi?action=article;sid=20261101115637) | `openbsd` | [讨论](https://lobste.rs/s/zjjvbo/work_on_gefs_good_enough_file_system_for) |
| 10 | 2 | [Program](https://schmud.de/posts/2026-11-02-program.html) | `programming` | [讨论](https://lobste.rs/s/yv7udx/program) |
| 11 | 2 | [Recognizing Keystrokes Using WiFi Devices](https://ieeexplore.ieee.org/document/7875144) | `security` | [讨论](https://lobste.rs/s/8gsafe/recognizing_keystrokes_using_wifi) |
| 7 | 0 | [SuperVote: 15 year retrospective on an app for sharing political endorsements](https://callejas.com/a/supervote/) | `ios` `java` | [讨论](https://lobste.rs/s/jo8vaj/supervote_15_year_retrospective_on_app) |
| 6 | 9 | [Virtual Art Museum built with Three js](https://dostoynikov.bearblog.dev/virtual-museum-for-my-wifes-artworks/) | `art` `culture` `javascript` | [讨论](https://lobste.rs/s/c8ayyw/virtual_art_museum_built_with_three_js) |
| 41 | 11 | [Pratt parsing is a black box](https://vinipsmaker.github.io/blog/article/pratt-parsing-is-a-black-box/) | `compilers` `plt` | [讨论](https://lobste.rs/s/bzazar/pratt_parsing_is_black_box) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 74 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 21 | 15 | 71% | — |
| 🔴 先核对 | 16 | 8 | 50% | — |
| 🟡 在降温 | 5 | 0 | 0% | — |
| 🔵 已被发现 | 2 | 0 | 0% | — |
| 🟢 窗口内 | 10 | 6 | 60% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) | 2026-10-20 | 🚀 爆发 | 6282 | 50632 | 6 | ✅ 起来了 |
| [nichochar/ari](https://github.com/nichochar/ari) | 2026-10-20 | 🔴 先核对 | 154 | 219 | 0 | 没起来 |
| [simbasjungles/free-my-tv](https://github.com/simbasjungles/free-my-tv) | 2026-10-20 | 🚀 爆发 | 481 | 5777 | 1 | ✅ 起来了 |
| [zcbacxc/mcd-party-planner](https://github.com/zcbacxc/mcd-party-planner) | 2026-10-20 | 🟢 窗口内 | 505 | 1596 | 0 | ✅ 起来了 |

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
