---
title: "Vercel environment variables cleared during synchronization"
url: "https://trigger.dev/blog/incident-report-oct-6-2026"
date: "2026-10-07"
author: "Daniel Sutton"
feed_url: "https://trigger.dev/blog/rss.xml"
---
On October 6, 2026, a change we enabled caused our Vercel integration to overwrite some environment variable values with empty strings. Tasks that needed those values started failing.
