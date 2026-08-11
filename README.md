# Lamek Tsegay

Building multi-agent systems — and the tooling to see what they're actually doing.

Currently at [fetch.ai](https://fetch.ai), San Francisco. Most of my work lives at the
seam between agents that talk to each other and the observability that makes those
conversations debuggable.

---

### What I'm working on

| Project | |
|---|---|
| **[uagents-trace](https://github.com/lamek-tsegay/uagents-trace)** | Drop-in, read-only observability for [uAgents](https://github.com/fetchai/uAgents). Records a span for every send and receive to local SQLite, then draws the message flow live in your terminal — so you can see what got delivered, what timed out, and what got dropped. |
| **[launchpad](https://github.com/lamek-tsegay/launchpad)** | A ~33-agent system that turns a one-line business idea into a starter kit: brand, site copy, market scan, compliance checklist. Built specifically to stress-test `uagents-trace` under real fan-out. |
| **[patch](https://github.com/lamek-tsegay/patch)** | An autonomous security agent that scans a codebase, classifies vulnerabilities, proposes ranked fixes, and commits approved ones. Every action is governed by a YAML policy, with a full audit trail. |
| **[aeroshift](https://github.com/lamek-tsegay/aeroshift)** | Unsupervised detection of behavioral shifts in aircraft arrival trajectories — clustering flight paths to catch when the pattern quietly changes. |
| **[prism](https://github.com/lamek-tsegay/prism)** | Your face, your sound. Real-time webcam emotion detection mapped to generated chord progressions. React + face-api.js on the front, C# on the back. |
| **[taskr-depsched](https://github.com/lamek-tsegay/taskr-depsched)** | A dependency-aware task runner in the spirit of make and Bazel. Models tasks as a DAG, tracks completion state, and supports incremental rebuilds via invalidation. |

Lower-level things I keep going back to: a
[hash-table database in C](https://github.com/lamek-tsegay/bizdb), an
[expression engine](https://github.com/lamek-tsegay/expr-engine), and
[list operations in RISC-V assembly](https://github.com/lamek-tsegay/riscv-listops).

---

### By the numbers

<p align="left">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=lamek-tsegay&hide_border=true&theme=github-dark-blue">
    <img src="https://streak-stats.demolab.com?user=lamek-tsegay&hide_border=true&theme=default" alt="Total contributions and commit streak for lamek-tsegay" height="170">
  </picture>
</p>

<!--
  WANT THE ALL-TIME COMMIT COUNT CARD TOO?

  The public github-readme-stats instance is currently paused (returns 503), so its
  card would show as a broken image. Deploy your own copy — it takes about 5 minutes,
  never rate-limits, and unlike the shared instance it can count your PRIVATE commits:

    1. Fork https://github.com/anuraghazra/github-readme-stats
    2. Import the fork at https://vercel.com/new
    3. Add env var PAT_1 = a GitHub token with the `repo` scope
    4. Uncomment the block below, replacing YOUR-APP with your Vercel subdomain

<p align="left">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://YOUR-APP.vercel.app/api?username=lamek-tsegay&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=github_dark">
    <img src="https://YOUR-APP.vercel.app/api?username=lamek-tsegay&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=default" alt="Total commits, stars, pull requests and issues for lamek-tsegay" height="170">
  </picture>
</p>
-->


---

### Reach me

[GitHub](https://github.com/lamek-tsegay) · [Email](mailto:lamektsegaya@gmail.com)
