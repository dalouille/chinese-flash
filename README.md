# 汉字 Flash

A minimal, no-tracking Chinese flashcard app for HSK 1–3 learners. Open it in your phone browser — no install, no account, no ads.

🔗 **Live app:** `https://YOUR-USERNAME.github.io/chinese-flash`

---

## Features

- Random sentence from `sentences.csv`
- Two card directions: **Chinese → English** or **English → Chinese**
- Filter by **HSK level** (1, 2, 3 or all)
- Direction toggle: **Random**, **中 → EN**, or **EN → 中**
- HSK tag on every card
- No scoring, no spaced repetition, no pressure

---

## Adding sentences

Edit `sentences.csv` — it has four columns:

```
zh,pinyin,english,hsk
我很好。,wǒ hěn hǎo,I'm doing well.,1
我喜欢看电影。,wǒ xǐ huān kàn diàn yǐng,I like watching movies.,2
```

| Column | Description |
|--------|-------------|
| `zh` | Chinese sentence |
| `pinyin` | Space-separated pinyin with tone marks |
| `english` | English translation |
| `hsk` | HSK level of the hardest word in the sentence (1, 2 or 3) |

You can edit this file directly on GitHub (click the file → pencil icon). No coding needed.

---

## Setup (one time, ~10 minutes)

1. [Create a free GitHub account](https://github.com/join) if you don't have one
2. Create a new **public** repository called `chinese-flash`
3. Upload `index.html` and `sentences.csv`
4. Go to **Settings → Pages → Source → Deploy from branch → main → / (root) → Save**
5. Wait ~1 minute, then visit `https://YOUR-USERNAME.github.io/chinese-flash`
6. On your phone: open that URL → Share → **Add to Home Screen**

---

## Contributing

Pull requests welcome!
- Add more sentences to `sentences.csv`
- Fix pinyin or translation errors
- Add new HSK levels

---

## License

MIT — do whatever you want with it.
