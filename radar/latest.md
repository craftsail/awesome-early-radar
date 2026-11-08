# early-radar 选题雷达 · 2026-11-08

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 101 个，细查前 20 个 · 比上次 = 和 2026-11-07 那次比 · 生成于 2026-11-08 05:39 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 0 个 · Show HN ✅ 24 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 5 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 4 个 · 🟡 在降温 10 个 · 🔵 已被发现 0 个 · 💤 不活跃 1 个 · 🔴 先核对 5 个
- **今天新出现 2 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [storytold/craft-anything](https://github.com/storytold/craft-anything) 平均每天 +2773，见 [爆发](#爆发)
- **复盘**：🚀 爆发 28/41 · 🔴 先核对 10/21 · 🟡 在降温 0/5 · 🔵 已被发现 1/3 · 🟢 窗口内 6/13（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [benjitaylor/skills](https://github.com/benjitaylor/skills) — Skills for AI coding agents.（近 7 天 +1939，比前 7 天快 3.3 倍，在加速）
  - [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) — 🤖 Open-source, local-first alternative to Grok Bot, OpenAI d…（近 7 天 +1871，比前 7 天快 2.2 倍，在加速）
  - [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) — Agent skill: describe your stack in a sentence, get an archi…（近 7 天 +1356，比前 7 天快 1.9 倍，在加速）
- **趋势信号**：带 `ai-agents` topic 的新仓库这批里有 24 个（star 合计 24535），代表：[morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering)、[reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：3 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: HackerBooks – HackerTube, but for books mentioned on HN](https://hackerbooks.org) — 1867 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| ✅ [storytold/craft-anything](https://github.com/storytold/craft-anything) | 21120 | 2773 | +2528 | 7.6 | [5](https://news.ycombinator.com/item?id=50377361) | craft anything · storytold craft anything · artcraft craft anything | Craft Anything: understand how any software works, and craft… |
| [deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) | 20915 | 2668 | +534 | 7.8 | [11](https://news.ycombinator.com/item?id=50316116) | dsh superagent prototype · deepseek-ai dsh superagent prototype · deepseek dsh superagent prototype | Towards a More Autonomous Agent System |
| [zortos293/Lichii](https://github.com/zortos293/Lichii) | 5927 | 776 | +1730 | 7.6 | — | lichii · zortos293 lichii · zortos lichii | VERY experimental Nintendo Switch 2 emulator |
| 🆕 [NotRexed/Hookshot](https://github.com/NotRexed/Hookshot) | 2058 | 756 | +1649 | 2.7 | [1](https://news.ycombinator.com/item?id=50410236) | hookshot · notrexed hookshot | A Native Recompilation Of The Legend Of Zelda: Ocarina Of Ti… |
| [ccch1mneyyy/dsh-Go](https://github.com/ccch1mneyyy/dsh-Go) | 14817 | 1066 | +1633 | 13.9 | — | dsh go · ccch1mneyyy dsh go · chimney dsh go | dsh-go — DeepSeek Harness 装进口袋：手机本机运行，也能遥控你的电脑。 |
| [heydamir/unslop](https://github.com/heydamir/unslop) | 11461 | 1196 | +603 | 9.6 | — | unslop · heydamir unslop · damir unslop | A Claude skill that turns vibecoded, AI-looking UI into a de… |
| [JenkinWoo/sheeridVerify](https://github.com/JenkinWoo/sheeridVerify) | 1747 | 949 | +687 | 1.8 | — | sheeridverify · jenkinwoo sheeridverify |  |
| [worldonlyu/Google_AI_Pro_2Year_ZeroCost_Auto](https://github.com/worldonlyu/Google_AI_Pro_2Year_ZeroCost_Auto) | 3094 | 856 | +167 | 3.6 | — | google ai pro 2year zerocost auto · worldonlyu google ai pro 2year zerocost auto | Google_AI_Pro_2Year_ZeroCost_Auto |
| [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop) | 3993 | 815 | +243 | 4.9 | — | agent autoloop · kkkkhazix agent autoloop · khazix agent autoloop | 让你的命令行 Agent 在后台自己接活、自己跟进到底；平时不烦你，遇到拿不准的事才发卡片找你拍板。 |
| [wangzan101/Mika](https://github.com/wangzan101/Mika) | 7643 | 794 | +197 | 9.6 | — | mika · wangzan101 mika · wangzan mika | An on-device AI agent for Android that operates apps and the… |
| [Minireel/HGhub](https://github.com/Minireel/HGhub) | 2466 | 530 | +662 | 4.6 | — | hghub · minireel hghub | YellowFruit third-party client |
| [patch-gg/pixelfx](https://github.com/patch-gg/pixelfx) | 5890 | 658 | +237 | 9 | — | pixelfx · patch-gg pixelfx · patch pixelfx | 244 pixel art effects, every one a small piece of code. Plus… |
| 🆕 [sostenesfreitas/ocarina-recomp](https://github.com/sostenesfreitas/ocarina-recomp) | 841 | 646 | — | 1.3 | — | ocarina recomp · sostenesfreitas ocarina recomp | Ocarina of Time running natively on Windows, no emulator. Bu… |
| [valentderah/totk-pc-recomp](https://github.com/valentderah/totk-pc-recomp) | 5733 | 590 | +263 | 9.7 | — | totk pc recomp · valentderah totk pc recomp · valiantsin totk pc recomp | Static recompilation of The Legend of Zelda: Tears of the Ki… |
| 🆕 [Th0rgal/satmux](https://github.com/Th0rgal/satmux) | 573 | 573 | — | 1 | — | satmux · th0rgal satmux · thomas satmux | Accelerate high-latency GEO inflight Wi-Fi via warm BBR TCP… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 90.8 | 🟢 窗口内 | [benjitaylor/skills](https://github.com/benjitaylor/skills) | TypeScript | 2525 | +274 | +1939 | +587 | `·····▃▇▇█▆▃▂▄·` | 12 | — | — |
| 2 | 90.4 | 🟢 窗口内 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) | Python | 2735 | +6 | +1871 | +864 | `·····▁▇█▅▄▁▁▁·` | 11 | — | — |
| 3 | 86.6 | 🟢 窗口内 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | TypeScript | 2079 | +94 | +1356 | +723 | `······█▇▄▂▂▂▂·` | 7 | — | — |
| 4 | 77.3 | 🟢 窗口内 | [sqlpxc/airhand](https://github.com/sqlpxc/airhand) | Rust | 781 | +154 | +628 | +153 | `·····▃▅▃▅▁█▆▇·` | 7 | — | — |
| 5 | 69.8 | 🟡 在降温 | [qybaihe/bla](https://github.com/qybaihe/bla) | TypeScript | 2960 | +364 | +1072 | +1886 | `▁▂▁█▅▃▂▂▂▃▂▂▄·` | 14 | — | — |
| 6 | 68.1 | 🟡 在降温 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 2069 | +85 | +907 | +1157 | `▁▂▁▂▄██▆▄▃▃▃▂·` | 12 | [2](https://news.ycombinator.com/item?id=50272846) | — |
| 7 | 65.3 | 🟡 在降温 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 2150 | +75 | +687 | +870 | `▇▇▄▃▃▂▂▃█▄▃▃▃·` | 13 | — | — |
| 8 | 61.4 | 🟡 在降温 | [ZiChuanLan/agent-purge](https://github.com/ZiChuanLan/agent-purge) | JavaScript | 1432 | +74 | +464 | +808 | `█▆▄▂▂▁▂▂▅▂▂▂▃·` | 13 | — | — |
| 9 | 57.8 | 🟡 在降温 | [daveebbelaar/bama](https://github.com/daveebbelaar/bama) | Swift | 1676 | +29 | +322 | +1354 | `▄██▆▅▅▇▄▃▂▂▂▂·` | 14 | — | — |
| 10 | 53 | 🟡 在降温 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2639 | +40 | +199 | +482 | `▆█▄▃▃▃▃▂▂▂▃▄▃·` | 17 | [3](https://news.ycombinator.com/item?id=50207695) | — |
| 11 | 52.1 | 🟡 在降温 | [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) | TypeScript | 1988 | +11 | +182 | +1805 | `·██▃▂▂▂▂▁▁▁▁▁·` | 17 | — | — |
| 12 | 52 | 🟡 在降温 | [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | TypeScript | 1863 | +12 | +181 | +1594 | `█▄▃▂▁▁▂▂▁▁▁▁▁·` | 13 | — | — |
| 13 | 51.9 | 🟡 在降温 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | Rust | 2053 | +11 | +179 | +1423 | `▆█▂▁▂▁▂▁▁▁▁▁▁·` | 19 | [4](https://news.ycombinator.com/item?id=50340534) | — |
| 14 | 45.6 | 🟡 在降温 | [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) | Python | 1757 | +10 | +95 | +779 | `█▃▂▂▃▃▂▁▁▁▁▁▁·` | 16 | — | — |
| 15 | 43 | 🔴 先核对 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Rust | 1287 | +92 | +1287 | +0 | `········▁█▃▂▂·` | 6 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 16 | 41.4 | 🆕 🔴 先核对 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode) | Python | 996 | +503 | +996 | +0 | `·········▅▂▂█·` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 17 | 41 | 🆕 🔴 先核对 | [voyager-so/vork](https://github.com/voyager-so/vork) | Rust | 935 | +466 | +935 | +0 | `···········█▇·` | 2 | [8](https://news.ycombinator.com/item?id=50396650) | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 36.9 | 💤 不活跃 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 2489 | +29 | +468 | +339 | `▄▅▃▃▂▂▅██▅▃▃▃·` | 20 | — | — |
| 19 | 36.3 | 🔴 先核对 | [Lowbetweentrim/crypto-portfolio-tracker](https://github.com/Lowbetweentrim/crypto-portfolio-tracker) | Python | 426 | +1 | +426 | +0 | `···········█▁·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 27.2 | 🔴 先核对 | [lexifina/global-law](https://github.com/lexifina/global-law) | HTML | 1859 | +19 | +231 | +1628 | `···▂█▃▂▂▁▁▁▁▁·` | 10 | [1](https://news.ycombinator.com/item?id=50283329) | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 700 | 30 | 46387 | [qybaihe/bla](https://github.com/qybaihe/bla)、[benjitaylor/skills](https://github.com/benjitaylor/skills)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) |
| `mcp` | 304 | 30 | 38009 | [qybaihe/bla](https://github.com/qybaihe/bla)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) |
| `rust` | 249 | 30 | 34824 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[opengeos/RustGIS](https://github.com/opengeos/RustGIS)、[oscar-soirey/Raven](https://github.com/oscar-soirey/Raven) |
| `local-first` | 82 | 30 | 13998 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot)、[yjid/kensaku](https://github.com/yjid/kensaku)、[s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `ai-agents` | 24 | 24535 | [morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering)、[reacher-z/Awesome-REA](https://github.com/reacher-z/Awesome-REA)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama) |
| `claude-code` | 20 | 28518 | [qybaihe/bla](https://github.com/qybaihe/bla)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) |
| `agent-skills` | 15 | 23702 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) |
| `codex` | 14 | 18973 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) |
| `mcp-server` | 11 | 14805 | [qybaihe/bla](https://github.com/qybaihe/bla)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `macos` | 10 | 8846 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[Zfinix/eleven](https://github.com/Zfinix/eleven) |
| `windows` | 10 | 7848 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[yjid/kensaku](https://github.com/yjid/kensaku)、[yzlin286-wq/Deepscient](https://github.com/yzlin286-wq/Deepscient) |
| `llm` | 8 | 6677 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot)、[heqiangdiao-wq/AI-Cross-Border-Ecommerce-Agent-Toolkit](https://github.com/heqiangdiao-wq/AI-Cross-Border-Ecommerce-Agent-Toolkit)、[sahenjp/RustXNG](https://github.com/sahenjp/RustXNG) |
| `typescript` | 8 | 3952 | [rociiu/talorys](https://github.com/rociiu/talorys)、[shinyobjectz/raea](https://github.com/shinyobjectz/raea)、[SouravBeraAkaSpeed/xiryn](https://github.com/SouravBeraAkaSpeed/xiryn) |
| `claude-skills` | 7 | 12400 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) |
| `self-hosted` | 7 | 6967 | [marclou/mailcheap](https://github.com/marclou/mailcheap)、[rociiu/talorys](https://github.com/rociiu/talorys)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) |
| `open-source` | 7 | 4660 | [yjid/kensaku](https://github.com/yjid/kensaku)、[alexgaoth/awesome-reverse-engineered](https://github.com/alexgaoth/awesome-reverse-engineered)、[FortoGraphy/prism-download-manager](https://github.com/FortoGraphy/prism-download-manager) |

**语言分布**：Rust 34 · Python 23 · TypeScript 18 · JavaScript 10 · Go 5 · HTML 5 · Astro 1 · C 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [benjitaylor/skills](https://github.com/benjitaylor/skills) · 🟢 窗口内 · 90.8 分

> Skills for AI coding agents.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2525 | +1939 | +587 | 179 | 0 | TypeScript | — | 10-26（12 天前） | 3 天前 |

- **近 14 天每天新增**：`·····▃▇▇█▆▃▂▄·` 0 0 0 0 0 139 448 476 556 366 165 106 270 0
- **势头**：比前 7 天快 3.3 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) · 🟢 窗口内 · 90.4 分

> 🤖 Open-source, local-first alternative to Grok Bot, OpenAI dots and Claude Duet. Your own AI bots on any model: GPT, Claude, Gemini, Grok, DeepSeek, Kimi, GLM and 70+ more through one Modelflare key. Reach them in the app, WeChat or Feishu; they remember you, work in the background, run commands and use your computer. Pay per use.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2735 | +1871 | +864 | 43 | 0 | Python | MIT | 10-27（11 天前） | 今天 |

- **近 14 天每天新增**：`·····▁▇█▅▄▁▁▁·` 0 0 0 0 0 1 863 961 511 355 20 16 8 0
- **势头**：比前 7 天快 2.2 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `ai-assistant` `chatbot` `claude` `computer-use` `deepseek` `desktop-app` `dsh` `electron` `feishu` `gemini` `gpt` `grok` `llm` `local-first` `modelflare` `multi-model` `openai-compatible` `personal-ai-agent` `wechat`
- **主页**：<https://anymodel.bot/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) · 🟢 窗口内 · 86.6 分

> Agent skill: describe your stack in a sentence, get an architecture diagram with official logos

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2079 | +1356 | +723 | 100 | 2 | TypeScript | MIT | 11-01（7 天前） | 5 天前 |

- **近 14 天每天新增**：`······█▇▄▂▂▂▂·` 0 0 0 0 0 0 723 594 330 145 96 110 81 0
- **势头**：比前 7 天快 1.9 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `architecture-diagram` `claude-code` `claude-skills` `codex` `diagram` `system-architecture` `tech-stack`
- **主页**：<stacks.caru.moe>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [sqlpxc/airhand](https://github.com/sqlpxc/airhand) · 🟢 窗口内 · 77.3 分

> High-performance remote desktop over QUIC · Rust + Tauri + React

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 781 | +628 | +153 | 103 | 0 | Rust | MIT | 10-31（7 天前） | 今天 |

- **近 14 天每天新增**：`·····▃▅▃▅▁█▆▇·` 0 0 0 0 0 45 108 64 95 12 182 121 154 0
- **势头**：比前 7 天快 4.1 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [qybaihe/bla](https://github.com/qybaihe/bla) · 🟡 在降温 · 69.8 分

> 🛡️ BLA (Blind LLM Agents) — Adversarial defense shield that protects binaries, Electron apps, JS bundles, Python, and WebAssembly against AI reverse-engineering agents like REA. Poison -> Exhaust -> Hallucinate.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2960 | +1072 | +1886 | 374 | 7 | TypeScript | MIT | 10-25（14 天前） | 今天 |

- **近 14 天每天新增**：`▁▂▁█▅▃▂▂▂▃▂▂▄·` 27 143 31 814 488 238 145 123 96 257 108 146 342 0
- **势头**：只有前 7 天的 57%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adversarial-ai` `claude-code` `cursor` `electron-security` `llm-security` `mcp` `mcp-server` `obfuscation` `reverse-engineering` `webassembly`
- **主页**：<https://bla.tools>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 6. [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) · 🟡 在降温 · 68.1 分

> UEFI pre-driver NVIDIA GPU unlocker for Windows Linux Hackintosh and all EFI-bootable system (Rust): SEC2 scrubber -> FWSEC/WPR2 -> signed Booter -> V67 four-write payload, read-back verified. Verified on most RTX 20 30 40 Series.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2069 | +907 | +1157 | 189 | 29 | Rust | GPL-2.0 | 10-26（12 天前） | 今天 |

- **近 14 天每天新增**：`▁▂▁▂▄██▆▄▃▃▃▂·` 7 51 30 34 168 448 419 307 196 114 101 114 75 0
- **势头**：只有前 7 天的 78%，在减速
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50272846)）
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 7. [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) · 🟡 在降温 · 65.3 分

> Evidence-first genealogy skill for AI agents (Codex, Claude Code): church books, civil, military, deportation and repression records across the former USSR. Replies in your language.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2150 | +687 | +870 | 218 | 1 | Python | MIT | 10-25（13 天前） | 今天 |

- **近 14 天每天新增**：`▇▇▄▃▃▂▂▃█▄▃▃▃·` 228 255 113 88 71 61 54 64 285 105 82 81 70 0
- **势头**：只有前 7 天的 79%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `archives` `claude-code` `codex` `family-history` `familysearch` `genealogy` `ussr`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 8. [ZiChuanLan/agent-purge](https://github.com/ZiChuanLan/agent-purge) · 🟡 在降温 · 61.4 分

> One persona, many coding agents. Replace or inject system prompts across codex, claude, opencode, grok, omp, hermes, pi, zcode - with a local web console.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1432 | +464 | +808 | 894 | 1 | JavaScript | MIT | 10-25（13 天前） | 今天 |

- **近 14 天每天新增**：`█▆▄▂▂▁▂▂▅▂▂▂▃·` 311 208 146 50 36 18 39 61 188 58 41 49 67 0
- **势头**：只有前 7 天的 57%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`claude-code` `codex` `coding-agent` `deepseek-harness` `harness` `omp` `opencode` `pi` `system-prompt`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [daveebbelaar/bama](https://github.com/daveebbelaar/bama) · 🟡 在降温 · 57.8 分

> BAMA: Build Any Mac App. Agent skills to research, clone, design, build, optimize, and test native macOS apps with Swift and SwiftUI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1676 | +322 | +1354 | 205 | 1 | Swift | MIT | 10-24（14 天前） | 2 天前 |

- **近 14 天每天新增**：`▄██▆▅▅▇▄▃▂▂▂▂·` 121 265 251 183 152 154 228 111 64 51 36 34 26 0
- **势头**：只有前 7 天的 24%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-agents` `app-clone` `claude-code` `claude-code-plugin` `codex` `computer-use` `liquid-glass` `macos` `macos-app` `native-apps` `skills` `swift` `swiftdata` `swiftui`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [xevrion/hatchzip](https://github.com/xevrion/hatchzip) · 🟡 在降温 · 53 分

> HatchZip is a free, open-source archive extractor for Windows, macOS and Linux that extracts ZIP, 7z, RAR, tar and split archives in place, so it needs free space for the extracted files only. Desktop app and CLI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2639 | +199 | +482 | 84 | 20 | Rust | Apache-2.0 | 10-21（17 天前） | 2 天前 |

- **近 14 天每天新增**：`▆█▄▃▃▃▃▂▂▂▃▄▃·` 101 144 70 49 31 39 48 24 21 17 45 54 38 0
- **势头**：只有前 7 天的 41%，在减速
- **HN**：发过 1 次，最高 3 分（[讨论](https://news.ycombinator.com/item?id=50207695)）
- **topics**：`7z` `7zip` `archive` `archive-extractor` `cli` `crash-safe` `disk-space` `extract` `extractor` `gui` `in-place` `linux` `macos` `rar` `rust` `tar` `unrar` `unzip` `windows` `zip`
- **主页**：<https://hatchzip.dev>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) — 一天进了一半以上的 star，但 HN 上没火过
- [sarpstar/cinecode](https://github.com/sarpstar/cinecode) — 一天进了一半以上的 star，但 HN 上没火过
- [voyager-so/vork](https://github.com/voyager-so/vork) — 一天进了一半以上的 star，但 HN 上没火过
- [Lowbetweentrim/crypto-portfolio-tracker](https://github.com/Lowbetweentrim/crypto-portfolio-tracker) — 一天进了一半以上的 star，但 HN 上没火过
- [lexifina/global-law](https://github.com/lexifina/global-law) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 1867 | 306 | [Show HN: HackerBooks – HackerTube, but for books mentioned on HN](https://hackerbooks.org) | [HN](https://news.ycombinator.com/item?id=50326821) |
| 842 | 395 | [Show HN: Subvocal – Talk to your computer without making noise](https://news.ycombinator.com/item?id=50340088) | [HN](https://news.ycombinator.com/item?id=50340088) |
| 488 | 83 | [Show HN: HackerTV – HN's most-recommended Youtube videos as 24/7 TV channels](https://hackertv.org) | [HN](https://news.ycombinator.com/item?id=50346755) |
| 475 | 148 | [Show HN: Hacker Times, a New York Times-inspired version of Hacker News](https://hackertimes.ca/) | [HN](https://news.ycombinator.com/item?id=50346981) |
| 339 | 104 | [Show HN: Wikihack – HackerTube, but for Wikipedia articles mentioned on HN](https://wikihack.netlify.app) | [HN](https://news.ycombinator.com/item?id=50333339) |
| 325 | 55 | [Show HN: Warsaw in voxels – An interactive 3D map of the city centre](https://p.migdal.pl/warsaw-vibe-voxel/) | [HN](https://news.ycombinator.com/item?id=50339221) |
| 321 | 97 | [Show HN: OmniDiff – Opensource, super fast, content aware Git difftool, in Rust](https://github.com/ivankovic/omnidiff) | [HN](https://news.ycombinator.com/item?id=50325253) |
| 282 | 29 | [Show HN: A decent text-to-image model trained for ~$20K (Apache 2.0 Weights)](https://www.linum.ai/field-notes/pjit-21k) | [HN](https://news.ycombinator.com/item?id=50368208) |
| 255 | 40 | [Show HN: After a decade of reversing, I got co-op working in DOS Wing Commander](https://fireflyk64.github.io/wcmulti/) | [HN](https://news.ycombinator.com/item?id=50369895) |
| 238 | 58 | [Show HN: I've updated my Linux System Call website and API](https://syscall.sh/) | [HN](https://news.ycombinator.com/item?id=50334704) |
| 209 | 46 | [Show HN: Coldframe, a honeypot that poses as a supermarket fridge controller](https://github.com/hedgerow-dev/coldframe) | [HN](https://news.ycombinator.com/item?id=50406292) |
| 185 | 25 | [Show HN: HackerHack – HackerBooks but for Posts Posted on HN](https://news.ycombinator.com/) | [HN](https://news.ycombinator.com/item?id=50333877) |
| 170 | 30 | [Show HN: Firenook – Firebase emulators in Rust: 40× faster writes, 10× less RAM](https://firenook.dev/) | [HN](https://news.ycombinator.com/item?id=50378643) |
| 127 | 69 | [Show HN: Uncracked City, detective game where you question LLM suspects that lie](https://uncracked.city) | [HN](https://news.ycombinator.com/item?id=50358352) |
| 119 | 85 | [Show HN: I built a tool that prices a pre-built PC part by part](https://pcdealcheck.com/) | [HN](https://news.ycombinator.com/item?id=50366929) |
| 105 | 36 | [Show HN: Kairos – Open-source risk and fraud decisioning platform](https://github.com/finic-ai/kairos) | [HN](https://news.ycombinator.com/item?id=50358314) |
| 92 | 34 | [Show HN: Stroq – a local audit of what your coding agent did and why](https://github.com/AGGIB/Stroq) | [HN](https://news.ycombinator.com/item?id=50380704) |
| 81 | 40 | [Show HN: Waymark – A workflow engine that compiles jobs instead of replaying](https://github.com/piercefreeman/waymark) | [HN](https://news.ycombinator.com/item?id=50379221) |
| 72 | 57 | [Show HN: I built a little browser game to practice Vim commands](https://hjkl.duy.run) | [HN](https://news.ycombinator.com/item?id=50347552) |
| 71 | 26 | [Show HN: HackerChurn – which SaaS tools HN wants to cancel](https://hissingkitty.com/hacker-churn) | [HN](https://news.ycombinator.com/item?id=50353386) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 184 | [VibeVoice Technical Report](https://huggingface.co/papers/2508.19205) | VibeVoice synthesizes long-form multi-speaker speech using next-token diffusion and a highly efficient continuous speech tokenizer, achievin… | [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice) 56706★ |
| 162 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 121221★ |
| 63 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 47250★ |
| 14 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 4955★ |
| 67 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 23053★ |
| 111 | [FreeToken: Efficient Edge-Native MoE Serving with Bandwidth-Adaptive Execution](https://huggingface.co/papers/2608.16157) | FreeToken is an edge-native Mixture-of-Experts serving system that dynamically maps computation and model state onto heterogeneous local har… | [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken) 16816★ |
| 103 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 30853★ |
| 8 | [Persistent Recursive Worlds Enable Autonomous Software Evolution](https://huggingface.co/papers/2608.10450) | Genesis organizes long-horizon software development around a persistent project rather than persistent agents, enabling multi-day compiler c… | 💡 [EMI-Group/genesis](https://github.com/EMI-Group/genesis) 552★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 21 | [VisSearch-Bench: Evaluating Long Horizon Visual Search in Multimodal Agents](https://huggingface.co/papers/2611.04894) | VisSearch-Bench evaluates multimodal agents on visually intensive search tasks that require integrating visual context with external informa… | 💡 [antins-labs/VisSearch-Bench-v1](https://github.com/antins-labs/VisSearch-Bench-v1) 59★ |
| 86 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 92893★ |
| 39 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 35556★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 35559★ |
| 45 | [WeVisOne-VL: Unified Visual Perception from Objects to Pixels](https://huggingface.co/papers/2610.31329) | WeVisOne-VL unifies object-level and pixel-level visual perception via structured token prediction, supporting detection, localization, coun… | [Tencent/WeVisOne-VL](https://github.com/Tencent/WeVisOne-VL) 1061★ |
| 48 | [Democratizing Robot-Use Agents: A Unified Harness with Open Models](https://huggingface.co/papers/2611.01560) | Uni-robot-agent enables open-weight robot-use agents to surpass proprietary models in zero-shot manipulation and suggests joint development… | 💡 [Open-RUA/uni-robot-agent](https://github.com/Open-RUA/uni-robot-agent) 278★ |
| 156 | [ARIS: Autonomous Research via Adversarial Multi-Agent Collaboration](https://huggingface.co/papers/2605.03042) | ARIS is an open-source research harness that uses cross-model adversarial collaboration to ensure reliable long-term research outcomes throu… | [wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) 18840★ |
| 75 | [Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory](https://huggingface.co/papers/2504.19413) | Mem0, a memory-centric architecture with graph-based memory, enhances long-term conversational coherence in LLMs by efficiently extracting,… | [mem0ai/mem0](https://github.com/mem0ai/mem0) 68587★ |
| 29 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 9132★ |
| 181 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 83273★ |
| 1 | [Differentiable Data Augmentation with Kornia](https://huggingface.co/papers/2011.09832) | This paper reviews the Kornia differentiable data augmentation module for both 2D and 3D tensors, integrating with PyTorch's autograd and op… | [arraiyopensource/kornia](https://github.com/arraiyopensource/kornia) 12353★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

_这次没有（新上榜 0 个）。_

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 29 | 39 | [*sshole, or when are we finally going to get rid of C?](https://sunshowers.io/posts/sshole/) | `security` | [讨论](https://lobste.rs/s/owsnms/sshole_when_are_we_finally_going_get_rid_c) |
| 61 | 58 | [How are you dealing with all the negative side effects of AI on the web?](https://lobste.rs/s/ipplhe) | `ask` `web` | [讨论](https://lobste.rs/s/ipplhe/how_are_you_dealing_with_all_negative_side) |
| 48 | 7 | [Meridian — an experimental web browser built on Servo and GPUI](https://op.tngl.io/meridian/) | `browsers` `rust` | [讨论](https://lobste.rs/s/j63dme/meridian_experimental_web_browser_built) |
| 158 | 7 | [Libghostty 1.0](https://mitchellh.com/writing/libghostty-1-0) | `c` `release` `zig` | [讨论](https://lobste.rs/s/0ouxwf/libghostty_1_0) |
| 24 | 11 | [Scriptable GeoDNS: leaving AWS for Bunny](https://vincent.bernat.ch/en/blog/2026-bunny-geodns) | `performance` `web` | [讨论](https://lobste.rs/s/jsvlfm/scriptable_geodns_leaving_aws_for_bunny) |
| 11 | 1 | [I’m not a fan of Deno’s security model (2024)](https://goldstein.lol/posts/deno-security/) | `security` | [讨论](https://lobste.rs/s/sh62d1/i_m_not_fan_deno_s_security_model_2024) |
| 20 | 1 | [OpenBSD top(1) adds flag to show chroot, pledge and unveil status](https://undeadly.org/cgi?action=article;sid=20261106104957) | `openbsd` `security` | [讨论](https://lobste.rs/s/tfywf1/openbsd_top_1_adds_flag_show_chroot_pledge) |
| 49 | 6 | [Progress Report: Linux 7.3 - Asahi Linux](https://asahilinux.org/2026/11/progress-report-7-3/) | `linux` `mac` | [讨论](https://lobste.rs/s/4qiair/progress_report_linux_7_3_asahi_linux) |
| 6 | 1 | [Dear Open Source Developers: It's OK not to embargo](https://opensourcesecurity.io/2026/10-embargo/) | `security` | [讨论](https://lobste.rs/s/lhovnm/dear_open_source_developers_it_s_ok_not) |
| 57 | 6 | [The Port That Does Not Exist](https://acid.vegas/blog/the-port-that-does-not-exist/) | `networking` | [讨论](https://lobste.rs/s/osqswf/port_does_not_exist) |
| 32 | 1 | [Two Dimensional Version Control](https://www.redblobgames.com/blog/2026-09-27-jujutsu-experience/) | `vcs` | [讨论](https://lobste.rs/s/49o9f3/two_dimensional_version_control) |
| 4 | 1 | [Catching prompt injections hidden in PDFs](https://tomclancy.info/joshua-judges-ruth.html) | `a11y` `ai` `pdf` `security` | [讨论](https://lobste.rs/s/hreu0b/catching_prompt_injections_hidden_pdfs) |
| 7 | 2 | [GhostMap: The Android flaw that crashes your phone before you open the app](https://www.bitdefender.com/en-us/blog/labs/ghostmap-android) | `android` `security` | [讨论](https://lobste.rs/s/c99mdx/ghostmap_android_flaw_crashes_your_phone) |
| 4 | 2 | [CHIMERA simulates organic sound with acoustic tubes](https://chimera-vocal-synth.vercel.app/) | `art` | [讨论](https://lobste.rs/s/ngkqj1/chimera_simulates_organic_sound_with) |
| 3 | 0 | [How to prove equations using diagrams, part 1](https://www.epatters.org/post/e-graphs-1/) | `compilers` `math` `plt` | [讨论](https://lobste.rs/s/jvicvb/how_prove_equations_using_diagrams_part_1) |
| 7 | 2 | [Alpine Linux : openssh-server password authentication bypass](https://www.alpinelinux.org/posts/2026-11-05-openssh-password-authentication-bypass/) | `security` | [讨论](https://lobste.rs/s/7dbarm/alpine_linux_openssh_server_password) |
| 5 | 0 | [Workflow dependency lockfiles](https://docs.github.com/en/actions/concepts/security/workflow-dependency-lockfiles) | `vcs` | [讨论](https://lobste.rs/s/nft1s2/workflow_dependency_lockfiles) |
| 63 | 9 | [Making musl and proprietary NVIDIA drivers work together](https://chimera-linux.org/news/2026/11/musl-nvidia.html) | `linux` | [讨论](https://lobste.rs/s/hvxjbb/making_musl_proprietary_nvidia_drivers) |
| 24 | 23 | [The MustCreate Pattern for Go Tests](https://mtlynch.io/notes/go-must-create-pattern/) | `go` `testing` | [讨论](https://lobste.rs/s/i96uyr/mustcreate_pattern_for_go_tests) |
| 29 | 7 | [Inside GitHub's new Git storage architecture](https://github.blog/engineering/architecture-optimization/inside-githubs-new-git-storage-architecture/) | `distributed` `vcs` | [讨论](https://lobste.rs/s/y3hvme/inside_github_s_new_git_storage) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 67 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 41 | 28 | 68% | — |
| 🔴 先核对 | 21 | 10 | 47% | — |
| 🟡 在降温 | 5 | 0 | 0% | — |
| 🔵 已被发现 | 3 | 1 | 33% | — |
| 🟢 窗口内 | 13 | 6 | 46% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [JustAResearcher/gpu-unlock-ada](https://github.com/JustAResearcher/gpu-unlock-ada) | 2026-10-25 | 🚀 爆发 | 1005 | 4836 | 3 | ✅ 起来了 |
| [Sam-Hui-dot/mcd-budget-meal](https://github.com/Sam-Hui-dot/mcd-budget-meal) | 2026-10-25 | 🟢 窗口内 | 1339 | 1326 | 0 | 没起来 |
| [Zagitta/gpu-unlock](https://github.com/Zagitta/gpu-unlock) | 2026-10-25 | 🚀 爆发 | 3367 | 17920 | 353 | ✅ 起来了 |
| [amosblomqvist/learnharness](https://github.com/amosblomqvist/learnharness) | 2026-10-25 | 🔴 先核对 | 1117 | 6251 | 14 | ✅ 起来了 |
| [yeqv111/mccarbon](https://github.com/yeqv111/mccarbon) | 2026-10-25 | 🟢 窗口内 | 1567 | 1795 | 0 | 没起来 |

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
