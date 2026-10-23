---
title: "Why we replaced Node.js with Bun for 5x throughput"
url: "https://trigger.dev/blog/firebun"
date: "2026-03-27"
author: "Nick"
feed_url: "https://trigger.dev/blog/rss.xml"
---
How we took our warm start service from 2,099 req/s on Node + SQLite to 10,700 req/s on a compiled Bun binary, and found a subtle memory leak that only exists in Bun's HTTP model.
