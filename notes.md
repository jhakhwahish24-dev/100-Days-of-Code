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

## Day 05: Asyncio Task Management & Retries
**Date:** August 18, 2026 (2026-08-18T14:23:10+05:30)

- Built bounded asynchronous task runner using `asyncio.Queue`.
- Integrated jittered exponential backoff for handling upstream rate limits (HTTP 429).
- Added graceful shutdown handlers for cancellation signals.

---

## Day 06: MongoDB Indexing & Query Profiling
**Date:** August 19, 2026 (2026-08-19T15:02:13+05:30)

- Profiled slow queries using `explain('executionStats')`.
- Replaced full collection scans with a compound index on `(github_username, github_repo)`.
- Reduced execution time from 140ms to 2ms on lookups.

---

## Day 07: REST API Error Handling & Standards
**Date:** August 20, 2026 (2026-08-20T16:19:27+05:30)

- Standardized error response structure according to RFC 7807 (Problem Details).
- Added middleware validation for Bearer token presence and format.
- Prevented unhandled 500 exceptions on malformed requests.

---

## Day 08: Trees & Graph Traversal
**Date:** August 21, 2026 (2026-08-21T14:25:31+05:30)

- Implemented in-order, pre-order, and post-order depth-first traversals.
- Created helper function to check if a binary search tree satisfies AVL balance criteria.
- Analyzed recursion stack space complexity.

---

## Day 09: CLI UX & Argument Parsing
**Date:** August 22, 2026 (2026-08-22T17:51:06+05:30)

- Refactored argument parser with subcommands and mutually exclusive flags.
- Added rich help formatting and default fallback environment variables.
- Verified input sanitization for repository paths.

---

## Day 10: Caching Strategies & Invalidation
**Date:** August 23, 2026 (2026-08-23T14:23:28+05:30)

- Designed thread-safe LRU cache using `collections.OrderedDict`.
- Added TTL expiration timestamp checks on cache hits.
- Benchmarked cache hit ratio under synthetic high-concurrency workloads.

---

