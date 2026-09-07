# Integration Specifications

## EyePop AI — proposed video intelligence integration

EyePop AI can provide customizable visual-intelligence processing for image/video inputs and structured outputs. In this MVP, the integration is limited to participant-authorized, job-relevant video-profile organization.

### Suggested sequence

1. Obtain explicit, versioned consent.
2. Store the video in a protected bucket.
3. Create an EyePop processing job with a narrow prompt/configuration.
4. Request transcript-linked, job-relevant structured information only.
5. Store processing status and returned timestamps/metadata.
6. Present all results to the participant for correction and visibility selection.
7. Publish only participant-approved fields/clips to authorized employers.
8. Log access and allow revocation/deletion.

### Required guardrail prompt

“Identify only explicit, job-relevant statements made by the participant, such as named skills, tools, credentials, work examples, and stated job interests. Return the source timestamp for each item. Do not infer emotion, personality, honesty, confidence, intelligence, disability, health, age, race, ethnicity, gender, socioeconomic status, criminal risk, or any protected or sensitive characteristic. Do not score or recommend hiring. If the participant does not explicitly state an item, return unknown.”

## Supabase

- Auth with role-aware onboarding
- PostgreSQL tables based on DATA_MODEL.md
- Row-level security by role and consent state
- Private storage for résumés and videos
- Signed, short-lived access for authorized review
- Audit events for AI generation, corrections, employer access, consent, and deletion
- Edge functions for integration calls; never expose secret keys in the client

## Reimbursement program data

- Begin with administrator-managed records.
- Require source, jurisdiction, verification owner, and last-verified date.
- Suppress expired or unverified programs.
- Present only potential fit until an authorized program representative confirms eligibility.

## Matching service

- Start with deterministic, explainable rules.
- Store every match reason and source field.
- Require mutual interest.
- Require human review before an introduction.
- Monitor match distribution and false positives across cohorts.
