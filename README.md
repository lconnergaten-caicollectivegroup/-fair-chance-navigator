# Fair Chance Navigator™

![Fair Chance Navigator product cover](public/fair-chance-navigator-cover.jpg)

Fair Chance Navigator™ is a human-centered, two-sided workforce platform from CAI Collective Group. It helps justice-impacted talent become opportunity-ready while helping employers become fair-chance-ready, then creates consent-based matches that can move through Speed Connect™ to interview, hire, and retention.

## MVP promise

One simple starting input for each user:

- Talent uploads a résumé or records a video profile.
- Employers enter a website or job description.

The platform structures the information, builds readiness profiles, identifies high-fit matches, prepares both sides, routes consequential decisions to humans, and tracks outcomes.

## Core product model

`INPUT → LEARN → ASSESS → DEVELOP → MATCH → REVIEW → CONNECT → HIRE → RETAIN`

The experience contains two coordinated journeys:

- **Talent Orbit™:** assessment, development, certification, matching, interview preparation, and progress tracking.
- **Employer Orbit™:** readiness assessment, hiring-practice development, matching, reimbursement guidance, onboarding, and retention support.

## Start here

1. Read [docs/PRD.md](docs/PRD.md).
2. Review [docs/UX_SPEC.md](docs/UX_SPEC.md) and [docs/USER_FLOWS.md](docs/USER_FLOWS.md).
3. Paste [docs/LOVABLE_MASTER_PROMPT.md](docs/LOVABLE_MASTER_PROMPT.md) into Lovable.
4. Use [docs/DEVPOST_SUBMISSION.md](docs/DEVPOST_SUBMISSION.md) for the hackathon entry.
5. Treat [docs/RESPONSIBLE_AI.md](docs/RESPONSIBLE_AI.md) as required—not optional polish.

For a no-code build, create a new Lovable project, paste the master prompt, then upload the remaining files as project knowledge. Ask Lovable to implement the Talent Orbit™ and Employer Orbit™ dashboards as clickable, responsive flows using the included sample states.

## Proposed integrations

- **EyePop AI:** candidate-controlled video ingestion and customizable visual-intelligence processing that returns structured output. The MVP must not infer emotion, personality, criminal risk, demographic traits, disability, or protected characteristics.
- **Workforce reimbursement programs:** display partner-supplied eligibility rules and potential reimbursement of up to 80% for eligible staff hours. This is guidance, not a funding guarantee.
- **Supabase:** authentication, database, storage, row-level security, and audit events.
- **Lovable:** initial React/TypeScript user-interface build.

## Repository status

This package is a product and UX specification repository for rapid prototyping. It does not contain a production hiring-decision system.

## Ownership

Copyright © 2026 CAI Collective Group. Fair Chance Navigator™, Fair Chance Orbit™, Talent Orbit™, Employer Orbit™, Speed Connect™, Fair Chance Career Ready™, and Fair Chance Employer Ready™ are proprietary product and program names.
