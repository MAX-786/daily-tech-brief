# 🗞️ Daily Tech Brief

A curated daily technology briefing for Mohammad K. Hussain.

Each brief is auto-generated at **8:00 AM IST** by an AI agent that scans tech feeds across security, AI/LLMs, JavaScript/React, dev tools, and industry news — and distills the signal from the noise.

## Structure

```
briefs/           — one markdown file per day (YYYY-MM-DD.md)
index.json        — machine-readable index of all briefs (date, title)
```

## Web App

The briefs are rendered at: [daily-tech-brief-app on Vercel](#)

## Pipeline

Powered by [Hermes Agent](https://hermes-agent.nousresearch.com) via a scheduled cron job
that fetches RSS feeds, curates with an LLM, and pushes to this repo daily.
