---
layout: post
---
For the 2022 edition of Google Summer of Code, I worked on adding a [Prometheus](https://prometheus.io) REST endpoint to Jitsi Videobridge, a component of the [Jitsi project](https://jitsi.org). The project idea was originally proposed by members of the Jitsi team. If you weren't linked to this page from the GSoC project page, I wrote [a short summary in the Jitsi community forums](https://community.jitsi.org/t/gsoc-jvb-prometheus-stats/114718).

## Jitsi Videobridge

### Pull Requests
#### Closed
- [Add metric wrappers and MetricsContainer for Prometheus endpoint.](https://github.com/jitsi/jitsi-videobridge/pull/1915)
- [ref: Port both failed conferences stats to Metrics.](https://github.com/jitsi/jitsi-videobridge/pull/1930)
- [Port totalConferencesCompleted stat to Metric.](https://github.com/jitsi/jitsi-videobridge/pull/1931)
- [ref: Port ICE stats to Metrics.](https://github.com/jitsi/jitsi-videobridge/pull/1932)
- [Port some more metrics to MetricsContainer.](https://github.com/jitsi/jitsi-videobridge/pull/1934)
- [Port additional metrics to MetricsContainer.](https://github.com/jitsi/jitsi-videobridge/pull/1935)
- [Move some keyframe metrics to MetricsContainer.](https://github.com/jitsi/jitsi-videobridge/pull/1936)
- [Port some packet stats to MetricsContainer.](https://github.com/jitsi/jitsi-videobridge/pull/1941)
- [Move a few metrics to MetricsContainer.](https://github.com/jitsi/jitsi-videobridge/pull/1942)
- [Port a few more stats to MetricsContainer.](https://github.com/jitsi/jitsi-videobridge/pull/1944)

#### Extra
- [Add checkstyle rules to match guidelines for opening braces.](https://github.com/jitsi/jitsi-videobridge/pull/1920)

## Jicoco (Jitsi COmmon COmponents)

### Pull Requests
#### Closed
- [Rework metrics system for Prometheus (moved from jvb).](https://github.com/jitsi/jicoco/pull/173)
- [Add Prometheus REST endpoint (moved from JVB).](https://github.com/jitsi/jicoco/pull/175)
- [feat: Add resetAll() to MetricsContainer for testing.](https://github.com/jitsi/jicoco/pull/176)

#### Open
- [Append missing _total suffix when registering Counter metrics.](https://github.com/jitsi/jicoco/pull/177)
  - Last commit during work period: [Add check for base metric name when registering a counter.](https://github.com/jitsi/jicoco/pull/177/commits/883a4f6cd44d66d4d0980137d6fc33b074425791)
- [Add OpenMetrics units to metrics.](https://github.com/jitsi/jicoco/pull/178)
  - Last commit during work period: [Add OpenMetrics units to metrics.](https://github.com/jitsi/jicoco/pull/178/commits/63d1e84b55bcd499c41ff86c9abf5036fbbc7962)
