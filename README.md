<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3000&pause=800&center=true&vCenter=true&width=600&lines=Hi%2C+I'm+Guanzheng+Wei+%F0%9F%91%8B;LLM+PM+%C2%B7+Agent+Builder;ASR+%C2%B7+Jobs+%26+Recruiting+%C2%B7+Model+Data" alt="Typing intro / 动态简介" />

<p>
  <a href="https://guanzhengpm.github.io/"><img src="https://img.shields.io/badge/Blog-guanzhengpm.github.io-0969da?style=flat-square&logo=githubpages&logoColor=white" alt="Blog"></a>
  <a href="https://scholar.google.com/citations?user=QZ43KEIAAAAJ"><img src="https://img.shields.io/badge/Google%20Scholar-Guanzheng%20Wei-4285F4?style=flat-square&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <img src="https://img.shields.io/badge/Base-Beijing-cf222e?style=flat-square&logo=googlemaps&logoColor=white" alt="Beijing">
  <img src="https://img.shields.io/badge/ex-Z.ai-24292f?style=flat-square" alt="ex Z.ai">
  <img src="https://img.shields.io/badge/Focus-Coding%20Agents-8250df?style=flat-square" alt="Focus">
</p>

</div>

## 🛠 What I'm Building · 正在做的项目

<table>
<thead>
<tr><th align="left" width="230">Project</th><th align="left">What it does</th></tr>
</thead>
<tbody>
<tr><td colspan="2"><b>Agent Harness</b></td></tr>
<tr>
  <td><a href="https://github.com/GuanZhengPM/looongtime-agent">looongtime-agent</a></td>
  <td>A harness for long-horizon coding tasks. Task state is durable and survives interruption; completion is judged on execution evidence, not the model's own report.<br>面向长程任务的 Coding Agent Harness。任务状态持久化，中断后可恢复；完成与否以执行证据判定，而非模型自述。</td>
</tr>
<tr>
  <td><a href="https://github.com/GuanZhengPM/AAA-Agent">AAA-Agent</a></td>
  <td>A terminal coding agent built from scratch. Routes models by task, adapts execution policy to model capability, and verifies its output before handing it back.<br>从零构建的终端 Coding Agent。按任务路由模型，执行策略随模型能力调整，产出经验证后再交付。</td>
</tr>
<tr>
  <td><a href="https://github.com/GuanZhengPM/agent-merge">agent-merge</a></td>
  <td>Multi-agent orchestration with version control for agent sessions. Workers run in isolated Git worktrees, patches are selected by test results, failed attempts go to a repair round, and every attempt is retained as a traceable timeline.<br>多 Agent 编排与会话版本控制。多个 Agent 在独立 Git worktree 中并行处理同一任务，以测试结果筛选补丁，失败的进入修复轮；全部尝试留存为可回溯的时间线。</td>
</tr>
<tr>
  <td><a href="https://github.com/GuanZhengPM/agent-learning-gate">agent-learning-gate</a></td>
  <td>Governs what an agent learns. Checks evidence and scope before anything is written to memory, rules or skills, and records rejected approaches so a new session does not retry a path already ruled out.<br>管控 Agent 的长期学习。写入记忆、规则或 Skill 前校验证据与作用域，避免把一次性反馈固化为长期指令；同时留存被否决的方案，防止新会话重复已淘汰的路径。</td>
</tr>
<tr><td colspan="2"><b>Speech · 语音</b></td></tr>
<tr>
  <td><a href="https://github.com/GuanZhengPM/TurnAlign">TurnAlign</a></td>
  <td>Streaming ASR orchestration with timestamps and speaker diarization. The underlying recognition model is replaceable.<br>流式 ASR 编排，输出带时间戳与说话人分离结果，底层识别模型可替换。</td>
</tr>
<tr>
  <td><a href="https://github.com/GuanZhengPM/DayAudio">DayAudio</a></td>
  <td>Local transcription for day-long recordings. Resumable, speaker-aware, and every line of the summary is linked back to its position in the audio.<br>全天录音的本地转写。支持断点续跑与说话人识别，摘要中每条结论均关联到原始音频位置。</td>
</tr>
<tr><td colspan="2"><b>Writing · 写作</b></td></tr>
<tr>
  <td><a href="https://guanzhengpm.github.io/">guanzhengpm.github.io</a></td>
  <td>Notes on agents, evaluation and LLM product work.<br>关于 Agent、评测与大模型产品的笔记。</td>
</tr>
</tbody>
</table>

## 🔥 Token Furnace · Token 使用记录

<a href="https://tokscale.ai/u/GuanZhengPM">
  <img width="100%" src="./assets/tokscale.svg" alt="Cached token usage stats / Token 使用统计缓存" />
</a>
