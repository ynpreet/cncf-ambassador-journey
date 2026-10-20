# CNCF Project Contributions — Log

Every contribution gets a row here the day it happens. PR links are the proof the
Ambassador application reviewers ask for.

Bar to clear (CNCF application page): **minimum DevStats score of 20** for the
"Active Contribution to a CNCF Project" category. Docs PRs in a project repo count
toward DevStats the same as code PRs. No public per-event point formula exists —
the play is steady merged PRs across projects, not a fixed count.

Mechanics: OpenTelemetry projects use a **CLA** (Linux Foundation EasyCLA);
Prometheus, Thanos, Jaeger use **DCO** sign-off (`git commit -s`). AI-assisted work
is accepted when the human contributor understands and owns it; Prometheus asks
for an `Assisted-by:` commit trailer — we follow that everywhere.

## Targets (picked Oct 20, 2026 — issues verified open on CLotributor/GitHub)

| # | Project | Issue | Type | Status |
|---|---------|-------|------|--------|
| 1 | OpenTelemetry Python Contrib | [#4202 Document OTEL_SEMCONV_STABILITY_OPT_IN](https://github.com/open-telemetry/opentelemetry-python-contrib/issues/4202) | docs (Python) | skipped — already fixed by open PR #5067 |
| 2 | OpenTelemetry Python Contrib | [#2642](https://github.com/open-telemetry/opentelemetry-python-contrib/issues/2642) | docs (Python) | skipped — already fixed by open PR #5013 |
| 3 | OpenTelemetry Python Contrib | [#2556](https://github.com/open-telemetry/opentelemetry-python-contrib/issues/2556) | docs (Python) | skipped — already fixed by open PR #4862 |
| 4 | OpenTelemetry Python | [#1059 Add support for OTEL_LOG_LEVEL env variable](https://github.com/open-telemetry/opentelemetry-python/issues/1059) | code (Python) | picked |
| 5 | OpenTelemetry Python | [#1559](https://github.com/open-telemetry/opentelemetry-python/issues/1559) | code (Python) | picked |
| 6 | Kepler | [#2604](https://github.com/sustainable-computing-io/kepler/issues/2604) | docs | skipped — already fixed by open PR #2614 |
| 7 | Kepler | [#2601](https://github.com/sustainable-computing-io/kepler/issues/2601) | docs | skipped — already fixed by open PR #2610 |
| 8 | Kepler | [#2429](https://github.com/sustainable-computing-io/kepler/issues/2429) | docs | skipped — assigned, and open PR #2503 implements it |
| 9 | Prometheus (docs) | [#3066](https://github.com/prometheus/docs/issues/3066) | docs | skipped — already fixed by open PR #3089 |
| 10 | Prometheus (docs) | [#2014](https://github.com/prometheus/docs/issues/2014) | docs | skipped — claimed by other contributors in-thread (Aug 2025, Feb 2026); re-verified Oct 20 |
| 11 | OpenTelemetry docs site | [#11927](https://github.com/open-telemetry/opentelemetry.io/issues/11927) | docs | skipped — fix needs LFX platform access/automation, not a docs-only change; re-verified Oct 20 |
| 12 | OpenTelemetry docs site | [#9427](https://github.com/open-telemetry/opentelemetry.io/issues/9427) | docs | skipped — Portuguese localization tracker, not a fit; re-verified Oct 20 |
| 13 | OpenTelemetry docs site | [#9046](https://github.com/open-telemetry/opentelemetry.io/issues/9046) | docs/localisation | picked |
| 14 | Inspektor Gadget | [#5634](https://github.com/inspektor-gadget/inspektor-gadget/issues/5634) | docs guide | PR open — https://github.com/inspektor-gadget/inspektor-gadget/pull/5897 — DCO check PASSING (replaced #5895, now closed; commits re-signed as Preet Mehta <preetmehta1995@gmail.com> Oct 20) |
| 15 | Thanos | [#8794](https://github.com/thanos-io/thanos/issues/8794) | docs/code | scoped Oct 20: Go feature (native --rule-file auto-reload) — larger build, queued |
| 16 | Thanos | [#8506](https://github.com/thanos-io/thanos/issues/8506) | docs/code | picked |
| 17 | Cortex | [#7064](https://github.com/cortexproject/cortex/issues/7064) | docs/code | scoped Oct 20: Go feature (AutoMemLimit, mirrors Prometheus) — larger build, queued |
| 18 | Jaeger | [#9717](https://github.com/jaegertracing/jaeger/issues/9717) | code (4 small PRs) | picked |
| 19 | Jaeger | [#9474 Elasticsearch/OpenSearch schema](https://github.com/jaegertracing/jaeger/issues/9474) | code — data skills | picked |
| 20 | Perses | [#4034](https://github.com/perses/perses/issues/4034) | docs/code | picked |
| 21 | OTel Collector Contrib | [#51845 Kafka receiver/exporter](https://github.com/open-telemetry/opentelemetry-collector-contrib/issues/51845) | code — data pipelines | picked |
| 22 | Fluentd | [#3501](https://github.com/fluent/fluentd/issues/3501) | docs-first | picked |

Projects covered: OpenTelemetry (Python, Python Contrib, docs site, Collector Contrib),
Kepler, Prometheus, Inspektor Gadget, Thanos, Cortex, Jaeger, Perses, Fluentd — **10 projects**.

| 25 | OpenTelemetry Python Contrib | [#1641 confluent-kafka semantic conventions](https://github.com/open-telemetry/opentelemetry-python-contrib/issues/1641) | code (Python) | PREPARED Oct 20, 2026 — verified: open, unassigned, 0 PRs ever. Implementation complete locally: branch confluent-kafka-semconv-1641, commit f2eb2614, 4 files +439/-14, 12 new tests (28 passed with core main; caveat: pinned uv.lock core lacks V1_44_0 — upstream's own tests fail the same way, flagged in PR draft). Gap analysis + PR draft in ~/workspace/eb1a-open-source/otel-1641-confluent-kafka/. NOT submitted — needs Preet's explicit go + his EasyCLA signing. Also logged as EB-1A Lane 2 in ~/workspace/eb1a-evidence/contributions/open-source-contributions-log.md |
| 26 | OpenTelemetry Python Contrib | [#1640 celery semantic conventions](https://github.com/open-telemetry/opentelemetry-python-contrib/issues/1640) | code (Python) | backup — verified Oct 20, 2026: open, unassigned, 0 open PRs |
| 27 | OpenTelemetry Python | [#1559 IPv6 Jaeger exporter](https://github.com/open-telemetry/opentelemetry-python/issues/1559) | code (Python) | backup — verified Oct 20, 2026: open, unassigned, 0 PRs ever |

Status key: `picked` → `in progress` → `PR open` → `merged`
| 23 | Inspektor Gadget | [#5631 trace_lsm Guide](https://github.com/inspektor-gadget/inspektor-gadget/issues/5631) | docs guide | PR open — https://github.com/inspektor-gadget/inspektor-gadget/pull/5898 — DCO check PASSING (replaced #5896, now closed; commits re-signed as Preet Mehta <preetmehta1995@gmail.com> Oct 20) |
| 24 | Inspektor Gadget | [#5632 trace_malloc Guide](https://github.com/inspektor-gadget/inspektor-gadget/issues/5632) | docs guide | skipped — already fixed by open PR #5858 |
