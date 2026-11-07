# Speaking to Camera Dashboard

A 30-day interactive tracker for getting confident speaking to camera, based on Gabe Harris (@watch.gabe).

## Sources

- 30-day roadmap: https://www.instagram.com/p/DfaEkgzCp5P/ — "The Ultimate Beginner's Guide To Just F*cking Starting"
- B-roll in one day: https://www.instagram.com/p/DfI0cSvoBYL/ — "How To Film A Month's Worth of B-Roll in One Day"

## The plan

- **Week 1 — Getting Comfy:** daily 10-minute unscripted video journal, no posting. Watch it back, pick one thing to fix the next day (eye contact, filler words).
- **Week 2 — AI Interviews:** continue daily logs, 2x/week AI interrogations (dream customer, business, method, experiences), ending each session asking for your top 10 content ideas.
- **Week 3 — Filming:** continue AI interviews, 2x B-roll sequences/week (wide / medium / tight), 3x talking-head videos from AI topics.
- **Week 4 — Go Live:** post 3x/week, layer B-roll over talking-head footage, continue 2x AI convos, 1x batch recording, 1x B-roll sequence/week.

## Run locally

This is a single self-contained static file — no build step, no server needed.

```sh
# Open index.html in a browser, or serve it locally:
python3 -m http.server 8000
# then open http://localhost:8000
```

Progress (checked days, streak, idea bank, B-roll ticks) is saved in the browser's local storage.

## Deploy

Hosted on Vercel from this repo as a static site. `index.html` is the entry point.
