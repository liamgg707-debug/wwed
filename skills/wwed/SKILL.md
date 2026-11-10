---
name: "wwed"
description: "What Would Elon Do: take any situation, find the single limiting factor from first principles, and lay out how to clear it. Use when asked for wwed, a bottleneck or limiting-factor analysis."
---

# WWED: What Would Elon Do

A method for finding the one thing that limits speed toward a goal, and clearing it.

It is distilled from 39 public sources, about 559k words of Elon Musk's own interviews, factory tours, shareholder meetings and talks from 2012 to 2026. Source tags like (S014) mark which source a rule or quote came from; the source list itself is not included.

This is an analysis tool, not a persona. No debate, no council, no scoring rounds. Do not speak as him or imitate his voice. Quote him only with the exact lines below, never invented ones.

Everything needed for a run is in this file.

## Worldview in three lines

- Physics sets the floor on cost and speed. Almost everything above the floor is process, habit and dumb requirements.
- So question and delete before anyone optimizes or automates.
- The leader's time goes to whatever limits progress right now. What is working gets left alone.

## The core tools (ranked by how often he uses them)

**1. Tackle the limiting factor.** (12 sources)
- Find the one input capping speed right now, solve it, then ask again.
- Pick a point in time first. The limit this month is not the limit in three years.
- Money, people and the founder's hours follow the bottleneck. If nobody else will fix it, fix it yourself.
- Predict the next bottleneck before the current one clears.
- "I just repeatedly tackle the limiting factor. Whatever the limiting factor is on speed, I'm going to tackle that." (S002)
- "if something is working well and making good progress, then there's no point in me spending time on it." (S002)

**2. The algorithm. The order is the point.** (10 sources)
1. Make the requirements less dumb. Each one gets a named person, never a department.
2. Delete the part or step.
3. Simplify or optimize. Only now.
4. Accelerate cycle time.
5. Automate. Last.
- "make your requirements less dumb. Your requirements are definitely dumb." (S014)
- "if you're not adding things back in 10% of the time, you're clearly not deleting enough." (S014)
- "possibly the most common error of a smart engineer is to optimize a thing that should not exist." (S014)
- He admits doing all five steps backwards himself on the Model 3 line (S014). Most waste comes from wrong order.

**3. First principles.** (12 sources)
- Boil the problem down to the facts most likely to be true, reason up from them, check against physics.
- Reject "the industry does it this way" as a reason. Copy the principle, not the form.
- It failed him when he accepted the standard answer: Starship started in carbon fiber and should have been steel from the start (S002).

**4. The material floor and the million-units test.** (6 sources)
- Price the thing from its raw inputs. That is the floor. The gap between floor and actual cost is process, and process can be cut.
- "If it's still expensive at a million units a year, then volume is not the reason why your thing is expensive." (S006)
- For a service business, the floor is the cheapest raw input to one unit of the goal (for example the price of one lead, or the labor for one job). Compare it with the real cost per finished unit.
- Do not call this the "idiot index". That name is not in the source transcripts.

**5. Requirements with a name.** (5 sources)
- Every rule, constraint and recurring cost needs a person who will defend it. His example: a requirement traced to an intern who had left two years earlier (S014).

**6. Delete the part, delete the process.** (13 sources)
- Ask of each step: is it necessary to solve the problem in front of us now? If not, delete or punt it.
- "In case" arguments keep almost everything alive. Keep deletions reversible.

**7. Decompose the impossible.** (6 sources)
- When told something takes far longer than you need, break it into parts and find a workaround for each. Set the deadline from what you need, not from the quote.

**8. Physical-unit math.** (10 sources)
- Work in real units. Get each key number right to a factor of ten before acting. Push a variable to its extreme to see what still matters.
- Ask which number in the plan is wrong.

**9. Make it work, then make it efficient.** (8 sources)
- Get one working version by any means, small first. Optimize after.

**10. Risk dial.** (10 sources)
- Iterate fast and accept failures where nobody gets hurt. Be conservative where customers or people carry the risk.

**11. The 50th percentile deadline.** (11 sources)
- Internal date you would hit about half the time, because work expands to fill the schedule.
- His dates slip by years. Use the aggressive date for the team only. Hedge anything promised to customers or lenders.

**12. Time goes to the limiting factor.** (11 sources)
- Review the limiting item weekly or more with the people doing the work. Go where the work happens. Protect against context switching.

**13. One metric.** (12 sources)
- Pick one hard-to-fake number for the whole effort before arguing about priorities.

**14. Close the loop on reality.** (7 sources)
- Ask for negative feedback. Don't grade your own homework. Treat every action the customer is forced to take as an error to shrink.

## Process

Gather facts first. Read the project docs, data and numbers available before asking the user anything. Use real numbers. If a number is missing, say so and state the assumption.

1. **Goal.** One metric in real units per unit of time. If the user's goal is vague, pick the likeliest metric and say so.
2. **Chain.** List the 4 to 8 steps that must happen in order for one unit of the goal to come out.
3. **Measure.** For each step: current rate, capacity, how full it is. Mark guesses. Sanity-check each number to a factor of ten.
4. **Name the limiting factor at a date.** The step with the lowest throughput relative to what reaches it, as of now. Doubling test: if this step doubled, would the goal move right away? If not, it isn't the limit. Check nothing upstream is starving it.
5. **Physics or process?** State the floor for that step and the ratio of actual to floor. Then reason from first principles: what has to be true for a unit to pass this step? Which of those is failing? Stop at a fact, not a habit.
6. **Run the algorithm on that step only, in order.**
   - Requirements: list each rule in the way, who set it, and whether it still holds.
   - Delete: what goes. Expect to add about 10% back.
   - Simplify: only what survived.
   - Accelerate: cut the cycle time.
   - Automate: last, and only if the step is now proven.
7. **Risk dial.** Say where failure hurts nobody (move fast) and where a customer or person carries the risk (stay careful).
8. **Date and test.** The cheapest fast test, one action that starts within 24 hours, a half-odds internal deadline, and the number that proves it worked.
9. **Founder time.** Where the person's hours go this week, and what gets zero.
10. **Next limiting factor.** What binds once this clears, and the trigger for switching.

## Signature questions to ask of any plan

These are paraphrased from his rules, not quotes.

- Which requirement here is dumb, and whose name is on it?
- What would you delete if you had to cut half the steps?
- What is the limiting factor this month?
- Is this expensive because of physics or because of how you do it?
- Which number in your plan do you think is wrong?

## Output format

Keep it short. Follow the user's own formatting preferences if they have them. Otherwise:

- **Goal:** one line with the metric.
- **The chain:** small table of step, current rate, capacity, verdict.
- **Limiting factor (as of date):** one sentence, plus the doubling test.
- **Physics or process:** the floor, the ratio, and 2 to 4 first-principles bullets.
- **Clear it:** the five algorithm steps, one or two bullets each, requirement owners named.
- **Next 24 hours:** one action.
- **Proof it worked:** one number and a date.
- **Next limiting factor:** one line.
- **Stop doing:** short list of work that is off the limiting factor.
- **Confidence:** one line, with what data would change the answer.

## Where this lens misfires (say so when it applies)

- **Services and audience businesses.** Delete-first, cycle time and the limiting factor apply to delivery and to the sales funnel. Cost-from-materials and build-it-yourself mostly do not.
- **Marketing and offers.** The source material has little on discounting, paid ads or pricing. Find the limiting factor with this lens, then use other evidence for the fix.
- **Small-founder capital.** Betting the company at 10% odds comes from someone who can raise billions. Do not recommend a bet the user cannot survive losing.
- **People.** His hours are not a quota for anyone else. Do not prescribe overwork.
- **Over-deletion.** In safety, legal, regulated or trust-critical areas, keep the dial conservative. "Delete the requirement" never covers legal, safety or honesty requirements. Mark those as fixed.
- **Outside promises.** Aggressive dates are internal only.

## Rules

- One limiting factor. If two look tied, say which you'd bet on and why. Never hand back a list of five.
- Never recommend speeding up, scaling or automating a step before the delete step has been done.
- Small samples get called small.
- Respect the user's standing rules and constraints. Flag one as worth questioning if it is the limiting factor, but leave the decision to them.
- Analysis only. Change nothing in the user's systems unless asked.