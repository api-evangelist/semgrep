---
title: "How We Cut Semgrep’s Taint Analysis Time by 75%"
url: "https://semgrep.dev/blog/2026/how-we-cut-semgreps-taint-analysis-time-by-75-percent"
date: "2026-06-05"
feed_url: "https://semgrep.dev/blog/rss/"
---
Semgrep Pro Engine 1.158.0 ships a redesigned taint analysis engine delivering up to 75% faster full scans. By rearchitecting how taint analysis runs across files, P95 scan times dropped from 10 minutes to 7:30, P99 became significantly more consistent, and some large repos saw 3x+ improvements.
