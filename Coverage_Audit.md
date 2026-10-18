# NICL Assistant Mains Quiz – Coverage Audit (18 Oct 2026)

External verification (IRDAI/RBI/government sites) was **not performed** (no web access in this build). Every answer is exactly as printed in your PDFs.

## Source-wise audit (PDFs containing MCQs)

| PDF | Pages | Original found | Imported | Duplicates (excluded) | Missing answer | Flagged to verify | Explanation: PDF / auto-matched note / answer-only | Generated |
|---|---|---|---|---|---|---|---|---|
| June_2026.pdf | 65 | 171 | 171 | 0 | 0 | 0 | 0 / 143 / 28 | 33 |
| July-2026-BFA.pdf | 34 | 200 | 200 | 4 | 0 | 0 | 0 / 163 / 37 | 9 |
| July-2026-Current-Affairs.pdf | 56 | 200 | 200 | 0 | 0 | 0 | 200 / 0 / 0 | 17 |
| August-Banking-and-Financial-Awareness.pdf | 43 | 200 | 200 | 0 | 0 | 1 | 0 / 112 / 88 | 2 |
| August-2026-Current-Affairs.pdf | 34 | 223 | 223 | 0 | 0 | 1 | 0 / 116 / 107 | 3 |
| September-2026-Banking-and-Financial-Awareness.pdf | 37 | 200 | 200 | 5 | 0 | 0 | 0 / 174 / 26 | 8 |
| September-2026-Current-Affairs.pdf | 31 | 250 | 250 | 0 | 0 | 0 | 0 / 218 / 32 | 11 |

**Totals:** 1444 original questions found and imported; 9 exact/near duplicates kept in the bank but excluded from quizzes (1435 unique original); 83 generated questions.

PDFs with no MCQs: `June-2026-Current-Affairs.pdf` (11 pages, notes only) and the one-liner sections of the other files; these were used only as the source for explanations and generated questions.

## Completeness checks
- Question numbering in each PDF runs 1..N with no gaps; extracted counts match (June 110+61, July CA 200, July BFA 200, Aug BFA 200, Aug CA booklet 223 with 223 key entries, Sept CA 250, Sept BFA 200).
- All 8 PDFs have a text layer; no unreadable pages. June answers were cross-checked against the printed answer key: 0 mismatches.
- June PDF prints Economy Q14–15 after Q16–19; handled.

## Duplicates (excluded, primary kept)
- JBF-165 duplicates JBF-133
- JBF-176 duplicates JBF-024
- JBF-177 duplicates JBF-027
- JBF-178 duplicates JBF-148
- SBF-035 duplicates SCA-012
- SBF-083 duplicates SCA-025
- SBF-153 duplicates SCA-154
- SBF-184 duplicates SCA-185
- SBF-187 duplicates SCA-186

## Items to verify
- **ABF-126 vs ACA-157**: PDFs disagree on who released *Reimagining Care* (Social Justice & Empowerment vs NITI Aayog).
- `August-2026-Current-Affairs.pdf` has metadata/headers saying *July 2026*; its MCQs are filed under August because of the filename.
- Some same-topic questions have different answers because they ask different things (11 pairs listed in audit.json); not errors.
- JBF-106 ("ISP base year") is very terse in the source.

## Limitations
- Explanations missing in the PDFs (1,244 questions) were auto-matched to the closest note in your PDFs; 'answer-only' ones had no match. They are labelled in the app.
- Generated questions are a first pass: automated fill-in-the-blank numeric facts with computed distractors, flagged 'Auto-generated'. Quality is uneven; treat as bonus practice.
- Section/topic tags (Current Affairs / Insurance / Banking-Financial-Economic) are keyword-assigned, so some borderline items may be mis-tagged.
