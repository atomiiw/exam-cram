# Exam cram

Exam cram is a Claude skill for problem-solving courses like physics, math and engineering. You give it your homework and a practice exam, and it works out exactly which equations each exam problem needs and teaches you only those, in five-minute pieces you can follow on a tired brain. Thirty minutes in, you solve a problem just like the first one on your exam, by yourself.

## One five-minute piece

> **Chunk 2 · which way the wave goes**
>
> <img src="assets/chunk.svg" width="560" alt="Two waves: with a minus sign the wave slides toward +z, with a plus sign toward −z">
>
> **The picture shows one thing:** the sign in front of βz decides the direction.
>
> - A wave is written cos(ωt − βz). One part is about time, the other about position.
> - Look at the sign on the position part. Minus means it moves toward +. Plus means it moves toward −.
> - Here is why. Watch one crest. As time grows, z has to grow too for the bracket to stay the same, so the crest slides toward +z.
>
> **Quick quiz**
> 1. Which way does cos(ωt + 5z) move?
> 2. Which way does cos(ωt − 5x) move?
> 3. A wave moves toward −y. Is the sign minus or plus?

> **You:** −z, +x, plus
>
> **Claude:** All three right. Next is Chunk 3, frequency and speed.

Six of these, at most, and then you do a problem just like problem 1 of your exam.

## The plan it writes

```markdown
### Thu

| Item | Type | Topic | Done |
|---|---|---|---|
| HW5 Q4 | ✍️ | Speed of a wave in glass | ✅ |
| A3 | 📚 | Polarization |  |
| HW5 Q5 | ✍️ | Linear or circular |  |
```

📚 is a lesson. ✍️ is a homework problem, done closed-book. The practice exam stays unopened until the last day, when you sit it timed.

## What it needs

- Your course's homework or exam problems. This is required, because the plan is built from them.
- Slides, textbook, syllabus and equation sheet if you have them.
- One answer from you: how many days you have.

## Install

```
/plugin marketplace add atomiiw/exam-cram
/plugin install exam-cram@atomiiw
```
