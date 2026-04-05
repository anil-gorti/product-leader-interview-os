> ⚠️ Consolidated into [anil-gorti/product-org-os-master](https://github.com/anil-gorti/product-org-os-master). This repository is archived and kept for historical reference.

# Product Leader Interview OS

**A Claude Code-powered preparation system for Directors and above  
interviewing with the C-suite at Indian product companies.**

---

## What This Is

Most senior interview prep is generic. You rehearse answers to predictable  
questions against a nameless interviewer. The gap between that rehearsal  
and a real C-suite conversation is enormous — because C-suite conversations  
are not skill demonstrations. They are peer-level strategic exchanges where  
your credibility is established in the first five minutes or not at all.

This OS closes that gap. You build a knowledge base of your specific career  
evidence, your specific target company intelligence, and your specific  
strategic thesis. Claude Code reads all of it and simulates the specific  
founders and executives you are about to face — with their backgrounds,  
their companies' constraints, and the exact traps each one tends to set.

The memory layer compounds. What you practised in session one informs  
session two. By session five, the system knows which of your stories are  
ready and which need work better than you do.

---

## Who This Is For

- Directors, VPs, and Heads of Product preparing for C-suite panels
- Senior PMs moving into their first Director or Head of Product role
- Product leaders interviewing at Indian startups at Series B through pre-IPO
- Anyone whose next conversation is with a founder, CEO, CTO, or COO
  who will evaluate strategy and capital judgment, not just PM craft

This OS is built specifically for the **Indian product leadership context**:  
INR-denominated metrics, Indian market constraints, Bengaluru/Mumbai/Delhi  
ecosystem dynamics, and the specific cultural translation required when  
your experience is partly or fully from outside India.

---

## The Core Insight

A Director interview at an Indian startup is evaluated on three things  
that have nothing to do with product management skill:

**1. Capital judgment** — Does this person understand that engineering  
capacity is capital, and can they make the investment case for their  
roadmap in the language executives use?

**2. Team rebuild instinct** — At Director level and above, the interview  
question is rarely "what would you build?" It is "what would you do with  
the team you are inheriting?" Most candidates are not prepared for this.

**3. Platform thinking** — Indian founders who have raised a Series B or C  
are no longer interested in feature roadmaps. They want to know whether  
this product leader can identify the architectural bet that changes the  
company's trajectory. That requires a different kind of answer.

This OS trains for all three.

---

## Setup — Five Steps

### Step 1: Clone or use as template

```bash
git clone https://github.com/[handle]/product-leader-os
cd product-leader-os
```

Or click **"Use this template"** on GitHub for a clean copy.

### Step 2: Open in Claude Code

Open the `product-leader-os` folder as your Claude Code project.

### Step 3: Fill in your four core files

These are the minimum required before your first useful session:

```
knowledge/_me/proof-points.md       Your metrics. Named and verified.
knowledge/_me/career-arc.md         Your story. Compressed to the signal.
knowledge/target-company/company.md Their stage, funding, product, tech.
knowledge/target-company/interviewers.md One card per person you are facing.
```

Templates with instructions live in `/templates/`.  
Filled examples (anonymised) live in `/examples/`.

### Step 4: Set your phase and next conversation

Open `AGENTS.md` and complete the **Current Phase** section:
- Which role, which company, which stage
- Who is the next conversation with
- What that specific person cares about

### Step 5: Run your first session

In Claude Code, say:

> "Read AGENTS.md. Then read knowledge/_me/proof-points.md,  
> knowledge/target-company/company.md, and  
> knowledge/target-company/interviewers.md.  
> Confirm what context you have loaded.  
> Then simulate my next conversation with [name and role].  
> Play them as the hardest version of that person."

---

## How the Sessions Work

### Practice a specific interviewer
> "Simulate the [CEO / CTO / COO] conversation. Play them hard."

### Test a specific objection
> "Run the 'you haven't operated at this scale' objection."  
> "Run the 'your team will resist you' objection."  
> "Run the 'why should we hire you over an internal candidate' objection."

### Retrieve the right story
> "Which story from my career should I use when asked about  
> managing through ambiguity? Pull from my proof points."

### Frame the capital allocation argument
> "How do I present my investment thesis to a Series B founder  
> who is thinking about Series C positioning?"

### Debrief and log
> "Debrief that session using the interview-debrief skill and  
> log to memory."

---

## The Memory Layer

After every session, the system logs:
- What landed and why
- What was generic and the specific fix
- Which metrics were used and whether they were strong
- The one thing to change before the real conversation

Next session loads that log. The preparation compounds.

---

## Switching to Working Phase

Once you join, say: "I joined. Switching to working phase."

The OS shifts skills from interview preparation to operating as a  
product leader: capability assessment, decision logging, discovery  
synthesis, executive communication, architecture review.

Your interview prep context becomes the seed knowledge for how  
you operate inside the company.

---

## The India-Specific Layer

The `/knowledge/india-context/` directory holds context that is  
specific to the Indian product leadership operating environment:

- The cultural translation required when your background is partly US/global
- How INR metrics land differently than USD metrics in Indian board rooms  
- The specific dynamics of Series A through Series D Indian startup contexts
- The Bengaluru, Mumbai, and Delhi product ecosystem differences
- How to frame the "bodies not leverage" problem that is endemic to  
  Indian engineering organisations at scale

This context is loaded automatically when the target company is Indian.

---

## Skills Reference

| Skill | When to Use |
|---|---|
| `capital-allocator` | Framing roadmap as investment portfolio for C-suite |
| `executive-peer` | Practising peer-level strategic conversation with CEO/CTO |
| `org-designer` | Thinking through team rebuild, capability gaps, hiring plan |
| `story-retrieval` | Finding the right proof point for any question |
| `objection-response` | Practising the hardest objections for senior roles |
| `interview-debrief` | Logging what landed and what needs work |
| `team-diagnostics` | Capability assessment framework for inherited teams |
| `series-narrative` | Building the Series B/C/D product story |
| `culture-bridge` | Navigating Silicon Valley vs Bengaluru product culture gaps |
| `board-communicator` | Writing and framing board-level product narratives |
| `working-backwards` | Customer-first product thinking for any feature or platform bet |
| `decision-logger` | Logging key product decisions with context and alternatives |

---

## Contributing

PRs welcome for:
- New skill files that work for senior product leaders
- India-specific context additions (ecosystem, funding dynamics, cultural)
- Anonymised examples of strong proof-points or thesis files
- Objection libraries for specific types of companies or roles

See `CONTRIBUTING.md` for the format.

---

## Built From

This template was extracted from a real preparation system built for interviews at Indian tech companies.  
While the specific content has been removed, the architecture and the  
skill design are kept intact because they are universally applicable  
to any senior product leader preparing for a C-suite panel.

---

*Product Leader Interview OS — built for Directors and above,  
interviewing with founders and executives at Indian product companies.*
