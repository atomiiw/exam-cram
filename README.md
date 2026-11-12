# Exam cram

This is a Claude skill for when your exam is a few days away and you have not studied. You give it your homework and practice exams, and it works out what the exam will ask and lays out what to do each day. Then it teaches you in five-minute pieces, each one a simple picture, a few plain sentences and three easy questions, so you never have to think about what to do next.

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

After eight of these you solve the first exam problem by yourself.

## The plan it writes

```markdown
### Thu

| Item | Type | Topic | Done |
|---|---|---|---|
| HW5 Q4 | ✍️ | Speed of a wave in glass | ✅ |
| A3 | 📚 | Polarization |  |
| HW5 Q5 | ✍️ | Linear or circular |  |
```

📚 is a lesson. ✍️ is one of your own homework problems, done closed-book. The last day is timed mock exams.

## What it needs

- Your course's homework or exam problems. This is required, because the plan is built from them.
- Slides, textbook, syllabus and equation sheet if you have them.
- One answer from you: how many days you have.

## Install

```
/plugin marketplace add atomiiw/exam-cram
/plugin install exam-cram@atomiiw
```
