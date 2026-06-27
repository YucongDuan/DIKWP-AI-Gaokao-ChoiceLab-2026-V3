# DIKWP AI Gaokao ChoiceLab 2026 V3

A standalone, offline-first, open-source reference system for Chinese Gaokao candidates and parents choosing AI-related majors in 2026.

## Core workflow

Student profile → Province rule → Official data ledger → Hard qualification filter → AI major taxonomy → Future AI scenario analysis → Rank risk band → College-major explorer → Volunteer list builder → University charter verification → Family consensus → Four-year AI capability roadmap → Choice Passport.

## Quick start

Open `index.html` in a modern browser. No server, database, API key, account, or network is required.

Optional CLI:

```bash
python tools/run_ai_choice.py examples/sample_student.json data/programs_ai_official_template.csv --out outputs
```

## Real-use rule

The bundled program data are synthetic demonstrations. Before real志愿 use, replace them with the candidate province's 2026 official admission plan, university admission charters, and verified rank history.

## Boundaries

This system does not guarantee admission, submit志愿, store exam credentials, or replace provincial admission systems, 阳光高考, school charters, or human family decisions.
