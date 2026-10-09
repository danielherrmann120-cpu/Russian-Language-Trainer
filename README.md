# Граница — Russian Language Trainer

An interactive, single-file Russian language learning web app. No installation, no server, no account — open `index.html` in any browser and start learning. Progress, XP, streaks, and spaced-repetition review state are all saved locally via `localStorage`.

## Features

### 🏡 Home
A branching "skill tree" dashboard — a trunk node splits into **Practice** (Lessons, Flashcards, News) and **Learn & Reference** (Alphabet, Phrases, Vocabulary, Grammar, Tips) branches, each leading straight to that section.

### 📚 Lessons
Eight progressive lessons that unlock in sequence, laid out as a winding progression path (not a flat grid) with hearts, combo streaks, and an "Out of Hearts" retry state. Each lesson introduces vocabulary with learn cards, then tests it through five exercise types:

- **Multiple choice** — translate a word or phrase from four options
- **Fill in the blank** — complete a Russian sentence by selecting the missing word
- **Tap to build** — arrange shuffled word tiles to form a correct Russian sentence
- **Match pairs** — connect Russian words to their English meanings
- **Listen & choose** — hear a Russian word spoken aloud and identify its meaning

### 🗂️ Flashcards + 🔁 Spaced Repetition
Self-paced flashcard practice across multiple decks, plus a real spaced-repetition engine: a Leitner-box review queue pools all Words and Phrases, tracks each item's box/due date, and resurfaces it on an increasing interval (1 → 2 → 4 → 8 → 16 → 30 days) when you get it right, or resets it when you get it wrong. The deck picker shows a live "due today" count and seeds new items daily so the queue never runs dry.

### 🔤 Alphabet
All 33 Cyrillic letters with transliteration and pronunciation. Click a card to reveal how it sounds, or press 🔊 to hear it — first-time reveals earn XP.

### 💬 Phrases & 📚 Vocabulary
50+ phrases and 100+ words across more than a dozen categories (Greetings, Numbers, Family, Food, Weather, Transport, National Security, and more), each with Russian text, transliteration, and English translation.

### 📖 Grammar
- **Pronouns**, **Noun Gender**, **Sentences**, **Negation** — core reference topics.
- **Verb Conjugation** — the two conjugation patterns explained side by side, a 13-verb browser (regular Conjugation I/II plus irregulars), and a multiple-choice drill where wrong answers are other persons of the *same* verb, so you're specifically practicing the ending.
- **Cases** — all six Russian cases (Nominative through Prepositional) with their function and common prepositions, the accusative-animacy rule explained, a 7-noun declension browser spanning all genders/stem types, and the same ending-focused practice drill applied to case endings.

### 📰 News
Real (constructed) Russian headlines across Ukraine / Russia / Diplomacy / Regional categories, each collapsible with vocabulary callouts, audio, and a comprehension quiz. Includes an interactive schematic map of the region (click a pin to filter headlines by location) and a **📅 Daily** tab that deterministically rotates one headline per day — no network calls, fully offline.

### 💡 Tips
Six reference cards covering pronunciation, grammar essentials, alphabet tricks, learning strategies, formal vs. informal register, and common word patterns.

## Gamification

- **XP & Levels** — a level badge and XP progress bar live in the header on every tab, not just the Lessons hub.
- **Daily streak** — tracked across any completed lesson.
- **Daily goal** — a 20 XP/day target shown on the Lessons hub.
- **Achievements** — unlockable badges for lesson milestones, streaks, alphabet mastery, flashcard rounds, and news engagement.
- **Combos** — consecutive correct answers in a lesson build a combo multiplier bonus.

## Audio / Text-to-Speech

The app uses the browser's built-in **Web Speech API** to pronounce Russian words and phrases. This requires a Russian (`ru-RU`) voice installed on your system — if none is found, a banner lets you know, and every other feature still works normally.

| Browser | Russian TTS |
|---------|------------|
| Chrome | Supported |
| Edge | Supported |
| Firefox | Depends on OS voices |
| Safari | Supported on macOS/iOS |

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
- `localStorage` for progress, XP, streaks, achievements, and spaced-repetition state

## License

MIT — free to use, modify, and distribute.
