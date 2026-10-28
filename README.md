<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="logo/dropcap-classic-dark.svg">
    <img src="logo/dropcap-classic-light.svg" alt="LessonMark" width="420">
  </picture>
</p>

<p align="center">
  <b>Write a lesson in a simple text file. Get a beautiful, interactive lesson page.</b><br>
  Video clips, reading texts, images and self-checking exercises, from plain text.
</p>

<p align="center">
  <a href="https://jeronimovis.github.io/lessonmark/lesson/"><b>🎬 Try a real lesson</b></a>
  &nbsp;·&nbsp;
  <a href="https://jeronimovis.github.io/lessonmark/"><b>✨ Feature guide</b></a>
  &nbsp;·&nbsp;
  <a href="https://jeronimovis.github.io/lessonmark/LessonMark-reference.html"><b>📖 Quick reference</b></a>
  &nbsp;·&nbsp;
  <a href="#-make-your-own-lesson-in-3-steps"><b>🚀 Get started</b></a>
  &nbsp;·&nbsp;
  <a href="#-from-a-youtube-video-to-a-lesson-with-two-prompts"><b>🤖 Video to lesson with AI</b></a>
</p>

---

## 🎬 See what a real lesson looks like

### 👉 [A House That Tells a Story](https://jeronimovis.github.io/lessonmark/lesson/)

*A 45-minute C1 listening lesson for architects and architectural engineers, built around a short house-tour video of Rob Mills's Murray River Residence.*

Open it and try it as a student would. In one page, learners:

- 💬 **warm up** with a quote about “less is more” and predict what the house will look like;
- 🔤 **pre-learn key words** like *holistic*, *cocooning* and *seek respite* in a matching task;
- ▶️ **watch three short clips** of the video, each one starting and stopping at exactly the right moment;
- ✏️ **check what they understood** with true/false items, a 9-gap listening text, short and long answers;
- 🧩 **work on real grammar from the video**: participle clauses and sentences like *“How we do that is…”*;
- 🗣️ **discuss** design choices from their own profession, with useful phrases and a class timer.

Every exercise has **Check**, **Show** and **Clear** buttons, a folded *“Need help?”* word bank, and answers in a key at the end. Transcripts stay folded until students have listened.

> ✍️ **The best part:** this whole lesson is one text file, [`lesson/data.md`](lesson/data.md). Open it to see how little it takes.

## ✨ Explore everything else

| | |
|---|---|
| 🧭 **[Feature guide](https://jeronimovis.github.io/lessonmark/)** | A lesson about *the incredible engineering of Venice* that shows **every feature in action**, each one with the exact text that produced it. |
| 📖 **[Quick reference](https://jeronimovis.github.io/lessonmark/LessonMark-reference.html)** | Every feature and its notation on one page, with a **Copy** button on each example. Handy to keep open while you write. |

## 👋 Why LessonMark?

LessonMark started in a real classroom: an English teacher preparing C1 listening lessons for architects and engineers, tired of rebuilding web pages by hand for every class.

The idea is simple: you write the lesson the way you'd write notes, in one text file, and LessonMark turns it into a polished page your students can use on any computer, tablet or phone. No coding, no apps, no accounts.

## 📝 This is all it takes

These lines from the house lesson…

```
## The land and the river | Individual · 5 minutes
> Watch Clip A. Are the statements true or false?

[play https://www.youtube.com/watch?v=p2hnrfN58H4 00:06 01:25 "Clip A – the land and the river"]

[tf] The client already had a site when he first came to the architect. [t]
[tf] Because of the slope, the house was designed to sit low and hidden in the land. [f]
```

…become a numbered exercise with a video player limited to that clip, two true/false questions that check themselves, and answers in the key.

## 🌟 What you can do with it

**Present your material**
- Audio and video clips that play **only the part you choose** (from a file or from YouTube)
- Reading texts with an elegant drop cap and numbered paragraphs
- Square images, side by side or beside the text; transparent PNGs blend right in
- Transcripts that stay folded until students have listened
- Vocabulary lists, fact boxes, useful-language boxes, role cards, timelines, quotes and a class timer

**Get students practising**
- Gap fills, word banks, dropdowns and word formation
- True or false, multiple choice, short and long answers
- Matching, ordering, error correction and key word transformations
- Odd one out, categorising and discussion prompts

**And the page takes care of the rest**
- ✅ **Check**, **Show** and **Clear** buttons on every exercise
- 💡 A folded *“Need help?”* word bank for students who are stuck
- 🔑 A complete answer key at the end
- 🌗 Light and dark mode, plus two styles: *Classic* (serif) and *Modern* (sans)
- 🖨️ A clean printout for paper worksheets
- 🔢 Automatic numbering and a menu to jump between exercises

## 🚀 Make your own lesson in 3 steps

1. **Copy this repository.** Click **Use this template** or **Fork** at the top of this page. Or just download `index.html`: it's the only file you really need.
2. **Write your lesson** in a file called `data.md`, next to `index.html`. Start from [the house lesson](lesson/data.md) and change it, or look things up in the [quick reference](https://jeronimovis.github.io/lessonmark/LessonMark-reference.html).
3. **Put it online.** In your copy, go to **Settings → Pages**, choose the `main` branch and click **Save**. A minute later your lesson is live.

Add your own `audio.mp3`, `video.mp4` and images to the same folder, and they'll play right away.

> 💡 **Several lessons?** Give each one its own folder with `index.html` and `data.md`, like [`lesson/`](lesson/). Or keep them together as `venice.md`, `bridges.md`… and open `index.html?lesson=venice.md`.

## 🤖 From a YouTube video to a lesson, with two prompts

The house lesson was made exactly this way. Each prompt starts with a short **Teacher's choices** box (video link, learners, level, class length…), so you only fill in the top and paste.

| Step | Prompt | What you get |
|------|--------|--------------|
| **1 · Gemini** watches the video | [`1-gemini-extract-video-script.txt`](prompts/1-gemini-extract-video-script.txt) | A word-for-word, timestamped transcript, suggested clips, key vocabulary with times, grammar examples and discussion ideas. |
| **2 · Claude** writes the lesson | [`2-claude-build-lessonmark-lesson.txt`](prompts/2-claude-build-lessonmark-lesson.txt) | A finished `data.md`, ready to drop next to `index.html`. |

For step 2, Claude works best with the **lessonmark-lesson** skill: download [`lessonmark-lesson-skill.zip`](prompts/lessonmark-lesson-skill.zip) and add it in Claude under **Customize → Skills → + → Create skill → Upload a skill**. No skill? Attach [`LessonMark-spec.md`](LessonMark-spec.md) instead: it describes the whole notation in plain text, so any AI assistant can write LessonMark lessons from a transcript or a text.

> 📋 The full steps are in [`prompts/README.txt`](prompts/README.txt).

## 📂 What's in here

| File | What it is |
|------|------------|
| [`lesson/`](lesson/) | The house-tour lesson: [try it live](https://jeronimovis.github.io/lessonmark/lesson/) or [read its `data.md`](lesson/data.md). |
| [`index.html`](index.html) | The LessonMark page. You never need to edit it. |
| [`data.md`](data.md) | The feature guide you see on the [main page](https://jeronimovis.github.io/lessonmark/). |
| [`LessonMark-reference.html`](https://jeronimovis.github.io/lessonmark/LessonMark-reference.html) | The quick reference page. |
| [`LessonMark-spec.md`](LessonMark-spec.md) | The notation in plain text, for writing lessons with AI. |
| [`prompts/`](prompts/) | The Gemini and Claude prompts, plus the lessonmark-lesson skill for Claude. |
| `image01.png` … `image04.png` | Illustrations used in the feature guide. |
| [`logo/`](logo/) | The LessonMark logo in light and dark versions. |

## ❓ Good to know

- **Opening the page from your computer?** Browsers don't let a page read files by itself. In Chrome or Edge, choose the lesson folder once and it opens automatically after that. In other browsers, pick the file or use the online version.
- **Audio and video files** aren't included in this repository, so the feature guide's local players show a short message. All YouTube clips play normally.
- **Something wrong in your lesson file?** A red box at the top of the page tells you which line to fix.

## 🙏 Credits

- The house lesson uses [*Architect Designs a Home That Disappears Into the Hill (House Tour)*](https://www.youtube.com/watch?v=p2hnrfN58H4) by The Local Project, featuring Rob Mills of Rob Mills Architects.
- The feature guide's clips come from the TED-Ed video [*The incredible engineering of Venice*](https://www.youtube.com/watch?v=uBwkMc1llmM) by Stephanie H. Smith.
- Fonts: [Newsreader](https://fonts.google.com/specimen/Newsreader) and [Manrope](https://fonts.google.com/specimen/Manrope), from Google Fonts.

---

<p align="center">
  Made with care for teachers and their students.<br>
  <a href="https://jeronimovis.github.io/lessonmark/lesson/">Try the house lesson</a> · <a href="https://jeronimovis.github.io/lessonmark/">See every feature</a> · Ideas or questions? <a href="https://github.com/jeronimovis/lessonmark/issues">Open an issue</a>, it's always welcome.
</p>
