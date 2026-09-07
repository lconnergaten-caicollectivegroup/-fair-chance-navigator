# User Flows

## Talent flow

`Choose Talent Orbit™ → Consent → Upload résumé / record video / share goals → Review extracted information → Complete readiness assessment → Activate development plan → Earn readiness status → Review explainable matches → Express interest → Human review → Mutual match → Speed Connect™ → Interview → Hire → Retention support`

## Employer flow

`Choose Employer Orbit™ → Organization verification → Enter website / job description → Review extracted requirements → Complete employer-readiness assessment → Activate development plan → Earn readiness status → Review anonymized talent matches → Request participant-approved video → Express interest → Review reimbursement pathway → Human review → Mutual match → Speed Connect™ → Interview → Hire → Onboarding and retention`

## Video-profile flow

`Explicit consent → Record/upload → EyePop processing job → Transcript and job-relevant metadata → Participant review/correction → Participant chooses visibility → Authorized employer review → Human notes → Participant may revoke access`

## Reimbursement flow

`Employer views program → Platform shows potential fit and source → Employer requests review → Workforce professional verifies eligibility → Documents collected outside or inside authorized workflow → Approval/denial recorded by responsible program → Hours and reimbursement milestones tracked → Audit trail retained`

## Match-state model

- Draft profile
- Readiness in progress
- Readiness verified
- Match suggested
- Talent interested
- Employer interested
- Human review pending
- Mutual match approved
- Speed Connect™ scheduled
- Interviewing
- Hired
- Retention support
- Closed / declined / withdrawn

## Exception flows

- **Consent revoked:** immediately stop future processing and remove employer visibility.
- **Incorrect extraction:** user edits or deletes the item; previous value remains only in protected audit history when legally justified.
- **Unsafe AI output:** hide output, route to human reviewer, and log incident.
- **Stale resource/funding data:** suppress recommendation until reverified.
- **No match:** show development actions and human support rather than a failure message.
