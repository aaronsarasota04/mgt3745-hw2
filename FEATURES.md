# FEATURES.md

**Name: Aaron Rahim*
**Date: 09/10/2026**
**Assignment:** HW2, MGT 3745 O

---

## Kano-Classified Feature List
`15 pts`

> At least six candidate features. Classify each as Must-be, Performance, Attractive,
> Indifferent, or Reverse, with a one-line reason drawn from your research.
> An honest "Indifferent" is worth more than a flattering "Attractive."

**Classification date:**

| # | Feature | Kano class | Reason from research |
|---|---------|-----------|----------------------|
| 1 |         |           |                      |
| 2 |         |           |                      |
| 3 |         |           |                      |
| 4 |         |           |                      |
| 5 |         |           |                      |
| 6 |         |           |                      |

---

## 1. Context
`part of Specification Quality, 30 pts total`

The primary user is a senior Computer Science student at Georgia Tech who is actively pursuing software engineering or data engineering roles across the United States. They are open to relocation anywhere in the country and expect to graduate in December 2026, creating a narrow window to assess opportunities, decide which applications are worth submitting, and prioritize roles that align with their background, goals, and timing. In this context, the user wants a practical way to evaluate whether a role is worth pursuing even when the posted requirements are only a partial match, while also discovering openings that may not appear on major job boards.

---

## 2. Users

This feature is designed for early-career technical job seekers who are navigating competitive hiring pipelines and making strategic decisions about where to apply. It is informed by the profiles in [USERS.md](USERS.md), especially the candidate who relied on portfolio work and network connections instead of traditional internship experience, and the recruiter who evaluates whether a candidate should advance even when they do not match every listed requirement exactly.

---

## 3. Scope

**This does:**
- Help a senior Computer Science student evaluate whether a software or data engineering role is worth pursuing even when the posted requirements are only a partial match.
- Identify job opportunities through multiple sources beyond major job boards, including company career pages, alumni and recruiter connections, and other less visible channels.
- Support strategic application decisions by helping the user weigh fit, timing, and evidence such as projects, relevant experience, and networking rather than rigidly treating job descriptions as checklists.

**This deliberately does not do:**
- Guarantee an interview, offer, or job placement simply because a user follows the suggested strategies.
- Replace the user’s judgment, portfolio work, networking, or direct outreach, all of which remain necessary parts of an effective job search.
- Treat every job description as equally relevant or every role as a good fit; the feature only helps the user assess opportunities more intelligently and efficiently.

---

## 4. Behavior

- The user evaluates a software or data engineering role by comparing the role’s stated requirements to their own background, including coursework, projects, internship experience, and job-relevant skills.
- When a role does not match every requirement exactly, the user can still assess whether the role is worth pursuing if the core responsibilities, toolset, and growth potential are aligned with their profile and timing.
- The user searches for opportunities across more than one channel, including major job boards, company career pages, alumni networks, recruiter outreach, and other less visible sources, rather than relying on a single platform.
- The user prioritizes evidence of capability over strict checklist compliance, such as personal projects, GitHub work, portfolio quality, and prior experience that demonstrates readiness for the role.
- The user applies strategically by targeting roles where they have a credible match, a realistic path to the next stage, and a reasonable chance of being considered despite missing one or more ideal-candidate requirements.

---

## 5. Constraints

- The feature is intended for a student who is actively pursuing technical roles during the final semester before graduation, when the job search is time-sensitive and application volume matters.
- The user must be able to evaluate opportunities using information that is publicly available or provided by the user themselves, such as resume details, project evidence, and job descriptions.
- No private or sensitive candidate data should be required beyond what the user voluntarily provides, and the tool should not assume access to employer-side hiring records or internal recruiting systems.
- The feature must function across common job-search environments, including public job boards, recruiter outreach, and company career sites, rather than depending on a single platform.
- The user is expected to invest time in building a credible portfolio, refining application materials, and maintaining outreach effort; the feature supports decision-making but does not eliminate the work required to secure interviews.

---

## 6. Acceptance

- WHEN the user reviews a job posting, THE SYSTEM SHALL compare the role’s requirements to the user’s skills, projects, and relevant experience.
- IF the role is only a partial match, THEN THE SYSTEM SHALL flag it as a potential fit and show which qualifications are missing or weak.
- THE SYSTEM SHALL evaluate opportunities from multiple sources, including job boards, company career pages, and networking channels, before recommending a role.
- WHILE the user is comparing roles, THE SYSTEM SHALL display a fit summary that separates must-have requirements from preferred qualifications.
- WHERE recruiter contact information is available, THE SYSTEM SHALL suggest a follow-up message based on the user’s qualifications and role fit.

---

## Handoff Test

*A competent stranger would still need to know which evidence sources are considered strong enough to justify applying to a role, and how the system should weigh factors such as project quality, recruiter connections, and experience gaps. This specification is based on two interviews and should be treated as a practical starting point rather than a fully validated model of hiring behavior.*

---

## AI Use Note

> What you used AI for on this assignment, if anything. Write "none" if you did not use any.

*AI was used to polish responses which I initially drafted responses for. Final output was reviewed by me to ensure it accurately reflects my thoughts*
