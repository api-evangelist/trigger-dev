---
title: "We ditched worktrees for Claude Code. Here's what we use instead"
url: "https://trigger.dev/blog/parallel-agents-gitbutler"
date: "2026-04-16"
author: "Eric Allam"
feed_url: "https://trigger.dev/blog/rss.xml"
---
Git worktrees solve code isolation but create infrastructure nightmares. We teach Claude Code to use GitButler's CLI directly, splitting one session's work across multiple branches without duplicating databases, Redis, or dev servers.
