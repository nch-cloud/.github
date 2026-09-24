---
name: ODS Application Onboarding Request
about: This is the template to use with an Application Onboarding Request.
title: "[ONBOARDING] "
labels: ''
assignees: ''
type: Change

---
Before submitting, review our Application Onboarding Process on ANCHOR and complete SRE-FRM-010 System Change Impact Assessment.

# [ONBOARDING] <application name>
One or two lines: what this application does and the business need it serves.

## Artifacts
- **FRM-010 (System Change Impact Assessment):** <link>
- **Architecture Diagram:** <link>
- **Data Flow Diagram:** <link>
- **IAM Roles:** <link to YAML/JSON>
- **KMS Keys:** <link to YAML/JSON>
- **Additional artifacts:** <link or N/A>

## Data Classification
Does this application handle CUI or PHI? If yes, ensure you’ve identified what and where in your SRE-FRM-010.

## External Connectivity
Does this application connect to any system outside the SRE boundary? If yes, ensure you’ve identified what and where in your SRE-FRM-010.

## Deviations
Any known deviations from the provided standards. If none, use N/A. Note that each deviation requires a separate approved exception request.

## Go-Live Date
Requested date and any hard dependencies driving it.
