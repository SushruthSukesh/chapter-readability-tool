# Chapter Readability Checker

Paste a chapter and get Flesch Reading Ease, Flesch-Kincaid grade level, word and sentence counts, and the five hardest sentences, highlighted in context. Runs entirely in the browser: no backend, no dependencies, no API keys.

## Run locally
Open `index.html` in a browser.

## Known limitation
Syllables are counted with a rule-based heuristic, so names, abbreviations and irregular words can be miscounted. A production version would use a pronunciation dictionary (e.g. CMUdict).
