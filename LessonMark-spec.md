# LessonMark – notation for lesson files

You will turn a script, transcript or text into ONE lesson file (.md) using the notation below.
Output only the file content. Plain Markdown is allowed for headings, bold, italics, lists and tables.
Do not write an answer key: the page generates it automatically from the markers.

## General rules
- Tags are in square brackets and start at the beginning of a line.
- One-line items end on the same line. Multi-line blocks close with [/tag].
  A short block may also be written on one line: [note "Tip"] Text here. [/note]
- `*` marks a correct option. `=` introduces an answer. `|` separates accepted alternatives.
- Text in "double quotes" inside a tag is a title, caption or label.
- Never use { } in normal text; braces are reserved for gaps. Write \{ \} \[ \] for literal symbols.
- Times use mm:ss or hh:mm:ss.
- Base all questions on the script. Only use clip times that appear in the script.
- Exercises (tasks with answers) are numbered and checked. Presentation blocks (texts, images,
  transcripts, notes…) are never numbered and can appear anywhere.

## File header
---
title: Lesson title
subtitle: One-line tagline (optional)
level: C1
intro: A short paragraph that sets the scene (optional)
meta: About 60 minutes · Audio: audio.mp3 (optional)
style: classic (optional: classic = serif, modern = sans serif; readers can still switch)
---

## Structure
# Part 1 – Listening                      ← part title, not numbered
## Exercise title | Pairs · 10 minutes    ← numbered exercise; text after " | " is optional
### Subheading                            ← optional heading inside an exercise

## Instructions (rubric) – one at the start of each exercise
> Listen to the extract and answer the questions.


# PRESENTING MATERIAL

## Reading text (title | source; first letter gets a drop cap)
[read] The Bridge That Kept Falling Down | Adapted from Venice: A Biography, 2009
Venice is built on 118 small islands. For centuries the only way across the
Grand Canal was a single bridge at the Rialto…

The first crossing was a **pontoon bridge**, built around 1181…
[/read]
- Title and source are optional: [read] alone is fine.
- [read numbered] adds paragraph numbers in the margin, so questions can say "in paragraph 3".
- Gaps {like this} work inside a reading text.

## Image (shown as a square, cropped from the centre; caption in quotes)
[img image01.png "Schematic plan of Toronto City Hall"]
[img plan.png right "The Rialto Bridge, 1591"]
- Position: full (default), left or right (smaller, beside the text).
- Two or three [img] lines in a row form a grid.
- Always write a caption: it is also the description for screen readers.
- Transparent PNGs blend with the page (no box behind, never cropped). The page detects them;
  add `transparent` to be sure: [img piles.png right transparent "Caption"]

## Media clip (YouTube link, .mp3 or .mp4; name in quotes is optional)
[play audio.mp3 01:53 02:37 "Extract 1 – the first bridges"]
[play https://youtu.be/ID 01:53 02:37 "Part A"]

## Transcript (folded until opened; "Name:" at the start of a line = speaker)
[transcript]
Masha: In the 50s, Toronto decided it needed a new city hall.
Sean: But he wasn't satisfied with simply designing the building.
[/transcript]
- Put it right after the [play] it belongs to.

## Note / fact box (title optional)
[note "Did you know?"]
The Rialto Bridge rests on about 12,000 wooden piles.
[/note]

## Vocabulary (reference list, not an exercise)
[vocab]
mimetic = imitating or copying something
cantilever = a beam supported at only one end
[/vocab]

## Useful language (phrase box in two columns; title optional)
[phrases "Useful language"]
It could be argued that…
What strikes me is…
I'd go along with that up to a point, but…
[/phrases]

## Role cards
[roles]
Budget officer: Is worried about the cost of restoration and storage.
Heritage conservationist: Argues for protecting modern design as well as old buildings.
[/roles]

## Timeline
[timeline]
1181 = A pontoon bridge is built across the Grand Canal
1444 = The wooden bridge collapses under a crowd
1591 = The stone bridge opens
[/timeline]

## Pull quote (speaker in quotes)
[quote "Viljo Revell"] The biggest disappointment of my life. [/quote]

## Timer (countdown the teacher starts in class; label optional)
[timer 5:00 "Discuss in pairs"]

## Link card
[link https://www.toronto.ca/city-hall "Toronto City Hall – official page"]

## Teacher's notes (collected in a folded box at the end of the page)
[teacher]
Clip times refer to the full episode. Skip Part C if time is short.
[/teacher]


# EXERCISES

## Gap fill (anywhere in normal text, tables or reading texts)
The main problem with {architecture} is that it is not usually {well paid|well-paid}.
- Every exercise with typed gaps or short answers automatically gets a folded
  "Need help? Word bank" with its answers. Nothing to write. (Not added where [bank] already shows the words.)

## Gap fill with word bank (+ optional extra words)
[bank + concrete, timber]
Text with {gaps}.
[/bank]

## Dropdown gap
The bridge {*was|were|has been} completed in 1591.

## Word formation
The {construction}(CONSTRUCT) took ten years.

## True / false (ends with [t] or [f])
[tf] The Rialto Bridge was built once and never rebuilt. [f]

## Multiple choice (one option per line; * = correct, - = wrong)
[m] How did Dandolo react?
- He cancelled the deal and sent the ships home
* He redirected the army against Venice's Christian rivals
- He resigned as leader of the Republic
[/m]

## Long answer (= suggested answer)
[long] The first footbridges had three weaknesses. What were they?
= They were prone to decay, collapse and fire.
[/long]

## Short answer (auto-checked, 1–3 words)
[short] In what year did the stone bridge open? = 1591

## Matching (write correct pairs; page shuffles)
[match]
cantilever = a beam supported at only one end
load-bearing wall = a wall that supports the structure above it
[/match]

## Ordering (write in correct order; page shuffles)
[order]
The wooden bridge burned down.
A competition was held for a stone design.
The stone bridge opened in 1591.
[/order]

## Error correction
[fix] The bridge were built in 1591.
= The bridge was built in 1591.
[/fix]

## Key word transformation
[transform] They rebuilt the bridge three times. (BEEN)
The bridge = has been rebuilt = three times.
[/transform]

## Odd one out (* = the odd one)
[odd] concrete, steel, *cantilever, timber

## Categorising
[sort]
Materials: concrete, steel, timber
Structural elements: beam, column, slab
[/sort]

## Discussion prompt (no answer)
[discuss] Would you restore a historic bridge or replace it with a modern design?
