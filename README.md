# Ku Kids Daily Lessons

Daily Usborne-style worksheets for Kid B, Kid C, and Kid A — auto-built from the curriculum markdown and published every weekday at ~7:30am HKT.

- **Live:** https://djayku.github.io/kids-lessons
- **Source builder:** `../build_usborne.py` (in the OpenClaw workspace)
- **Curriculum source:** `../*-curriculum-week*.md` (OpenClaw workspace)
- **Cron job:** Publishes at 7:30am HKT, Mon–Fri

## Structure

```
kids-lessons/
├── index.html              # Today's landing page (3 cards)
├── kid a/2026-08-10.html  # Kid A's lesson for Aug 10
├── kid c/2026-08-10.html
└── kid b/2026-08-10.html
```

Each day's page is one file per kid. Older days stay archived.
