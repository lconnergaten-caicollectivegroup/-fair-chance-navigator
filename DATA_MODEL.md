# Conceptual Data Model

## Core entities

### User

- id
- role: talent | employer | coach | admin | evaluator
- authentication metadata
- consent status
- accessibility preferences
- created_at / updated_at

### TalentProfile

- user_id
- display name / protected identity fields
- goals
- verified skills
- transferable skills
- credentials
- preferences
- readiness milestones
- support preferences
- visibility controls

### VideoProfile

- talent_profile_id
- storage reference
- consent version
- transcript
- participant-approved skill tags
- approved clips/timestamps
- visibility status
- processing status
- deletion status

### EmployerProfile

- organization_id
- website
- locations
- fair-chance commitments
- readiness milestones
- authorized reviewers
- onboarding and retention supports

### JobRole

- employer_profile_id
- title
- purpose
- essential skills
- preferred skills
- pay range
- location / schedule
- accessibility/support details
- source and verification date

### Match

- talent_profile_id
- job_role_id
- job-relevant reasons
- gaps / development actions
- talent interest
- employer interest
- human-review state
- status timeline

### ReimbursementProgram

- provider
- jurisdiction
- description
- maximum reimbursement percentage
- eligible hours/costs
- eligibility rules
- documentation requirements
- source URL/reference
- last_verified_at
- expiration date

### ReimbursementReview

- employer_profile_id
- talent_profile_id
- job_role_id
- reimbursement_program_id
- potential-fit status
- authorized reviewer
- decision source
- verified amount/percentage
- milestones

### AuditEvent

- actor
- action
- entity
- timestamp
- model/prompt/version where applicable
- human reviewer
- correction/deletion status

## Data-separation rule

Protected or sensitive participant data must be logically separated from employer-visible job-matching data. Employers receive only participant-authorized, job-relevant content.
