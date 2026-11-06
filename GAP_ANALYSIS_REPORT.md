# Simulated Readiness Findings — CISO Brief
**Company:** Nova Care Cloud (fictional)  
**Prepared by:** GRC Analyst (portfolio exercise)  
**Date:** November 6, 2026

## Executive summary
Of **8 internally defined practice controls**, **3 passed, 3 failed, 2 could not be tested** due to missing evidence. This illustrates control-testing discipline but makes **no claim about HITRUST readiness score, certification eligibility, or HIPAA compliance**.

| Finding | Severity | Evidence | Proposed corrective action |
|---|---|---|---|
| F-01: Late access removal | High | EV-002 | Integrate HR and IAM offboarding, automate 24-hour alert |
| F-02: Late critical remediation | High | EV-004 | Triage remediation backlog, record exception approvals |
| F-03: Missing tabletop report | Medium | EV-005 missing | Schedule tabletop, store signed outcomes |
| F-04: High-risk vendor review missing | High | EV-007 | Complete review, document acceptance/escalation |
| F-05: Missing restore test evidence | High | EV-008 missing | Run restore test and preserve results |

## Testing notes
- **EV-002:** EMP-102 was disabled **32 hours** after separation, beyond the fictional 24-hour policy.
- **EV-004:** V102 took **22 days** from identification to resolution, beyond the fictional 15-day policy.
- **EV-007:** VEN-02 has no current documented review in the provided sample.
- **EV-005 / EV-008:** Not tested because artifacts were not supplied. Control performance cannot be inferred from missing evidence alone.

## CISO decisions requested
1. Approve owners and remediation deadlines for the high-severity findings.
2. Require owners to supply incident tabletop and restore testing artifacts.
3. Re-test late offboarding and vulnerability remediation after fixes.
4. Determine an appropriate HITRUST pathway and obtain official scoping requirements before any certification program begins.

**Disclaimer:** All data and findings are fictional.
