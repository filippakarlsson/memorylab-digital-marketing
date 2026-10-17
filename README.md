# MemoryLab — Digital Marketing Mastery

An offline-capable browser study app covering **all 156 glossary terms across Lectures 1–8** from the supplied 42-page PDF. Every card retains the source definition, expanded explanation, example and PDF page reference.

## Start
Live app: https://filippakarlsson.github.io/memorylab-digital-marketing/

Open `index.html` in any modern desktop or mobile browser. No install or account is required, and the app works offline (Google fonts are an optional online enhancement). Or run `python3 -m http.server 8000` in this folder and open http://localhost:8000.

## Study modes
- Study cards: read and review each term with explanations and examples.
- Active recall: attempt an answer with no cues before revealing the reference answer.
- Quick quiz: answer four-option randomized definition questions.
- Exam writing: type an answer and compare it to the full source text.
- Past exam practice: 18 multiple-choice, 6 short-answer and 4 longer essay questions, with saved written answers and self-review guidance.
- Complete library: search all 156 terms and read the expanded entries.
- Dashboard: see all eight lectures, mastery, coverage and performance.

Use Again, Hard or Got it to schedule future revision. Progress is stored in your browser using `localStorage`. Export/import progress to transfer devices or keep backups.

The hosted app stores progress separately from a downloaded copy because browser storage is specific to each site. The progress export/import feature transfers study progress; past-exam drafts use separate browser storage and are not included in that export. Download the repository to use the app offline; the hosted site does not install an offline cache.

## Publishing
GitHub Pages serves the root of the `main` branch. The original app files from `MemoryLab_Updated.zip` are preserved unchanged; only this README and `.nojekyll` are added or updated for hosting.

**Assessment note:** spaced-repetition stage and mastery are based on your ratings and quiz results; the app does not automatically grade free-text answers for semantic correctness.
