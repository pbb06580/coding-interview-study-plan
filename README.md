# 3 month coding interview study plan: a 12-week schedule for patterns, timed practice, and mock interviews

Ninety days is the number most people land on when they have a real interview loop coming and no idea where to start. It's also the number that gets argued about the most — some guides say three months is the ideal runway, others say you need six. Anyone telling you "three months is plenty" without asking how many hours a week you can actually give is selling something.

So here's the useful framing. Three months is enough time to cover the patterns that show up in most coding interviews, practice them under a clock, and run a handful of mocks before the real thing. It is not enough time to grind 500 problems from scratch. The plan below picks the first option.

The other thing worth saying up front: this is a schedule, not a personality test. If you fall two days behind in week 5, you're still on track. If you skip month 3 because you got an offer, congratulations, the plan worked.

## What 90 days actually buys you

The standard recommendation across prep guides is roughly 11 hours a week for three months, which works out to about 140 hours. Give yourself more if you're starting from near-zero on data structures, less if you've interviewed in the past two years.

Split that budget honestly:

- **Pattern learning: ~35% of your time.** This is where you learn *why* a problem is a sliding-window problem instead of guessing. Text-based courses that map problems to named patterns are built for exactly this slice.
- **Volume practice: ~35%.** Applying the patterns to problems you've never seen, at increasing speed.
- **Mock interviews: ~15%.** Higher if you've ever frozen mid-interview. Lower if you already narrate your thinking well.
- **Everything else: ~15%.** Behavioral stories, system design if you're targeting mid-level and above, resume, and the arithmetic word problems that some companies still ask.

Notice that "watch 40 hours of lecture" isn't on that list. Passive learning feels productive and it doesn't transfer to a 45-minute interview where someone is watching you type.

## Three decisions to make before week 1

Make these now, in writing, and don't revisit them in week 6 when you're tired.

**1. Pick one language and stay in it.** Python and Java are the most common choices, and both are fine. Switching languages mid-plan is the most reliable way to reset your progress to zero.

**2. Know your target tier.** Interviewing at Google, Meta, or Amazon means dynamic programming, harder graph problems, and a system design round if you're mid-level or above. Interviewing at mid-size product companies and startups usually means arrays, strings, hashing, trees, and BFS/DFS done well. The difference is real and it changes how you spend month 3.

**3. Mark a fake deadline.** If your interview is 14 weeks out, treat week 12 as the interview. Mocks work better when there's a date attached.

## The 12-week study plan, phase by phase

### Phase 1 (weeks 1–4): build the pattern vocabulary

Month one is about coverage, not volume. You're learning roughly 20 core patterns and doing enough problems with each one that you can name it on sight. Expect to feel slow — that's the point. Rushing here is why people hit week 8 and still can't tell binary search on a rotated array from a two-pointer problem.

Don't chase hard problems in month 1. Medium problems solved with a clear template beat hard problems solved by looking up the editorial.

### Phase 2 (weeks 5–8): graphs, DP, and a clock

Phase 2 adds the two pattern families that take the longest to internalize: graphs and dynamic programming. It's also where a timer enters the room. From week 5 onward, target 25–30 minutes for a medium problem, and if you blow past 40 minutes without a working approach, read the solution and re-solve it two days later from memory.

Dynamic programming deserves special handling. It's the highest-variance topic in interviews and the one most people waste the most time on. If you're not targeting a company known for DP questions, learn the 1D and 2D basics and move on — that's the tradeoff course designers make explicitly when they tell you to skip ahead.

### Phase 3 (weeks 9–12): mocks, company sets, and the system design question

The last month is where most self-directed plans fall apart, because there's no new topic to learn and no obvious next step. Fill it deliberately: two mock interviews a week, company-specific questions for your top three targets, one weak area per week, and behavioral prep that you actually say out loud rather than just write down.

System design is the fork in the road. If you're interviewing for senior roles at large companies, 20–40 hours of dedicated system design prep is a realistic estimate, and a DSA-focused course won't cover it. If you're a new grad or targeting entry-level coding rounds, deprioritize it and spend those hours on mocks.

| Week | Focus | What to do | Checkpoint by Sunday |
| --- | --- | --- | --- |
| 1 | Arrays, strings, hash maps, two pointers | 8–10 easy/medium problems; learn the two-pointer template | Two array problems solved clean in 20 minutes |
| 2 | Sliding window, prefix sums | 8–10 problems; practice spotting when the window can shrink | Name the pattern of a new problem in under 2 minutes |
| 3 | Binary search variants, linked lists, stacks and queues | 8–10 problems; write binary search from scratch three times | No index off-by-one errors on binary search boundaries |
| 4 | Trees: BFS/DFS, BST properties, recursion | 10 problems; implement all four traversals from memory | Recursion traced on paper without drawing every frame |
| 5 | Graphs: BFS/DFS, grids, topological sort | 10 problems; start timing every medium at 30 minutes | Grid traversal written with no reference code |
| 6 | Heaps, priority queues, sorting-based patterns, intervals | 10 problems; merge-interval and kth-largest variants | Heap solution recognized without hints |
| 7 | Dynamic programming I: 1D (climbing stairs, house robber, LIS) | 8–10 problems; write the recurrence before the code | Can state the state and transition in plain words |
| 8 | DP II: 2D, knapsack, grid paths, string DP | 8–10 problems; add a second timed session each week | Two mediums back-to-back inside 60 minutes |
| 9 | Company question sets; first two mock interviews | Target top three companies; log every mistake by pattern | Mock debrief written with two concrete fixes |
| 10 | System design basics (if targeting mid-level+) or deeper graphs | 2 mocks; 5–6 hours of design reading and practice | Full mock completed without stalling |
| 11 | Behavioral stories, weak-pattern remediation | 2 mocks; rewrite STAR stories for five scenarios; patch your two worst patterns | STAR story delivered in under 2 minutes |
| 12 | Light review, easy problems, rest | Rapid pattern review; 2–3 easy problems daily; stop new topics by mid-week | Confident, not exhausted |

Fitting in the weekly hours matters more than the topic order. A realistic split is 1.5–2 hours on four weekdays plus one longer weekend block of three hours — that's 9–11 hours, and it holds up better than five-hour bursts followed by three days off.

## Where AlgoMonster fits in a 12-week plan

This is the piece most plans leave vague. "Learn patterns" is advice; it doesn't tell you what to read on Monday night.

[AlgoMonster](https://algo.monster?fpr=li69) is built around that gap. It's a DSA course from ex-Google engineers structured as 48 named coding patterns rather than a problem bank, which maps almost directly onto phase 1 and the graph/DP work in phase 2. Its own roadmap page recommends a specific order and splits the entry point two ways:

- **Foundation Course** — arrays, strings, linked lists, stacks, queues, hash tables, for people who are new to data structures or just learning to program.
- **Core Patterns** — the algorithmic patterns, for people who can already solve easy problems in about 15 minutes.

The per-section loop is short and repeatable: read the concept, take the quiz at the end, solve the section's practice problems, then run a **Speedrun** — multiple-choice pattern-recognition drills meant to build the "which pattern is this?" instinct fast. After the main sections there's the AlgoMonster 50 problem list, drawn from questions asked at larger companies, plus company-specific interview guides.

The free tier gives you limited access to a subset of patterns and problems. That's enough to judge whether the text-and-diagram teaching style works for you before paying — which matters, because format preference is the biggest variable in whether a course sticks. If you learn best from hour-long video walkthroughs, this isn't that.

## AlgoMonster plans and current pricing

The subscribe page currently lists two paid tiers and a free tier. Both paid plans include full access to all patterns, lessons and problems, unlimited use of the AI assistant, unlimited Speedrun, company question sets updated monthly, 500+ lessons across 6 courses, 1,000+ illustrations, and 3,000+ editorials.

| Plan | What you get | Price | Billing | Get access |
| --- | --- | --- | --- | --- |
| Free | Limited access to a subset of patterns and problems | $0 | — | [ Create a free AlgoMonster account](https://algo.monster?fpr=li69) |
| Pro Yearly | All patterns, lessons and problems; unlimited AI assistant; unlimited Speedrun; company questions updated monthly; 500+ lessons across 6 courses; 1,000+ illustrations; 3,000+ editorials; member discount on live bootcamps | **$99/year** | $8.25/mo, billed annually; 12 months of access | [ Subscribe to Pro Yearly](https://algo.monster/subscribe?fpr=li69) |
| Pro Lifetime | Everything in Pro Yearly, plus lifetime updates and no renewal | **$189** | One-time payment | [ Buy Pro Lifetime access](https://algo.monster/subscribe?fpr=li69) |

Two notes. First, aggregator sites and older reviews still quote numbers like $459 for lifetime access or $119–$299 for the annual plan — those are stale, and the official subscribe page is the only number that counts. Second, AlgoMonster runs promotions often, so the price you see on any given day may be lower than the list price above. Worth checking before you buy rather than assuming.

## Is the paid tier worth it for a 12-week sprint?

Do the arithmetic on your own schedule instead of the sticker price.

For a 90-day push, Pro Yearly at $99 works out to about **$1.10 a day**, and it covers the entire plan. The lifetime plan at $189 is roughly double the annual cost, one time. It only makes sense if you expect to interview again — which, for most engineers, is a matter of when rather than if. If this is a single job change and you're done after it, the annual plan is the cheaper bet, and you can decide about lifetime later.

Where the paid tier earns its money is the middle of month 1, when you're staring at a list of 500 patterns-vs-problems questions with no idea which order to study them in. That's the specific problem the ordered curriculum solves. It doesn't solve getting faster — that's still reps and a timer.

One honest caveat on fairness: if you can already identify patterns quickly and your real weakness is volume and speed under pressure, the money is better spent elsewhere, and you should read the next section carefully.

## What this plan won't cover

The recurring criticism in published reviews of AlgoMonster is consistent, and it's worth taking literally rather than as a knock: the platform is text-and-diagrams, its system design content is introductory, and every problem is solved at your own pace with nobody watching. Those are the real gaps in a three-month plan, and each needs a patch.

- **Live pressure.** Nothing in a self-paced course simulates a 45-minute interview with follow-up questions. Run two mocks a week from week 9. Peer mocks through your network, a friend at your target company, or a paid service all work.
- **System design.** For L5+ roles at large companies, budget 20–40 hours separately. A DSA platform won't substitute.
- **Behavioral rounds.** Amazon's Leadership Principles and Meta's cross-functional questions need their own prep. Five written STAR stories, rehearsed out loud, is the minimum.
- **Volume.** A few hundred problems is enough to learn patterns; top-tier loops reward speed that comes from more reps. Company-tagged problem sets on any large problem bank cover this, and the standard advice in prep communities — learn patterns first, grind volume second — holds up.

## Five ways a 3-month plan goes wrong

1. **Starting with hard problems.** They teach you less per hour and cost you the confidence you need in week 9.
2. **Skipping the clock.** Solving problems correctly with no time limit is a different skill from solving them in an interview. Add timing by week 5 at the latest.
3. **Never saying anything out loud.** Interviewers score your reasoning, not just your output. Narrate while you code, even alone.
4. **Reading solutions as your main method.** Reading an editorial feels like progress. Re-solving the same problem two days later from memory is progress.
5. **Restarting the plan.** Every restart resets you to week 1. Finish the 12 weeks, imperfectly.

## How to know you're on track

Skip the vague self-assessment and use checkpoints. By the end of week 4 you should be able to name the pattern behind a new medium problem in a couple of minutes. By the end of week 8, you should be finishing two mediums in an hour with a working approach. By the end of week 11, you should have completed at least six mocks and have a written list of your three most common mistakes.

If you're missing those, the fix is rarely "study harder." It's usually "cut the scope" — drop DP for a non-DP company, or drop system design if your loop doesn't include it.

## Short answers

**How many hours a week do I need?** Around 11 is the commonly cited minimum for a three-month plan. Under six hours a week, plan for five months instead of three.

**Should I buy a course or just use a problem bank?** If you can't explain why a problem is a sliding-window problem, use a structured pattern course first. If you can, spend the money on more problems and mocks.

**Do I need both a pattern course and LeetCode?** Most people end up using both, and the sequencing that comes up repeatedly is patterns first, volume second. [👉 Start with the AlgoMonster pattern curriculum](https://algo.monster/subscribe?fpr=li69) during weeks 1–6, then move practice volume to a larger problem bank in weeks 7–12.

**Is 12 weeks enough for a senior loop?** For the coding rounds, usually. For the full loop including system design and behavioral, you'll want to start earlier or accept that month 3 will be crowded.
