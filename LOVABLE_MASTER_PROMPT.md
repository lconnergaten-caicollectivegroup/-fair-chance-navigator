# Lovable Master Prompt

Paste everything below into Lovable as the initial build prompt.

---

Build a polished, responsive MVP web application called **Fair Chance Navigator™**, owned by **CAI Collective Group** and positioned within **Fair Chance Orbit™**.

## Product concept

This is a human-centered, two-sided workforce-readiness and matching platform for:

1. **Talent Orbit™:** justice-impacted people seeking employment, development, coaching, and verified resources.
2. **Employer Orbit™:** employers seeking prepared fair-chance talent, structured hiring support, faster hiring, retention support, and verified workforce reimbursement guidance.

The core journey is:

**INPUT → LEARN → ASSESS → DEVELOP → MATCH → REVIEW → CONNECT → HIRE → RETAIN**

Use a Gojiberry-inspired interaction model: each user begins with one simple input; the interface shows the AI structuring that input, learning the user’s needs, identifying high-fit matches, and preparing the next action. Do not copy Gojiberry branding or proprietary assets.

## Visual system

- Premium, vibrant, clean enterprise-technology design
- Deep navy, electric cobalt, teal, coral, and warm gold accents
- White/light-blue surfaces, rounded cards, soft shadows, subtle glass effects, orbit lines, and restrained gradients
- Modern sans-serif typography
- Mobile-first Talent Orbit™ and desktop-first Employer Orbit™
- Dynamic transitions with reduced-motion support
- WCAG 2.2 AA target
- No prison bars, handcuffs, mugshots, courts, or stereotypical justice imagery

## Landing page

Hero:

- Product: “FAIR CHANCE NAVIGATOR™”
- Tagline: “From barriers to a clear next step.”
- Supporting copy: “Prepare talent. Prepare employers. Create better matches.”
- Two primary buttons: “I’m seeking opportunity” and “I’m ready to hire.”

Show a visual two-sided flow:

**Talent Orbit™ + Employer Orbit™ → Mutual Match → Human Review → Speed Connect™ → Hire • Retain**

## Talent Orbit™

Create these screens:

1. **Talent welcome:** heading “What are your goals?” with three options: Upload résumé, Record video profile, Share goals manually.
2. **Consent:** separate toggles for résumé processing, EyePop AI video processing, employer visibility, and referrals. No prechecked boxes.
3. **Profile extraction review:** editable cards for skills, tools, credentials, work/project examples, preferences, and transcript clips. Include source timestamps, edit, hide, and delete.
4. **Readiness assessment:** career goals, transferable skills, communication, workplace readiness, confidence, and self-awareness. Frame results as strengths and development priorities—not pass/fail.
5. **My Path:** Today, Next 7 Days, and 30-Day Plan. Include résumé/profile development, storytelling, interview simulation, coaching, verified resources, and Speed Connect™ preparation.
6. **Opportunity matches:** explainable cards showing role, employer readiness status, required skills, verified alignment, development gaps, schedule/location, and “Interested / Not now.”
7. **Progress:** readiness milestones, introductions, interviews, onboarding, and retention support.

## Employer Orbit™

Create these screens:

1. **Employer welcome:** heading “Who are you ready to hire?” with one dominant input for website or job description.
2. **Requirement extraction review:** editable role purpose, essential skills, preferred skills, pay range, location, schedule, and support commitments.
3. **Employer readiness:** fair-chance practices, manager confidence, structured interviewing, onboarding, retention readiness, and leadership support.
4. **Partner Dashboard:** active roles, readiness actions, anonymized match cards, mutual-interest status, reimbursement reviews, interviews, hires, and retention milestones.
5. **Talent match:** job-relevant match reasons, verified skills, readiness milestones, development gaps, and participant consent state. Do not show protected or prohibited data.
6. **Video profile review:** participant-approved video player, captions/transcript, skill tags, and bookmarked timestamps. Display: “Candidate controlled,” “Human review required,” and “No emotion or protected-trait scoring.”
7. **Reimbursement:** prominent card saying “Up to 80% reimbursement” and “For eligible staff hours through participating justice-impacted workforce programs.” Include source program, jurisdiction, potential eligibility, last verified date, documents needed, and “Request eligibility review.” Display “Potential eligibility—verification required.”

## EyePop AI integration placeholder

Create a service abstraction and mock-data flow for participant-authorized video processing. The UI should show:

- Upload/record
- Processing status
- Transcript-linked skill extraction
- Participant review and correction
- Visibility approval
- Authorized employer viewing

Never infer or display emotion, personality, honesty, confidence, intelligence, disability, health, age, race, ethnicity, gender, socioeconomic status, criminal risk, or protected characteristics. Do not perform facial recognition, biometric matching, candidate scoring, or automated hiring decisions.

## Matching logic

Use mock explainable matching based on essential skills, transferable skills, credentials, participant interests, schedule/location, and verified readiness milestones. Display match reasons as text. Require talent interest, employer interest, and human review before Speed Connect™.

## Roles

- Talent
- Employer
- Coach/Navigator
- Administrator

Create role-aware navigation and demo accounts with mock data only.

## Core data objects

User, TalentProfile, VideoProfile, EmployerProfile, JobRole, ReadinessAssessment, DevelopmentPlan, Match, ConsentRecord, ReimbursementProgram, ReimbursementReview, Referral, Outcome, AuditEvent.

## Technical direction

- React + TypeScript
- Tailwind CSS
- shadcn/ui components
- Lucide icons
- Recharts only for meaningful outcome visualizations
- Supabase-ready architecture for auth, PostgreSQL, private storage, row-level security, and edge functions
- Keep integration secrets server-side
- Seed realistic but fictional demo data
- Responsive for mobile, tablet, and desktop

## Required states

Loading, empty, processing, needs correction, pending consent, pending human review, mutual interest, scheduled, declined, revoked, stale program data, and error recovery.

## Required trust features

- Consent center
- Privacy settings
- Download/correct/delete controls
- AI-output labels and sources
- Human-review status
- Audit timeline for authorized users
- Funding-source and verification dates

## Build order

1. Design system and landing page
2. Talent onboarding and My Path
3. Employer onboarding and Partner Dashboard
4. Explainable matching and mutual-interest flow
5. Video-profile mock integration
6. Reimbursement workflow
7. Governance, consent, and audit views
8. Accessibility and responsive QA

Deliver a functional front-end prototype with mock data and complete navigation. Do not claim that external integrations, funding eligibility, hiring decisions, or production security are active until connected and validated.

---
