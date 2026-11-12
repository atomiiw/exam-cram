# Reading the material, cutting it up, scheduling it

Contents: reading · facts to pin down · solution chains · blocks and items · the first lesson · what to keep in your head · scheduling · when it does not fit

## Reading

Read in this order, because each step tells you what to look for in the next:

1. **The exam-facing documents**: practice exam, past exams, cover sheet, equation sheet, the announcement of what is covered. These tell you what a problem on this exam looks like, how long the student gets per problem, and what they will be handed.
2. **Every homework problem and every solution**, in full. Solutions show the method the grader expects, the notation, and the level of detail that earns full credit.
3. **Lecture notes and textbook**, only for the topics the problems touch. You are looking for the course's own way of explaining each idea, its sign and naming conventions, and its worked examples.

Practical points:

- **Scanned or handwritten PDFs** often have no text layer. Check with a quick text extraction; if a page comes back empty, render it to an image and read it visually.
- **Large volumes** (dozens of handwritten slide pages, a hundred pages of notes) are worth giving to subagents in parallel if you have them, one per topic cluster. Tell each one which problems that cluster serves, ask for the equations exactly as written with their conventions, every worked example with its numbers, and an explicit "illegible here" rather than a guess. Read the exam-facing documents yourself; they are short and everything hangs on them.
- **Check as you read.** Recompute the numbers in official solutions. Note every slip you find (a wrong digit, a solution to a different version of the problem, a mislabeled figure). You will need these when grading, so the student is not marked wrong for being right.
- **Check file names against contents.** A file called "solutions" may be the student's own attempt.

## Facts to pin down before planning

From the materials, not from the student, unless the materials are silent:

- exam date and time, length, number of problems, points
- coverage, and anything explicitly excluded
- allowed aids: calculator type, notes, equation sheet
- what the equation sheet gives, line by line, so you know what is *not* on it

If the scope is stated in terms of homework ("covers HW6–9"), that is the scope. If two sources disagree, the most recent announcement wins; tell the student which one you used.

## Solution chains

This is the step that decides what the student learns, so do it problem by problem, not from memory of the subject.

For each exam problem and then each homework problem, write the chain that solves it:

```
Practice exam P1(a)  given E = x̂ 10 e^(−j20πz), f = 1.5 GHz
  sign of exponent           -> direction +z            (must know)
  ω = 2πf, v = ω/β           -> v = 1.5e8 m/s           (v = ω/β: must know)
P1(b)  v = c/√εr             -> εr = 4                  (on sheet as v = 1/√(με))
P1(c)  η = 377/√εr, H = E/η, E × H along travel -> H    (377 Ω: must know)
P1(d)  S = |E|²/2η           -> 0.27 W/m²               (sheet gives the general form)
```

Every equation or idea that appears in some chain is in. Mark each one *on the sheet* or *must know*. Everything that appears in no chain is out, even when the lectures spend an hour on it. The student should never be taught an equation you cannot point to a problem for.

## Blocks and items

**A typical exam problem chains three or four capabilities. Those capabilities are your items.**

1. Go through the chains and write down, in a few words, the capability each step needs: "read direction and speed from a wave expression", "pick the right approximation for a lossy medium", "set up a null hypothesis from a word problem".
2. Merge duplicates. What is left is the list of **items**. Name each one as a capability in two to five words. An item is the right size when it takes two to six 5-minute chunks to teach and at least one provided problem exercises it.
3. Group items into three to six **blocks** that mirror how the exam is organised. If the practice exam has four problems on four topics, those are probably four of your blocks. Letter the blocks (A, B, C…) and number items inside them (A1, A2…).
4. Order blocks and items by dependency. Inside a block, put the item with the fewest prerequisites first.

Then run the coverage check in both directions:

- **Every in-scope problem maps to an item.** A problem that maps to nothing means an item is missing.
- **Every item has a problem.** If no provided problem exercises an item, either it is not really needed (drop it) or the scope statement names it explicitly (keep it and plan to write a drill yourself).
- **Everything left out is named.** Problems that are out of scope or not exam-like (plotting assignments, coding exercises on a paper exam, excluded topics) go on the plan's "Skipped on purpose" line with a two-word reason, so the student can see it was a decision.

Lecture material that no problem touches and the scope statement does not name is not taught. A cramming student cannot afford it, and the problems are the best evidence of what the examiner cares about.

## The first lesson

The first thirty minutes decide whether the student stays. They end with the student solving, alone, a problem just like the first one on the exam, so build the lesson from that exam problem's chain and from nothing else.

- Take the chain for practice exam problem 1. Each idea in it is one chunk, in the order the chain uses them. Merge two only when one is a single symbol.
- **Six chunks at most.** If the chain has more, drop the ideas that only the last sub-part needs, and have the student solve the sub-parts the six reach.
- Do not add what the chapter "starts with". If problem 1 never asks for a wavelength, wavelength waits.
- Prerequisites the student has forgotten are taught inside the chunk that needs them, in two or three lines.
- The lesson is item `A1`. The row after it is the problem they solve: a homework problem whose chain matches problem 1's, or, when none matches closely enough, a twin you write (`A1 drill`) with the same sub-parts and different numbers and directions.
- The exam problem itself is not shown, quoted or solved. It stays unseen for mock day.

With no practice exam, aim the lesson at the homework problem that looks most like an exam problem and comes earliest in the material, and have the student solve a twin of it.

## What to keep in your head for each item

None of this goes in the plan file. It is what you draw on while teaching:

- the problems that exercise the item and their chains, and which is the simplest to demonstrate on
- the equations involved, split into *on the sheet* and *must know*
- the prerequisite ideas the student will be missing, to teach at the moment of need
- the course's notation and sign conventions for this topic
- the traps visible in the solutions (a sign that flips, amplitude versus power, a unit conversion)
- any error in the official key for these problems

In a long engagement your context may be summarised. The source files remain; re-read the ones for the current item at the start of each session.

## Scheduling

Inputs: the items, the problems, the number of days the student gave you, and the exam date.

- **Estimate the load.** A lesson item is two to six chunks of about five minutes plus the student's answering time; call it 15–30 minutes. A homework problem done closed-book is 5–20 minutes plus grading. Add them up per day and keep a day to what the student can actually do. When they have not said, assume around three hours.
- **Exam papers appear only on mock day.** ✍️ rows before that are homework problems, textbook or slide problems, or problems you write. Never a practice-exam or past-exam problem, in whole or in part.
- **Each lesson row is followed by its problems.** Learning A3 and then immediately solving the homework problem on A3 is what turns "I followed that" into "I can do that".
- **Open each day with yesterday.** Hold back one or two problems from the previous day's last items and make them the first rows of the next day. Retrieving after a night's sleep is what makes it stick, and it shows both of you whether it did.
- **End with mock exams.** Reserve the last study day (roughly the last third when there are three days or fewer) for full timed exams:
  - the official practice exam, unseen until then, under real conditions
  - a review row: grade it, fix every lost point
  - a second mock exam that you write in the same style, covering the same blocks with different numbers and set-ups
  - a review row for that one
  - a redo row: every ✍️ problem that was missed earlier, done again
- **Exam morning** is one short review row: missed problems and the must-know list. No new problems.
- **Fewer days than there are until the exam.** If the student's number of days runs out before the exam, the lesson rows and their problems end on that day, and the days after it hold the mock exams and the redo list.

If there is only one exam-style document and no homework, do not burn it: write your own practice problems for the ✍️ rows, modelled on its problems, and keep the original for the timed run.

## When it does not fit

Say so plainly, with numbers: "there are 16 items and about 14 hours of work, and you have two days". Then cut from the bottom of a ranking, not at random:

1. Rank items by how much of the exam they account for: how many provided problems use them, and how many points those problems carry on the practice exam.
2. Keep prerequisites of anything you keep.
3. Shrink before dropping: an item can be taught as one recipe chunk plus one problem.
4. Put what was dropped on the "Skipped on purpose" line.

Do not solve a time problem by making days longer than the student said they have, or by removing the mock exam. One timed run is worth more than the last two items.
