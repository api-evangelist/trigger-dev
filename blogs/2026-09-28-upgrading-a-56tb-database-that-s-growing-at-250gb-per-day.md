---
title: "Upgrading a 56TB database that's growing at 250GB per day with (nearly) no downtime"
url: "https://trigger.dev/blog/upgrading-a-56tb-database"
date: "2026-09-28"
author: "Daniel Sutton"
feed_url: "https://trigger.dev/blog/rss.xml"
---
We had to upgrade our 56TB Aurora Postgres cluster by 31 July without taking Trigger.dev down. Instead of moving the database, we made the problem smaller: new runs and the control plane went to PlanetScale, and the old runs stayed behind.
