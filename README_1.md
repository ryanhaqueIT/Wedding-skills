# 🎀 Wedding Planning Skills for Claude

## What Is This?

A **skill** is a document that teaches Claude how to think like *you* — an experienced wedding planner. Without a skill, Claude gives generic textbook advice. With your skill loaded, Claude follows your exact process, uses your benchmarks, and knows your tricks.

**You don't need to write any code.** You just need to answer questions about how you do your job, and put the answers into a simple template.

---

## How It Works (30-Second Version)

Think of it like training a new junior planner — except you only do it once.

You write a document that says:
- "When someone asks about **X**, here's exactly how I'd handle it"
- "Here are the mistakes rookies make"
- "Here are the numbers/benchmarks I actually use"
- "Here's what I always check that others forget"

Claude reads your document and follows your methodology instead of making things up.

---

## How Claude Uses Your Skill (The 3 Layers)

Think about how you work with a client. You don't dump everything on them in meeting one.

| Layer | What It Is | Analogy |
|-------|-----------|---------|
| **1. The Label** | Skill name + one-line description | The label on a filing cabinet — Claude sees this always, decides if it needs to open the drawer |
| **2. The Playbook** | Your full step-by-step process | What's inside the folder — Claude reads this only when the topic comes up |
| **3. The Reference Files** | Checklists, templates, vendor lists | The detailed attachments — Claude grabs these only when actively working on a specific task |

This means Claude isn't overwhelmed. It only loads what it needs, when it needs it.

---

## Your Skill Library (Build in This Order)

### 🟢 Start Here (Highest Impact)
1. **Client Intake & Consultation** — discovery process, qualifying questions, setting expectations
2. **Budget Planning & Allocation** — category breakdowns, regional benchmarks, tracking methodology  
3. **Vendor Procurement** — vetting criteria, negotiation frameworks, contract review checklists

### 🟡 Build Next
4. **Venue Selection & Evaluation** — capacity analysis, site visit checklist, contract red flags
5. **Day-of Timeline Creation** — ceremony-to-reception flow, vendor arrival schedules, buffer calculations
6. **Guest Management & RSVPs** — tracking, dietary requirements, seating chart logic

### 🔵 Specialized Skills
7. **Design & Styling** — theme development, colour palettes, décor coordination
8. **Contract & Payment Management** — payment schedules, clause review, dispute handling
9. **Rehearsal Coordination** — run-of-show, roles briefing, timing
10. **Destination Wedding Logistics** — travel coordination, legal requirements by location
11. **Cultural Ceremony Integration** — multi-faith ceremonies, cultural protocols, family dynamics
12. **Weather Contingency Planning** — Plan B triggers, indoor/outdoor switchover logistics
13. **Post-Wedding Wrap-up** — vendor settlement, reviews, final client deliverables

---

## How to Build Each Skill

### Step 1: Brain Dump

For each skill, answer the questions in **[INTERVIEW-GUIDE.md](./INTERVIEW-GUIDE.md)**. Just talk — write messy notes, voice-record yourself, whatever works. Don't worry about formatting.

### Step 2: Fill In the Template

Copy **[TEMPLATE.md](./templates/TEMPLATE.md)** and fill it in using your brain dump. There's a completed example at **[examples/client-intake.md](./examples/client-intake/SKILL.md)** so you can see exactly what "done" looks like.

### Step 3: Add Your Secret Sauce 🌶️

**This is the most important part.** Generic advice is worthless — Claude already knows generic advice. What makes your skill valuable is the stuff only YOU know from years of experience:

- The specific numbers and benchmarks you actually use (not textbook numbers)
- The questions you always ask that other planners don't
- The vendor negotiation tactics you've refined over the years
- The timeline buffers you've learned are essential (e.g. always add 30 min between ceremony and reception for photos running long)
- The contract clauses you always push back on
- The seasonal pricing patterns you've noticed in your region
- The early warning signs that a client/vendor/venue is going to be a problem
- The recovery plays when something goes wrong day-of

**If you're thinking "everyone knows that" — they don't. Write it down.**

### Step 4: Test It

Give the skill to Claude and ask it a realistic question. Then check: "Would I have said that? Did it miss anything? Did it give bad advice?" Refine and repeat.

---

## File Structure

Each skill is just a folder with a text file (and optionally extra reference files):

```
wedding-planning-skills/
├── README.md                          ← You're here
├── INTERVIEW-GUIDE.md                 ← Questions to answer for each skill
├── templates/
│   └── TEMPLATE.md                    ← Copy this for each new skill
├── examples/
│   └── client-intake/
│       └── SKILL.md                   ← Completed example to reference
└── skills/
    ├── client-intake/
    │   └── SKILL.md                   ← Your completed skills go here
    ├── budget-planning/
    │   └── SKILL.md
    ├── vendor-procurement/
    │   ├── SKILL.md
    │   └── references/
    │       └── contract-checklist.md  ← Optional extra reference files
    └── ... (one folder per skill)
```

---

## Quick Rules for Writing Good Skills

1. **Be specific, not vague.** "Consider the budget" is useless. "Venue should be 40-50% of total budget; if total is $50K, don't show venues over $25K" is gold.
2. **Write it like you're training someone.** Step-by-step. What to do first, second, third.
3. **Include real examples.** "Last year I had a couple who..." makes the skill 10x better.
4. **Add what can go wrong.** Troubleshooting sections save the most time.
5. **Keep each skill focused.** One skill = one topic. Don't cram everything into one file.
6. **Update as you learn.** Skills aren't set-and-forget. When you discover something new, add it.
