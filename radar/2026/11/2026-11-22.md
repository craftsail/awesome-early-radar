# early-radar 选题雷达 · 2026-11-22

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 99 个，细查前 20 个 · 比上次 = 和 2026-11-21 那次比 · 生成于 2026-11-22 06:14 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 4 个 · Show HN ✅ 22 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 5 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 8 个 · 🟡 在降温 8 个 · 🔵 已被发现 1 个 · 💤 不活跃 0 个 · 🔴 先核对 3 个
- **今天新出现 1 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [ItsNotRexed/Leonida](https://github.com/ItsNotRexed/Leonida) 平均每天 +5227，见 [爆发](#爆发)
- **复盘**：🚀 爆发 51/72 · 🔴 先核对 22/40 · 🟡 在降温 0/6 · 🔵 已被发现 1/3 · 💤 不活跃 0/1 · 🟢 窗口内 10/22（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon) — AI assistant and MCP server for Blender: visual chat, scene…（近 7 天 +2681，刚发布一周内）
  - [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) — Paste a link, get captioned 9:16 clips in ~2 min. Free, loca…（近 7 天 +1802，刚发布一周内）
  - [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) — Agent skill for hill-climbing local LLM serving speed (decod…（近 7 天 +1750，刚发布一周内）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 24 个（star 合计 28886），代表：[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DIYgod/pinky](https://github.com/DIYgod/pinky)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：4 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: I made an audio-to-MIDI model 60x more efficient](https://kobi.music/research/dettato) — 301 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| 🆕 [ItsNotRexed/Leonida](https://github.com/ItsNotRexed/Leonida) | 7430 | 5227 | — | 1.4 | [114](https://news.ycombinator.com/item?id=50595168) | leonida · itsnotrexed leonida · notrexed leonida | Leonida Is A Native PC Recompilation Of The Xbox Version Of… |
| [erkamyaman/rust-anything](https://github.com/erkamyaman/rust-anything) | 7550 | 1312 | +705 | 5.8 | [1](https://news.ycombinator.com/item?id=50558549) | rust anything · erkamyaman rust anything · erkam rust anything | Rewrite your whole app in Rust, one piece at a time, checked… |
| [krisgfx9/Wireless-Device-Battery-Monitor](https://github.com/krisgfx9/Wireless-Device-Battery-Monitor) | 5883 | 1080 | +450 | 5.4 | [1](https://news.ycombinator.com/item?id=50543820) | wireless device battery monitor · krisgfx9 wireless device battery monitor · krisgfx wireless device battery monitor | Show the battery level of wireless mice, headsets, keyboards… |
| [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon) | 2681 | 1013 | +827 | 2.6 | — | blender ai mcp addon · bookwjitchieni1986 blender ai mcp addon | AI assistant and MCP server for Blender: visual chat, scene… |
| 🆕 [omonkeyz/xbox-emulator](https://github.com/omonkeyz/xbox-emulator) | 898 | 898 | — | 1 | — | xbox emulator · omonkeyz xbox emulator | Progress notes for running Xbox Series X/S builds on PC (Tom… |
| [hatsunemiku-ai/google-one-tools](https://github.com/hatsunemiku-ai/google-one-tools) | 1133 | 849 | +752 | 1.3 | — | google one tools · hatsunemiku-ai google one tools |  |
| [huami1314/GestaltX](https://github.com/huami1314/GestaltX) | 8757 | 672 | +90 | 13 | — | gestaltx · huami1314 gestaltx | An MobileGestalt editor for iOS 27.x, featuring region-code… |
| 🆕 [R0Y00/Xbox2Windows](https://github.com/R0Y00/Xbox2Windows) | 1015 | 667 | — | 1.5 | — | xbox2windows · r0y00 xbox2windows · royoo xbox2windows | GTA VI static recompilation research for x64 Windows. Source… |
| [XinaTian/MROffice](https://github.com/XinaTian/MROffice) | 1756 | 153 | +635 | 11.5 | [4](https://news.ycombinator.com/item?id=50546074) | mroffice · xinatian mroffice · xina mroffice | MR Office: open-source document, spreadsheet, presentation,… |
| [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) | 1802 | 634 | +451 | 2.8 | — | neonclipping · iamajmeena neonclipping | Paste a link, get captioned 9:16 clips in ~2 min. Free, loca… |
| [gylive/google-ultra](https://github.com/gylive/google-ultra) | 2621 | 543 | +70 | 4.8 | — | google ultra · gylive google ultra |  |
| [deepseek-ai/chat-demo](https://github.com/deepseek-ai/chat-demo) | 5240 | 528 | +90 | 9.9 | [2](https://news.ycombinator.com/item?id=50509966) | chat demo · deepseek-ai chat demo · deepseek chat demo | Chat Demo |
| [simplexai-labs/linger](https://github.com/simplexai-labs/linger) | 3529 | 292 | +498 | 12.1 | — | linger · simplexai-labs linger · simplexai linger | Linger is An Open-Source Personal Agent That Runs Fully on Y… |
| [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) | 1750 | 319 | +372 | 5.5 | — | inference optimisation skill · sybil-solutions inference optimisation skill · sybil inference optimisation skill | Agent skill for hill-climbing local LLM serving speed (decod… |
| 🆕 [opokukopoku/gta-6-pc-release](https://github.com/opokukopoku/gta-6-pc-release) | 368 | 368 | — | 1 | — | gta 6 pc release · opokukopoku gta 6 pc release | GTA 6 PC Release: Full Access, Zero Hassle |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 94.7 | 🟢 窗口内 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon) | — | 2681 | +827 | +2681 | +0 | `··········██▇·` | 2 | — | — |
| 2 | 90 | 🟢 窗口内 | [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) | Python | 1802 | +451 | +1802 | +0 | `··········▇█▅·` | 2 | — | — |
| 3 | 89.6 | 🟢 窗口内 | [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) | Python | 1750 | +372 | +1750 | +0 | `·······▆█▃▂▂▆·` | 5 | — | — |
| 4 | 89.6 | 🟢 窗口内 | [XinaTian/MROffice](https://github.com/XinaTian/MROffice) | TypeScript | 1756 | +635 | +1755 | +1 | `······▁▁▁▁▆█▇·` | 11 | [4](https://news.ycombinator.com/item?id=50546074) | — |
| 5 | 83.9 | 🟢 窗口内 | [huggingface/pybot](https://github.com/huggingface/pybot) | Python | 1092 | +43 | +1090 | +2 | `···▁···▇█▃▃▂▂·` | 9 | [7](https://news.ycombinator.com/item?id=50517920) | — |
| 6 | 82.7 | 🟢 窗口内 | [Lemxy/WinRust](https://github.com/Lemxy/WinRust) | Rust | 979 | +184 | +979 | +0 | `········▃▂█▇▅·` | 4 | — | — |
| 7 | 80 | 🟢 窗口内 | [boringmarketer/boring-marketing-skills](https://github.com/boringmarketer/boring-marketing-skills) | Python | 784 | +34 | +784 | +0 | `·······██▃▂▂▂·` | 5 | — | — |
| 8 | 78.4 | 🟢 窗口内 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Rust | 2565 | +183 | +684 | +468 | `▃▂▂▃▂▂▁▁▂▂▂█▄·` | 20 | — | — |
| 9 | 60 | 🟡 在降温 | [DIYgod/pinky](https://github.com/DIYgod/pinky) | Go | 2649 | +39 | +403 | +1125 | `█▅▃▃▂▂▂▂▃▂▂▂▂·` | 15 | — | — |
| 10 | 59.2 | 🟡 在降温 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki) | Swift | 1758 | +54 | +370 | +764 | `█▅▃▃▅▇▅▆▃▂▄▂▃·` | 16 | — | — |
| 11 | 58.7 | 🟡 在降温 | [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) | TypeScript | 1916 | +52 | +352 | +1564 | `··██▂▂▃▂▂▁▁▂▂·` | 13 | [5](https://news.ycombinator.com/item?id=49789538) | — |
| 12 | 56.1 | 🟡 在降温 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 2825 | +47 | +273 | +431 | `█▆█▆▄▆▆▄▆▅▇▄▅·` | 26 | [2](https://news.ycombinator.com/item?id=50272846) | — |
| 13 | 55.8 | 🟡 在降温 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode) | Python | 2841 | +22 | +265 | +887 | `█▄▆▄▃▃▃▂▃▂▂▂▂·` | 18 | — | — |
| 14 | 51.9 | 🟡 在降温 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research) | Python | 2723 | +18 | +178 | +333 | `▇▆▄▃▅█▅▄▄▆▄▂▃·` | 27 | — | — |
| 15 | 51.4 | 🟡 在降温 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | TypeScript | 2695 | +7 | +169 | +371 | `▄▄█▃▂▂▂▂▃▃▂▂▁·` | 21 | — | — |
| 16 | 44.8 | 🟡 在降温 | [voyager-so/vork](https://github.com/voyager-so/vork) | Rust | 1679 | +11 | +87 | +401 | `█▄▇▃▃▄▂▂▂▂▂▂▂·` | 16 | [8](https://news.ycombinator.com/item?id=50396650) | — |
| 17 | 36.9 | 🔴 先核对 | [Illson/RustText](https://github.com/Illson/RustText) | C# | 469 | +22 | +469 | +0 | `········█▅▂▂▂·` | 5 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 35.3 | 🔵 已被发现 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt) | TypeScript | 2883 | +89 | +1166 | +1717 | `··█▇▄▃▃▃▃▅▃▃▂·` | 11 | [307](https://news.ycombinator.com/item?id=50454625) | — |
| 19 | 32.8 | 🆕 🔴 先核对 | [w01fb0ss/PiBot](https://github.com/w01fb0ss/PiBot) | TypeScript | 234 | — | +234 | +0 | `············█·` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 30.1 | 🔴 先核对 | [prajwaljeevan50-web/openclaw-personal-workspace](https://github.com/prajwaljeevan50-web/openclaw-personal-workspace) | JavaScript | 151 | -1 | +151 | +0 | `···········█··` | 1 | — | 一天进了一半以上的 star，但 HN 上没火过 |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 1097 | 30 | 46650 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) |
| `mcp` | 213 | 30 | 33130 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[DIYgod/pinky](https://github.com/DIYgod/pinky) |
| `rust` | 200 | 30 | 28819 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker)、[s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) |
| `local-first` | 75 | 30 | 16475 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[yjid/kensaku](https://github.com/yjid/kensaku) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 24 | 28886 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DIYgod/pinky](https://github.com/DIYgod/pinky) |
| `ai-agents` | 20 | 19815 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) |
| `codex` | 18 | 19586 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[ZiChuanLan/agent-purge](https://github.com/ZiChuanLan/agent-purge) |
| `model-context-protocol` | 17 | 13391 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[JosssphZhou/poki](https://github.com/JosssphZhou/poki)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) |
| `mcp-server` | 16 | 13273 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[DIYgod/pinky](https://github.com/DIYgod/pinky)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) |
| `windows` | 13 | 11480 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[yjid/kensaku](https://github.com/yjid/kensaku)、[Renly1994/xiaotang-daozai](https://github.com/Renly1994/xiaotang-daozai) |
| `agent-skills` | 11 | 14507 | [DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[morganlinton/BeautifulRust](https://github.com/morganlinton/BeautifulRust) |
| `blender` | 10 | 7252 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[racdeufindurch198812/Blender-AI-MCP-Studio](https://github.com/racdeufindurch198812/Blender-AI-MCP-Studio)、[credoksopho1984/blender-ai-copilot-studio](https://github.com/credoksopho1984/blender-ai-copilot-studio) |
| `blender-addon` | 10 | 7252 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[racdeufindurch198812/Blender-AI-MCP-Studio](https://github.com/racdeufindurch198812/Blender-AI-MCP-Studio)、[credoksopho1984/blender-ai-copilot-studio](https://github.com/credoksopho1984/blender-ai-copilot-studio) |
| `blender-ai` | 10 | 7252 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[racdeufindurch198812/Blender-AI-MCP-Studio](https://github.com/racdeufindurch198812/Blender-AI-MCP-Studio)、[credoksopho1984/blender-ai-copilot-studio](https://github.com/credoksopho1984/blender-ai-copilot-studio) |
| `blender-automation` | 10 | 7252 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[racdeufindurch198812/Blender-AI-MCP-Studio](https://github.com/racdeufindurch198812/Blender-AI-MCP-Studio)、[credoksopho1984/blender-ai-copilot-studio](https://github.com/credoksopho1984/blender-ai-copilot-studio) |
| `blender-mcp` | 10 | 7252 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[racdeufindurch198812/Blender-AI-MCP-Studio](https://github.com/racdeufindurch198812/Blender-AI-MCP-Studio)、[credoksopho1984/blender-ai-copilot-studio](https://github.com/credoksopho1984/blender-ai-copilot-studio) |

**语言分布**：Rust 26 · TypeScript 22 · Python 19 · JavaScript 9 · Go 4 · HTML 2 · Swift 2 · C# 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon) · 🟢 窗口内 · 94.7 分

> AI assistant and MCP server for Blender: visual chat, scene tools, multi-agent workflows. Works with ChatGPT/GPT, Claude, Gemini, Ollama, OpenCode. Blender AI addon, copilot for 3D, bpy Python scripting, MCP integration.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2681 | +2681 | +0 | 36 | 60 | — | MIT | 11-19（2 天前） | 2 天前 |

- **近 14 天每天新增**：`··········██▇·` 0 0 0 0 0 0 0 0 0 0 937 934 810 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `ai-assistant` `blender` `blender-addon` `blender-ai` `blender-automation` `blender-mcp` `blender-plugin` `blender-scripting` `bpy` `chatgpt` `claude` `gemini` `llm` `mcp` `mcp-for-blender` `mcp-server` `model-context-protocol` `ollama` `opencode`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) · 🟢 窗口内 · 90 分

> Paste a link, get captioned 9:16 clips in ~2 min. Free, local, open-source clipping engine (audio-first, YouTube captions, local LLM).

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1802 | +1802 | +0 | 89 | 17 | Python | MIT | 11-19（2 天前） | 今天 |

- **近 14 天每天新增**：`··········▇█▅·` 0 0 0 0 0 0 0 0 0 0 657 729 416 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-video-clipper` `clipping` `faster-whisper` `ffmpeg` `gameplay-clipper` `local-llm` `ollama` `open-source-video-editor` `opusclip-alternative` `shorts` `twitch-clips` `vertical-video` `video` `whisper` `youtube-shorts-generator` `yt-dlp`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) · 🟢 窗口内 · 89.6 分

> Agent skill for hill-climbing local LLM serving speed (decode, speculative decoding, prefill, KV, startup, TTFT) on any hardware and quantization

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1750 | +1750 | +0 | 159 | 14 | Python | MIT | 11-16（5 天前） | 5 天前 |

- **近 14 天每天新增**：`·······▆█▃▂▂▆·` 0 0 0 0 0 0 0 403 577 179 113 107 371 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `benchmarking` `claude-code` `inference` `llm` `speculative-decoding`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [XinaTian/MROffice](https://github.com/XinaTian/MROffice) · 🟢 窗口内 · 89.6 分

> MR Office: open-source document, spreadsheet, presentation, PDF, handwriting and code editors. https://mroffice.ai

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1756 | +1755 | +1 | 199 | 0 | TypeScript | AGPL-3.0 | 11-10（11 天前） | 今天 |

- **近 14 天每天新增**：`······▁▁▁▁▆█▇·` 0 0 0 0 0 0 1 1 1 32 490 644 587 0
- **势头**：比前 7 天快 1755.0 倍，在加速
- **HN**：发过 1 次，最高 4 分（[讨论](https://news.ycombinator.com/item?id=50546074)）
- **topics**：`ai` `collaboration` `document-editor` `docx` `embed` `excel` `mcp` `office` `office-suite` `pdf` `pdf-editor` `powerpoint` `pptx` `presentation` `sdk` `spreadsheet` `typescript` `word` `wordprocessor` `xlsx`
- **主页**：<https://mroffice.ai>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [huggingface/pybot](https://github.com/huggingface/pybot) · 🟢 窗口内 · 83.9 分

> PyBot: a chatbot written in pure Python by a swarm of agents. No weights, no training, just rules.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1092 | +1090 | +2 | 122 | 11 | Python | Apache-2.0 | 11-12（9 天前） | 5 天前 |

- **近 14 天每天新增**：`···▁···▇█▃▃▂▂·` 0 0 0 2 0 0 0 325 408 133 114 71 39 0
- **势头**：比前 7 天快 545.0 倍，在加速
- **HN**：发过 2 次，最高 7 分（[讨论](https://news.ycombinator.com/item?id=50517920)）
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [Lemxy/WinRust](https://github.com/Lemxy/WinRust) · 🟢 窗口内 · 82.7 分

> Windows shell replacement in Rust: taskbar, file manager, NTFS search, task manager, disk cleaner. One installer exe.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 979 | +979 | +0 | 55 | 48 | Rust | Apache-2.0 | 11-17（4 天前） | 今天 |

- **近 14 天每天新增**：`········▃▂█▇▅·` 0 0 0 0 0 0 0 0 82 73 348 298 178 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [boringmarketer/boring-marketing-skills](https://github.com/boringmarketer/boring-marketing-skills) · 🟢 窗口内 · 80 分

> 32 free marketing skills for your AI agent: research, positioning, copy, pages, SEO, AI search, ads, email and content, plus a deep local-business pack. MIT.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 784 | +784 | +0 | 280 | 2 | Python | MIT | 11-16（5 天前） | 4 天前 |

- **近 14 天每天新增**：`·······██▃▂▂▂·` 0 0 0 0 0 0 0 283 303 91 49 28 30 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-agents` `claude-code` `codex` `copywriting` `local-seo` `marketing` `seo`
- **主页**：<https://boringmarketing.com>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) · 🟢 窗口内 · 78.4 分

> Blazing-fast native notes app and rich-text editor for macOS, Windows, and Linux. Built with Rust + GPUI. Local-first and beautifully designed.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2565 | +684 | +468 | 217 | 74 | Rust | MIT | 11-01（20 天前） | 今天 |

- **近 14 天每天新增**：`▃▂▂▃▂▂▁▁▂▂▂█▄·` 116 52 62 87 64 66 21 26 47 34 29 370 178 0
- **势头**：比前 7 天快 1.5 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://quiet.md>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 9. [DIYgod/pinky](https://github.com/DIYgod/pinky) · 🟡 在降温 · 60 分

> Let AI use your iPhone or Android phone, with you in the loop: any MCP agent from macOS, Windows or Linux, or Pinky itself, right on the phone.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2649 | +403 | +1125 | 277 | 19 | Go | Apache-2.0 | 11-06（15 天前） | 今天 |

- **近 14 天每天新增**：`█▅▃▃▂▂▂▂▃▂▂▂▂·` 419 219 142 129 67 71 78 73 92 82 68 51 37 0
- **势头**：只有前 7 天的 36%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `android` `claude-code` `ios` `iphone` `mcp` `mcp-server` `phone-automation`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [JosssphZhou/poki](https://github.com/JosssphZhou/poki) · 🟡 在降温 · 59.2 分

> Poki uses your iPhone like you do. An open-source agent app that runs on your iPhone, reads the screen, and taps, types and swipes in real apps with your own model account.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1758 | +370 | +764 | 270 | 162 | Swift | AGPL-3.0 | 11-05（16 天前） | 今天 |

- **近 14 天每天新增**：`█▅▃▃▅▇▅▆▃▂▄▂▃·` 191 120 48 48 101 158 98 145 46 28 71 28 52 0
- **势头**：只有前 7 天的 48%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `ai-assistant` `automation` `claude-code` `computer-use` `gui-agent` `ios` `ios-app` `iphone` `llm` `mcp` `mobile-agent` `model-context-protocol` `open-source` `phone-agent` `swift` `voice-assistant`
- **主页**：<https://poki.bot>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [Illson/RustText](https://github.com/Illson/RustText) — 一天进了一半以上的 star，但 HN 上没火过
- [w01fb0ss/PiBot](https://github.com/w01fb0ss/PiBot) — 一天进了一半以上的 star，但 HN 上没火过
- [prajwaljeevan50-web/openclaw-personal-workspace](https://github.com/prajwaljeevan50-web/openclaw-personal-workspace) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 301 | 69 | [Show HN: I made an audio-to-MIDI model 60x more efficient](https://kobi.music/research/dettato) | [HN](https://news.ycombinator.com/item?id=50526023) |
| 251 | 94 | [Show HN: ExitPath – Open-source ways out of Slack, Notion and Microsoft 365](https://exitpath-ruddy.vercel.app/) | [HN](https://news.ycombinator.com/item?id=50547980) |
| 238 | 60 | [Show HN: Take Voyager 1 apart, down to a single memory chip](https://rshekhar.com/voyager/) | [HN](https://news.ycombinator.com/item?id=50548161) |
| 237 | 121 | [Show HN: Cornhole News – A Hacker News inspired site for news across the Midwest](https://cornholenews.news) | [HN](https://news.ycombinator.com/item?id=50561515) |
| 221 | 134 | [Show HN: Tinnitus frequency finder and audio notch tool](https://trynotched.com/find) | [HN](https://news.ycombinator.com/item?id=50541568) |
| 211 | 40 | [Show HN: Alloy CSS, dialogs, menus and tabs that work with JavaScript off](https://alloyhtml.com/example.html) | [HN](https://news.ycombinator.com/item?id=50532385) |
| 156 | 44 | [Show HN: Mastra Factory, the open-source software factory we use to build Mastra](https://news.ycombinator.com/item?id=50548660) | [HN](https://news.ycombinator.com/item?id=50548660) |
| 149 | 72 | [Show HN: Type Fighter 2](https://typefighter2.com/) | [HN](https://news.ycombinator.com/item?id=50544821) |
| 147 | 104 | [Show HN: Zero C# – C# without a runtime or GC](https://onurgumus.github.io/zero-csharp/index.html) | [HN](https://news.ycombinator.com/item?id=50590279) |
| 136 | 45 | [Show HN: Fast deterministic natural language search for OpenStreetMap data](https://hippomaps.ch/?q=cafes+by+the+Limmat+100+m+from+the+lake+in+zurich#map=15.02/47.36708/8.54935) | [HN](https://news.ycombinator.com/item?id=50561199) |
| 128 | 94 | [Show HN: Foolscap – a writing app that reads your book and never writes for you](https://foolscap.works/) | [HN](https://news.ycombinator.com/item?id=50559749) |
| 123 | 17 | [Show HN: Open-source, real-time object tracking for live video feeds](https://github.com/aryamandarda/tamserve) | [HN](https://news.ycombinator.com/item?id=50523377) |
| 119 | 36 | [Show HN: OpenComputer – an open source alternative to Devin](https://github.com/diggerhq/opencomputer) | [HN](https://news.ycombinator.com/item?id=50581403) |
| 89 | 21 | [Show HN: The Last Complication, a Zachtronics-style watchmaking puzzle game](https://lastcomplication.com/) | [HN](https://news.ycombinator.com/item?id=50511718) |
| 81 | 11 | [Show HN: An API for word timestamps from speech, 75% within 20ms](https://quebec.yarn.so) | [HN](https://news.ycombinator.com/item?id=50532515) |
| 72 | 36 | [Show HN: Sutra-OS – A self-hosted ontology platform](https://github.com/0nelight/sutra-os) | [HN](https://news.ycombinator.com/item?id=50525052) |
| 63 | 18 | [Show HN: Unref – A Python dead code finder built on Ruff's parser](https://github.com/Apakottur/unref) | [HN](https://news.ycombinator.com/item?id=50517410) |
| 59 | 22 | [Show HN: An ASCII cell aquarium for your terminal](https://github.com/kborer/cells/) | [HN](https://news.ycombinator.com/item?id=50541047) |
| 58 | 64 | [Show HN: Nobody blocks a keyboard – Rooted Android as a physical USB Deck](https://github.com/mr-anjaneyam/Emittr) | [HN](https://news.ycombinator.com/item?id=50517840) |
| 54 | 8 | [Show HN: TrnRT – An open-source LLM inference engine for AWS Trainium](https://github.com/RunanywhereAI/trnrt) | [HN](https://news.ycombinator.com/item?id=50533270) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 11 | [PaperOrchestra: A Multi-Agent Framework for Automated AI Research Paper Writing](https://huggingface.co/papers/2604.05018) | PaperOrchestra is a multi-agent framework that converts unstructured research materials into complete LaTeX manuscripts with literature synt… | [google-research/paper-orchestra](https://github.com/google-research/paper-orchestra) 5681★ |
| 31 | [Depth Pro 2: Sharp and Temporally Consistent Metric Monocular Depth](https://huggingface.co/papers/2611.26603) | A single scalable network estimates dense metric depth for images and video at native resolution, jointly improving metric accuracy, boundar… | 💡 [apple-aiml-research/ml-depth-pro-2](https://github.com/apple-aiml-research/ml-depth-pro-2) 354★ |
| 148 | [Gamer: A Generalist Vision-Language-Action Foundation Model for Long-Horizon Real-Time Game Agent](https://huggingface.co/papers/2611.18397) | Gamer is a generalist agent framework that integrates perception, memory, and multi-step reasoning, trained through continued pre-training,… | [RainBowLuoCS/Gamer](https://github.com/RainBowLuoCS/Gamer) 1188★ |
| 21 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 7894★ |
| 18 | [π^4: A Foundation Model for 4D Scene Geometry and Motion](https://huggingface.co/papers/2611.23144) | This unified foundation model enables the recovery of dense geometry, camera poses, and object tracking from diverse, uncalibrated observati… | 💡 [yyfz/Pi4](https://github.com/yyfz/Pi4) 403★ |
| 169 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 123382★ |
| 37 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 12186★ |
| 70 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 24654★ |
| 22 | [Bitnet.cpp: Efficient Edge Inference for Ternary LLMs](https://huggingface.co/papers/2502.11880) | Bitnet.cpp enhances edge inference for ternary LLMs using a novel mixed-precision matrix multiplication library, achieving significant speed… | [microsoft/BitNet](https://github.com/microsoft/BitNet) 42373★ |
| 78 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 110 | [FreeToken: Efficient Edge-Native MoE Serving with Bandwidth-Adaptive Execution](https://huggingface.co/papers/2608.16157) | FreeToken is an edge-native Mixture-of-Experts serving system that dynamically maps computation and model state onto heterogeneous local har… | [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken) 17560★ |
| 2 | [LittleBit: Ultra Low-Bit Quantization via Latent Factorization](https://huggingface.co/papers/2506.13771) | LittleBit is a novel method for extreme compression of large language models using low-rank factorization and multi-scale compensation, achi… | 💡 [SamsungLabs/LittleBit](https://github.com/SamsungLabs/LittleBit) 729★ |
| 87 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 93972★ |
| 39 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 36438★ |
| 73 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 36438★ |
| 187 | [VibeVoice Technical Report](https://huggingface.co/papers/2508.19205) | VibeVoice synthesizes long-form multi-speaker speech using next-token diffusion and a highly efficient continuous speech tokenizer, achievin… | [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice) 57460★ |
| 185 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 84102★ |
| 40 | [Geometric Context Transformer for Streaming 3D Reconstruction](https://huggingface.co/papers/2604.14141) | LingBot-Map is a feed-forward 3D foundation model that reconstructs scenes from video streams using a geometric context transformer architec… | [robbyant/lingbot-map](https://github.com/robbyant/lingbot-map) 18918★ |
| 35 | [HuggingFace's Transformers: State-of-the-art Natural Language Processing](https://huggingface.co/papers/1910.03771) | Transformers library provides state-of-the-art Transformer architectures and pretrained models for natural language processing tasks with a… | [huggingface/transformers](https://github.com/huggingface/transformers) 169375★ |
| 45 | [WeMM-Video: Pushing the Frontiers of Open-Source Omni-Modal Video Understanding](https://huggingface.co/papers/2611.26409) | WeMM-Video is a family of Chinese-English bilingual omni-modal foundation models that unify text, image, audio, and video processing for joi… | 💡 [Tencent/WeMM-Video](https://github.com/Tencent/WeMM-Video) 68★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 12 | [inkling 2 mini](https://huggingface.co/AtomicChat/Inkling-2-Mini-Uncensored-GGUF) | image-text-to-text | 450 | 2 |
| 18 | [sulphur 3](https://huggingface.co/SulphurAI/Sulphur-3) | — | 706 | 1 |
| 31 | [pi h3](https://huggingface.co/Lakonik/pi-H3) | image-text-to-video | 101 | 1 |
| 45 | [sava](https://huggingface.co/inworld/sava) | voice-activity-detection | 78 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 85 | 7 | [My Monitor Was Cutting My Download Speed by 75%](https://blog.tymscar.com/posts/studiodisplayethernet/) | `networking` | [讨论](https://lobste.rs/s/qzerls/my_monitor_was_cutting_my_download_speed) |
| 47 | 9 | [TODOs JJ Style](https://bwc9876.dev/blog/jj_todo/) | `vcs` | [讨论](https://lobste.rs/s/qxzs4y/todos_jj_style) |
| 9 | 1 | [NixOS bring-up on an Alibaba RISC-V board](https://feyor.sh/blog/nixos-bringup-on-an-alibaba-riscv-board/) | `hardware` `nix` | [讨论](https://lobste.rs/s/6jloca/nixos_bring_up_on_alibaba_risc_v_board) |
| 11 | 2 | [Advice for the next 100 Rust GUIs](https://linebender.org/blog/next-100-guis/) | `rust` | [讨论](https://lobste.rs/s/inhlo2/advice_for_next_100_rust_guis) |
| 12 | 3 | [How I Got Postgres into a Single Binary](https://progrium.xyz/articles/2026/single-binary-postgres) | `databases` | [讨论](https://lobste.rs/s/pvylnk/how_i_got_postgres_into_single_binary) |
| 8 | 2 | [Researcher plants 2m canaries into the AI supply chain. A privacy disaster surfaced](https://arstechnica.com/security/2026/11/a-leaky-ai-supply-chain-is-exposing-secret-user-data-at-an-alarming-rate/) | `ai` `security` | [讨论](https://lobste.rs/s/32rhzb/researcher_plants_2m_canaries_into_ai) |
| 16 | 23 | [C++26 is done (again)! — Trip report: November 2026 ISO C++ standards meeting (Búzios, Brazil)](https://herbsutter.com/2026/11/21/c26-is-done-again-trip-report-november-2026-iso-c-standards-meeting-buzios-brazil/) | `c++` | [讨论](https://lobste.rs/s/fjueso/c_26_is_done_again_trip_report_november) |
| 18 | 1 | [port scanning for mojang](https://sipacid.com/blog/port-scanning-for-mojang/) | `rant` | [讨论](https://lobste.rs/s/et5q0q/port_scanning_for_mojang) |
| 26 | 1 | [Probabilistic data structures in Go, part 2](https://antonz.org/probabilistic-data-structures-2/) | `go` | [讨论](https://lobste.rs/s/hcofqi/probabilistic_data_structures_go_part_2) |
| 14 | 7 | [Microsoft 365 Outage - Post Incident Report](https://tianyin.github.io/misc/pir_microsoft_365_11-12-2026.pdf) | `distributed` `pdf` | [讨论](https://lobste.rs/s/becitz/microsoft_365_outage_post_incident) |
| 104 | 62 | [Levent Alpöge Claims Proof of Riemann Hypothesis](https://alpo.ge/remark.pdf) | `math` `pdf` | [讨论](https://lobste.rs/s/cmifpg/levent_alpoge_claims_proof_riemann) |
| 8 | 4 | [Changes on freedesktop.org](https://blog.tenstral.net/2026/11/new-fdo-website.html) | `programming` | [讨论](https://lobste.rs/s/p5zsx4/changes_on_freedesktop_org) |
| 81 | 14 | [Slopstrap: Make your site look hastily vibecoded](https://slopstrap.mikelacher.com/l) | `css` `satire` `web` | [讨论](https://lobste.rs/s/1n8fzn/slopstrap_make_your_site_look_hastily) |
| 2 | 1 | [GhostScript CVE 2026-125396: "Upload2Shell"](https://pwn.ai/upload2shell/research.html) | `security` | [讨论](https://lobste.rs/s/n5i1ds/ghostscript_cve_2026_125396) |
| 73 | 28 | [Vim Classic 8.3.1 released](https://vim-classic.org/news/vim-8.3.1-released.html) | `editors` `release` | [讨论](https://lobste.rs/s/kkglbw/vim_classic_8_3_1_released) |
| 71 | 33 | [Announcing jj-musubi: live sync for Jujutsu](https://www.serpentine.com/posts/2026/announcing-jj-musubi/) | `release` `vcs` | [讨论](https://lobste.rs/s/tj1j4b/announcing_jj_musubi_live_sync_for) |
| 85 | 7 | [Internet Archive Staffers Are Unionizing](https://cwa-union.org/news/releases/internet-archive-workers-launch-union-campaign-communications-workers-america) | `culture` | [讨论](https://lobste.rs/s/o5coeq/internet_archive_staffers_are) |
| 68 | 10 | [Removing binder.c](https://lwn.net/Articles/1102982/) | `android` `linux` `rust` | [讨论](https://lobste.rs/s/vo5jve/removing_binder_c) |
| 5 | 1 | [How 2 Security Research (MLG)](https://www.youtube.com/watch?v=dXQ_9WN6KLQ) | `satire` `security` `video` | [讨论](https://lobste.rs/s/emymet/how_2_security_research_mlg) |
| 26 | 3 | [Alice v0.6.0](https://www.alicecaml.org/blog/alice-v0-6-0/) | `ml` `release` | [讨论](https://lobste.rs/s/18c0lq/alice_v0_6_0) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 93 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 72 | 51 | 70% | — |
| 🔴 先核对 | 40 | 22 | 55% | — |
| 🟡 在降温 | 6 | 0 | 0% | — |
| 🔵 已被发现 | 3 | 1 | 33% | — |
| 💤 不活跃 | 1 | 0 | 0% | — |
| 🟢 窗口内 | 22 | 10 | 45% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [NotRexed/Hookshot](https://github.com/NotRexed/Hookshot) | 2026-11-08 | 🚀 爆发 | 2058 | 0 | 2 | 仓库没了 |
| [Th0rgal/satmux](https://github.com/Th0rgal/satmux) | 2026-11-08 | 🚀 爆发 | 573 | 1104 | 0 | 没起来 |
| [sarpstar/cinecode](https://github.com/sarpstar/cinecode) | 2026-11-08 | 🔴 先核对 | 996 | 2841 | 0 | ✅ 起来了 |
| [sostenesfreitas/ocarina-recomp](https://github.com/sostenesfreitas/ocarina-recomp) | 2026-11-08 | 🚀 爆发 | 841 | 1244 | 0 | 没起来 |
| [voyager-so/vork](https://github.com/voyager-so/vork) | 2026-11-08 | 🔴 先核对 | 935 | 1679 | 8 | 没起来 |

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
