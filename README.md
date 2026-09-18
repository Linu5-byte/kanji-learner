# Japanese SRS Trainer

A single-page browser trainer for Japanese vocabulary CSVs.

Open the GitHub Pages site, load a CSV with the columns `Kanji`, `Reading`, `Romaji`, `Meaning`, and `KanjiMeaning`, then study from any browser. Progress is stored locally in that browser.

Three pages, same CSV format and progress store (per filename), so switching between them doesn't reset your deck:
- `index.html` — the original page. Type the reading, then press Enter.
- `typing.html` — same typing mode, with the deck stats moved below the study card.
- `mcq.html` — pick the reading from generated multiple-choice options, with a Yes/No "do you know this?" gate before each question.
