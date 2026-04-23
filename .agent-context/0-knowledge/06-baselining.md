# Baselining

## Overview

Baselines capture a snapshot of the plan at a point in time. They can be set at multiple hierarchy levels and there is no limit to the number of times a plan can be re-baselined.

## Setting a Baseline

1. User clicks the **Baseline** button
2. A dialogue box is presented to confirm what should be baselined
3. User selects the hierarchy level and scope

### Baseline Dialogue

```
┌─────────────────────────────────────────┐
│  Set baseline for                       │
│                                         │
│  Choose hierarchy:                      │
│  ☐ Portfolio                            │
│  ☐ Programme                            │
│  ☐ Project                              │
│  ☐ Selected tasks                       │
│                                         │
│  Scope:                                 │
│  ▼ Project 1                            │
│    Project 2                            │
│    Project 3                            │
│    Project 4                            │
│                                         │
│  [Baseline History]    [Set Baseline]   │
└─────────────────────────────────────────┘
```

- User clicks on the **dropdown** and gets hierarchy level options
- Hovers on selection for further options based on existing data set in the plan
- If user has already **selected tasks** in the plan, selecting a parent will automatically include the children

## Hierarchy Levels for Baselining

| Level | Example |
|-------|---------|
| Enterprise | — |
| Portfolio | Portfolio Baseline 1, 2…n |
| Programme | Programme Baseline 1, 2…n |
| Project | Project Baseline 1, 2…n |
| Task | No numbering required |

## What Happens When a Baseline is Set

1. **Tasks within the baseline are set to Green** status. If this changes the status of any tasks, Lyra asks the user first.
2. **Dates are stored as baseline dates**. These can be viewed as an attribute and/or in the baseline history.

## Baseline Numbering

Now that Lyra understands structure, baselines are numbered:
- Portfolio Baseline 1, 2…n
- Programme Baseline 1, 2…n
- Project Baseline 1, 2…n
- No need to number task baselines

## Baseline History

Takes the user to a **filtered view of the change log**. "Baseline" is a category in the change log.

Baselining is logged in the change table.

## Baseline Record

When a baseline is created:
> **Baseline x created**
- Change control record added
- Baseline ID added to relevant rows in plan
- Overall visual indication that line items are baselined
