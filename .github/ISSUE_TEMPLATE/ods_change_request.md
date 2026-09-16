---
name: ODS Change Request
about: This is the template to use with a Change Request.
title: "[CHANGE] "
labels: ''
assignees: ''
type: Change

---
Before submitting a change, review our Change Management Process on ANCHOR. 

# [CHANGE] <short descriptive title> 
One or two lines: what this is, the parent issue, and any associated PRs. 
 
## Change Type 
Normal, Standard, or Emergency.
> NOTE: 'Standard' changes must have prior been logged in our Standard Change Registry on the SRE Sharepoint.
 
## Risk Level 
Low, Medium, or High as assessed by our Risk Assessment Matrix on ANCHOR.
 
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
