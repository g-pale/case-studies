# n8n AI News Pipeline (TechRadar RSS → LLM → Telegram)

## Goal
Automate AI news delivery: fetch → translate → summarize → publish.

## What it does
- Pulls AI-related articles from **TechRadar official RSS feeds** on schedule
- Translates to Russian + produces a short summary via LLM
- Publishes to Telegram channel: https://t.me/TechnoRadarAI

## Reliability note
Self-hosted n8n on a RU-based server. To avoid delivery failures to Telegram node due to network restrictions, implemented proxy + reverse-proxy setup.

## Stack
n8n (self-hosted), Docker/Linux, proxy/reverse proxy, LLM APIs.

## Evidence
Workflow is private (personal). Can share architecture screenshots and node-by-node overview upon request.
