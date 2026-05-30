[README.md](https://github.com/user-attachments/files/28423558/README.md)
# Russian Language Basics

An interactive, single-file Russian language learning web app. No installation, no server, no account — open `index.html` in any browser and start learning.

## Features

### Lessons
Eight progressive lessons that unlock in sequence. Each lesson introduces new vocabulary with learn cards, then tests understanding through four exercise types:

- **Multiple choice** — translate a word or phrase from four options
- **Fill in the blank** — complete a Russian sentence by selecting the missing word
- **Tap to build** — arrange shuffled word tiles to form a correct Russian sentence
- **Match pairs** — connect Russian words to their English meanings
- **Listen & choose** — hear a Russian word spoken aloud and identify its meaning

Progress and XP are saved automatically via `localStorage`.

### Alphabet
All 33 Cyrillic letters with transliteration and pronunciation guide. Click any card to reveal how the letter sounds, or press the speaker button to hear it.

### Phrases
40+ common phrases across six categories — Greetings, Farewells, Polite Expressions, Getting Around, Questions, and Emergencies — each with Russian text, transliteration, and English translation.

### Vocabulary
80+ words across six categories — Numbers, Colors, Family, Food & Drink, Days & Time, and Common Verbs.

### Flashcards
Self-paced flashcard practice with five deck options. Flip each card, mark whether you knew it, and track your score across the round.

### Tips
Six reference cards covering pronunciation, grammar essentials, alphabet tricks, learning strategies, formal vs. informal register, and common word patterns.

## Lessons Overview

| # | Title | Topic |
|---|-------|-------|
| 1 | Essential Words | да, нет, привет, спасибо, пожалуйста |
| 2 | Greetings | Formal/informal hellos, introductions |
| 3 | Numbers 1–5 | Один, два, три, четыре, пять |
| 4 | Numbers 6–10 | Шесть, семь, восемь, девять, десять |
| 5 | Colors | Красный, синий, зелёный and more |
| 6 | Family | Мама, папа, брат, сестра and more |
| 7 | Food & Drink | Вода, чай, кофе, хлеб and more |
| 8 | Asking Questions | Что, кто, где, когда, почему, как |

## Audio / Text-to-Speech

The app uses the browser's built-in **Web Speech API** to pronounce Russian words and phrases. This requires a Russian (`ru-RU`) voice to be installed on your system.

| Browser | Russian TTS |
|---------|------------|
| Chrome | Supported |
| Edge | Supported |
| Firefox | Depends on OS voices |
| Safari | Supported on macOS/iOS |

If no Russian voice is available, all other features still work normally.

## Usage

1. Download or clone this repository
2. Open `index.html` in any modern browser
3. No internet connection required after the file is on your device

```
file:///C:/Users/YourName/path-to-folder/index.html
```

## Tech Stack

- Plain HTML, CSS, and JavaScript — zero dependencies
- Web Speech API for audio pronunciation
- `localStorage` for lesson progress persistence

## License

MIT — free to use, modify, and distribute.
