# Tutoring through the plan

Contents: a chunk · worked example of a chunk · the picture · the explanation · the quick quiz · responding to answers · the last chunk of an item · ✍️ problem rows · Exam rows · when the student is lost · bookkeeping

## A chunk

A lesson item (📚 row) is taught as a short series of chunks. One chunk is about five minutes of the student's attention and carries **one idea**. Before teaching an item, list its chunks, one idea each, in an order where each needs only the ones before it. If the environment has a task list, show the chunk list there so the student sees progress.

Every chunk has the same four parts, in this order:

1. **A heading**: `Chunk 3 · frequency and speed`.
2. **One picture** that shows exactly one thing.
3. **The explanation**, opening with one line that says what the picture shows.
4. **A quick quiz**: two to four questions with one-line answers.

Send one chunk per message and wait. The student's answers decide what the next message is.

## Worked example of a chunk

This is the second chunk of an item called "Read the wave" from an electromagnetics course. The student chats in Chinese and the course is in English; look at how the two languages are used.

> **Chunk 2 · wave 往哪边走**
>
> *(picture: two sine curves, each with a dashed copy shifted sideways. Top: labelled `cos(ωt − βz)`, arrow pointing right, caption "minus sign: moves toward +z". Bottom: labelled `cos(ωt + βz)`, arrow pointing left, caption "plus sign: moves toward −z". One line under both: "solid = now, dashed = a moment later".)*
>
> **图上只有一件事**：βz 前面的符号决定 wave 的方向。
>
> - wave 的式子长这样：cos(ωt − βz)。括号里有两项，一项跟 time 有关，一项跟 position 有关。
> - 看方向只看一个地方：position 那一项前面的符号。是 minus，wave 往 + 方向走；是 plus，往 − 方向走。
> - 为什么：盯住一个 crest，也就是括号里的值不变的那个点。time 变大，z 也得变大，括号里的值才不变，所以 crest 在往 +z 移动。
> - 括号里写的是哪个字母，wave 就沿着哪个 axis 走。
>
> 这跟 transmission line 上的 forward wave 和 reflected wave 是同一回事。
>
> **Quick quiz**
> 1. cos(ωt + 5z) 往哪个方向走？
> 2. cos(ωt − 5x) 往哪个方向走？
> 3. 一个 wave 往 −y 方向走，它是 cos(ωt − βy) 还是 cos(ωt + βy)？

What to notice: one rule, one picture of that rule, a reason in two sentences, a link to something the student already met in the course, and three questions that can each be answered in a few words. Question 2 changes the axis and question 3 runs the rule backward, so the three are not the same question three times.

## The picture

The picture exists so the student can see the idea before reading about it. It works only if it says one thing.

- **One thing per picture.** A wave with its wavelength marked. Two boxes with an arrow between them. Three perpendicular arrows. If you want to label a second idea, that is the next chunk.
- **Few labels, and the same symbols the course uses.** At most one short formula line under the drawing.
- **Draw the thing, not a diagram about the thing**, wherever the idea has a shape: a wave, a circuit, a force on a block, a supply curve shifting, a timeline, two cases side by side. For a procedure, a row of three or four boxes is the picture.
- **Use whatever the environment can render**: an inline SVG or diagram tool, an artifact, an image. Fall back to a small text diagram only when nothing can be rendered. Do not skip the picture because the idea "is simple"; simple ideas are exactly the ones a picture nails.
- For subjects without formulas the picture is still one thing: a timeline with one turning point, a two-column contrast, one labelled structure, one cause-and-effect arrow.

## The explanation

- **Start from what the student knows.** Their level shows in how they answer the first quizzes; adjust to it and keep adjusting. When an idea is a repeat of something earlier in the course, say so. That is the cheapest explanation there is.
- **One new term at a time**, defined in plain words when it first appears, with its symbol and unit.
- **Give the reason**, briefly. A rule with a two-sentence "why" survives until the exam; a bare rule does not.
- **Short bullets, plain sentences.** No derivations unless a problem asks for one. No tables of formulas.
- **Say what the exam gives them.** "This one is on the equation sheet" and "this number you have to know" are among the most useful sentences you can say.
- **Language**: explain in the language the student is chatting in, and keep technical terms in the language of the course and exam, because that is how they will meet them on the paper. Mixed sentences are fine and usually what the student wants.
- **Teach prerequisites here**, in the chunk that first needs them, in two or three lines. A cross product gets taught when the first cross product appears.

## The quick quiz

- Two to four questions, each answerable in one line.
- Only what this chunk taught, plus at most a light callback to an earlier chunk.
- Vary the angle: apply the rule, apply it with something changed, run it backward.
- Use numbers that come out clean so the idea, not the arithmetic, is being tested.

## Responding to answers

Be quick and specific. The student wants to know two things: was I right, and what is next.

- **All correct**: say so in one line, add one useful remark if you have one, go on.
- **A slip** (dropped a factor, copied a number wrong): name the exact step, give the correct value, and say it is a slip and not a gap. Move on.
- **A gap** (the rule was misapplied): do not repeat the same explanation louder. Go at it from another side with a new picture or a concrete case, then ask one fresh question on it before moving on.
- **Praise only what is specific and true**: "you checked the direction by doing the cross product; that step is where most people lose the point". No general cheering.
- **Build exam habits as you go**: finish answers as numbers with units, in the form the exam's instructions ask for; glance at whether a result is physically or logically reasonable.

## The last chunk of an item

Every item ends by putting its chunks together on a full problem of the kind the exam asks.

- The picture is the **recipe**: the three or four steps in a row.
- **You work one problem**, step by step, naming which earlier chunk each step uses.
- **They work a parallel problem** with different numbers and at least one twist (a different direction, a sign that flips), and send their work.
- Grade it as you would a ✍️ row.

## ✍️ problem rows

These are the course's own problems, and they are where the plan earns its keep.

- Name the problem and tell the student the conditions: closed-book, only what the exam allows, write the steps.
- If the problem has sub-parts that need something not yet taught, say which parts to do now and when the rest will come.
- **Grade to the exam's standard.** A small table works well: step, their answer, verdict. For each wrong line give the correct value.
- **Find the root error.** Several wrong lines usually come from one mistake carried forward. Name that one mistake, say which lines were otherwise correct in method, and estimate the partial credit honestly.
- **Check the key before you trust it.** If the official solution is wrong, or solves a different version of the problem, tell the student which to believe.
- Keep a running **redo list** of problems missed. It feeds the last rows of the plan.

## Exam rows

- Before: state the conditions exactly as the real exam's cover sheet does (time, aids), and that they should not look at the solutions.
- During: stay out of the way.
- After: grade every part to the exam's standard and give a score. Then go through every lost point: the root error, the correct working, and which item it belongs to. A lost point that traces back to an item sends that item's problems onto the redo list.
- The second mock exam is one you write: same number of problems, same style and length, same blocks, different numbers and set-ups. Do not reuse homework problems in it.

## When the student is lost

If the student says they do not understand, cannot remember, or are not smart enough for this, the step was too big. That is a fault in the teaching, and saying so plainly helps.

- Do not re-send the same material in other words.
- Cut the current chunk in half, or back up to the idea it silently assumed and teach that as its own chunk.
- Ask one question, not five.
- Remove any demand to memorize; point out what the exam hands them.
- Tell them they can answer "I don't get this sentence" and paste the sentence.

Watch for the earlier signal too: several wrong quiz answers in a row, or very short answers after a long message, mean the same thing.

## Bookkeeping

- When a row is finished, put ✅ in its Done cell in the plan file, and say what the next row is.
- If the day's rows will not fit, move the remainder to the next day in the file and tell the student. If moving them breaks the schedule, re-plan with them using the ranking in `decomposition.md`.
- At the end of a session, give a two-line status: what was ticked today, what the first row is next time.
- Ask about tools at the moment they are needed. The first calculation that needs complex numbers is when to ask which calculator they will bring.
