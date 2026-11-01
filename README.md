# MemoryLab — Digital Marketing + Information Visualization

A browser study app with two courses. The course picker in `index.html` opens Digital Marketing or Information Visualization.

## Courses

**Digital Marketing** (`digital-marketing.html`) preserves the existing course unchanged, covering **all 156 glossary terms across Lectures 1–8** from the supplied 42-page PDF. Every card retains the source definition, expanded explanation, example and PDF page reference.

**Information Visualization** (`information-visualization.html`) includes four original lecture PDFs (00–03), all 229 slide images, study concepts, quizzes, comparisons, browser speech playback, and three original past-exam PDFs with 12 supporting exam images. The three papers are shuffled variants of the same 14 questions. Suggested answers are not official marking keys; written answers require self-assessment. Lectures 04–11 are mentioned in the timetable but are not included in the supplied material.

The Information Visualization glossary includes original lecture visuals for 99 concepts, including chart types, maps, colour scales, visual encoding and navigation. Images appear in both the glossary list and full explanations, with descriptive captions, lecture/slide references and full-size links. Images load as needed while scrolling.

## Start
Live app: https://filippakarlsson.github.io/memorylab-digital-marketing/

Open `index.html` in any modern desktop or mobile browser. No install or account is required, and the app works offline (Google fonts are an optional online enhancement). Or run `python3 -m http.server 8000` in this folder and open http://localhost:8000.

## Digital Marketing study modes
- Study cards: read and review each term with explanations and examples.
- Active recall: attempt an answer with no cues before revealing the reference answer.
- Quick quiz: answer four-option randomized definition questions.
- Exam writing: type an answer and compare it to the full source text.
- Past exam practice: 18 multiple-choice, 6 short-answer and 4 longer essay questions, with saved written answers and self-review guidance.
- Complete library: search all 156 terms and read the expanded entries.
- Dashboard: see all eight lectures, mastery, coverage and performance.

Use Again, Hard or Got it to schedule future revision. Each course stores its progress separately in your browser using `localStorage`. Existing hosted Digital Marketing progress continues to use the same storage keys and site origin. Digital Marketing supports export/import of study progress to transfer devices or keep backups.

The hosted app stores progress separately from a downloaded copy because browser storage is specific to each site. The progress export/import feature transfers study progress; past-exam drafts use separate browser storage and are not included in that export. Download the repository to use the app offline; the hosted site does not install an offline cache.

## Publishing
GitHub Pages serves the root of the `main` branch. The web assets are unpacked from `MemoryLab_Two_Courses_with_Past_Exams.zip`; the archive itself is not needed. The previous `index.html` is preserved byte-for-byte as `digital-marketing.html`, and the existing supporting files remain available. Keep `slides/`, `exam-images/`, `source-lectures/`, the exam PDFs, and the JSON data beside the HTML pages when downloading or publishing. `.nojekyll` allows all assets to be served directly.

**Assessment note:** spaced-repetition stage and mastery are based on your ratings and quiz results; the app does not automatically grade free-text answers for semantic correctness.
