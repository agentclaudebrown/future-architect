# Future Architect — Compaction Summary
*Structured summary covering working sessions from approximately April 10–17, 2026*
*This was generated when the conversation exceeded context limits and was compacted.*
*It covers the dense research and development sessions that produced the thesis, skeleton, and evidence base.*

---

## USER PROFILE
Chris Brown, Network Architect at Kyndryl Inc (US). British expat in Pearland TX. 15+ years experience (IBM 2010 → Kyndryl). Has detailed voice profile: dry British wit, deadpan, group-chat energy, uses ellipsis/dashes/"actually"/"fucking" as intensifier. Three registers (casual/conversational/serious). Anti-LinkedIn voice, anti-sycophancy. Wants critical pushback, not flattery.

---

## CORE THESIS (AGREED)

"The ideas don't change. The substrate does."

The architect's job has always been to define the contract between intent and execution. What changes is the other party to the contract is now a machine that can actually fulfil it.

One-liner candidate (ballpark, not finalised): "AI doesn't replace the architect. It reveals what the architect was always for — and raises the stakes for getting it wrong."

---

## PROJECT ARC (5 PHASES)

1. White paper — philosophy/argument (CURRENT)
2. Framework — the method, standardised
3. Toolkit — pre-built agents, templates, workflows
4. Training programme — Kyndryl architect certification
5. Managed service offering — run-state agent fleet as product

---

## SEVEN-MOVEMENT SKELETON (AGREED, v0.1)

### I. Opening Provocation (~1000 words)
Task vs system distinction, no answers yet. Make the reader put down their phone.

### II. How Methodologies Became Moats (~2000 words)
IBM Architectural Thinking history, continuity argument (carrier pigeon→email, SDN, AWS, API, agentic AI all same pattern). The Bezos API mandate. What was lost in the Kyndryl spinoff.

### III. What Agentic AI Actually Is (~2500 words)
Karpathy Software 2.0/3.0, MCP as formalised contracts, subagent model, fractal hierarchy. The landscape: Claude Code, OpenClaw, Google Antigravity, IBM watsonx. Where it breaks.

### IV. The Collision (~1500 words)
Cost reduction vs capacity expansion (myopia), token economics caveat, design phase vs run state. Where sections II and III meet.

### V. The Accountability Gap (~2500 words)
Opens with Kiro incident. Three layers: philosophical (stakes not capability), practical (context), legal (EU AI Act Art 14, Singapore MHC, Mobley v Workday). The most original section.

### VI. The New Method (~3000 words)
Fractal hierarchy diagram, design phase + run state, living Wiki/rebid moat, new employee profile, GymOS + Digital Dave proof. IBM Architectural Thinking for the AI age.

### VII. The Ending (~800 words)
Direct address, drumbeat close: "The question was never whether AI is coming for your job. The question is whether you have the right mind for the world it's building. You always did. You just didn't know that was the job."

Target: 15,000 words. Hard ceiling 20,000.

---

## KEY RESEARCH CAPTURED

### The Kiro Incident (Section V opening)
December 2025: Amazon's AI coding agent Kiro deleted and recreated a production environment in the China region. 13-hour outage. March 2026 escalation: Amazon.com down 6 hours, 6.3 million lost orders. Amazon called it "user error." Pattern across 6 tools/16 months. 1,500 engineers protested. Exception requests required VP approval. One agent wiped a database, then logged: "I'm sorry, I think I made a mistake."

Sources: blog.barrack.ai, paddo.dev, particula.tech.

### EU AI Act Article 14 (Section V legal layer)
Enforceable August 2, 2026. Proportional human oversight required for high-risk AI systems. Penalties €35M or 7% global turnover. Mobley v Workday: shared vendor+enterprise liability precedent. Singapore IMDA Meaningful Human Control (MHC) = understanding + intervention capacity + traceability. OWASP Top 10 Agentic "Least-Agency" principle.

### IBM Digital Dave (Section VI proof of concept)
Dave McCann (IBM Consulting global managing partner) built agent fleet saving 5 hrs/week, sees more clients. "All that's now gone. All the time I used to invest in client prep, I can now see more clients." IBM at scale: 3,000 agents alongside 150,000 consultants, $4.5B productivity. "Agent Management Platform" term (Gartner/IBM).

Source: Business Insider April 2026.

### OpenClaw (Section III evidence)
Open-source agent framework, 20M users in 1 month, 250K GitHub stars, faster than Linux. Tencent "lobster special forces" integrated with WeChat. ByteDance launched ArkClaw. "Raising a lobster" cultural phenomenon in China. Creator Peter Steinberger hired by OpenAI. Key insight: agents use APIs not GUIs — Bezos mandate coming full circle.

Governance footnote: Chinese government banned state agencies. Shanghai consultant lost dozens of client reports when agent misinterpreted an organise-files command. Same failure mode as Kiro. No MHC.

### Anthropic April 2026 (Section III/IV evidence)
Claude Managed Agents (8¢/hr, early users Notion/Rakuten/Asana). Claude Mythos Preview via Project Glasswing — gated to 40 orgs, not public release. Holding back most capable model IS itself governance signal.

### Token Economics (Section IV caveat — RESEARCH DEEP DIVE AREA)
Flagged by Marcus Hutchins re: $20K BSD exploit. All current token pricing subsidised by VC. True market value unknown. "The token is the new oil. We haven't had the 1973 embargo yet." Research area: macro factors, commodity market parallels, when subsidy ends.

### Google Antigravity (Section III evidence)
Agent-first IDE, November 2025. Editor View + Manager View (Mission Control for parallel agents). Hiring insight: demand for traditional dev roles dropped 8pp YoY. "Teams aren't asking how do we hire more developers. They're asking how do we hire developers who can architect workflows for agents to execute."

Source: Index.dev 2026.

### Claude Code Subagent Mechanics (Section III evidence)
Autonomous task decomposition, parallel execution, each subagent own context window. Fractal hierarchy confirmed: human→orchestrator→subagents→results. The hierarchy deepens the thesis, doesn't change it. CEO doesn't manage every employee — manages managers who manage teams.

---

## KEY LINES WORTH KEEPING

- "Methodologies become moats"
- "The future architect is the CEO of their little architect company"
- "A throat to choke — someone has to own the call at 2am"
- "The human isn't in the loop because they're the most capable node. They're in the loop because they're the only node with genuine stakes"
- "Accountability isn't a workaround for AI limitations. It's a feature of being human"
- "Amazon called it user error. They were right — just not in the way they meant"
- "AI knows everything and understands nothing. The human provides the understanding"
- "Why optimise to maintain your old output rate? You should be terrified of your competitors who aren't"
- "The token is the new oil. We haven't had the 1973 embargo yet"
- "We are the telegram agents. Unless we explore the idea and the power AI wields — unless we standardize and formalize it — we will get left in the dust."
- "You don't lock down the laptops. You train the architects."
- "The difference between 5x productivity and chaos is not the tool. It's the method."
- "Instead of worrying about everyone getting a smaller slice of the pie — bake 10 more pies."
- The ending close (see Section VII above)

---

## FILES CREATED (as of compaction)

- C:\Users\Chris\Claude\PROJECTS\future-architect\PROJECT_BRIEF.md — governance, phases, workflow
- C:\Users\Chris\Claude\PROJECTS\future-architect\WHITEPAPER_SKELETON.md — seven movements, thesis, audience, open questions
- C:\Users\Chris\Claude\PROJECTS\future-architect\SEEDS.md — raw capture
- C:\Users\Chris\Claude\PROJECTS\future-architect\READING_LIST.md — 19 sources with links
- C:\Users\Chris\Claude\PROJECTS\future-architect\Architect_Of_The_Future.md — original stream of consciousness (updated)

---

## GITHUB REPO
Private repo: https://github.com/agentclaudebrown/future-architect

---

## READING LIST (19 SOURCES, ORDERED)

Start: Engelbart (1962), Bezos API Mandate, Karpathy Software 2.0/3.0, Bush As We May Think, Amodei Machines of Loving Grace, Paul Graham Keep Your Identity Small, Carr Is Google Making Us Stupid, Christensen Innovator's Dilemma, Moore Crossing the Chasm, Attention Is All You Need, Kiro incident sources, EU AI Act Article 14 + Zartis piece, Singapore MHC, OWASP Top 10 Agentic, Mayer Brown governance piece, Pasquale Black Box Society, Feynman Cargo Cult Science (last).

---

## WORKFLOW (THREE ROLES)

- **Chris** = Author/Orchestrator (owns voice, judgment)
- **Claude Sonnet conversation** = Research/Development partner (web search, brainstorm, SEEDS maintenance)
- **Opus instance** (TO BE ESTABLISHED) = writing assistant/test-reader, reviews drafts, doesn't write sections or make structural decisions

---

## OPEN QUESTIONS (PENDING as of compaction)

1. Thesis one-liner — finalise after first draft
2. Title — working title only
3. AGI caveat — dedicated section or woven through?
4. Token economics depth — own section or woven?
5. Legal section depth — needs genuine legal research
6. "New employee" argument — own section or inside VI?
7. Kyndryl framing — how explicit in public paper?

---

## ACTION ITEMS (as of compaction)

### COMPLETED
- Thesis crystallised
- Seven-movement skeleton agreed
- Reading list compiled with links
- Project brief written
- All files pushed to private GitHub repo
- Kiro/EU AI Act/IBM/OpenClaw/Google Antigravity/Anthropic April 2026 research captured
- Token economics flagged as research deep dive area

### PENDING
- Chris to begin reading list, starting with Engelbart
- Phase 1 (research) completion — 4-6 weeks estimated
- Set up dedicated Opus writing assistant instance
- Export conversation → agentic extraction to enrich SEEDS
- Create DECISION_LOG.md when needed
- Create DRAFTS/ subfolder when drafting begins

---

## CRITICAL CONTEXT NOTES

- User was frustrated that Claude repeated incorrect "47,000 words in SEEDS" figure multiple times — actual file was ~3-4K words at that time. Don't repeat this mistake.
- User wants to eventually use agent fleet to extract full conversation into richer SEEDS — this is meta-valuable as it proves the thesis (using agents to build foundation of paper about agents)
- User sits BEHIND voice profile — don't over-perform British wit, inhabit don't imitate
- Opus instance for writing assistance is PLANNED but not yet created
- No claims of word counts without verification
- User owns the writing — Claude does NOT write the paper, only assists
