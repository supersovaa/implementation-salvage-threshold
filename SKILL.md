---
name: implementation-salvage-threshold
description: Decide whether an outdated in-progress implementation is worth salvaging or should be reimplemented from the latest confirmed design and plan.
---

# Implementation Salvage Threshold

Compare salvaging an outdated in-progress implementation with reimplementing from the latest confirmed state.

## Apply when implementation falls behind

Apply this skill when changed assumptions, design, or plans leave an in-progress implementation behind the latest confirmed state.

## Compare total effort

Compare the total effort of salvaging the existing implementation with the effort of reimplementation.
Include code changes, design adjustment, replanning, synchronization, additional review, and complexity introduced by preserving older assumptions.

When the salvage work is likely to create a heavier chain of work than reimplementation, recommend reimplementation from the latest confirmed state.

## Promote useful knowledge

Extract useful design decisions, discoveries, constraints, and test perspectives from the existing implementation.
Reflect them in the authoritative design, plan, or other appropriate source of truth before proceeding.
Use the resulting confirmed state as the basis for continued implementation.

Treat implementation preservation as a means of reducing total work rather than as a goal of its own.

This skill decides whether implementation salvage is worthwhile.
Replanning procedures, implementation workflows, and repository operations belong to their respective skills.
