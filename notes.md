# 100 Days of Code — Engineering Journal

A log of daily algorithms, architecture concepts, code refactoring, and engineering notes.

---

## Day 01: Sliding Window & Two Pointers
**Date:** August 14, 2026 (2026-08-14T12:23:46+05:30)

- Explored variable vs. fixed window sizes.
- Implemented `max_sub_array_len` with O(n) time and O(1) space complexity.
- Solved edge cases around empty arrays and all-negative inputs.

---

## Day 02: Python Memory Optimization with __slots__
**Date:** August 15, 2026 (2026-08-15T13:37:34+05:30)

- Replaced standard dict-backed attributes with `__slots__` for high-volume objects.
- Observed ~35% memory footprint reduction during benchmark runs.
- Documented immutability tradeoffs and inheritance behavior.

---

## Day 03: System Architecture & Separation of Concerns
**Date:** August 16, 2026 (2026-08-16T11:11:00+05:30)

- Outlined domain entities, use-case interactors, and external interfaces.
- Added mermaid sequence diagram for the client synchronization pipeline.
- Defined boundary contracts between API controllers and DB models.

---

## Day 04: Unit Testing & Boundary Analysis with Pytest
**Date:** August 17, 2026 (2026-08-17T17:36:03+05:30)

- Created test fixtures covering leap years, DST shifts, and timezone offsets.
- Verified ISO 8601 formatting and UTC normalization for GitHub heatmap alignment.
- Achieved 98% branch coverage on the date transformation module.

---

