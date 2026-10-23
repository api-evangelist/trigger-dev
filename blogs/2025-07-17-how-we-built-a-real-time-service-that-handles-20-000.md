---
title: "How we built a real-time service that handles 20,000 updates per second"
url: "https://trigger.dev/blog/how-we-built-realtime"
date: "2025-07-17"
author: "Matt Aitken"
feed_url: "https://trigger.dev/blog/rss.xml"
---
We process 20,000 run updates per second and 500GB of data daily using Postgres replication slots and ElectricSQL. Here's why we chose this over WebSockets and how we solved the hard problems of authentication, rate limiting, and caching.
