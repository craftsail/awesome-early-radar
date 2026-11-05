# early-radar 选题雷达 · 2026-11-05

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 100 个，细查前 20 个 · 比上次 = 和 2026-11-04 那次比 · 生成于 2026-11-05 06:12 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 3 个 · Show HN ✅ 29 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 8 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 6 个 · 🟡 在降温 9 个 · 🔵 已被发现 0 个 · 💤 不活跃 0 个 · 🔴 先核对 5 个
- **今天新出现 2 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) 平均每天 +3878，见 [爆发](#爆发)
- **复盘**：🚀 爆发 21/31 · 🔴 先核对 8/18 · 🟡 在降温 0/5 · 🔵 已被发现 0/2 · 🟢 窗口内 6/11（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) — 🤖 Open-source, local-first alternative to Grok Bot, OpenAI d…（近 7 天 +2702，前 7 天没有新增，这周才开始涨）
  - [benjitaylor/skills](https://github.com/benjitaylor/skills) — Skills for AI coding agents.（近 7 天 +1966，前 7 天没有新增，这周才开始涨）
  - [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) — Agent skill: describe your stack in a sentence, get an archi…（近 7 天 +1782，刚发布一周内）
- **趋势信号**：带 `ai-agents` topic 的新仓库这批里有 23 个（star 合计 24514），代表：[KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop)、[HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：6 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: HackerBooks – HackerTube, but for books mentioned on HN](https://hackerbooks.org) — 1852 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) | 18850 | 3878 | +1431 | 4.9 | [11](https://news.ycombinator.com/item?id=50316116) | dsh superagent prototype · deepseek-ai dsh superagent prototype · deepseek dsh superagent prototype | Towards a More Autonomous Agent System |
| ✅ [storytold/craft-anything](https://github.com/storytold/craft-anything) | 12831 | 2765 | +3733 | 4.6 | — | craft anything · storytold craft anything · artcraft craft anything | Craft Anything: understand how any software works, and craft… |
| [ccch1mneyyy/dsh-Go](https://github.com/ccch1mneyyy/dsh-Go) | 10114 | 926 | +2001 | 10.9 | — | dsh go · ccch1mneyyy dsh go · chimney dsh go | dsh-go — DeepSeek Harness 装进口袋：手机本机运行，也能遥控你的电脑。 |
| [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop) | 2807 | 1459 | +1689 | 1.9 | — | agent autoloop · kkkkhazix agent autoloop · khazix agent autoloop | 让你的命令行 Agent 在后台自己接活、自己跟进到底；平时不烦你，遇到拿不准的事才发卡片找你拍板。 |
| [heydamir/unslop](https://github.com/heydamir/unslop) | 8886 | 1345 | +1182 | 6.6 | — | unslop · heydamir unslop · damir unslop | A Claude skill that turns vibecoded, AI-looking UI into a de… |
| 🆕 [govijr/terminal-mac](https://github.com/govijr/terminal-mac) | 1673 | 790 | +1107 | 2.1 | [1](https://news.ycombinator.com/item?id=50359027) | terminal mac · govijr terminal mac | Entire MacOS running in your terminal. |
| [wangzan101/Mika](https://github.com/wangzan101/Mika) | 6795 | 1022 | +609 | 6.7 | — | mika · wangzan101 mika · wangzan mika | An on-device AI agent for Android that operates apps and the… |
| 🆕 [worldonlyu/Google_AI_Pro_2Year_ZeroCost_Auto](https://github.com/worldonlyu/Google_AI_Pro_2Year_ZeroCost_Auto) | 1016 | 1016 | — | 1 | — | google ai pro 2year zerocost auto · worldonlyu google ai pro 2year zerocost auto | Google_AI_Pro_2Year_ZeroCost_Auto |
| [patch-gg/pixelfx](https://github.com/patch-gg/pixelfx) | 4860 | 813 | +604 | 6 | — | pixelfx · patch-gg pixelfx · patch pixelfx | 244 pixel art effects, every one a small piece of code. Plus… |
| [valentderah/totk-pc-recomp](https://github.com/valentderah/totk-pc-recomp) | 4920 | 730 | +331 | 6.7 | — | totk pc recomp · valentderah totk pc recomp · valiantsin totk pc recomp | Static recompilation of The Legend of Zelda: Tears of the Ki… |
| [Djihads80/Eglantine](https://github.com/Djihads80/Eglantine) | 3873 | 535 | +730 | 7.2 | — | eglantine · djihads80 eglantine · djihad eglantine | VERY experimental Nintendo Switch 2 emulator |
| [anhao/ai-pose-gallery-zh](https://github.com/anhao/ai-pose-gallery-zh) | 5988 | 685 | +169 | 8.7 | — | ai pose gallery zh · anhao ai pose gallery zh | 中文版 AI 姿势参考图库 · 1439 组 / 2878 张图片 / 完整汉化 · 零依赖静态画廊 |
| [unclebob/ub-mode](https://github.com/unclebob/ub-mode) | 7010 | 662 | +183 | 10.6 | [3](https://news.ycombinator.com/item?id=50369325) | ub mode · unclebob ub mode · robert ub mode |  |
| [BryceYuuu/RUN](https://github.com/BryceYuuu/RUN) | 3766 | 555 | +501 | 6.8 | — | run · bryceyuuu run · bryce run | RUN · 润：海外移居手册（欧洲 36 国 · 110 条路线 · 主要移民地区） |
| 🆕 [wquguru/cicada](https://github.com/wquguru/cicada) | 1277 | 318 | +540 | 4 | — | cicada · wquguru cicada | 知了 Cicada · 任何会议和直播的实时字幕、同声传译、AI 会议纪要，Mac、Windows、Linux、Andr… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 94.8 | 🟢 窗口内 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) | Python | 2703 | +332 | +2702 | +0 | `········▁▇█▅▄·` | 8 | — | — |
| 2 | 91 | 🟢 窗口内 | [benjitaylor/skills](https://github.com/benjitaylor/skills) | TypeScript | 1965 | +412 | +1966 | +0 | `········▃▇▇█▅·` | 10 | — | — |
| 3 | 89.8 | 🟢 窗口内 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | TypeScript | 1782 | +162 | +1782 | +0 | `·········█▇▄▂·` | 4 | — | — |
| 4 | 88.8 | 🟢 窗口内 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 1766 | +110 | +1639 | +127 | `··▁▁▂▁▂▄██▆▄▃·` | 9 | [2](https://news.ycombinator.com/item?id=50272846) | — |
| 5 | 86.3 | 🟢 窗口内 | [qybaihe/bla](https://github.com/qybaihe/bla) | TypeScript | 2348 | +257 | +1331 | +1019 | `··▁▁▂▁█▅▃▂▂▂▃·` | 11 | — | — |
| 6 | 74 | 🟢 窗口内 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 2374 | +89 | +477 | +423 | `▅▄▅▄▅▃▃▂▂▅██▅·` | 17 | — | — |
| 7 | 66.3 | 🟡 在降温 | [daveebbelaar/bama](https://github.com/daveebbelaar/bama) | Swift | 1573 | +46 | +753 | +820 | `···▄██▆▅▅▇▄▃▂·` | 11 | — | — |
| 8 | 64.6 | 🟡 在降温 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 1914 | +112 | +636 | +1277 | `··█▄▄▂▂▂▂▂▂▄▂·` | 10 | — | — |
| 9 | 62.3 | 🟡 在降温 | [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) | Kotlin | 1625 | +62 | +505 | +1119 | `▄█▇▄▅▄▃▃▃▃▃▃▃·` | 14 | — | — |
| 10 | 59.8 | 🟡 在降温 | [ZiChuanLan/agent-purge](https://github.com/ZiChuanLan/agent-purge) | JavaScript | 1269 | +73 | +393 | +876 | `··▅█▆▄▂▂▁▂▂▅▂·` | 11 | — | — |
| 11 | 59.5 | 🟡 在降温 | [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) | TypeScript | 1944 | +29 | +383 | +1560 | `····██▃▂▂▂▂▁▁·` | 14 | — | — |
| 12 | 56.7 | 🟡 在降温 | [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) | Python | 1716 | +19 | +288 | +1429 | `·▅█▅▂▁▂▂▂▁▁▁▁·` | 13 | — | — |
| 13 | 56.2 | 🟡 在降温 | [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | TypeScript | 1783 | +19 | +274 | +1509 | `··▂█▄▃▂▁▁▂▂▁▁·` | 10 | — | — |
| 14 | 55.1 | 🟡 在降温 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | Rust | 1986 | +24 | +246 | +1553 | `▁▂▃▆█▂▁▂▁▂▁▁▁·` | 16 | [4](https://news.ycombinator.com/item?id=50340534) | — |
| 15 | 51.9 | 🟡 在降温 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2501 | +14 | +178 | +2299 | `█▅▂▂▂▁▁▁▁▁▁▁▁·` | 14 | [3](https://news.ycombinator.com/item?id=50207695) | — |
| 16 | 47.6 | 🔴 先核对 | [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop) | TypeScript | 2807 | +1689 | +2809 | +0 | `···········█▇·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 44.3 | 🔴 先核对 | [lexifina/global-law](https://github.com/lexifina/global-law) | HTML | 1804 | +38 | +1620 | +184 | `······▂█▃▂▂▁▁·` | 7 | [1](https://news.ycombinator.com/item?id=50283329) | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 40 | 🆕 🔴 先核对 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Rust | 782 | — | +782 | +0 | `···········▁█·` | 3 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 36.7 | 🔴 先核对 | [Balanov/shim](https://github.com/Balanov/shim) | Go | 456 | +11 | +456 | +0 | `··········█▂▁·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 30.1 | 🆕 🔴 先核对 | [Balanov/equal](https://github.com/Balanov/equal) | Go | 151 | — | +151 | +0 | `············█·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 588 | 30 | 48483 | [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop)、[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) |
| `mcp` | 304 | 30 | 38691 | [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop)、[qybaihe/bla](https://github.com/qybaihe/bla)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `rust` | 244 | 30 | 31865 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[opengeos/RustGIS](https://github.com/opengeos/RustGIS)、[indexable-inc/blaze](https://github.com/indexable-inc/blaze) |
| `local-first` | 82 | 30 | 13729 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo)、[yjid/kensaku](https://github.com/yjid/kensaku) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `ai-agents` | 23 | 24514 | [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop)、[HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering) |
| `claude-code` | 21 | 31407 | [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop)、[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) |
| `codex` | 16 | 21265 | [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) |
| `agent-skills` | 14 | 21366 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) |
| `mcp-server` | 11 | 13882 | [qybaihe/bla](https://github.com/qybaihe/bla)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `llm` | 9 | 7639 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot)、[Syenzzz/mcd-coupon-strategist](https://github.com/Syenzzz/mcd-coupon-strategist)、[sahenjp/RustXNG](https://github.com/sahenjp/RustXNG) |
| `self-hosted` | 8 | 9988 | [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `typescript` | 8 | 7232 | [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop)、[pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust)、[rociiu/talorys](https://github.com/rociiu/talorys) |
| `claude-skills` | 7 | 11718 | [Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[UnderleveledBuilder/awesome-short-drama-skills](https://github.com/UnderleveledBuilder/awesome-short-drama-skills) |
| `macos` | 7 | 6568 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[kitlangton/scrawl](https://github.com/kitlangton/scrawl) |
| `windows` | 7 | 6010 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[LingCore/WinShun](https://github.com/LingCore/WinShun)、[yzlin286-wq/Deepscient](https://github.com/yzlin286-wq/Deepscient) |
| `developer-tools` | 7 | 5846 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai)、[kitlangton/scrawl](https://github.com/kitlangton/scrawl) |

**语言分布**：Rust 32 · Python 19 · TypeScript 17 · JavaScript 13 · Go 7 · HTML 4 · Swift 2 · Astro 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) · 🟢 窗口内 · 94.8 分

> 🤖 Open-source, local-first alternative to Grok Bot, OpenAI dots and Claude Duet. Your own AI bots on any model: GPT, Claude, Gemini, Grok, DeepSeek, Kimi, GLM and 70+ more through one Modelflare key. Reach them in the app, WeChat or Feishu; they remember you, work in the background, run commands and use your computer. Pay per use.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2703 | +2702 | +0 | 32 | 0 | Python | MIT | 10-27（8 天前） | 今天 |

- **近 14 天每天新增**：`········▁▇█▅▄·` 0 0 0 0 0 0 0 0 1 870 965 513 353 0
- **势头**：前 7 天没有新增，这周才开始涨
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `ai-assistant` `chatbot` `claude` `computer-use` `deepseek` `desktop-app` `dsh` `electron` `feishu` `gemini` `gpt` `grok` `llm` `local-first` `modelflare` `multi-model` `openai-compatible` `personal-ai-agent` `wechat`
- **主页**：<https://anymodel.bot/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [benjitaylor/skills](https://github.com/benjitaylor/skills) · 🟢 窗口内 · 91 分

> Skills for AI coding agents.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1965 | +1966 | +0 | 136 | 0 | TypeScript | — | 10-26（10 天前） | 今天 |

- **近 14 天每天新增**：`········▃▇▇█▅·` 0 0 0 0 0 0 0 0 139 450 478 556 343 0
- **势头**：前 7 天没有新增，这周才开始涨
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) · 🟢 窗口内 · 89.8 分

> Agent skill: describe your stack in a sentence, get an architecture diagram with official logos

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1782 | +1782 | +0 | 81 | 0 | TypeScript | MIT | 11-01（4 天前） | 2 天前 |

- **近 14 天每天新增**：`·········█▇▄▂·` 0 0 0 0 0 0 0 0 0 723 595 331 133 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `architecture-diagram` `claude-code` `claude-skills` `codex` `diagram` `system-architecture` `tech-stack`
- **主页**：<stacks.caru.moe>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) · 🟢 窗口内 · 88.8 分

> UEFI pre-driver NVIDIA GPU unlocker for Windows Linux Hackintosh and all EFI-bootable system (Rust): SEC2 scrubber -> FWSEC/WPR2 -> signed Booter -> V67 four-write payload, read-back verified. Verified on most RTX 20 30 40 Series.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1766 | +1639 | +127 | 167 | 35 | Rust | GPL-2.0 | 10-26（9 天前） | 今天 |

- **近 14 天每天新增**：`··▁▁▂▁▂▄██▆▄▃·` 0 0 5 7 51 30 34 169 449 420 307 196 98 0
- **势头**：比前 7 天快 12.9 倍，在加速
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50272846)）
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [qybaihe/bla](https://github.com/qybaihe/bla) · 🟢 窗口内 · 86.3 分

> 🛡️ BLA (Blind LLM Agents) — Adversarial defense shield that protects binaries, Electron apps, JS bundles, Python, and WebAssembly against AI reverse-engineering agents like REA. Poison -> Exhaust -> Hallucinate.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2348 | +1331 | +1019 | 310 | 19 | TypeScript | MIT | 10-25（11 天前） | 今天 |

- **近 14 天每天新增**：`··▁▁▂▁█▅▃▂▂▂▃·` 0 0 2 27 143 31 816 488 238 145 123 96 241 0
- **势头**：比前 7 天快 1.3 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adversarial-ai` `claude-code` `cursor` `electron-security` `llm-security` `mcp` `mcp-server` `obfuscation` `reverse-engineering` `webassembly`
- **主页**：<https://bla.tools>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) · 🟢 窗口内 · 74 分

> 让你的agent一键直出商业级产品宣传片：会作曲，能指着画面改。Commercial-grade launch films by your coding agent — point at the frame to change it.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2374 | +477 | +423 | 237 | 4 | JavaScript | MIT | 10-18（17 天前） | 13 天前 |

- **近 14 天每天新增**：`▅▄▅▄▅▃▃▂▂▅██▅·` 78 50 83 68 73 37 34 26 29 73 137 131 81 0
- **势头**：比前 7 天快 1.1 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `animation` `claude-code` `codex` `gsap` `launch-video` `motion-graphics` `skills`
- **主页**：<https://github.com/alchaincyf/huashu-motion>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [daveebbelaar/bama](https://github.com/daveebbelaar/bama) · 🟡 在降温 · 66.3 分

> BAMA: Build Any Mac App. Agent skills to research, clone, design, build, optimize, and test native macOS apps with Swift and SwiftUI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1573 | +753 | +820 | 196 | 5 | Swift | MIT | 10-24（11 天前） | 3 天前 |

- **近 14 天每天新增**：`···▄██▆▅▅▇▄▃▂·` 0 0 0 121 265 251 183 152 154 228 111 64 44 0
- **势头**：只有前 7 天的 92%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-agents` `app-clone` `claude-code` `claude-code-plugin` `codex` `computer-use` `liquid-glass` `macos` `macos-app` `native-apps` `skills` `swift` `swiftdata` `swiftui`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) · 🟡 在降温 · 64.6 分

> Evidence-first genealogy skill for AI agents (Codex, Claude Code): church books, civil, military, deportation and repression records across the former USSR. Replies in your language.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1914 | +636 | +1277 | 193 | 1 | Python | MIT | 10-25（10 天前） | 今天 |

- **近 14 天每天新增**：`··█▄▄▂▂▂▂▂▂▄▂·` 0 0 593 228 255 113 88 71 61 54 64 286 100 0
- **势头**：只有前 7 天的 50%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `archives` `claude-code` `codex` `family-history` `familysearch` `genealogy` `ussr`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) · 🟡 在降温 · 62.3 分

> A community-built phone app for Clean Your TV: clean up an Android TV from your phone. No laptop, no coding agent, nothing uninstalled.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1625 | +505 | +1119 | 142 | 4977 | Kotlin | MIT | 10-21（14 天前） | 1 天前 |

- **近 14 天每天新增**：`▄█▇▄▅▄▃▃▃▃▃▃▃·` 103 288 243 133 150 114 88 79 95 92 101 76 62 0
- **势头**：只有前 7 天的 45%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adb` `android-tv` `debloat` `fire-tv` `google-tv` `launcher`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [ZiChuanLan/agent-purge](https://github.com/ZiChuanLan/agent-purge) · 🟡 在降温 · 59.8 分

> One persona, many coding agents. Replace or inject system prompts across codex, claude, opencode, grok, omp, hermes, pi, zcode - with a local web console.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1269 | +393 | +876 | 822 | 1 | JavaScript | MIT | 10-25（11 天前） | 今天 |

- **近 14 天每天新增**：`··▅█▆▄▂▂▁▂▂▅▂·` 0 0 161 311 208 146 50 36 18 39 61 188 51 0
- **势头**：只有前 7 天的 45%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`claude-code` `codex` `coding-agent` `deepseek-harness` `harness` `omp` `opencode` `pi` `system-prompt`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop) — 一天进了一半以上的 star，但 HN 上没火过
- [lexifina/global-law](https://github.com/lexifina/global-law) — 一天进了一半以上的 star，但 HN 上没火过
- [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) — 一天进了一半以上的 star，但 HN 上没火过
- [Balanov/shim](https://github.com/Balanov/shim) — 一天进了一半以上的 star，但 HN 上没火过
- [Balanov/equal](https://github.com/Balanov/equal) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 1852 | 306 | [Show HN: HackerBooks – HackerTube, but for books mentioned on HN](https://hackerbooks.org) | [HN](https://news.ycombinator.com/item?id=50326821) |
| 830 | 390 | [Show HN: Subvocal – Talk to your computer without making noise](https://news.ycombinator.com/item?id=50340088) | [HN](https://news.ycombinator.com/item?id=50340088) |
| 471 | 148 | [Show HN: Hacker Times, a New York Times-inspired version of Hacker News](https://hackertimes.ca/) | [HN](https://news.ycombinator.com/item?id=50346981) |
| 463 | 80 | [Show HN: HackerTV – HN's most-recommended Youtube videos as 24/7 TV channels](https://hackertv.org) | [HN](https://news.ycombinator.com/item?id=50346755) |
| 339 | 104 | [Show HN: Wikihack – HackerTube, but for Wikipedia articles mentioned on HN](https://wikihack.netlify.app) | [HN](https://news.ycombinator.com/item?id=50333339) |
| 323 | 52 | [Show HN: Warsaw in voxels – An interactive 3D map of the city centre](https://p.migdal.pl/warsaw-vibe-voxel/) | [HN](https://news.ycombinator.com/item?id=50339221) |
| 319 | 96 | [Show HN: OmniDiff – Opensource, super fast, content aware Git difftool, in Rust](https://github.com/ivankovic/omnidiff) | [HN](https://news.ycombinator.com/item?id=50325253) |
| 297 | 153 | [Show HN: A working Nintendo in ~1GB of Qwen weights](https://github.com/dbreunig/nesformer) | [HN](https://news.ycombinator.com/item?id=50306442) |
| 262 | 55 | [Show HN: Point your camera at a landscape to learn about its geology](https://outcrop.rocks/) | [HN](https://news.ycombinator.com/item?id=50290533) |
| 245 | 80 | [Show HN: To Honor Sir Patrick Stewart, Enjoy the TNG Episode Guessing Game](https://tng.episodle.com/) | [HN](https://news.ycombinator.com/item?id=50311686) |
| 237 | 55 | [Show HN: I've updated my Linux System Call website and API](https://syscall.sh/) | [HN](https://news.ycombinator.com/item?id=50334704) |
| 183 | 25 | [Show HN: HackerHack – HackerBooks but for Posts Posted on HN](https://news.ycombinator.com/) | [HN](https://news.ycombinator.com/item?id=50333877) |
| 154 | 133 | [Show HN: Auto Dismiss Mac OS "Allow <app> to find devices on local networks?"](https://github.com/johncassil/dontallow) | [HN](https://news.ycombinator.com/item?id=50294506) |
| 148 | 17 | [Show HN: After a decade of reversing, I got co-op working in DOS Wing Commander](https://fireflyk64.github.io/wcmulti/) | [HN](https://news.ycombinator.com/item?id=50369895) |
| 132 | 36 | [Show HN: I Turned DOOM into a Transformer](https://github.com/mottopanikeiku/doomformer) | [HN](https://news.ycombinator.com/item?id=50297697) |
| 124 | 66 | [Show HN: Uncracked City, detective game where you question LLM suspects that lie](https://uncracked.city) | [HN](https://news.ycombinator.com/item?id=50358352) |
| 109 | 6 | [Show HN: A language model that lives in a boot sector](https://github.com/kerlenton/bootgpt) | [HN](https://news.ycombinator.com/item?id=50315782) |
| 107 | 30 | [Show HN: I rebuilt my old canvas 3D library as a small WebGL 2 library – phoria2](https://kevs3d.co.uk/phoria2/) | [HN](https://news.ycombinator.com/item?id=50314508) |
| 104 | 33 | [Show HN: Kairos – Open-source risk and fraud decisioning platform](https://github.com/finic-ai/kairos) | [HN](https://news.ycombinator.com/item?id=50358314) |
| 99 | 72 | [Show HN: I built a tool that prices a pre-built PC part by part](https://pcdealcheck.com/) | [HN](https://news.ycombinator.com/item?id=50366929) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 63 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 46814★ |
| 13 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 4780★ |
| 161 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 120676★ |
| 67 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 22669★ |
| 110 | [FreeToken: Efficient Edge-Native MoE Serving with Bandwidth-Adaptive Execution](https://huggingface.co/papers/2608.16157) | FreeToken is an edge-native Mixture-of-Experts serving system that dynamically maps computation and model state onto heterogeneous local har… | [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken) 16634★ |
| 45 | [Democratizing Robot-Use Agents: A Unified Harness with Open Models](https://huggingface.co/papers/2611.01560) | Uni-robot-agent enables open-weight robot-use agents to surpass proprietary models in zero-shot manipulation and suggests joint development… | 💡 [Open-RUA/uni-robot-agent](https://github.com/Open-RUA/uni-robot-agent) 212★ |
| 104 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 30571★ |
| 1 | [Differentiable Data Augmentation with Kornia](https://huggingface.co/papers/2011.09832) | This paper reviews the Kornia differentiable data augmentation module for both 2D and 3D tensors, integrating with PyTorch's autograd and op… | [arraiyopensource/kornia](https://github.com/arraiyopensource/kornia) 12328★ |
| 44 | [WeVisOne-VL: Unified Visual Perception from Objects to Pixels](https://huggingface.co/papers/2610.31329) | WeVisOne-VL unifies object-level and pixel-level visual perception via structured token prediction, supporting detection, localization, coun… | 💡 [Tencent/WeVisOne-VL](https://github.com/Tencent/WeVisOne-VL) 909★ |
| 17 | [SpecPilot: Autonomous Algorithm Discovery and Systems Optimization for Speculative Decoding](https://huggingface.co/papers/2611.02501) | SpecPilot autonomously discovers deployment-specific algorithms and system optimizations to maximize speculative decoding speedups across di… | 💡 [StargazerX0/SpecPilot](https://github.com/StargazerX0/SpecPilot) 123★ |
| 39 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 35376★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 35377★ |
| 13 | [Xiaomi-OCR-0 Technical Report](https://huggingface.co/papers/2609.36136) | Xiaomi-OCR-0 is a compact vision-language model that unifies document parsing and OCR understanding through automated data synthesis, progre… | 💡 [SeerRay-Lab/Xiaomi-OCR-0](https://github.com/SeerRay-Lab/Xiaomi-OCR-0) 905★ |
| 29 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 9042★ |
| 31 | [HairDeck: Animation-Ready Stylized Hair Cards from a Single Image](https://huggingface.co/papers/2610.40599) | HairDeck generates stylized hair cards and spring-bone animations as unordered token sets using a diffusion transformer, improving accuracy… | 💡 [hyz317/HairDeck](https://github.com/hyz317/HairDeck) 816★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 86 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 92650★ |
| 101 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 3189★ |
| 78 | [CUA-Master: Scaling Computer-use Agents through Open-World Recursive Improvements](https://huggingface.co/papers/2611.03126) | CUA-Master uses nested recursive loops with open-world data and feedback-driven retries to continuously improve computer-use agents across d… | 💡 [xlyu0106/CUA-Master](https://github.com/xlyu0106/CUA-Master) 98★ |
| 90 | [MOSS-Image Technical Report](https://huggingface.co/papers/2610.23374) | MOSS-Image is an open diffusion transformer that combines high-fidelity synthesis with intent-aware prompt enhancement to generate text-rich… | [OpenMOSS/MOSS-Image](https://github.com/OpenMOSS/MOSS-Image) 2609★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 4 | [kimi k3.1 pro](https://huggingface.co/moonshotai/Kimi-K3.1-Pro) | image-text-to-text | 601 | 1 |
| 30 | [ripple](https://huggingface.co/ricursiveAI/Ripple-65B-Preview) | — | 147 | 1 |
| 49 | [qwen3.8 flash next](https://huggingface.co/unsloth/Qwen3.8-Flash-Next-GGUF) | image-text-to-text | 1390 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 80 | 11 | [So my ISP was hijacking my DNS](https://karthihegde.dev/posts/dns_tampering) | `networking` | [讨论](https://lobste.rs/s/cozhtg/so_my_isp_was_hijacking_my_dns) |
| 72 | 8 | [Shlemiel the Painter Is Back: How Zig’s libc Rewrite Made SQLite Slower](https://dennisforbes.ca/blog/microblog/2026/10/the_accidental_12000x_sqlite_slowdown/) | `performance` `rust` `zig` | [讨论](https://lobste.rs/s/lh1j0e/shlemiel_painter_is_back_how_zig_s_libc) |
| 54 | 10 | [Your Cryptography Conspiracy Theory Is Wrong](https://soatok.blog/2026/10/29/your-cryptography-conspiracy-theory-is-wrong/) | `cryptography` | [讨论](https://lobste.rs/s/bqllfe/your_cryptography_conspiracy_theory_is) |
| 20 | 2 | [Declarative Dragging](https://declarative-dragging.github.io/) | `design` `graphics` `plt` | [讨论](https://lobste.rs/s/jplxxr/declarative_dragging) |
| 37 | 10 | [Introducing Adaptive Dark Mode](https://webkit.org/blog/18541/introducing-adaptive-dark-mode/) | `css` `web` | [讨论](https://lobste.rs/s/yba0yg/introducing_adaptive_dark_mode) |
| 21 | 4 | [A new Go API for JSON](https://go.dev/blog/jsonv2) | `go` | [讨论](https://lobste.rs/s/gfm0xn/new_go_api_for_json) |
| 34 | 4 | [Man-in-the-middle arbitrary code execution in Debian’s apt](https://lists.debian.org/debian-security-announce/2026/msg00526.html) | `linux` `security` | [讨论](https://lobste.rs/s/h7bvma/man_middle_arbitrary_code_execution) |
| 34 | 29 | [C++26 Disapproved](https://andreasfertig.com/blog/2026/11/cpp26-dis-failed-how-does-cpp-survive/) | `c++` | [讨论](https://lobste.rs/s/xvtufg/c_26_disapproved) |
| 36 | 1 | [How to speed up the Rust compiler in November 2026](https://nnethercote.github.io/2026/11/04/how-to-speed-up-the-rust-compiler-in-november-2026.html) | `compilers` `rust` | [讨论](https://lobste.rs/s/ecrqpy/how_speed_up_rust_compiler_november_2026) |
| 48 | 0 | [Zig 0.17.1 Released](https://ziglang.org/news/0.17.1-released/) | `release` `zig` | [讨论](https://lobste.rs/s/pa1411/zig_0_17_1_released) |
| 114 | 2 | [Observations from Running stealmybitcoin.com](https://pavursec.com/blog/stealmybitcoin/) | `php` `security` | [讨论](https://lobste.rs/s/fgucra/observations_from_running) |
| 13 | 2 | [Burnt TOAST](https://www.pgedge.com/blog/burnt-toast) | `databases` | [讨论](https://lobste.rs/s/dmpdid/burnt_toast) |
| 16 | 0 | [Gleam Programming Language Update October 2026](https://www.youtube.com/watch?v=Jm2HZhwreNs) | `gleam` `video` | [讨论](https://lobste.rs/s/afjqpg/gleam_programming_language_update) |
| 106 | 92 | [Death comes for XSLT](https://dbushell.com/2026/11/03/xslt-rip/) | `browsers` `web` | [讨论](https://lobste.rs/s/chypzr/death_comes_for_xslt) |
| 17 | 0 | [Lorem Ipsum Dot Gov Dot UK](https://shkspr.mobi/blog/2026/11/lorem-ipsum-dot-gov-dot-uk/) | `testing` `web` | [讨论](https://lobste.rs/s/5xljpx/lorem_ipsum_dot_gov_dot_uk) |
| 4 | 0 | [Residential Proxies Detected on White House Network](https://layer3intel.com/blog/residential-proxies-white-house-network) | `security` | [讨论](https://lobste.rs/s/253two/residential_proxies_detected_on_white) |
| 4 | 0 | [A history of backdoors (2015)](https://blog.cryptographyengineering.com/2015/07/20/a-history-of-backdoors/) | `cryptography` `historical` | [讨论](https://lobste.rs/s/x1wkwe/history_backdoors_2015) |
| 80 | 63 | [The Ubuntu 26.04 Rust sudo is not compatible with standard sudo](https://utcc.utoronto.ca/~cks/space/blog/linux/Ubuntu2604RustSudoNotCompatible) | `linux` `rust` | [讨论](https://lobste.rs/s/e201eb/ubuntu_26_04_rust_sudo_is_not_compatible) |
| 9 | 0 | [Python on my wrist](https://tildeweb.nl/~michiel/python-on-my-wrist.html) | `hardware` `python` | [讨论](https://lobste.rs/s/0vis9y/python_on_my_wrist) |
| 47 | 5 | [Announcing NetBSD 11.1](https://www.netbsd.org/releases/formal-11/NetBSD-11.1.html) | `netbsd` `release` | [讨论](https://lobste.rs/s/siqsg7/announcing_netbsd_11_1) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 71 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 31 | 21 | 67% | — |
| 🔴 先核对 | 18 | 8 | 44% | — |
| 🟡 在降温 | 5 | 0 | 0% | — |
| 🔵 已被发现 | 2 | 0 | 0% | — |
| 🟢 窗口内 | 11 | 6 | 54% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [9bie/php2shell-bypass-aslr-exp](https://github.com/9bie/php2shell-bypass-aslr-exp) | 2026-10-22 | 🚀 爆发 | 615 | 1554 | 0 | ✅ 起来了 |
| [ctresb/leis](https://github.com/ctresb/leis) | 2026-10-22 | 🚀 爆发 | 1047 | 2512 | 0 | ✅ 起来了 |
| [eagle-hq/EAGLE-4](https://github.com/eagle-hq/EAGLE-4) | 2026-10-22 | 🚀 爆发 | 747 | 1156 | 2 | 没起来 |
| [eness/php2shell-CVE-2026-109618-CVE-2026-109619-PoC](https://github.com/eness/php2shell-CVE-2026-109618-CVE-2026-109619-PoC) | 2026-10-22 | 🚀 爆发 | 657 | 1067 | 0 | 没起来 |
| [ikow/php2shell-poc](https://github.com/ikow/php2shell-poc) | 2026-10-22 | 🚀 爆发 | 1104 | 1937 | 0 | 没起来 |
| [kanaworksai-hue/audio-studio-mcp](https://github.com/kanaworksai-hue/audio-studio-mcp) | 2026-10-22 | 🟢 窗口内 | 429 | 585 | 0 | 没起来 |
| [openai/php2shell-checker](https://github.com/openai/php2shell-checker) | 2026-10-22 | 🚀 爆发 | 499 | 1463 | 2 | ✅ 起来了 |
| [realskyrin/ns-game-apple-arm-port](https://github.com/realskyrin/ns-game-apple-arm-port) | 2026-10-22 | 🔴 先核对 | 429 | 534 | 0 | 没起来 |

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
