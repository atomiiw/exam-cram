# Exam cram

A Claude skill for teaching yourself a course in the last few days before an exam.

You give it the course's real problems. It works out what the exam will ask you to do, writes a short day-by-day plan, and then tutors you through that plan until every row is ticked.

## What you give it

- **Required**: homework problems and/or exam problems (problem sets, practice exams, past exams), ideally with solutions. Everything is built from these: how the course is cut up, which equations matter, what gets skipped.
- **Optional**: lecture notes or slides, the textbook, the syllabus, the equation sheet, the exam announcement. It will remind you once if they are missing and carry on without them.
- **Two answers**: how many days you are going to study, and in how many days you expect to be able to solve all of those problems yourself.

## What you get

**1. One plan file.** A markdown checklist, nothing else:

```markdown
# PHYS 201 · Midterm 2 Plan

Exam: Fri 3/14, 10:00 am · 60 min · 4 problems · HW5–8, no relativity.

### Wed 3/12

| Item | Type | Topic | Done |
|---|---|---|---|
| HW5 Q4 | ✍️ | Speed of a wave in glass (A1) | ✅ |
| A3 | 📚 | Polarization |  |
| HW5 Q5 | ✍️ | Linear or circular |  |
```

📚 rows are lessons, ✍️ rows are the course's own problems done closed-book, and the last day holds timed mock exams.

**2. A tutoring conversation.** Each lesson is a handful of 5-minute chunks. Every chunk is one picture that shows exactly one thing, a plain-language explanation, and a few one-line quiz questions. You answer, it grades, you move on. Homework problems and mock exams are graded the way the exam would grade them.

## Install

In Claude Code:

```
/plugin marketplace add atomiiw/exam-cram
/plugin install exam-cram@atomiiw
```

Or copy `skills/exam-cram/` into your skills folder.

## Use

> I have a thermo midterm on Friday and I haven't opened the book since the last one. Here are problem sets 5–8 and last year's exam. I can study three days.

## Structure

- `skills/exam-cram/SKILL.md`: the workflow
- `skills/exam-cram/references/decomposition.md`: reading the material, cutting it into blocks and items, scheduling
- `skills/exam-cram/references/teaching.md`: the chunk format, pictures, quizzes, grading
- `skills/exam-cram/assets/plan-template.md`: the plan file's structure
