<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="logo/dropcap-classic-dark.svg">
    <img src="logo/dropcap-classic-light.svg" alt="LessonMark" width="420">
  </picture>
</p>

<p align="center">
  <b>Write a lesson in a simple text file. Get a beautiful, interactive lesson page.</b><br>
  Listening clips, reading texts, images and self-checking exercises, from plain text.
</p>

<p align="center">
  <a href="https://jeronimovis.github.io/lessonmark/"><b>✨ See it live</b></a>
  &nbsp;·&nbsp;
  <a href="https://jeronimovis.github.io/lessonmark/LessonMark-reference.html"><b>📖 Quick reference</b></a>
  &nbsp;·&nbsp;
  <a href="#-make-your-first-lesson-in-3-steps"><b>🚀 Get started</b></a>
</p>

---

## 👋 Welcome

**LessonMark** started in a real classroom: an English teacher preparing C1 listening lessons for architects and engineers, tired of rebuilding web pages by hand for every class.

So here's the idea: you write the lesson the way you'd write notes, in one text file, and LessonMark turns it into a polished page your students can use on any computer, tablet or phone. No coding, no apps, no accounts.

## ✨ Take a look

The best way to understand LessonMark is to open it:

### 👉 [Open the live guide](https://jeronimovis.github.io/lessonmark/)

A complete lesson about *the incredible engineering of Venice* that shows **every feature in action**. Each section has a short explanation and the exact text that produced it, so you can copy what you like.

### 📖 [Open the quick reference](https://jeronimovis.github.io/lessonmark/LessonMark-reference.html)

Every feature and its notation on one page, with a **Copy** button on each example. Handy to keep open while you write.

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
- 💡 A folded *"Need help?"* word bank for students who are stuck
- 🔑 A complete answer key at the end
- 🌗 Light and dark mode, plus two styles: *Classic* (serif) and *Modern* (sans)
- 🖨️ A clean printout for paper worksheets
- 🔢 Automatic numbering and a menu to jump between exercises

## 📝 This is all it takes

A few lines in your lesson file…

```
## Listen and fill the gaps | Individual · 10 minutes
> Listen to the clip and complete the text.

[play audio.mp3 00:47 01:50 "Clip A"]

The settlers drove wooden {piles} into the {mud|ground}.

[tf] The piles were made of stone. [f]
```

…become a numbered exercise with an audio player, two gaps that check themselves, a true-or-false question, a help word bank and answers in the key.

## 🚀 Make your first lesson in 3 steps

1. **Copy this repository.** Click **Use this template** or **Fork** at the top of this page. Or just download `index.html`, it's the only file you really need.
2. **Write your lesson** in a file called `data.md`, next to `index.html`. Start from the guide's `data.md` and change it, or look things up in the [quick reference](https://jeronimovis.github.io/lessonmark/LessonMark-reference.html).
3. **Put it online.** In your copy, go to **Settings → Pages**, choose the `main` branch and click **Save**. A minute later your lesson is live.

Add your own `audio.mp3`, `video.mp4` and images to the same folder, and they'll play right away.

> 💡 **Several lessons?** Name them `venice.md`, `bridges.md`… and open `index.html?lesson=venice.md`.

## 🤖 Let an AI assistant help

[`LessonMark-spec.md`](LessonMark-spec.md) describes the whole notation in plain text. Give it to an AI assistant together with a transcript or a text, and ask it to write a lesson. You'll get a `data.md` ready to drop in.

## 📂 What's in here

| File | What it is |
|------|------------|
| [`index.html`](index.html) | The LessonMark page. You never need to edit it. |
| [`data.md`](data.md) | The guide lesson you see in the [live demo](https://jeronimovis.github.io/lessonmark/). |
| [`LessonMark-reference.html`](https://jeronimovis.github.io/lessonmark/LessonMark-reference.html) | The quick reference page. |
| [`LessonMark-spec.md`](LessonMark-spec.md) | The notation in plain text, for writing lessons with AI. |
| `image01.png` … `image04.png` | Illustrations used in the guide. |
| [`logo/`](logo/) | The LessonMark logo in light and dark versions. |

## ❓ Good to know

- **Opening the page from your computer?** Browsers don't let a page read files by itself. In Chrome or Edge, choose the lesson folder once and it opens automatically after that. In other browsers, pick the file or use the online version.
- **Audio and video files** aren't included in this repository, so the guide's local players show a short message. Its YouTube clips play normally.
- **Something wrong in your lesson file?** A red box at the top of the page tells you which line to fix.

## 🙏 Credits

- The guide's media clips are based on the TED-Ed video [*The incredible engineering of Venice*](https://www.youtube.com/watch?v=uBwkMc1llmM) by Stephanie H. Smith.
- Fonts: [Newsreader](https://fonts.google.com/specimen/Newsreader) and [Manrope](https://fonts.google.com/specimen/Manrope), from Google Fonts.

---

<p align="center">
  Made with care for teachers and their students.<br>
  <a href="https://jeronimovis.github.io/lessonmark/">Try LessonMark</a> · Ideas or questions? <a href="https://github.com/jeronimovis/lessonmark/issues">Open an issue</a>, it's always welcome.
</p>
