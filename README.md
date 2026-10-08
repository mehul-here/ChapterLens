# ChapterLens
A free, browser-only readability checker for authors.

## What it does
- Flesch Reading Ease score
- Word/sentence/syllable counts
- Average sentence length
- Five hardest sentences
- In-place highlighting
- No backend and no text upload

## Deploy
This is a static HTML/CSS/JS site and can be hosted on GitHub Pages. GitHub Pages publishes HTML, CSS and JavaScript directly from a repository.

## AI tools used
ChatGPT (GPT-5.6 Luna) was used to design and generate the interface and client-side logic.

## Known limitation / AI mistake
The initial implementation relied on a simple English syllable heuristic. That can miscount irregular words (for example, “queue” or “beautiful”), which can distort the Flesch score. A production version should use a tested dictionary/phoneme-based syllabifier and compare results against known readability benchmarks.
