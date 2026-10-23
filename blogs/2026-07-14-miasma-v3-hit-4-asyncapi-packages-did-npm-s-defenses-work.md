---
title: "Miasma v3 Hit 4 AsyncAPI Packages — Did NPM's Defenses Work, or Just Get Dodged?"
url: "https://semgrep.dev/blog/2026/miasma-v3-asyncapi-npm-hardening"
date: "2026-07-14"
feed_url: "https://semgrep.dev/blog/rss/"
---
On 14 July 2026, malicious versions of three AsyncAPI packages were published to npm: @asyncapi/generator@3.3.1, @asyncapi/generator-helpers@1.1.1, and @asyncapi/generator-components@0.7.1 after an attacker gained push access to the repository's next branch and triggered the project's own CI/CD release pipeline. The malicious packages carry valid npm OIDC provenance attestations and execute a multi-stage downloader when the library is loaded via require().
