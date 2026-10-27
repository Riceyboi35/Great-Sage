# TradieFlow AI

A mobile app that helps small tradies run and grow their business, with AI
features built in.

## Stack
- **Builder:** FlutterFlow (free plan now, upgrading to Basic soon).
- **Backend:** Supabase.
- **Platforms:** Android, Apple App Store, plus TradieFlow web pages.
- Moved from Bubble after repeated problems with Add Lead form dropdowns.

## Status
- First working feature: **Save Lead** saves to Supabase and returns to the dashboard.
- Add Lead form fields: customer, contact, address, job description, lead source,
  priority, status.

## Planned features (Tradie AI dashboard blueprint)
- AI reception on/off toggle
- Missed-call text-back (Twilio)
- AI quote drafting
- Supply alerts for upcoming jobs
- Automatic quote follow-up after 4 days
- Simple invoice / mark-job-paid
- Maybe later: a human-sounding AI voice agent that takes job details, gives a
  rough quote and books a callback (still deciding)

## How it gets built
- A TradieFlow agent inside Great Sage (Claude Code) builds in FlutterFlow via
  FlutterFlow's official CLI/MCP once on the Basic plan.
- Dan reviews and learns each step.
- The agent keeps a record of what it did, and sends scheduled lesson-style
  summaries for him to approve or reject.
- Make it work first; polish the UI for tradies later.

## Launch plan
- Trial first with Dan's own trade: cabinet makers, joiners, 2pac sprayers.
- Then other trades. Dan will do outreach himself (visits, emails, ads).
