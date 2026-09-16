# CSE R22 → 2030: A Curriculum Audit

Round 2 submission for HKAIVERSE — redesigning a B.Tech CSE (R22, JNTUH) degree for students graduating in 2030.

**Candidate:** Poojitha · **Branch:** B.Tech CSE · **Regulation:** R22 · **Target grad year:** 2030

## Read it here

- 🔗 **Live interactive report:** [add your published link here]
- 📄 **PDF version:** [`assets/CSE_R22_to_2030_Curriculum_Audit.pdf`](assets/CSE_R22_to_2030_Curriculum_Audit.pdf)

## What this is

Every core subject in the R22 CSE syllabus, labeled **KEEP / UPDATE / REDUCE / ADD** for a 2030 graduate — each label backed by one of: a 2026 job posting, an industry/tech-trend report, an AI capability test, or a conversation with a working grad. Not opinion-based.

## Method

1. Mapped the current degree (all 8 semesters) and diffed R22 against R25
2. Labeled all 10 core subjects with evidence
3. Checked the syllabus against 2026 field-reality (JetBrains 2026 Dev Ecosystem Survey, etc.)
4. Checked the syllabus against 3 real 2026 job postings
5. Ran an AI capability test on 6 subjects — where AI already does the work vs. where it doesn't
6. Interviewed a 2024 grad, now a Platform Engineer, on what the degree got wrong/right in practice
7. Proposed a 2030 redesign within a 20–25% credit-change cap
8. Self-critiqued (Section 7) and fact-checked one AI-generated claim in the original brief (Section 8) — found it false

## Repo structure

```
├── README.md
├── sections/
│   ├── 01-current-degree.md
│   ├── 02-whats-taught.md
│   ├── 03-subject-labels.md
│   ├── 04-2026-reality.md
│   ├── 05-vs-job-postings.md
│   ├── 06-2030-redesign.md
│   ├── 07-what-would-make-me-wrong.md
│   └── 08-ai-claim-checked.md
├── evidence/
│   ├── job-postings.md
│   ├── ai-capability-test.md
│   └── human-conversation.md
└── assets/
    └── CSE_R22_to_2030_Curriculum_Audit.pdf
```

## Key findings (short version)

- DevOps structure/credits are fine in R25 — the tooling is stale (Jenkins/manual kubectl vs. GitHub Actions/ArgoCD/Terraform).
- Computer Networks flipped from KEEP to UPDATE after a grad interview: labs still teach RIP in Packet Tracer against a real world of VPCs and edge networking.
- Git/version control is a double-sourced zero-coverage gap (job posting + grad's day-1 experience).
- Cloud Computing already exists as a professional elective — the fix is promoting it to core, not adding a new course.
- One claim in the original HKAIVERSE brief (a DevOps 4→1 credit cut) was checked against two primary sources and found false — see [Section 8](sections/08-ai-claim-checked.md).

Full detail in [`sections/`](sections/) and [`evidence/`](evidence/).
