# Project180 — Progress Log

**Track:** Data Engineering → AI Engineering
**Day 1:** Tue 1 Sep 2026 · **Day 180:** Sat 27 Feb 2027
**Through-line:** local data infrastructure for maternal health + low-resource NLP
**Public:** #180ToShow · @elmustyy_

---

## How to use this

Three levels, three different cadences. Don't do all three every day.

| Level | When | Time | Purpose |
|---|---|---|---|
| Daily log | Every day, end of session | 2 min | Proof you showed up. Nothing more. |
| Weekly review | Sundays | 15 min | Catch drift early. |
| Block review | Every 30 days | 45 min | Did you ship? What changed? |

The daily log is the only non-negotiable. If you're too tired to write more than one line, write one line. A skipped log is worse than a bad log — the streak is the asset.

---

## Daily log

Copy this block. Newest entry at the top of the file, so the log reads most-recent-first.

```
### Day 004 — Fri 4 Sep 2026
**Time:** 1h 20m
**Worked on:** window functions — RANK vs DENSE_RANK vs ROW_NUMBER
**Shipped/committed:** 3 solutions pushed to sql-problems repo
**Stuck on:** still don't intuit when PARTITION BY changes the frame
**Tomorrow:** finish the DataLemur medium set, start CTEs
```

Five fields. Don't add more — the moment logging feels like work you'll stop doing it.

**Rules:**
- Log the time honestly, including the bad days. `Time: 45m, mostly re-reading yesterday` is a real entry.
- "Stuck on" is the most valuable field. It's your future blog posts, your interview stories, and the thing that makes your public posts worth reading. Never leave it empty by pretending you weren't stuck.
- If you take a flex day, log it: `### Day 031 — FLEX DAY (4/10 used)`. Flex days are part of the plan, not failures.

---

## Weekly review

Every Sunday. Fifteen minutes, honest answers.

```
## Week 01 — 1–6 Sep 2026
**Days logged:** 6/6 · **Total hours:** 9h 15m · **Flex used:** 0/10

**What actually got built this week:**


**What I said I'd do and didn't:**


**Concept I understand now that I didn't last Sunday:**


**Biggest time sink (and was it worth it?):**


**Adjustment for next week:**
```

The "said I'd do and didn't" question is the one that keeps this honest. If the same item appears three weeks running, it's not a task problem — either it's harder than you scoped or you don't actually want to do it. Both need a decision, not another week of deferral.

---

## Block review

Every 30 days. This is where you decide whether the plan is still the right plan.

```
## Block 1 Review — Days 1–30 (1 Sep – 30 Sep 2026)
**Theme:** SQL deeply + Git/Docker/Python-as-software
**Ship target:** SQL problem set repo (30 hard problems + explanations)

**Did I ship it?** Y / N / Partially —
**Link:**

**Hours total:** ___ · **Days logged:** ___/30 · **Flex used:** ___/10

**Three things I can do now that I couldn't on Day 1:**
1.
2.
3.

**Where the plan was wrong:**


**What I'm carrying into Block 2:**


**Public artifact from this block** (thread, writeup, repo README):
```

---

## Ship log

The part that matters. Everything else is process; this is evidence.

| Block | Days | Dates | Target | Status | Link |
|---|---|---|---|---|---|
| 1 | 1–30 | 1 Sep – 30 Sep 2026 | SQL problem set repo — 30 hard problems + explanations | Not started | |
| 2 | 31–60 | 1 Oct – 30 Oct 2026 | Maternal health classifier refactored: tested, containerised | Not started | |
| 3 | 61–90 | 31 Oct – 29 Nov 2026 | Scheduled pipeline on Nigerian data, running unattended | Not started | |
| 4 | 91–120 | 30 Nov – 29 Dec 2026 | Post-mortem: 30 days of production failures + fixes | Not started | |
| 5 | 121–150 | 30 Dec – 28 Jan 2027 | dbt analytics layer + public application tracker | Not started | |
| 6 | 151–180 | 29 Jan – 27 Feb 2027 | Pidgin NLP model in production: endpoint + eval numbers | Not started | |

Status values: `Not started` → `In progress` → `Shipped` → `Shipped + written up`

A block isn't done when the code works. It's done when someone else can look at it and understand what you built.

---

## Running counters

Update weekly. These are the numbers you'll want on Day 180.

```
Days logged:        ___ / 180
Total hours:        ___
Flex days used:     ___ / 10
Longest streak:     ___
Repos shipped:      ___
Public posts:       ___
Applications sent:  ___   (starts Block 5)
Interviews:         ___
```

---

## Concept ledger

Every time something clicks, write it here in one sentence in your own words. Not notes — notes go elsewhere. This is a list of things you understand.

```
- Day 004 · A window function doesn't collapse rows; GROUP BY does. That's the whole difference.
- Day ___ ·
```

By Day 180 this file is the most convincing thing in your portfolio. It's also the raw material for every thread you'll write, and it's what you read on the days you feel like you've learned nothing.

---

## Stuck ledger

Problems that cost you more than an hour. Log the fix when you find it.

| Day | Problem | Time lost | Resolution |
|---|---|---|---|
| | | | |

Two reasons this exists. One: you will hit the same problem twice, and past-you already solved it. Two: "tell me about a time you debugged something hard" is an interview question, and most juniors have no answer because they never wrote it down.

---

## Notes on honesty

This log only works if it's true. The temptation around Day 40 is to log hours you didn't work, or to write "shipped" for something half-finished. Nobody's auditing you — which is exactly why it matters.

A log with 140 honest days and 40 gaps is more useful than 180 fabricated ones. The gaps tell you when your system breaks: exam weeks, travel, the week after a big ship. That's information you need for Block 6, and for whatever you run after this.
