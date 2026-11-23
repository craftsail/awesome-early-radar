# early-radar 选题雷达 · 2026-11-23

> 从 GitHub、Hacker News、Hugging Face Papers、Lobsters 收来的候选选题，按「正在涨 × 还没被写烂 × 活着 × 可信」打分。
> 机器只负责找和收；选什么、怎么写、是不是真的好用，是人的事。

**参数**：关键词 `agent` `mcp` `rust` `local-first` · 最近 30 天新建 · star 50–3000 · 候选 100 个，细查前 20 个 · 比上次 = 和 2026-11-22 那次比 · 生成于 2026-11-23 07:06 UTC

**数据源**：GitHub 搜索 ✅ 4/4 个关键词 · star 历史 ✅ 20/20 · HN 覆盖 ✅ 20/20 · 爆发 ✅ 15 个 · HF 模型 ✅ 新上榜 2 个 · Show HN ✅ 23 条 · HF 论文 ✅ 20 篇 · Lobsters ✅ 20 条 · 复盘 ✅ 5 个

## 今日速览

- **细查 20 个仓库**：🟢 窗口内 8 个 · 🟡 在降温 7 个 · 🔵 已被发现 2 个 · 💤 不活跃 0 个 · 🔴 先核对 3 个
- **今天新出现 3 个**（🆕），其余之前报过
- **🚀 爆发 15 个**：最快的 [ItsNotRexed/Leonida](https://github.com/ItsNotRexed/Leonida) 平均每天 +6940，见 [爆发](#爆发)
- **复盘**：🚀 爆发 53/74 · 🔴 先核对 24/42 · 🟡 在降温 0/6 · 🔵 已被发现 1/3 · 💤 不活跃 0/1 · 🟢 窗口内 11/23（起来了 / 复盘了，最近 60 天）
- **最值得今天试的**：
  - [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon) — AI assistant and MCP server for Blender: visual chat, scene…（近 7 天 +2758，刚发布一周内）
  - [XinaTian/MROffice](https://github.com/XinaTian/MROffice) — MR Office — the open-source editors of the AI office suite c…（近 7 天 +2459，比前 7 天快 1229.5 倍，在加速）
  - [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) — Paste a link, get captioned 9:16 clips in ~2 min. Free, loca…（近 7 天 +2166，刚发布一周内）
- **趋势信号**：带 `claude-code` topic 的新仓库这批里有 27 个（star 合计 33700），代表：[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[DIYgod/pinky](https://github.com/DIYgod/pinky)。一个方向批量出现，比单个项目火不火更值得写
- **前沿论文**：4 篇热门论文带代码、但代码 star 还不到 1000，见 💡
- **Show HN 本周最高**：[Show HN: I built a game where you are an LLM's subagent](https://github.com/gulivan/worker755) — 309 分

**目录**：[爆发](#爆发) · [GitHub 候选](#一github新还不太火有势头) · [趋势信号](#二趋势信号) · [逐个看](#三逐个看) · [需要人工核对](#四需要人工核对) · [Show HN](#五show-hn) · [HF 论文](#六hugging-face-热门论文) · [HF 新模型](#hugging-face-新上热门的模型) · [Lobsters](#七lobsters-热门) · [复盘](#复盘14-天前报的后来怎么样) · [怎么读](#怎么读这份选题单)

## 爆发

不看关键词、不设 star 上限：创建不到 14 天，平均每天涨 200 星以上，或者比上次多 400 星以上。关键词搜索有 star 上限，涨得最快的反而会掉出去，在这里补上。

| 仓库 | star | 每天 | 比上次 | 天数 | HN 最高分 | 怎么搜它 | 一句话 |
| --- | ---: | ---: | ---: | ---: | ---: | --- | --- |
| [ItsNotRexed/Leonida](https://github.com/ItsNotRexed/Leonida) | 17054 | 6940 | +9624 | 2.5 | [217](https://news.ycombinator.com/item?id=50595168) | leonida · itsnotrexed leonida · notrexed leonida | Leonida Is A Native PC Recompilation Of The Xbox Version Of… |
| 🆕 [EL4CTEO/fast-anything](https://github.com/EL4CTEO/fast-anything) | 2290 | 1360 | — | 1.7 | [192](https://news.ycombinator.com/item?id=50596155) | fast anything · el4cteo fast anything | Don't rewrite it in Rust. Rewrite the 5% that's slow: profil… |
| [erkamyaman/rust-anything](https://github.com/erkamyaman/rust-anything) | 8180 | 1205 | +630 | 6.8 | [1](https://news.ycombinator.com/item?id=50558549) | rust anything · erkamyaman rust anything · erkam rust anything | Rewrite your whole app in Rust, one piece at a time, checked… |
| [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon) | 2758 | 749 | +77 | 3.7 | — | blender ai mcp addon · bookwjitchieni1986 blender ai mcp addon | AI assistant and MCP server for Blender: visual chat, scene… |
| [omonkeyz/xbox-emulator](https://github.com/omonkeyz/xbox-emulator) | 1401 | 716 | +503 | 2 | — | xbox emulator · omonkeyz xbox emulator | Progress notes for running Xbox Series X/S builds on PC (Tom… |
| [XinaTian/MROffice](https://github.com/XinaTian/MROffice) | 2461 | 196 | +705 | 12.5 | [4](https://news.ycombinator.com/item?id=50546074) | mroffice · xinatian mroffice · xina mroffice | MR Office — the open-source editors of the AI office suite c… |
| 🆕 [os6/nospeaker](https://github.com/os6/nospeaker) | 635 | 635 | — | 1 | [8](https://news.ycombinator.com/item?id=50601696) | nospeaker · os6 nospeaker · cody nospeaker | make your macbook's trackpad talk using its haptic motor |
| [huami1314/GestaltX](https://github.com/huami1314/GestaltX) | 8827 | 627 | +70 | 14.1 | — | gestaltx · huami1314 gestaltx | An MobileGestalt editor for iOS 27.x, featuring region-code… |
| [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) | 2166 | 558 | +364 | 3.9 | — | neonclipping · iamajmeena neonclipping | Paste a link, get captioned 9:16 clips in ~2 min. Free, loca… |
| [R0Y00/Xbox2Windows](https://github.com/R0Y00/Xbox2Windows) | 1356 | 530 | +341 | 2.6 | — | xbox2windows · r0y00 xbox2windows · royoo xbox2windows | GTA VI static recompilation research for x64 Windows. Source… |
| [deepseek-ai/chat-demo](https://github.com/deepseek-ai/chat-demo) | 5312 | 485 | +72 | 11 | [2](https://news.ycombinator.com/item?id=50509966) | chat demo · deepseek-ai chat demo · deepseek chat demo | Chat Demo |
| 🆕 [pithings/unkernel](https://github.com/pithings/unkernel) | 1189 | 115 | +459 | 10.4 | [213](https://news.ycombinator.com/item?id=50533945) | unkernel · pithings unkernel | A real Linux kernel, compiled to WebAssembly. It boots to a… |
| [simplexai-labs/linger](https://github.com/simplexai-labs/linger) | 3985 | 303 | +456 | 13.1 | — | linger · simplexai-labs linger · simplexai linger | Linger is An Open-Source Personal Agent That Runs Fully on Y… |
| [Hut-hzf/ung220z-tool](https://github.com/Hut-hzf/ung220z-tool) | 2428 | 310 | +183 | 7.8 | — | ung220z tool · hut-hzf ung220z tool | ung220z-tool 是一个针对 UNG220Z，另含中兴/烽火/华为/九联多厂商适配、固件指纹识别与分家族排障建议… |
| [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) | 2000 | 307 | +250 | 6.5 | — | inference optimisation skill · sybil-solutions inference optimisation skill · sybil inference optimisation skill | Agent skill for hill-climbing local LLM serving speed (decod… |

「怎么搜它」拿去小红书、B站、抖音搜一下，看中文区有没有人写过。

## 一、GitHub：新、还不太火、有势头

| # | 分 | 判断 | 仓库 | 语言 | star | 比上次 | 近 7 天 | 前 7 天 | 近 14 天走势 | 天数 | HN 最高分 | 疑点 |
| ---: | ---: | --- | --- | --- | ---: | ---: | ---: | ---: | --- | ---: | ---: | --- |
| 1 | 95.1 | 🟢 窗口内 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon) | — | 2758 | +77 | +2758 | +0 | `·········██▇▁·` | 3 | — | — |
| 2 | 93.7 | 🟢 窗口内 | [XinaTian/MROffice](https://github.com/XinaTian/MROffice) | TypeScript | 2461 | +705 | +2459 | +2 | `·····▁▁▁▁▆██▇·` | 12 | [4](https://news.ycombinator.com/item?id=50546074) | — |
| 3 | 92.2 | 🟢 窗口内 | [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) | Python | 2166 | +364 | +2166 | +0 | `·········▇█▅▄·` | 3 | — | — |
| 4 | 88.5 | 🟢 窗口内 | [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) | Python | 2000 | +250 | +1597 | +403 | `······▆█▃▂▂▆▄·` | 6 | — | — |
| 5 | 85.8 | 🟢 窗口内 | [Lemxy/WinRust](https://github.com/Lemxy/WinRust) | Rust | 1270 | +291 | +1270 | +0 | `·······▃▂█▇▅▇·` | 5 | — | — |
| 6 | 80.2 | 🟢 窗口内 | [huggingface/pybot](https://github.com/huggingface/pybot) | Python | 1126 | +34 | +799 | +327 | `··▁···▇█▃▃▂▂▂·` | 10 | [7](https://news.ycombinator.com/item?id=50517920) | — |
| 7 | 79.4 | 🟢 窗口内 | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Rust | 2650 | +85 | +745 | +377 | `▂▂▃▂▂▁▁▂▂▂█▄▃·` | 21 | — | — |
| 8 | 75 | 🟢 窗口内 | [boringmarketer/boring-marketing-skills](https://github.com/boringmarketer/boring-marketing-skills) | Python | 799 | +15 | +516 | +283 | `······██▃▂▂▂▁·` | 6 | — | — |
| 9 | 59.3 | 🟡 在降温 | [DIYgod/pinky](https://github.com/DIYgod/pinky) | Go | 2692 | +43 | +374 | +779 | `█▆▅▃▃▃▃▄▄▃▃▂▂·` | 16 | — | — |
| 10 | 57.9 | 🟡 在降温 | [JosssphZhou/poki](https://github.com/JosssphZhou/poki) | Swift | 1859 | +101 | +327 | +718 | `▆▃▃▅█▅▇▃▂▄▂▄▅·` | 17 | — | — |
| 11 | 57.6 | 🟡 在降温 | [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) | TypeScript | 1963 | +47 | +317 | +1646 | `·██▂▂▃▂▂▁▁▂▂▂·` | 14 | [5](https://news.ycombinator.com/item?id=49789538) | — |
| 12 | 56.6 | 🟡 在降温 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker) | Rust | 2870 | +45 | +286 | +384 | `▇█▆▄▆▇▄▆▅▇▄▅▅·` | 28 | [2](https://news.ycombinator.com/item?id=50272846) | — |
| 13 | 55.9 | 🟡 在降温 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode) | Python | 2890 | +49 | +267 | +669 | `▆█▆▅▄▃▃▄▃▃▂▂▃·` | 19 | — | — |
| 14 | 54 | 🟡 在降温 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram) | TypeScript | 2771 | +76 | +220 | +342 | `▄█▃▂▂▂▂▃▃▂▂▂▅·` | 22 | — | — |
| 15 | 46.4 | 🆕 🔵 已被发现 | [EL4CTEO/fast-anything](https://github.com/EL4CTEO/fast-anything) | Rust | 2290 | — | +2290 | +0 | `···········▂█·` | 1 | [192](https://news.ycombinator.com/item?id=50596155) | — |
| 16 | 44.9 | 🟡 在降温 | [voyager-so/vork](https://github.com/voyager-so/vork) | Rust | 1692 | +13 | +88 | +288 | `▄█▃▃▅▂▂▂▂▂▂▂▂·` | 17 | [8](https://news.ycombinator.com/item?id=50396650) | — |
| 17 | 40.4 | 🆕 🔴 先核对 | [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) | Python | 862 | — | +845 | +17 | `······▁▁▁▁▁▁█·` | 6 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 18 | 38.6 | 🆕 🔴 先核对 | [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) | TypeScript | 626 | — | +626 | +0 | `········▁▂▄▂█·` | 4 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 19 | 36.5 | 🔴 先核对 | [w01fb0ss/PiBot](https://github.com/w01fb0ss/PiBot) | TypeScript | 441 | +207 | +441 | +0 | `···········█▆·` | 2 | — | 一天进了一半以上的 star，但 HN 上没火过 |
| 20 | 34.9 | 🔵 已被发现 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt) | TypeScript | 3000 | +117 | +1084 | +1916 | `·█▇▄▃▃▃▃▅▃▃▂▂·` | 12 | [307](https://news.ycombinator.com/item?id=50454625) | — |

## 二、趋势信号

单个项目火不火是抽奖；**一个方向在短时间里冒出好几个项目**，本身就是信号。适合写成「这个月最值得装的 N 个 xxx」。

**按搜索关键词**：最近 30 天新建、star 在区间内的仓库一共有多少个

| 关键词 | GitHub 上总数 | 本批取到 | 取到的 star 合计 | 代表项目 |
| --- | ---: | ---: | ---: | --- |
| `agent` | 1086 | 30 | 48111 | [sarpstar/cinecode](https://github.com/sarpstar/cinecode)、[caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon) |
| `mcp` | 208 | 30 | 36129 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[DIYgod/pinky](https://github.com/DIYgod/pinky) |
| `rust` | 200 | 30 | 29261 | [physicsdolphin/nv-uefi-unlocker](https://github.com/physicsdolphin/nv-uefi-unlocker)、[s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[EL4CTEO/fast-anything](https://github.com/EL4CTEO/fast-anything) |
| `local-first` | 71 | 30 | 17305 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[s1dashu/quiet-md](https://github.com/s1dashu/quiet-md)、[iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) |

**按 GitHub topic**：全部候选里 ≥ 2 个仓库共用的 topic（去掉搜索关键词本身）

| topic | 仓库数 | star 合计 | 代表项目 |
| --- | ---: | ---: | --- |
| `claude-code` | 27 | 33700 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[DIYgod/pinky](https://github.com/DIYgod/pinky) |
| `ai-agents` | 22 | 23201 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[EL4CTEO/fast-anything](https://github.com/EL4CTEO/fast-anything)、[agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) |
| `codex` | 21 | 25219 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[XinaTian/MROffice](https://github.com/XinaTian/MROffice) |
| `mcp-server` | 18 | 17484 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[DIYgod/pinky](https://github.com/DIYgod/pinky)、[XinaTian/MROffice](https://github.com/XinaTian/MROffice) |
| `model-context-protocol` | 16 | 12824 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[JosssphZhou/poki](https://github.com/JosssphZhou/poki)、[emanuele-em/kanzo](https://github.com/emanuele-em/kanzo) |
| `windows` | 13 | 11966 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[yjid/kensaku](https://github.com/yjid/kensaku)、[Renly1994/xiaotang-daozai](https://github.com/Renly1994/xiaotang-daozai) |
| `agent-skills` | 11 | 15103 | [caru-ini/stack-diagram](https://github.com/caru-ini/stack-diagram)、[DenisSergeevitch/ex-ussr-kinship-research](https://github.com/DenisSergeevitch/ex-ussr-kinship-research)、[EL4CTEO/fast-anything](https://github.com/EL4CTEO/fast-anything) |
| `developer-tools` | 10 | 5703 | [EL4CTEO/fast-anything](https://github.com/EL4CTEO/fast-anything)、[alexeyw/lot-map](https://github.com/alexeyw/lot-map)、[INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) |
| `llm` | 9 | 12014 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill)、[agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) |
| `macos` | 9 | 8905 | [FrigadeHQ/yogurt](https://github.com/FrigadeHQ/yogurt)、[daveebbelaar/bama](https://github.com/daveebbelaar/bama)、[simpsoka/zigzag](https://github.com/simpsoka/zigzag) |
| `ai-agent` | 8 | 8048 | [DIYgod/pinky](https://github.com/DIYgod/pinky)、[XinaTian/MROffice](https://github.com/XinaTian/MROffice)、[INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) |
| `blender` | 8 | 6335 | [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon)、[racdeufindurch198812/Blender-AI-MCP-Studio](https://github.com/racdeufindurch198812/Blender-AI-MCP-Studio)、[credoksopho1984/blender-ai-copilot-studio](https://github.com/credoksopho1984/blender-ai-copilot-studio) |

**语言分布**：Rust 28 · TypeScript 26 · Python 17 · JavaScript 8 · Go 4 · HTML 2 · Swift 2 · C# 1

## 三、逐个看

分数最高的 10 个，写之前该知道的都在这里。

### 1. [bookwjitchieni1986/blender-ai-mcp-addon](https://github.com/bookwjitchieni1986/blender-ai-mcp-addon) · 🟢 窗口内 · 95.1 分

> AI assistant and MCP server for Blender: visual chat, scene tools, multi-agent workflows. Works with ChatGPT/GPT, Claude, Gemini, Ollama, OpenCode. Blender AI addon, copilot for 3D, bpy Python scripting, MCP integration.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2758 | +2758 | +0 | 39 | 61 | — | MIT | 11-19（3 天前） | 今天 |

- **近 14 天每天新增**：`·········██▇▁·` 0 0 0 0 0 0 0 0 0 937 934 825 62 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `ai-assistant` `blender` `blender-addon` `blender-ai` `blender-automation` `blender-mcp` `blender-plugin` `blender-scripting` `bpy` `chatgpt` `claude` `gemini` `llm` `mcp` `mcp-for-blender` `mcp-server` `model-context-protocol` `ollama` `opencode`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 2. [XinaTian/MROffice](https://github.com/XinaTian/MROffice) · 🟢 窗口内 · 93.7 分

> MR Office — the open-source editors of the AI office suite closest to Microsoft Office: documents, spreadsheets, presentations, PDF and code in the browser. Copilot in every editor edits real Word, Excel and PowerPoint files with you; an MCP server lets Claude, ChatGPT, Cursor and Codex create and edit them; embed it in your app with one line.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2461 | +2459 | +2 | 283 | 0 | TypeScript | AGPL-3.0 | 11-10（12 天前） | 今天 |

- **近 14 天每天新增**：`·····▁▁▁▁▆██▇·` 0 0 0 0 0 1 1 1 32 490 643 674 619 0
- **势头**：比前 7 天快 1229.5 倍，在加速
- **HN**：发过 1 次，最高 4 分（[讨论](https://news.ycombinator.com/item?id=50546074)）
- **topics**：`ai` `ai-agent` `claude-code` `codex` `copilot` `cursor` `document-editor` `docx` `embed` `excel` `mcp` `mcp-server` `microsoft-office-alternative` `office-suite` `pdf-editor` `powerpoint` `pptx` `spreadsheet` `word` `xlsx`
- **主页**：<https://mroffice.ai>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 3. [iamajmeena/neonclipping](https://github.com/iamajmeena/neonclipping) · 🟢 窗口内 · 92.2 分

> Paste a link, get captioned 9:16 clips in ~2 min. Free, local, open-source clipping engine (audio-first, YouTube captions, local LLM).

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2166 | +2166 | +0 | 126 | 30 | Python | MIT | 11-19（3 天前） | 1 天前 |

- **近 14 天每天新增**：`·········▇█▅▄·` 0 0 0 0 0 0 0 0 0 657 728 460 321 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-video-clipper` `clipping` `faster-whisper` `ffmpeg` `gameplay-clipper` `local-llm` `ollama` `open-source-video-editor` `opusclip-alternative` `shorts` `twitch-clips` `vertical-video` `video` `whisper` `youtube-shorts-generator` `yt-dlp`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 4. [sybil-solutions/inference-optimisation-skill](https://github.com/sybil-solutions/inference-optimisation-skill) · 🟢 窗口内 · 88.5 分

> Agent skill for hill-climbing local LLM serving speed (decode, speculative decoding, prefill, KV, startup, TTFT) on any hardware and quantization

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2000 | +1597 | +403 | 184 | 20 | Python | MIT | 11-16（6 天前） | 6 天前 |

- **近 14 天每天新增**：`······▆█▃▂▂▆▄·` 0 0 0 0 0 0 403 576 179 113 107 408 214 0
- **势头**：比前 7 天快 4.0 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skill` `benchmarking` `claude-code` `inference` `llm` `speculative-decoding`
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 5. [Lemxy/WinRust](https://github.com/Lemxy/WinRust) · 🟢 窗口内 · 85.8 分

> Windows shell replacement in Rust: taskbar, file manager, NTFS search, task manager, disk cleaner. One installer exe.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1270 | +1270 | +0 | 70 | 51 | Rust | Apache-2.0 | 11-17（5 天前） | 今天 |

- **近 14 天每天新增**：`·······▃▂█▇▅▇·` 0 0 0 0 0 0 0 80 73 348 298 183 288 0
- **势头**：刚发布一周内
- **HN**：还没人发过，你可能是最早写它的
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 6. [huggingface/pybot](https://github.com/huggingface/pybot) · 🟢 窗口内 · 80.2 分

> PyBot: a chatbot written in pure Python by a swarm of agents. No weights, no training, just rules.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1126 | +799 | +327 | 126 | 12 | Python | Apache-2.0 | 11-12（10 天前） | 6 天前 |

- **近 14 天每天新增**：`··▁···▇█▃▃▂▂▂·` 0 0 2 0 0 0 325 408 132 114 71 39 35 0
- **势头**：比前 7 天快 2.4 倍，在加速
- **HN**：发过 2 次，最高 7 分（[讨论](https://news.ycombinator.com/item?id=50517920)）
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 7. [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) · 🟢 窗口内 · 79.4 分

> Blazing-fast native notes app and rich-text editor for macOS, Windows, and Linux. Built with Rust + GPUI. Local-first and beautifully designed.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2650 | +745 | +377 | 226 | 46 | Rust | MIT | 11-01（21 天前） | 今天 |

- **近 14 天每天新增**：`▂▂▃▂▂▁▁▂▂▂█▄▃·` 52 61 87 64 66 21 26 46 34 29 370 182 84 0
- **势头**：比前 7 天快 2.0 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **主页**：<https://quiet.md>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 8. [boringmarketer/boring-marketing-skills](https://github.com/boringmarketer/boring-marketing-skills) · 🟢 窗口内 · 75 分

> 32 free marketing skills for your AI agent: research, positioning, copy, pages, SEO, AI search, ads, email and content, plus a deep local-business pack. MIT.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 799 | +516 | +283 | 282 | 2 | Python | MIT | 11-16（6 天前） | 5 天前 |

- **近 14 天每天新增**：`······██▃▂▂▂▁·` 0 0 0 0 0 0 283 303 91 49 28 31 14 0
- **势头**：比前 7 天快 1.8 倍，在加速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`agent-skills` `ai-agents` `claude-code` `codex` `copywriting` `local-seo` `marketing` `seo`
- **主页**：<https://boringmarketing.com>
- **判断**：还在加速、HN 上没人发过、没有疑点。值得当天在容器里装一下试试。

### 9. [DIYgod/pinky](https://github.com/DIYgod/pinky) · 🟡 在降温 · 59.3 分

> Let AI use your iPhone or Android phone, with you in the loop: any MCP agent from macOS, Windows or Linux, or Pinky itself, right on the phone.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 2692 | +374 | +779 | 278 | 20 | Go | Apache-2.0 | 11-06（16 天前） | 今天 |

- **近 14 天每天新增**：`█▆▅▃▃▃▃▄▄▃▃▂▂·` 219 142 129 67 71 78 73 92 82 68 51 43 38 0
- **势头**：只有前 7 天的 48%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agent` `android` `claude-code` `ios` `iphone` `mcp` `mcp-server` `phone-automation`
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

### 10. [JosssphZhou/poki](https://github.com/JosssphZhou/poki) · 🟡 在降温 · 57.9 分

> Poki uses your iPhone like you do. An open-source agent app that runs on your iPhone, reads the screen, and taps, types and swipes in real apps with your own model account.

| star | 近 7 天 | 前 7 天 | fork | issue | 语言 | 许可 | 创建 | 最近提交 |
| ---: | ---: | ---: | ---: | ---: | --- | --- | --- | --- |
| 1859 | +327 | +718 | 277 | 171 | Swift | AGPL-3.0 | 11-05（17 天前） | 今天 |

- **近 14 天每天新增**：`▆▃▃▅█▅▇▃▂▄▂▄▅·` 120 48 48 101 158 98 145 46 28 71 28 64 90 0
- **势头**：只有前 7 天的 46%，在减速
- **HN**：还没人发过，你可能是最早写它的
- **topics**：`ai-agents` `ai-assistant` `automation` `claude-code` `computer-use` `gui-agent` `ios` `ios-app` `iphone` `llm` `mcp` `mobile-agent` `model-context-protocol` `open-source` `phone-agent` `swift` `voice-assistant`
- **主页**：<https://poki.bot>
- **判断**：增速在放缓，窗口可能快过了。要写就尽快，或者换一个更深的角度。

## 四、需要人工核对

拿不到 star 名单以后只能看形状，下面这些**只是提醒你人工看一眼，不是结论**。也可能是被大号转了才一天爆发，或者作者真的在两天里发了一组项目。

- [pierridotite/mobile-agent-testers](https://github.com/pierridotite/mobile-agent-testers) — 一天进了一半以上的 star，但 HN 上没火过
- [INK-Q/agy-fast](https://github.com/INK-Q/agy-fast) — 一天进了一半以上的 star，但 HN 上没火过
- [w01fb0ss/PiBot](https://github.com/w01fb0ss/PiBot) — 一天进了一半以上的 star，但 HN 上没火过

核对时看：issue 和讨论是不是真人、作者有没有历史、README 是不是 AI 堆出来的。**有些刷星仓库本身就是恶意软件，只在容器或虚拟机里跑。**

## 五、Show HN

最近 7 天 50 分以上，按分数排。适合找「好玩」类选题。

| 分 | 评论 | 标题 | 讨论 |
| ---: | ---: | --- | --- |
| 309 | 74 | [Show HN: I built a game where you are an LLM's subagent](https://github.com/gulivan/worker755) | [HN](https://news.ycombinator.com/item?id=50599762) |
| 308 | 70 | [Show HN: I made an audio-to-MIDI model 60x more efficient](https://kobi.music/research/dettato) | [HN](https://news.ycombinator.com/item?id=50526023) |
| 251 | 94 | [Show HN: ExitPath – Open-source ways out of Slack, Notion and Microsoft 365](https://exitpath-ruddy.vercel.app/) | [HN](https://news.ycombinator.com/item?id=50547980) |
| 240 | 60 | [Show HN: Take Voyager 1 apart, down to a single memory chip](https://rshekhar.com/voyager/) | [HN](https://news.ycombinator.com/item?id=50548161) |
| 237 | 122 | [Show HN: Cornhole News – A Hacker News inspired site for news across the Midwest](https://cornholenews.news) | [HN](https://news.ycombinator.com/item?id=50561515) |
| 231 | 137 | [Show HN: Tinnitus frequency finder and audio notch tool](https://trynotched.com/find) | [HN](https://news.ycombinator.com/item?id=50541568) |
| 211 | 40 | [Show HN: Alloy CSS, dialogs, menus and tabs that work with JavaScript off](https://alloyhtml.com/example.html) | [HN](https://news.ycombinator.com/item?id=50532385) |
| 176 | 126 | [Show HN: Zero C# – C# without a runtime or GC](https://onurgumus.github.io/zero-csharp/index.html) | [HN](https://news.ycombinator.com/item?id=50590279) |
| 158 | 45 | [Show HN: Mastra Factory, the open-source software factory we use to build Mastra](https://news.ycombinator.com/item?id=50548660) | [HN](https://news.ycombinator.com/item?id=50548660) |
| 150 | 73 | [Show HN: Type Fighter 2](https://typefighter2.com/) | [HN](https://news.ycombinator.com/item?id=50544821) |
| 138 | 48 | [Show HN: Fast deterministic natural language search for OpenStreetMap data](https://hippomaps.ch/?q=cafes+by+the+Limmat+100+m+from+the+lake+in+zurich#map=15.02/47.36708/8.54935) | [HN](https://news.ycombinator.com/item?id=50561199) |
| 129 | 96 | [Show HN: Foolscap – a writing app that reads your book and never writes for you](https://foolscap.works/) | [HN](https://news.ycombinator.com/item?id=50559749) |
| 125 | 36 | [Show HN: OpenComputer – an open source alternative to Devin](https://github.com/diggerhq/opencomputer) | [HN](https://news.ycombinator.com/item?id=50581403) |
| 123 | 17 | [Show HN: Open-source, real-time object tracking for live video feeds](https://github.com/aryamandarda/tamserve) | [HN](https://news.ycombinator.com/item?id=50523377) |
| 88 | 59 | [Show HN: The Riemann Proof Handbook](https://github.com/tamnd/riemann-handbook) | [HN](https://news.ycombinator.com/item?id=50596664) |
| 82 | 11 | [Show HN: An API for word timestamps from speech, 75% within 20ms](https://quebec.yarn.so) | [HN](https://news.ycombinator.com/item?id=50532515) |
| 72 | 37 | [Show HN: Sutra-OS – A self-hosted ontology platform](https://github.com/0nelight/sutra-os) | [HN](https://news.ycombinator.com/item?id=50525052) |
| 66 | 22 | [Show HN: An ASCII cell aquarium for your terminal](https://github.com/kborer/cells/) | [HN](https://news.ycombinator.com/item?id=50541047) |
| 63 | 18 | [Show HN: Unref – A Python dead code finder built on Ruff's parser](https://github.com/Apakottur/unref) | [HN](https://news.ycombinator.com/item?id=50517410) |
| 58 | 64 | [Show HN: Nobody blocks a keyboard – Rooted Android as a physical USB Deck](https://github.com/mr-anjaneyam/Emittr) | [HN](https://news.ycombinator.com/item?id=50517840) |

## 六、Hugging Face 热门论文

💡 = 带代码、但代码 star 还不到 1000：论文热度高、代码还冷，是「前沿技术」类选题的好来源。

| 赞 | 论文 | 一句话 | 代码 |
| ---: | --- | --- | --- |
| 12 | [PaperOrchestra: A Multi-Agent Framework for Automated AI Research Paper Writing](https://huggingface.co/papers/2604.05018) | PaperOrchestra is a multi-agent framework that converts unstructured research materials into complete LaTeX manuscripts with literature synt… | [google-research/paper-orchestra](https://github.com/google-research/paper-orchestra) 5916★ |
| 107 | [Unlimited OCR Works](https://huggingface.co/papers/2606.23050) | Unlimited OCR introduces Reference Sliding Window Attention to eliminate growing memory consumption during long-sequence OCR tasks, enabling… | [baidu/Unlimited-OCR](https://github.com/baidu/Unlimited-OCR) 32005★ |
| 35 | [Depth Pro 2: Sharp and Temporally Consistent Metric Monocular Depth](https://huggingface.co/papers/2611.26603) | A single scalable network estimates dense metric depth for images and video at native resolution, jointly improving metric accuracy, boundar… | 💡 [apple-aiml-research/ml-depth-pro-2](https://github.com/apple-aiml-research/ml-depth-pro-2) 516★ |
| 157 | [Gamer: A Generalist Vision-Language-Action Foundation Model for Long-Horizon Real-Time Game Agent](https://huggingface.co/papers/2611.18397) | Gamer is a generalist agent framework that integrates perception, memory, and multi-step reasoning, trained through continued pre-training,… | [RainBowLuoCS/Gamer](https://github.com/RainBowLuoCS/Gamer) 1299★ |
| 21 | [TokenEconomizer: Experience-Driven Black-Box Cost Control for Coding Agents](https://huggingface.co/papers/2610.22732) | TokenEconomizer reduces recurring token costs of coding agents across sequential real-world tasks by pruning irrelevant tools, injecting mic… | [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) 7948★ |
| 169 | [TradingAgents: Multi-Agents LLM Financial Trading Framework](https://huggingface.co/papers/2412.20138) | A multi-agent framework using large language models for stock trading simulates real-world trading firms, improving performance metrics like… | [tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) 123502★ |
| 71 | [Harness^2: Recursive Agent Harnessing for an Open World](https://huggingface.co/papers/2610.14224) | Harness² improves agent execution harnesses through recursive task-level refinement and continual harness-level learning, boosting performan… | [google-research/harness2](https://github.com/google-research/harness2) 24775★ |
| 21 | [π^4: A Foundation Model for 4D Scene Geometry and Motion](https://huggingface.co/papers/2611.23144) | This unified foundation model enables the recovery of dense geometry, camera poses, and object tracking from diverse, uncalibrated observati… | 💡 [yyfz/Pi4](https://github.com/yyfz/Pi4) 442★ |
| 22 | [Bitnet.cpp: Efficient Edge Inference for Ternary LLMs](https://huggingface.co/papers/2502.11880) | Bitnet.cpp enhances edge inference for ternary LLMs using a novel mixed-precision matrix multiplication library, achieving significant speed… | [microsoft/BitNet](https://github.com/microsoft/BitNet) 42425★ |
| 78 | [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://huggingface.co/papers/2309.06180) | PagedAttention algorithm and vLLM system enhance the throughput of large language models by efficiently managing memory and reducing waste i… | [vllm-project/vllm](https://github.com/vllm-project/vllm) 86094★ |
| 37 | [The Other Half of the Memory Wall: Serving 35B MoEs from SSD with Trained Routing Prediction](https://huggingface.co/papers/2609.18063) | Edge0 enables efficient mixture-of-experts inference on consumer hardware by predicting expert routing ahead of time and using recovery adap… | [Edge0-AI/edge0](https://github.com/Edge0-AI/edge0) 12210★ |
| 110 | [FreeToken: Efficient Edge-Native MoE Serving with Bandwidth-Adaptive Execution](https://huggingface.co/papers/2608.16157) | FreeToken is an edge-native Mixture-of-Experts serving system that dynamically maps computation and model state onto heterogeneous local har… | [FlashML-org/FreeToken](https://github.com/FlashML-org/FreeToken) 17648★ |
| 87 | [OpenDevin: An Open Platform for AI Software Developers as Generalist Agents](https://huggingface.co/papers/2407.16741) | OpenDevin is a platform for developing AI agents that interact with the world by writing code, using command lines, and browsing the web, wi… | [opendevin/opendevin](https://github.com/opendevin/opendevin) 94088★ |
| 2 | [LittleBit: Ultra Low-Bit Quantization via Latent Factorization](https://huggingface.co/papers/2506.13771) | LittleBit is a novel method for extreme compression of large language models using low-rank factorization and multi-scale compensation, achi… | 💡 [SamsungLabs/LittleBit](https://github.com/SamsungLabs/LittleBit) 786★ |
| 73 | [AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications](https://huggingface.co/papers/2508.16279) | AgentScope enhances agentic applications by providing flexible tool-based interactions, unified interfaces, and advanced infrastructure base… | [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) 36484★ |
| 39 | [Very Large-Scale Multi-Agent Simulation in AgentScope](https://huggingface.co/papers/2407.17789) | Enhancements to the AgentScope platform improve scalability, efficiency, and ease of use for large-scale multi-agent simulations through dis… | [modelscope/agentscope](https://github.com/modelscope/agentscope) 36481★ |
| 185 | [MinerU2.5: A Decoupled Vision-Language Model for Efficient High-Resolution Document Parsing](https://huggingface.co/papers/2509.22186) | MinerU2.5, a 1.2B-parameter document parsing vision-language model, achieves state-of-the-art recognition accuracy with computational effici… | [opendatalab/MinerU](https://github.com/opendatalab/MinerU) 84154★ |
| 188 | [VibeVoice Technical Report](https://huggingface.co/papers/2508.19205) | VibeVoice synthesizes long-form multi-speaker speech using next-token diffusion and a highly efficient continuous speech tokenizer, achievin… | [microsoft/VibeVoice](https://github.com/microsoft/VibeVoice) 57492★ |
| 13 | [MovieRoll: A Systematic Framework for Rolling Out Long-Form Videos](https://huggingface.co/papers/2611.21339) | Streaming video generation must sustain quality beyond the training horizon while handling self-generated history and growing cache costs. | 💡 [Tencent-Hunyuan/MovieRoll](https://github.com/Tencent-Hunyuan/MovieRoll) 271★ |
| 158 | [ARIS: Autonomous Research via Adversarial Multi-Agent Collaboration](https://huggingface.co/papers/2605.03042) | ARIS is an open-source research harness that uses cross-model adversarial collaboration to ensure reliable long-term research outcomes throu… | [wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) 19620★ |

## Hugging Face 新上热门的模型

上次不在热门榜、这次进了前 50 的模型；量化版、微调版归到同一个名字下。模型先上榜，围绕它的工具和教程通常几天后才出来。

| 名次 | 模型 | 任务 | ♥ | 版本数 |
| ---: | --- | --- | ---: | ---: |
| 40 | [lingsante 3.1 flash](https://huggingface.co/inclusionAI/LingSante-3.1-flash) | text-generation | 65 | 1 |
| 42 | [jeveration](https://huggingface.co/linlinlinlinsdada/Jeveration) | text-to-image | 81 | 1 |

## 七、Lobsters 热门

偏硬核的技术话题。

| 分 | 评论 | 标题 | 标签 | 讨论 |
| ---: | ---: | --- | --- | --- |
| 43 | 12 | [GitHub Actions accepts invalid YAML](https://yossarian.net/til/post/github-actions-accepts-invalid-yaml/) | `programming` | [讨论](https://lobste.rs/s/leqwqu/github_actions_accepts_invalid_yaml) |
| 34 | 4 | [Gliver completes the Guix desktop](https://dustycloud.org/blog/gliver-completes-the-guix-desktop/) | `linux` `lisp` | [讨论](https://lobste.rs/s/wc8fla/gliver_completes_guix_desktop) |
| 123 | 19 | [Researcher plants 2m canaries into the AI supply chain. A privacy disaster surfaced](https://arstechnica.com/security/2026/11/a-leaky-ai-supply-chain-is-exposing-secret-user-data-at-an-alarming-rate/) | `security` | [讨论](https://lobste.rs/s/32rhzb/researcher_plants_2m_canaries_into_ai) |
| 30 | 4 | [Falsehoods Programmers Believe About ATProto](https://reiver.link/atproto/falsehoods-programmers-believe/) | `api` | [讨论](https://lobste.rs/s/bjoete/falsehoods_programmers_believe_about) |
| 5 | 5 | [Good morning and welcome to my idea of a new web](https://dave.writersweb.org/index.md) | `web` | [讨论](https://lobste.rs/s/l8u1tj/good_morning_welcome_my_idea_new_web) |
| 12 | 4 | [scriptura: a cozy corner for your scripts](https://alanpearce.eu/post/scriptura/) | `programming` | [讨论](https://lobste.rs/s/oeamed/scriptura_cozy_corner_for_your_scripts) |
| 34 | 12 | [NixOS bring-up on an Alibaba RISC-V board](https://feyor.sh/blog/nixos-bringup-on-an-alibaba-riscv-board/) | `hardware` `nix` | [讨论](https://lobste.rs/s/6jloca/nixos_bring_up_on_alibaba_risc_v_board) |
| 7 | 1 | [Testing Terraform with AWS Emulator](https://notes.hatedabamboo.me/terraform-tests-with-aws-emulator/) | `programming` | [讨论](https://lobste.rs/s/g5msf2/testing_terraform_with_aws_emulator) |
| 5 | 3 | [Calculate radio link placement and node amount for your city's mesh network](https://meshcoveragecalculator.lalala.ing/) | `hardware` | [讨论](https://lobste.rs/s/e89tey/calculate_radio_link_placement_node) |
| 127 | 10 | [My Monitor Was Cutting My Download Speed by 75%](https://blog.tymscar.com/posts/studiodisplayethernet/) | `networking` | [讨论](https://lobste.rs/s/qzerls/my_monitor_was_cutting_my_download_speed) |
| 3 | 0 | [De-fanging dangerous triggers in GitHub Actions across an organization](https://pyfound.blogspot.com/2026/11/de-fanging-dangerous-triggers-in-github.html) | `security` | [讨论](https://lobste.rs/s/rvvt6x/de_fanging_dangerous_triggers_github) |
| 35 | 16 | [Advice for the next 100 Rust GUIs](https://linebender.org/blog/next-100-guis/) | `rust` | [讨论](https://lobste.rs/s/inhlo2/advice_for_next_100_rust_guis) |
| 6 | 14 | [What If Netscape Did SSL the HTTP Way?](https://owl.billpg.com/what-if-netscape-did-ssl-the-http-way/) | `cryptography` `web` | [讨论](https://lobste.rs/s/yhl0jk/what_if_netscape_did_ssl_http_way) |
| 1 | 0 | [Marches & Gnats programming challenges](https://mng.quest/) | `games` `programming` | [讨论](https://lobste.rs/s/2zhfms/marches_gnats_programming_challenges) |
| 9 | 0 | [Fixing Google’s Feedburner problem, and caching that half works](https://joshua.hu/fixing-google-feedburner-cache-problem-atom-rss) | `web` | [讨论](https://lobste.rs/s/nbtm5j/fixing_google_s_feedburner_problem) |
| 65 | 10 | [TODOs JJ Style](https://bwc9876.dev/blog/jj_todo/) | `vcs` | [讨论](https://lobste.rs/s/qxzs4y/todos_jj_style) |
| 61 | 13 | [port scanning for mojang](https://sipacid.com/blog/port-scanning-for-mojang/) | `rant` | [讨论](https://lobste.rs/s/et5q0q/port_scanning_for_mojang) |
| 27 | 4 | [How I Got Postgres into a Single Binary](https://progrium.xyz/articles/2026/single-binary-postgres) | `databases` | [讨论](https://lobste.rs/s/pvylnk/how_i_got_postgres_into_single_binary) |
| 26 | 12 | [Microsoft 365 Outage - Post Incident Report](https://tianyin.github.io/misc/pir_microsoft_365_11-12-2026.pdf) | `distributed` `pdf` | [讨论](https://lobste.rs/s/becitz/microsoft_365_outage_post_incident) |
| 21 | 28 | [C++26 is done (again)! — Trip report: November 2026 ISO C++ standards meeting (Búzios, Brazil)](https://herbsutter.com/2026/11/21/c26-is-done-again-trip-report-november-2026-iso-c-standards-meeting-buzios-brazil/) | `c++` | [讨论](https://lobste.rs/s/fjueso/c_26_is_done_again_trip_report_november) |

## 复盘：14 天前报的，后来怎么样

起来了 = 之后 star 翻倍且多了 500 以上，或者之后上了 HN 100 分。比 HN 早 = HN 那一帖比雷达晚几天。用来看哪种判断靠得住。

**最近 60 天**（还有 93 个没到 14 天）

| 当初的判断 | 复盘了 | 起来了 | 命中率 | 比 HN 早（中位数） |
| --- | ---: | ---: | ---: | ---: |
| 🚀 爆发 | 74 | 53 | 71% | — |
| 🔴 先核对 | 42 | 24 | 57% | — |
| 🟡 在降温 | 6 | 0 | 0% | — |
| 🔵 已被发现 | 3 | 1 | 33% | — |
| 💤 不活跃 | 1 | 0 | 0% | — |
| 🟢 窗口内 | 23 | 11 | 47% | 0 天 |

**今天复盘的**

| 仓库 | 第一次报 | 当初 | 那时 star | 现在 | HN 最高分 | 结论 |
| --- | --- | --- | ---: | ---: | ---: | --- |
| [DIYgod/pinky](https://github.com/DIYgod/pinky) | 2026-11-09 | 🔴 先核对 | 1045 | 2692 | 0 | ✅ 起来了 |
| [JosssphZhou/poki](https://github.com/JosssphZhou/poki) | 2026-11-09 | 🟢 窗口内 | 622 | 1859 | 0 | ✅ 起来了 |
| [anefzaoui/misterdownloadmanager](https://github.com/anefzaoui/misterdownloadmanager) | 2026-11-09 | 🔴 先核对 | 2161 | 16876 | 0 | ✅ 起来了 |
| [jhaizhou-ops/S2Arm](https://github.com/jhaizhou-ops/S2Arm) | 2026-11-09 | 🚀 爆发 | 827 | 3835 | 0 | ✅ 起来了 |
| [tangerineturtle1/NX2navi](https://github.com/tangerineturtle1/NX2navi) | 2026-11-09 | 🚀 爆发 | 1511 | 4345 | 0 | ✅ 起来了 |

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
