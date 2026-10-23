---
title: "Making Semgrep rip: How Ripgrep inspired us to shave hours off (some) scans"
url: "https://semgrep.dev/blog/2026/making-semgrep-rip-how-ripgrep-inspired-us-to-shave-hours-off-some-scans"
date: "2026-06-10"
feed_url: "https://semgrep.dev/blog/rss/"
---
Semgrep 1.162.0 fixes a file targeting bottleneck that caused scans on large repos to take hours. By replacing expensive regex calls with string comparisons and a constant-time hash table lookup, P99 diff scan times dropped from ~60 minutes to under 12, with one customer repo improving from 7.5 hours to under 2 minutes.
