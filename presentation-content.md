# Building a Research mechanism

## Taking Back Control

Engineering & Product Leadership Review  
Audience: DXD

## Summary

This presentation argues that the team should build its own lightweight product intelligence capability instead of relying on fragmented analytics tools and analyst-heavy workflows. The core idea is to start small, use UX research to define what should be measured, and create a repeatable loop where product decisions are informed by owned usage data.

The proposed first step is to instrument Order Action as a focused research case, collect a limited set of user interaction signals, and use those findings to guide roadmap decisions. The broader goal is to move from reactive decision-making to a model where engineering, product, and UX operate with clearer evidence and tighter feedback loops.

## From Data Chaos to Product Intelligence

TAKING BACK CONTROL

Engineering & Product Leadership Review

## The Data Clarity Problem

BACKGROUND

Today's analytics tools promise insight but deliver complexity.

- Fragmented Tools: Power BI, Analytics, ContentSquare — each showing a different slice of truth. No single source of reality.
- Expert Dependency: Only data analysts can navigate dashboards. PMs and engineers wait in queue for answers to basic questions.
- Lagging Signals: By the time reports surface, the product has moved on. Insights are historical artefacts, not decision tools.

## Interfaces Should Respond to Users

BEYOND STATIC PAGES

The era of one-size-fits-all dashboards is over. Data lets us build experiences that adapt.

- Context-Aware: Surfaces that show the right information to the right person — not the same page for every role.
- Driven by Real Usage: When we own our data, we can shape the interface around how people actually use the product.
- Continuously Improving: Static pages are built once and forgotten. Data-driven interfaces get better every release.

## The Window Is Now

THE OPPORTUNITY

AI amplifies teams that already have signal. Without data, it just moves faster in the wrong direction.

- Data Informs Everything: Every product decision — what to build, what to drop, what to fix — gets sharper when it's grounded in real usage.
- AI Needs Research to Work: AI is only as good as the context it gets. A team with owned data can prompt, automate, and build in ways others can't.
- Position the Team: This is how we stop being reactive. Owning our data layer is how we show up as a team that leads with intelligence.

## We Start Small, We Move Fast

OWNING OUR DATA

We don't need a perfect data platform to begin — we need ownership and momentum.

- Start Small: We begin by collecting our own data now — no big platform migrations, no waiting for perfect infrastructure.
- Intelligence Over Intuition: Strong opinions are good. Strong opinions backed by data are better. We add signal to every call we make.
- UX Research at the Centre: This isn't just engineering infra — UX Research drives what we measure, what we learn, and where we go next.
- Feedback Loops: Every release feeds back into the data. We learn faster with each cycle and compound that over time.

## Collect → Distill → Improve

THE LOOP

A continuous intelligence flywheel that compounds product quality over time.

1. Collect: Capture user events, errors, performance signals into our own data layer — structured, versioned, owned.
2. Distill Insights: Transform raw events into actionable product signals: retention patterns, friction points, feature adoption.
3. Improve Product: Feed insights directly into the roadmap. Every sprint is informed by real usage — not intuition or guesswork.

## How do we get started?

Let's align on next steps

1. Define 1 core product questions we need data to answer.
2. Agree on data ownership model and where we centralize.
3. Start working on it as soon as we can.

## Order Action as Our First Resarch Signal

WHERE WE START

We don't need to boil the ocean. Order Action is a known problem with a clear data story waiting to be told.

- A Known Problem: Order Action has friction we've felt but never measured. This is our chance to stop guessing and start knowing.
- A Clean Data Opportunity: The events are there to capture. User actions, drop-offs, error states — structured, owned, queryable by us.
- Small Enough to Start: This isn't a platform migration. It's one flow, one data layer, one feedback loop. The perfect first step.
- Fast Enough to Learn: A tight scope means we see results quickly — and build the muscle for every feature that comes after.

## Order Action: Let's Make It Real

WHERE WE START

1. Log all action clicks to a GCP Bucket — same approach as smiley feedback.
2. Cap at 20k clicks for now, exportable as JSON for easy access.
3. We analyse the data, identify patterns, feed findings into the roadmap.

## Control When We Listen

WHERE WE START

Logging everything all the time isn't the goal — the goal is collecting the right data at the right moment.

- Collect With Intent: We only log when we have a research question to answer. No data debt, no noise, no storing what we can't handle.
- UX Research-Led: UX defines when logging goes live — tied to a study, a hypothesis, a sprint. Data collection becomes a research act.
- Repeatable by Design: Turn it on, gather signal, turn it off, analyse. A lightweight rhythm we can run as often as we need.
- Flagga-Controlled: We add a toggle in Flagga to turn logging on and off — no deploys, no tickets, just a switch we own.

## What do you think?

OPEN DISCUSSION

How do you see this from your perspective? What would you add, challenge, or do differently?

Contact olof.bustamante@ingka.ikea.com