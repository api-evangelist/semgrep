---
title: "Rust crates arrayref & append-only-vec compromised via malicious proc-macro1 dependency"
url: "https://semgrep.dev/blog/2026/rust-crates-arrayref-append-only-vec-compromised-proc-macro1"
date: "2026-08-20"
feed_url: "https://semgrep.dev/blog/rss/"
---
Rust crates arrayref (244M downloads) and append-only-vec (4M downloads) were compromised with one added dependency line pointing to proc-macro1, a typosquat of proc-macro2. The malicious code sits in build.rs, which Cargo runs at build time, merely compiling a dependent project downloads and executes a detached payload. A second lookalike, proc-macro-en, published under "daveroundy" impersonating maintainer "droundy," suggests the campaign was still expanding.
