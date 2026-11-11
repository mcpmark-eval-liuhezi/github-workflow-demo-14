# Workflow Audit

This page documents how branch, pull request, issue, and close-out fit together in this repository. It is the audit artifact for the end-to-end GitHub workflow demo.

## Overview

A tidy GitHub workflow keeps every piece of work visible in one place:

- **Branch** — where work happens. Changes are made on a dedicated branch (`feature/audit-notes`) instead ofdirectly on the default branch.
- **Pull Request** — the change is proposed from a feature branch into the default branch (`main`) for review before it lands.
- **Issue** — the work item lives as an issue (`Demo: workflow checklist`) so progress is tracked separately from code.
- **Close-out** — once the checklist is done and the PR is reviewed, the issue is closed as completed and the PR is left open (not merged) for the demo.

## How the pieces fit together

1. A issue is opened to define the task: **"Demo: workflow checklist"**.
2. A follow-up issue (**"Follow-up:Owner profile details"**) is attached as a sub-issue to track the smaller remaining work.
3. Work is done on `feature/audit-notes`, documented in `WORKFLOW_AUDIT.md`, and committed with the message **"Add audit documentation"**.
4. A pull request titled **"Add workflow audit notes"** is opened from `feature/audit-notes` into `main` for review.
5. A comment **"Checklist complete, closing this out"** is posted on the checklist issue, and the checklist issue is closed as **completed**.
6. The pull request is left **open** (not merged) so the team can walk through the review� process live during show-and-tell.

## Close-out checklist

- [x] Working branch created: `feature/audit-notes`
- [x] Audit write-up committed with message: `Add audit documentation`
- [x] Pull request opened: "Add workflow audit notes" (left open, not merged)
- [x] Checklist issue opened: "Demo: workflow checklist"
- [x] Follow-up issue attached as sub-issue
- [x] Comment posted: "Checklist complete, closing this out"
- [x] Checklist issue closed as completed; follow-up issue left open

## Owner

Profile details for the demo owner, drawn from the GitHub profile API:

- **Login:** `HeziLiu`
- **Display name:** Hezi Liu
- **Bio:** treat me like a tree
- **Location:** Beijing/Guiyang
- **Company:** BUPT/GZU
- **Profile URL:** https://github.com/HeziLiu
- **Account ID:** 28861483
- **Account created:** 2017-05-22
- **Public repos:** 4
- **Followers / Following:** 6 / 5
- **Email:** tackic@icloud.com
