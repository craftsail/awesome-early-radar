# early-radar 选题雷达 · 2026-11-04

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 101 个，细查前 20 个 · 比上次 = 和 2026-11-03 那次比 · 生成于 2026-11-04 05:51 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 1 个 · Show HN ✅ 28 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 5 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 7 个 · 🟡 在降温 9 个 · 🔵 已被发现 0 个 · 💤 不活跃 0 个 · 🔴 先核对 4 个
- **今天新出现 4 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) 平均每天 +4529，见 [爆发](#爆发)
- **复盘**：🚀 爆发 18/25 · 🔴 先核对 8/17 · 🟡 在降温 0/5 · 🔵 已被发现 0/2 · 🟢 窗口内 6/10（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) — 🤖 Open-source, local-first alternative to Grok Bot, OpenAI d…（近 7 天 +2371，刚发布一周内）
  - [qybaihe/bla](https://github.com/qybaihe/bla) — 🛡️ BLA (Blind LLM Agents) — Adversarial defense shield that…（近 7 天 +1888，比前 7 天快 9.3 倍，在加速）
  - [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) — Agent skill: describe your stack in a sentence, get an archi…（近 7 天 +1620，刚发布一周内）
- **趋势信号**：带 `ai-agents` topic 的新仓库这批里有 23 个（star 合计 22745），代表：[HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering)、[marclou/mailcheap](https://github.com/marclou/mailcheap)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：6 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: HackerBooks – HackerTube, but for books mentioned on HN](https://hackerbooks.org) — 1842 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [deepseek-ai/dsh-superagent-prototype](https://github.com/deepseek-ai/dsh-superagent-prototype) | 17419 | 4529 | +3070 | 3.8 | [11](https://news.ycombinator.com/item?id=50316116) | dsh superagent prototype · deepseek-ai dsh superagent prototype · deepseek dsh superagent prototype | Towards a More Autonomous Agent System |
| ✅ [storytold/craft-anything](https://github.com/storytold/craft-anything) | 9098 | 2509 | +3971 | 3.6 | — | craft anything · storytold craft anything · artcraft craft anything | Craft Anything: understand how any software works, and craft… |
| [ccch1mneyyy/dsh-Go](https://github.com/ccch1mneyyy/dsh-Go) | 8113 | 819 | +1874 | 9.9 | — | dsh go · ccch1mneyyy dsh go · chimney dsh go | dsh-go — DeepSeek Harness 装进口袋：手机本机运行，也能遥控你的电脑。 |
| [heydamir/unslop](https://github.com/heydamir/unslop) | 7704 | 1378 | +1164 | 5.6 | — | unslop · heydamir unslop · damir unslop | A Claude skill that turns vibecoded, AI-looking UI into a de… |
| [BryceYuuu/RUN](https://github.com/BryceYuuu/RUN) | 3265 | 566 | +1280 | 5.8 | — | run · bryceyuuu run · bryce run | RUN · 润：海外移居手册（欧洲 36 国 · 110 条路线 · 主要移民地区） |
| 🆕 [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop) | 1118 | 1118 | — | 1 | — | agent autoloop · kkkkhazix agent autoloop · khazix agent autoloop | 让你的命令行 Agent 在后台自己接活、自己跟进到底；平时不烦你，遇到拿不准的事才发卡片找你拍板。 |
| [wangzan101/Mika](https://github.com/wangzan101/Mika) | 6186 | 1097 | +580 | 5.6 | — | mika · wangzan101 mika · wangzan mika | An on-device AI agent for Android that operates apps and the… |
| [patch-gg/pixelfx](https://github.com/patch-gg/pixelfx) | 4256 | 857 | +590 | 5 | — | pixelfx · patch-gg pixelfx · patch pixelfx | 244 pixel art effects, every one a small piece of code. Plus… |
| [valentderah/totk-pc-recomp](https://github.com/valentderah/totk-pc-recomp) | 4589 | 802 | +450 | 5.7 | — | totk pc recomp · valentderah totk pc recomp · valiantsin totk pc recomp | Static recompilation of The Legend of Zelda: Tears of the Ki… |
| 🆕 [Pika-Labs/Pika-H3-Flex](https://github.com/Pika-Labs/Pika-H3-Flex) | 1402 | 254 | +793 | 5.5 | — | pika h3 flex · pika-labs pika h3 flex · pika pika h3 flex | Pika H3 Flex: video and audio generation inference |
| [anhao/ai-pose-gallery-zh](https://github.com/anhao/ai-pose-gallery-zh) | 5819 | 753 | +236 | 7.7 | — | ai pose gallery zh · anhao ai pose gallery zh | 中文版 AI 姿势参考图库 · 1439 组 / 2878 张图片 / 完整汉化 · 零依赖静态画廊 |
| [unclebob/ub-mode](https://github.com/unclebob/ub-mode) | 6827 | 713 | +205 | 9.6 | — | ub mode · unclebob ub mode · robert ub mode |  |
| [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) | 2371 | 301 | +619 | 7.9 | — | anymodelbot · modelflare-ai anymodelbot · modelflare anymodelbot | 🤖 Open-source, local-first alternative to Grok Bot, OpenAI d… |
| [rddmwmddr/android-ad-cleaner](https://github.com/rddmwmddr/android-ad-cleaner) | 6158 | 559 | +195 | 11 | — | android ad cleaner · rddmwmddr android ad cleaner | 关掉国产安卓手机系统里的广告、热搜、资讯推荐和营销推送。不 root，可还原，支持 AI 智能体一键执行。 |
| [l0ng-ai/openidea](https://github.com/l0ng-ai/openidea) | 5764 | 420 | +552 | 13.7 | [41](https://news.ycombinator.com/item?id=50323848) | openidea · l0ng-ai openidea | The IDE you know, rebuilt in Rust. IntelliJ IDEA–style keyma… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 93.3 | 🟢 窗口内 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) | Python | 2371 | +619 | +2371 | +0 | `·········▁▇█▅·` | 7 | — | — |
| 2 | 90.5 | 🟢 窗口内 | [qybaihe/bla](https://github.com/qybaihe/bla) | TypeScript | 2091 | +84 | +1888 | +203 | `···▁▁▂▁█▅▃▂▂▂·` | 10 | — | — |
| 3 | 88.7 | 🟢 窗口内 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | TypeScript | 1620 | +328 | +1620 | +0 | `··········█▇▄·` | 3 | — | — |
| 4 | 88.3 | 🟢 窗口内 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 1656 | +195 | +1563 | +93 | `···▁▁▂▁▂▄██▆▄·` | 8 | [2](https://news.ycombinator.com/item?id=50272846) | — |
| 5 | 88.2 | 🆕 🟢 窗口内 | [benjitaylor/skills](https://github.com/benjitaylor/skills) | TypeScript | 1553 | +536 | +1553 | +0 | `·········▃▇██·` | 8 | — | — |
| 6 | 81.5 | 🟢 窗口内 | [daveebbelaar/bama](https://github.com/daveebbelaar/bama) | Swift | 1527 | +68 | +890 | +637 | `····▄██▆▅▅▇▄▃·` | 10 | — | — |
| 7 | 81.1 | 🟢 窗口内 | [emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) | Rust | 991 | +82 | +858 | +133 | `····▂▂▂▂▁▂█▅▂·` | 9 | — | — |
| 8 | 64.2 | 🟡 在降温 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 1802 | +282 | +611 | +1190 | `···█▄▄▂▂▂▂▂▂▄·` | 9 | — | — |
| 9 | 62.8 | 🟡 在降温 | [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) | Kotlin | 1563 | +81 | +531 | +1032 | `▁▄█▇▄▅▄▃▃▃▃▃▃·` | 13 | — | — |
| 10 | 62.6 | 🟡 在降温 | [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) | TypeScript | 1915 | +46 | +524 | +1389 | `·····██▃▂▂▂▂▁·` | 13 | — | — |
| 11 | 60.4 | 🟡 在降温 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion) | JavaScript | 2285 | +129 | +420 | +545 | `█▅▃▅▄▄▃▃▂▂▄▇▆·` | 16 | — | — |
| 12 | 60.2 | 🟡 在降温 | [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | TypeScript | 1764 | +25 | +409 | +1355 | `···▂█▄▃▂▁▁▂▂▁·` | 9 | — | — |
| 13 | 59.1 | 🆕 🟡 在降温 | [ZiChuanLan/agent-purge](https://github.com/ZiChuanLan/agent-purge) | JavaScript | 1196 | +180 | +369 | +827 | `···▅█▆▄▂▂▁▂▂▅·` | 9 | — | — |
| 14 | 58 | 🟡 在降温 | [morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) | Python | 1697 | +9 | +328 | +1369 | `··▅█▅▂▁▂▂▂▁▁▁·` | 12 | — | — |
| 15 | 55.6 | 🟡 在降温 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze) | Rust | 1962 | +39 | +258 | +1522 | `▁▁▂▃▆█▂▁▂▁▂▁▁·` | 15 | [4](https://news.ycombinator.com/item?id=50340534) | — |
| 16 | 53.6 | 🟡 在降温 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip) | Rust | 2487 | +21 | +212 | +2274 | `▁█▅▂▂▂▁▁▁▁▁▁▁·` | 13 | [3](https://news.ycombinator.com/item?id=50207695) | — |
| 17 | 44.9 | 🆕 🔴 先核对 | [lexifina/global-law](https://github.com/lexifina/global-law) | HTML | 1766 | +51 | +1767 | +0 | `·······▂█▃▂▂▁·` | 6 | [1](https://news.ycombinator.com/item?id=50283329) | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 42.1 | 🆕 🔴 先核对 | [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop) | TypeScript | 1118 | — | +1118 | +0 | `············█·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 36.6 | 🔴 先核对 | [Balanov/shim](https://github.com/Balanov/shim) | Go | 445 | +87 | +445 | +0 | `···········█▂·` | 1 | [29](https://news.ycombinator.com/item?id=21744910) | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 30.8 | 🔴 先核对 | [t3dotgg/tstack](https://github.com/t3dotgg/tstack) | Python | 2768 | +123 | +471 | +2297 | `·▁▁▁█▃▂▂▁▁▁▁▂·` | 11 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 577 | 30 | 48435 | [t3dotgg/tstack](https://github.com/t3dotgg/tstack)、[academa-labs/manimgx](https://github.com/academa-labs/manimgx)、[Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill) |
| `mcp` | 307 | 30 | 37511 | [qybaihe/bla](https://github.com/qybaihe/bla)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[cranebeaker/coop-anything](https://github.com/cranebeaker/coop-anything) |
| `rust` | 241 | 30 | 32558 | [academa-labs/manimgx](https://github.com/academa-labs/manimgx)、[xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[opengeos/RustGIS](https://github.com/opengeos/RustGIS) |
| `local-first` | 79 | 30 | 12907 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo)、[yjid/kensaku](https://github.com/yjid/kensaku) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `ai-agents` | 23 | 22745 | [HelixDB/helix-foundry](https://github.com/HelixDB/helix-foundry)、[morluto/awesome-reverse-engineering](https://github.com/morluto/awesome-reverse-engineering)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `claude-code` | 22 | 29658 | [Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[qybaihe/bla](https://github.com/qybaihe/bla) |
| `codex` | 17 | 19861 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[UnderleveledBuilder/awesome-short-drama-skills](https://github.com/UnderleveledBuilder/awesome-short-drama-skills) |
| `agent-skills` | 15 | 21652 | [alchaincyf/huashu-motion](https://github.com/alchaincyf/huashu-motion)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) |
| `mcp-server` | 11 | 13883 | [qybaihe/bla](https://github.com/qybaihe/bla)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[marclou/mailcheap](https://github.com/marclou/mailcheap) |
| `llm` | 10 | 8251 | [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot)、[hanzohanzhe/Grandet](https://github.com/hanzohanzhe/Grandet)、[Syenzzz/mcd-coupon-strategist](https://github.com/Syenzzz/mcd-coupon-strategist) |
| `self-hosted` | 8 | 8237 | [marclou/mailcheap](https://github.com/marclou/mailcheap)、[rociiu/talorys](https://github.com/rociiu/talorys)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai) |
| `claude-skills` | 7 | 11358 | [Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)、[zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar)、[UnderleveledBuilder/awesome-short-drama-skills](https://github.com/UnderleveledBuilder/awesome-short-drama-skills) |
| `developer-tools` | 7 | 6701 | [indexable-inc/blaze](https://github.com/indexable-inc/blaze)、[jwuthri-cloud/Tracely-ai](https://github.com/jwuthri-cloud/Tracely-ai)、[hanzohanzhe/Grandet](https://github.com/hanzohanzhe/Grandet) |
| `macos` | 7 | 6437 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[kitlangton/scrawl](https://github.com/kitlangton/scrawl) |
| `windows` | 7 | 5845 | [xevrion/hatchzip](https://github.com/xevrion/hatchzip)、[LingCore/WinShun](https://github.com/LingCore/WinShun)、[yzlin286-wq/Deepscient](https://github.com/yzlin286-wq/Deepscient) |
| `typescript` | 7 | 5349 | [pingdotgg/ts-rust](https://github.com/pingdotgg/ts-rust)、[rociiu/talorys](https://github.com/rociiu/talorys)、[KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop) |

**语言分布**：Rust 30 · Python 20 · TypeScript 20 · JavaScript 14 · Go 5 · HTML 4 · Swift 2 · Astro 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) · 🟢 窗口内 · 93.3 分

> 🤖 Open-source, local-first alternative to Grok Bot, OpenAI dots and Claude Duet. Your own AI bots on any model: GPT, Claude, Gemini, Grok, DeepSeek, Kimi, GLM and 70+ more through one Modelflare key. Reach them in the app, WeChat or Feishu; they remember you, work in the background, run commands and use your computer. Pay per use.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2371 | +2371 | +0 | 26 | 2 | Python | MIT | 10-27（7 天前） | 今天 |

- **近 14 天每天新增**：`·········▁▇█▅·` 0 0 0 0 0 0 0 0 0 1 885 976 509 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `ai-assistant` `chatbot` `claude` `computer-use` `deepseek` `desktop-app` `dsh` `electron` `feishu` `gemini` `gpt` `grok` `llm` `local-first` `modelflare` `multi-model` `openai-compatible` `personal-ai-agent` `wechat`
- **主页**：<https://anymodel.bot/>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [qybaihe/bla](https://github.com/qybaihe/bla) · 🟢 窗口内 · 90.5 分

> 🛡️ BLA (Blind LLM Agents) — Adversarial defense shield that protects binaries, Electron apps, JS bundles, Python, and WebAssembly against AI reverse-engineering agents like REA. Poison -> Exhaust -> Hallucinate.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2091 | +1888 | +203 | 280 | 19 | TypeScript | MIT | 10-25（10 天前） | 1 天前 |

- **近 14 天每天新增**：`···▁▁▂▁█▅▃▂▂▂·` 0 0 0 2 27 143 31 816 488 238 145 123 78 0
- **势头**：比前 7 天快 9.3 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adversarial-ai` `claude-code` `cursor` `electron-security` `llm-security` `mcp` `mcp-server` `obfuscation` `reverse-engineering` `webassembly`
- **主页**：<https://bla.tools>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) · 🟢 窗口内 · 88.7 分

> Agent skill: describe your stack in a sentence, get an architecture diagram with official logos

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1620 | +1620 | +0 | 67 | 0 | TypeScript | MIT | 11-01（3 天前） | 1 天前 |

- **近 14 天每天新增**：`··········█▇▄·` 0 0 0 0 0 0 0 0 0 0 724 595 301 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `architecture-diagram` `claude-code` `claude-skills` `codex` `diagram` `system-architecture` `tech-stack`
- **主页**：<stacks.caru.moe>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) · 🟢 窗口内 · 88.3 分

> UEFI pre-driver NVIDIA GPU unlocker for Windows Linux Hackintosh and all EFI-bootable system (Rust): SEC2 scrubber -> FWSEC/WPR2 -> signed Booter -> V67 four-write payload, read-back verified. Verified on most RTX 20 30 40 Series.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1656 | +1563 | +93 | 148 | 31 | Rust | GPL-2.0 | 10-26（8 天前） | 今天 |

- **近 14 天每天新增**：`···▁▁▂▁▂▄██▆▄·` 0 0 0 5 7 51 30 34 169 449 420 308 183 0
- **势头**：比前 7 天快 16.8 倍，在加速
- **HN**：发过 1 次，最高 2 分（[讨论](https://news.ycombinator.com/item?id=50272846)）
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. 🆕 [benjitaylor/skills](https://github.com/benjitaylor/skills) · 🟢 窗口内 · 88.2 分

> Skills for AI coding agents.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1553 | +1553 | +0 | 111 | 2 | TypeScript | — | 10-26（8 天前） | 3 天前 |

- **近 14 天每天新增**：`·········▃▇██·` 0 0 0 0 0 0 0 0 0 139 450 478 486 0
- **势头**：前 7 天没有新增，这周才开始涨
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [daveebbelaar/bama](https://github.com/daveebbelaar/bama) · 🟢 窗口内 · 81.5 分

> BAMA: Build Any Mac App. Agent skills to research, clone, design, build, optimize, and test native macOS apps with Swift and SwiftUI.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1527 | +890 | +637 | 189 | 5 | Swift | MIT | 10-24（10 天前） | 2 天前 |

- **近 14 天每天新增**：`····▄██▆▅▅▇▄▃·` 0 0 0 0 121 265 251 183 152 154 228 112 61 0
- **势头**：比前 7 天快 1.4 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-agents` `app-clone` `claude-code` `claude-code-plugin` `codex` `computer-use` `liquid-glass` `macos` `macos-app` `native-apps` `skills` `swift` `swiftdata` `swiftui`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) · 🟢 窗口内 · 81.1 分

> Self-hosted, sharable kanban for humans and agents. One 4.5 MB binary, 4.5 MB of RAM, 10 to 60 tokens per agent reply, starts in 2 ms, zero setup.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 991 | +858 | +133 | 60 | 10 | Rust | AGPL-3.0 | 10-25（9 天前） | 1 天前 |

- **近 14 天每天新增**：`····▂▂▂▂▁▂█▅▂·` 0 0 0 0 38 61 34 54 11 48 443 231 71 0
- **势头**：比前 7 天快 6.5 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `claude-code` `cli` `codex` `coding-agents` `kanban` `local-first` `mcp` `mcp-server` `model-context-protocol` `productivity` `project-management` `raspberry-pi` `rust` `self-hosted` `sqlite` `task-manager`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) · 🟡 在降温 · 64.2 分

> Evidence-first genealogy skill for AI agents (Codex, Claude Code): church books, civil, military, deportation and repression records across the former USSR. Replies in your language.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1802 | +611 | +1190 | 183 | 1 | Python | MIT | 10-25（9 天前） | 今天 |

- **近 14 天每天新增**：`···█▄▄▂▂▂▂▂▂▄·` 0 0 0 593 229 255 113 88 71 61 54 64 273 0
- **势头**：只有前 7 天的 51%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `archives` `claude-code` `codex` `family-history` `familysearch` `genealogy` `ussr`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 9. [udhaykumarbala/cleanyourtv-app](https://github.com/udhaykumarbala/cleanyourtv-app) · 🟡 在降温 · 62.8 分

> A community-built phone app for Clean Your TV: clean up an Android TV from your phone. No laptop, no coding agent, nothing uninstalled.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1563 | +531 | +1032 | 137 | 4552 | Kotlin | MIT | 10-21（13 天前） | 今天 |

- **近 14 天每天新增**：`▁▄█▇▄▅▄▃▃▃▃▃▃·` 1 103 288 243 133 150 114 89 79 96 92 101 74 0
- **势头**：只有前 7 天的 51%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`adb` `android-tv` `debloat` `fire-tv` `google-tv` `launcher`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [CopilotKit/OpenDuet](https://github.com/CopilotKit/OpenDuet) · 🟡 在降温 · 62.6 分

> An Open Source template for a proactive AI agent that gets your work done and keeps you in the loop.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1915 | +524 | +1389 | 243 | 11 | TypeScript | MIT | 10-21（13 天前） | 1 天前 |

- **近 14 天每天新增**：`·····██▃▂▂▂▂▁·` 0 0 0 0 0 699 690 171 105 71 73 58 46 0
- **势头**：只有前 7 天的 38%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<copilotkit.ai/openduet>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [lexifina/global-law](https://github.com/lexifina/global-law) — 一天进了一半以上的 star，但 HN 上没火过
- [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop) — 一天进了一半以上的 star，但 HN 上没火过
- [Balanov/shim](https://github.com/Balanov/shim) — 一天进了一半以上的 star，但 HN 上没火过
- [t3dotgg/tstack](https://github.com/t3dotgg/tstack) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 1842 | 304 | [Show HN: HackerBooks – HackerTube, but for books mentioned on HN](https://hackerbooks.org) | [HN](https://news.ycombinator.com/item?id=50326821) |
| 814 | 387 | [Show HN: Subvocal – Talk to your computer without making noise](https://news.ycombinator.com/item?id=50340088) | [HN](https://news.ycombinator.com/item?id=50340088) |
| 452 | 146 | [Show HN: Hacker Times, a New York Times-inspired version of Hacker News](https://hackertimes.ca/) | [HN](https://news.ycombinator.com/item?id=50346981) |
| 339 | 104 | [Show HN: Wikihack – HackerTube, but for Wikipedia articles mentioned on HN](https://wikihack.netlify.app) | [HN](https://news.ycombinator.com/item?id=50333339) |
| 318 | 96 | [Show HN: OmniDiff – Opensource, super fast, content aware Git difftool, in Rust](https://github.com/ivankovic/omnidiff) | [HN](https://news.ycombinator.com/item?id=50325253) |
| 317 | 52 | [Show HN: Warsaw in voxels – An interactive 3D map of the city centre](https://p.migdal.pl/warsaw-vibe-voxel/) | [HN](https://news.ycombinator.com/item?id=50339221) |
| 297 | 153 | [Show HN: A working Nintendo in ~1GB of Qwen weights](https://github.com/dbreunig/nesformer) | [HN](https://news.ycombinator.com/item?id=50306442) |
| 261 | 55 | [Show HN: Point your camera at a landscape to learn about its geology](https://outcrop.rocks/) | [HN](https://news.ycombinator.com/item?id=50290533) |
| 257 | 53 | [Show HN: HackerTV – HN's most-recommended Youtube videos as 24/7 TV channels](https://hackertv.org) | [HN](https://news.ycombinator.com/item?id=50346755) |
| 244 | 80 | [Show HN: To Honor Sir Patrick Stewart, Enjoy the TNG Episode Guessing Game](https://tng.episodle.com/) | [HN](https://news.ycombinator.com/item?id=50311686) |
| 231 | 55 | [Show HN: I've updated my Linux System Call website and API](https://syscall.sh/) | [HN](https://news.ycombinator.com/item?id=50334704) |
| 182 | 25 | [Show HN: HackerHack – HackerBooks but for Posts Posted on HN](https://news.ycombinator.com/) | [HN](https://news.ycombinator.com/item?id=50333877) |
| 154 | 133 | [Show HN: Auto Dismiss Mac OS "Allow <app> to find devices on local networks?"](https://github.com/johncassil/dontallow) | [HN](https://news.ycombinator.com/item?id=50294506) |
| 132 | 36 | [Show HN: I Turned DOOM into a Transformer](https://github.com/mottopanikeiku/doomformer) | [HN](https://news.ycombinator.com/item?id=50297697) |
| 107 | 6 | [Show HN: A language model that lives in a boot sector](https://github.com/kerlenton/bootgpt) | [HN](https://news.ycombinator.com/item?id=50315782) |
| 106 | 29 | [Show HN: I rebuilt my old canvas 3D library as a small WebGL 2 library – phoria2](https://kevs3d.co.uk/phoria2/) | [HN](https://news.ycombinator.com/item?id=50314508) |
| 91 | 81 | [Show HN: NES Contra (1987) port (ASM –> C and then C –> WebAssembly)](https://epoyraz.github.io/nes-contra-us/) | [HN](https://news.ycombinator.com/item?id=50319169) |
| 85 | 43 | [Show HN: I built a multiplayer game where you're an aerial fighter cat](https://catcopter.com) | [HN](https://news.ycombinator.com/item?id=50305320) |
| 84 | 13 | [Show HN: A proof-of-concept formalization of the IRS federal tax forms](https://github.com/emmilco/us-tax-model) | [HN](https://news.ycombinator.com/item?id=50278678) |
| 83 | 36 | [Show HN: SlideBySide – Present slides without sharing your screen](https://slidebyside.com/) | [HN](https://news.ycombinator.com/item?id=50276883) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 11 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 4682★ |
| 161 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 120409★ |
| 63 | [Kronos: A Foundation Model for the Language of Financial Markets](https://huggingface.co/papers/2508.02739) | Kronos, a specialized pre-training framework for financial K-line data, outperforms existing models in forecasting and synthetic data genera… | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) 46525★ |
| 111 | [FreeToken: Efficient Edge-Native MoE Serving with Bandwidth-Adaptive Execution](https://huggingface.co/papers/2608.16157) | FreeToken is an edge-native Mixture-of-Experts serving system that dynamically maps computation and model state onto heterogeneous local har… | [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken) 16517★ |
| 68 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 22452★ |
| 42 | [Democratizing Robot-Use Agents: A Unified Harness with Open Models](https://huggingface.co/papers/2611.01560) | Uni-robot-agent enables open-weight robot-use agents to surpass proprietary models in zero-shot manipulation and suggests joint development… | 💡 [Open-RUA/uni-robot-agent](https://github.com/Open-RUA/uni-robot-agent) 162★ |
| 1 | [Differentiable Data Augmentation with Kornia](https://huggingface.co/papers/2011.09832) | This paper reviews the Kornia differentiable data augmentation module for both 2D and 3D tensors, integrating with PyTorch's autograd and op… | [arraiyopensource/kornia](https://github.com/arraiyopensource/kornia) 12311★ |
| 103 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 30482★ |
| 13 | [Xiaomi-OCR-0 Technical Report](https://huggingface.co/papers/2609.36136) | Xiaomi-OCR-0 is a compact vision-language model that unifies document parsing and OCR understanding through automated data synthesis, progre… | 💡 [SeerRay-Lab/Xiaomi-OCR-0](https://github.com/SeerRay-Lab/Xiaomi-OCR-0) 858★ |
| 39 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 35312★ |
| 30 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 8988★ |
| 71 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 35312★ |
| 31 | [HairDeck: Animation-Ready Stylized Hair Cards from a Single Image](https://huggingface.co/papers/2610.40599) | HairDeck generates stylized hair cards and spring-bone animations as unordered token sets using a diffusion transformer, improving accuracy… | 💡 [hyz317/HairDeck](https://github.com/hyz317/HairDeck) 786★ |
| 77 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 95 | [CUA-Master: Scaling Computer-use Agents through Open-World Recursive Improvements](https://huggingface.co/papers/2611.03126) | CUA-Master uses nested recursive loops with open-world data and feedback-driven retries to continuously improve computer-use agents across d… | 💡 [xlyu0106/CUA-Master](https://github.com/xlyu0106/CUA-Master) 86★ |
| 86 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 92586★ |
| 101 | [nanoMuse: An Open-Source Personal Agent for Every Device You Own](https://huggingface.co/papers/2610.08699) | Assistants from 2011 answered and waited, and agents from 2023 did a task and stopped. | [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) 3129★ |
| 90 | [MOSS-Image Technical Report](https://huggingface.co/papers/2610.23374) | MOSS-Image is an open diffusion transformer that combines high-fidelity synthesis with intent-aware prompt enhancement to generate text-rich… | [OpenMOSS/MOSS-Image](https://github.com/OpenMOSS/MOSS-Image) 2564★ |
| 44 | [WeVisOne-VL: Unified Visual Perception from Objects to Pixels](https://huggingface.co/papers/2610.31329) | WeVisOne-VL unifies object-level and pixel-level visual perception via structured token prediction, supporting detection, localization, coun… | 💡 [Tencent/WeVisOne-VL](https://github.com/Tencent/WeVisOne-VL) 670★ |
| 89 | [CoworkOS:Scaling Agent Coworkers for Real-world Automation](https://huggingface.co/papers/2611.03178) | CoworkOS is a long-horizon agent harness that separates strategy from execution, supports human-in-the-loop collaboration via shared artifac… | 💡 [RUC-NLPIR/CoworkOS](https://github.com/RUC-NLPIR/CoworkOS) 78★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 11 | [qwen image 2.1](https://huggingface.co/abenzerps/Qwen-Image-2.1-Turbo-Quantized) | text-to-image | 5626 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 70 | 63 | [Death comes for XSLT](https://dbushell.com/2026/11/03/xslt-rip/) | `browsers` `web` | [讨论](https://lobste.rs/s/chypzr/death_comes_for_xslt) |
| 55 | 29 | [The Ubuntu 26.04 Rust sudo is not compatible with standard sudo](https://utcc.utoronto.ca/~cks/space/blog/linux/Ubuntu2604RustSudoNotCompatible) | `linux` `rust` | [讨论](https://lobste.rs/s/e201eb/ubuntu_26_04_rust_sudo_is_not_compatible) |
| 36 | 9 | [Could a modern chess engine on a Pentium have defeated Kasparov in 1996?](https://nicholas.carlini.com/writing/2026/algorithmic-improvements-chess.html) | `games` `retrocomputing` | [讨论](https://lobste.rs/s/1gndxr/could_modern_chess_engine_on_pentium_have) |
| 23 | 0 | [Observations from Running stealmybitcoin.com](https://pavursec.com/blog/stealmybitcoin/) | `php` `security` | [讨论](https://lobste.rs/s/fgucra/observations_from_running) |
| 22 | 1 | [Announcing NetBSD 11.1](https://www.netbsd.org/releases/formal-11/NetBSD-11.1.html) | `netbsd` `release` | [讨论](https://lobste.rs/s/siqsg7/announcing_netbsd_11_1) |
| 104 | 17 | [A Decade of Kill Bugs](https://alangrow.com/blog/a-decade-of-kill-bugs) | `historical` `linux` `unix` | [讨论](https://lobste.rs/s/wgoato/decade_kill_bugs) |
| 14 | 5 | [Would you believe it's jank?](https://www.youtube.com/watch?v=tHgApFhevrQ) | `c++` `clojure` `video` | [讨论](https://lobste.rs/s/xbmjlj/would_you_believe_it_s_jank) |
| 12 | 9 | [Your terminal manipulation/navigation setups](https://lobste.rs/s/r3gton) | `a11y` `ask` `editors` | [讨论](https://lobste.rs/s/r3gton/your_terminal_manipulation_navigation) |
| 27 | 0 | [kitty 0.50.0](https://sw.kovidgoyal.net/kitty/changelog/#id1) | `release` `unix` | [讨论](https://lobste.rs/s/gwyv50/kitty_0_50_0) |
| 156 | 10 | [Jailbreaking my car's navigation system just so I can change the time](https://blog.nns.ee/2026/11/02/renault-hack/) | `linux` `reversing` `security` | [讨论](https://lobste.rs/s/qvdatp/jailbreaking_my_car_s_navigation_system) |
| 41 | 39 | [Why did you choose the nix you nix?](https://lobste.rs/s/7fcuxz) | `ask` `nix` | [讨论](https://lobste.rs/s/7fcuxz/why_did_you_choose_nix_you_nix) |
| 97 | 7 | [This background sound leaks your exact location](https://youtu.be/UytYrhYLOKI) | `math` `security` `video` | [讨论](https://lobste.rs/s/s1btqo/this_background_sound_leaks_your_exact) |
| 64 | 25 | [Stop Hardcoding Your Timeouts](https://alfy.blog/2026/04/23/stop-hardcoding-your-timeouts.html) | `practices` | [讨论](https://lobste.rs/s/qa0owz/stop_hardcoding_your_timeouts) |
| 3 | 1 | [The valley of webhooks](https://weli.dev/blog/the-valley-of-webhooks/) | `api` | [讨论](https://lobste.rs/s/in86vn/valley_webhooks) |
| 7 | 0 | [mine](https://coalton-lang.github.io/mine/) | `editors` `lisp` | [讨论](https://lobste.rs/s/znbrpn/mine) |
| 5 | 0 | [Gist of Go: Concurrency](https://antonz.org/go-concurrency/) | `go` | [讨论](https://lobste.rs/s/erkjnx/gist_go_concurrency) |
| 7 | 2 | [A Second Futamura Projection](https://blog.veitheller.de/A_Second_Futamura_Projection.html) | `compilers` `plt` | [讨论](https://lobste.rs/s/ihvhfk/second_futamura_projection) |
| 49 | 15 | [Sparks of Weight-Space Programming: LLMs can natively read & write neural network weights](https://rikiyat.github.io/blog/weight-space-programming/) | `ai` | [讨论](https://lobste.rs/s/u7wdqj/sparks_weight_space_programming_llms_can) |
| 44 | 35 | [My favourite laptop](https://blog.jsbarretto.com/post/laptop) | `hardware` | [讨论](https://lobste.rs/s/ezg5mx/my_favourite_laptop) |
| 4 | 0 | [Postgres 19 REPACK: Built-In Online Table Bloat Cleanup](https://www.snowflake.com/en/blog/engineering/postgres-19-repack-table-bloat/) | `databases` | [讨论](https://lobste.rs/s/uutnr5/postgres_19_repack_built_online_table) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 74 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 25 | 18 | 72% | — |
| 🔴 先核对 | 17 | 8 | 47% | — |
| 🟡 在降温 | 5 | 0 | 0% | — |
| 🔵 已被发现 | 2 | 0 | 0% | — |
| 🟢 窗口内 | 10 | 6 | 60% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [ELY-Open-Source/ElyOffice](https://github.com/ELY-Open-Source/ElyOffice) | 2026-10-21 | 🔴 先核对 | 638 | 1198 | 0 | 没起来 |
| [JoasASantos/REA-Prompts](https://github.com/JoasASantos/REA-Prompts) | 2026-10-21 | 🚀 爆发 | 1066 | 3554 | 0 | ✅ 起来了 |
| [deepseek-ai/DeepInfer](https://github.com/deepseek-ai/DeepInfer) | 2026-10-21 | 🚀 爆发 | 14287 | 25272 | 2355 | 没起来 |
| [pengchujin/aerial-tv](https://github.com/pengchujin/aerial-tv) | 2026-10-21 | 🚀 爆发 | 978 | 9441 | 0 | ✅ 起来了 |
| [stackedlol/ascii-sharks](https://github.com/stackedlol/ascii-sharks) | 2026-10-21 | 🚀 爆发 | 579 | 1399 | 0 | ✅ 起来了 |

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
