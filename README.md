# SAT Mock Exams

A collection of hardest-level SAT mock exams for Reading & Writing and Math, built as single-file HTML apps with answer keys, explanations, timers, and print support.

## Live Demo

Access the mock exam hub here:

👉 **[View SAT Mock Exams](https://flynntaggart26.github.io/SAT-mock/SAT%20mock/index.html)**

## Available Mocks

| Mock | Questions | Time | Sections | Link |
|------|-----------|------|----------|------|
| Mock 1 | 37 (15 R&W + 22 Math) | ~99 min | Reading & Writing, Math | [Take Mock 1](SAT%20mock/mock1.html) |

## Features

- **Digital SAT format** — timed sections mirroring the real exam (32 min R&W, 35 min Math)
- **Hardest-level questions** — advanced Reading & Writing passage analysis and challenging Math problems
- **Multiple-choice & grid-in** — A–D choices plus student-produced responses for Math
- **Instant feedback** — correct/incorrect indicators with the correct answer shown
- **Detailed explanations** — every question includes a step-by-step solution
- **Estimated scoring** — 400–1600 total score with percentile estimate
- **Print-ready** — clean print stylesheets for answer keys and explanations
- **No setup required** — open any `.html` file in a browser and start

## File Structure

```
SAT-mock/
├── README.md
└── SAT mock/
    ├── index.html          # Landing page / mock selection hub
    └── mock1.html          # First full SAT mock exam
```

## How to Use

1. Click the link above or open `SAT mock/index.html` in your browser.
2. Select a mock exam card to start.
3. Answer questions section by section with an on-screen timer.
4. When finished, view your estimated score and review the full answer key with explanations.
5. Use the **Print** button to print the answer key for offline study.

## How to Add a New Mock

1. Create a new file, e.g., `mock2.html`, inside `SAT mock/`.
2. Copy the structure from `mock1.html` and update the questions, answers, and explanations.
3. Add a new card to `SAT mock/index.html` linking to your new file:

```html
<a href="mock2.html" class="mock-card">
  <span class="tag">Mock 2 • Available</span>
  <h2>SAT Mock Exam #2</h2>
  <p>Description of the mock...</p>
  <div class="mock-meta">
    <span><strong>37 Questions</strong></span>
    <span><strong>~99 min</strong></span>
  </div>
  <span class="arrow">→</span>
</a>
```

## License

MIT License — free to use for personal SAT practice.