# early-radar 选题雷达 · 2026-11-07

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 101 个，细查前 20 个 · 比上次 = 和 2026-11-06 那次比 · 生成于 2026-11-07 05:37 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 1 个 · Show HN ✅ 25 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 4 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 5 个 · 🟡 在降温 11 个 · 🔵 已被发现 0 个 · 💤 不活跃 1 个 · 🔴 先核对 3 个
- **今天新出现 2 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) 平均每天 +2981，见 [爆发](#爆发)
- **复盘**：🚀 爆发 26/39 · 🔴 先核对 9/20 · 🟡 在降温 0/5 · 🔵 已被发现 1/3 · 🟢 窗口内 6/11（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) — 🤖 Open-source, local-first alternative to Grok Bot, OpenAI d…（近 7 天 +2728，比前 7 天快 2728.0 倍，在加速）
  - [benjitaylor/skills](https://github.com/benjitaylor/skills) — Skills for AI coding agents.（近 7 天 +2113，比前 7 天快 15.2 倍，在加速）
  - [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) — Agent skill: describe your stack in a sentence, get an archi…（近 7 天 +1985，刚发布一周内）
- **趋势信号**：带 `ai-agents` topic 的新仓库这批里有 23 个（star 合计 22392），代表：[morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：5 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: HackerBooks – HackerTube, but for books mentioned on HN](https://hackerbooks.org) — 1864 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) | 20381 | 2981 | +647 | 6.8 | [11](https://news.ycombinator.com/item?id=50316116) | dsh superagent prototype · deepseek-ai dsh superagent prototype · deepseek dsh superagent prototype | Towards a More Autonomous Agent System |
| ✅ [storytold/craft-anything](https://github.com/storytold/craft-anything) | 18592 | 2810 | +2807 | 6.6 | [5](https://news.ycombinator.com/item?id=50377361) | craft anything · storytold craft anything · artcraft craft anything | Craft Anything: understand how any software works, and craft… |
| [zortos293/Lichii](https://github.com/zortos293/Lichii) | 4197 | 632 | +1574 | 6.6 | — | lichii · zortos293 lichii · zortos lichii | VERY experimental Nintendo Switch 2 emulator |
| [heydamir/unslop](https://github.com/heydamir/unslop) | 10858 | 1265 | +820 | 8.6 | — | unslop · heydamir unslop · damir unslop | A Claude skill that turns vibecoded, AI-looking UI into a de… |
| [ccch1mneyyy/dsh-Go](https://github.com/ccch1mneyyy/dsh-Go) | 13184 | 1022 | +1252 | 12.9 | — | dsh go · ccch1mneyyy dsh go · chimney dsh go | dsh-go — DeepSeek Harness 装进口袋：手机本机运行，也能遥控你的电脑。 |
| [worldonlyu/Google_AI_Pro_2Year_ZeroCost_Auto](https://github.com/worldonlyu/Google_AI_Pro_2Year_ZeroCost_Auto) | 2927 | 1120 | +352 | 2.6 | — | google ai pro 2year zerocost auto · worldonlyu google ai pro 2year zerocost auto | Google_AI_Pro_2Year_ZeroCost_Auto |
| 🆕 [JenkinWoo/sheeridVerify](https://github.com/JenkinWoo/sheeridVerify) | 1060 | 1060 | — | 1 | — | sheeridverify · jenkinwoo sheeridverify |  |
| [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop) | 3750 | 962 | +378 | 3.9 | — | agent autoloop · kkkkhazix agent autoloop · khazix agent autoloop | 让你的命令行 Agent 在后台自己接活、自己跟进到底；平时不烦你，遇到拿不准的事才发卡片找你拍板。 |
| [JuneYaooo/rea-video](https://github.com/JuneYaooo/rea-video) | 3224 | 377 | +951 | 8.6 | [4](https://news.ycombinator.com/item?id=50368605) | rea video · juneyaooo rea video | Reverse-engineer any video, shot by shot: tells whether each… |
| [wangzan101/Mika](https://github.com/wangzan101/Mika) | 7446 | 863 | +234 | 8.6 | — | mika · wangzan101 mika · wangzan mika | An on-device AI agent for Android that operates apps and the… |
| [patch-gg/pixelfx](https://github.com/patch-gg/pixelfx) | 5653 | 711 | +279 | 8 | — | pixelfx · patch-gg pixelfx · patch pixelfx | 244 pixel art effects, every one a small piece of code. Plus… |
| [valentderah/totk-pc-recomp](https://github.com/valentderah/totk-pc-recomp) | 5470 | 628 | +258 | 8.7 | — | totk pc recomp · valentderah totk pc recomp · valiantsin totk pc recomp | Static recompilation of The Legend of Zelda: Tears of the Ki… |
| [anhao/ai-pose-gallery-zh](https://github.com/anhao/ai-pose-gallery-zh) | 6286 | 587 | +155 | 10.7 | — | ai pose gallery zh · anhao ai pose gallery zh | 中文版 AI 姿势参考图库 · 1439 组 / 2878 张图片 / 完整汉化 · 零依赖静态画廊 |
| [unclebob/ub-mode](https://github.com/unclebob/ub-mode) | 7217 | 574 | +76 | 12.6 | [3](https://news.ycombinator.com/item?id=50369325) | ub mode · unclebob ub mode · robert ub mode |  |
| 🆕 [Minireel/HGhub](https://github.com/Minireel/HGhub) | 1804 | 494 | +538 | 3.6 | — | hghub · minireel hghub | YellowFruit third-party client |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 94.9 | 🟢 窗口内 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) | Python | 2729 | +9 | +2728 | +1 | `······▁▇█▅▄▁▁·` | 10 | — | — |
| 2 | 91.9 | 🟢 窗口内 | [benjitaylor/skills](https://github.com/benjitaylor/skills) | TypeScript | 2251 | +109 | +2113 | +139 | `······▃▇▇█▆▃▂·` | 11 | — | — |
| 3 | 91.1 | 🟢 窗口内 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | TypeScript | 1985 | +104 | +1985 | +0 | `·······█▇▄▂▂▂·` | 6 | — | — |
| 4 | 85.5 | 🟢 窗口内 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 1984 | +112 | +1241 | +743 | `▁▁▂▁▂▄██▆▄▃▃▃·` | 11 | [2](https://news.ycombinator.com/item?id=50272846) | — |
| 5 | 76.4 | 🆕 🟢 窗口内 | [sqlpxc/airhand](https://github.com/sqlpxc/airhand) | Rust | 627 | +122 | +582 | +45 | `······▃▅▃▅▁█▆·` | 6 | — | — |
| 6 | 67.5 | 🟡 在降温 | [qybaihe/bla](https://github.com/qybaihe/bla) | TypeScript | 2596 | +137 | +853 | +1743 | `▁▁▂▁█▅▃▂▂▂▃▂▂·` | 13 | — | — |
| 7 | 65 | 🟡 在降温 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 2075 | +79 | +666 | +1408 | `█▄▄▂▂▂▂▂▂▄▂▂▂·` | 12 | — | — |
| 8 | 62.6 | 🟡 在降温 | [daveebbelaar/bama](https://github.com/daveebbelaar/bama) | Swift | 1647 | +34 | +521 | +1126 | `·▄██▆▅▅▇▄▃▂▂▂·` | 13 | — | — |
| 9 | 61.4 | 🟡 在降温 | [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) | Kotlin | 1756 | +66 | +463 | +902 | `█▅▅▄▄▃▄▄▄▃▃▃▃·` | 16 | — | — |
| 10 | 60.6 | 🟡 在降温 | [ZiChuanLan/agent-purge](https://github.com/ZiChuanLan/agent-purge) | JavaScript | 1358 | +46 | +429 | +929 | `▅█▆▄▂▂▁▂▂▅▂▂▂·` | 12 | — | — |
| 11 | 55.4 | 🟡 在降温 | [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | TypeScript | 1851 | +18 | +254 | +1597 | `▂█▄▃▂▁▁▂▂▁▁▁▁·` | 12 | — | — |
| 12 | 55 | 🟡 在降温 | [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) | TypeScript | 1977 | +12 | +243 | +1733 | `··██▃▂▂▂▂▁▁▁▁·` | 16 | — | — |
| 13 | 54.1 | 🟡 在降温 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | Rust | 2042 | +25 | +222 | +1525 | `▃▆█▂▁▂▁▂▁▁▁▁▁·` | 18 | [4](https://news.ycombinator.com/item?id=50340534) | — |
| 14 | 53.3 | 🟡 在降温 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2599 | +55 | +206 | +630 | `█▅▆▄▃▂▂▃▂▂▂▃▃·` | 16 | [3](https://news.ycombinator.com/item?id=50207695) | — |
| 15 | 53.2 | 🟡 在降温 | [cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) | Python | 1933 | +18 | +204 | +507 | `█▄▃▃▃▄▄▄▃▃▂▂▂·` | 21 | [1](https://news.ycombinator.com/item?id=50177079) | — |
| 16 | 48.4 | 🟡 在降温 | [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) | Python | 1747 | +16 | +125 | +1319 | `█▅▂▁▂▂▂▁▁▁▁▁▁·` | 15 | — | — |
| 17 | 42.5 | 🔴 先核对 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Rust | 1195 | +82 | +1195 | +0 | `·········▁█▃▂·` | 5 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 37.4 | 💤 不活跃 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 2460 | +38 | +510 | +349 | `▅▄▅▃▃▂▂▅██▅▃▃·` | 19 | — | — |
| 19 | 36.3 | 🆕 🔴 先核对 | [Lowbetweentrim/crypto-portfolio-tracker](https://github.com/Lowbetweentrim/crypto-portfolio-tracker) | Python | 425 | — | +425 | +0 | `············█·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 29.9 | 🔴 先核对 | [lexifina/global-law](https://github.com/lexifina/global-law) | HTML | 1840 | +16 | +394 | +1446 | `····▂█▃▂▂▁▁▁▁·` | 9 | [1](https://news.ycombinator.com/item?id=50283329) | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 612 | 30 | 45323 | [qybaihe/bla](https://github.com/qybaihe/bla)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[benjitaylor/skills](https://github.com/benjitaylor/skills) |
| `mcp` | 309 | 30 | 36771 | [qybaihe/bla](https://github.com/qybaihe/bla)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) |
| `rust` | 243 | 30 | 33310 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[opengeos/RustGIS](https://github.com/opengeos/RustGIS)、[indexable-inc/blaze](https://github.com/indexable-inc/blaze) |
| `local-first` | 82 | 30 | 13262 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot)、[s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[yjid/kensaku](https://github.com/yjid/kensaku) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `ai-agents` | 23 | 22392 | [morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering)、[marclou/mailcheap](https://github.com/marclou/mailcheap)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama) |
| `claude-code` | 19 | 26923 | [qybaihe/bla](https://github.com/qybaihe/bla)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `agent-skills` | 15 | 22534 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) |
| `codex` | 15 | 19562 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) |
| `mcp-server` | 11 | 14289 | [qybaihe/bla](https://github.com/qybaihe/bla)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `windows` | 10 | 7178 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[yjid/kensaku](https://github.com/yjid/kensaku)、[yzlin286-wq/Deepscient](https://github.com/yzlin286-wq/Deepscient) |
| `macos` | 8 | 7792 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[Zfinix/eleven](https://github.com/Zfinix/eleven) |
| `open-source` | 8 | 5150 | [alexgaoth/awesome-reverse-engineered](https://github.com/alexgaoth/awesome-reverse-engineered)、[yjid/kensaku](https://github.com/yjid/kensaku)、[FortoGraphy/prism-download-manager](https://github.com/FortoGraphy/prism-download-manager) |
| `typescript` | 8 | 3827 | [rociiu/talorys](https://github.com/rociiu/talorys)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[Lowbetweentrim/crypto-portfolio-tracker](https://github.com/Lowbetweentrim/crypto-portfolio-tracker) |
| `self-hosted` | 7 | 6871 | [marclou/mailcheap](https://github.com/marclou/mailcheap)、[rociiu/talorys](https://github.com/rociiu/talorys)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) |
| `llm` | 7 | 6448 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot)、[heqiangdiao-wq/AI-Cross-Border-Ecommerce-Agent-Toolkit](https://github.com/heqiangdiao-wq/AI-Cross-Border-Ecommerce-Agent-Toolkit)、[sahenjp/RustXNG](https://github.com/sahenjp/RustXNG) |
| `claude-skills` | 6 | 9708 | [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[UnderleveledBuilder/awesome-short-drama-skills](https://github.com/UnderleveledBuilder/awesome-short-drama-skills) |

**语言分布**：Rust 33 · Python 21 · TypeScript 18 · JavaScript 10 · Go 6 · HTML 5 · C++ 2 · Astro 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) · 🟢 窗口内 · 94.9 分

> 🤖 Open-source, local-first alternative to Grok Bot, OpenAI dots and Claude Duet. Your own AI bots on any model: GPT, Claude, Gemini, Grok, DeepSeek, Kimi, GLM and 70+ more through one Modelflare key. Reach them in the app, WeChat or Feishu; they remember you, work in the background, run commands and use your computer. Pay per use.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2729 | +2728 | +1 | 42 | 0 | Python | MIT | 10-27（10 天前） | 今天 |

- **近 14 天每天新增**：`······▁▇█▅▄▁▁·` 0 0 0 0 0 0 1 864 963 511 356 20 14 0
- **势头**：比前 7 天快 2728.0 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `ai-assistant` `chatbot` `claude` `computer-use` `deepseek` `desktop-app` `dsh` `electron` `feishu` `gemini` `gpt` `grok` `llm` `local-first` `modelflare` `multi-model` `openai-compatible` `personal-ai-agent` `wechat`
- **主页**：<https://anymodel.bot/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [benjitaylor/skills](https://github.com/benjitaylor/skills) · 🟢 窗口内 · 91.9 分

> Skills for AI coding agents.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2251 | +2113 | +139 | 161 | 0 | TypeScript | — | 10-26（11 天前） | 2 天前 |

- **近 14 天每天新增**：`······▃▇▇█▆▃▂·` 0 0 0 0 0 0 139 448 477 556 366 165 101 0
- **势头**：比前 7 天快 15.2 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) · 🟢 窗口内 · 91.1 分

> Agent skill: describe your stack in a sentence, get an architecture diagram with official logos

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1985 | +1985 | +0 | 90 | 0 | TypeScript | MIT | 11-01（6 天前） | 4 天前 |

- **近 14 天每天新增**：`·······█▇▄▂▂▂·` 0 0 0 0 0 0 0 723 594 331 145 96 96 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `architecture-diagram` `claude-code` `claude-skills` `codex` `diagram` `system-architecture` `tech-stack`
- **主页**：<stacks.caru.moe>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) · 🟢 窗口内 · 85.5 分

> UEFI pre-driver NVIDIA GPU unlocker for Windows Linux Hackintosh and all EFI-bootable system (Rust): SEC2 scrubber -> FWSEC/WPR2 -> signed Booter -> V67 four-write payload, read-back verified. Verified on most RTX 20 30 40 Series.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1984 | +1241 | +743 | 182 | 26 | Rust | GPL-2.0 | 10-26（11 天前） | 今天 |

- **近 14 天每天新增**：`▁▁▂▁▂▄██▆▄▃▃▃·` 5 7 51 30 34 168 448 419 307 196 114 101 104 0
- **势头**：比前 7 天快 1.7 倍，在加速
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50272846)）
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. 🆕 [sqlpxc/airhand](https://github.com/sqlpxc/airhand) · 🟢 窗口内 · 76.4 分

> High-performance remote desktop over QUIC · Rust + Tauri + React

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 627 | +582 | +45 | 103 | 0 | Rust | MIT | 10-31（6 天前） | 5 天前 |

- **近 14 天每天新增**：`······▃▅▃▅▁█▆·` 0 0 0 0 0 0 45 108 64 95 12 182 121 0
- **势头**：比前 7 天快 12.9 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [qybaihe/bla](https://github.com/qybaihe/bla) · 🟡 在降温 · 67.5 分

> 🛡️ BLA (Blind LLM Agents) — Adversarial defense shield that protects binaries, Electron apps, JS bundles, Python, and WebAssembly against AI reverse-engineering agents like REA. Poison -> Exhaust -> Hallucinate.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2596 | +853 | +1743 | 343 | 8 | TypeScript | MIT | 10-25（13 天前） | 今天 |

- **近 14 天每天新增**：`▁▁▂▁█▅▃▂▂▂▃▂▂·` 2 27 143 31 814 488 238 145 123 96 257 108 124 0
- **势头**：只有前 7 天的 49%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adversarial-ai` `claude-code` `cursor` `electron-security` `llm-security` `mcp` `mcp-server` `obfuscation` `reverse-engineering` `webassembly`
- **主页**：<https://bla.tools>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 7. [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) · 🟡 在降温 · 65 分

> Evidence-first genealogy skill for AI agents (Codex, Claude Code): church books, civil, military, deportation and repression records across the former USSR. Replies in your language.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2075 | +666 | +1408 | 206 | 1 | Python | MIT | 10-25（12 天前） | 今天 |

- **近 14 天每天新增**：`█▄▄▂▂▂▂▂▂▄▂▂▂·` 592 228 255 113 88 71 61 54 64 285 105 82 76 0
- **势头**：只有前 7 天的 47%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `archives` `claude-code` `codex` `family-history` `familysearch` `genealogy` `ussr`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [daveebbelaar/bama](https://github.com/daveebbelaar/bama) · 🟡 在降温 · 62.6 分

> BAMA: Build Any Mac App. Agent skills to research, clone, design, build, optimize, and test native macOS apps with Swift and SwiftUI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1647 | +521 | +1126 | 201 | 1 | Swift | MIT | 10-24（13 天前） | 1 天前 |

- **近 14 天每天新增**：`·▄██▆▅▅▇▄▃▂▂▂·` 0 121 265 251 183 152 154 228 111 64 51 36 31 0
- **势头**：只有前 7 天的 46%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-agents` `app-clone` `claude-code` `claude-code-plugin` `codex` `computer-use` `liquid-glass` `macos` `macos-app` `native-apps` `skills` `swift` `swiftdata` `swiftui`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) · 🟡 在降温 · 61.4 分

> A community-built phone app for Clean Your TV: clean up an Android TV from your phone. No laptop, no coding agent, nothing uninstalled.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1756 | +463 | +902 | 155 | 6117 | Kotlin | MIT | 10-21（16 天前） | 3 天前 |

- **近 14 天每天新增**：`█▅▅▄▄▃▄▄▄▃▃▃▃·` 243 133 150 114 88 79 95 92 101 75 66 73 56 0
- **势头**：只有前 7 天的 51%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adb` `android-tv` `debloat` `fire-tv` `google-tv` `launcher`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [ZiChuanLan/agent-purge](https://github.com/ZiChuanLan/agent-purge) · 🟡 在降温 · 60.6 分

> One persona, many coding agents. Replace or inject system prompts across codex, claude, opencode, grok, omp, hermes, pi, zcode - with a local web console.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1358 | +429 | +929 | 862 | 0 | JavaScript | MIT | 10-25（12 天前） | 今天 |

- **近 14 天每天新增**：`▅█▆▄▂▂▁▂▂▅▂▂▂·` 160 311 208 146 50 36 18 39 61 188 58 41 42 0
- **势头**：只有前 7 天的 46%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`claude-code` `codex` `coding-agent` `deepseek-harness` `harness` `omp` `opencode` `pi` `system-prompt`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) — 一天进了一半以上的 star，但 HN 上没火过
- [Lowbetweentrim/crypto-portfolio-tracker](https://github.com/Lowbetweentrim/crypto-portfolio-tracker) — 一天进了一半以上的 star，但 HN 上没火过
- [lexifina/global-law](https://github.com/lexifina/global-law) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 1864 | 306 | [Show HN: HackerBooks – HackerTube, but for books mentioned on HN](https://hackerbooks.org) | [HN](https://news.ycombinator.com/item?id=50326821) |
| 840 | 394 | [Show HN: Subvocal – Talk to your computer without making noise](https://news.ycombinator.com/item?id=50340088) | [HN](https://news.ycombinator.com/item?id=50340088) |
| 485 | 82 | [Show HN: HackerTV – HN's most-recommended Youtube videos as 24/7 TV channels](https://hackertv.org) | [HN](https://news.ycombinator.com/item?id=50346755) |
| 475 | 148 | [Show HN: Hacker Times, a New York Times-inspired version of Hacker News](https://hackertimes.ca/) | [HN](https://news.ycombinator.com/item?id=50346981) |
| 339 | 104 | [Show HN: Wikihack – HackerTube, but for Wikipedia articles mentioned on HN](https://wikihack.netlify.app) | [HN](https://news.ycombinator.com/item?id=50333339) |
| 325 | 55 | [Show HN: Warsaw in voxels – An interactive 3D map of the city centre](https://p.migdal.pl/warsaw-vibe-voxel/) | [HN](https://news.ycombinator.com/item?id=50339221) |
| 320 | 97 | [Show HN: OmniDiff – Opensource, super fast, content aware Git difftool, in Rust](https://github.com/ivankovic/omnidiff) | [HN](https://news.ycombinator.com/item?id=50325253) |
| 272 | 29 | [Show HN: A decent text-to-image model trained for ~$20K (Apache 2.0 Weights)](https://www.linum.ai/field-notes/pjit-21k) | [HN](https://news.ycombinator.com/item?id=50368208) |
| 254 | 39 | [Show HN: After a decade of reversing, I got co-op working in DOS Wing Commander](https://fireflyk64.github.io/wcmulti/) | [HN](https://news.ycombinator.com/item?id=50369895) |
| 238 | 57 | [Show HN: I've updated my Linux System Call website and API](https://syscall.sh/) | [HN](https://news.ycombinator.com/item?id=50334704) |
| 185 | 25 | [Show HN: HackerHack – HackerBooks but for Posts Posted on HN](https://news.ycombinator.com/) | [HN](https://news.ycombinator.com/item?id=50333877) |
| 169 | 30 | [Show HN: Firenook – Firebase emulators in Rust: 40× faster writes, 10× less RAM](https://firenook.dev/) | [HN](https://news.ycombinator.com/item?id=50378643) |
| 127 | 69 | [Show HN: Uncracked City, detective game where you question LLM suspects that lie](https://uncracked.city) | [HN](https://news.ycombinator.com/item?id=50358352) |
| 117 | 83 | [Show HN: I built a tool that prices a pre-built PC part by part](https://pcdealcheck.com/) | [HN](https://news.ycombinator.com/item?id=50366929) |
| 109 | 6 | [Show HN: A language model that lives in a boot sector](https://github.com/kerlenton/bootgpt) | [HN](https://news.ycombinator.com/item?id=50315782) |
| 107 | 30 | [Show HN: I rebuilt my old canvas 3D library as a small WebGL 2 library – phoria2](https://kevs3d.co.uk/phoria2/) | [HN](https://news.ycombinator.com/item?id=50314508) |
| 104 | 36 | [Show HN: Kairos – Open-source risk and fraud decisioning platform](https://github.com/finic-ai/kairos) | [HN](https://news.ycombinator.com/item?id=50358314) |
| 93 | 81 | [Show HN: NES Contra (1987) port (ASM –> C and then C –> WebAssembly)](https://epoyraz.github.io/nes-contra-us/) | [HN](https://news.ycombinator.com/item?id=50319169) |
| 90 | 34 | [Show HN: Stroq – a local audit of what your coding agent did and why](https://github.com/AGGIB/Stroq) | [HN](https://news.ycombinator.com/item?id=50380704) |
| 72 | 54 | [Show HN: I built a little browser game to practice Vim commands](https://hjkl.duy.run) | [HN](https://news.ycombinator.com/item?id=50347552) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 183 | [VibeVoice Technical Report](https://huggingface.co/papers/2508.19205) | VibeVoice synthesizes long-form multi-speaker speech using next-token diffusion and a highly efficient continuous speech tokenizer, achievin… | [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice) 56486★ |
| 162 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 121047★ |
| 63 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 47071★ |
| 13 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 4899★ |
| 67 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 22948★ |
| 110 | [FreeToken: Efficient Edge-Native MoE Serving with Bandwidth-Adaptive Execution](https://huggingface.co/papers/2608.16157) | FreeToken is an edge-native Mixture-of-Experts serving system that dynamically maps computation and model state onto heterogeneous local har… | [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken) 16777★ |
| 102 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 30776★ |
| 17 | [VisSearch-Bench: Evaluating Long Horizon Visual Search in Multimodal Agents](https://huggingface.co/papers/2611.04894) | VisSearch-Bench evaluates multimodal agents on visually intensive search tasks that require integrating visual context with external informa… | 💡 [antins-labs/VisSearch-Bench-v1](https://github.com/antins-labs/VisSearch-Bench-v1) 57★ |
| 45 | [WeVisOne-VL: Unified Visual Perception from Objects to Pixels](https://huggingface.co/papers/2610.31329) | WeVisOne-VL unifies object-level and pixel-level visual perception via structured token prediction, supporting detection, localization, coun… | [Tencent/WeVisOne-VL](https://github.com/Tencent/WeVisOne-VL) 1048★ |
| 39 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 35511★ |
| 48 | [Democratizing Robot-Use Agents: A Unified Harness with Open Models](https://huggingface.co/papers/2611.01560) | Uni-robot-agent enables open-weight robot-use agents to surpass proprietary models in zero-shot manipulation and suggests joint development… | 💡 [Open-RUA/uni-robot-agent](https://github.com/Open-RUA/uni-robot-agent) 264★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 35512★ |
| 86 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 92827★ |
| 1 | [Differentiable Data Augmentation with Kornia](https://huggingface.co/papers/2011.09832) | This paper reviews the Kornia differentiable data augmentation module for both 2D and 3D tensors, integrating with PyTorch's autograd and op… | [arraiyopensource/kornia](https://github.com/arraiyopensource/kornia) 12348★ |
| 37 | [TailSteer: Trajectory-Tail Steering for Drift-Resistant Multi-turn Image Editing](https://huggingface.co/papers/2611.06741) | TailSteer, a final-stage training framework, reduces cumulative visual drift in multi-turn editing by keeping early denoising dynamics close… | 💡 [Lyricccco/tailsteer](https://github.com/Lyricccco/tailsteer) 37★ |
| 156 | [ARIS: Autonomous Research via Adversarial Multi-Agent Collaboration](https://huggingface.co/papers/2605.03042) | ARIS is an open-source research harness that uses cross-model adversarial collaboration to ensure reliable long-term research outcomes throu… | [wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) 18803★ |
| 55 | [Harness-S: Learning from Sibling Harnesses for Generalizable Agent Training](https://huggingface.co/papers/2611.04277) | A selective harness-rescue training method uses specialized sibling harnesses to replace failed reinforcement learning rollouts and transfer… | 💡 [DeepExperience/Harness-S](https://github.com/DeepExperience/Harness-S) 53★ |
| 29 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 9111★ |
| 19 | [SpecPilot: Autonomous Algorithm Discovery and Systems Optimization for Speculative Decoding](https://huggingface.co/papers/2611.02501) | SpecPilot autonomously discovers deployment-specific algorithms and system optimizations to maximize speculative decoding speedups across di… | 💡 [StargazerX0/SpecPilot](https://github.com/StargazerX0/SpecPilot) 171★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 48 | [deepseek v4 pro qwen3.5 heretic](https://huggingface.co/xtools-at/DeepSeek-V4-Pro-Qwen3.5-9B-UNCENSORED-heretic) | text-generation | 116 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 49 | 1 | [Libghostty 1.0](https://mitchellh.com/writing/libghostty-1-0) | `c` `release` `zig` | [讨论](https://lobste.rs/s/0ouxwf/libghostty_1_0) |
| 53 | 9 | [Making musl and proprietary NVIDIA drivers work together](https://chimera-linux.org/news/2026/11/musl-nvidia.html) | `linux` | [讨论](https://lobste.rs/s/hvxjbb/making_musl_proprietary_nvidia_drivers) |
| 17 | 22 | [The MustCreate Pattern for Go Tests](https://mtlynch.io/notes/go-must-create-pattern/) | `go` `testing` | [讨论](https://lobste.rs/s/i96uyr/mustcreate_pattern_for_go_tests) |
| 23 | 2 | [The Port That Does Not Exist](https://acid.vegas/blog/the-port-that-does-not-exist/) | `networking` | [讨论](https://lobste.rs/s/osqswf/port_does_not_exist) |
| 17 | 4 | [Inside GitHub's new Git storage architecture](https://github.blog/engineering/architecture-optimization/inside-githubs-new-git-storage-architecture/) | `distributed` `vcs` | [讨论](https://lobste.rs/s/y3hvme/inside_github_s_new_git_storage) |
| 15 | 1 | [Hacking the meta ray-ban smartglasses](https://p0pcycle.com/2026/11/06/hacking-the-meta-ray-ban-smartglasses/) | `security` | [讨论](https://lobste.rs/s/xhrab6/hacking_meta_ray_ban_smartglasses) |
| 18 | 3 | [Upgrading NetBSD from 11.0 to 11.1](https://www.dwarmstrong.org/netbsd-upgrade/) | `netbsd` | [讨论](https://lobste.rs/s/0agusd/upgrading_netbsd_from_11_0_11_1) |
| 24 | 43 | [What are you doing this weekend?](https://lobste.rs/s/jmdchp) | `ask` `programming` | [讨论](https://lobste.rs/s/jmdchp/what_are_you_doing_this_weekend) |
| 172 | 41 | [sshhole](https://sshhole.com/) | `linux` `security` | [讨论](https://lobste.rs/s/oq5pem/sshhole) |
| 111 | 9 | [Software Line Specialist](https://lovro-bikic.github.io/software-line-specialist/) | `satire` | [讨论](https://lobste.rs/s/yoywed/software_line_specialist) |
| 10 | 0 | [Nondeterminism in Futhark](https://futhark-lang.org/blog/2026-11-04-nondeterminism.html) | `apl` `plt` | [讨论](https://lobste.rs/s/4lgvnf/nondeterminism_futhark) |
| 5 | 0 | [How hard could implementing DTLS 1.3 possibly be?](https://joturk.net/posts/dtls) | `security` | [讨论](https://lobste.rs/s/lssm6h/how_hard_could_implementing_dtls_1_3) |
| 11 | 0 | [From Linux to Wikipedia: How Volunteers Build the Internet](https://thereader.mitpress.mit.edu/from-linux-to-wikipedia-how-volunteers-build-the-internet/) | `linux` | [讨论](https://lobste.rs/s/lzuqfr/from_linux_wikipedia_how_volunteers) |
| 45 | 2 | [Clojure Distilled](https://yogthos.net/ClojureDistilled.html) | `lisp` | [讨论](https://lobste.rs/s/dxno99/clojure_distilled) |
| 15 | 0 | [Pushing the Limits with getaddrinfo](https://acid.vegas/blog/pushing-the-limits-with-getaddrinfo/) | `networking` `security` | [讨论](https://lobste.rs/s/5cwnpu/pushing_limits_with_getaddrinfo) |
| 9 | 0 | [How we continuously validate formal specifications in production](https://www.datadoghq.com/blog/engineering/continuous-formal-spec-validation/) | `formalmethods` `testing` | [讨论](https://lobste.rs/s/gzdimd/how_we_continuously_validate_formal) |
| 7 | 1 | [Firststeps in bare-metal programming using UEFI](https://kevinboone.me/efitest_index.html) | `osdev` | [讨论](https://lobste.rs/s/id3f9d/firststeps_bare_metal_programming_using) |
| 2 | 1 | [Exploring Janet and the httpf web framework](https://nick.gs/blog/2026-11/exploring-janet-and-the-httpf-web-framework/) | `lisp` `web` | [讨论](https://lobste.rs/s/ydzlvp/exploring_janet_httpf_web_framework) |
| 7 | 1 | [UploadYourRam.org](https://uploadyourram.org/) | `satire` | [讨论](https://lobste.rs/s/miazwz/uploadyourram_org) |
| 44 | 2 | [X-87 - DOS 256 bytes](https://www.onirom.fr/wiki/codegolf/x-87/) | `art` `assembly` `concatenative` | [讨论](https://lobste.rs/s/q0ld7f/x_87_dos_256_bytes) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 67 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 39 | 26 | 66% | — |
| 🔴 先核对 | 20 | 9 | 45% | — |
| 🟡 在降温 | 5 | 0 | 0% | — |
| 🔵 已被发现 | 3 | 1 | 33% | — |
| 🟢 窗口内 | 11 | 6 | 54% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [EthanArbuckle/fairplay-decrypt](https://github.com/EthanArbuckle/fairplay-decrypt) | 2026-10-24 | 🚀 爆发 | 1644 | 2370 | 25 | 没起来 |
| [Revivedx/SavageWindRecomp](https://github.com/Revivedx/SavageWindRecomp) | 2026-10-24 | 🚀 爆发 | 1086 | 3349 | 0 | ✅ 起来了 |
| [wesbos/3d-model-anything](https://github.com/wesbos/3d-model-anything) | 2026-10-24 | 🚀 爆发 | 1173 | 2825 | 0 | ✅ 起来了 |
| [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | 2026-10-24 | 🔴 先核对 | 1087 | 2599 | 3 | ✅ 起来了 |

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
