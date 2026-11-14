# PaperPilot — Research Reading Workspace PRD

## Vision
PaperPilot is a local-first research reading companion for students who need to turn dense papers into structured, traceable understanding. It organizes claims, evidence, limitations, and follow-up questions instead of generating ungrounded summaries.

## Problem
Students save papers but lose the reasoning behind what matters: the research question, dataset, method, evidence, limitations, and relevance to their own work. Notes become disconnected from sources and are difficult to compare.

## Target users
- AI, ML, and cybersecurity students
- Undergraduate researchers
- Journal-club participants and capstone teams

## MVP requirements
1. Create a reading record with citation metadata and tags.
2. Capture the research question, core claim, method, evidence, limitations, and personal relevance.
3. Maintain a claim–evidence ledger with confidence labels.
4. Generate a structured reading-progress score from completed fields—not paper quality.
5. Save a local library and reopen records.
6. Export a record as Markdown.
7. Provide responsible-reading prompts and a reproducibility checklist.
8. Keep all data in the browser.

## Non-goals
- Automatic PDF ingestion or hallucinated summaries
- Citation verification, plagiarism detection, or peer review
- Judging whether a paper is scientifically correct
- Replacing domain experts or primary-source reading

## Success criteria
- A user can create, save, reopen, and export a structured paper note.
- Every saved claim has an associated evidence note and confidence label.
- The interface makes incomplete critical-reading areas visible.
- No paper text or notes leave the device.

## Future work
- Consent-based PDF text extraction with page anchors
- Cross-paper comparison matrices
- DOI metadata lookup
- Citation graph visualization
- Team journal-club workspaces

