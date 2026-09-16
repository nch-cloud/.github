---
name: ODS Change Request
about: This is the template to use with a Change Request.
title: "[CHANGE] "
labels: ''
assignees: ''
type: Change

---
Before submitting a change, review our [Change Management Process](https://nationwidechildrens.sharepoint.com/:b:/r/sites/A10147/Shared%20Documents/03%20Processes/SRE-PRC-001%20Change%20Management%20Process.pdf?d=wf2dd981ff29944edb6ef1f3aa24e96d1&csf=1&web=1&e=WWqEiu) on ANCHOR. 

# [CHANGE] <short descriptive title> 
One or two lines: what this is, the parent issue, and any associated PRs. 
 
## Change Type 
Normal, Standard, or Emergency.
NOTE: 'Standard' changes must have prior been logged in our [Standard Change Registry](https://nationwidechildrens.sharepoint.com/:w:/r/sites/H10708/Shared%20Documents/01%20RESOURCES/05%20Program%20Management/SRE-APX-009%20SRE%20Standard%20Change%20Register%20v1.0.docx?d=wc06c6473c4a8436b9b6c5a7966906186&csf=1&web=1&e=2INMGN).
 
## Risk Level 
Low, Medium, or High as assessed by our [Risk Assessment Matrix](https://nationwidechildrens.sharepoint.com/:b:/r/sites/A10147/Shared%20Documents/07%20Appendices/SRE-APX-002%20Risk%20Assessment%20Matrix.pdf?d=wc40d891fd9e64ee89a4e6a65c1217369&csf=1&web=1&e=tfKxcS).
 
## Business Justification 
The problem this solves and why it needs to be done. 
 
## What changes 
The changes as bullet points, including target account/environment.
- Change
- Change
- Change
 
## Testing and Validation 
How it was validated (nonprod, live checks) to ensure it works on deploy. 
 
## Implementation Plan 
Numbered steps from merge to live. 
1. Step One
2. Step Two
3. Step Three
 
## Rollback Triggers 
Conditions that would cause a rollback. 
 
## Rollback Plan 
How to undo, including the PR revert path. 
 
## Communication Plan 
Who needs to be informed, and any written comms plans. If none, use N/A. 
