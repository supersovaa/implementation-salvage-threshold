# Implementation Salvage Threshold

A lightweight skill for deciding whether an outdated in-progress implementation should be salvaged or replaced by reimplementation from the latest confirmed state.

## Core idea

Preserving existing implementation is useful only when it reduces total work.
When salvage would create a heavier chain of code changes, design adjustment, replanning, synchronization, review, and compatibility work than reimplementation, the implementation should restart from the latest confirmed state.

## Responsibility

`implementation-salvage-threshold` owns the salvage-versus-reimplementation decision and the promotion of useful discoveries from outdated implementation into the appropriate authoritative sources before work continues.

## Adjacent responsibilities

Replanning procedures belong to the planning skill used by the repository.
Implementation execution belongs to the implementation skill used by the repository.
Repository operations and review procedures belong to their respective skills.

Executable behavior and detailed operational rules remain in `SKILL.md`.
