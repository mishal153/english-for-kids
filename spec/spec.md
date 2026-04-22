# Execution Plan: Lesson Workbooks

## Goal
Generate printable Markdown lesson workbook files per the spec in CLAUDE.md. Each file is a standalone workbook page for a 13-year-old Hindi-speaking beginner, printed and filled in with pencil. For each worksheet, also create an answer sheet containing the correct answers.

## File Naming
`type-lesson-NN-short-topic-slug.md`, e.g. `worksheet-lesson-01-alphabet-uppercase.md`
Answer sheets follow the same pattern: `answers-lesson-NN-short-topic-slug.md`

## Per-file Structure
Every lesson file follows this template:

```
# Lesson NN — Topic Name
## विषय: Hindi topic name

---

## Concept
[Brief explanation of the topic with examples. Include Hindi translations.]

---

[2–3 exercise blocks chosen from the formats below, appropriate to the topic]

---
```

Leave 2–3 blank lines after every answer blank for writing space. Always include Hindi translation for every English word or phrase introduced.

## Exercise Formats

- **Tracing**: dotted letters or words for the student to trace over
- **Matching**: two columns connected by drawing lines
- **Fill blank**: sentence with a `___________` gap to write in

## Series 1: Foundations

| Topic | Primary exercise types |
|-------|------------------------|
| Alphabet — uppercase, lowercase, tracing | Tracing |
| Numbers, days, months | Matching + Fill blank |
| Nouns — body, home, food, animals | Matching + Fill blank |
| Greetings and introductions | Fill blank + Matching |
| Basic verbs — is, am, are, has, have | Fill blank |
| Colors, shapes, sizes | Matching + Fill blank |
| Simple sentences — subject + verb + object | Fill blank |

## Series 2: Grammar for Reading

| Topic | Primary exercise types |
|-------|------------------------|
| Articles — a, an, the | Fill blank |
| This / that / these / those | Fill blank + Matching |
| Question words — what, where, who, when, how, why | Fill blank + Matching |
| Present tense — I eat, she runs, they play | Fill blank |
| Past tense — was, were, went, did | Fill blank |
| Future tense — will, going to | Fill blank |
| Prepositions — in, on, at, from, with, by | Fill blank + Matching |
| Connectors — and, but, because, so, then | Fill blank |
| Web vocabulary — click, search, home, login, buy, share | Matching + Fill blank |
| Reading practice — real-style web sentences | Fill blank |

## Verification
- Confirm blank lines give adequate writing space when printed