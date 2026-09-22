# Automated Email & Executive Briefing System

An AI system that reads a CEO's inbox and tells him what actually 
matters — not a summary of everything.

## Why I built this
I saw a job post from a CEO who wanted exactly this. So I built it 
myself first.

## What it does
Checks Gmail every 2 hours. AI decides what's important and what's not — 
a decision needed, a customer issue, a deadline change. Every morning 
at 7am it sends one clean briefing: what changed, what's falling 
behind, what needs a decision.

Built with n8n, Groq AI, and Airtable. Working end to end right now.

## Demo
[Watch a walkthrough](https://www.loom.com/share/a5b56bf28d3e487b8510a96837b56930)

## Stack
- n8n (workflow orchestration)
- Groq AI (email analysis and prioritization)
- Airtable (data storage)
- Gmail (source inbox)

## Status
Still adding urgent alerts and links back to original emails.

## Files
- `ai-executive-briefing.json` — main workflow

## Screenshots
![Workflow diagram](workflow-screenshot.png)

## Note
API keys and credentials have been removed from this export. To run 
this yourself, you'll need your own Groq API key and Gmail/Airtable 
credentials set up in n8n.
