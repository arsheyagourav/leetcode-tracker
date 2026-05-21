# LeetCode Company Questions Tracker

A free, open alternative to LeetCode Premium's company question lists.

**Live site → [arsheyagourav.github.io/leetcode-tracker](https://arsheyagourav.github.io/leetcode-tracker/)**

---

## Why I built this

LeetCode Premium costs ~$160/year, and a big part of what you're paying for is access to company-tagged questions — seeing which problems Google, Meta, Amazon, etc. actually ask in interviews. That information shouldn't be locked behind a paywall when you're already stressed about job hunting.

I built this for myself first. I wanted a clean place to track which questions I've done, save the ones I want to revisit, and focus on the companies I'm actually interviewing at — without paying for a subscription or digging through spreadsheets.

If it helps other people prep too, that's a bonus.

## What it does

- Browse 663+ companies and their most frequently asked LeetCode questions
- Questions sorted by interview frequency, not just problem number
- Filter by difficulty, time period (last 30 days, 3 months, 6 months, all time)
- **Mark questions as done** — track your progress as you grind
- **Save questions and companies** — build your own shortlist to revisit
- Data pulls live from a community-maintained GitHub repo, so it stays current without any backend

## How it works

Everything is a single HTML file. No login, no backend, no tracking. Your favorites and completed questions are saved locally in your browser.

Question data comes from [snehasishroy/leetcode-companywise-interview-questions](https://github.com/snehasishroy/leetcode-companywise-interview-questions) — a community-maintained dataset. All credit to the contributors there.

## Running locally

Just open `index.html` in a browser. No build step, no dependencies.

```
git clone https://github.com/arsheyagourav/leetcode-tracker.git
cd leetcode-tracker
open index.html
```
