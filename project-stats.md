---
title: Stage Overview
has_children: false
nav_order: 0
layout: page
parent: Stages
---

# Stage Overview

The **Overview** tab under each project stage provides visual insights and detailed statistics for screening and annotation activities, helping you easily track progress.

## Screening Stage

### Dual Screening

The dual screening stage provides two distinct chart views:

#### Basic View
Displays overall screening progress across categories:
- Not Started
- Single Screened
- Dual Screened Completed
- Dual Screened (Disagreement - requires reconciliation)
- Triple Screened Completed (requires reconciliation)
- Over Screened

![Screening Overview - Basic](figs/Fig_Project-Stats_Screening_CSI.png)

#### Detailed View (Show Screening Decisions)
Displays detailed screening decisions:
- Single/Dual screened studies with inclusion or exclusion decisions
- Disagreements requiring reconciliation
- Over screened studies with inclusion/exclusion decisions

![Screening Overview - Detailed](figs/Fig_Project-Stats_Screening2_CSI.png)

**Hover over chart slices for exact study counts and percentages:**

![Hover Examples](figs/Fig_Project-Stats_Screening3_CSI.png) ![Hover Examples](figs/Fig_Project-Stats_Screening4_CSI.png)

#### Screening Leaderboard
The **Screening Leaderboard** table tracks each user's screening activities, providing:
- Number of studies screened
- Studies available/unavailable for screening

![Screening Leaderboard](figs/Fig_Project-Stats_Screening-table_CSI.png)

### Single Screening

Single screening offers similar basic and detailed views:

- Basic view:
  - Not Screened
  - Screened Once
  - Over Screened

- Detailed view:
  - Adds decisions for inclusion/exclusion.

## Annotation Stage

The annotation stage features two primary views:

#### Basic View
Shows overall annotation progress, categorized by:
- No Completed Reviews
- One Completed Review
- Two Completed Reviews
- Over Annotated

![Annotation Overview - Basic](figs/Fig_Project-Stats_Annotation_CSI.png)

#### Detailed View ("Show All")
Breaks down annotation progress by session completion status:
- Complete Sessions (green)
- Incomplete Sessions (orange; annotation started but unfinished)

![Annotation Overview - Detailed](figs/Fig_Project-Stats_Annotation2_CSI.png)

**Hover over slices for exact study counts and session status:**

![Hover Examples](figs/Fig_Project-Stats_Annotation3_CSI.png) ![Hover Examples](figs/Fig_Project-Stats_Annotation4_CSI.png)

#### Annotation Leaderboard
The **Annotation Leaderboard** table provides user-specific annotation metrics, including:
- Annotated studies
- Reviews in progress
- Studies available/unavailable for annotation

![Annotation Leaderboard](figs/Fig_Project-Stats_Annotation-table_CSI.png)

## Review Completion Criteria

| Without "Show All"         | With "Show All"                                        |
|----------------------------|---------------------------------------------------------|
| No completed review        | 0 complete and 0 incomplete sessions                    |
|                            | 1 incomplete and 0 complete sessions                    |
|                            | 2 incomplete and 0 complete sessions                    |
| One completed review       | 1 complete and 0 incomplete sessions                    |
|                            | 1 complete and 1 incomplete sessions                    |
| Two completed reviews      | 2 complete and 0 incomplete sessions                    |
| Over annotated             | ≥ 3 complete sessions                                   |
|                            | ≥ 2 complete and ≥ 1 incomplete sessions                |
|                            | ≥ 1 complete and ≥ 2 incomplete sessions                |
|                            | ≥ 3 incomplete sessions                                 |

**Note:** This view is optimized for stages configured with "Required Annotators per Study" set to 2. Thus, studies with ≥ 3 annotators are considered "over annotated".

