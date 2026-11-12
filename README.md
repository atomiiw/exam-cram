# Exam cram

*Exam in five days. Haven't opened the book since the last one.*

You don't need a study guide. You need someone who has read every problem set, knows exactly what the exam will ask, and hands you the next five minutes: one picture, a few plain sentences, three questions you can answer in a line. Then the next five. You never decide what to study. You just answer the next question.

Exam cram puts that tutor inside Claude.

## Before / after

Ask an AI to help you review and you get this:

> **Prerequisites.** Phasors: x(t) = Re[X·e^(jωt)]. Reflection: Γ = (Z_L − Z₀)/(Z_L + Z₀). Input impedance: Z_in = Z₀(Z_L + jZ₀ tan βℓ)/(Z₀ + jZ_L tan βℓ). Cross products: x̂ × ŷ = ẑ … Now try these five problems.

All correct. And the honest reply is: *I can't follow this, and I'll never remember it.*

With exam cram, the same material arrives like this:

> **Chunk 2 · which way the wave goes**
>
> <img src="assets/chunk.svg" width="560" alt="Two waves: with a minus sign the wave slides toward +z, with a plus sign toward −z">
>
> **The picture shows one thing:** the sign in front of βz decides the direction.
>
> - A wave is written cos(ωt − βz). One part is about time, one about position.
> - Look only at the sign on the position part. Minus: it moves toward +. Plus: toward −.
> - Why: watch one crest. As time grows, z has to grow too for the bracket to stay the same, so the crest slides toward +z.
>
> **Quick quiz**
> 1. cos(ωt + 5z) moves which way?
> 2. cos(ωt − 5x)?
> 3. A wave moving toward −y: minus or plus?

> **You:** −z, +x, plus
>
> **Tutor:** All three right. Next, Chunk 3 · frequency and speed.

Eight of those and you are working the first problem on the exam, on your own.

## How it works

1. **You hand over the course's real problems**: homework, practice exams, past exams. They decide everything: what gets taught, which formulas matter, what gets skipped.
2. **It asks two things**: how many days you'll study, and when you want to have the problems down.
3. **It writes one checklist.** Lessons, the homework problems to redo closed-book, timed mock exams at the end. Nothing else on the page.
4. **It walks you through it**, five minutes at a time, and ticks each row as you finish.

```markdown
### Thu

| Item | Type | Topic | Done |
|---|---|---|---|
| HW5 Q4 | ✍️ | Speed of a wave in glass | ✅ |
| A3 | 📚 | Polarization |  |
| HW5 Q5 | ✍️ | Linear or circular |  |
```

Slides, textbook, syllabus, equation sheet are welcome and optional.

## Install

```
/plugin marketplace add atomiiw/exam-cram
/plugin install exam-cram@atomiiw
```

Then: *"Thermo midterm Friday, here are problem sets 5–8 and last year's exam, I have three days."*
