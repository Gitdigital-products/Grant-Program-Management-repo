<a href='https://ko-fi.com/T6T61WAZYZ' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi5.png?v=6' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>



<script src="https://liberapay.com/GitDigital_liberapay/widgets/button.js"></script>
<noscript><a href="https://liberapay.com/GitDigital_liberapay/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a>noscript>

https://liberapay.com/GitDigital_liberapay/widgets/button.js
<!-- Security Badges -->
![Security Foundational](https://img.shields.io/badge/security-foundational-blue)
![Security Scanning](https://img.shields.io/badge/security-scanning-active-green)
![Dependency Status](https://img.shields.io/badge/deps-up--to--date-brightgreen)

<!-- Activity Badges -->
![Last Commit](https://img.shields.io/badge/commit-recent-yellow)
![Issues Health](https://img.shields.io/badge/issues-healthy-brightgreen)
![PR Velocity](https://img.shields.io/badge/PR-velocity-fast-brightgreen)

<!-- Maturity Badges -->
![CI Status](https://img.shields.io/badge/CI-passing-brightgreen)
![Versioning](https://img.shields.io/badge/versioning-semver-blue)
![Test Coverage](https://img.shields.io/badge/coverage-comprehensive-brightgreen)

<!-- Technology Badges -->
![Containerized](https://img.shields.io/badge/containerized-Docker-blue)
![CI Platform](https://img.shields.io/badge/CI-GitHub_Actions-blue)

<!-- Quality Badges -->
![Linting](https://img.shields.io/badge/linting-passing-brightgreen)
![Documentation](https://img.shields.io/badge/docs-complete-brightgreen)
![Code Owners](https://img.shields.io/badge/codeowners-defined-blue)

<!-- Community Badges -->
![License](https://img.shields.io/badge/license-MIT-yellow) 
<!-- Security Badges -->
![Security Foundational](https://img.shields.io/badge/security-foundational-blue)
![Security Scanning](https://img.shields.io/badge/security-scanning-active-green)
![Security Vulnerabilities](https://img.shields.io/badge/vulnerabilities-0-critical-brightgreen)

<!-- Activity Badges -->
![Last Commit](https://img.shields.io/badge/commit-recent-yellow)
![Issues Health](https://img.shields.io/badge/issues-healthy-brightgreen)

<!-- Maturity Badges -->
![CI Status](https://img.shields.io/badge/CI-passing-brightgreen)
![Versioning](https://img.shields.io/badge/versioning-semver-blue)
![Test Coverage](https://img.shields.io/badge/coverage-comprehensive-brightgreen)

<!-- Technology Badges -->
![Primary Language](https://img.shields.io/badge/language-JavaScript-yellow)
![Secondary Language](https://img.shields.io/badge/language-Python-blue)
![CI Platform](https://img.shields.io/badge/CI-GitHub_Actions-blue)

<!-- Quality Badges -->
![Linting](https://img.shields.io/badge/linting-passing-brightgreen)
![Documentation](https://img.shields.io/badge/docs-complete-brightgreen)
![Code Owners](https://img.shields.io/badge/codeowners-defined-blue)
![Dependency Health](https://img.shields.io/badge/deps-healthy-brightgreen)

<!-- Community Badges -->
![License](https://img.shields.io/badge/license-MIT-yellow)


<!-- Security Badges -->
![Security Foundational](https://img.shields.io/badge/security-foundational-blue)
![Security Scanning](https://img.shields.io/badge/security-scanning-inactive-red)

<!-- Activity Badges -->
![Last Commit](https://img.shields.io/badge/commit-recent-yellow)
![Release Status](https://img.shields.io/badge/releases-none-red)

<!-- Technology Badges -->
![License](https://img.shields.io/badge/license-MIT-yellow)

<!-- Quality Badges -->
![Documentation](https://img.shields.io/badge/docs-minimal-orange)

<!-- Community Badges -->
![Governance](https://img.shields.io/badge/governance-partial-orange)



<!-- Security Badges -->
![Security Foundational](https://img.shields.io/badge/security-foundational-blue)
![Security Scanning](https://img.shields.io/badge/security-scanning-inactive-red)

<!-- Activity Badges -->
![Last Commit](https://img.shields.io/badge/commit-recent-yellow)
![Release Status](https://img.shields.io/badge/releases-none-red)

<!-- Technology Badges -->
![License](https://img.shields.io/badge/license-MIT-yellow)

<!-- Quality Badges -->
![Documentation](https://img.shields.io/badge/docs-minimal-orange)

<!-- Community Badges -->
![Governance](https://img.shields.io/badge/governance-partial-orange)


<!-- Security Badges -->
![Security Foundational](https://img.shields.io/badge/security-foundational-blue)
![Security Scanning](https://img.shields.io/badge/security-scanning-active-green)

<!-- Activity Badges -->
![Last Commit](https://img.shields.io/badge/commit-current-brightgreen)
![Issues Health](https://img.shields.io/badge/issues-healthy-brightgreen)
![Release Cadence](https://img.shields.io/badge/releases-active-brightgreen)

<!-- Maturity Badges -->
![CI Status](https://img.shields.io/badge/CI-passing-brightgreen)
![Versioning](https://img.shields.io/badge/versioning-semver-blue)

<!-- Technology Badges -->
![Primary Language](https://img.shields.io/badge/language-JavaScript-yellow)
![Containerized](https://img.shields.io/badge/containerized-Docker-blue)

<!-- Quality Badges -->
![Linting](https://img.shields.io/badge/linting-passing-brightgreen)
![Documentation](https://img.shields.io/badge/docs-complete-brightgreen)

<!-- Community Badges -->
![Contributors](https://img.shields.io/badge/contributors-2-blue)
![License](https://img.shields.io/badge/license-MIT-yellow)


# Grant Program Management

A comprehensive toolkit for managing developer grant programs, including application workflows, review processes, and program administration.

## Features

- Grant application management
- Reviewer assignment and workflows
- Application scoring and evaluation
- Program analytics and reporting
- Document templates and guidelines

## Quick Start

```bash
git clone https://github.com/your-username/grant-program-management
cd grant-program-management
npm install
npm run dev
```
1. SYSTEM OVERVIEW

Purpose

The Grant Program Management System (GPMS) is a comprehensive platform for managing end-to-end grant lifecycles. It supports multiple grant rounds, applicant submissions, peer review, scoring, governance, and transparency reporting. The system ensures fair, auditable, and efficient grant distribution.

High-Level Architecture

· Frontend: Static site generated via GitHub Pages (HTML/CSS/JS) for public pages and applicant/reviewer dashboards.
· Backend: Serverless functions (AWS Lambda / GitHub Actions) for automation; data stored in JSON files within the repository (Git-based versioning) and optionally synced to a database.
· Data Layer: Flat files (CSV, JSON) in /data; schemas in /schemas; version controlled.
· Automation: GitHub Actions workflows handle repetitive tasks (scoring aggregation, status updates, exports).
· Integration: CLI tools for local management; optional API for external systems.

Core Modules

· Application Management: Forms, submission, validation, and applicant tracking.
· Reviewer Management: Onboarding, assignment, conflict-of-interest checks, scoring.
· Scoring & Aggregation: Weighted rubrics, automated scoring, tie-breaking, risk flags.
· Governance & Compliance: Validation rules, compliance checks, final decision workflows.
· Transparency & Reporting: Public dashboards, exportable reports, audit logs.

Data Flow

1. Applicant submits form → JSON stored in /data/applications/ with unique ID and status "submitted".
2. Automation moves status to "under-review" and assigns reviewers based on logic.
3. Reviewers submit scores → stored in /data/scores/; aggregation triggers when all scores received.
4. Aggregated scores → /data/aggregated_scores/; governance committee reviews.
5. Final decision (approve/decline) → status updated; notifications generated.
6. Transparency report generated → /docs/transparency/ and published on GitHub Pages.

User Roles

· Applicant: Submits proposals, views status, receives notifications.
· Reviewer: Reviews assigned applications, submits scores, adheres to code of conduct.
· Admin: Manages grant rounds, reviewers, assignments, and system configuration.
· Program Lead: Oversees program, makes final decisions, publishes reports.

2. FULL REPO STRUCTURE

```
/
├── .github/
│   └── workflows/
│       ├── assign-reviewers.yml
│       ├── aggregate-scores.yml
│       ├── update-status.yml
│       ├── compliance-check.yml
│       ├── export-reports.yml
│       └── generate-transparency-report.yml
├── config/
│   ├── grant-rounds.json
│   ├── scoring-rubric.json
│   ├── reviewer-assignment-rules.json
│   └── compliance-rules.json
├── data/
│   ├── applications/
│   │   └── *.json
│   ├── reviewers/
│   │   └── *.json
│   ├── scores/
│   │   └── *.json
│   ├── aggregated_scores/
│   │   └── *.json
│   ├── grants/
│   │   └── *.json
│   ├── master_tracker.csv
│   ├── proposal_library.csv
│   ├── follow_up_log.csv
│   ├── contacts.csv
│   └── reviewer_scoring_sheet.csv
├── docs/
│   ├── workflows/
│   │   ├── application-intake.md
│   │   ├── reviewer-assignment.md
│   │   ├── scoring.md
│   │   ├── governance-validation.md
│   │   ├── compliance-checks.md
│   │   ├── status-transitions.md
│   │   ├── final-decision.md
│   │   ├── exporting-results.md
│   │   └── transparency-reporting.md
│   ├── templates/
│   │   ├── applicant-instructions.md
│   │   ├── reviewer-instructions.md
│   │   ├── program-announcement.md
│   │   ├── award-notification.md
│   │   ├── decline-notification.md
│   │   ├── follow-up-email.md
│   │   └── transparency-report.md
│   ├── reviewer-guides/
│   │   ├── onboarding.md
│   │   ├── code-of-conduct.md
│   │   └── scoring-instructions.md
│   └── applicant-guides/
│       └── how-to-apply.md
├── pages/
│   ├── index.md
│   ├── tracker.md
│   ├── proposals.md
│   ├── reviewer.md
│   ├── apply.md
│   ├── governance.md
│   └── status.md
├── schemas/
│   ├── application-schema.json
│   ├── reviewer-schema.json
│   ├── score-schema.json
│   ├── grant-round-schema.json
│   ├── status-update-schema.json
│   └── transparency-report-schema.json
├── scoring/
│   ├── rubric.md
│   ├── weighted-criteria.json
│   ├── reviewer-sheet.md
│   ├── reviewer-sheet.csv
│   ├── aggregation-logic.js
│   ├── tie-breaking-rules.md
│   └── risk-flags.json
├── status/
│   ├── status-flow.json
│   └── transitions.json
├── grant-rounds/
│   ├── round-001/
│   │   ├── config.json
│   │   ├── applications/
│   │   └── reviewers/
│   └── round-002/
├── scripts/
│   ├── assign-reviewers.js
│   ├── aggregate-scores.js
│   ├── compliance-check.js
│   ├── export-csv.js
│   └── generate-report.js
├── automation/
│   ├── status-updater.js
│   ├── reviewer-matcher.js
│   ├── score-aggregator.js
│   ├── compliance-checker.js
│   ├── exporter.js
│   └── report-generator.js
├── cli/
│   ├── index.js
│   ├── commands/
│   └── package.json
├── api/
│   ├── openapi.yaml
│   └── endpoints/
├── public/
│   └── assets/
├── README.md
└── LICENSE
```

File Contents (Selected Examples)

Due to space, only critical files are fully shown; others are summarized.

.github/workflows/assign-reviewers.yml

```yaml
name: Assign Reviewers
on:
  push:
    paths:
      - 'data/applications/*.json'
jobs:
  assign:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Run assignment script
        run: node scripts/assign-reviewers.js
      - name: Commit changes
        run: |
          git config --global user.name 'github-actions'
          git config --global user.email 'actions@github.com'
          git add data/reviewers/ data/scores/
          git commit -m "Auto-assign reviewers" || exit 0
          git push
```

config/grant-rounds.json

```json
{
  "rounds": [
    {
      "id": "R001",
      "name": "Spring 2025 Grants",
      "status": "open",
      "openDate": "2025-01-01",
      "closeDate": "2025-03-31",
      "maxApplications": 100,
      "scoringRubric": "default"
    }
  ]
}
```

config/scoring-rubric.json

```json
{
  "criteria": [
    {
      "name": "Impact",
      "weight": 0.3,
      "minScore": 1,
      "maxScore": 10
    },
    {
      "name": "Feasibility",
      "weight": 0.25,
      "minScore": 1,
      "maxScore": 10
    },
    {
      "name": "Innovation",
      "weight": 0.2,
      "minScore": 1,
      "maxScore": 10
    },
    {
      "name": "Team",
      "weight": 0.15,
      "minScore": 1,
      "maxScore": 10
    },
    {
      "name": "Budget",
      "weight": 0.1,
      "minScore": 1,
      "maxScore": 10
    }
  ]
}
```

config/reviewer-assignment-rules.json

```json
{
  "minReviewersPerApp": 3,
  "maxAppsPerReviewer": 10,
  "avoidConflict": true,
  "matchByExpertise": true
}
```

data/applications/APP-2025-001.json

```json
{
  "id": "APP-2025-001",
  "roundId": "R001",
  "status": "submitted",
  "submittedAt": "2025-02-15T10:30:00Z",
  "applicant": {
    "name": "Jane Doe",
    "email": "jane@example.org",
    "organization": "Nonprofit Inc."
  },
  "proposal": {
    "title": "Community Garden Project",
    "summary": "We aim to create a community garden...",
    "impact": "Will benefit 200 families...",
    "feasibility": "We have land and volunteers...",
    "innovation": "Using hydroponics...",
    "team": "Experienced gardeners...",
    "budget": 50000,
    "budgetBreakdown": "..."
  },
  "files": []
}
```

docs/workflows/application-intake.md

Application Intake Workflow

Steps

1. Applicant accesses /apply page and fills form.
2. Form validation (client-side and server-side) checks required fields.
3. On submission, system generates unique ID (APP-YYYY-XXX).
4. Application JSON saved to /data/applications/.
5. Confirmation email sent to applicant (template in /docs/templates/).
6. Status set to "submitted".
7. Automation triggers reviewer assignment.

Actors

· Applicant
· System (automation)

Inputs

· Form data (name, email, proposal details, etc.)

Outputs

· JSON file in /data/applications/
· Confirmation email

Validation Rules

· All required fields present.
· Email format valid.
· Budget numeric and positive.
· Max length on summary (500 chars).
· No duplicate submissions per email per round.

docs/templates/applicant-instructions.md

Applicant Instructions

Thank you for your interest in our grant program. Please read carefully:

Eligibility

· Organizations must be registered nonprofits.
· Projects must align with our mission.

How to Apply

1. Go to apply.md.
2. Fill out all required fields.
3. Upload any supporting documents.
4. Submit before the deadline.

After Submission

You will receive a confirmation email with your application ID. You can track your application status at tracker.md.

pages/index.md

```markdown
---
title: Grant Program Home
layout: default
---

# Welcome to the Grant Program Management System

We manage multiple grant rounds to fund impactful projects.

## Current Grant Rounds
- Spring 2025 Grants: Open until March 31, 2025. [Apply now](/pages/apply.md).

## Quick Links
- [Proposal Library](/pages/proposals.md)
- [Reviewer Dashboard](/pages/reviewer.md)
- [Governance](/pages/governance.md)
- [Status Tracker](/pages/status.md)
```

pages/tracker.md

```markdown
---
title: Application Tracker
layout: default
---

# Track Your Application

Enter your application ID to see status:

<form>
  <input type="text" placeholder="APP-2025-001" />
  <button>Check Status</button>
</form>

## Recent Submissions
| ID | Title | Status | Submitted |
|----|-------|--------|-----------|
| APP-2025-001 | Community Garden | Under Review | 2025-02-15 |
| APP-2025-002 | Coding Bootcamp | Submitted | 2025-02-16 |
```

schemas/application-schema.json

```json
{
  "$schema": "http://json-schema.org/draft-07/schema#",
  "type": "object",
  "required": ["id", "roundId", "applicant", "proposal"],
  "properties": {
    "id": {"type": "string", "pattern": "^APP-\\d{4}-\\d{3}$"},
    "roundId": {"type": "string"},
    "status": {"type": "string", "enum": ["submitted", "under-review", "scored", "approved", "declined"]},
    "submittedAt": {"type": "string", "format": "date-time"},
    "applicant": {
      "type": "object",
      "required": ["name", "email"],
      "properties": {
        "name": {"type": "string"},
        "email": {"type": "string", "format": "email"},
        "organization": {"type": "string"}
      }
    },
    "proposal": {
      "type": "object",
      "required": ["title", "summary", "impact", "feasibility", "innovation", "team", "budget"],
      "properties": {
        "title": {"type": "string"},
        "summary": {"type": "string", "maxLength": 500},
        "impact": {"type": "string"},
        "feasibility": {"type": "string"},
        "innovation": {"type": "string"},
        "team": {"type": "string"},
        "budget": {"type": "number", "minimum": 0},
        "budgetBreakdown": {"type": "string"}
      }
    },
    "files": {"type": "array", "items": {"type": "string"}}
  }
}
```

scoring/rubric.md

Scoring Rubric

Criterion Description Weight Score (1-10)
Impact Potential to create positive change 30% 
Feasibility Likelihood of successful implementation 25% 
Innovation Novelty and creativity 20% 
Team Expertise and capacity 15% 
Budget Reasonableness and alignment 10% 

Total Weighted Score = sum(score * weight)

scoring/weighted-criteria.json

```json
{
  "criteria": [
    {"name": "Impact", "weight": 0.3},
    {"name": "Feasibility", "weight": 0.25},
    {"name": "Innovation", "weight": 0.2},
    {"name": "Team", "weight": 0.15},
    {"name": "Budget", "weight": 0.1}
  ]
}
```

scoring/aggregation-logic.js

```javascript
module.exports = function aggregateScores(scores) {
  const criteriaWeights = {...}; // load from config
  let total = 0;
  scores.forEach(score => {
    total += score.criteria.impact * 0.3 + score.criteria.feasibility * 0.25 + ...;
  });
  return total / scores.length;
};
```

scoring/tie-breaking-rules.md

Tie-Breaking Rules

In case of equal weighted scores:

1. Higher score in "Impact" criterion.
2. If still tied, higher score in "Feasibility".
3. If still tied, review by Program Lead.

scoring/risk-flags.json

```json
{
  "flags": [
    {
      "name": "Budget too high",
      "condition": "proposal.budget > 100000"
    },
    {
      "name": "Unclear impact",
      "condition": "scores.impact < 5"
    }
  ]
}
```

docs/reviewer-guides/onboarding.md

Reviewer Onboarding

Welcome! As a reviewer, you will evaluate grant applications.

Steps

1. Read the Code of Conduct.
2. Familiarize with the scoring rubric.
3. You will receive an email when applications are assigned.
4. Log in to the Reviewer Dashboard.

docs/reviewer-guides/code-of-conduct.md

Reviewer Code of Conduct

· Declare any conflicts of interest immediately.
· Maintain confidentiality of applications.
· Score objectively based on rubric.
· Do not discuss applications outside the system.
· Complete reviews by the deadline.

scripts/assign-reviewers.js

```javascript
// Reads applications and assigns reviewers based on rules
const fs = require('fs');
const rules = require('../config/reviewer-assignment-rules.json');
// ... logic
```

automation/status-updater.js

```javascript
// Updates application status based on events
```

data/master_tracker.csv

```csv
ID,Title,Applicant,Status,Reviewers,Average Score,Decision
APP-2025-001,Community Garden,Jane Doe,under-review,"REV-001,REV-002",,
APP-2025-002,Coding Bootcamp,John Smith,submitted,,,
```

data/proposal_library.csv

```csv
ID,Title,Organization,Year,Amount Requested,Status
APP-2025-001,Community Garden,Nonprofit Inc.,2025,50000,Under Review
```

data/follow_up_log.csv

```csv
ID,Date,Type,Notes
APP-2025-001,2025-02-20,Email,Sent confirmation
```

data/contacts.csv

```csv
ID,Name,Email,Role
REV-001,Alice Reviewer,alice@example.com,Reviewer
```

data/reviewer_scoring_sheet.csv

```csv
Application ID,Reviewer ID,Impact,Feasibility,Innovation,Team,Budget,Comments
APP-2025-001,REV-001,8,7,9,6,5,Great project but budget concerns
```

schemas/score-schema.json

```json
{
  "$schema": "http://json-schema.org/draft-07/schema#",
  "type": "object",
  "required": ["applicationId", "reviewerId", "criteria", "comments"],
  "properties": {
    "applicationId": {"type": "string"},
    "reviewerId": {"type": "string"},
    "criteria": {
      "type": "object",
      "properties": {
        "impact": {"type": "number", "minimum": 1, "maximum": 10},
        "feasibility": {"type": "number", "minimum": 1, "maximum": 10},
        "innovation": {"type": "number", "minimum": 1, "maximum": 10},
        "team": {"type": "number", "minimum": 1, "maximum": 10},
        "budget": {"type": "number", "minimum": 1, "maximum": 10}
      }
    },
    "comments": {"type": "string"}
  }
}
```

status/status-flow.json

```json
{
  "states": [
    "submitted",
    "under-review",
    "scored",
    "approved",
    "declined"
  ],
  "transitions": [
    {"from": "submitted", "to": "under-review", "trigger": "assign_reviewers"},
    {"from": "under-review", "to": "scored", "trigger": "all_scores_received"},
    {"from": "scored", "to": "approved", "trigger": "governance_approval"},
    {"from": "scored", "to": "declined", "trigger": "governance_decline"}
  ]
}
```

grant-rounds/round-001/config.json

```json
{
  "id": "R001",
  "name": "Spring 2025 Grants",
  "openDate": "2025-01-01",
  "closeDate": "2025-03-31",
  "status": "open"
}
```

cli/index.js

```javascript
#!/usr/bin/env node
// CLI tool for local management
console.log('Grant Program CLI');
```

api/openapi.yaml

```yaml
openapi: 3.0.0
info:
  title: Grant Program API
  version: 1.0.0
paths:
  /applications:
    get:
      summary: List applications
    post:
      summary: Create application
```

public/assets/style.css

```css
body { font-family: sans-serif; }
```

README.md

```markdown
# Grant Program Management System

See documentation in /docs.
```

3. WORKFLOW BLUEPRINTS

Application Intake Workflow

· Steps: See above (Section 2 docs/workflows/application-intake.md).
· Actors: Applicant, System.
· Inputs: Form data.
· Outputs: JSON file, confirmation email.
· Validation: Required fields, email, budget >0, no duplicate.

Reviewer Assignment Workflow

· Steps:
  1. New application with status "submitted" triggers assignment.
  2. System loads available reviewers (exclude those with conflicts).
  3. Matches based on expertise (if configured) and workload.
  4. Assigns minReviewersPerApp reviewers.
  5. Creates score records for each reviewer (empty).
  6. Updates application status to "under-review".
  7. Notifies reviewers.
· Actors: System, Admin (override).
· Inputs: Application, reviewer list.
· Outputs: Reviewer assignments, score placeholders.
· Validation: No self-review, no conflict of interest.

Scoring Workflow

· Steps:
  1. Reviewer accesses dashboard, sees assigned applications.
  2. Reviewer fills scoring sheet (scores 1-10 per criterion, comments).
  3. Submits scores; system stores in /data/scores/.
  4. When all assigned reviewers have submitted, aggregation triggers.
· Actors: Reviewer, System.
· Inputs: Scores.
· Outputs: Score JSON, aggregated score.
· Validation: Scores within range, all criteria filled.

Governance Validation Workflow

· Steps:
  1. Aggregated scores presented to Program Lead/Governance committee.
  2. They review applications and scores.
  3. They make decision (approve/decline) with optional comments.
  4. Status updated accordingly.
· Actors: Program Lead, Admin.
· Inputs: Aggregated scores, applications.
· Outputs: Decision record, status update.
· Validation: Quorum if committee.

Compliance Checks Workflow

· Steps:
  1. Before final decision, run compliance rules.
  2. Check budget against limits, eligibility, risk flags.
  3. Flag any applications that need additional review.
· Actors: System.
· Inputs: Application data.
· Outputs: Compliance report.
· Validation: Rules defined in config.

Status Transitions Workflow

· Steps: Defined in status-flow.json; automated via GitHub Actions on relevant events.
· Actors: System.
· Inputs: Event triggers.
· Outputs: Updated status in application JSON.

Final Decision Process Workflow

· Steps:
  1. Governance reviews compliance and scores.
  2. Approves or declines.
  3. System sends award/decline notification.
  4. Status updated to "approved" or "declined".
  5. If approved, grant record created.
· Actors: Program Lead, Admin, System.
· Inputs: Decision.
· Outputs: Notification, grant record.

Exporting Results Workflow

· Steps:
  1. Admin triggers export (manual or scheduled).
  2. System aggregates all applications, scores, decisions.
  3. Generates CSV/JSON files.
  4. Stores in /data/exports/ or commits to repo.
· Actors: Admin, System.
· Inputs: None.
· Outputs: Export files.

Transparency Reporting Workflow

· Steps:
  1. After grant round closes, generate transparency report.
  2. Include list of applications, scores (anonymized), decisions, total funds awarded.
  3. Publish to /docs/transparency/ and GitHub Pages.
· Actors: System, Admin.
· Inputs: Round data.
· Outputs: Report in markdown/HTML.

4. SCORING SYSTEM

Scoring Rubric

See scoring/rubric.md above.

Weighted Criteria

See scoring/weighted-criteria.json above.

Reviewer Scoring Sheet (Markdown)

See scoring/reviewer-sheet.md:

```markdown
# Reviewer Scoring Sheet

Application ID: __________
Reviewer ID: __________

| Criterion | Score (1-10) | Comments |
|-----------|--------------|----------|
| Impact    |              |          |
| Feasibility|             |          |
| Innovation|              |          |
| Team      |              |          |
| Budget    |              |          |

**Total Weighted Score:** (calculated automatically)
```

Reviewer Scoring Sheet (CSV)

See data/reviewer_scoring_sheet.csv above.

JSON Schema for Scoring

See schemas/score-schema.json above.

Aggregation Logic

See scoring/aggregation-logic.js above.

Tie-Breaking Rules

See scoring/tie-breaking-rules.md above.

Risk Flags

See scoring/risk-flags.json a
