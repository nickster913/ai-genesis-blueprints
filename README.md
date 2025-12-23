# AI Genesis Blueprints

A curated library of **production-minded blueprints, templates, and modules** for building and operating AI-driven software systems end-to-end.

This repo is not a “cool AI demos” scrapbook. It’s a **reference arsenal** for shipping real systems: reliable, observable, maintainable, and aligned to business outcomes.

## What this repo is

- **Blueprints**: end-to-end reference architectures (problem → stack → deployment → ops)
- **Templates**: reusable project starters (API services, workers, UIs, infra)
- **Modules**: composable building blocks (auth, retries, tracing, RAG, connectors)
- **Stacks**: known-good combinations you can reach for repeatedly
- **Cookbooks**: short playbooks and operational guides
- **Examples**: minimal runnable demos for specific patterns
- **Playgrounds**: experiments and spikes (kept separate on purpose)

## Why it exists

Most “AI app” repos stop at *it runs on my laptop*.  
This one cares about the things that actually matter when users show up:

- failure modes (timeouts, bad inputs, rate limits, partial outages)
- observability (logs, traces, metrics, cost visibility)
- reproducibility (evals, regression tests, prompts/models tracked)
- deployment reality (environments, secrets, migrations)
- business outcomes (time saved, revenue lift, risk reduction)

## Repository structure

```text
blueprints/   End-to-end reference architectures
templates/    Project starters (service/worker/UI/infra)
modules/      Composable building blocks
stacks/       Known-good combinations of the above
cookbooks/    Copy/paste playbooks (shipping, ops, evals)
examples/     Minimal runnable examples
playgrounds/  Experiments and spikes
docs/         Philosophy, standards, decision notes, diagrams
scripts/      Repo utilities (scaffolding, checks, etc.)
.github/      GitHub templates and CI
