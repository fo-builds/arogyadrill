# ArogyaDrill

**Adaptive micro-learning for frontline health workers.**

ArogyaDrill is an offline-first web app that trains ASHA workers, ANMs, nursing
students and primary-care volunteers on the life-saving protocols they use every
day: maternal and newborn care, immunization, nutrition and anemia, communicable
diseases, danger signs and emergencies, NCD screening, and infection prevention.

## Why

Frontline health workers carry enormous responsibility with the least training
time. Cramming a 200-page manual does not survive a busy week. ArogyaDrill turns
the highest-stakes knowledge into 60-second drills that:

- **Schedule themselves.** An SM-2-inspired spaced-repetition engine grows the
  review interval for every answer you get right and resets weak questions to
  reappear in 10 minutes, so study time goes where memory actually fails.
- **Target weak spots.** Today's queue pulls due reviews first, then feeds new
  questions from your weakest module.
- **Work offline.** One HTML file, no backend, no account, no network calls.
  Progress is stored only on the device. It loads and runs on a low-end phone
  with no connectivity, which is where most of the audience works.
- **Teach the failure, not the score.** Every answer, right or wrong, shows a
  one-line clinical rationale aligned with WHO and India's MoHFW/NHM guidance
  (IMNCI, NTEP, Anemia Mukt Bharat, Universal Immunization Programme).

## Features

- 66 exam-grade questions across 7 modules, each with a sourced rationale
- Hindi interface toggle, plus Hindi content for the emergency and danger-sign
  module
- Daily goal, streaks, mistake log with one-tap re-drill
- Per-topic mastery rings based on retention interval, not raw attempts
- A 60-second soft timer per question (advisory, never enforced)

## Run it

No build step. Open `index.html` in any browser, or serve it with any static
host. GitHub Pages deployment:

```bash
# the app is a single static file; host the repo root
```

## Disclaimer

ArogyaDrill is an educational drill tool. It does not diagnose, prescribe or
replace clinical judgment. Content is aligned with WHO and MoHFW/NHM guidance
but protocols change; always follow your facility's current protocol and refer
per local SOPs.

## License

MIT. See [LICENSE](LICENSE).

## Try it

- **Live demo:** https://arogyadrill.netlify.app (no install, no account, works offline after first load)
- **Single file:** open `index.html` in any browser
- **60-second demo video:** `ArogyaDrill_Demo.mp4`

Built as a hackathon project (ArogyaDrill, Devpost: https://devpost.com/software/arogyadrill).
