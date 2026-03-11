# Render Blueprint path test (fork)

Fork of [aculich/render-blueprint-test](https://github.com/aculich/render-blueprint-test). Tests whether the **Deploy to Render** button prefills **Blueprint Path** (or finds `render.yaml`) when deploying from a **real fork**.

- Single file: `render.yaml` at repo root (one static site).
- Public repo. **Deploy button below points at this fork.**

## Deploy

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/aculich-forks/render-blueprint-test-actual-fork/tree/main)

When the Blueprint form loads, check **Blueprint Path**. If Render says "render.yaml not found", that suggests forking is the trigger. If it is empty or a placeholder, type `render.yaml` and continue.
