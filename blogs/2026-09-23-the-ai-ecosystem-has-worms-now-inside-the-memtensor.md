---
title: "The AI Ecosystem Has Worms Now: Inside the MemTensor Compromise"
url: "https://semgrep.dev/blog/2026/the-ai-ecosystem-has-worms-now-inside-the-memtensor-compromise"
date: "2026-09-23"
feed_url: "https://semgrep.dev/blog/rss/"
---
On September 23, 2026, an attacker published credential-stealing builds of MemTensor's MemOS packages to npm and PyPI. Neither build runs on install, instead both wire the payload into code paths that run anyway, and on the Python side that means the moment your code imports the library. The first thing it finds?
