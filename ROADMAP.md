# MyTargets Roadmap

This roadmap defines the planned evolution of **MyTargets** from a
simple target dashboard into a complete personal target and execution
management system.

## Phase 0 --- Foundation

**Status: In Progress**

### Completed

-   [x] Create MyTargets repository
-   [x] Define MyTargets purpose
-   [x] Create initial target spreadsheet
-   [x] Define target categories
-   [x] Add target quantity and unit
-   [x] Add priority
-   [x] Add status
-   [x] Add start and completion dates
-   [x] Add progress tracking
-   [x] Calculate completion percentage
-   [x] Create initial dashboard
-   [x] Define GitHub Pages approach

### Next

-   [ ] Finalize target spreadsheet structure
-   [ ] Review all current targets
-   [ ] Define milestone structure
-   [ ] Define task structure
-   [ ] Define progress-entry structure
-   [ ] Define review process

------------------------------------------------------------------------

## Phase 1 --- Live Dashboard

**Goal:** Make the GitHub Pages dashboard read real data.

### Tasks

-   [ ] Rename `dashboard.html` to `index.html`
-   [ ] Connect Google Sheets
-   [ ] Read target data dynamically
-   [ ] Read progress data dynamically
-   [ ] Calculate progress dynamically
-   [ ] Calculate remaining target dynamically
-   [ ] Calculate days remaining dynamically
-   [ ] Display last updated date
-   [ ] Add loading state
-   [ ] Add error handling
-   [ ] Validate dashboard against Excel/Google Sheets

### Outcome

The dashboard becomes a live view of the MyTargets spreadsheet.

------------------------------------------------------------------------

## Phase 2 --- Target Management

**Goal:** Make targets easier to understand and manage.

### Tasks

-   [ ] Target detail view
-   [ ] Target history view
-   [ ] Category filtering
-   [ ] Priority filtering
-   [ ] Status filtering
-   [ ] Due-date filtering
-   [ ] Sort targets
-   [ ] Show completed targets separately
-   [ ] Show overdue targets
-   [ ] Show targets needing attention

### Outcome

Users can quickly understand the current state of all targets.

------------------------------------------------------------------------

## Phase 3 --- Milestones & Tasks

**Goal:** Connect targets to execution.

### Target hierarchy

``` text
Target
   ↓
Milestone
   ↓
Task
   ↓
Action
```

### Tasks

-   [ ] Define milestone data model
-   [ ] Define task data model
-   [ ] Link milestones to targets
-   [ ] Link tasks to milestones
-   [ ] Add task status
-   [ ] Add task priority
-   [ ] Add task due date
-   [ ] Add task completion
-   [ ] Show next actions for each target

### Outcome

MyTargets moves beyond progress tracking into execution management.

------------------------------------------------------------------------

## Phase 4 --- Daily & Weekly Management

**Goal:** Help decide what to work on.

### Tasks

-   [ ] Today's focus
-   [ ] Today's tasks
-   [ ] Overdue tasks
-   [ ] Weekly plan
-   [ ] Weekly review
-   [ ] Daily progress entry
-   [ ] Weekly progress summary
-   [ ] Priority-based recommendations

### Outcome

The system helps answer:

> **What should I focus on today?**

------------------------------------------------------------------------

## Phase 5 --- Reviews & Insights

**Goal:** Turn historical data into useful decisions.

### Tasks

-   [ ] Daily review
-   [ ] Weekly review
-   [ ] Monthly review
-   [ ] Target progress trends
-   [ ] Identify stalled targets
-   [ ] Identify consistently delayed targets
-   [ ] Compare planned vs actual progress
-   [ ] Track completion rate
-   [ ] Add simple progress insights

### Outcome

MyTargets becomes a feedback system:

``` text
Plan
 ↓
Execute
 ↓
Measure
 ↓
Review
 ↓
Improve
```

------------------------------------------------------------------------

## Phase 6 --- Application Architecture

**Goal:** Move from spreadsheet-driven management toward a dedicated
application where appropriate.

### Possible architecture

``` text
Frontend
   ↓
MyTargets API
   ↓
Database
```

Potential technologies can be evaluated later based on actual
requirements.

Possible options:

-   HTML / CSS / JavaScript
-   React
-   Spring Boot
-   PostgreSQL
-   Google Sheets as an initial integration

**Important:** Do not introduce a backend until the simpler Google
Sheets approach has been validated.

------------------------------------------------------------------------

## Phase 7 --- Advanced MyTargets

**Future**

Potential capabilities:

-   [ ] Automated reminders
-   [ ] Progress alerts
-   [ ] Target health score
-   [ ] Goal forecasting
-   [ ] Personal analytics
-   [ ] Calendar integration
-   [ ] Mobile-friendly experience
-   [ ] Authentication
-   [ ] Multiple dashboards
-   [ ] Data export/import
-   [ ] Backup and restore

These features should only be added when they solve a real problem.

------------------------------------------------------------------------

## Guiding Principle

MyTargets should evolve incrementally.

``` text
Simple
  ↓
Useful
  ↓
Reliable
  ↓
Measurable
  ↓
Intelligent
```

We should avoid building features simply because they are technically
possible.

Every feature should answer:

> **Does this help me make better progress toward my targets?**
