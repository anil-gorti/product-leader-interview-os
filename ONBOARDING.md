# Onboarding Guide

**Complete this before your first Claude Code session.**  
Estimated time: 90 minutes for the core files. Worth every minute.

---

## The Minimum Viable Setup (do these first)

These four files are the minimum required for a useful first session.  
Everything else compounds on top of them.

### 1. knowledge/_me/proof-points.md
Your career metrics. Named, verified, sourced.

The most common mistake: vague numbers.  
"Improved engagement significantly" is not a proof point.  
"Reduced time-to-first-value from 14 days to 6 days for the enterprise cohort" is.

**Rule**: if you cannot remember the exact number, write your best estimate  
and mark it [VERIFY BEFORE USING]. Do not cite it until you have confirmed it.

Use the template at `templates/proof-points-template.md`.  
See a filled example at `examples/proof-points-filled.md`.

### 2. knowledge/_me/career-arc.md
Your story, compressed to the signal that matters for this role.

Not a resume. Not a timeline. The answer to: what is the through-line  
of your career, what did you learn at each stage, and why does this  
role represent the right next chapter?

A strong career arc has three parts:
- The formation: what shaped how you think about product
- The evidence: what you built and what it proved
- The thesis: what you now believe about what great product leadership does

Use `templates/career-arc-template.md`.

### 3. knowledge/target-company/company.md
The target company intelligence. Not from their website — from your analysis.

What stage are they at? What is the product actually doing well and  
what is it not doing yet? What does the founding team care about at  
this specific moment? What is their Series C / IPO story and does the  
product currently support it?

Use `templates/company-template.md`.

### 4. knowledge/target-company/interviewers.md
One card per person you are meeting.

For each person:
- Their background (not from LinkedIn summary — from their actual career)
- What they care about in a product leader
- The real test they are running (usually not the question they ask)
- The one trap this person typically sets
- The language that lands with them specifically

Use `templates/interviewer-card-template.md`.

---

## The Full Setup (do these before panel rounds)

Once the four core files are complete, fill these in priority order:

**Priority 2 — Your strategic thesis**
```
knowledge/strategy/my-thesis.md
knowledge/strategy/30-60-90.md
knowledge/strategy/investment-bets.md
```

**Priority 3 — The analogies layer**
```
knowledge/analogies/
```
For each major proof point in your career, create a file that maps  
the structural parallel to the target company. The best analogies are  
ones where the architecture of what you built is identical to what  
the target company needs — different domain, same primitive.

**Priority 4 — Domain vocabulary**
```
knowledge/domain/vocabulary.md
```
25 domain terms with analogies drawn from your own professional experience.  
The goal: never pause in an interview because a term is unfamiliar.

**Priority 5 — India context (if applicable)**
```
knowledge/india-context/
```
See the files already provided in this directory. Add your own  
observations from your operating experience in the Indian market.

---

## First Session Command

Once the four core files are filled, open Claude Code and say:

> "Read AGENTS.md. Then read knowledge/_me/proof-points.md,  
> knowledge/_me/career-arc.md, knowledge/target-company/company.md,  
> and knowledge/target-company/interviewers.md.  
> Tell me what context you have and what is missing.  
> Then tell me the three areas where my preparation has gaps."

This gives you a diagnostic before you start practising.

---

## The Session Rhythm

**Session 1**: Gap diagnostic. What is missing from the knowledge files.  
**Session 2**: Simulate the hardest conversation (usually the CEO or founder).  
**Session 3**: Run the three most likely objections for this specific role.  
**Session 4**: Simulate the technical or strategy deep-dive (CTO or board).  
**Session 5**: Full panel simulation. All conversations back to back.  
**Night before**: 20-minute review. Ask: "What are the three things I must  
not forget tomorrow?"

---

## What Not to Do

Do not start practising before the knowledge files are filled.  
Without context, Claude Code gives generic answers that sound good  
and are useless preparation for a specific senior conversation.

Do not practise only the questions you are comfortable with.  
The session that is most valuable is the one where the AI plays  
the hardest version of the interviewer and you are genuinely  
uncomfortable for the first few minutes.

Do not skip the debrief.  
The memory layer is only as good as what gets logged.  
A session without a debrief is a session that does not compound.
