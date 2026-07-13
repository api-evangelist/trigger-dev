---
title: "Runs list and logs degraded"
url: "https://trigger.dev/blog/incident-report-jun-30-2026"
date: "2026-06-30"
author: "Eric Allam, CTO at Trigger.dev"
feed_url: "https://trigger.dev/blog"
---
On June 30, 2026, Trigger.dev experienced a roughly 6.5-hour outage affecting the dashboard runs list and logs visibility. The root cause traced back to a ClickHouse database upgrade on June 17 combined with a June 29 configuration change that removed protective safeguards. Task execution itself remained unaffected; only visibility and debugging surfaces were degraded.
