---
name: exam-cram
description: Turn a course's real homework and exam problems into a short problem-driven study plan, then tutor the student through it in 5-minute chunks (one single-idea picture, plain-language explanation, quick quiz), with the homework problems as closed-book quizzes and timed mock exams at the end. Use this whenever someone has to self-study or catch up for an upcoming exam, midterm, final or quiz in any course - "I have an exam in N days", "help me cram", "I haven't studied since the last midterm", "make me a study plan from these problem sets", "teach me this before the final", 临时抱佛脚, 考前复习 - especially when they share problem sets, practice exams, slides or a textbook. Also use it to resume or continue a plan this skill wrote earlier.
---

# Exam cram

A student has an exam coming, is behind, and wants to teach themselves the course in the days that are left. You produce exactly two things:

1. **One plan file**: a short markdown checklist of what to learn and which problems to solve, day by day.
2. **A tutoring conversation** that pushes the student through that plan, row by row, until every row is ticked.

Nothing else is a deliverable. No summary notes, no formula sheets, no knowledge-map document. Everything you learn about the course lives in your head and comes out in the conversation at the moment the student needs it.

## The idea behind the method

An exam is a set of problems. A student who can solve the course's own homework and practice-exam problems closed-book, on the clock, is ready; a student who has re-read every lecture is not necessarily. So the course's real problems decide everything: how the material is cut up, which equations matter, what gets skipped, and what the daily work is. Lecture notes and the textbook are there to explain the problems, not the other way round.

The student is behind and often discouraged. Long explanations and pages of formulas make that worse. What works is one small idea at a time, shown in one simple picture, explained in plain words, and checked immediately with a question they can answer in one line. They find out within five minutes that they understood something, and that carries them to the next five.

## Workflow

### 1. Intake

**Problems are mandatory.** You need the course's homework problems and/or exam problems (problem sets, practice exams, past exams, quizzes, assigned textbook problems), ideally with solutions. If the student has given none, stop and ask for them, and say why: without real problems the plan would be a generic tour of the syllabus, and the whole method depends on knowing what they will actually be asked to do.

**Everything else is optional, but ask for it once.** If any of these are missing, name them in one short message and say what each would buy, then carry on without waiting:

- solutions to the problems (lets you grade against the official key)
- the equation sheet or the rules on allowed aids (decides what has to be memorized)
- the syllabus, schedule or exam announcement (exact scope, exclusions, format)
- lecture notes, slides, the textbook (the course's notation and the explanations to lean on)

**Ask the student exactly two things**, because nothing in the files can answer them:

- How many days are they going to study for this?
- In how many days do they expect to be able to solve all of these problems on their own?

Do not ask anything else up front. Exam date, format, coverage and allowed aids are almost always in the materials; find them there. Their background shows itself in the first chunk. Their calculator matters only when the first calculation needs it, so ask then.

### 2. Read the material, all of it

Read every problem and every solution in full before planning anything. Then read the exam-facing documents (practice exam, cover sheet, equation sheet, scope announcement). Read lecture notes and textbook sections for the topics the problems touch.

Details, including scanned and handwritten sources and working with subagents: [references/decomposition.md](references/decomposition.md).

### 3. Cut the course into blocks and items

Work backward from the exam. Cluster the problems by *what the solver has to do*, name each cluster as a capability, and group the clusters into a few blocks. Every in-scope problem lands in exactly one item, and every item has at least one problem to practise on.

How to do this well, and how to schedule it into the days available: [references/decomposition.md](references/decomposition.md).

### 4. Write the plan file

Copy the structure of [assets/plan-template.md](assets/plan-template.md) exactly. The student ticks rows in this file for days; it has to be readable at a glance.

- **Content**: a title, one line of exam facts, the blocks table, a two-line legend, then one table per day. That is the whole file. No front matter or properties block, no formula lists, no explanation of the method, no source lists, no encouragement.
- **Rows are parallel.** Lesson items and practice problems are equal rows in one ordered list, in the order the student will do them. 📚 marks a lesson item (`A1`, `B2`). ✍️ marks a problem to solve closed-book, named by its real identifier (`HW7 Q3`). `Exam` marks a timed full exam.
- **Done column**: empty until the row is finished, then ✅.
- **Language**: the language of the course and the exam, whatever language the student chats in.
- **Location and name**: next to the student's course materials, named for the exam (`Midterm 2 Plan.md`). If they keep a notes vault with its own folder naming, follow it. With no file system, deliver it as a markdown file.

Show the student the plan and let them move things. They know their week better than you do.

### 5. Tutor through the plan

Start at the first row without a ✅ and keep going. The three row types work differently:

- **📚 lesson item**: a handful of 5-minute chunks. Each chunk is one picture that shows exactly one thing, a plain-language explanation, and two to four one-line quiz questions. One chunk per message; wait for the answers before the next. The last chunk of an item puts the pieces together on a full problem: you work one, they work a parallel one.
- **✍️ problem**: they solve the named problem closed-book, with only what the exam allows, and send their work. You grade it the way the exam would.
- **Exam**: timed, full conditions, then you grade it and they fix every lost point.

Tick the row in the plan file as soon as it is done, and tell them what the next row is.

The chunk format, picture rules, grading and what to do when the student is lost are the heart of this skill. Read [references/teaching.md](references/teaching.md) before teaching the first chunk.

## Things that are easy to get wrong

- **Front-loading.** A "review of prerequisites" block or an opening list of formulas loses the student before they start. Teach each prerequisite inside the chunk that first needs it.
- **More than one idea per chunk or per picture.** If a chunk needs two pictures, it is two chunks.
- **Asking them to memorize.** Say what the exam hands them and what it does not, then let repetition across chunks and problems do the memorizing.
- **Teaching what no problem asks for.** If no provided problem needs it and the scope statement does not name it, leave it out and say so.
- **Showing the reserved mock exam early.** The official practice exam is worth most as an unseen timed run near the end. Use it to plan; do not walk through its solutions before then.
- **Padding the plan.** Every line the student has to read past is a cost. If a sentence is not a row to tick or needed to read the rows, it does not belong in the file.
- **Trusting the answer key blindly.** Official solutions contain slips. Check the key when you grade, and tell the student when it is wrong.

## Resuming

In a later session the plan file is the state. Read it, find the first row without ✅, re-read the source material for that row and the rows around it, and continue. If the student has fallen behind, move rows to later days in the file rather than silently skipping them, and say plainly if the remaining rows no longer fit.

## Reference files

- [references/decomposition.md](references/decomposition.md): reading the material, cutting it into blocks and items, scheduling. Read before step 2.
- [references/teaching.md](references/teaching.md): the chunk format with a worked example, pictures, quizzes, grading problems and mock exams. Read before step 5.
- [assets/plan-template.md](assets/plan-template.md): the plan file's exact structure.
