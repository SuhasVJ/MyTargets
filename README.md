# MyTargets

**MyTargets** is a personal target and execution management system
designed to turn meaningful goals into measurable targets, actionable
tasks, and continuous progress.

> **Don't just manage tasks. Manage progress toward your targets.**

## Purpose

MyTargets helps manage different areas of life and work from one
structured system.

It is designed to answer three simple questions:

1.  **What do I want to achieve?**
2.  **How much progress have I made?**
3.  **What should I do next?**

## Core Model

MyTargets follows this execution cycle:

**Vision → Targets → Milestones → Projects → Tasks → Actions → Results →
Review → Improve**

The system is intentionally built around measurable outcomes rather than
only maintaining a task list.

## Target Management

Each target can contain:

-   Target ID
-   Target name
-   Category
-   Description
-   Start date
-   Target completion date
-   Target quantity
-   Unit
-   Priority
-   Status
-   Final target value
-   Completed value
-   Completion percentage
-   Last updated date

Targets can use different measurement units, such as:

-   ₹ / money
-   \%
-   hours
-   books
-   km
-   other measurable units

## Progress Tracking

Every target can maintain a progress history.

Example:

``` text
T2 - School Fees

Final Target:  ₹84,000
Completed:     ₹25,000
Remaining:     ₹59,000
Progress:      29.76%
```

Progress entries provide historical information instead of only showing
the current state.

## Dashboard

The first dashboard version provides:

-   Overall target summary
-   Active targets
-   Completion percentage
-   High-priority targets
-   Progress bars
-   Category filtering
-   Priority filtering
-   Today's focus
-   Recent progress
-   Days remaining
-   System status

The current dashboard uses sample/static data while the Google Sheets
integration is being developed.

## Data Source

The initial data model is maintained in Excel/Google Sheets.

The planned evolution is:

``` text
Excel / Google Sheets
        ↓
MyTargets Data Model
        ↓
Dashboard
        ↓
Tasks & Progress
        ↓
Reviews & Insights
```

Google Sheets is planned as the initial live data source so the system
can be validated without introducing a full backend database too early.

## Repository Structure

``` text
MyTargets/
├── index.html
├── README.md
├── ROADMAP.md
├── CHANGELOG.md
└── data/
```

During the early phase, the dashboard may temporarily be named
`dashboard.html`. For GitHub Pages, it should eventually be renamed to
`index.html`.

## Development Principles

1.  **Keep the system simple.**
2.  **Targets come before tasks.**
3.  **Measure progress whenever possible.**
4.  **Keep historical progress instead of overwriting it.**
5.  **Avoid unnecessary architecture too early.**
6.  **Build the system around real usage, not assumptions.**
7.  **Review and improve continuously.**

## Current Status

**Phase 0 --- Foundation**

-   Target data model established
-   Progress tracking structure established
-   Multiple target types supported
-   Dashboard V0.1 created
-   GitHub Pages direction established
-   Google Sheets integration planned

## Long-Term Vision

MyTargets should evolve into a personal management system that helps
convert long-term goals into daily execution and measurable results.

The goal is not to build another generic Todo application.

The goal is to build a system that helps answer:

> **What matters, where am I now, and what should I do next?**
