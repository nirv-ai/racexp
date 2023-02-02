# CTA - Context-Technoloy-Asides

- capture use case specifications, requirements & acceptance criteria without hardcoding top-down requirements or having to manage-up

---

nimlangs styleguide: replace `code` with whatever it is you do

> Good code usually happens after several rewrites.
> On the first pass: the focus is on the problem, not the code.
> When the problem is well understood, the code can be rewritten.

---

## Observations

- the race team is a smart team, but...
  - we need to be creative and remove innapropriate barriars that restrict our solutions
- usually the 1s and 0s are defined once we exit ideation, so...
  - shift right those 1s and 0s
  - shift left imagination

## First Principles

- CTAs should be living documents:
  - a single CTA can go through multiple iterations and races
  - ownership being passed between multiple drivers and amongst multiple race teams
- Participants should be responsive
- The process should be creative

## Outline

- context: the biz context; put on your CEO & forward-facing CTO hat
  - strive to provide what needs to be achieved, vs what needs to be completed
  - taking a declarative approach enables more flexibility in how downstream tasks materialize
  - the context should invoke questions of why, not questions of what or debates on how
- technology: the tech context & implementation strategy; put on your inward-facing CTO & engineer hat
  - how do we achieve the goals & vision setout by the context?
  - how do we build something resilient to future (and expected) changes
- asides: additional abbreviations supporting the biz & tech context

## F.U.N buckets

- each CTA should creative, profitable, and FUN!

### Fix

- brownfield > intolerables: straight to a race
- e.g. bugs, defects

### Upgrade

- bluefield > enhancements & restrictions: line up in the grid
- e.g. tests, documentation, redesign, revamps, improvements
- we dont use the word `refactor` in these parts of town cowboy

### New

- greenfield > rapid prototyping: require pit boss approval
- everyone loves something new
- but can we afford it? can we win if we enter the race?

## List of bad words

- Done: nothing is ever done, we're just moving the goalpost on what we're trying to achieve
  - instead: use Deployed, as we expect to bluefield everything in the future
- refactor: everything is an improvement, even new products are refactors of someone elses idea
  - instead: focus on the improvement/restriction that gets us closer to the finish line
- [Sprint](https://blogs.infosupport.com/3-reasons-for-using-sprints-and-why-they-may-be-bad/): i'll trade your predictability for adaptability anyday
  - instead: embrace the complexity, risk and potential for failure. Focus on change-management and short-feedback loops with immediate corrective actions

## FoF: frfr

- Focus On Features: Features Reap Future Revenue
- every CTA should be bourn from a feature needed/provided
  - need more testing? I loving buying durable products
  - need to revamp something? lets increment that release version
  - gotta fix this bug? converting existing customers to returning customers is a solid business approach
