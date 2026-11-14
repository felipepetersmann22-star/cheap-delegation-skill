---
name: cheap-delegation
description: Plan and coordinate agent delegation when work can be divided, an independent review is needed, or a worker needs a clear brief. Use for choosing scope and effort, avoiding duplicated research, and integrating delegated results.
license: MIT
---

# Cheap delegation

Delegate when it improves the outcome enough to justify coordination. A short lookup or a few dependent steps usually stay with one agent. Independent substantial work, specialist work, or a genuinely independent review can justify parallel workers. Preserve any user-required reviewers, model choices, or independence even if they cost more.

## Decide and scope

Check whether delegation is allowed and which workers, tools, context inheritance, models and effort controls are actually available. A worker may inherit history or start with limited context; do not assume either. If delegation is unavailable or out of scope, do the work directly and report any missing independent review.

Split work at real boundaries. Assign each worker a deliverable, explicit file or responsibility ownership when editing, relevant input and what is already known. Parallel writers must know they share a workspace and must not revert others' changes. Avoid redundant exploration, but use separate reviewers where independence is a requirement. Set the number of workers to the task's complexity and available capacity, not a fixed universal limit.

Choose available effort and capabilities for complexity, ambiguity, risk and consequences. Simple extraction may need little; difficult reasoning or a consequential error may justify more from the start. Retry or adjust only when evidence warrants it. Do not assume an effort or model control exists.

## Brief and coordinate

Use [the worker brief](assets/worker-brief.md) when it helps. Give the goal and decision, necessary context and source pointers, scope and ownership, allowed tools and side effects, expected output, completion criteria, and a useful blocked condition. Give an independent reviewer only the information appropriate to its review; do not reveal the intended answer to a blind evaluator.

Reuse a worker that already knows the workstream where possible. If it is unavailable, give its successor the relevant findings and source pointers. Follow the user's requested cadence and platform rules for progress updates. A skill instruction is not permission to contact third parties, change external systems, or exceed the original task.

## Integrate

Read the actual deliverables, not only worker summaries. Reconcile conflicts, inspect changes against ownership and scope, and run checks appropriate to the result. Distinguish a worker's report from independently verified behavior. Report missing work, disagreement, blocked tasks and untested assumptions; do not claim success from a dispatched task alone. Cite primary sources and dates for changeable facts when the work calls for research.

## Example

For a single known file lookup, search directly. For an implementation with independent frontend and backend changes plus a required blind review, assign separate non-overlapping ownership and keep the review independent; integrate and test the combined result before reporting it complete.
