# PR Guardrail Studio

A single-file, local-only web app inspired by the trend "Copilot edited an ad into my PR".

## What it does

PR Guardrail Studio simulates how AI-assisted code changes can accidentally (or adversarially) introduce promotional content, stealth links, hidden reviewer instructions, telemetry expansion, or suspicious dependency additions.

You can:
- Load scenarios (PR diff, README, telemetry expansion, dependency bait)
- Tune behavior knobs (alignment, promotion bias, strictness, hallucination) + threat model
- Toggle detectors and see an explainable risk score
- Generate a guardrail patch template and a sanitized preview
- Export a session JSON and create a shareable URL hash

## Run it

Open `index.html` in your browser.

## Notes

This is a simulation and not a real security scanner. Use it as a conversation starter for guardrails, review checklists, and policy.
