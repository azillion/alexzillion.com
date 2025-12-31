---
title: "When Code Is Cheap, What Do You Race On?"
description: "Code is getting cheap. What was the bottleneck (skilled labor to produce working software) is becoming commoditized. So what's the new bottleneck?"
date: 2025-12-28
tags: ["AI", "software", "career"]
---

_70% confidence. a bet about the next 2-3 years, not a general theory._

# The Premise

code is getting cheap. not free, but cheap enough that the bottleneck is shifting.

for most of software history, the constraint was labor. skilled humans who could translate intent into working systems. companies competed for this labor. they hoarded it. the best engineers were the moat.
that's breaking down. not because engineers are worthless. because the floor is rising. a mid engineer with ai tools now ships what a senior engineer shipped three years ago. the distribution of "good enough" expanded.

so what's the new bottleneck? the obvious answers are capital, distribution, data, trust. these matter. but they're slow-moving; inertial at a 6-month cadence. they assume a new equilibrium where you figure out the game and then play it.

what if there isn't an equilibrium? what if the ground keeps moving?

**During capability acceleration, adaptation velocity dominates, until the bottleneck becomes customer adoption and trust.**

## Definitions

before going further, some terms:

- **"code is cheap"** = marginal cost of implementing a feature approaches zero relative to validation + integration
- **"adaptation velocity"** = time-to-integrate-new-capability into production workflow
- **"customer metabolism"** = rate of change the buyer can absorb without trust or regulatory failure

## The Red Queen

there's a line from Through the Looking Glass. the red queen tells alice: ["it takes all the running you can do, to keep in the same place."](https://sabian.org/looking_glass2.php) this is how [evolution works](https://fs.blog/the-red-queen-effect/). the antelope doesn't need to be fast. it needs to be faster than the other antelopes. and it needs to keep getting faster, because the cheetahs are also adapting. there's no finish line. fitness is relative and temporary. i think this is where we are with ai. the capabilities landscape shifts every six months. what worked in january is table stakes by july. you're not trying to reach a destination. you're trying to maintain a speed.

## Two Races

here's the core model: you're running two races at once.

**race one is internal.** can you integrate new capabilities faster than your competitors? can you build systems that are composable enough to swap out pieces when the landscape shifts? this is the red queen race. adaptation velocity.

**race two is external.** can you translate that capability into something your customers can actually absorb? can you pace your delivery to match their metabolism without falling behind competitors who found a faster path to trust?

i work in legal tech. law firms are not fast. they have compliance requirements, training costs, workflow inertia, risk aversion. they've been burned by vendors before. they don't trust easily and they don't change quickly.

the companies that win aren't the fastest runners. they're the ones who can sprint internally while walking externally. building optionality they don't deploy yet. staying three steps ahead but only showing one.

this is harder than it sounds. the temptation is to ship everything you can do. to show off. but if you outrun your customers, you're just alone at the front. they'll buy from whoever meets them where they are.

the bottleneck isn't your speed. it's the gap between your speed and theirs.

## The Wrong Answer

when production gets cheap, people reach for "taste" as the new scarcity. taste is the thing that separates good from great. taste is what ai can't replicate. taste is the moat.

i don't really buy that.
taste is a word people use to hide mechanisms they either don't understand or don't want to explain. it's a black box labeled "you either have it or you don't." that's not an explanation. that's a shrug wearing a turtleneck.

same problem with "capital wins" or "distribution wins." these are true but incomplete. they're tautologies, they describe outcomes, not mechanisms. it's like saying "the team with more points wins." yeah. but how do you score?

the deeper issue: all of these assume a stable game. the game isn't stable. that's the whole point.

## So What?

if this is true, what does it mean for your worth as a programmer? as a founder? as someone trying to build something that matters?

the old answer: your worth is your ability to produce. write code, ship features, solve hard technical problems. accumulate skill and watch your value go up.

my new answer: production is cheap. your worth is your ability to adapt and constrain. recognize when the ground shifts. abandon what's working before it stops working. set constraints that others can execute. take responsibility for outcomes, not just outputs.

this isn't comfortable. most of us got into this because we like building. we like the craft. the idea that craft matters less than adaptation speed feels like a betrayal.

but i don't think craft disappears. i think it migrates. the craft used to be in the code. now it's in the choices. what to build, when to abandon, how fast to move, how much to show.

here's my checklist. the questions i'm asking myself:

- can i define a problem in a way that survives contact with users?
- can i set constraints others can execute, including ai?
- can i swap components without collapse when the landscape shifts?
- can i recognize when my current approach is dying and move off it first?
- what's my internal cycle time vs customer adoption cycle time?

if the answer to most of these is solid, i think you're fine. maybe better off than before. if you can't answer them, the gap is going to widen.

## What Could Happen

here are some of my bets.

*what is possible:*

- solo builders ship full products in weeks. one person companies become normal, not exceptional.
- engineering teams shrink but "operator engineers" who can wrangle ai and own outcomes become high leverage.
- implementation-only roles get commoditized. the junior dev who just writes code is competing against every other junior dev plus ai.
- trust and regulation become the moat. soc-2, iso certifications, enterprise relationships. boring stuff that's expensive to fake.
- the gap between "uses ai well" and "doesn't use ai" becomes larger than the gap between "great engineer" and "good engineer."

*what is likely:*

my bet is bifurcation. 70% confidence.

the floor rises. mediocre talent with ai and high adaptation velocity beats great talent with slow adoption. during the transition, adoption is the dominant variable.

but once adoption saturates, talent differences get amplified, not compressed. ai is a multiplier. if everyone has the multiplier, the base matters more than ever. the 10x engineer becomes a 50x engineer. the 1x engineer is still 1x.

we've seen this before. from 
Richard W. Hamming's [*The Art of Doing Science and Engineering*](https://press.stripe.com/the-art-of-doing-science-and-engineering):

> "As a result we were able, with about the same amount of effort on our part, to produce almost ten times as much as the others were doing. But to them programming in FORTRAN was not for real programmers!"

so: a window where speed beats skill, followed by a world where skill matters more than it ever did. we're in the window. it won't last.

to be concrete about "skill" here, not taste, but mechanisms:

- **problem framing under ambiguity:** turning vague customer pain into a buildable spec before you've seen the answer
- **system composition:** swapping components without collapse, maintaining coherence as pieces get replaced. *composability*
- **distribution and trust building:** the boring, non-automatable work of earning permission to operate

these are the skills that get amplified when production cost drops to zero.

*what is desirable:*

i want to be the person who constrains entropy, not the person who types. i want to own outcomes, not rent out labor. i want to build systems that let me adapt faster than the ground shifts, and relationships that let me deliver at a pace customers can absorb.

## Falsifiability

checkable by end of 2026:

*for the red queen claim:*
if companies that adopted ai tools in 2023-2024 but stopped iterating still outperform late adopters, then adaptation velocity doesn't matter as much as i think. one-time adoption is enough.

*for the customer metabolism claim:*
if b2b startups that ship at maximum speed consistently beat those that pace to customer adoption, then the constraint isn't real. speed alone wins.

*for the bifurcation claim:*
if the wage premium for top-decile engineers compresses rather than expands after ai adoption exceeds 80%, then talent doesn't get amplified. the multiplier helps everyone equally.

*for my personal bet:*
if i focus on adaptation velocity and constraint-setting for the next 18 months and my career options narrow instead of expand, i'm wrong about what matters.
