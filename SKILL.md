---
name: lessonmark-lesson
description: Turn a YouTube link and its timestamped script into a complete LessonMark data.md lesson: clips, vocabulary, grammar, listening tasks and discussion.
---

# LessonMark lesson builder

Input: a YouTube link and a timestamped script or transcript (pasted or attached). Output: one `data.md` file in LessonMark notation, ready to drop next to LessonMark's `index.html`, plus a short summary for the teacher.

LessonMark: https://jeronimovis.github.io/lessonmark/ · Reference: https://jeronimovis.github.io/lessonmark/LessonMark-reference.html

## 0. Settle the brief (ask only if unclear; otherwise use defaults and state them)

- **Level:** default C1.
- **Learners:** default adult professionals. If the teacher mentions a group (e.g. architects and engineers), angle vocabulary choices, examples and discussion to their field.
- **Length:** default **30–60 minutes**. Aim for about 45 minutes unless the teacher gives a length. If the teacher asks for a longer class, scale up with the larger numbers in each range below.
- **Media:** default YouTube clips from the link. If the teacher says `audio.mp3` / `video.mp4` with the same content sit next to the page, use those files with the same timestamps (they work offline). Never invent files that were not mentioned, except images the teacher will supply: then name them `image01.png`… and say so.
- **Style:** `classic` unless asked for `modern`.

## 1. Read the script like a teacher

1. Identify topic, speakers, structure and the story arc. Note where the real content starts and ends: skip intros, sponsor messages, calls to subscribe and credits.
2. Mark natural sections (topic shifts, new speaker, new stage of the story).
3. Flag lines marked uncertain in the script and avoid building answers on them.

## 2. Choose the clips

- **2–3 clips** of **60–120 seconds** each for a 30–60 minute class (up to 4 for longer classes), starting and ending at sentence boundaries. A clip may be replayed in several exercises.
- Use **only timestamps that appear in the script**. Start about a second before the first word if the script allows (round down), end after the last word (round up).
- Give each clip a short, telling name: `"Clip A – building on mud"`.

## 3. Mine the language

Work clip by clip and keep a list with the timestamp of each item.

**Vocabulary (8–14 items; up to 20 for longer classes).** Prefer, in this order:
1. Words the learners will reuse in their field (domain terms with transfer value: *load-bearing, compacted, longevity*).
2. Strong collocations and chunks (*broker an arrangement, lay the foundation for, prone to decay*).
3. Phrasal verbs and idioms (*soldier on, put the word out*).
4. Academic/C1 words from the AWL or above (*necessitate, impervious, unprecedented*).
Skip proper nouns, words learners at this level surely know, and words whose meaning in context is unusual or misleading.

**Grammar (1–2 points; up to 3 for longer classes).** Only structures that actually occur in the script, with the line they come from. Good C1 targets: passives and passive reporting, participle clauses, inversion (*little did they know*), cleft sentences, nominalisation, mixed conditionals, modals of speculation and deduction, narrative tenses, reduced relative clauses, linking and contrast (*despite, yet, whereas*). Build each language-focus exercise from these lines.

**Discussion angles (2–4).** Look for: a dilemma or trade-off, a controversial claim, a cause–effect worth questioning, a link to the learners' own work or country, an ethical issue, a "what would you have done?" moment. Write open questions that need opinions plus reasons, never questions with a factual answer.

## 4. Build the lesson arc

Use `# Part` headings for stages and `## Exercise title | Interaction · minutes` for each numbered exercise. Every exercise starts with a `>` rubric written to students. The minutes in the `|` lines must add up to the class length. A typical 30–60 minute arc (adapt; drop what does not fit the material):

1. **Lead-in (3–5 min)** – an image or a pull quote and 2 `[discuss]` prompts that activate ideas and make students predict.
2. **Key vocabulary (4–6 min)** – `[vocab]` for reference or a `[match]` of 5–6 words needed for the first listening.
3. **Listening for gist (5–8 min)** – first clip; 3–4 `[m]` or `[tf]` items on main ideas.
4. **Listening for detail (8–12 min)** – gap fill of 6–10 gaps built from the exact transcript words (key vocabulary), or a table completion with numbers, dates and names. Put `[transcript]` right after the `[play]` line of that clip.
5. **Second clip (5–10 min, if time)** – `[short]`, `[long]`, `[order]` for sequences of events, or a `[timeline]` for chronology.
6. **Language focus (5–10 min)** – one or two exercises on the grammar and vocabulary from the script: word formation `{answer}(BASE)`, key word transformations, dropdowns, error correction, `[bank]` gap fill, `[odd]` or `[sort]`.
7. **Speaking (8–15 min)** – 2–4 `[discuss]` prompts with a `[phrases]` box and a `[timer]`; for 50–60 minutes, a short role play with `[roles]` instead.
8. **`[teacher]`** – clip list with times and content, timing tips, the grammar points and where they occur, what to cut if time runs short, and ideas for fast finishers or homework.

For classes longer than 60 minutes add a third clip, an original `[read]` text that extends the topic (marked `Original text written for this lesson`), more language focus, a `[note "Did you know?"]` and a fuller role play.

## 5. Rules for good items

- **Gap fills:** answers are the exact words in the transcript; one gap per idea; never two gaps side by side; accept real variants with `|` (`{oxygen-free|oxygen free}`, `{33,000|33000}`). The sentence around the gap stays faithful to the clip.
- **Multiple choice:** 3–4 options, one `*` correct; distractors plausible (they use words from the clip or a common misunderstanding), similar in length, no "all of the above".
- **True/false:** balance true and false; paraphrase rather than copy the script, so students must understand, not match words; avoid trick negatives.
- **Short answers:** 1–3 words; list every reasonable answer with `|`.
- **Long answers:** need inference or explanation; the suggested answer is 1–3 sentences.
- **Matching:** 4–8 pairs; definitions of similar length.
- **Word formation / transformations:** C1 difficulty; the key word in capitals; transformation answers 2–5 words with contracted and full forms accepted.
- Questions follow the order of the clip. Answers never depend on outside knowledge.
- Use the learners' field for examples and discussion where natural.

## 6. Respect the source

- Credit the video in `meta:` and in `[teacher]` (title, channel or speaker).
- Include transcript text only inside `[transcript]` blocks for clips used in the lesson and inside gap-fill sentences; keep any `[quote]` under 15 words.
- Reading texts are your own writing, not copied from articles.

## 7. Check before delivering

- Header complete; `meta:` states the class length; every `##` has a `|` detail line and a `>` rubric; the minutes add up to the class length.
- Every `[play]` uses the given link or the named local files, with timestamps from the script, start < end.
- Every block tag is closed (`[/m]`, `[/match]`, `[/transcript]`…); every `[tf]` ends in `[t]` or `[f]`; every `[m]` has exactly one `*`; every `[odd]` has one `*`.
- No `{` `}` outside gaps (write `\{ \}` if needed). No literal `[` at the start of a normal line unless it is a tag.
- Every gap answer appears in the transcript at the clip's time.

## 8. Deliver

Write the file as `data.md` (or the name the teacher asks for) and hand it over. Then give a short summary: the class length, the clips with times and content, the vocabulary chosen, the grammar points with their source lines, and the discussion focus. Mention any assumptions (level, learners, length, media) and anything the teacher must supply (images, local media files).

---

# LessonMark notation reference

Tags are in square brackets at the start of a line. One-line items end on the same line; blocks close with `[/tag]` (a short block can open and close on one line). `*` = correct option, `=` = answer, `|` = alternatives, `"double quotes"` inside a tag = title, caption or label. Curly brackets always make a gap. Times are `mm:ss` or `hh:mm:ss`. Exercises are numbered and checked automatically; presentation blocks are not. The page adds Check / Show / Clear buttons, a "Need help?" word bank (for typed gaps and short answers) and an answer key by itself: never write a key.

## Header and structure
```
---
title: Lesson title
subtitle: One-line tagline
level: C1
intro: A short paragraph that sets the scene
meta: About 45 minutes · Video: Channel, “Title”
style: classic
---

# Part 1 – Before you watch
## Warm-up | Pairs · 5 minutes
> Instructions for students.
### Optional subheading
```
Plain Markdown: paragraphs, `**bold**`, `*italics*`, `- lists`, `[text](url)`, tables (`| a | b |` then `|---|---|`; gaps allowed in cells).

## Presentation blocks
```
[read numbered] Title | Source
Paragraph one…

Paragraph two…
[/read]

[img image01.png "Caption"]
[img image01.png right "Caption"]          (also left; add transparent for see-through PNGs)

[play https://youtu.be/ID 00:47 01:50 "Clip A – name"]
[play audio.mp3 00:47 01:50 "Clip A – name"]
[play video.mp4 01:58 03:09 "Clip B – name"]

[transcript "Transcript (after you have finished)"]
Narrator: text of the clip…
[Music]
[/transcript]

[note "Did you know?"]
Text.
[/note]

[vocab "Key words"]
word = meaning
[/vocab]

[phrases "Useful language"]
It could be argued that…
[/phrases]

[roles]
Role: description
[/roles]

[timeline]
1591 = The stone bridge opens
[/timeline]

[quote "Speaker"] Short quotation. [/quote]

[timer 5:00 "Discuss in pairs"]

[link https://… "Watch the full video"]

[teacher]
Notes for the teacher, shown folded at the end of the page.
[/teacher]
```

## Exercises
```
Gap fill:          The settlers drove wooden {piles} into the {mud|ground}.
Dropdown:          The bridge {*was|were|has been} completed in 1591.
Word formation:    The {construction}(CONSTRUCT) took ten years.

[bank + extra, words]
Text with {gaps}.
[/bank]

[tf] Statement. [t]
[tf] Statement. [f]

[m] Question?
- wrong
* right
- wrong
[/m]

[short] Question? = answer|other answer

[long] Question?
= Suggested answer.
[/long]

[match]
term = definition
[/match]

[order]
First event (write in the correct order; the page shuffles)
Second event
[/order]

[fix] Wrong sentence.
= Correct sentence.|Another correct version.
[/fix]

[transform] First sentence. (KEY WORD)
Start of second sentence = answer|alternative = end.
[/transform]

[odd] word, word, *odd one, word

[sort]
Category: item, item, item
Category: item, item, item
[/sort]

[discuss] Open question?
```
