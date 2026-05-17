---
title: "BSides Birmingham 2026 - Follow-Up"
date: 2026-05-16T12:45:00+01:00
# weight: 1
# aliases: ["/first"]
tags: ["bsides"]
author: "Jimmy"
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
# description: "Desc Text."
disableHLJS: true # to disable highlightjs
disableShare: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
# ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
    responsiveImages: true
---

As promised during my talk at BSides Birmingham on 16th May 2026, here is the content from my talk on the Full-Stack Human, and why a non-linear technical career builds better systems.

## Opening

**The Full-Stack Human**

*Why a Non-Linear Technical Career Builds Better Systems*

*BSides Birmingham 2026*

## If your career feels like Spaghetti Junction...

![Spaghetti Junction](/images/bsides-birmingham-2026/spaghetti-junction-crop.jpg)
...this talk is for you

## What you'll leave with

- **5 muscles** you can train, regardless of current role
- **1 playbook** for moving from reactive to proactive
- **1 mindset shift** for why generalism is a security superpower
And sports analogies...

## The Scenic Route in 30 Seconds

A career is a training plan, not a ladder
- Support
- Professional Services
- Technical Pre-Sales
- Developer Relations
- Architecture
![Straight ladder vs winding scenic path](/images/bsides-birmingham-2026/ladder-vs-path.png)


## Muscle 1: The Detective

**Every error message is a user interface.**
![Messy server rack / wall of error logs](/images/bsides-birmingham-2026/muscle1-detective.png)
- **The pattern:** 3am on-call, alert fatigue
- **In security:** SOC triage, incident response under pressure
- **Train it Monday:** shadow an on-call shift, sit with your SOC for an hour

### From the speaker notes

- Years watching things break in the wild
- Root-cause thinking = design philosophy, not just outage skill
- "Supported it → build it observable by default"
- "Can you ping it?" → systems should self-diagnose

## Muscle 2: The Builder

**"It works on my machine" is not a threat model.**
![Blueprint vs muddy construction site](/images/bsides-birmingham-2026/muscle2-builder.png)
- **The pattern:** gap between design doc and the real environment
- **In security:** paper controls vs pen test reality
- **Train it Monday:** deploy one of your own changes to prod, end-to-end

### From the speaker notes

- Unknown assumptions, unwritten rules, defaults — they bite
- Beautiful InfoSec policy ≠ real environment
- Consult: educate, explain, propose
- Not the decision-maker? You can still influence

## Muscle 3: The Storyteller

**Architecture is 80% people, 20% code.**
![Bridge between Technical Specs and Business Value](/images/bsides-birmingham-2026/muscle3-storyteller.png)
- **The pattern:** great technical ideas dying in boardrooms
- **In security:** mapping CVEs to business continuity risk to get controls funded
- **Train it Monday:** pitch one security project to a non-technical stakeholder

### From the speaker notes

- Techies called it "the dark side"… then I joined
- Best technical solution is worthless if you can't sell it
- Security: can't convince a stakeholder why a control matters → no funding
- "Storytelling is a technical requirement"

## Muscle 4: The Translator

**Friction is the enemy of security.**
![Universal translator or clean README snippet](/images/bsides-birmingham-2026/muscle4-translator.png)
- **The pattern:** tools no one uses, docs no one reads, policies people bypass
- **In security:** pasting secrets into Slack because your vault is hard
- **Train it Monday:** write the README for your own security tool, like a developer would

### From the speaker notes

- DevRel Sounds niche — but hear me out
- Tooling only as good as community's ability to use it
- Friction → smart people route around → control + shadow process (worse!)
- Empathy is a control surface, not a soft skill
- Black Hat firewall automation: only I used it → democratised UI → team adoption + accuracy + speed

## Muscle 5: The Architect

**Stop working tickets. Start spotting patterns.**
![Panoramic view of whole system](/images/bsides-birmingham-2026/muscle5-architect.png)
- **The pattern:** the reactive loop - alerts, tickets, fire-fighting
- **In security:** defense in depth requires whole-system view
- **Train it Monday:** pick one repeating alert and propose its replacement

### From the speaker notes

- Not coding, not on-call, not configuring firewalls
- See the whole system: humans, processes, business risk
- Think bigger picture

## The Cross-Training Effect

![Multi-tool with each tool labelled as a muscle, or Venn of 5 muscles](/images/bsides-birmingham-2026/multitool-muscles.png)

### From the speaker notes

- 1 muscle SOLVES a problem
- 2 muscles UNLOCK an opportunity
- All 5 build a career hard to replace
- Runners: not faster by only running, or only hamstrings — cross-train (swim, cycle)
- Engineers: not senior by only writing code; security pros not by only firewalls / endpoint / pen test
- The COMPOUNDING effect is the point

## From Whac-A-Mole to Approved

![Whac-A-Mole left, Approved-stamped proposal right](/images/bsides-birmingham-2026/whacamole-approved.png)
I stopped waiting for "tickets"
How?

### From the speaker notes

- 15 yrs reactive: tickets, boss, PMs, "the business" told me what to do
- Shift is not technical — it's behavioural
- Permission you give YOURSELF

## The Proactive Playbook

1. **Identify the pattern** - The Detective spots the repeating failure
2. **Build the prototype** - The Builder + The Architect ship a small, ugly version
3. **Sell the solution** - The Storyteller + The Translator make it the new standard

### From the speaker notes

- 1: Detective → spot repeating failure (support already trained you)
- 2: Builder + Architect → small ugly PoC (especially with AI)
- 3: Storyteller + Translator → make it the new standard
- Recent: SOC detection-rule dedup → PoC → demo'd → into prod in 2 weeks

## The Confidence Dip

![Confidence vs Time line graph showing the dip then climb](/images/bsides-birmingham-2026/confidence-curve.png)
The dip is the cost. **The climb is the muscle.** However...

### From the speaker notes

- "Confidence drops before it climbs"
- "Every domain pivot felt like starting from zero"
- Without this slide → talk = victory lap
- Cost of generalism: imposter syndrome — not saying it's easy
- Knowing nothing again / wondered if mistake / jealous of ladder paths
- "However…" → bridge to next slide

## You already have the muscle

| What you call it      | What architects call it     |
|-----------------------|-----------------------------|
| Ticket triage         | Resilience and fault tolerance |
| Customer workshops    | Stakeholder alignment       |
| "Just write the docs" | Developer experience        |
| Bug reproduction      | Threat modelling            |
| Runbooks              | Operational design          |


### From the speaker notes

- Everyone in the room has muscle they don't credit themselves for
- Reframing vocabulary unlocks progress

## May 2026: AI democratises execution. Not judgement.

- LLMs win at narrow artifacts
- Judgement lives across the stack
- Generalist territory
- Integration compounds

### From the speaker notes

- Skilling up with AI = a given, widely covered
- LLMs WIN narrow: Sigma rule · YARA sig · IAM policy · Terraform module
- LLMs DON'T have: threat model · risk appetite · data classification · team maturity
- That's where the generalist comes with the answers
- Integration muscle (experience + scars) compounds harder than execution skill

## Generalism is a Security Posture

Attackers move across the whole system.
Defenders cannot afford silos.
For example...

### From the speaker notes

- NOT a weakness to apologise for — it's a DEFENSIVE REQUIREMENT
- Siloed DBA / network engineer / app dev = tunnel-vision specialist
- Threat model spans the whole system
- JLR (down the road, £1.9bn, GDP impact): IT/OT generalist oversight? helpdesk ↔ identity boundary? — weak points
- M&S incident: similar traits

## The Final Four

- Don't rush to specialise
- Collect muscles, not certifications
- Speak Bash **and** Business
- Stop waiting for permission

### From the speaker notes

- "Four things for Monday."

## One last thing

The most complex system you will ever build,
is your own career.
**Build it generalist.**


## Let's talk about your scenic route...
