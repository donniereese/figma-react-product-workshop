# React Implementation Readiness Guide

Use this checklist to ensure Figma artifacts are implementation-ready.

## Component thinking
- Define component boundaries by business responsibility, not only layout.
- Document reusable primitives and composite components.
- Align naming so design and code refer to the same entities.

## State variations
- Cover baseline and exception states: loading, empty, error, success, permission-restricted.
- Document transition triggers and expected UI feedback.
- Clarify optimistic vs server-confirmed state updates.

## Responsive behavior
- Define behavior at key breakpoints (layout shifts, density changes, action placement).
- Document what must remain persistent across viewport changes.

## Accessibility expectations
- Specify keyboard path and focus behavior for core tasks.
- Include semantic expectations for tables, forms, and status announcements.
- Define minimum accessibility acceptance criteria for each high-usage flow.

## Interaction behavior
- Annotate timing-sensitive interactions (autosave, async actions, retries, timeouts).
- Specify confirmation patterns for destructive or high-risk actions.

## Handoff package minimum
- Component inventory
- Variant/state matrix
- Behavior annotations
- Responsive notes
- Accessibility criteria
- Open issues and implementation constraints log
