# Decision Dock

## What this is
A tiny vanilla MVP that ranks a handful of options so teams can choose one without drifting into analysis paralysis.

## Problem
Small product and ops decisions often get stuck in vague discussion, with no quick way to compare impact, effort, and risk.

## Solution
Decision Dock turns a short list of options into a ranked matrix with a recommended pick, a quick win, and a lowest-risk choice.

## Theme
Brutalist-light / decision matrix

## Demo data
- 5 sample options load instantly on open.
- Each line can include impact, effort, risk, and a short note.
- The dashboard highlights the top pick, quickest win, and safest option.

## Run locally
```bash
python3 -m http.server 8080
```

## Deploy notes
Static HTML/CSS/JS MVP with no framework, sample data baked in, and a bold split-screen layout to keep the daily stream visually fresh.
