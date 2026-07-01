# Day 10 Reliability Final Report

## Metrics Summary

| Metric | Value |
|---|---:|
| total_requests | 300 |
| availability | 0.9933 |
| error_rate | 0.0067 |
| latency_p50_ms | 274.28 |
| latency_p95_ms | 318.15 |
| latency_p99_ms | 319.41 |
| fallback_success_rate | 0.9733 |
| cache_hit_rate | 0.64 |
| circuit_open_count | 8 |
| recovery_time_ms | 2234.518527984619 |
| estimated_cost | 0.045204 |
| estimated_cost_saved | 0.192 |

## Chaos Scenarios

| Scenario | Status |
|---|---|
| primary_timeout_100 | pass |
| primary_flaky_50 | pass |
| all_healthy | pass |

## Analysis TODO(student)

Explain what failed, why the fallback path worked or did not work, and what you would change before production.