---
title: The Incredible Engineering of Venice
subtitle: A LessonMark guide: every way to present content, and every type of activity
level: C1
intro: In the 560s, people fleeing invaders hid in a swampy lagoon and turned it into one of the richest cities in the world. This lesson tells their story and, at the same time, shows teachers everything LessonMark can do.
meta: Video: TED-Ed, “The incredible engineering of Venice” by Stephanie H. Smith · Files: video.mp4, audio.mp3, image01–04.png
style: classic
---

[note "Start here: how LessonMark works"]
A lesson is one plain text file called **data.md**, saved in the same folder as **index.html**, together with any audio, video and images it uses. The page reads the file and builds everything: numbers, menu, players, buttons and the answer key.

The guide has two parts. **Part 1 – Presentation** shows every way to put content on the page. **Part 2 – Activities** shows every type of exercise. Each section has a short description, a live example and a **Notation** box with exactly what to type.

- The header between the two `---` lines sets `title:`, `subtitle:`, `level:`, `intro:`, `meta:` and `style:` (classic or modern).
- `# Part title` starts a part. `## Section title | details` starts a numbered section; the text after `|` is optional.
- If something in data.md is wrong, a red box at the top of the page says which line to fix.
[/note]

# Part 1 – Presentation

## Text and instructions | Plain Markdown and `>`
Normal text is written as it is. Use Markdown for **bold**, *italics* and lists. Instructions for students go in the blue box.

> Read about the first settlers. You will hear more about them in Clip A (Section 5).

In the late 560s, a Germanic group called the **Lombards** invaded northern Italy. To escape them, families fled by boat into the *Venetian Lagoon*, a maze of mudflats and islands that was:
- the perfect place to hide,
- and a very unstable place to live.

[note "Notation"]
- Write text normally. `**bold**`, `*italics*`, and lines starting with `- ` make a list.
- `> Instructions for students.` – the blue instructions box.
- `### Subheading` – a small heading inside a section.
[/note]

## Reading text | `[read]`
A text for reading, with a title, a source line and a large first letter. Add `numbered` to number the paragraphs so questions can refer to them.

[read numbered] Can Venice Be Saved? | Original text written for this lesson
For a thousand years, the lagoon was Venice's best defence. Its shallow, shifting channels kept enemy fleets away, and its mud kept the city's foundations alive. Now the water has become the enemy.

At the start of the twentieth century, St Mark's Basilica flooded about seven times a year. Today it floods hundreds of times. Rising sea levels are part of the problem, but not all of it: waves from fast motorboats slowly wear away the mud that protects the ancient piles.

In 2020, Venice raised a system of mobile flood barriers, known as MOSE, for the first time. They work, but they are expensive to run, and closing the lagoon too often could damage its fragile ecosystem.
[/read]

[note "Notation"]
- `[read numbered] Title | Source` on the first line, then the paragraphs, then `[/read]`.
- Title, source and `numbered` are all optional. Gaps can go inside a reading text too.
[/note]

## Images | `[img]`
Images are always shown square. They can fill the column, or sit on the left or right of the text. Transparent PNGs blend with the page, with no box behind them.

[img image04.png right transparent "A cluster of wooden piles (a transparent PNG)"]

The first settlers drove clusters of wooden piles, one to three metres long, into the mud. The process squeezed out the water and packed the mud tightly around each pile. With no oxygen, insects and fungi could not attack the wood, which is why the piles are still holding Venice up 1,500 years later.

[img image02.png "A Venetian foundation: brick walls, stone platforms, timber and piles"]

[note "Notation"]
- `[img image02.png "Caption"]` – full width.
- `[img image04.png right "Caption"]` – beside the text; also `left`.
- Add `transparent` for see-through PNGs: `[img piles.png right transparent "Caption"]`.
- Always write a caption: it is also read aloud for blind users.
[/note]

## Image grid | Several `[img]` lines in a row
Two or three images on consecutive lines are shown side by side, ideal for comparing.

[img image01.png "Above the water: the bridge visitors see"]
[img image02.png "Below the water: the foundations nobody sees"]
[img image03.png "Plan view: a dense grid of piles under one pier"]

[note "Notation"]
- Write the `[img]` lines one after another, with no empty line between them.
[/note]

## Audio clip | `[play]` with an .mp3 file
Plays only part of a recording, with play/pause, a progress bar, restart and a slower speed.

[play audio.mp3 00:47 01:50 "Clip A – building on mud"]

[note "Notation"]
- `[play audio.mp3 00:47 01:50 "Clip A – building on mud"]` – file, start time, end time, name.
- Times use minutes:seconds. Leave out the end time to play to the end, and both times to play everything.
[/note]

## Transcript | `[transcript]`
A folded transcript inside the player above it, for students to open after listening.

[play audio.mp3 00:47 01:50 "Clip A – with its transcript"]
[transcript "Transcript (after you have finished)"]
Narrator: So the new arrivals set out to tame the lagoon and build the most unlikely of cities from the mud.
Narrator: While some fishermen already inhabited the region in stilted huts, the settlers wanted to build a foundation to support heavier, longer-lasting structures.
Narrator: They drove clusters of 1-to-3-meter-long wooden piles into the ground in a process that squeezed out groundwater and compacted mud around the piles.
Narrator: This created an oxygen-free environment that protected the wood from insects and fungi.
[/transcript]

[note "Notation"]
- Put `[transcript "Button text"]` straight after a `[play]` line, then one line per speaker as `Name: text`, then `[/transcript]`.
- A line in square brackets, like `[Music]`, is shown in grey italics.
[/note]

## Video clip | `[play]` with an .mp4 file
The same tag plays part of a video file stored next to the page.

[play video.mp4 01:58 03:09 "Clip B – bridges, canals and trade"]

[note "Notation"]
- `[play video.mp4 01:58 03:09 "Clip B"]` – works with .mp4, .webm and .mov.
[/note]

## YouTube clip | `[play]` with a YouTube link
The same tag again, with a YouTube link instead of a file.

[play https://www.youtube.com/watch?v=uBwkMc1llmM 03:09 04:37 "Clip C – the deal that built an empire"]

[note "Notation"]
- `[play https://www.youtube.com/watch?v=uBwkMc1llmM 03:09 04:37 "Clip C"]` – short youtu.be links work too.
- YouTube needs the page to be online; it usually refuses to play when the page is opened by double-click.
[/note]

## Table | Markdown table
Tables organise information. Gaps can go inside cells (see Section 21).

| Period | What happened in Venice |
|--------|-------------------------|
| 560s | Settlers flee into the lagoon |
| c. 697 | The Republic of Venice is declared |
| 1797 | French attacks end the Republic |
| Today | Floods and tourism threaten the city |

[note "Notation"]
- `| Column | Column |` on the first line, `|---|---|` on the second, then one row per line.
[/note]

## Fact box | `[note]`
A shaded box for background information, a curious fact or a tip.

[note "Did you know?"]
In 1900, St Mark's Basilica flooded about seven times a year. According to the video, it now floods roughly 250 times a year.
[/note]

[note "Notation"]
- `[note "Title"]`, the text, then `[/note]`. A short note can sit on one line: `[note "Tip"] Text. [/note]`
- These Notation boxes are notes too.
[/note]

## Vocabulary | `[vocab]`
A two-column glossary for reference. It is not an exercise.

[vocab]
pile = a long wooden post driven into the ground to support a building
lagoon = an area of shallow water separated from the sea
impervious to = not affected or damaged by something
longevity = how long something lasts
[/vocab]

[note "Notation"]
- `[vocab "Title"]`, one `word = meaning` per line, then `[/vocab]`. The title is optional.
[/note]

## Useful language | `[phrases]`
A box of phrases students can use in a speaking task, in two columns.

[phrases "Useful language for discussing Venice"]
What strikes me is that…
It could be argued that…
I'd go along with that up to a point, but…
Surely the real issue is…
[/phrases]

[note "Notation"]
- `[phrases "Title"]`, one phrase per line, then `[/phrases]`.
[/note]

## Role cards | `[roles]`
Cards for role plays and debates.

[roles]
Structural engineer: Wants to repair the oldest foundations first.
Tourism manager: Wants to limit motorboats without losing visitors.
Resident: Lives on a ground floor that floods every winter.
Environmental scientist: Worries that closing the lagoon will damage it.
[/roles]

[note "Notation"]
- `[roles]`, one `Role: description` per line, then `[/roles]`.
[/note]

## Timeline | `[timeline]`
Dates and events on a vertical line. Any text works as a date.

[timeline]
560s = People flee the Lombards into the lagoon
c. 697 = The Republic of Venice is declared
1453 = The Ottomans conquer Constantinople
1866 = Venice becomes part of Italy
[/timeline]

[note "Notation"]
- `[timeline]`, one `date = event` per line, then `[/timeline]`.
[/note]

## Pull quote | `[quote]`
A large quotation, good for opening a discussion.

[quote "TED-Ed"] The lessons of yesterday can help us face the challenges of today. [/quote]

[note "Notation"]
- `[quote "Speaker"] Text. [/quote]` – on one line or over several lines.
[/note]

## Timer | `[timer]`
A countdown the teacher starts in class.

[timer 2:00 "Tell your partner the story of Venice"]

[note "Notation"]
- `[timer 2:00 "Label"]` – minutes:seconds; `[timer 5]` means five minutes.
[/note]

## Link card | `[link]`
A clear box that opens a web page in a new tab.

[link https://www.youtube.com/watch?v=uBwkMc1llmM "Watch the full video on YouTube"]

[note "Notation"]
- `[link https://… "Title"]`
[/note]

## Teacher's notes | `[teacher]`
Notes for the teacher. They are hidden from the lesson and collected in a folded box at the very end of the page.

[teacher]
**Clips used in this guide.** A 00:47–01:50 (foundations), B 01:58–03:09 (bridges and canals), C 03:09–04:37 (trade and the Crusade). Video: TED-Ed, “The incredible engineering of Venice”, Stephanie H. Smith.

**Several lessons in one folder.** Name them venice.md, bridges.md… and open index.html?lesson=venice.md.
[/teacher]

[note "Notation"]
- `[teacher]`, the notes, then `[/teacher]`. Scroll to the bottom of the page to see them.
[/note]

# Part 2 – Activities

[note "How activities work"]
Every section with answers gets **Check answers**, **Show answers** and **Clear** buttons, and its answers go into the **Answer key** at the end of the page. Sections with typed answers also get a folded **Need help? Word bank**. You write none of this: it appears by itself. Checking ignores capitals, accents and final full stops.
[/note]

## Gap fill | Answers in curly brackets
> Listen to Clip A and complete the text. Write one or two words in each gap.

[play audio.mp3 00:47 01:50 "Clip A – building on mud"]

Some fishermen already lived in the region in {stilted} huts, but the settlers wanted a {foundation} for heavier, longer-lasting structures. They drove clusters of wooden {piles} into the ground. This {squeezed out} groundwater and {compacted} the mud around them, creating an {oxygen-free|oxygen free} environment that protected the wood from insects and {fungi}.

[note "Notation"]
- Write the answer in curly brackets: `{piles}`. Accept other answers with a bar: `{oxygen-free|oxygen free}`.
- Gaps work in normal text, tables and reading texts.
[/note]

## Gap fill with a word bank | `[bank]`
> Complete the text with words from the box. There are two extra words.

[bank + flourished, sheltered]
For centuries, Venice's {dominance} of the Mediterranean seemed secure. After the Ottomans took Constantinople, the Republic {soldiered on} for another 300 years, until it was finally {ceded} to Italy in 1866. Today, waves from motorboats {erode} the mud that protects its foundations.
[/bank]

[note "Notation"]
- `[bank + extra, words]`, the text with gaps, then `[/bank]`. The box shows the answers and the extra words, shuffled.
[/note]

## Table completion | Gaps inside a table
> Watch Clip C and complete the notes about the Fourth Crusade.

[play https://www.youtube.com/watch?v=uBwkMc1llmM 03:09 04:37 "Clip C – the deal that built an empire"]

| The deal | Details |
|----------|---------|
| Arranged by | the {Pope} |
| Soldiers expected | {33,000|33000} |
| Soldiers who arrived | {one third|a third|1/3} |
| City attacked instead | {Constantinople} |

[note "Notation"]
- A normal table with `{answers}` in the cells.
[/note]

## Choose the right word | Dropdown gaps
> Choose the correct word for each gap.

The settlers wanted a foundation that would {*support|carry out|hold on} heavier buildings. The city's layout {*necessitated|neglected|navigated} foot travel for all classes. The Pope {*brokered|broke|brought} an arrangement with Venice's leader.

[note "Notation"]
- `{*right|wrong|wrong}` – the asterisk marks the correct option.
[/note]

## Word formation | Gap with a base word
> Use the word in capitals to form a word that fits the gap.

Venice's {dominance}(DOMINATE) over the Mediterranean lasted for centuries.
Each new bridge used materials that improved its {longevity}(LONG).
Motorboat waves are causing serious {erosion}(ERODE) of the lagoon's mud.

[note "Notation"]
- `{answer}(BASE WORD)` – the base word appears after the gap.
[/note]

## True or false | `[tf]`
> Decide whether each statement is true or false according to Clip A.

[tf] Nobody lived in the lagoon before the settlers arrived. [f]
[tf] Driving the piles removed water from the surrounding mud. [t]
[tf] The lack of oxygen protected the wood from insects and fungi. [t]

[note "Notation"]
- `[tf] Statement. [t]` for true, `[f]` for false – one line each.
[/note]

## Multiple choice | `[m]`
> Watch Clip B and choose the best answer.

[play video.mp4 01:58 03:09 "Clip B – bridges, canals and trade"]

[m] What was the problem with the first footbridges?
- They were too narrow for carts
* They were prone to decay, collapse and fire
- They blocked the way for boats
[/m]

[m] How was Venice different from the rest of Europe?
- Nobles travelled by boat while commoners walked
* Everyone, rich or poor, had to travel on foot
- Only merchants could use the canals
[/m]

[note "Notation"]
- `[m] Question?`, then one option per line: `* correct` and `- wrong`, then `[/m]`.
[/note]

## Short answers | `[short]`
> Answer in one to three words.

[short] What did Venice have no land for? = farming
[short] What kind of boats navigated the canals? = gondolas|slender gondolas

[note "Notation"]
- `[short] Question? = answer|other accepted answer` – one line each.
[/note]

## Long answers | `[long]`
> Answer in two or three sentences, then compare with the suggested answer.

[long] Why have the wooden piles not rotted after 1,500 years?
= Driving them in squeezed out the water and packed the mud around them, so there is no oxygen. Without oxygen, insects and fungi cannot attack the wood.
[/long]

[note "Notation"]
- `[long] Question?`, then `= suggested answer`, then `[/long]`. Students write freely and can open the suggestion.
[/note]

## Matching | `[match]`
> Match each term to its definition.

[match]
foundation = the solid base that carries a building's weight
stilted hut = a simple house raised above water on posts
beam = a long horizontal piece of wood in a structure
platform = a flat raised surface that spreads a load
[/match]

[note "Notation"]
- `[match]`, one `term = definition` per line, then `[/match]`. Write the correct pairs; the page shuffles them.
[/note]

## Ordering | `[order]`
> Put the stages of the city's development in the order they happened.

[order]
Settlers flee into the lagoon to escape the Lombards.
Wooden piles are driven into the mud.
Footbridges are built to connect the islands.
The channels are lined with stone to create canals.
Venice becomes a port linking Europe to the Silk Road.
[/order]

[note "Notation"]
- `[order]`, the lines in the correct order, then `[/order]`. The page shuffles them.
[/note]

## Correct the mistakes | `[fix]`
> Each sentence has one mistake. Rewrite it correctly.

[fix] The piles has supported Venice for 1,500 years.
= The piles have supported Venice for 1,500 years.
[/fix]

[fix] Venice was depend on trade because it had no farmland.
= Venice was dependent on trade because it had no farmland.|Venice depended on trade because it had no farmland.
[/fix]

[note "Notation"]
- `[fix] Wrong sentence.`, then `= Correct sentence.|Another correct version.`, then `[/fix]`.
[/note]

## Key word transformations | `[transform]`
> Complete the second sentence so that it means the same as the first. Use the word in capitals and two to five words.

[transform] Only a third of the soldiers arrived. (TURNED)
Only a third of the soldiers = turned up = .
[/transform]

[transform] If nobody deals with these problems, they could destroy the city. (UNADDRESSED)
If these problems are = left unaddressed = , they could destroy the city.
[/transform]

[note "Notation"]
- `[transform] First sentence. (KEY WORD)`, then `Start = answer = end.`, then `[/transform]`.
[/note]

## Odd one out | `[odd]`
> Choose the word that does not belong.

[odd] piles, beams, platforms, *gondolas
[odd] silks, spices, glass, *floods

[note "Notation"]
- `[odd] word, word, *odd one, word` – the asterisk marks the answer.
[/note]

## Categorising | `[sort]`
> Decide whether each item helped Venice or threatens it.

[sort]
Helped Venice: wooden piles, canal network, Silk Road trade
Threatens Venice: rising sea levels, motorboat waves, mass tourism
[/sort]

[note "Notation"]
- `[sort]`, one `Category: item, item` per line, then `[/sort]`.
[/note]

## Discussion | `[discuss]`
> Discuss the questions in groups. Use the useful language from Section 12.

[discuss] Should cities like Venice limit the number of tourists? How?
[discuss] Would you spend public money to protect a city that may sink anyway?
[discuss] Which building in your city would you protect first, and why?

[note "Notation"]
- `[discuss] Question?` – a numbered speaking prompt with no answer and no buttons.
[/note]
