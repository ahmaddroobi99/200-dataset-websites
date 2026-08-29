# Vishnu.ai — Agent Links (from Facebook Reel)

Pulled from the public Facebook Reel that asks viewers to comment **"Agent"** for the link, then documented here with explanations so the links live on GitHub instead of inside a Facebook DM funnel.

## Source reel

| What | Link |
| --- | --- |
| Share URL you sent | https://www.facebook.com/share/r/1JjRTET5aj/ |
| Canonical reel | https://www.facebook.com/reel/4435206106748151/ |
| Page | [Vishnu.ai](https://www.facebook.com) (public reel) |
| Caption | Comment "Agent" for the link |
| Stats when pulled | ~17K views · 353 reactions · 127 comments · 65 shares |
| Creator site | https://www.vishnuai.in/ |
| Creator resources hub | https://www.vishnuai.in/resources |

**How the reel works:** this is a comment-to-DM growth post. Facebook does not put the destination URL in the caption. Viewers comment the keyword `Agent`, then an automation DMs the pack. The public destination that matches that keyword is Vishnu.ai's **Top 7 AI Agent Repos** page.

Direct pack page:

- https://www.vishnuai.in/ai-agent-repos

---

## The 7 agent repos ("those")

These are the seven GitHub repositories listed on Vishnu.ai's agent pack. Each one is a building block for coding / research / ops agents.

### 1. OpenViking — agent context database
- **Link:** https://github.com/volcengine/OpenViking
- **Why it is here:** treats memory, knowledge, and skills as one organized context store instead of dumping everything into the prompt.
- **Use when:** you need a shared long-term context layer for multiple agents or sessions.

### 2. AgentMemory — persistent memory for coding agents
- **Link:** https://github.com/rohitg00/agentmemory
- **Why it is here:** coding agents forget repo conventions, failed approaches, and prior decisions between tasks.
- **Use when:** you want a coding agent to remember what it already learned in this codebase.

### 3. Diagram Design — Claude Code diagram pack
- **Link:** https://github.com/cathrynlavery/diagram-design
- **Why it is here:** high-quality diagram patterns aimed at Claude Code workflows (architecture, flows, system maps).
- **Use when:** you want an agent to emit clean diagrams instead of ad-hoc ASCII.

### 4. Scientific Agent Skills — 160+ research skills
- **Link:** https://github.com/K-Dense-AI/scientific-agent-skills
- **Why it is here:** a large skill library plus scientific databases so an agent can act as a research assistant, not just a chatbot.
- **Use when:** literature review, lab/data workflows, or science-domain tool use.

### 5. Awesome Harness Engineering — agent harness patterns
- **Link:** https://github.com/ai-boost/awesome-harness-engineering
- **Why it is here:** curated patterns for memory, skills, security, evals, and orchestration — the "harness" around the model.
- **Use when:** you are designing the control plane / runtime around an agent, not just a single prompt.

### 6. Anthropic Cybersecurity Skills — security skill pack
- **Link:** https://github.com/mukul975/Anthropic-Cybersecurity-Skills
- **Why it is here:** hundreds of structured cybersecurity skills for modern coding agents.
- **Use when:** threat modeling, secure code review, or security-oriented agent workflows.
- **Note:** treat this as a skills library, not an exploit cookbook. Use only on systems you own or are authorized to test.

### 7. Browser Use — agents that can drive a real browser
- **Link:** https://github.com/browser-use/browser-use
- **Why it is here:** lets an agent click, type, and complete tasks in a live browser instead of only calling APIs.
- **Use when:** the task lives on a website with no clean API (forms, dashboards, research pages).

---

## Related Vishnu.ai pages (same creator, same theme)

These are public pages on the same site. They are not all behind the "Agent" keyword, but they are the rest of the pack the reel is funneling people into.

| Page | Link | What it is |
| --- | --- | --- |
| Agent repos pack | https://www.vishnuai.in/ai-agent-repos | The 7 repos above |
| Resources hub | https://www.vishnuai.in/resources | Full prompt / repo / workflow index |
| Clawdbot 24/7 assistant | https://www.vishnuai.in/clawdbot-onboarding | Setup a Telegram/WhatsApp agent on a small server (~30–40 min, ~$20/mo API) |
| Run Claude Code free/local | https://www.vishnuai.in/run-claude-code-free | Claude Code + Ollama + GPT-OSS, no API key |
| KERNEL prompt framework | https://www.vishnuai.in/kernel-prompt | 6-rule prompt system (Keep simple, Easy to verify, Reproducible, Narrow, …) |
| 10 token-saver GitHub repos | https://www.vishnuai.in/github-token-savers | Proxies / MCP / graphs that cut Claude token use 60–98% |
| Stop rate limits | https://www.vishnuai.in/stop-rate-limits | Token-hygiene tips so long chats stop exploding cost |
| 300 Claude prompts | https://www.vishnuai.in/300-claude-prompts | Copy-ready prompts including "Design an AI Agent" and multi-agent setups |
| Instagram carousel skill | https://www.vishnuai.in/instagram-carousel-skill | Claude Project instruction that emits export-ready carousel HTML |
| $300 Google AI credits | https://www.vishnuai.in/google-credits | Walkthrough to unlock Google Cloud / AI Studio credits |
| Claude Design sites | https://www.vishnuai.in/claude-design | No-code animated sites via Claude Design + motionsites.ai |

---

## Bonus: token-saver GitHub repos from the same site

From https://www.vishnuai.in/github-token-savers — useful if the agent repos above make context windows explode.

| Repo | Link | Point |
| --- | --- | --- |
| RTK (Rust Token Killer) | https://github.com/rtk-ai/rtk | Filter noisy terminal output before it hits context (claimed 60–90%) |
| Context Mode | https://github.com/mksglu/context-mode | Park raw tool output in SQLite; only summaries enter the chat |
| code-review-graph | https://github.com/tirth8205/code-review-graph | Tree-sitter knowledge graph so the model reads what matters |
| Token Savior | https://github.com/Mibayy/token-savior | MCP that navigates by symbols instead of whole files |
| Caveman Claude | https://github.com/JuliusBrussee/caveman | Force terse output to cut completion tokens |
| claude-token-efficient | https://github.com/drona23/claude-token-efficient | A CLAUDE.md that keeps replies short |
| token-optimizer-mcp | https://github.com/ooples/token-optimizer-mcp | MCP caching / compression for tools |
| claude-token-optimizer | https://github.com/nadimtuhin/claude-token-optimizer | Reusable setup prompts for any project |
| token-optimizer | https://github.com/alexgreensh/token-optimizer | Find "ghost tokens" eating context |
| claude-context (Zilliz) | https://github.com/zilliztech/claude-context | Code-search MCP over the whole repo |

---

## What I could not pull

Facebook blocks the reel player behind a login wall, so:

1. The exact automated DM text was not captured (that only arrives after commenting `Agent` while logged in).
2. The video file itself was not downloaded. GitHub is the wrong place for a Facebook Reel binary anyway; the durable artifact is the **link list + explanation**.
3. Some items on https://www.vishnuai.in/resources are email-gated (XML prompting guide, learning materials, webinars, recommended-tools list). Those are marked gated on the site and are not copied here.

If you comment `Agent` on the reel and the DM contains extra URLs not listed above, paste them and they can be appended to this file.

---

## Quick start

If you only open three links:

1. https://www.vishnuai.in/ai-agent-repos — the pack the reel is selling
2. https://github.com/browser-use/browser-use — most immediately useful agent capability (real browser)
3. https://github.com/ai-boost/awesome-harness-engineering — map of how serious agent stacks are assembled
