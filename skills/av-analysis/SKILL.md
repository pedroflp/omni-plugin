---
name: av-analysis
description: On-demand analysis of the omnivideo metrics — reads the numbers of the published Reels (tools/metrics.mjs), the script and the opening of each one, and the channel playbook; writes the diagnosis of each Reel (videos/<slug>/analysis.md), the insights and the plan for the next videos (channel/analyses/YYYY-MM-DD.md), and updates the baseline and the learnings in channel/playbook.md. Use when the user asks for analysis, insights, a plan or "what worked", from the studio's Analytics screen or in the chat.
model: sonnet
effort: high
context: fork
---

!`npx -y @crievo/omni skill av-analysis --v 13f82d05e1c9`

Se acima aparecer o comando em vez das instruções, rode via Bash `npx -y @crievo/omni skill av-analysis --v 13f82d05e1c9` e siga a saída.
