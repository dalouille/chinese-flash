# 汉字 Flash

A lightweight, mobile-friendly sentence browser for language learners. No accounts, no algorithms, no pressure — just random exposure to the language, one sentence at a time.

## What it is

Most language tools want you to *study*. This one doesn't. 汉字 Flash shows you a random sentence, lets you peek at the translation, and moves on. That's it. Think of it less like a flashcard app and more like flipping through a phrasebook with your eyes closed — you get a moment with the language without any obligation to remember it.

It currently supports Chinese, with sentences tagged by HSK level (1–3) so you can filter by difficulty. Each card shows the characters, pinyin, and English translation.

## How to use it

- **Tap the card** to reveal the translation
- **Swipe left/right** (or use the arrows) to move between sentences
- **Filter by HSK level** using the pills at the top
- **Toggle direction** between Chinese → English or English → Chinese

## What's coming

- **Personal tagging + Anki export** — mark sentences you want to actually study, then export them as a CSV to import into Anki
- **Load your own sentence list** — point the app at any CSV (e.g. a published Google Sheet) to use your own collection
- **Multi-language support** — the same low-stress browsing experience for other languages

## Sentence format

Sentences live in a simple CSV file:

```
zh,pinyin,english,hsk
你好,nǐ hǎo,Hello,1
```

Want to contribute sentences or build your own list? That's all you need.

## Philosophy

Spaced repetition is great. It's also a commitment. Sometimes you just want to spend two minutes with the language without opening a queue. That's the gap this tries to fill.
