---
name: lessonmark-lesson
description: Turn a YouTube link and its timestamped script into a complete LessonMark data.md lesson: clips, vocabulary, grammar, listening tasks and discussion.
---

# LessonMark lesson builder

You turn a video (a YouTube link or local media) and its timestamped script into ONE lesson file,
`data.md`, written in LessonMark notation. LessonMark's `index.html` reads that file and builds an
interactive lesson page. The page is strict: if the notation is wrong, exercises break or a red
warning box appears. So this skill has two parts:

- **Part A – Method:** how to plan and write a good lesson (sections 0–10).
- **Part B – Notation:** the complete LessonMark specification. Every line you write must follow it
  exactly. When Part A and Part B seem to differ, Part B wins.

Read the whole skill before you start. Write nothing that is not in Part B.

LessonMark: https://jeronimovis.github.io/lessonmark/ · Reference: https://jeronimovis.github.io/lessonmark/LessonMark-reference.html


# PART A – METHOD

## 0. Settle the brief

Use what the teacher gives you. For anything missing, use these defaults and state them in the
summary you give after the file (never inside it). Ask a question only if the video link or the
script is missing.

| Choice | Default |
|---|---|
| Level | C1 |
| Learners | Adult professionals. If the teacher names a field (e.g. architects and engineers), angle vocabulary, examples and discussion to it. |
| Length | 30–60 minutes; aim for 45 unless told otherwise. |
| Media | YouTube clips from the given link. Use `audio.mp3` / `video.mp4` only if the teacher says those files exist, with the same timestamps. |
| Images | None, unless the teacher will supply them. Then call them `image01.png`, `image02.png`… and say so in the summary. |
| Style | `classic`. Use another style only if the teacher names one of: modern, editorial, blueprint, concrete, notebook. |

Never invent a link, a file, a timestamp, a quotation or a fact that is not in the material.

## 1. Read the script like a teacher

1. Find the topic, the speakers, the structure and the story arc.
2. **Name the speakers.** Take names from the script, the video title or description, or from
   self-introductions ("I'm Rob Mills…"). If a speaker has no name, use a role: `Narrator`,
   `Interviewer`, `Designer`, `Client`. Never write `Speaker 1` or `Speaker 2` anywhere in the lesson.
3. Mark where the real content starts and ends: skip intros, sponsor messages, calls to subscribe,
   credits and music.
4. Mark natural sections: topic shifts, a new speaker, a new stage of the story.
5. Flag lines marked as uncertain (`[inaudible]`, `(?)`) and never build an answer on them.
6. **Notice spoken slips.** Speech often contains things that are wrong or poor in writing:
   dangling participles ("Walking into the space, your eye is drawn…": the eye is not walking),
   agreement slips ("textures and tones that makes you…"), false starts, run-on sentences.
   Such a line may be quoted in a transcript, but it must NEVER be presented as a model answer,
   a correct sentence in `[fix]`, or a target structure. It can be the WRONG sentence of a `[fix]`
   item only if the correction is clear and uncontroversial.

## 2. Choose the clips

- **2–3 clips** of **60–120 seconds** each for a 30–60 minute class (up to 4 for longer classes).
- Start and end at sentence boundaries. Use only timestamps that appear in the script: start at
  or just before the first word (round down), end just after the last word (round up).
- Every question about a clip must be answerable from that clip alone, and questions follow the
  order of the clip.
- Give each clip a short, telling name: `"Clip A – the land and the river"`. Letter the clips
  A, B, C in order.
- A clip may be replayed in several exercises: repeat the same `[play]` line.

## 3. Mine the language

Work clip by clip. Keep a private list with the timestamp of every item.

**Vocabulary (8–14 items; up to 20 for longer classes).** Prefer, in this order:
1. Words the learners will reuse in their field (domain terms with transfer value).
2. Strong collocations and chunks (*seek respite*, *lean into a process*, *lay the foundation for*).
3. Phrasal verbs and idioms.
4. C1 academic words.

Skip proper nouns, words learners at this level surely know (for architects: *staircase*,
*skylight*, *kitchen*), and words whose meaning in context is unusual or misleading.

**Grammar (1–2 points; up to 3 for longer classes).** Only structures that really occur in the
script AND are correct in standard written English. Good C1 targets: passives and passive
reporting, participle clauses, inversion, cleft and pseudo-cleft sentences, nominalisation, mixed
conditionals, modals of deduction, narrative tenses, reduced relative clauses, linking and
contrast. When the speaker's version is a slip (section 1.6), build the exercise on a corrected
or different sentence and say so in `[teacher]`.

**Discussion angles (2–4).** A dilemma or trade-off, a controversial claim, a cause–effect worth
questioning, a link to the learners' own work or country, an ethical issue, a "what would you
have done?" moment. Open questions that need an opinion plus reasons, never questions with a
factual answer.

## 4. Build the lesson arc

Use `# Part` headings for stages and `## Title | Interaction · minutes` for each exercise.
Interaction is `Individual`, `Pairs`, `Groups` or `Whole class`. The minutes of all `##`
exercises must add up to the class length. A typical 30–60 minute arc (drop what does not fit):

| Stage | Minutes | Content |
|---|---|---|
| 1 Lead-in | 3–5 | A `[quote]` (≤15 words, exact, correctly attributed) or an `[img]`, plus 2 `[discuss]` prompts that activate ideas and make students predict. |
| 2 Key vocabulary | 4–6 | `[match]` of 4–6 words needed for the first listening, or a `[vocab]` list for reference. |
| 3 Listening for gist | 5–8 | First clip; 3–4 `[m]` or `[tf]` items on MAIN ideas only (who, why, what overall), not details. |
| 4 Listening for detail | 8–12 | The same clip again; gap fill of 6–10 gaps from the exact transcript words, or a table with numbers, dates and names. `[transcript]` right after the `[play]` line. |
| 5 Second clip | 5–10 | `[short]`, `[long]`, `[order]` for sequences, `[m]`, or a `[timeline]`. |
| 6 Language focus | 5–10 | One or two exercises on the grammar and vocabulary: word formation, `[transform]`, dropdowns, `[fix]`, `[bank]`, `[odd]`, `[sort]`. |
| 7 Speaking | 8–15 | 2–4 `[discuss]` prompts with a `[phrases]` box and a `[timer]`; for 50–60 minutes, a short role play with `[roles]`. |
| 8 Teacher's notes | – | One `[teacher]` block at the very end (section 7). |

For classes longer than 60 minutes: a third clip, an original `[read]` text marked
`| Original text written for this lesson`, more language focus, a `[note "Did you know?"]`,
a fuller role play.

Keep each `##` exercise to one task type (two at most, e.g. `[play]` + `[tf]`). One `> ` rubric
per exercise, written to students, saying exactly what to do.

## 5. Choose the right tag

| What students do | Tag |
|---|---|
| Type a missing word in a text | `{answer}` gap |
| Choose a missing word from a list | `[bank]` with gaps, or `{*right\|wrong}` dropdowns |
| Form a word from a base word | `{answer}(BASE)` |
| Decide if a statement is true | `[tf]` |
| Choose one answer to a question | `[m]` |
| Answer in 1–3 words | `[short]` |
| Answer in sentences / explain / rewrite freely | `[long]` |
| Correct a sentence that contains a mistake | `[fix]` |
| Rewrite a CORRECT sentence using a given word | `[transform]` |
| Pair terms with meanings | `[match]` |
| Put events in order | `[order]` |
| Find the odd one | `[odd]` |
| Put words into groups | `[sort]` |
| Talk | `[discuss]` |

There is no other exercise type. Never use `[fix]` for a sentence that is already correct.

## 6. Rules for good items

**Gap fills.** The answer is the exact word(s) from the transcript; the sentence around it stays
faithful to the clip. One gap per idea; never two gaps side by side; 1–3 words per gap. Accept
real variants with `|`. Do not gap words students could guess without listening.

**Word bank.** The page adds the gap answers to the bank itself. Extra words after `+`: 2–3
plausible distractors of the same word class, never one of the answers.

**Dropdowns.** 3 options, one `*`, all grammatical-looking.

**Multiple choice.** 3–4 options, exactly one correct; distractors plausible (they reuse words from
the clip or a likely misunderstanding), similar in length, no "all/none of the above". Gist
questions ask about main ideas; detail questions about facts.

**True/false.** Balance true and false. Paraphrase the script so students must understand, not
match words. No trick negatives, no double negatives.

**Short answers.** 1–3 words. List every reasonable answer with `|`: with and without an article,
singular and plural if both fit, numbers as digits and words.

**Long answers.** Need inference or explanation. ONE suggested answer of 1–3 sentences.

**Matching.** 4–8 pairs. Definitions of similar length (≤12 words), in plain English, never
containing the term itself.

**Error correction (`[fix]`).** Each sentence has exactly ONE clear mistake of a type learners at
this level make, linked to the grammar point. The answer is the minimal correction (change as
little as possible). Accept every correct correction with `|`.

**Key word transformations (`[transform]`).** The first sentence is correct and natural. The new
sentence means exactly the same. The answer is 2–5 words, includes the key word unchanged, and
there is text both before and after the gap. Accept contracted and full forms with `|`.
Check the finished sentence word by word: is it correct English with the same meaning?

**Odd one out / categorising.** Exactly one defensible odd one; each item fits one category only.

**Discussion.** Open, specific to the clip, linked to the learners' field where natural.

**Quotes.** At most 15 words, exact, attributed to the person who said them.

**Transcripts.** Only for clips used in the lesson; one line per turn as `Name: text`.

## 7. The `[teacher]` block

One block at the very end. Include:
- the video (title, channel, speakers);
- each clip with times and content;
- the timing plan and what to cut if time runs short;
- the grammar points with the script lines and times they come from, and any correction you made
  to a spoken slip;
- ideas for fast finishers or homework.

Write it in Markdown (paragraphs, `**bold**`, `- lists`). No gaps.

## 8. Respect the source

- Credit the video in `meta:` and in `[teacher]`.
- Use transcript text only inside `[transcript]` blocks and gap-fill sentences, and only for clips
  used in the lesson. Keep `[quote]` under 15 words.
- `[read]` texts are your own writing, never copied from articles.

## 9. Write, then validate

1. Write the file in order, copying the patterns of Part B and changing only the words.
2. Then validate it line by line with the Final checklist in Part B, section 12. For each block
   tag, find its closing tag. For each `[transform]`, count the `=` signs. For each `[m]`, count
   the `*`. For each `[bank +]`, compare the extras with the answers. Search the file for `“`
   inside tags, for `Speaker`, for lines starting with `[` that are not tags, and for ```` ``` ````.
3. Add up the minutes in the `##` lines; they must equal the class length.
4. Re-read every answer: is it correct English, is it really in the clip, are all reasonable
   variants accepted?
5. Fix anything that fails and validate again.

## 10. Deliver

- **If you can create files:** create `data.md` (or the name the teacher asked for) containing only
  the lesson.
- **If you answer in a chat:** put the entire file in ONE code block that starts with
  ```` ```markdown ```` and ends with ```` ``` ````. Nothing but the lesson goes inside the block.
- **After the file** (outside the code block), give the teacher a short summary: class length;
  clips with times and content; vocabulary chosen; grammar points with their source lines;
  discussion focus; any assumptions (level, learners, length, media); anything the teacher must
  supply (images, local media files). Also tell them: "Open the lesson. If a red box appears,
  paste its lines back to me and I will fix them."


# PART B – LESSONMARK NOTATION

## 1. Output

- The output is the lesson file and nothing else: no greeting, no explanation, no answer key,
  no notes outside `[teacher]`, no "eof", no summary inside the file.
- If you can create files, create `data.md` containing only the lesson.
- If you answer in a chat, put the whole file in ONE code block that starts with ```` ```markdown ````
  and ends with ```` ``` ````. Nothing else goes inside that block. Anything for the teacher
  (a summary, assumptions) goes AFTER the closing ```` ``` ````, never inside it.
- The first line of the file is `---` (the header). The last line is the last line of the lesson,
  usually `[/teacher]`.
- Never use ```` ``` ```` inside the lesson itself.


## 2. Ten golden rules

1. **Tags start at the beginning of a line** and are written in lowercase: `[tf]`, `[m]`, `[play …]`.
2. **Block tags always open and close on their own lines**: `[m]` … `[/m]`. Never write an exercise
   block on one line. Every block you open, you close with the same name: `[fix]` … `[/fix]`.
3. **Single-line tags never get a closing tag**: `[tf]`, `[short]`, `[odd]`, `[discuss]`, `[play]`,
   `[img]`, `[timer]`, `[link]`. Write the whole item on one line.
4. **Inside tags use straight double quotes** `"…"` for titles, captions, labels and speaker names.
   Curly quotes `“…”` inside a tag break it. (Curly quotes in normal text are fine.)
5. **Curly braces always make a gap.** Never write `{` or `}` for any other purpose.
   Write `\{` `\}` if you need the symbols. Use gaps only where section 9 allows them.
6. **A line that starts with `[word]` is read as a tag.** Never start a normal line with
   `[Music]`, `[Pause]`, `[Note]`, `[Answer]` or similar. (`[Music]` is fine inside `[transcript]`.)
7. **`=` introduces an answer only where this document says so.** In `[transform]` the `=` signs
   mark the gap inside the sentence: they never start the line.
8. **`|` separates accepted alternatives** only in gaps, `[short]`, `[fix]` and `[transform]`.
   Never in `[long]`, `[m]`, `[tf]`, `[match]` or anywhere else.
9. **Never write numbers, letters or keys yourself.** The page numbers exercises and items,
   letters the options, shuffles matching and ordering, and builds the answer key.
10. **Use only the tags in section 6.** No HTML, no other tags, no invented options.


## 3. File skeleton

```
---
title: …
subtitle: …
level: …
intro: …
meta: …
style: classic
---

# Part 1 – …

## Exercise title | Interaction · minutes
> Instructions for students.

(exercise content)

## Next exercise title | Interaction · minutes
> Instructions.

(exercise content)

# Part 2 – …

…

[teacher]
Notes for the teacher.
[/teacher]
```


## 4. Header

The file starts with a header between two lines that contain only `---`.
One `key: value` per line. Only these keys exist:

| Key | Required | What it is |
|---|---|---|
| `title:` | yes | Lesson title. |
| `subtitle:` | no | One-line tagline under the title. |
| `level:` | no | e.g. `B2`, `C1`. |
| `course:` | no | Small label above the title, e.g. `English for Architects`. Default: "Lesson". |
| `intro:` | no | One short paragraph that sets the scene. One line in the file. |
| `meta:` | no | One line of practical facts: length, source, files. Separate items with ` · `. |
| `style:` | no | Exactly one word: `classic`, `modern`, `editorial`, `blueprint`, `concrete` or `notebook`. Default `classic`. Nothing else on the line. |

Each value stays on ONE line. No quotes around values. No other keys.


## 5. Structure and plain text

```
# Part 1 – Before you watch              ← part title: not numbered, not an exercise
## Key vocabulary | Pairs · 5 minutes    ← exercise: numbered automatically
> Match the words with their meanings.   ← rubric (instructions to students)
### Group A                              ← optional subheading inside an exercise
```

- `#` = part title. It closes the current exercise.
- `##` = an exercise. Everything until the next `#` or `##` belongs to it. Text after ` | `
  (space, bar, space) is the detail line, shown small under the title:
  `Interaction · minutes`, for example `Pairs · 5 minutes`. Interaction is one of
  `Individual`, `Pairs`, `Groups`, `Whole class`.
- Do not write "Exercise 1", "1.", "Task A" in titles: numbering is automatic.
- Every `##` starts with exactly one rubric line starting with `> ` written to students.
- `###` = optional subheading inside an exercise.
- Every graded item (gaps, `[tf]`, `[m]`, `[short]`, `[fix]` …) must be inside a `##` exercise.
- Plain Markdown that works: paragraphs (separate with a blank line), `**bold**`, `*italics*`,
  `` `code` ``, `[link text](https://…)`, lists (`- item` or `1. item`), and tables:

```
| Feature | Detail |
|---|---|
| Bridges built | {about 400} |
```

- Lines that start with `-`, `*`, `+` or `1.` become list items. Lines that start with `>` become
  rubrics. Lines that start with `#` become headings. Lines that start with `|` followed by a
  `|---|` line become a table.
- No HTML. No images in Markdown syntax (use `[img]`). No footnotes.


## 6. Tag overview

| Tag | Kind | Form | Closing tag |
|---|---|---|---|
| `[play src start end "label"]` | presentation | single line | none |
| `[img file options "caption"]` | presentation | single line | none |
| `[timer 5:00 "label"]` | presentation | single line | none |
| `[link url "title"]` | presentation | single line | none |
| `[read]` | presentation | block | `[/read]` |
| `[transcript "label"]` | presentation | block | `[/transcript]` |
| `[note "title"]` | presentation | block | `[/note]` |
| `[vocab "title"]` | presentation | block | `[/vocab]` |
| `[phrases "title"]` | presentation | block | `[/phrases]` |
| `[roles]` | presentation | block | `[/roles]` |
| `[timeline]` | presentation | block | `[/timeline]` |
| `[quote "speaker"]` | presentation | block | `[/quote]` |
| `[teacher]` | presentation | block | `[/teacher]` |
| `{answer}` and variants | exercise | inside text | none |
| `[tf] … [t]` / `[f]` | exercise | single line | none |
| `[short] … = …` | exercise | single line | none |
| `[odd] …` | exercise | single line | none |
| `[discuss] …` | exercise (not graded) | single line | none |
| `[m]` | exercise | block | `[/m]` |
| `[long]` | exercise | block | `[/long]` |
| `[fix]` | exercise | block | `[/fix]` |
| `[transform] … (KEY)` | exercise | block | `[/transform]` |
| `[match]` | exercise | block | `[/match]` |
| `[order]` | exercise | block | `[/order]` |
| `[sort]` | exercise | block | `[/sort]` |
| `[bank]` or `[bank + extra, words]` | exercise | block | `[/bank]` |

A block tag line may carry its options and a quoted title, but its content always starts on the
NEXT line, and the closing tag is alone on its own line.


## 7. Presentation blocks (never numbered, never graded)

### Media clip – `[play]`
```
[play https://www.youtube.com/watch?v=p2hnrfN58H4 00:06 01:25 "Clip A – the land and the river"]
[play audio.mp3 00:47 01:50 "Clip A – building on mud"]
[play video.mp4 01:58 03:09 "Clip B – bridges and canals"]
```
- Order: source, start time, end time, "label". One space between parts.
- Source: a YouTube link (`youtube.com/watch?v=…`, `youtu.be/…`, `/shorts/…`), or a file name
  in the same folder (`.mp3`, `.m4a`, `.wav`, `.ogg` play as audio; `.mp4`, `.webm`, `.mov` as video),
  or a full web address of such a file.
- Times: `mm:ss` (or `hh:mm:ss`), digits only: `01:26`, not `1m26s`, not `86`. End after start.
  Leaving out the end time plays to the end; leaving out both plays everything.
- Label: in straight double quotes, short, telling: `"Clip A – the land and the river"`.
- The same clip may be repeated in several exercises (copy the line).

### Transcript – `[transcript]`
```
[transcript "Transcript (after you have finished)"]
Rob Mills: As an architect, it gives you the opportunity to capture space and light.
Narrator: The house sits low in the landscape.
[Music]
[/transcript]
```
- Put it directly after the `[play]` line it belongs to (blank lines between are fine).
  It then appears folded inside that player.
- One line per turn. `Name: text` shows the name in bold: the name starts with a capital letter,
  is at most 30 characters, and is followed by a colon and a space.
- Use real names or roles (`Rob Mills`, `Narrator`, `Interviewer`), never `Speaker 1`, `Speaker 2`.
- A line that is entirely in brackets (`[Music]`, `[Laughter]`) is shown as a sound cue.
- No gaps inside.

### Reading text – `[read]`
```
[read numbered] The House on the River | Original text written for this lesson
The first paragraph. The first letter gets a drop cap.

The second paragraph, after a blank line.
[/read]
```
- On the tag line, after `[read]` or `[read numbered]`: optional title, then ` | ` and optional source.
- `numbered` adds paragraph numbers in the margin.
- Paragraphs are separated by blank lines. Gaps `{…}` work inside (the text then becomes part
  of the current exercise).

### Image – `[img]`
```
[img image01.png "Plan of the ground floor"]
[img image02.png right "The staircase and skylight"]
[img logo.png left transparent "The studio's logo"]
```
- Order: file name, then options, then "caption". Options: `full` (default), `left`, `right`,
  `transparent`. No other options exist.
- Two or three `[img]` lines in a row (no blank line between them) form a grid.
- Always write a caption. Only use image files the teacher said they will supply.

### Fact box – `[note]`
```
[note "Did you know?"]
The Rialto Bridge rests on about 12,000 wooden piles.
[/note]
```

### Vocabulary list – `[vocab]` (reference, not an exercise)
```
[vocab "Key words"]
cantilever = a beam supported at only one end
load-bearing = carrying the weight of the structure above
[/vocab]
```
- One `term = meaning` per line. The first `=` separates them.

### Useful language – `[phrases]`
```
[phrases "Useful language"]
It could be argued that…
I take the point, but…
[/phrases]
```
- One phrase per line.

### Role cards – `[roles]`
```
[roles]
Client: Wants a home that feels hidden in the landscape.
Architect: Wants to show the river from every room.
[/roles]
```
- One `Role: description` per line.

### Timeline – `[timeline]`
```
[timeline]
1181 = A pontoon bridge is built
1591 = The stone bridge opens
[/timeline]
```
- One `when = what` per line.

### Pull quote – `[quote]`
```
[quote "Rob Mills"]
Less is more.
[/quote]
```
- The speaker in straight double quotes on the tag line: a real name or role, never `Speaker 2`.
- Quote the exact words, at most 15 words.

### Timer – `[timer]`
```
[timer 5:00 "Discuss in pairs"]
```
- Time as `m:ss` or `mm:ss`, then an optional "label".

### Link card – `[link]`
```
[link https://www.youtube.com/watch?v=p2hnrfN58H4 "Watch the full video"]
```

### Teacher's notes – `[teacher]`
```
[teacher]
**Clips.** A 00:06–01:25 (site), B 01:26–03:24 (interiors).

**If time is short,** skip exercise 6.
[/teacher]
```
- Shown folded at the end of the page, for the teacher only. Markdown works inside; gaps do not.
- Use one `[teacher]` block, at the end of the file.


## 8. Exercises

Each graded item gets Check / Show / Clear buttons and goes into the answer key automatically.
Typed gaps and short answers also get a folded "Need help? Word bank" automatically.

### Gap fill – `{answer}`
```
The settlers drove wooden {piles} into the mud and created an {oxygen-free|oxygen free} environment.
```
- The answer goes inside the braces, exactly as it completes the sentence.
- Accepted alternatives separated by `|`. The first one is the main answer.
- One gap per idea. Never two gaps next to each other.

### Dropdown gap – `{*right|wrong|wrong}`
```
The bridge {*was|were|has been} completed in 1591.
```
- 2–4 options separated by `|`. Exactly one starts with `*` (the correct one).

### Word formation – `{answer}(BASE)`
```
The {construction}(CONSTRUCT) took ten years.
```
- The base word in capitals in round brackets, immediately after the closing brace, no space.

### Gap fill with a word bank – `[bank]`
```
[bank + timber, glass]
The kitchen combines {bronze} and {alabaster} to create a {grounded} space.
[/bank]
```
- Write the text with gaps between `[bank]` and `[/bank]`. The page puts every gap answer
  into the bank by itself: do NOT list the answers.
- Optional extra (distractor) words after `+`, separated by commas, on the tag line.
  Extra words must NOT be answers of the gaps.
- Use one `[bank]` block per exercise. Write the text as normal sentences or a paragraph;
  do not number the lines.

### True or false – `[tf]`
```
[tf] The client already owned the land when he met the architect. [t]
[tf] The house was designed to stand out on top of the hill. [f]
```
- One statement per line, ending with `[t]` (true) or `[f]` (false). No gaps.

### Multiple choice – `[m]`
```
[m] Why did the designer travel overseas?
- To find cheaper building materials
* To find pieces that are hard to get in Australia
- To study French building methods
[/m]
```
- First line(s): the question. Then one option per line: `* ` for the correct option,
  `- ` for wrong options (the symbol, then a space). Exactly one `*`. 3–4 options.
- Nothing after the options except `[/m]`: no explanations, no "Answer:" lines.
- One question per `[m]` block. For several questions, write several blocks.

### Short answer – `[short]`
```
[short] What kind of tree grows at the base of the stairs? = a bottle tree|bottle tree
```
- Question, then ` = `, then the answer(s) on the same line. Answers are 1–3 words.
  Separate alternatives with `|`. List every reasonable form.

### Long answer – `[long]`
```
[long] Why does the architect call the house holistic?
= Because architecture, interiors, landscape, art and furniture were designed together as one project, not as separate disciplines.
[/long]
```
- The question, then ONE line starting with `= ` with one suggested answer (1–3 sentences).
- No `|`, no alternatives, no "Suggested answer:" label (the page adds it).
- Not auto-checked: students compare with the suggestion.

### Matching – `[match]`
```
[match]
holistic = treating all the parts as one whole
cocooning = making a space feel warm and enclosed
respite = a short rest from something difficult
[/match]
```
- One `term = definition` per line, in the correct pairs. The page shuffles them.
- 4–8 pairs. The term may not contain `=`.

### Ordering – `[order]`
```
[order]
The client buys the land.
The team writes the story of the house.
The designer travels to source furniture.
[/order]
```
- One item per line, in the CORRECT order. The page shuffles them. 3–8 items. No numbers.

### Error correction – `[fix]`
```
[fix]
The relationship creating by the building affects how clients feel.
= The relationship created by the building affects how clients feel.
[/fix]
```
- Line 1: a sentence that contains exactly ONE mistake.
- Line 2: ONE line starting with `= ` with the full corrected sentence. Accepted alternatives
  on the same line, separated by `|`.
- The wrong sentence must really be wrong. Never use `[fix]` for sentences that are already
  correct ("rewrite", "make it more formal", "use a participle"): use `[transform]` for that.
- One sentence per `[fix]` block. For several sentences, write several blocks.

### Key word transformation – `[transform]`
```
[transform]
Rob Mills values his relationships with clients more than anything else. (WHAT)
The relationships with clients = are what Rob Mills values = most.
[/transform]
```
WRONG – this is the most common mistake:
```
[transform]
Rob Mills values his relationships with clients more than anything else. (WHAT)
= The relationships with clients are what Rob Mills values = most.
[/transform]
```
The correct form, exactly:
```
[transform]
First sentence. (KEYWORD)
Start of the new sentence = answer|alternative answer = end of the new sentence.
[/transform]
```
- Line 1: the original sentence, then the key word in CAPITALS in round brackets at the end.
- Line 2: the new sentence with the missing part between two `=` signs:
  `start text = ANSWER = end text`. Line 2 never starts with `=`, never ends with `=`,
  and contains exactly two `=` signs. Start and end text are never empty.
- The answer is 2–5 words, contains the key word unchanged, and makes the new sentence mean
  the same as the first one. Accept contracted and full forms with `|`.
- Exactly two lines between `[transform]` and `[/transform]`. One item per block.

### Odd one out – `[odd]`
```
[odd] timber, bronze, alabaster, *skylight
```
- Words separated by commas, exactly one marked with `*` (the odd one). Words contain no commas.

### Categorising – `[sort]`
```
[sort]
Materials: timber, bronze, alabaster
Spaces: study, terrace, kitchen
[/sort]
```
- One `Category: item, item, item` per line. At least two categories. Each item belongs to one
  category only.

### Discussion prompt – `[discuss]`
```
[discuss] Should architects tell one strong story, or leave space for the people who will live there?
```
- One open question per line. Not graded, no answer.


## 9. Where gaps `{…}` work

| Gaps WORK in | Gaps do NOT work in (braces show as text) |
|---|---|
| normal paragraphs and list items | `[tf]`, `[m]`, `[short]`, `[long]`, `[fix]`, `[transform]` |
| table cells (not the header row) | `[match]`, `[order]`, `[sort]`, `[odd]`, `[discuss]` |
| inside `[read]` and `[bank]` | `[note]`, `[vocab]`, `[phrases]`, `[roles]`, `[timeline]`, `[quote]` |
| | `[transcript]`, `[teacher]`, headings, the header, rubrics |


## 10. How answers are checked

- Not case-sensitive. Accents, extra spaces and final punctuation (`. ! ? , ; :`) are ignored.
  Curly and straight apostrophes count as the same.
- Everything else must match one alternative exactly. So list real variants with `|`:
  contractions (`it's|it is`), hyphens (`well-known|well known`), numbers (`3|three`),
  British and American spelling (`travelled|traveled`), optional articles (`a bottle tree|bottle tree`).


## 11. Common mistakes (wrong → right)

| Wrong | Right |
|---|---|
| `[fix] Wrong sentence.` + `= Right sentence.` with no `[/fix]` | add `[/fix]` on its own line |
| `[m] Question? - a * b - c [/m]` on one line | question and each option on its own line |
| `[long]` answer `= Suggested answer: A.\|B.` | `= A.` (one answer, no label, no `\|`) |
| `[transform]` line 2 `= The relationships with clients are = most.` | `The relationships with clients = are what Rob Mills values = most.` |
| `[fix]` with a correct sentence to "rewrite" | `[transform]` with a key word |
| `[bank + glass, separate]` where `separate` is a gap answer | extras that are not answers |
| `[bank]` text written as `1. …` `2. …` | plain sentences or a paragraph |
| `[quote “Rob Mills”]` (curly quotes) | `[quote "Rob Mills"]` |
| `[quote "Speaker 2"]` / `Speaker 1:` in transcripts | a real name or role |
| `[tf] The {skylight} connects the levels. [t]` | no gaps in `[tf]` |
| `[short] Question? = answer [/short]` | no closing tag for `[short]` |
| `1. [tf] …` or `a) [m] …` | tags at the very start of the line, no numbering |
| `[Music]` on a normal line | only inside `[transcript]` |
| `style: classic (serif)` | `style: classic` |
| ```` ``` ```` / `eof` / a summary after `[/teacher]` | nothing after the lesson |
| `## Exercise 3: Vocabulary` | `## Key vocabulary \| Pairs · 5 minutes` |
| An "Answer key" section | nothing: the page builds it |


## 12. Final checklist

Go through the file line by line before you deliver it:

1. Line 1 is `---`; the header uses only the keys in section 4; `style:` is one of the six words.
2. Every `##` has a ` | Interaction · minutes` detail and a `> ` rubric.
3. Every graded item is inside a `##` exercise.
4. Every block tag (section 6) has its closing tag on its own line; no single-line tag has one.
5. Every `[tf]` ends in `[t]` or `[f]`; every `[short]` has ` = answer`; every `[odd]` has one `*`.
6. Every `[m]` has 3–4 options, exactly one `*`, each option on its own line starting with `* ` or `- `.
7. Every `[fix]` has a wrong sentence and one `= ` line; every `[long]` has one `= ` line without `|`.
8. Every `[transform]` has exactly two lines; line 2 has exactly two `=`, text before the first and
   after the second; the key word appears in the answer.
9. `[bank +]` extras are not answers. Gaps appear only where section 9 allows.
10. Every tag uses straight quotes `"`. No line outside `[transcript]` starts with `[` unless it is a tag.
11. Every `[play]` has a valid source and `mm:ss` times with start before end.
12. Nothing comes after the last `[/teacher]`; no code fences, no answer key, no comments.


## 13. Complete example

```
---
title: A House That Disappears
subtitle: Listening to an architect describe a house
level: C1
course: English for Architects
intro: A house on the Murray River was designed to sit quietly in the landscape. Listen to how its architect and designer explain their choices.
meta: About 25 minutes · Video: The Local Project, "Architect Designs a Home That Disappears Into the Hill"
style: classic
---

# Part 1 – Before you watch

## Warm-up | Pairs · 3 minutes
> Discuss the questions with a partner.

[quote "Rob Mills"]
Less is more.
[/quote]

[discuss] What do you expect a house that "disappears into the hill" to look like?
[discuss] When is restraint a sign of luxury?

## Key vocabulary | Individual · 4 minutes
> Match the words with their meanings.

[match]
holistic = treating all the parts as one whole
cocooning = making a space feel warm and enclosed
respite = a short rest from something difficult
alabaster = a soft, pale stone that lets light through
[/match]

# Part 2 – Watch

## The interiors | Individual · 8 minutes
> Watch the clip. Answer the questions, then complete the summary.

[play https://www.youtube.com/watch?v=p2hnrfN58H4 01:26 03:24 "Clip A – inside the house"]

[transcript "Transcript (after you have finished)"]
Designer: This project is a very holistic design approach towards architecture, interiors, landscape, art, and furniture.
[/transcript]

[tf] The designer sees architecture and interiors as separate disciplines. [f]

[m] What connects the two levels of the house?
- A glass lift
* A large skylight above the staircase
- A double-height kitchen
[/m]

[bank + steel, glass]
In winter, the study feels {cocooning} and warm. In the kitchen, timber, bronze and {alabaster} create a {grounded} space.
[/bank]

## Language focus | Individual · 6 minutes
> Correct the mistake in the first sentence. Then complete the second sentence so that it means the same as the first. Use the word in capitals.

[fix]
The relationship creating by the building affects how clients feel.
= The relationship created by the building affects how clients feel.
[/fix]

[transform]
Rob Mills values his relationships with clients more than anything else. (WHAT)
The relationships with clients = are what Rob Mills values = most.
[/transform]

# Part 3 – Talk about it

## Discussion | Groups · 4 minutes
> Discuss the questions in small groups.

[discuss] Should a house tell one strong story, or leave space for the people who live in it?

[timer 4:00 "Discuss in groups"]

[teacher]
**Clip.** A 01:26–03:24: holistic design, skylight, study, kitchen materials.
[/teacher]
```
