# 4D BIM Training Analytics Dashboard

Interactive, single-file dashboard I built to track participant performance in a Synchro Pro 4D BIM training programme delivered to a large contractor's engineering team on a supertall tower project.

> **Note:** This is an anonymised portfolio version. Client, project and participant names have been removed and replaced with codes. It is not the client deliverable.

## Business question

Training managers needed to answer, after every session:
- Who is keeping up, and who is falling behind?
- Which topics need a recap?
- Is attendance turning into actual learning (quiz completion)?

## What the dashboard does

- **KPI header:** participants, sessions, programme average, share of "Excellent" grades
- **Session averages:** score per session to spot weak modules
- **Grade distribution** across quiz takers
- **Group comparison:** two training groups, session by session
- **Leaderboard:** average, quiz count, attendance and grade per participant
- **Difficult questions:** questions with the lowest correct rate, flagged for review
- **Key findings:** written insights for the training manager (e.g. a group gap on schedule import, quiz non-submission despite attendance)
- **Excel export** of the underlying data

## Data

- 34 participants, 2 groups, 12 sessions
- Quiz scores per session and attendance cross-checked against Microsoft Teams logs
- Grades derived from averages (Excellent / Good / Average / Below Avg)

## Tech

- Plain HTML, CSS and JavaScript in one self-contained file
- Chart.js for charts, GSAP for scroll animations
- The original version also had an AI assistant for natural-language questions on the data. It is disabled here because a static site cannot hold an API key securely.

## Run

Open `index.html` in a browser, or view it on GitHub Pages.
