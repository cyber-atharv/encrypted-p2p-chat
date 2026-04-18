# Changelog

All notable changes to encrypted-p2p-chat are documented here.

### [2025-12-25]
- perf: optimize memory allocation in buffer pool

### [2025-12-30]
- fix: handle nil pointer dereference on unexpected connection close

### [2026-01-18]
- fix: handle nil pointer dereference on unexpected connection close

### [2026-01-21]
- docs: update license headers and author metadata

### [2026-01-31]
- feat: improve error logging with contextual debug traces

### [2026-02-07]
- fix: handle nil pointer dereference on unexpected connection close

### [2026-03-13]
- chore: update internal constants and clean up legacy comments

### [2026-03-19]
- fix: prevent duplicate event emission during rapid retry bursts

### [2026-03-22]
- style: clean up trailing whitespace and fix alignment

### [2026-04-01]
- perf: parallelize independent batch verification tasks

### [2026-04-18]
- fix: prevent duplicate event emission during rapid retry bursts

### [2026-05-01]
- perf: optimize memory allocation in buffer pool

### [2026-05-18]
- perf: minimize redundant heap allocations in hot loop

### [2026-05-18]
- test: implement mock service for end-to-end integration tests

### [2026-06-09]
- fix: resolve memory leak in idle connection reaper

### [2026-06-19]
- fix: correct endianness conversion in raw packet parser

### [2026-06-28]
- docs: add example configuration commands to quickstart guide

### [2026-07-03]
- security: sanitize input strings to mitigate format string risks

### [2026-07-04]
- feat: add graceful shutdown signal handler (SIGINT/SIGTERM)

### [2026-07-17]
- refactor: use enum types for status codes instead of magic numbers

### [2026-07-17]
- perf: replace linear search with hash map lookup for fast querying

### [2026-08-31]
- security: enforce strict bounds checking on dynamic byte slices

